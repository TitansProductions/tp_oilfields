# General Information

1. Since the system does not allow the Oil Fields to be functional without ownership, there is a way allowing you to do it, by manually by stopping the script or when the server is completely stopped by editing the database table `tp_oilfields` .

- `identifier` : Set a non-existent identifier ownership, even `steam:xxxxxxxxxxxxx` should work fine.
- `charidentifier` : Set just a charId (**DO NOT LEAVE IT AS 0**), just set any number > 0.

Then, in case you want the players to always be able to do deliveries or oil extractions by workers, you have to also edit manually the following:

- `oil_capacity` : Set this to unlimited number such as 999999999 or disable (set) the `RequiredOilDelivery` on `Config.Deliveries` to 0.
- `account` : Set this to unlimited number as mentioned above so the oil fields account ledger will never be empty.
