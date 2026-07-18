# Darkin Class Mod

## Development Overview

This project was created using Baldur's Gate 3's data-driven modding toolkit to add new featues to the game. New features include: new gameplay systems, abilities, statuses, and character class progressions. The goal of this project was to recreate the unique gameplay identities of Aatrox, Varus, and Naafiri within Baldur's Gate 3 while adapting their abilities to the game's turn-based combat system.

## Project Status

Published mod available on mod.io with 600+ downloads. The project is complete and is open to receiving maintenance based on player feedback.

## More Information

This repository serves as a small overview for the full project on mod.io. For detailed ability descriptions, progression paths, and gameplay overview, see the mod page: [Darkin Class](https://mod.io/g/baldursgate3/m/darkin-class#description)

## Tools Used

- Baldur's Gate 3 Modding Toolkit
- Larian Localization Tools
- Image editing tools for custom assets

## Features

- Three unique subclasses
- Full progression from levels 1–12
- Nine custom abilities
- Three evolving passive abilities
- Custom status effects and mechanics

## Technical Highlights

This project involved designing and implementing gameplay systems such as:

- Conditional event and status logic
- Ability replacement and progression
- Stack-based combat mechanics
- Summon coordination systems
- Custom status effects
- Localization
- UI icons and ability tooltips


## Design Notes

Each subclass was designed around a different gameplay style:

- **Darkin Greatsword** – melee bruiser focused on positioning and healing.
- **Darkin Bow** – ranged executioner built around stacking and consuming Blight.
- **Darkin Dagger** – summoner that coordinates attacks with player controlled companions.

## Technical Systems

### Ability and Status Systems

Created custom abilities using Baldur's Gate 3's status and event systems. Abilities were designed around conditional effects, allowing gameplay mechanics such as:

- Damage bonuses based on active statuses
- Abilities that change behavior depending on previous actions
- Resource-based mechanics
- Temporary buffs and debuffs

### Progression System

Designed a level-based ability progression system from levels 1–12.

- Passive abilities are upgraded throughout progression.
- Active abilities receive upgraded versions at later levels.
- Players can replace earlier versions of abilities with stronger variants while maintaining class progression.

### Combo and Position-Based Combat

Implemented a multi-stage melee combat system for the Darkin Greatsword subclass focused on timing and positioning.

- Created a chained attack system where each consecutive attack increases in power.
- Implemented different outcomes based on attack placement, rewarding accurate positioning with increased damage while providing sustain through healing effects.
- Designed abilities around temporary combat states that modify player damage, accuracy, and survivability.

### Stack-Based Combat Mechanics

Implemented the Blight system for the Darkin Bow subclass.

- Attacks apply stacking debuffs to enemies.
- Other abilities consume stacks for increased effects.
- Higher-level upgrades increase stack capacity and introduce additional interactions.

### Summon Coordination

Designed a summon-focused subclass.

- Created mechanics that allow summoned wolves to benefit from player-applied effects.
- Implemented resource management through spell slot usage and temporary statuses.
- Designed abilities around coordinating player actions with companion behavior.

