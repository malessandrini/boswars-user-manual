# Introduction

[Bos Wars](https://www.boswars.org/) is a free-software real-time strategy (RTS) game. In an RTS game you usually must conquer the whole "world" in a given level, destroying all the enemies in the process. Generally you start in a small corner with very few resources, and you have to build your army (including defenses for your bases) in order to explore and conquer wider and wider areas and defy the enemies you encounter. In doing so you also have to manage the resources you need (energy, materials) and find ever new supplies of them. But beware, enemies in the dark meanwhile are working fast with the same goal, including destroying you, so you must adopt a good strategy and balance all your resources.

# The map

![Game map](pics/map/map.png "Example of game map")

The map is where the game takes place. You can distinguish three types af areas:
- Full-bright areas: areas in direct sight from your units, that is where at least one of your units currently is. Thanks to physical presence you can see what's actually happening. Every unit has a predefined sight range, usually not too wide.
- Black areas: initially the most part, they are unknown areas where you never went, that will be discovered when reached. This feature can be disabled (so to see the full map from the beginning), but come on, that would not be funny, right?
- Obfuscated areas: areas where you previously went but now no more of your units are, for example if all the units in an area are killed. You can still see the area, but you cannot see what's currently happening anymore; you only have a "photo" of the last time you were there. This feature is called "fog of war". This feature can be disabled, too, but again, enjoy the game as it's meant!

You can scroll the map in the four directions by moving the mouse near the four borders.

## The mini-map

![Mini-map](pics/map/minimap.png "Example of mini-map")

The mini-map, in the upper right corner, gives you a glance of the full map. You can move rapidly through the map by clicking and dragging in the mini-map.

# Basic actions: selection and movement

## selection

A single unit can be selected by left-cliking on it, like in thie example:
![Single selection](pics/map/select1.png "Single selection")

More than one unit can be selected by keeping the shift key pressed and left-clicking on the next ones.

You can select all the units of a given type by double-clicking one of them:
![Selection by type](pics/map/select2.png "Selection by type")

You can select a group of units by dragging a rectangle around them with the left mouse button:
![Rectangular selection](pics/map/select3.png "Selection by dragging a rectangle")

