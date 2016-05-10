---
layout: page
title: Events
---

Events trigger code in a script, and provide variables that the script can use. Events are listened to using `on <eventname>:`.
For example, to listen to the `join` event, type `on join:`. Below is a list of events and what they do.

## Join

Called whenever a player joins the server.

**Variables:** `player`

## Quit

Called whenever a player leaves the server.

**Variables:** `player`

## Break

Called whenever a player breaks a block.

**Variables:** `player`, `block`
