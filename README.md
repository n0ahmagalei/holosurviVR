# **holo surviVR**

A first-person VR survival game inspired by games like HoloCure and Vampire Survivors. The objective is simple: survive increasingly difficult enemy waves for 3 minutes, collect experience orbs, level up, and stack upgrades to stay alive as long as possible.

## Project Overview

holo surviVR was built as a VR class final project in Unity and C#. The game takes the auto-attacking survival formula and reimagines it in a first-person virtual reality setting, where players are surrounded by enemies, forced to reposition constantly, and make quick upgrade decisions while under pressure.

The core idea was to create a replayable VR survival experience where the player spawns with a random set of weapons, fights off continuous waves of enemies, and becomes stronger through level-up upgrades. The pacing was tuned around a short 3-minute run so multiple people could quickly try the game during a showcase setting.

## Gameplay Features
First-person VR survival combat
3-minute enemy survival loop
Increasing enemy count over time
XP orb collection and level progression
Randomized starting weapon loadout for replayability
Upgrade selection menu that pauses gameplay
Mix of auto-targeting and manual-aim weapons
Weapons

### The game includes four weapon types:

Automatic Gun
Automatically fires at the closest enemy and does not require manual aiming.
Split Gun
Fires multiple bullets in multiple directions and requires manual aiming.
Poison Gun
Launches a projectile in an arc that explodes and leaves behind a poison puddle that damages enemies over time.
Rotating Weapon
Spawns orbiting spheres around the player that damage enemies on contact.
Upgrade System

### As enemies are defeated, they drop experience orbs. Collecting enough XP causes the player to level up, which pauses the game and brings up an upgrade menu in front of the player. Upgrade options focus on things like:

increasing bullet count
increasing fire speed
increasing weapon damage

### This system gave the game a stronger sense of progression while also giving players brief breathing room during intense moments.

## VR Controls
Left joystick / left touchpad: player movement
Right joystick / right touchpad: snap turn camera left or right
Left trigger: confirm upgrade selection
Left joystick: move menu selector between upgrade choices
Technical Highlights

A big part of the project was building the game in a modular way so different systems could be adjusted quickly during development.

Enemy prefabs shared common scripts for movement, collision, and damage logic
The player prefab held the majority of the gameplay systems, including health, XP, HUD, VR movement, and weapon scripts
Weapon scripts were designed so bullet prefabs could be assigned through the Unity Inspector
Public variables made balancing easier for the whole team
The automatic gun used enemy-distance checks to find and fire at the nearest target
A cooldown system was added to the level-up menu input so joystick scrolling would not move too fast every frame
My Contributions

My role on this project focused on sound design, audio implementation, and programming support. I created the in-game sound effects, worked on integrating audio into the experience, and helped support different parts of the project as we moved toward final testing and presentation. I also used Audacity to build out weapon, hit, and enemy-related sound effects.

## Development Challenges

Like a lot of VR projects, development came with a few technical headaches. One of the main challenges was dealing with Unity and SteamVR bugs while trying to keep the experience stable and presentation-ready. We also learned a lot about collaboration, version control, and dividing responsibilities across art, audio, UI, and gameplay systems.

## What I Learned

### This project helped reinforce a few important things for me:

designing gameplay for VR requires different pacing and fairness decisions than standard games
modular scripting makes balancing and iteration much easier
audio has a huge impact on how satisfying combat feels
team communication and version control matter just as much as coding during game development
Tools Used
Unity
C#
SteamVR
Audacity
GitHub
Trello
Team

### This project was developed by Group 4:

Dax Taraleskof — Programmer / Manager
Riley Saliba — Artist / Animator
Alfredo Hernandez — Art Team Communication / Documentation
Noah Magalei — Sound Design / Programming
Octavio Lozano — Programmer / Systems Designer
Media

## Notes:
holo surviVR was a team-built VR survival project that combined fast-paced gameplay, modular systems, and replayability through randomized weapons and upgrades. For me, it was a strong hands-on project in VR development, sound design, and collaborative game production.
