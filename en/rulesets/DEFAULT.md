# DEFAULT RULESET

## [RU](/ru/rulesets/DEFAULT.md) | [**EN**](/en/rulesets/DEFAULT.md)

<details>
  <summary>
    <b> Main Set </b>
  </summary>

## Main Set

**Item set**

* Resources
  * Wood ![Wood](/img/blocks/x16/oak_log.png)
  * Stone ![Stone](/img/blocks/x16/stone.png)
  * Beef ![Beef](/img/items/x16/beef.png)
  * Arrow ![Arrow](/img/items/x16/arrow.png)
  * Wooden Hoe ![Wooden Hoe](/img/items/x16/wooden_hoe.png)
* Utility blocks
  * Crafting Table ![Crafting Table](/img/blocks/x16/crafting_table_side.png)
  * Barrel ![Barrel](/img/blocks/x16/barrel_side.png)
  * Furnace ![Furnace](/img/blocks/x16/furnace_front.png)
* Tools
  * Wooden Sword ![Wooden Sword](/img/items/x16/wooden_sword.png)
  * Wooden Axe ![Wooden Axe](/img/items/x16/wooden_axe.png)
  * Wooden Pickaxe ![Wooden Pickaxe](/img/items/x16/wooden_pickaxe.png)
* Combat items
  * Wooden Sword ![Wooden Sword](/img/items/x16/wooden_sword.png)
  * Wooden Axe ![Wooden Axe](/img/items/x16/wooden_axe.png)
  * Bow ![Bow](/img/items/x16/bow.png)
  * Shield ![Shield](/img/items/x16/shield_front.png)
* Food
  * Beef ![Beef](/img/items/x16/beef.png)
  * Steak ![Steak](/img/items/x16/cooked_beef.png)
  * Bread ![Bread](/img/items/x16/bread.png)

---

**Mechanics set**

**Starting conditions**

* 3 inventory slots
* 3 actions on the first turn
* 3 HP in the inventory
* Board size:
  * 4x4 for 2 players
  * 6x6 for 3 players
  * 8x8 for 4 players
* Action limit of 3

**Actions**

* **Crafting** - performed on the board using ingredients and required items
  * Ingredients must touch each other (including diagonally)

* **Attack** - can be performed simultaneously with the Movement of the attacking item on the board
  * requires a certain amount of HP in the inventory, which is removed before the attack

* **Destruction** - destroying any item except Food gives 1 HP

**Items**

* **Resources** - items consumed for certain actions

* **Utility block** - blocks that expand gameplay options
  * Crafting Table ![Crafting Table](/img/blocks/x16/crafting_table_side.png) - unlocks advanced recipes while it is on the board
  * Furnace ![Furnace](/img/blocks/x16/furnace_front.png) - unlocks advanced recipes while it is on the board
  * Barrel ![Barrel](/img/blocks/x16/barrel_side.png) - provides 2 inventory slots while it is on the board
    * If the number of slots is reduced, the inventory owner may choose which items remain

* **Tools** - items that simplify gameplay
  * Wooden Sword ![Wooden Sword](/img/items/x16/wooden_sword.png) - allows taking Beef
  * Wooden Axe ![Wooden Axe](/img/items/x16/wooden_axe.png) - reduces the number of Woods required in recipes by 1
  * Wooden Pickaxe ![Wooden Pickaxe](/img/items/x16/wooden_pickaxe.png) - allows taking Stone

* **Combat items** - items that have an attack action and their own attack parameters
  * Wooden Sword ![Wooden Sword](/img/items/x16/wooden_sword.png)
    * Area 3x3 around the sword at the final movement position
    * Attack types:
      * Primary
        * Cost **5**
        * Destroys 2 HP
      * Secondary
        * Cost **3**
        * Destroys 1 HP

  * Wooden Axe ![Wooden Axe](/img/items/x16/wooden_axe.png)
    * Area 3x3 around the axe at the final movement position
    * Attack types:
      * Primary
        * Cost **6**
        * Destroys 8 HP

  * Bow ![Bow](/img/items/x16/bow.png)
    * Area unlimited
    * Attack types:
      * Primary
        * Cost **4**
        * Destroys 1 HP
        * Requires 1 Arrow on the board, removed after the attack

  * Shield ![Shield](/img/items/x16/shield_front.png)
    * Area of the opponent's attack being performed
    * Absorbs all attack damage, removed together with its own HP when triggered

* **Food** - gives more HP when destroyed than other items
  * Beef ![Beef](/img/items/x16/beef.png) - **2**
  * Steak ![Steak](/img/items/x16/cooked_beef.png) - **5**
  * Bread ![Bread](/img/items/x16/bread.png) - **3**

**Mechanics**

* **One combat item type** - at any given moment, only one type of Combat item can be owned
  * When another type is obtained, all Combat items of the previous type must be removed

* **Picking up items** - after attacking, the attacking item can take any items from destroyed HP into its inventory
  * Items not picked up will be removed

---

**Recipes**

Requirements | Ingredients | Result
-|-|-
[]()| ![Wood](/img/blocks/x32/oak_log.png) ![Wood](/img/blocks/x32/oak_log.png) | ![Crafting Table](/img/blocks/x32/crafting_table_front.png) OR ![Barrel](/img/blocks/x32/barrel_side.png)
![Crafting Table](/img/blocks/x32/crafting_table_front.png)| ![Wood](/img/blocks/x32/oak_log.png) | ![Crafting Table](/img/blocks/x32/crafting_table_front.png) OR ![Barrel](/img/blocks/x32/barrel_side.png) OR ![Wooden Sword](/img/items/x32/wooden_sword.png) OR ![Wooden Axe](/img/items/x32/wooden_axe.png) OR ![Wooden Pickaxe](/img/items/x32/wooden_pickaxe.png) OR ![Wooden Hoe](/img/items/x32/wooden_hoe.png) OR ![Bow](/img/items/x32/bow.png) OR ![Arrow](/img/items/x32/arrow.png)
![Crafting Table](/img/blocks/x32/crafting_table_front.png)| ![Wooden Hoe](/img/items/x32/wooden_hoe.png) | ![Bread](/img/items/x32/bread.png)
![Crafting Table](/img/blocks/x32/crafting_table_front.png)| ![Stone](/img/blocks/x32/stone.png) | ![Furnace](/img/blocks/x32/furnace_front.png)
![Furnace](/img/blocks/x32/furnace_front.png)| ![Wood](/img/blocks/x32/oak_log.png) ![Stone](/img/blocks/x32/stone.png) | ![Shield](/img/items/x32/shield_front.png)
![Furnace](/img/blocks/x32/furnace_front.png)| ![Wood](/img/blocks/x32/oak_log.png) ![Beef](/img/items/x32/beef.png) | ![Steak](/img/items/x32/cooked_beef.png)
