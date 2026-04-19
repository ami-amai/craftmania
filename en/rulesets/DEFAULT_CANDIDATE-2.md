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
    * Raw Cod ![Raw Cod](/img/items/x16/cod.png)
    * Cooked Cod ![Cooked Cod](/img/items/x16/cooked_cod.png)
  * Meat
    * Raw Beef ![Raw Beef](/img/items/x16/beef.png)
    * Steak ![Steak](/img/items/x16/cooked_beef.png)

---

**Mechanics Set**

**Starting Conditions**

* 3 inventory slots
* 3 actions on the first turn
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

* **Attack** - is a Move of a Weapon that destroys blocks in the area tied to the Weapon's Attack
  * requires spending items from the inventory

* **Destroy** - destroying any item except Food gives 1 HP
  * 1 HP from Destroy can be placed immediately

**Items**

* **Resources** - items consumed for certain actions
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

* **Functional Item** - items that expand gameplay options while they are on the place
  * Craft Extenders - access to new Crafts
    * Crafting Table ![Crafting Table](/img/blocks/x16/crafting_table_side.png)
    * Furnace ![Furnace](/img/blocks/x16/furnace_front.png)
  * Storage - increase the number of inventory slots
    * Barrel ![Barrel](/img/blocks/x16/barrel_side.png) - 1 slot
    * Chest ![Chest](/img/blocks/x16/chest_front.png) - 2 slots

* **Tools** - give bonuses while they are on the place
  * Passive
    * Loot specific items
      * Wooden Sword ![Wooden Sword](/img/items/x16/wooden_sword.png) - Raw Beef ![Raw Beef](/img/items/x16/beef.png)
      * Wooden Axe ![Wooden Axe](/img/items/x16/wooden_axe.png) - reduces the consumed Oak Log ![Oak Log](/img/blocks/x16/oak_log.png) by 1
      * Wooden Hoe ![Wooden Hoe](/img/items/x16/wooden_hoe.png) - Wheat ![Wheat](/img/items/x16/wheat.png)
      * Wooden Pickaxe ![Wooden Pickaxe](/img/items/x16/wooden_pickaxe.png) - Stone ![Stone](/img/blocks/x16/stone.png)
      * Fishing Rod ![Fishing Rod](/img/items/x16/fishing_rod.png) - Raw Cod ![Raw Cod](/img/items/x16/cod.png)
    * Increase the received passive bonuses
      * Stick ![Stick](/img/items/x16/stick.png) - an additional Natural resource
  * Active
    * Shield ![Shield](/img/items/x16/shield_front.png) - absorbs damage
      * Triggers if it can be destroyed during someone else's Attack
      * Is destroyed
        * Together with the HP it is on
        * Deletes all other Shields ![Shield](/img/items/x16/shield_front.png) of the player on the place
      * Reduces the opponent's available HP for destruction by 1
      * The bonus stacks from all triggered Shields ![Shield](/img/items/x16/shield_front.png)

* **Weapons** - items that have the Attack action and their own attack parameters
  * Each weapon has 3 attack types:
    * Basic Attack - a simple attack, identical for all
    * Primary Attack - a unique weapon attack
  
  * Basic Attack
    * Area 3x3 around
    * Destroys 1 HP
    * Consumes
        * 3 Sweet Berries ![Sweet Berries](/img/items/x16/sweet_berries.png) ![Sweet Berries](/img/items/x16/sweet_berries.png) ![Sweet Berries](/img/items/x16/sweet_berries.png)
    
  * Wooden Sword ![Wooden Sword](/img/items/x16/wooden_sword.png)
    * Primary Attack
      * Area 3x3 around
      * Destroys 3 HP
      * Consumes
        * Bread ![Bread](/img/items/x16/bread.png) + 2 Sweet Berries ![Sweet Berries](/img/items/x16/sweet_berries.png) ![Sweet Berries](/img/items/x16/sweet_berries.png)
        * Raw Cod ![Raw Cod](/img/items/x16/cod.png) + Sweet Berries ![Sweet Berries](/img/items/x16/sweet_berries.png)

  * Wooden Axe ![Wooden Axe](/img/items/x16/wooden_axe.png)
    * Primary Attack
      * Area 3x3 around
      * Destroys 6 HP
      * Consumes
        * Cooked Cod ![Cooked Cod](/img/items/x16/cooked_cod.png) + Sweet Berries ![Sweet Berries](/img/items/x16/sweet_berries.png)
        * Steak ![Steak](/img/items/x16/cooked_beef.png) + Sweet Berries ![Sweet Berries](/img/items/x16/sweet_berries.png)

  * Wooden Spear ![Wooden Spear](/img/items/x16/wooden_spear.png)
    * Close Primary Attack
      * Area 3x3 around
      * Destroys 1 HP
      * Consumes
        * Raw Cod ![Raw Cod](/img/items/x16/cod.png)
        * Raw Beef ![Raw Beef](/img/items/x16/beef.png)
    * Long-Range Primary Attack
      * Area 5x5 not including the 3x3 around
      * Destroys 2 HP
      * Consumes
        * 2 Raw Cod ![Raw Cod](/img/items/x16/cod.png) ![Raw Cod](/img/items/x16/cod.png)
        * 2 Raw Beef ![Raw Beef](/img/items/x16/beef.png) ![Raw Beef](/img/items/x16/beef.png)
        * Raw Beef ![Raw Beef](/img/items/x16/beef.png) + Raw Cod ![Raw Cod](/img/items/x16/cod.png)
    * Very Long-Range Primary Attack
      * Area 7x7 not including the 5x5 around
      * Destroys 4 HP
      * Consumes
        * Cooked Cod ![Cooked Cod](/img/items/x16/cooked_cod.png)
        * Steak ![Steak](/img/items/x16/cooked_beef.png)

  * Bow ![Bow](/img/items/x16/bow.png)
    * Primary Attack
      * Unlimited area
      * Destroys 1 HP for each Arrow ![Arrow](/img/items/x16/arrow.png) consumed
      * Consumes
        * All Arrows ![Arrow](/img/items/x16/arrow.png) on the place + a Sweet Berry ![Sweet Berries](/img/items/x16/sweet_berries.png) for each Arrow ![Arrow](/img/items/x16/arrow.png) + Raw Beef ![Raw Beef](/img/items/x16/beef.png)
        * All Arrows ![Arrow](/img/items/x16/arrow.png) on the place + a Sweet Berry ![Sweet Berries](/img/items/x16/sweet_berries.png) for each Arrow ![Arrow](/img/items/x16/arrow.png) + Raw Cod ![Raw Cod](/img/items/x16/cod.png)

  * Crossbow ![Crossbow](/img/items/x16/crossbow_standby.png)
    * Primary Attack
      * Unlimited area
      * Destroys 4 HP
      * Consumes
        * Arrow ![Arrow](/img/items/x16/arrow.png) on the place + a Sweet Berry ![Sweet Berries](/img/items/x16/sweet_berries.png) + Cooked Cod ![Cooked Cod](/img/items/x16/cooked_cod.png)
        * Arrow ![Arrow](/img/items/x16/arrow.png) on the place + a Sweet Berry ![Sweet Berries](/img/items/x16/sweet_berries.png) + Steak ![Steak](/img/items/x16/cooked_beef.png)

  * Shield ![Shield](/img/items/x16/shield_front.png)
    * Primary Attack
      * Area 3x3 around
      * Triggers if 2 conditions are met
        * It can be destroyed by the current Attack
        * There are enough consumables
      * Consumes
        * Bread ![Bread](/img/items/x16/bread.png) + Sweet Berries ![Sweet Berries](/img/items/x16/sweet_berries.png)
        * Raw Cod ![Raw Cod](/img/items/x16/cod.png)
        * Raw Beef ![Raw Beef](/img/items/x16/beef.png)
      * Destroys half of the HP that can be destroyed by the opponent, rounded in favor of the Shield ![Shield](/img/items/x16/shield_front.png) owner

  * Fishing Rod ![Fishing Rod](/img/items/x16/fishing_rod.png)
    * Primary Attack
      * Area 5x5 around
      * Destroys 2 HP
      * Consumes
        * Bread ![Bread](/img/items/x16/bread.png) + Sweet Berries ![Sweet Berries](/img/items/x16/sweet_berries.png)
        * Raw Beef ![Raw Beef](/img/items/x16/beef.png)
      * Loots items from destroyed HP
    
  * Stick ![Stick](/img/items/x16/stick.png)
    * Copying Attack
      * Can use any attack of another weapon, with an area no larger than 5x5 around
      * Consumes
        * Same as the original attack + Raw Cod ![Raw Cod](/img/items/x16/cod.png)
        * Same as the original attack + Raw Beef ![Raw Beef](/img/items/x16/beef.png)
        * Same as the original attack + 3 Sweet Berries ![Sweet Berries](/img/items/x16/sweet_berries.png) ![Sweet Berries](/img/items/x16/sweet_berries.png) ![Sweet Berries](/img/items/x16/sweet_berries.png)
      * Deals 2 times less, rounded in favor of the Stick ![Stick](/img/items/x16/stick.png) owner

* **Food** - gives more HP when Destroyed, and is also required for the Attack action
  * Sweet Berries ![Sweet Berries](/img/items/x16/sweet_berries.png) - 1 HP
  * Bread ![Bread](/img/items/x16/bread.png) - 2 HP
  * Fish
    * Raw Cod ![Raw Cod](/img/items/x16/cod.png) - 3 HP
    * Cooked Cod ![Cooked Cod](/img/items/x16/cooked_cod.png) - 5 HP
  * Meat
    * Raw Beef ![Raw Beef](/img/items/x16/beef.png) - 3 HP
    * Steak ![Steak](/img/items/x16/cooked_beef.png) - 5 HP

**Mechanics**

* **Initial Game Phase** - the start before the first turn
  1. **Weapon Block**
    * Each player, in reverse turn order, blocks one weapon
    * Weapon after blocking
      * Identical to the blocked item
      * Cannot be chosen as a weapon in the next stage
  2. **Weapon Selection**
    * Each player, in reverse turn order, chooses one weapon
    * Chosen weapon
      * The only weapon the choosing player can attack with
      * Cannot be chosen by other players as a weapon
  3. **Item Block**
    * Each player, in reverse turn order, blocks one item
    * Blocked item
      * Not required in Crafts
      * One-time bonuses are applied once to all players until the end of the game
      * Passive bonuses do not require the blocked item
      * Cannot be Crafted or Looted
    * Basic resources cannot be blocked

* **Item Drops** - after HP is destroyed, the item inside remains in the same cell on the place
  * The item can be Looted by placing HP on it

</details>
