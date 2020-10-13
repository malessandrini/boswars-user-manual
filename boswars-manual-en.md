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

The mini-map, in the upper right corner, gives you a glance of the full map. You can move rapidly through the map by clicking and dragging in the mini-map. Dots of different colors indicate different kind of objects, for example green is your units, blue is enemy's structures, purple is magma spots.

## In-game menu

By pressing F10 during the game, you can pause the game and access the menu with actions related to the game, like saving or quitting.

## Units

Units (humans, vehicles, factories, facilities, etc) live on the map, unless they are attacked and deprived of all their health, in that case they are killed and disappear. For example the following is an engineer:

![Engineer](pics/units/engineer.png "Engineer")

This little yellow guy is a very important unit in the game; it cannot fight or defend itself, but it can build structures and harvest resources, as we'll see. As you can see, units show a bar with their current health (when not full), when it's empy the unit will die.


# Basic actions: selection and movement

## Selection

A single unit can be selected by left-cliking on it, like in thie example:

![Single selection](pics/map/select1.png "Single selection")

More than one unit can be selected by keeping the shift key pressed and left-clicking on the next ones.

You can select all the units of a given type by double-clicking one of them:

![Selection by type](pics/map/select2.png "Selection by type")

You can select a group of units by dragging a rectangle around them with the left mouse button:

![Rectangular selection](pics/map/select3.png "Selection by dragging a rectangle")

(Note: there seems to be a limit to the maximum number of units selectable at the same time.)

When a unit is selected, in the right area of the map you can see two boxes: its current status (health and features) and a menu with several buttons, indicating the actions you can make it perform. For example, when selecting an engineer:

![Unit status](pics/map/status-menu.png "Status and action menu of unit")

Every menu item can be clicked, or the corresponding letter can be pressed on keyboard. A menu item can open another menu with more details. You can move the mouse over a button to get a description or the features of a given element. The actions will be explained for every unit.

## Movement

When one or more units are selected, they can be moved by right-clicking on an empty (and reachable) area. They will try to find the best path, everyone at its speed. Sometimes right-clicking on an object, instead of an empty area, makes the unit do the right thing with that object, depending on the unit. This will be explained when needed.

# Resources

To build your increasing army, along with buildings, defenses, etc, you'll need two kind of resources: **energy** and **magma** (ore). At the top of the map there is an indicator of their quantities and production rate:

![Energy-magma indicator](pics/map/energy-magma.png "Energy and magma indicator")

For every kind of resource you can see the amount you are producing (plus sign), the amount you are consuming (minus sign) and the possible stocked supply (stocking is only possible if you have at least one vault).

Reources are consumed when your engineers are building things or when your factories are producing units. If the supply is not enough for the demand, production of units and structures will slow down.

Let's explain how to collect the two kind of resources.

## Energy

At a low level, energy can be harvested from trees. To do that, select an engineer, then in the menu at right select "harvest" (or press H) and click on a tree. A faster way is selecting an engineer and right-clicking on a tree. When the tree is exhausted, the engineer will move to another tree, and so on.

The standard and more efficient way of generating energy, though, is building power plants or nuclear power plants (see building structures). As soon as you have a limited income of energy and magma you can build one or more power plants and have an unlimited quantity of energy. For this reason energy is not a big problem in the game's economy.

## Magma

At a low level, magma can be harvested from rocks. You can use the same commands to make engineers harvest rocks or rock fields. This will last for a limited amount of time, until all the rocks in an area are exhausted.

The more effective way is finding magma spots (also called "hot spots") and build a magma pump on it. The pump will provide a steady flow of magma. To do that, select an engineer, than select "Build" in the menu at right (or press B), then "Magma pump" (M) in the submenu, finally click on the magma spot to start construction. A faster way is selecting an engineer and right-clicking on a magma spot.

Magma spots are often rare, and rocks have a limited duration, so magma is often the biggest problem in managing resources. Be sure to look for new magma spots as soon as you expand your dominion.

(You can even get magma by harvesting existing structures, including your own ones, but that's very inefficient.)




