# sd2snes YAML Cheat Codes

## Introduction

This repository will start with the YAML format cheat files for a small selection of the cartridges I own but over time I might add new ones.

I prefer to run SNES games plugged into my HDMI TV using the [Analog Super NT](https://www.analogue.co/super-nt/) with the ROMs from cartridges I own on a [sd2snes cartridge](https://sd2snes.de/blog/about) allowing my collection to stay safe from wear and tear in protective boxes.

I also run a [custom firmware for sd2snes which enables savestates](https://twitter.com/furious_/status/1050063105168945152).

Usually I prefer playing and beating games without cheats as overcoming the challenge of each title is part of the fun. However, it's sometimes nice to just relax with a nostalgic run through a favourite title without the threat of running out of lives on games from an era when Nintendo Difficult makes Dark Souls feel like Easy Mode ;)

Most of the codes were obtained from the excellent [GameHacking.org](https://gamehacking.org) site but saved here for my own personal easy of use.

## sd2snes cheats

### How to use cheats on a sd2snes cartridge

Edit the YML file and change any cheats you wish to enable to `enabled: true`. All cheats are currently set to `false` by default.

Upload the YML format cheat files onto your sdcard in the `/sd2snes/cheats` folder. Ensure the cheat file is the same name as your ROM file. For example `Super Mario World (USA).yml` will apply to `Super Mario World (USA).sfc`.

You will also need to enable In-Game Hooks in the sd2snes menu.

Now, once in the game you can enable cheats using `L + R + Start + A`.

### List of In-game hooks

- `L + R + Select + Start` - Reset game
- `L + R + Select + X` - Reset to sd2snes menu
- `L + R + Start + B` - Disable cheats
- `L + R + Start + A` - Enable cheats
- `L + R + Start + Y` - Permanently disable in-game hooks (in case they interfere with game operation).
- `L + R + Start + X` - Temporarily disable in-game hooks (~10 seconds - if you need to get past a glitch but don't want to lose in-game buttons)

## Custom Firmware with Savestates

### Where can I get the custom firmware to enable savestates?

You can download the custom sd2snes firmware from [dl.furious.pro](dl.furious.pro/sd2snes.zip).

### How do I use the savestates?

There are 4 save slots available to use. Select the slot by using `Select + Up`, `Select + Down`, `Select + Right`, or `Select + Left`

Once you've set the slot to use, you can save by hitting `Start + L` and load by hitting `Start + R`.

### Are there any issues with savestates?

It doesn't work on games that require special chips such as StarFox.

If using the Furious savestate custom firmware then cheats do not work while savestates are on at the same time. Disable SaveStates from the menu on the sd2snes menu.
