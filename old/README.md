# CRAFTMANIA

# Rules Core

* Ruleset builder

## [RU](/ru/README.md) | [**EN**](/en/README.md)

* A turn-based game for 2 to 4 players where the goal is to remove your opponent from the place using every game mechanic available

## Contents

* [Introduction](#introduction)
* [Rulesets](#rulesets)
* [Terms](#terms)
* [Actions](#actions)

## Introduction

* The game is played on a place up to 8x8 in size
* Players take turns, and each turn they have a certain number of Actions
* A player loses if they have no HP left on the place
* The game ends when only one player remains

## Rulesets

* [Main Set](/en/rulesets/DEFAULT.md)
* [Candidate for Main Set](/en/rulesets/DEFAULT_CANDIDATE.md)
* [Candidate-2 for Main Set](/en/rulesets/DEFAULT_CANDIDATE-2.md)

## Terms

### HP (Health Point block)

* Placed on the place
* Can contain an item
* Gives 1 Action
* Must be present on the place for the game to continue

### Action

* An available activity during a turn
* Actions:
    * Move - changing the position of items in the game
    * Loot - obtaining items
    * Attack - any action or condition that destroys HP on the place
    * Craft - creating items by combining resources
    * Destroy - removing an item for a reward and by spending an Action
    * Delete - removing an item without a reward and without spending an Action

### Ruleset

* A list of rules including:
    * Item Set
    * Mechanics Set
    * Crafts

### Inventory

* The in-game inventory is visible to every player
* Holds up to 9 items

## Actions

* Move - changing the position of items in the game:
    * Place <-> Inventory
    * Place <-> Place
    * Inventory <-> Inventory, usually does not spend an Action

* Loot - obtaining items into the inventory or onto an empty HP
    * Loot parameters
        * conditions
    * Also possible when the required resources for a Craft are missing

* Craft - creating items by combining resources
    * Craft parameters
        * required items
        * resources
        * placement
    * Produces the created item, deleting the used resources

* Attack - any action or condition linked to the destruction of HP in a certain area for some cost
    * Attack parameters
        * Cost
        * Area
        * Number of destroyed blocks

* Destroy - removing an item for a reward
    * Destroy parameters
        * item
        * reward
    * Delete - a subtype of Destroy, without a reward and without spending an Action
