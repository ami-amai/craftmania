# MAIN RULESET

## [RU](/ru/rulesets/DEFAULT_CANDIDATE-2.md) | [**EN**](/en/rulesets/DEFAULT_CANDIDATE-2.md)

<details>

<summary> <b> Main Set </b> </summary>

## Main Set

**Item Set**

* Resources
  * Basic
    * Oak Log ![Oak Log](/img/blocks/x16/oak_log.png)
    * Sweet Berries ![Sweet Berries](/img/items/x16/sweet_berries.png)
  * Natural
    * Stone ![Stone](/img/blocks/x16/stone.png)
    * Wheat ![Wheat](/img/items/x16/wheat.png)
    * Raw Cod ![Raw Cod](/img/items/x16/cod.png)
    * Beef ![Beef](/img/items/x16/beef.png)
  * Crafted
    * Arrow ![Arrow](/img/items/x16/arrow.png)

* Functional Items
  * Craft Extenders
    * Crafting Table ![Crafting Table](/img/blocks/x16/crafting_table_side.png)
    * Furnace ![Furnace](/img/blocks/x16/furnace_front.png)
  * Storage
    * Barrel ![Barrel](/img/blocks/x16/barrel_side.png)
    * Chest ![Chest](/img/blocks/x16/chest_front.png)

* Tools
  * Gathering
    * Wooden Sword ![Wooden Sword](/img/items/x16/wooden_sword.png)
    * Wooden Axe ![Wooden Axe](/img/items/x16/wooden_axe.png)
    * Wooden Hoe ![Wooden Hoe](/img/items/x16/wooden_hoe.png)
    * Wooden Pickaxe ![Wooden Pickaxe](/img/items/x16/wooden_pickaxe.png)
    * Fishing Rod ![Fishing Rod](/img/items/x16/fishing_rod.png)
    * Stick ![Stick](/img/items/x16/stick.png)
  * Defensive
    * Shield ![Shield](/img/items/x16/shield_front.png)

* Weapons
  * Wooden Sword ![Wooden Sword](/img/items/x16/wooden_sword.png)
  * Wooden Axe ![Wooden Axe](/img/items/x16/wooden_axe.png)
  * Wooden Spear ![Wooden Spear](/img/items/x16/wooden_spear.png)
  * Bow ![Bow](/img/items/x16/bow.png)
  * Crossbow ![Crossbow](/img/items/x16/crossbow_standby.png)
  * Shield ![Shield](/img/items/x16/shield_front.png)
  * Fishing Rod ![Fishing Rod](/img/items/x16/fishing_rod.png)
  * Stick ![Stick](/img/items/x16/stick.png)

* Food
  * Sweet Berries ![Sweet Berries](/img/items/x16/sweet_berries.png)
  * Bread ![Bread](/img/items/x16/bread.png)
  * Fish
    * Raw ![Raw Cod](/img/items/x16/cod.png)
    * Cooked ![Cooked Cod](/img/items/x16/cooked_cod.png)
  * Meat
    * Raw ![Beef](/img/items/x16/beef.png)
    * Cooked ![Steak](/img/items/x16/cooked_beef.png)

---

**Mechanics Set**

**Starting Conditions**

* 3 inventory slots
* 3 Actions on the first turn
* 3 HP in the inventory
* 20 Health
* Place size:
  * 4x4 for 2 players
  * 6x6 for 3 players
  * 8x8 for 4 players
* Action limit of 3

**Actions**

* **Craft** - performed with resources and required items on the place
  * Resources must touch each other, including diagonally

* **Attack** - is a Move of a Weapon that destroys blocks in the area tied to the weapon's Attack
  * requires spending items from the inventory

* **Destroy** - destroying any item except Food gives 1 HP
  * 1 HP from Destroy can be placed immediately

**Items**

* **Resources** - items spent for certain purposes
  * Basic - Looted without any additional conditions
    * Oak Log ![Oak Log](/img/blocks/x16/oak_log.png)
    * Sweet Berries ![Sweet Berries](/img/items/x16/sweet_berries.png)
  * Natural - Looted if the acquisition conditions are met
    * Stone ![Stone](/img/blocks/x16/stone.png)
    * Wheat ![Wheat](/img/items/x16/wheat.png)
    * Raw Cod ![Raw Cod](/img/items/x16/cod.png)
    * Beef ![Beef](/img/items/x16/beef.png)
  * Crafted - Crafted
    * Arrow ![Arrow](/img/items/x16/arrow.png)

* **Functional Item** - items that expand gameplay possibilities while they are on the place
  * Craft Extenders - access to new Crafts
    * Crafting Table ![Crafting Table](/img/blocks/x16/crafting_table_side.png)
    * Furnace ![Furnace](/img/blocks/x16/furnace_front.png)
  * Storage - increase the number of Inventory slots
    * Barrel ![Barrel](/img/blocks/x16/barrel_side.png) - 1 slot
    * Chest ![Chest](/img/blocks/x16/chest_front.png) - 2 slots

* **Tools** - give bonuses while they are on the place
  * Passive
    * Loot specific items
      * Wooden Sword ![Wooden Sword](/img/items/x16/wooden_sword.png) - Beef ![Beef](/img/items/x16/beef.png)
      * Wooden Axe ![Wooden Axe](/img/items/x16/wooden_axe.png) - reduces consumed Oak Log ![Oak Log](/img/blocks/x16/oak_log.png) by 1
      * Wooden Hoe ![Wooden Hoe](/img/items/x16/wooden_hoe.png) - Wheat ![Wheat](/img/items/x16/wheat.png)
      * Wooden Pickaxe ![Wooden Pickaxe](/img/items/x16/wooden_pickaxe.png) - Stone ![Stone](/img/blocks/x16/stone.png)
      * Fishing Rod ![Fishing Rod](/img/items/x16/fishing_rod.png) - Raw Cod ![Raw Cod](/img/items/x16/cod.png)
    * Increase received passive bonuses
      * Stick ![Stick](/img/items/x16/stick.png) - an additional Natural resource
  * Active
    * Shield ![Shield](/img/items/x16/shield_front.png) - absorbs damage
      * Triggers if it can be destroyed during an opponent's Attack
      * Is destroyed
        * Together with the HP it is on
        * Deletes all other Shield ![Shield](/img/items/x16/shield_front.png) of the player on the place
      * Reduces by 1 the HP available for destruction by the opponent
      * The bonus stacks from all triggered Shield ![Shield](/img/items/x16/shield_front.png)

* **Weapons** - items that have the Attack action and their own Attack parameters
  * Each weapon has 3 attack types:
    * Basic Attack - a simple attack, identical for all
    * Main Attack - the weapon's unique attack

  * Basic Attack
    * Area 3x3 around
    * Destroys 1 HP
    * Spends
      * 3 Sweet Berries ![Sweet Berries](/img/items/x16/sweet_berries.png) ![Sweet Berries](/img/items/x16/sweet_berries.png) ![Sweet Berries](/img/items/x16/sweet_berries.png)

  * Wooden Sword ![Wooden Sword](/img/items/x16/wooden_sword.png)
    * Main Attack
      * Area 3x3 around
      * Destroys 3 HP
      * Spends
        * 2 Raw Cod ![Raw Cod](/img/items/x16/cod.png) ![Raw Cod](/img/items/x16/cod.png)
        * 2 Bread ![Bread](/img/items/x16/bread.png) ![Bread](/img/items/x16/bread.png) + Sweet Berries ![Sweet Berries](/img/items/x16/sweet_berries.png)

  * Wooden Axe ![Wooden Axe](/img/items/x16/wooden_axe.png)
    * Main Attack
      * Area 3x3 around
      * Destroys 6 HP
      * Spends
        * 2 Cooked Cod ![Cooked Cod](/img/items/x16/cooked_cod.png) ![Cooked Cod](/img/items/x16/cooked_cod.png) + Sweet Berries ![Sweet Berries](/img/items/x16/sweet_berries.png)
        * 2 Steak ![Steak](/img/items/x16/cooked_beef.png) ![Steak](/img/items/x16/cooked_beef.png) + Sweet Berries ![Sweet Berries](/img/items/x16/sweet_berries.png)
        * Cooked Cod ![Cooked Cod](/img/items/x16/cooked_cod.png) + Steak ![Steak](/img/items/x16/cooked_beef.png) + Sweet Berries ![Sweet Berries](/img/items/x16/sweet_berries.png)

  * Wooden Spear ![Wooden Spear](/img/items/x16/wooden_spear.png)
    * Main Close Attack
      * Area 3x3 around
      * Destroys 1 HP + 1 HP for each Move of Wooden Spear ![Wooden Spear](/img/items/x16/wooden_spear.png), including the Attack, during the turn
      * Can be used without moving Wooden Spear ![Wooden Spear](/img/items/x16/wooden_spear.png)
      * Spends
        * 2 Raw Cod ![Raw Cod](/img/items/x16/cod.png) ![Raw Cod](/img/items/x16/cod.png)
        * 2 Beef ![Beef](/img/items/x16/beef.png) ![Beef](/img/items/x16/beef.png)
        * 2 Bread ![Bread](/img/items/x16/bread.png) ![Bread](/img/items/x16/bread.png) + Sweet Berries ![Sweet Berries](/img/items/x16/sweet_berries.png)
    * Main Ranged Attack
      * Area 5x5 excluding the 3x3 around
      * Destroys 1 HP + 1 HP for each Move of Wooden Spear ![Wooden Spear](/img/items/x16/wooden_spear.png), including the Attack, during the turn
      * Spends
        * Cooked Cod ![Cooked Cod](/img/items/x16/cooked_cod.png) + Sweet Berries ![Sweet Berries](/img/items/x16/sweet_berries.png)
        * Steak ![Steak](/img/items/x16/cooked_beef.png) + Sweet Berries ![Sweet Berries](/img/items/x16/sweet_berries.png)
    * Stored damage resets after the Attack

  * Bow ![Bow](/img/items/x16/bow.png)
    * Main Attack
      * Unlimited area
      * Destroys 1 HP for each spent Arrow ![Arrow](/img/items/x16/arrow.png)
      * Spends
        * All Arrows ![Arrow](/img/items/x16/arrow.png) from the place + Sweet Berries ![Sweet Berries](/img/items/x16/sweet_berries.png)

  * Crossbow ![Crossbow](/img/items/x16/crossbow_standby.png)
    * Main Attack
      * Unlimited area
      * Destroys 1 HP for each Sweet Berries ![Sweet Berries](/img/items/x16/sweet_berries.png) spent during the Attack
      * Spends
        * Arrow ![Arrow](/img/items/x16/arrow.png) from the place + Raw Cod ![Raw Cod](/img/items/x16/cod.png) + Sweet Berries ![Sweet Berries](/img/items/x16/sweet_berries.png) for each unit of Attack length
        * Arrow ![Arrow](/img/items/x16/arrow.png) from the place + Beef ![Beef](/img/items/x16/beef.png) + Sweet Berries ![Sweet Berries](/img/items/x16/sweet_berries.png) for each unit of Attack length
      * Destroys one of 8 directions, starting from the Crossbow ![Crossbow](/img/items/x16/crossbow_standby.png), with line length determined by the amount

  * Shield ![Shield](/img/items/x16/shield_front.png)
    * Main Attack
      * Area 3x3 around
      * Triggers if 2 conditions are met
        * It can be destroyed by the current Attack
        * There are enough spent items
      * Spends
        * 2 Raw Cod ![Raw Cod](/img/items/x16/cod.png) ![Raw Cod](/img/items/x16/cod.png)
        * 2 Beef ![Beef](/img/items/x16/beef.png) ![Beef](/img/items/x16/beef.png)
      * Destroys half of the opponent-destroyed HP, rounded in favor of the Shield ![Shield](/img/items/x16/shield_front.png) owner

  * Fishing Rod ![Fishing Rod](/img/items/x16/fishing_rod.png)
    * Main Attack
      * Area 5x5 around
      * Destroys 3 HP
      * Spends
        * 2 Raw Cod ![Raw Cod](/img/items/x16/cod.png) ![Raw Cod](/img/items/x16/cod.png)
        * 2 Bread ![Bread](/img/items/x16/bread.png) ![Bread](/img/items/x16/bread.png) + Sweet Berries ![Sweet Berries](/img/items/x16/sweet_berries.png)
      * Loots items from destroyed HP

  * Stick ![Stick](/img/items/x16/stick.png)
    * Copying Attack
      * Can use any Attack of another weapon, with area no larger than 3x3 around
      * Spends
        * The original Attack cost
      * Can destroy no more than 4 HP

* **Food** - gives increased HP on Destroy, and is also required for the Attack action
  * Sweet Berries ![Sweet Berries](/img/items/x16/sweet_berries.png) - 1 Health
  * Bread ![Bread](/img/items/x16/bread.png) - 2 HP
  * Fish
    * Raw ![Raw Cod](/img/items/x16/cod.png) - 3 HP
    * Cooked ![Cooked Cod](/img/items/x16/cooked_cod.png) - 5 HP
  * Meat
    * Raw ![Beef](/img/items/x16/beef.png) - 3 HP
    * Cooked ![Steak](/img/items/x16/cooked_beef.png) - 5 HP

**Mechanics**

* **Starting Phase** - the beginning before the first turn
  1. **Weapon Ban**
    * Each player, in reverse turn order, bans one weapon
    * A weapon after being banned
      * Is identical to the banned item
      * Cannot be chosen as a weapon in the next stage
  2. **Weapon Choice**
    * Each player, in reverse turn order, chooses one weapon
    * The chosen weapon
      * Is the only weapon with which the choosing player can Attack
      * Cannot be chosen by other players as a weapon
  3. **Item Ban**
    * Each player, in reverse turn order, bans one item
    * A banned item
      * Is not required in Crafts
      * One-time bonuses are applied once to all players until the end of the game
      * Passive bonuses do not require the banned item
      * Cannot be Crafted or Looted
      * Food is no longer required for Attack
        * For example, if an Attack requires Bread ![Bread](/img/items/x16/bread.png) or Beef ![Beef](/img/items/x16/beef.png), then after banning one option, the second option is used for the Attack, and only if all resource variants are banned does the Attack require no resources
    * Basic resources cannot be banned

* **Item Drops** - after HP is destroyed, the item inside remains in the same cell on the place
  * The item can be Looted by placing HP on it

* **Health** - a reserve of HP that can be gained during the game
  * If it runs out, the player can no longer gain new HP

---

**Crafts**

**Functional Blocks**
Requirements | Resources | Result
-|-|-
[]()| ![Oak Log](/img/blocks/x32/oak_log.png) | ![Crafting Table](/img/blocks/x32/crafting_table_front.png)
![Crafting Table](/img/blocks/x32/crafting_table_front.png)| ![Oak Log](/img/blocks/x32/oak_log.png) | ![Barrel](/img/blocks/x32/barrel_side.png)
![Crafting Table](/img/blocks/x32/crafting_table_front.png)| ![Oak Log](/img/blocks/x32/oak_log.png) ![Oak Log](/img/blocks/x32/oak_log.png) | ![Chest](/img/blocks/x32/chest_front.png)
![Crafting Table](/img/blocks/x32/crafting_table_front.png)| ![Stone](/img/blocks/x32/stone.png) | ![Furnace](/img/blocks/x32/furnace_front.png)

**Tools and Weapons**

Requirements | Resources | Result
-|-|-
![Crafting Table](/img/blocks/x32/crafting_table_front.png) | ![Oak Log](/img/blocks/x32/oak_log.png) | ![Wooden Pickaxe](/img/items/x32/wooden_pickaxe.png) OR ![Wooden Hoe](/img/items/x32/wooden_hoe.png) OR ![Arrow](/img/items/x32/arrow.png)
![Crafting Table](/img/blocks/x32/crafting_table_front.png) | ![Oak Log](/img/blocks/x32/oak_log.png) ![Oak Log](/img/blocks/x32/oak_log.png) | ![Wooden Sword](/img/items/x32/wooden_sword.png) OR ![Wooden Axe](/img/items/x32/wooden_axe.png) OR ![Bow](/img/items/x32/bow.png) OR ![Crossbow](/img/items/x32/crossbow_standby.png) OR ![Wooden Spear](/img/items/x32/wooden_spear.png) OR ![Fishing Rod](/img/items/x32/fishing_rod.png) OR ![Stick](/img/items/x32/stick.png) OR ![Shield](/img/items/x32/shield_front.png)

**Food**

Requirements | Resources | Result
-|-|-
![Crafting Table](/img/blocks/x32/crafting_table_front.png)| ![Wheat](/img/items/x32/wheat.png) | ![Bread](/img/items/x32/bread.png)
![Furnace](/img/blocks/x32/furnace_front.png)| ![Oak Log](/img/blocks/x32/oak_log.png) ![Raw Cod](/img/items/x32/cod.png) | ![Cooked Cod](/img/items/x32/cooked_cod.png)
![Furnace](/img/blocks/x32/furnace_front.png)| ![Oak Log](/img/blocks/x32/oak_log.png) ![Beef](/img/items/x32/beef.png) | ![Steak](/img/items/x32/cooked_beef.png)
</details>
