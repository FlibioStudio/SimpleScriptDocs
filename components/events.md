---
layout: page
title: Events
---

Events trigger code in a script, and provide variables that the script can use. Events are listened to using `on <eventname>:`.
For example, to listen to the `join` event, type `on join:`. There are currently two types of events in SimpleScript, normal events and linked events. Normal events are listened to in a script. Linked events can not be listened to, and only cancelled. They are used to stop certain effects caused by an event. A list of events and linked events can be found below.

## Events

### Join

Called whenever a player joins the server.

**Variables:** `player`

**Linked Events:** none

### Quit

Called whenever a player leaves the server.

**Variables:** `player`

**Linked Events:** none

### Break

Called whenever a player breaks a block.

**Variables:** `player`, `block`

**Linked Events:** `drop`

---

## Linked Events

### Drop

Called when an item is about to be dropped.
