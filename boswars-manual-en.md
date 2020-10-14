# Introduction

[Bos Wars](https://www.boswars.org/) is a free-software real-time strategy (RTS) game. In an RTS game you usually must conquer the whole "world" in a given level, destroying all the enemies in the process. Generally you start in a small corner with very few resources, and you have to build your army (including defenses for your bases) in order to explore and conquer wider and wider areas and defy the enemies you encounter. In doing so you also have to manage the resources you need (energy, materials) and find ever new supplies of them. But beware, enemies in the dark meanwhile are working fast with the same goal, including destroying you, so you must adopt a good strategy and balance all your resources.

# The map

![Game map](pics/map/map.png "Example of game map")

The map is where the game takes place. You can distinguish three types af areas:

- Full-bright areas: areas in direct sight from your units, that is where you have at least one of your units. Thanks to physical presence you can see what's actually happening. Every unit has a predefined sight range, usually not too wide.
- Black areas: initially the most part, they are unknown areas where you never went, that will be discovered when reached. This feature can be disabled (so to see the full map from the beginning), but come on, that would not be funny, right?
- Obfuscated areas (half-bright): areas where you previously went but now no more of your units are, for example if all the units in an area are killed. You can still see the area, but you cannot see what's currently happening anymore; you only have a "photo" of the last time you were there, so it may be full of enemies now, but you only can see it when you go there again. This feature is called "fog of war" and can be disabled, too, but again, enjoy the game as it's meant!

You can scroll the map in the four directions by moving the mouse near the four borders.

## The mini-map

![Mini-map](pics/map/minimap.png "Example of mini-map")

The mini-map, in the upper right corner, gives you a glance of the full map. You can move rapidly through the map by clicking and dragging in the mini-map. Dots of different colors indicate different kind of objects, for example green is your units, blue is enemy's structures, purple is magma spots.

## In-game menu

By pressing F10 during the game, you can pause the game and access the menu with game-related actions, like saving, quitting or changing speed.

## Units

Units (humans, vehicles, factories, facilities, etc) live on the map, unless they are attacked and deprived of all their health, in that case they are killed and disappear. For example the following is an engineer:

![Engineer](pics/units/engineer.png "Engineer")

This little yellow guy is a very important unit in the game. It cannot fight or defend itself, but it can build structures and harvest resources, and so we'll talk about him/her in various places throghout this document. As you can see, units show a bar with their current health (when not full), when it's empy the unit will die.

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

When a unit is selected, in the right area of the map you can see two boxes: its current status (health and features) and an action menu with several buttons, indicating the actions you can make it perform. For example, when selecting an engineer:

![Unit status](pics/map/status-menu.png "Status and action menu of unit")

Every action in the menu can be clicked, or the corresponding letter can be pressed on keyboard. A menu item can open another menu with more details. You can move the mouse over a button to get a description or the features of a given element. The actions will be explained for every unit.

## Movement

When one or more units are selected, they can be moved by right-clicking on an empty (and reachable) area. They will try to find the best path, everyone at its speed. Sometimes right-clicking on an object, instead of an empty area, makes the unit do the right thing with that object, depending on the unit. This will be explained when needed.

# Resources

To build your increasing army, along with buildings, defenses, etc, you'll need two kind of resources: **energy** and **magma** (ore). At the top of the map there is an indicator of their quantities and production rate:

![Energy-magma indicator](pics/map/energy-magma.png "Energy and magma indicator")

For every kind of resource you can see the amount you are producing (plus sign), the amount you are consuming (minus sign) and the stocked supply (stocking is only possible if you have at least one vault).

Reources are consumed when your engineers are building things or when your factories are producing units. If the supply is not enough for the demand, production of units and structures will slow down.

Let's explain how to collect the two kind of resources.

## Energy

At a low level, energy can be harvested from trees. To do that, select an engineer, then in the action menu select "harvest" (or press H) and click on a tree. A faster way is selecting an engineer and right-clicking on a tree. When the tree is exhausted, the engineer will move to another tree, and so on. Here's an engineer harvesting a tree:

![Harvesting trees](pics/map/tree-harvest.png "An engineer harvesting a tree for energy")

The standard and more efficient way of generating energy, though, is building power plants or nuclear power plants (see building structures). As soon as you have a minimum income of energy and magma you can build one or more power plants and have an unlimited quantity of energy. For this reason energy is not a big problem in the game's economy.

## Magma

At a low level, magma can be harvested from rocks. You can use the same commands as trees to make engineers harvest rocks or rock fields:

![Rocks](pics/map/rocks.png "Rocks and rock fields")

This will last for a limited amount of time, until all the rocks in an area are exhausted.

The more effective way is finding magma spots (also called "hot spots") and build a magma pump on it. The pump will provide a steady flow of magma. To do that, select an engineer, than select "Build" in the action menu (or press B), then "Magma pump" (M) in the submenu, and finally click on the magma spot to start construction. A faster way is selecting an engineer and right-clicking on a magma spot. Here is a magma spot alone and after a magma pump has been built on it:

![Magma spots](pics/map/magma.png "Magma spots and pumps")

Magma spots are often rare, and rocks have a limited duration, so magma is often the biggest problem in managing resources. Be sure to look for new magma spots as soon as you expand your dominion. A good income of magma is the key to build a big army fast.

(You can even get magma by harvesting existing structures, including your own ones, but that's very inefficient.)

# Building structures

Fixed structures are built by engineers. These structures include generic facilities, defense weapons and factories which, in turn, will build fighting units.

Due to its importance, we will describe now the engineer in detail.

## The engineer

![Engineer](pics/units/engineer.png "Engineer")

An engineer can build fixed structures, as described above, can harvest resources in case of shortcoming (described previously) and repair things.

To build a structure, select the engineer and then press one of the following action buttons (or press the matching key):

- B (Build basic structures) to build generic facilities
- U (Build unit structures) to build factories for fighting units
- D (Build defensive structures) to build defensive weapons

In each submenu you have the possible structures to be built, described later. Moving the mouse over them you can see a list of their features, plus the cost in energy and magma to build them (see pictures in the following sections). Usually elements in a submenu are ordered by importance, starting from cheaper but weaker units down to the most powerful (but more expensive) ones.

Once you have selected the desired structure (by clicking on it or pressing the matching key), you have to click on a clear area with room enough for it (the shape of the structure is shown at your mouse pointer). Finally the engineer will start building it, like in this example of an engineer building a vehicle factory:

![Engineer building a structure](pics/structs/engineer-building.png "An engineer building a structure")

Construction will take some time, a bar indicates its progress. The bar disappear when the structure is complete, but reappears if it's damaged, to indicate its health level.

An engineer can also repair a damaged object, or continue its construction if it was not finished to build. To do so, the fastest way is selecting an engineer and right-clicking on the object.

You can assign more engineers to build/repair an object if you want to accelerate the process; to do so, select other engineers and right-click on the object that the first engineer is already working on.

Finally, engineers can be produced like every other unit if you need more of them. Specifically they are produced by the vault or the training camp (see below).

Hint: be sure to always have at least one engineer alive, or to have factories able to produce them, or you will not be able to build new objects and replace destroyed ones.

## Basic structures

![Basic structure submenu](pics/structs/menu-basic.png "Basic structure submenu")

### Vault ("V")

![Vault](pics/structs/vault.png "Vault")

The vault can store energy and magma, so to stock surplus of them for later use, and can produce new engineers. Usually you start a level with an existing vault (but not always).

### Magma pump ("M")

![Magma pump](pics/structs/magma-pump.png "Magma pump")

Built on top of a magma spot, it produces a fixed amount of magma. See Resources for a deeper explanation.

### Radar ("R")

![Radar](pics/structs/radar.png "Radar")

The radar can give you a sight range in a given area and, more importantly, it can reveal important spots in the mini-map, even in unexplored areas. For this reason it's better to have one of them.

### Camera ("C")

![Camera](pics/structs/camera.png "Camera")

Like the radar, the camera can give you a point of sight from the place where it's built.

### Power plant ("P")

![Power plant](pics/structs/power.png "Power plant")

It produces a fixed amount of energy. See Resources.

### Nuclear power plant ("N")

![Nuclear power plant](pics/structs/nuclear.png "Nuclear")

Like the power plant, but it produces more energy. See Resources.


## Unit structures

![Unit structure submenu](pics/structs/menu-unit.png "Unit structure submenu")

### Training camp ("C")

![Training camp](pics/structs/training-camp.png "Training camp")

It "produces" human fighter of various strength, plus the engineers. Details in the following section.

### Hospital ("H")

### Vehicle factory ("V")

It produces fighting vehicles, like tanks for example. Details in the following section.

### Shipyard ("S")

It produces water vehicles that can travel and fight in water. A shipyard must be built near water.

### Aircraft factory ("A")

It produces aerial vehicles, that can reach every point of the map to explore or fight.


## Defensive structures

![Defensive structure submenu](pics/structs/menu-defensive.png "Defensive structure submenu")

### Gun turret ("G")

It shoots enemies as soon as they are in its range. Useful to create a defensive border around your base.

### Big gun turret ("B")

Like the gun turret, but more powerful.

### Cannon ("C")

It shoots at a very long range and it's quite powerful, usually you are hit by one of those before you can even see it (its shot looks like a light blue fireball). On the other hand it takes long to recharge and it's not very precise, especially on moving targets. For those reasons it can be seen more like an offensive weapon. Together with a radar, it can target enemy units even in unexplored areas.

### Missile silo ("M")

It can launch very powerful nuclear missiles to every target on the map, but it's very expensive to build and recharge.

Note:

destroy trees

copyright





