---
layout: page
title: Examples
---

**Spawn Location**

Teleports a player to a spawn location and sends them a hello message when they join the server.

```nohighlight
on join:
    teleport the player to -921 75 314
    send "Welcome to the server!" to the player
```

**Make Iron Ore Drop Stone**

Makes iron ore drop a stone when broken, instead of an iron ore.

```nohighlight
on break:
    block has block type of "minecraft:iron_ore"
    set block at block location to air
    cancel drop
    drop 1 stone at the block location
```

**Disallow Block Breaks**

Disallows block breaking, unless the player has the permission `admin.blockbreak`.

```nohighlight
on break:
    player has permission not of "admin.blockbreak"
    cancel
    send "You can not break blocks!" to the player
```