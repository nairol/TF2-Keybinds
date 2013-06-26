# TF2-Keybinds

A set of class specific scripts for Team Fortress 2.

## General Layout

Keys    | Action
------- | ------
W A S D | Movement
SHIFT   | Duck
TODO    | TODO

## Installation

There are two ways to get the cfg files into your game:

### Simple copy and paste

Make a new folder called "my-keybinds" (or something else) in the "custom" subfolder of TF2:
`PATH\TO\STEAM\SteamApps\common\Team Fortress 2\tf\custom\my-keybinds`

Then copy the cfg folder from this repository into the new folder.

### Transparent folder link ("NTFS Junction")

You might want to set up "Junctions" in your file system to keep the TF2 cfg folder in sync with this repository.

On the command line (cmd.exe) run the following command with the paths adjusted to your file system layout:
`mklink /j "PATH\TO\STEAM\SteamApps\common\Team Fortress 2\tf\custom\my-keybinds" "PATH\TO\THIS\REPOSITORY"`
