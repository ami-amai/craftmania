# CraftMania

[**EN**](/rules/RULES_EN.md) | [RU](/rules/RULES_RU.md)

## Contents

* [Introduction](#introduction)
* [About the Game](#about-the-game)
    * [Game Field](#game-field)
    * [Inventory](#inventory)
    * [Items](#items)
    * [Crafts](#craft)
    * [Actions](#actions)
* [Atlas](#atlas)
    * [Types](#types)
    * [Items](#items-1)

## Introduction

* A strategic game in which victory requires creating items, destroying enemy cells, and preventing the destruction of your own.

## About the Game

* The game features a [Game Field](#game-field), [Inventory](#inventory), Items, and Crafts.
* Up to 3 Actions can be performed per turn.

### Game Field

* The [Game Field](#game-field) allows placing items on it using [HBs](#health-blocks).
* Items on the field can sometimes provide bonuses or access to specific crafts.
* [HBs](#health-blocks) can be destroyed using the Attack Action; Items on destroyed blocks will also be destroyed.

### Inventory

* The [Inventory](#inventory) allows safely storing [Items](#items) and [HBs](#health-blocks) before placement, performing [Crafts](#crafts), and consuming [Items](#items).

### Items

* [Items](#items) can be Blocks, Tools, Resources, or Food.
    * Blocks can grant access to Crafts or be placed to reinforce [HBs](#health-blocks) if they have a high Tier.
    * Tools are used for the Multicraft Action on the field, can grant access to Crafts, and are used to destroy blocks by consuming material.
    * Resources can grant access to Crafts or be consumable.
        * Food provides additional [HBs](#health-blocks).
        * Material is consumed for [Attack](#attack) and affects the allowable Tier of destroyed blocks.

### Crafts

* Items can be converted into others while in the inventory if they meet the conditions regarding the presence of specific items on the field.
* They can also be converted using the multicraft action.

### Actions

#### On the Field

##### Placing

* You can place an [HB](#health-blocks) on the field.
* You can place an item by placing an [HB](#health-blocks), an Item Frame on top, and the desired item inside it.
* You can place an item on an already placed empty [HB](#health-blocks).

##### Taking

* You can take your item from the field by placing it into the inventory; the [HB](#health-blocks) remains on the field.

##### Attack

* Attack allows destroying all [HBs](#health-blocks) within a 1-block radius (3x3) of the placed tool using the tool, provided the tool is capable of destroying them using the used Material. The attack is a single action.

##### Multicraft

* You can place one of the necessary items for a craft near your items on the field. If all conditions are met after placement, a craft of the surrounding items linked to the placed item will be performed.

#### In Inventory

##### Craft
* You can craft an item if all craft conditions are met.

##### Use
* You can use an item if it is consumable.

##### Item Deletion
* You can destroy Items if the Inventory is full, in any quantity and any items inside the inventory; this does not spend an action.

### Health Blocks

* Health Blocks (HB) allow making moves. If a player has no HBs left on the field, they lose.

## Atlas

### Types

* #### Resource

    * Destroyed by any Tool.

* #### Dirt-type

    * Destroyed by a Shovel.

* #### Wooden

    * Destroyed by an Axe.

* #### Stone

    * Destroyed by a Pickaxe.

### Items

#### Log

* Type: [Wood](#wooden)
* Tier: 1
* **Base Resource**

#### Planks

* Type: [Wood](#wooden)
* Tier: 1
* Requirements:
* From: [Log](#log)

#### Crafting Table

* Type: [Wood](#wooden)
* Tier: 2
* Requirements:
* From: [Planks](#planks)

#### Stripped Log

* Type: [Wood](#wooden)
* Tier: 3
* Requirements: [Crafting Table](#crafting-table), Axe, [Log](#log) x2
* From: [Log](#log)

#### Composter

* Type: [Wood](#wooden)
* Tier: 3
* Requirements: [Crafting Table](#crafting-table), Axe, [Stripped Log](#stripped-log)
* From: [Stripped Log](#stripped-log)

#### Shovel

* Type: [Resource](#resource)
* Tier: 1
* Requirements: [Crafting Table](#crafting-table), [Planks](#planks), [Dirt](#dirt)
* From: [Planks](#planks)
* **Used to destroy [Dirt-type](#dirt-type) blocks using a resource.**

#### Axe

* Type: [Resource](#resource)
* Tier: 1
* Requirements: [Crafting Table](#crafting-table), [Planks](#planks), [Log](#log)
* From: [Planks](#planks)
* **Used to destroy [Wooden](#wooden) blocks using a resource.**

#### Pickaxe

* Type: [Resource](#resource)
* Tier: 1
* Requirements: [Crafting Table](#crafting-table), [Planks](#planks), [Stone](#stone)
* From: [Planks](#planks)
* **Used to destroy [Stone](#stone) blocks using a resource.**

#### Stone

* Type: [Stone](#stone)
* Tier: 1
* **Base Resource**

#### Cobblestone

* Type: [Stone](#stone)
* Tier: 1
* Requirements: [Pickaxe](#pickaxe)
* From: [Stone](#stone)

#### Furnace

* Type: [Stone](#stone)
* Tier: 2
* Requirements: [Crafting Table](#crafting-table), [Cobblestone](#cobblestone)
* From: [Cobblestone](#cobblestone)

#### Stone Bricks

* Type: [Stone](#stone)
* Tier: 3
* Requirements: [Furnace](#furnace), [Crafting Table](#crafting-table), [Stone](#stone) x2
* From: [Stone](#stone)

#### Copper Ore Block

* Type: [Stone](#stone)
* Tier: 1
* Requirements: [Pickaxe](#pickaxe)
* From: [Stone](#stone)

#### Iron Ore Block

* Type: [Stone](#stone)
* Tier: 1
* Requirements: [Pickaxe](#pickaxe)
* From: [Stone](#stone)
 
#### Gold Ore Block

* Type: [Stone](#stone)
* Tier: 1
* Requirements: [Pickaxe](#pickaxe)
* From: [Stone](#stone)
 
#### Copper Ingot

* Type: [Resource](#resource)
* Tier: 1
* Requirements: [Furnace](#furnace), [Pickaxe](#pickaxe)
* From: [Copper Ore Block](#copper-ore-block)

* **Allows destroying Tier 1 blocks using tools; is consumed.**
 
#### Copper Block

* Type: [Stone](#stone)
* Tier: 2
* Requirements: [Crafting Table](#crafting-table), [Copper Ingot](#copper-ingot) x2
* From: [Copper Ingot](#copper-ingot)

#### Iron Ingot

* Type: [Resource](#resource)
* Tier: 1
* Requirements: [Furnace](#furnace), [Pickaxe](#pickaxe)
* From: [Iron Ore Block](#iron-ore-block)
* **Allows destroying Tier 2 blocks and below using tools; is consumed.**

#### Iron Block

* Type: [Stone](#stone)
* Tier: 2
* Requirements: [Crafting Table](#crafting-table), [Iron Ingot](#iron-ingot)
* From: [Iron Ingot](#iron-ingot)

#### Gold Ore

* Type: [Resource](#resource)
* Tier: 1
* Requirements: [Pickaxe](#pickaxe)
* From: [Gold Ore Block](#gold-ore-block)

#### Gold Ingot

* Type: [Resource](#resource)
* Tier: 1
* Requirements: [Furnace](#furnace)
* From: [Gold Ore](#gold-ore)
* **Allows destroying Tier 3 blocks and below using tools; is consumed.**

#### Gold Block

* Type: [Stone](#stone)
* Tier: 3
* Requirements: [Crafting Table](#crafting-table), [Gold Ingot](#gold-ingot)
* From: [Gold Ingot](#gold-ingot)

#### Seeds

* Type: [Resource](#resource)
* Tier: 1
* **Base Resource**
* **When on the field, grants 1 HB every turn.**

#### Wheat

* Type: [Resource](#resource)
* Tier: 1
* Requirements:
* From: [Seeds](#seeds)

#### Bread

* Type: [Resource](#resource)
* Tier: 1
* Requirements: [Crafting Table](#crafting-table), [Wheat](#wheat)
* From: [Wheat](#wheat)
* **Consumable, grants 3 HB when used.**

#### Carrot

* Type: [Resource](#resource)
* Tier: 2
* Requirements: [Crafting Table](#crafting-table), Bread, Composter
* From: [Seeds](#seeds)
* **Consumable, grants 3 HB when used.**
* **When on the field, grants 1 HB every turn.**

#### Golden Carrot

* Type: [Resource](#resource)
* Tier: 3
* Requirements: [Crafting Table](#crafting-table), [Gold Ingot](#gold-ingot)
* From: [Carrot](#carrot)

* **Consumable, grants 5 HB when used.**
* **When on the field, grants 3 HB every turn.**

#### Dirt

* Type: [Dirt-type](#dirt-type)
* Tier: 1
* **Base Resource**

#### Mud

* Type: [Dirt-type](#dirt-type)
* Tier: 2
* Requirements: [Shovel](#shovel)
* From: [Dirt](#dirt)

#### Packed Mud

* Type: [Dirt-type](#dirt-type)
* Tier: 3
* Requirements: [Crafting Table](#crafting-table), Mud, [Wheat](#wheat)
* From: [Mud](#mud)

#### Mud Bricks

* Type: [Stone](#stone)
* Tier: 3
* Requirements: [Crafting Table](#crafting-table), Packed Mud
* From: [Packed Mud](#packed-mud)