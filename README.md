# brujam.github.io

Site to showcase my personal repositories.

Projects I've got;
* https://github.com/brujam/personal-game-wiki
  * Designed as a goal-discovery, -setting and -tracking tool.
  * View the tool here: https://brujam.github.io/personal-game-wiki/ - presently just an NEDB database inserter + insert-statement dumper.
  
Projects I want to make;

* Minecraft Skyblock Simulator
  * Mimicking the "accumulative game" style skyblocks like Garden of Glass etc, but with a Cookie-clicker like interface.
  * Gameplay loop; you start with X resources, you have the ability to queue up to 60 actions, done once per second.
  * Actions:
    * Build thing (cobble gen, items, tools...)
    * Break block with tool
    * Verb thing (sift blocks, smelt ore, break trees with crook + axe...)
  * You have a 10x10 platform of stone (can make infrastructure there), 10x10 of dirt (used for growing crops / trees).
  * From there you develop little bits of infrastructure, can spend 100 cobblestone for another platform and build another bit of infrastructure.
  * Each bit of infrastructure you build costs N, and returns M/sec resources. Simulate power use, simulate inventory + stock...
  * Use "Personal Game Wiki" goal setting, inventory tracking and resolution finding.
  * Maybe make this configurable with NEDB so that people can "build your own skyblock" + simulate tiering etc.
  * Record a log of what you do so that you can then use that to generate goals and methods to use *in the skyblock itself*.

* Brave Exvius Warehouse
  * Like Swarfarm (https://www.swarfarm.com/) for Final Fantasy Brave Exvius.
  * Manually enter your stocks and inventories etc.
    * Persistent "savegame" in cookies / HTML5 storage / etc.
  * Export JSON / NEDB to pastebin and send to others, import from pastebin / clipboard and load.
  * Develop a base database with characters, levels, sources etc.
  * Track capabilities (recipes, levels in Coliseum, etc).
  * Damage simulator based on your stats. Give min + max for against a given DEF/SPR level.
  * Wishlists.
    * Suggest "next steps" - complete quests for recipes, or get magic keys and get this thing, or...
  * Offer a system for people to contribute data points ("here are 5* Kefka's stats at level 67...")

Things I've contributed to:
* https://github.com/lucymhdavies/Lucy-as-a-Service
  * Mainly just adding quotes :)
