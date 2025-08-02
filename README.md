# Treasure Room Start <a href="https://steamcommunity.com/sharedfiles/filedetails/?id=2560433301"><img src="https://img.shields.io/endpoint.svg?url=https%3A%2F%2Fshieldsio-steam-workshop.jross.me%2F2560433301%2Fsubscriptions-text&style=for-the-badge" alt="Steam Workshop downloads"></a> ![Build Status](https://github.com/siramok/treasure-room-start/actions/workflows/ci.yml/badge.svg)

Treasure Room Start is a mod for [_The Binding of Isaac: Repentance_](https://store.steampowered.com/app/1426300/The_Binding_of_Isaac_Repentance/), written in [TypeScript](https://www.typescriptlang.org/) using the [IsaacScript](https://isaacscript.github.io/) framework. It will automatically restart new runs until you start next to a desired room type or with a desired floor curse.

## Features

- Automatically start new runs next to particular room types (treasure and planetarium rooms enabled by default).
- Automatically start new runs with particular floor curses (all enabled by default, like the vanilla game).
- Preserves your run streak.
- Also works when manually holding R to restart runs, or when victory lapping.
- Compatibility with [Beyond](url=https://steamcommunity.com/sharedfiles/filedetails/?id=2681875787) modded characters.

## How To Play

As of the latest update, this mod requires that you own the [Repentance DLC](https://store.steampowered.com/app/1426300/The_Binding_of_Isaac_Repentance/). You can play by subscribing to this mod on [the Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=2560433301). (Subscribing to the mod will automatically download and install it once you launch the game.)

## How To Compile

If you are a developer and want to build the mod yourself, perform the following steps:

- Download and install [Node.js](https://nodejs.org/en/download/) (Windows Installer .msi, 64-bit).
- Download and install [Git](https://git-scm.com/download/win) (64-bit Git for Windows setup).
- Download (or clone) this repository:
  - Click on the "Code" button in the top-right-corner of this page.
  - Click on "Download ZIP".
- Unzip the zip file to a new directory.
- Open the command prompt (or another shell of your choice).
- Use the `cd` command to navigate to the place where you unzipped the repository.
- Use the `pnpm install --frozen-lockfile` command to install the project dependencies.
- Use the `npx isaacscript` command to start the IsaacScript watcher.
- If IsaacScript is successful, you will see "Compilation successful." (You can continue to leave the terminal window open; it will monitor for changes in your project, and recompile if necessary.)
- Completely close Isaac if it is already open, and then open the game again, and the mod should be in the list of mods. You can now play or test the mod.
