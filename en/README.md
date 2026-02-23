# CRAFTMANIA

## [RU](/ru/README.md) | [**EN**](/en/README.md)

* A strategic turn-based game in which you must develop and destroy all [HP](#hp) of your opponents to win, for 2 to 4 players

## Table of Contents

* [Introduction](#introduction)
* [Terminology](#terminology)
    * [Rules](#rules)
        * [Core Rules](#core-rules)
        * [Ruleset](#ruleset)
    * [Game](#game)
        * [Field](#field)
        * [Inventory](#inventory)
        * [Action](#action)
        * [Item](#item)
        * [HP](#hp)
* [Actions](#actions)
    * [Placement](#placement)
        * [Place](#place)
        * [Move](#move)
        * [Swap](#swap)
        * [Attack](#attack)
    * [Obtain](#obtain)
    * [Craft](#craft)
    * [Destroy](#destroy)

## Introduction

* The game operates under the [Core Rules](#core-rules) with a [Ruleset](#ruleset)

* Players accumulate [Resources](#item) and craft [Items](#item) from them to gain an advantage

* Each turn, a player may use several available [Actions](#action) for whatever they need

* Placing [Items](#item) on the [Field](#field) is done using [HP](#hp)

## Terminology

### Rules

#### Core Rules
* Rules that generally work with any Ruleset, are immutable, and describe the core game mechanics

#### Ruleset
* Rules containing the [Items](#item) in the game, the ways to Craft and Obtain them, attack patterns and costs, the behavior of any other [Items](#item), and can be changed

### Game

#### Field
* The game board on which all main actions take place
* Size is defined by the [Ruleset](#ruleset)

#### Inventory
* The game inventory, up to 9 slots, where you can place [Items](#item) from the [Field](#field)
* Size is defined by the [Ruleset](#ruleset)

#### Action
* An activity that can be performed during a turn
* [Actions](#actions) are defined by the [Core Rules](#core-rules)

[**Actions**](#actions)

#### Item
* Any in-game item that participates in crafting or provides some ability in the game
* [Items](#item) are specified in the [Ruleset](#ruleset)
* Additional functionality within the [Core Rules](#core-rules) may be defined in [Rulesets](#ruleset)
    * Resource — an item consumed during [Crafting](#craft)
    * Attack Item — an item that allows performing an attack

#### HP
* A Health Point Block (HPb (HP) / HpB (HB)), required to place [Items](#item) on the [Field](#field), and can also be spent for certain [Actions](#action)

## Actions

### Placement

* An [Action](#action) aimed at changing the position of [Items](#item) in the game

#### Place

* Placing [HP](#hp) on the [Field](#field)
    * Empty [HP](#hp)
    * With an [Item](#item)

#### Move

* Moving [Items](#item) across the [Field](#field)
    * Inventory -> [Field](#field) (empty [HP](#hp))
    * [Field](#field) -> Inventory (empty slot)

#### Swap

* Swapping [Items](#item) with each other
    * [Field](#field) <-> Inventory
    * [Field](#field) <-> [Field](#field)

#### Attack

* The [Action](#action) is performed by any [Placement](#placement) of an attack [Item](#item) on the [Field](#field), spends [HP](#hp) and destroys all [HP](#hp) in a certain pattern as specified in the [Ruleset](#ruleset)
* You can spend your own [HP](#hp) from the [Field](#field) for an attack, but all [Items](#item) on those [HP](#hp) will be destroyed
* An attack may have its own destruction methods and conditions according to the current [Ruleset](#ruleset)

### Obtain

* An [Action](#action) used to receive a [Resource](#item)
    * Into inventory (empty slot)
    * Onto the [Field](#field) (empty [HP](#hp))

### Craft

* An [Action](#action) used to create new [Items](#item) from [Resources](#item)
    * All [Resources](#item) must be on the [Field](#field) adjacent to each other (within a radius of 1 block)
    * Crafting some [Items](#item) requires other [Items](#item) to be present on the [Field](#field)
    * All [Resources](#item) are destroyed after [Crafting](#craft)

### Destroy

* An [Action](#action) that destroys [Items](#item)
    * For free, in exchange for nothing
    * For an [Action](#action), in exchange for 1 [HP](#hp)
