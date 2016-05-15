---
layout: page
title: Variables
---

Variables are used to store information in a script. Variables are pre-defined by events (Allowing custom variables is planned).
Variables are used in most scripts, and are used in conditionals. A list of variable types and properties can be found below.

## Variable Types

A Variable Type represents the type of data a variable contains. These variable types can be created by scripts.

### String

**Example:** `"I am a string!"`

### Double

**Example:** `92.39`, `1`

### Boolean

**Example:** `true`, `false`

### Block Type

**Example:** `minecraft:grass`

### Item Type

**Example:** `cookie`

### Location

**Example:** `-912 81 351`

---

## Defined Variables

A Defined Variable is defined by an event and can not be created by a script.

### Player

Stores information about a specific player.

**Properties:** `display name`, `location`, `permission`

### Block

Stores information about a specific block.

**Properties:** `location`, `block type`

---

## Variable Properties

A Variable Property is a piece of data that is stored on a Defined Variable.

### Display Name

Contains the display name of a variable.

**Type:** `String`

**Example Value:** `Flibio`

### Permission

Checks if a player has a certain permission.

**Type:** `Boolean`

**Example Value:** Can only be used in a conditional

### Location

The location of something in the world.

**Type:** `Location`

**Example Value:** `-127 83 830`

### Block Type

The type of a block.

**Type:** `Block Type`

**Example Value:** `minecraft:grass`
