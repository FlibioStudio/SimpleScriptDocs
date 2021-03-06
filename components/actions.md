---
layout: page
title: Actions
---

Actions allow you to do something to the server. They must be ran inside of an event.
For example, to listen to send a player a message, type `send "Hello!" to the player:`. Below is a list of actions and what they do.

## Send

Sends a message to a player. Allows messages to be formatted using formatting codes (`&`).

**Usage:** `send <message> to <receiver>`

## Broadcast

Broadcasts a message to the entire server.

**Usage:** `broadcast <message>`

## Cancel

Cancels an event, if it can be cancelled. Any lines of script after `cancel` will not be run.

**Usage:** `cancel`

## Teleport

Teleports a player to a location.

**Usage:** `teleport <target> to <location>`

## Drop

Drops items at a certain location.

**Usage:** `drop <amount> <item type> at <location>`
