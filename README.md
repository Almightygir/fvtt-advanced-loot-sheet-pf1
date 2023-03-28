[![](https://img.shields.io/badge/Foundry-v0.9.0-informational)]()[![download_count](https://img.shields.io/github/downloads/Almightygir/fvtt-loot-sheet-npc-pf1/total.svg)]()[![Donate](https://img.shields.io/badge/Donate-BuyMeACoffee-green.svg)](https://ko-fi.com/almighty_gir)

# THIS MODULE IS NOW DISCONTINUED, AND IS UNSUPPORTED IN FOUNDRY V10+
As a lot of the functionality for this module has been added directly to the PF1e system, there is no further need for me to support this modules development.
Thank you for using it while it lasted!

# Loot Sheet NPC Pathfinder1
This module adds an additional NPC sheet which can be used for loot containers such as chests. It also allows spells to be automatically converted into spell scrolls by dragging them onto this sheet.

This version was forked from Sven Werlen's module (https://github.com/SvenWerlen/fvtt-loot-sheet-npc-pf1), which was a port of Jan Ole Peek's module (https://github.com/jopeek/fvtt-loot-sheet-npc-5e) to the PF1 game system.
This fork will be maintained separately and specifically for Pathfinder 1.

### Features

Allows for easy assembly of items and coins to be distributed to players.

More features detailed below.

#### Features for GM

##### Loot Sheet

* Prepare a loot by dragging items from compendiums
* Alternatively, you can convert a dead PNJ into a loot by changing the sheet to `PF1.LootSheetPF1NPC`

![Demo Loot Sheet](doc/img/add-items-loot.gif)

##### Create Spell Scrolls

* Dragging of spells into the sheet will automatically turn them into scrolls.

![Demo crate scrolls](doc/img/scroll.gif)

##### Permissions & split money

* Permissions can be set in the sheet for each player and range from no access (cannot open sheet) to observer (view sheet and contents) to owner (view sheet and add/remove items).
* Any coins in the sheet can easily be split evenly across all players with owner access. The math and distribution is done for you via a single click if you're the GM. 

![Demo Permissions & Split](doc/img/split.gif)

#### Shopkeeper Sheet

* Can be used to create an inventory of a shopkeeper to allow players to peruse their inventory. Prices are listed next to each item.
* Use rolltables to automatically fill shopkeeper inventory

![Demo merchant](doc/img/merchant.gif)

#### Feature for PC

##### Loot items and money

* A PC with owner permissions can loot money and items from the sheet

![Demo Loot items and money](doc/img/loot.gif)

##### Buy/sell items at shopkeeper

* A PC can buy items from a shopkeeper
* A PC can sell items (half-price) to a shopkeeper

![Demo Buy and Sell items](doc/img/give.gif)

##### Give items to another PC

* A PC can give an item to another PC by dragging it on the actor

![Demo Give items](doc/img/give.gif)


### Compatibility:
- Tested with FVTT v0.6.0.

### Installation Instructions
To install a module, follow these instructions:

1. Start FVTT and browse to the Game Modules tab in the Configuration and Setup menu.
2. Head to the latest release and grab the link to the latest `module.json`, the latest release can be found here: https://github.com/Almightygir/fvtt-loot-sheet-npc-pf1/releases/latest
3. Select the Install Module button and paste the link to the `module.json` file.
4. Click Install and wait for installation to complete.
5. Once installed, you can get the latest updates directly in foundry with the Update button.

### Feedback

If you have any suggestions or feedback, please contact me on Discord (Almighty_gir#6379).
