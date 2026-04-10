# MAIN RULESET CANDIDATE

## [RU](/ru/rulesets/DEFAULT_CANDIDATE.md) | [**EN**](/en/rulesets/DEFAULT_CANDIDATE.md)

<details>
  <summary>
    <b> Main Set </b>
  </summary>

## Main Set

**Item Set**

* Resources
  * Oak Log ![Oak Log](/img/blocks/x16/oak_log.png)
  * Stone ![Stone](/img/blocks/x16/stone.png)
* Resources with Attributes
  * Beef ![Beef](/img/items/x16/beef.png)
  * Wheat ![Wheat](/img/items/x16/wheat.png)
  * Arrow ![Arrow](/img/items/x16/arrow.png)
* Functional Items
  * Crafting Table ![Crafting Table](/img/blocks/x16/crafting_table_side.png)
  * Barrel ![Barrel](/img/blocks/x16/barrel_side.png)
  * Chest ![Chest](/img/blocks/x16/chest_front.png)
  * Furnace ![Furnace](/img/blocks/x16/furnace_front.png)
* Tools
  * Wooden Hoe ![Wooden Hoe](/img/items/x16/wooden_hoe.png)
  * Wooden Sword ![Wooden Sword](/img/items/x16/wooden_sword.png)
  * Wooden Axe ![Wooden Axe](/img/items/x16/wooden_axe.png)
  * Wooden Pickaxe ![Wooden Pickaxe](/img/items/x16/wooden_pickaxe.png)
  * Shield ![Shield](/img/items/x16/shield_front.png)
* Weapons
  * Wooden Sword ![Wooden Sword](/img/items/x16/wooden_sword.png)
  * Wooden Axe ![Wooden Axe](/img/items/x16/wooden_axe.png)
  * Bow ![Bow](/img/items/x16/bow.png)
  * Crossbow ![Crossbow](/img/items/x16/crossbow_standby.png)
* Food
  * Beef ![Beef](/img/items/x16/beef.png)
  * Steak ![Steak](/img/items/x16/cooked_beef.png)
  * Bread ![Bread](/img/items/x16/bread.png)

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

* **Attack** - is a Move of a Weapon that destroys blocks in the area tied to the Weapon
  * requires spending items from the inventory

* **Destroy** - destroying any item except Food gives 1 HP
  * One HP from Destroy can be placed immediately

**Items**

* **Resources** - items consumed for certain actions
  * Arrow ![Arrow](/img/items/x16/arrow.png) - consumed when attacking with ranged Weapons

* **Resources with Attributes** - resources whose presence in the inventory at the end of the turn gives bonuses at the start of the next turn
  * Attributes - bonuses to existing parameters
    * ![Healing](/img/items/x16/lime_dye.png) Healing ![Beef](/img/items/x16/beef.png) (Amount of HP gained from Destroy)
    * ![Action](/img/items/x16/light_blue_dye.png) Action ![Wheat](/img/items/x16/wheat.png) (Additional Action that ignores the current limit)
    * ![Damage](/img/items/x16/red_dye.png) Damage ![Arrow](/img/items/x16/arrow.png) (Number of destroyed blocks)
  * No more than 3 Attributes at once

* **Functional Item** - items that expand gameplay options
  * Crafting Table ![Crafting Table](/img/blocks/x16/crafting_table_side.png) - gives advanced Crafts while it is on the place
  * Furnace ![Furnace](/img/blocks/x16/furnace_front.png) - gives advanced Crafts while it is on the place
  * Barrel ![Barrel](/img/blocks/x16/barrel_side.png) - gives 1 inventory slot while it is on the place
    * When the slot count is reduced, the inventory owner may choose which items remain
  * Chest ![Chest](/img/blocks/x16/chest_front.png) - gives 3 inventory slots while it is on the place
    * When the slot count is reduced, the inventory owner may choose which items remain

* **Tools** - items that simplify the game
  * Wooden Sword ![Wooden Sword](/img/items/x16/wooden_sword.png) - allows Looting Beef ![Beef](/img/items/x16/beef.png)
  * Wooden Axe ![Wooden Axe](/img/items/x16/wooden_axe.png) - allows Looting an additional Oak Log ![Oak Log](/img/blocks/x16/oak_log.png)
  * Wooden Pickaxe ![Wooden Pickaxe](/img/items/x16/wooden_pickaxe.png) - allows Looting Stone ![Stone](/img/blocks/x16/stone.png)
  * Wooden Hoe ![Wooden Hoe](/img/items/x16/wooden_hoe.png) - allows Looting Wheat ![Wheat](/img/items/x16/wheat.png)
  * Shield ![Shield](/img/items/x16/shield_front.png) - absorbs one Attack, taking the damage itself
    * Triggers if it can be destroyed during the current Attack
    * When triggered, it is deleted together with its HP, canceling the Attack action
    * Only one can be owned per player

* **Weapons** - items that have the Attack action and their own Attack parameters
  * Wooden Sword ![Wooden Sword](/img/items/x16/wooden_sword.png)
    * Primary Attack
      * Area 3x3 around
      * Cost 1 Bread ![Bread](/img/items/x16/bread.png)
      * Destroys 1 HP
    * Critical Attack
      * Area 3x3 around
      * Cost Steak ![Steak](/img/items/x16/cooked_beef.png)
      * Destroys 4 HP

  * Wooden Axe ![Wooden Axe](/img/items/x16/wooden_axe.png)
    * Primary Attack
      * Area 3x3 around
      * Cost 2 Bread ![Bread](/img/items/x16/bread.png) ![Bread](/img/items/x16/bread.png)
      * Destroys 1 HP
    * Critical Attack
      * Area 3x3 around
      * Cost Steak ![Steak](/img/items/x16/cooked_beef.png)
      * Destroys 8 HP

  * Bow ![Bow](/img/items/x16/bow.png)
    * Primary Attack
      * Unlimited area
      * Cost Bread ![Bread](/img/items/x16/bread.png) for each Arrow ![Arrow](/img/items/x16/arrow.png), and the Arrows ![Arrow](/img/items/x16/arrow.png) themselves
      * Destroys an amount of HP equal to the number of spent Arrows ![Arrow](/img/items/x16/arrow.png)

  * Crossbow ![Crossbow](/img/items/x16/crossbow_standby.png)
    * Primary Attack
      * Unlimited area
      * Cost Steak ![Steak](/img/items/x16/cooked_beef.png) and Arrow ![Arrow](/img/items/x16/arrow.png)
      * Destroys a line of HP in any direction from the Crossbow (45 degrees) ![Crossbow](/img/items/x16/crossbow_standby.png)

* **Food** - gives more HP on Destroy than other items
  * Beef ![Beef](/img/items/x16/beef.png) - **2 HP**
  * Steak ![Steak](/img/items/x16/cooked_beef.png) - **5 + 3 Health**
  * Bread ![Bread](/img/items/x16/bread.png) - **3 HP + 1 Health**

**Mechanics**

* **One Weapon** - only one type of Weapon can be on the place
  * When another type of Weapon appears on the place, the previous type must be deleted
  * Move "Place <-> Inventory" between two Weapon types deletes the Weapon that was moved from the place to the inventory

* **Item Drops** - after HP is destroyed, the item inside remains in the same cell on the place
  * The item can be Looted by placing HP on it

* **Health** - a reserve of HP that can be gained during the game
  * Can be partially restored by Food
  * If it runs out, the player can no longer gain new HP

---

**Crafts**

Requirements | Resources | Result
-|-|-
[]()| ![Oak Log](/img/blocks/x32/oak_log.png) | ![Crafting Table](/img/blocks/x32/crafting_table_front.png)
![Crafting Table](/img/blocks/x32/crafting_table_front.png)| ![Oak Log](/img/blocks/x32/oak_log.png) | ![Barrel](/img/blocks/x32/barrel_side.png) OR ![Wooden Pickaxe](/img/items/x32/wooden_pickaxe.png) OR ![Wooden Hoe](/img/items/x32/wooden_hoe.png) OR ![Arrow](/img/items/x32/arrow.png)
![Crafting Table](/img/blocks/x32/crafting_table_front.png)| ![Oak Log](/img/blocks/x32/oak_log.png) ![Oak Log](/img/blocks/x32/oak_log.png) | ![Chest](/img/blocks/x32/chest_front.png) OR ![Wooden Sword](/img/items/x32/wooden_sword.png) OR ![Wooden Axe](/img/items/x32/wooden_axe.png) OR ![Bow](/img/items/x32/bow.png) OR ![Crossbow](/img/items/x32/crossbow_standby.png)
![Crafting Table](/img/blocks/x32/crafting_table_front.png)| ![Wooden Sword](/img/items/x32/wooden_sword.png) | ![Wooden Axe](/img/items/x32/wooden_axe.png) OR ![Bow](/img/items/x32/bow.png) OR ![Crossbow](/img/items/x32/crossbow_standby.png)
![Crafting Table](/img/blocks/x32/crafting_table_front.png)| ![Wooden Axe](/img/items/x32/wooden_axe.png) | ![Wooden Sword](/img/items/x32/wooden_sword.png) OR ![Bow](/img/items/x32/bow.png) OR ![Crossbow](/img/items/x32/crossbow_standby.png)
![Crafting Table](/img/blocks/x32/crafting_table_front.png)| ![Bow](/img/items/x32/bow.png) | ![Wooden Sword](/img/items/x32/wooden_sword.png) OR ![Wooden Axe](/img/items/x32/wooden_axe.png) OR ![Crossbow](/img/items/x32/crossbow_standby.png)
![Crafting Table](/img/blocks/x32/crafting_table_front.png)| ![Crossbow](/img/items/x32/crossbow_standby.png) | ![Wooden Sword](/img/items/x32/wooden_sword.png) OR ![Wooden Axe](/img/items/x32/wooden_axe.png) OR ![Bow](/img/items/x32/bow.png)
![Crafting Table](/img/blocks/x32/crafting_table_front.png)| ![Wheat](/img/items/x32/wheat.png) | ![Bread](/img/items/x32/bread.png)
![Crafting Table](/img/blocks/x32/crafting_table_front.png)| ![Stone](/img/blocks/x32/stone.png) | ![Furnace](/img/blocks/x32/furnace_front.png)
![Furnace](/img/blocks/x32/furnace_front.png)| ![Oak Log](/img/blocks/x32/oak_log.png) ![Stone](/img/blocks/x32/stone.png) | ![Shield](/img/items/x32/shield_front.png)
![Furnace](/img/blocks/x32/furnace_front.png)| ![Oak Log](/img/blocks/x32/oak_log.png) ![Beef](/img/items/x32/beef.png) | ![Steak](/img/items/x32/cooked_beef.png)
</details>
