---
title: Inn System
order: 4
link: inns
---

The inn system allows you to establish an inn on the server for your clan, which will allow players who check in there
to teleport to your inn for Bronze Coins!

- To establish an inn, you first need to build an inn at your base or an outpost. Currently, there is no "verification"
  that your inn is suitable, it's on the honor system that you will build something RP appropriate resembling an inn.
  Please do not establish inns in dungeons or places where you have not built an inn. You don't need to have a specific
  number of rooms or beds for now, the system will not have any information about the physical inn structure.

- You must place a carpet that indicates exactly where players will need to stand to check in at your inn. Make sure
  your inn teleport location is not locked inside a closed door, your guest will be stuck if it is! Once you're ready,
  stand on that marker and wait ~60 seconds, then use the command `v/establishinn “Inn Name”`. The bot will respond with
  your inn details. You can verify that the location is correct using SHIFT+ALT+L in game to see your current
  coordinates. There is no cost to establishing an inn. If you need to move it, you can use `v/closeinn` to start over.

- Once you have established an inn, it will be open for others to "check in" there. To check in at an inn, stand on the
  designated check-in spot and wait ~60 seconds, then use the command `v/checkin`. You can only be checked in at one inn
  at a time and you cannot check in at an inn owned by your own clan. It costs 10 Bronze Coins to check in at an inn,
  which is a fee paid to the bot (it disappears), but check-ins are now permanent. You can check in to as many inns as
  you like. Use `v/inninfo` to see your checkins and how to teleport to them.

- Once you've checked in at an inn, you can use the command `v/inn` at any time to teleport to the inn. This will cost 2
  Bronze Coins, deducted directly from your V-bank account. Each time you teleport to the inn, the proprietor will
  receive 1 Bronze Coin (paid directly to their account).

- You can display information about your current check-ins and your clan's inn by using the command `v/inninfo`. This
  will tell you where you are currently checked in, the cost to teleport there, the name and location of your clan's
  inn, and the number of checked-in guests.