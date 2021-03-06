# Godot 3.2 Multiplayer First Person Shooter

**A multiplayer first person shooter example project for Godot 3.2 game engine.**

Features
========

- Multiplayer: using Godot's High Level Multiplayer API
- Character with animations for different states, like running, swimming and climbing
- Bots: stack based FSM AI
- 3 types of weapons: an automatic machine gun, a shotgun with spread, a grabbity gun
- Sounds: footsteps, weapons, props, impacts, underwater effects
- Touchscreen controls

Keys
====

- Walk: `W/A/S/D`
- Jump: `Space`
- Fire: `Left Mouse Button`
- Grab: `Right Mouse Button`

Description
===========

First person shooter with a multiplayer. Includes a seperate project for server and one for client. 
To play over the internet in the main scene properties (client project) there's an exposed parameter for a public IP address, set to localhost by default.
Port 27015 (an arbitrary number, can be changed in the code) must be accessible through the firewall or in the router settings and not blocked by ISP (Internet Service Provider).
Make sure to run the server project first, then click "Play" on the client.

Preview
=======

[![Multiplayer FPS](https://i.ytimg.com/vi_webp/jlBdM_OZyqg/maxresdefault.webp)](https://www.youtube.com/watch?v=jlBdM_OZyqg)

Links
=====

High Level Multiplayer API
- https://docs.godotengine.org/en/stable/tutorials/networking/high_level_multiplayer.html

FPS Tutorial
- https://docs.godotengine.org/en/stable/tutorials/3d/fps_tutorial/part_one.html

Finite-State Machines: Theory and Implementation
- https://gamedevelopment.tutsplus.com/tutorials/finite-state-machines-theory-and-implementation--gamedev-11867

Credits
=======

Uses Gonkee's joystick script for Godot 3
- https://youtu.be/uGyEP2LUFPg

Touchscreen buttons by xelu
- https://opengameart.org/content/free-keyboard-and-controllers-prompts-pack

Sounds:

- https://sonniss.com/gameaudiogdc2017/
- https://sonniss.com/gameaudiogdc18/
- https://sonniss.com/gameaudiogdc19/
- https://freesound.org/people/monte32/sounds/353799/
- https://freesound.org/people/mickyman5000/sounds/340493/


Thank you
=========

To support this kind of projects consider becoming a patron.
- https://www.patreon.com/ic3bug
