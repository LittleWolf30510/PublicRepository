Public Repository
================

SQDuties - A system that utilizes SQL Connection Pooling/Async execution to allow staff members on the server to play as regular players with a regular non-staff permissions set, but if needed, the staff member can go into "Duty Mode" and recieve a new perms set and creative mode. The database stores the players inventory and location and will return them to survival mode and restore their inventory/location when they no longer need to be in duty mode. This plugin works across bungeecord servers. This project utilizes the following:
  - CardboardBox
  - Serialization
  - SQL Database
  - Blob Storage
  - Async write/read from DB
  - Bungee plugin messaging channel
  - Vault API

CardboardBox - A Bukkit library to serialize inventories and meta data. This library can package a player's inventory into a "Crate" which can be packagaged as an array of bytes and can be read in and out of a SQL database. This project utlizes the following:
  - Serialization
  - Inventory manipulation
  - Inheritance
