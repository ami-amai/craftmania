# MAIN RULESET

## [RU](/ru/rulesets/DEFAULT.md) | [**EN**](/en/rulesets/DEFAULT.md)

<details>
  <summary>
    <b> Main Set </b>
  </summary>

## Main Set

**Item Set**

* Resources
  * Oak Log ![Oak Log](/img/blocks/x16/oak_log.png)
  * Stone ![Stone](/img/blocks/x16/stone.png)
  * Beef ![Beef](/img/items/x16/beef.png)
  * Arrow ![Arrow](/img/items/x16/arrow.png)
  * Wooden Hoe ![Wooden Hoe](/img/items/x16/wooden_hoe.png)
* Functional Items
  * Crafting Table ![Crafting Table](/img/blocks/x16/crafting_table_side.png)
  * Barrel ![Barrel](/img/blocks/x16/barrel_side.png)
  * Furnace ![Furnace](/img/blocks/x16/furnace_front.png)
* Tools
  * Wooden Sword ![Wooden Sword](/img/items/x16/wooden_sword.png)
  * Wooden Axe ![Wooden Axe](/img/items/x16/wooden_axe.png)
  * Wooden Pickaxe ![Wooden Pickaxe](/img/items/x16/wooden_pickaxe.png)
  * Shield ![Shield](/img/items/x16/shield_front.png)
* Weapons
  * Wooden Sword ![Wooden Sword](/img/items/x16/wooden_sword.png)
  * Wooden Axe ![Wooden Axe](/img/items/x16/wooden_axe.png)
  * Bow ![Bow](/img/items/x16/bow.png)
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
* Place size:
  * 4x4 for 2 players
  * 6x6 for 3 players
  * 8x8 for 4 players
* Action limit of 3

**Actions**

* **Craft** - performed with resources and required items on the place
  * Resources must touch each other, including diagonally

* **Attack** - can be performed together with the Move of the attacking item on the place
  * requires a certain amount of HP in the inventory and removes it before the Attack

* **Destroy** - destroying any item except Food gives 1 HP
  * One HP from Destroy can be placed immediately

**Items**

* **Resources** - items consumed for certain actions

* **Functional Item** - items that expand gameplay options
  * Crafting Table ![Crafting Table](/img/blocks/x16/crafting_table_side.png) - gives advanced Crafts while it is on the place
  * Furnace ![Furnace](/img/blocks/x16/furnace_front.png) - gives advanced Crafts while it is on the place
  * Barrel ![Barrel](/img/blocks/x16/barrel_side.png) - gives 2 inventory slots while it is on the place
    * When the slot count is reduced, the inventory owner may choose which items remain

* **Tools** - items that simplify the game
  * Wooden Sword ![Wooden Sword](/img/items/x16/wooden_sword.png) - allows Looting Beef
  * Wooden Axe ![Wooden Axe](/img/items/x16/wooden_axe.png) - reduces the amount of Oak Log required in Crafts by 1
  * Wooden Pickaxe ![Wooden Pickaxe](/img/items/x16/wooden_pickaxe.png) - allows Looting Stone
  * Shield ![Shield](/img/items/x16/shield_front.png) - absorbs one Attack, taking the damage itself
    * Triggers if it can be destroyed during the current Attack
    * When triggered, it is deleted together with its HP, canceling the Attack action
    * Only one can be owned per player

* **Weapons** - items that have the Attack action and their own Attack parameters
  * Wooden Sword ![Wooden Sword](/img/items/x16/wooden_sword.png)
    * Area 3x3 around the sword at the final point of the Move
    * Attack types:
      * Primary
        * Cost **5**
        * Destroys 2 HP
      * Secondary
        * Cost **3**
        * Destroys 1 HP

  * Wooden Axe ![Wooden Axe](/img/items/x16/wooden_axe.png)
    * Area 3x3 around the sword at the final point of the Move
    * Attack types:
      * Primary
        * Cost **6**
        * Destroys 8 HP

  * Bow ![Bow](/img/items/x16/bow.png)
    * Area unlimited
    * Attack types:
      * Primary
        * Cost **4**
        * Destroys an amount of HP equal to its Arrows on the place during the Attack
        * Requires Arrows on the place, which are deleted after the Attack

* **Food** - gives more HP on Destroy than other items
  * Beef ![Beef](/img/items/x16/beef.png) - **2**
  * Steak ![Steak](/img/items/x16/cooked_beef.png) - **5**
  * Bread ![Bread](/img/items/x16/bread.png) - **3**

**Mechanics**

* **One Weapon** - only one type of Weapon can be on the place
  * When another type of Weapon appears on the place, the previous type must be deleted
  * Move "Place <-> Inventory" between two Weapon types deletes the Weapon that was moved from the place to the inventory

* **Looting Items** - after an Attack, the attacker can Loot any items from destroyed HP into its inventory
  * Items not Looted will be deleted

---

**Crafts**

Requirements | Resources | Result
-|-|-
[]()| ![Oak Log](/img/blocks/x32/oak_log.png) | ![Crafting Table](/img/blocks/x32/crafting_table_front.png)
![Crafting Table](/img/blocks/x32/crafting_table_front.png)| ![Oak Log](/img/blocks/x32/oak_log.png) | ![Crafting Table](/img/blocks/x32/crafting_table_front.png) OR ![Wooden Pickaxe](/img/items/x32/wooden_pickaxe.png) OR ![Wooden Hoe](/img/items/x32/wooden_hoe.png) OR ![Arrow](/img/items/x32/arrow.png)
![Crafting Table](/img/blocks/x32/crafting_table_front.png)| ![Oak Log](/img/blocks/x32/oak_log.png) ![Oak Log](/img/blocks/x32/oak_log.png) | ![Barrel](/img/blocks/x32/barrel_side.png) OR ![Wooden Sword](/img/items/x32/wooden_sword.png) OR ![Wooden Axe](/img/items/x32/wooden_axe.png) OR ![Bow](/img/items/x32/bow.png)
![Crafting Table](/img/blocks/x32/crafting_table_front.png)| ![Wooden Hoe](/img/items/x32/wooden_hoe.png) | ![Bread](/img/items/x32/bread.png)
![Crafting Table](/img/blocks/x32/crafting_table_front.png)| ![Stone](/img/blocks/x32/stone.png) | ![Furnace](/img/blocks/x32/furnace_front.png)
![Furnace](/img/blocks/x32/furnace_front.png)| ![Oak Log](/img/blocks/x32/oak_log.png) ![Stone](/img/blocks/x32/stone.png) | ![Shield](/img/items/x32/shield_front.png)
![Furnace](/img/blocks/x32/furnace_front.png)| ![Oak Log](/img/blocks/x32/oak_log.png) ![Beef](/img/items/x32/beef.png) | ![Steak](/img/items/x32/cooked_beef.png)
</details>
