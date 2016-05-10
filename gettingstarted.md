---
layout: page
title: Getting Started
---

Getting started with SimpleScript is easy to do. This page explains how to get started and provides a tutorial for
writing your first script.

### Installation

1. Download the latest SimpleScript file from the [GitHub repository](https://github.com/FlibioStudio/SimpleScript/releases).

2. Place the file in your `mods` directory found in your server root.

3. Restart your server.

### Scripts Location

Scripts are loaded from the `config/simplescript/scripts` directory. All scripts must have a `.ss` file extension.
You can have as many `.ss` files in the script directory as you like.

### Script Creation

Scripts are based around events. You can read more about events [here](http://flibiostudio.github.io/SimpleScriptDocs/components/events.html).
Events trigger a script, and provide variables that the script can use. For example, the `join` event is called whenever a player joins the server.

An action does something to the Sponge server. You can read more about actions [here](http://flibiostudio.github.io/SimpleScriptDocs/components/actions.html).
Actions can only be placed inside of an event. They must be indented using either four spaces or one tab. For example, the `send` action
is used to send a message to a player.

**Example Script:**

    on join:
	    send "Hello!" to the player
