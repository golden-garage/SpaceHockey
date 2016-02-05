# SpaceHockey QML Tutorial

This introductory tutorial on QML. In it, you will develop a simple two player touch game: SpaceHockey.


## Space Hockey Game Rules

**Players:** 2

**Object of Game:** score more Points than your Opponent

**Playing Field:** a walled arena with two open Goals on opposite walls

**Playing Pieces:** Planets (and other objects) that float around the Playing Field

**Tapping Area:** an area directly in front of each Goal that responds to Player touch gestures

**Touch Gestures:** *tap* - emit a 360 degree force outwards from the location of the tap

**Playing the Game:** each Tapping Gesture creates an impulse of force that moves the Planet(s)

**Scoring:** one Point is awarded to the Opponent when a Planet enters the Player's Goal


## Tools used to build the game

The SpaceHockey game is built using [Qt](http://www.qt.io/) with additional Gaming Components from
[V-Play](http://v-play.net/) (*hint:* the V-Play download includes Qt and the QtCreator).

[Qt](http://www.qt.io/) is the leading independent technology for cross-platform development. The
[Qt Quick](http://doc.qt.io/qt-5/qtquick-index.html) module is a library for writing applications in the Qt Meta-object
Language (QML) - a declarative language that simplifies the design and implementation of UIs. QML is based on CSS and
JavaScript. Large parts of QML code are just CSS-style name-value pairs of properties (e.g., color: "red"). The rest,
typically the behavioral parts like the response to a mouse click, is written in JavaScript.

[V-Play](http://v-play.net/) Gaming Components provide a specialized set of QML components for building 2D games on top
of Qt 5 for multiple platforms, with the same source code. Components exist for handling multiple display resolutions &
aspect ratios, Sprites, Physics, Particles, Multimedia, Multitouch Input and AI.

The current version of the game is a simple simulation of air hockey in a space-like environment.

## How do you build SpaceHockey?

### Step One - Download and Install V-Play

Use the instruction on the [V-Play Download](https://v-play.net/download/) site.

### Step Two - Create a New - Empty V-Play 2 Project

Start V-Play.

Choose File -> New File or Project.

Choose New -Empty V-Play 2 Project.

Name the project SpaceHockey. Click continue.

Select the Desktop kit from the Kit Selection screen. Click Continue.

Validate the App identifier. Click continue.

Add to version control (if you wish). Click Done (Finish).

Run the default game to test your installation (it is kinda boring).
