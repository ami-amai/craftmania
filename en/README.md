# CRAFTMANIA

# Rules Core

* Ruleset builder

## [RU](/ru/README.md) | [**EN**](/en/README.md)

* A turn-based game for 2 to 4 players where the goal is to remove your opponent from the board using every game mechanic available

## Contents

* Introduction
* Terms
    * HP
    * Action
* Actions

## Introduction

* The game is played on a board up to 8x8 in size
* Players take turns, and each turn they have a certain number of Actions
* A player loses if they have no HP left on the board
* The game ends when only one player remains

## Terms

### HP (Health Block)

* Placed on the board
* Can contain an item
* Gains 1 Action
* Must be present on the board for the game to continue

### Action

* An available activity during a turn
* Actions:
    * Movement - changing the position of items in the game
    * Looting - obtaining items
    * Attack - any action or condition that destroys HP on the board
    * Crafting - creating items from ingredients
    * Destruction - removing an item for a reward and by spending an action
    * Removal - removing an item without a reward and without spending an action

### Ruleset

* A list of rules that includes:
    * Item set
    * Mechanics set
    * Recipes
    <details>

    <summary> List of Rulesets </summary>

    * [Default](/en/rulesets/DEFAULT.md)

    </details>

### Inventory

* The in-game inventory is visible to every player
* Holds up to 9 items

## Actions

* Movement - changing the position of items in the game:
    * Board <-> Inventory
    * Board <-> Board
    * Inventory <-> Inventory, usually does not cost an action

* Gathering - obtaining items into the inventory or onto an empty HP
    * Gathering parameters
        * conditions
    * Also possible when the required ingredients for a Recipe are missing

* Crafting - creating items from ingredients
    * Crafting parameters
        * required items
        * ingredients
        * placement
    * Produces the created item while removing the ingredients used

* Attack - any action or condition linked to the destruction of HP in a certain area for some cost
    * Attack parameters
        * Cost
        * Area
        * Number of blocks destroyed

* Destruction - removing an item for a reward
    * Destruction parameters
        * item
        * reward
    * Removal - a subtype of Destruction, without a reward and without spending an action
