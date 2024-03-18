# SteamOS-alternatives-overview
SteamOS-alternatives-overview intends to provide an quick glance at the main differences between the Linux distributions offering an experience similar to Steam OS (Steam Deck's OS).

# Table of Contents
1. [Distribution Overview](https://github.com/berserkwarwolf/steamos-alternatives-overview#distribution-overview)
2. [Emoji Definitions](https://github.com/berserkwarwolf/steamos-alternatives-overview#emoji-definitions)
3. [How to Contribute (WIP)](https://github.com/berserkwarwolf/steamos-alternatives-overview#how-to-contribute-wip)

# Distribution Overview

|                                   | ChimeraOS          | SteamOS 3.x        | HoloISO           |Nobara            |Bazzite
| --------------------------------- | ------------------ | ------------------ | ------------------|------------------|------------------|
| Based on                          | Arch Linux         | Arch Linux         | Arch Linux        | Fedora Linux     | Fedora Atomic    |
| Desktop                           | Gnome              | KDE Plasma         | KDE Plasma        | KDE Plasma       | Gnome/KDE Plasma |
| Install method                    | ❔                | :x:                | ❔                |❔                |❔               |
| Atomic updates                    | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:|:x:               |:heavy_check_mark:|
| Read-write root filesystem        | :x:                | :x:                | :x:               |:heavy_check_mark:|:x:               |
| Custom partitioning               | :x:                | :x:                | :x:               |:heavy_check_mark:|:x:               |
| General hardware support          | :heavy_check_mark: | :x:                | :heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
| Up-to-date base packages          | :heavy_check_mark: | :x:                | :x:               |:heavy_check_mark:|:heavy_check_mark:|
| Remote app installation           | :heavy_check_mark: | :x:                | :x:               |                  |:x:               |
| Built-in EGS & GOG support        | :heavy_check_mark: | :x:                | :x:               |                  |:heavy_check_mark:|
| Built-in emulation support        | :heavy_check_mark: | :x:                | :x:               |                  |:x:               |
| Additional game tweaks            | :heavy_check_mark: | :x:                | :x:               |                  |:heavy_check_mark:|
| Additional artwork                | :heavy_check_mark: | :x:                | :x:               |                  |:x:               |
| Built-in GE Proton                | :heavy_check_mark: | :x:                | :x:               |:heavy_check_mark:|:heavy_check_mark:|
| TDP Control                       | :heavy_check_mark: | :heavy_check_mark: | ❔               |❔                |❔                |
| FPS Limiter                       | :heavy_check_mark: | :heavy_check_mark: | :x:               |:heavy_check_mark:|:heavy_check_mark:|
| Built-in Nvidia GPU Support       | :x:                | ⚪                | :x:               |:x:                |:heavy_check_mark:|
| Automated builds                  | :heavy_check_mark: | ⚪                | ❔               |❔                |❔                |
| TDP Control                       | :heavy_check_mark: | :x:                | :x:               |:heavy_check_mark:|:heavy_check_mark:|
| Full source publicly hosted       | :heavy_check_mark: | :x:                | :x:               |:heavy_check_mark:|:heavy_check_mark:|

# Emoji Definitions
✔️ means yes, it is supported
❌ means no, it is not supported
❔ means help wanted, author wasn't sure or couldn't judge the covered topic.
⚪ means the feature doesn't apply to this distribution and cannot be evaluated.
an empty cell is missing information. It is not intentionally left blank.

# Footnotes
WIP

# How to Contribute (WIP)
work in an editor that supports no forced line breaks (word wrap), otherwise you can't read the raw markdown table. VSCodium, Atom, Notepad++, Kate and others are suitable for raw markdown editing.

work in an editor that supports some sort of WYSIWYG like Obsidian or Typora otherwise it is a real mess to fill a markdown table. Typora can clean the final raw markdown table as well, and so can Obsidian with the Advanced Tables plugin.

To add a service it is always good to take the current version of the table to match the columns. I'll try to merge all PRs in a timely manner.

open issue or a PR

# Credits & acknowledgements
Thanks to the ChimeraOS project for most of the information found on the table, and selfhosted-music-overview for the structure inspiration.
