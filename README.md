<h1> <a href="https://reaper.fm"><img src="assets/awesome-reaper.svg" alt="Awesome Reaper logo" width="600"/></a><a href="https://awesome.re"><img align="right" src="https://awesome.re/badge.svg"></a> </h1>

> [Reaper](https://reaper.fm/) is a proprietary digital audio production application, offering a full multitrack audio and MIDI recording, editing, processing, mixing and mastering toolset.\
> Reaper supports a vast range of hardware, digital formats and plugins, and can be comprehensively extended, scripted and modified.

**A curated list of Reaper resources, scripts, extensions, JSFX, software and community links.**

# Contributing

This project promotes freely-available resources and content and can't be used as an advertisement platform for a commercial product. We welcome everything which meets our [quality standards](CONTRIBUTING.md#quality-standards), such as:

* Free Software / Open Source programs, libraries, extensions and scripts.
* Non-paywalled media, videos, podcasts, articles.
* Freely distributed books, courses, etc.

See [`CONTRIBUTING.md`](CONTRIBUTING.md) file for details on [Quality standards](CONTRIBUTING.md#quality-standards), [Contribution](CONTRIBUTING.md#contribution-guidelines) and  [Commit and Pull Request](CONTRIBUTING.md#commit-and-pull-request-guidelines) guidelines as well as a [primer on Git-based collaboration](CONTRIBUTING.md#git-basics).

# Contents

* [Extensions](#extensions)
* [Software and tools](#software-and-tools)
* [JSFX](#jsfx)
* [Scripts](#scripts)
* [Video Editing](#video-editing)
* [Scripting and JSFX development](#scripting-and-jsfx-development)
  * [General resources](#general-resources)
  * [JSFX / EEL2 resources](#jsfx--eel2-resources)
  * [Lua resources](#lua-resources)
  * [Python resources](#python-resources)
* [Developer resources](#developer-resources)
  * [Development tools](#development-tools)
  * [Documentation](#documentation)
    * [General documentation and resources](#general-documentation-and-resources)
  * [Libraries](#libraries)
    * [JavaScript/TypeScript](#javascripttypescript)
    * [Nim](#nim)
    * [Python](#python)
    * [Rust](#rust)
* [Learning](#learning)
  * [Articles](#articles)
  * [Books](#books)
  * [Videos](#videos)
* [Community](#community)
  * [Forums](#forums)
  * [Chats](#chats)
    * [Discord](#discord)
    * [Matrix](#matrix)
* [Web sites](#web-sites)

## Extensions

* [SWS / S\&M extension](https://www.sws-extension.org/) - A collection of features that seamlessly integrate into Reaper. A collaborative and open source project. [Repo](https://github.com/reaper-oss/sws) ⭐ 570 | 🐛 501 | 🌐 C++ | 📅 2026-05-10, [Forum thread](https://forums.cockos.com/showthread.php?t=29640).
* [ReaPack](https://reapack.com/) - Package manager for Reaper. Discover, install and keep up to date your Reaper resources. [Repo](https://github.com/cfillion/reapack) ⚠️ Archived, [Forum thread](https://forum.cockos.com/showthread.php?t=177978).
* [OSARA](https://osara.reaperaccessibility.com/) - REAPER extension which aims to make REAPER accessible to screen reader users. A collaborative and open source project. [Repo](https://github.com/jcsteh/osara) ⭐ 156 | 🐛 165 | 🌐 C++ | 📅 2026-08-09.
* [ReaLlm](https://github.com/ak5k/reallm) ⭐ 23 | 🐛 0 | 🌐 C++ | 📅 2026-07-20 - Low latency monitoring plug-in extension (automatically bypass plugins adding latency). [Forum thread](https://forum.cockos.com/showthread.php?t=245445).

## Software and tools

* [ReaBoot](https://reaboot.com/) - A convenient all-in-one online installer for REAPER, ReaPack and arbitrary packages by Helgoboss. [Repo](https://github.com/helgoboss/reaboot) ⭐ 11 | 🐛 5 | 🌐 Rust | 📅 2026-03-02, [Forum thread](https://forums.cockos.com/showthread.php?p=2773571)

## JSFX

* [JoepVanlier/JSFX](https://github.com/JoepVanlier/JSFX) ⭐ 628 | 🐛 11 | 🌐 Lua | 📅 2026-08-09 - A bundle of JSFX and scripts by Joep Vanlier (aka saike).
* [TukanStudios/JSFX](https://stash.reaper.fm/v/43504/TUKANPLUGINS.png) - A bundle of JSFX by John Matthews (Tukan Studios). [Repo](https://github.com/TukanStudios/TUKAN_STUDIOS_PLUGINS) ⭐ 357 | 🐛 24 | 🌐 HTML | 📅 2026-04-29, [Youtube](https://www.youtube.com/@johnmatthews8435) [forum thread](https://forums.cockos.com/showthread.php?p=2506848).
* [geraintluff/jsfx](https://geraintluff.github.io/jsfx/) - Collection of JSFX effects by Geraint Luff (aka geraintluff). [Repo](https://github.com/geraintluff/jsfx) ⭐ 222 | 🐛 5 | 🌐 HTML | 📅 2023-07-31, [Youtube playlist](https://www.youtube.com/watch?v=QLh6b88OvFs\&list=PLflIiXZOocKqgKexrkTxxtl6igGUWnpXK), [forum thread](https://forums.cockos.com/showthread.php?t=186554).

## Scripts

* [ReaTeam ReaScripts](https://github.com/ReaTeam/ReaScripts) ⭐ 400 | 🐛 23 | 🌐 Lua | 📅 2026-07-31 - Community-maintained collection of scripts for REAPER
* [Stem Manager](https://forum.cockos.com/showthread.php?t=268512) - Easily create stems by saving and recalling multiple sets of solo and mute states, run different sets of rules and actions for rendering, control render queue. [Repo](https://github.com/odedd/ReaScripts/) ⭐ 4 | 🐛 1 | 🌐 Lua | 📅 2026-01-04.

## Video Editing

* [ogler](https://github.com/frabert/ogler) ⭐ 15 | 🐛 4 | 🌐 C++ | 📅 2023-11-23 - VST plugin for writing video processing effects using GLSL shaders in Reaper. [Forum thread](https://forums.cockos.com/showthread.php?t=278451).

## Scripting and JSFX development

### General resources

* [ReaImGui](https://github.com/cfillion/reaimgui) ⚠️ Archived - ReaImGui: ReaScript binding for Dear ImGui.
* [ReaScripts-Templates](https://github.com/ReaTeam/ReaScripts-Templates) ⭐ 89 | 🐛 0 | 🌐 Lua | 📅 2025-01-23 - Templates, models, boilerplates, examples and snippets for REAPER ReaScript, for easier scripts creations. [Forum thread](https://forum.cockos.com/showthread.php?t=172123).
* [ReaImGui Knobs](https://github.com/AntoineBalaine/perken-reaper-scripts/tree/rack/imgui/knobs) ⭐ 7 | 🐛 0 | 🌐 Lua | 📅 2024-05-16 - A port of [imgui-rs-knobs](https://github.com/DGriffin91/imgui-rs-knobs) ⭐ 25 | 🐛 2 | 🌐 Rust | 📅 2022-04-17 to lua for ReaImGui by Antoine Balaine. [Forum thread](https://forums.cockos.com/showthread.php?t=288811).

### JSFX / EEL2 resources

* [CookDSP](http://ajaxsoundstudio.com/cookdspdoc/) - DSP library for JSFX by Olivier Bélanger. [Repo](https://github.com/belangeo/cookdsp) ⭐ 78 | 🐛 8 | 🌐 JavaScript | 📅 2022-03-05.
* [JS2EEL](https://js2eel.org/) - A compiler that enables you to write REAPER JSFX in JavaScript by Daniel Schebesta. [Repo](https://github.com/steeelydan/js2eel) ⭐ 20 | 🐛 0 | 🌐 TypeScript | 📅 2024-08-28. [Forum thread](https://forum.cockos.com/showthread.php?t=282257).
* [CodeBase](https://github.com/VisualCodeBase/CodeBase) ⭐ 12 | 🐛 0 | 📅 2026-03-25 - A "multi in multi out modern compiler" and JSFX/EEL-to-VST Building system. [Forum thread](https://forum.cockos.com/showthread.php?t=245285).

### Lua resources

### Python resources

## Developer resources

### Development tools

* [ReaScript VSCode Extension](https://marketplace.visualstudio.com/items?itemName=AntoineBalaine.reascript-docs) - Reaper's ReaScript API methods in Visual Studio Code. [Forum thread](https://forum.cockos.com/showthread.php?t=247290), [Repo](https://github.com/AntoineBalaine/vscode-reascript-extension) ⭐ 13 | 🐛 3 | 🌐 Lua | 📅 2025-12-12.

### Documentation

* [JSFX API](https://www.reaper.fm/sdk/js/js.php) - The official JSFX API documentation.
* [ReaImGui Documentation](https://api.codetabs.com/v1/proxy/?quest=https://github.com/cfillion/reaimgui/releases/latest/download/reaper_imgui_doc.html) - The official ReaImGui documentation.
* [ReaScript API](https://www.reaper.fm/sdk/reascript/reascripthelp.html) - The official ReaScript API documentation.
* [X-Raym's Reaper Action List](https://www.extremraym.com/cloud/reaper-action-list/) - Interactive web page with the list of available Reaper actions, including internal and a selection of third-party ones. [Forum thread](https://forum.cockos.com/showthread.php?t=273727).
* [X-Raym's Reascript API Documentation](https://www.extremraym.com/cloud/reascript-doc/) - Searchable and easy-to-read list of Reaper ReaScript API functions with common extensions support.

#### General documentation and resources

* [Python Documentation](https://docs.python.org/3) - The official Python documentation. See also [awesome-python/Resources](https://github.com/vinta/awesome-python#resources) ⭐ 313,644 | 🐛 25 | 🌐 Python | 📅 2026-08-05.
* [Lua Documentation](https://www.lua.org/docs.html) - The official Lua documentation. See also: [awesome-lua/Resources](https://github.com/LewisJEllis/awesome-lua#resources) ⭐ 4,550 | 🐛 47 | 📅 2024-08-11.
* [C++ Language Documentation](https://learn.microsoft.com/en-us/cpp/cpp/?view=msvc-170) - The Microsoft C++ documentation.
* [C++ Reference](https://cppreference.com)

### Libraries

#### JavaScript/TypeScript

* [reaper-with-typescript-starter](https://github.com/GavinRay97/reaper-with-typescript-starter) ⭐ 21 | 🐛 0 | 🌐 Lua | 📅 2021-01-08 - JavaScript/TypeScript Reaper API bindings and a script template utilizing the [TypeScriptToLua](https://typescripttolua.github.io/) transpiler. [Forum Thread](https://forum.cockos.com/showthread.php?t=247666).

#### Nim

* [ReaperExtensionNim](https://github.com/Alkamist/ReaperExtensionNim) ⭐ 3 | 🐛 0 | 🌐 Nim | 📅 2023-08-07 - Nim bindings for the Reaper API.

#### Python

* [reapy-boost](https://github.com/Levitanus/reapy-boost) ⭐ 30 | 🐛 5 | 🌐 Python | 📅 2022-12-22 - reapy is a pythonic wrapper around the quite unpythonic ReaScript Python API for Reaper.

#### Rust

* [reaper-rs](https://github.com/helgoboss/reaper-rs) ⭐ 118 | 🐛 25 | 🌐 Rust | 📅 2026-06-17 - Rust bindings for the Reaper C++ API.

## Learning

### Articles

* [AdmiralBumbleBee's tips](https://www.admiralbumblebee.com/tags/?year=false#Reaper) - A wide variety of tips: script showcase, configuration guide, accessibility, ReaScript tutorials.
* [Mix Rescue by Mike Senior](https://www.soundonsound.com/search/all?terms=Mix%20Rescue%20reaper) - A series of educational articles by Mike Senior featuring Reaper extensively.
* [SeventhSam's tutorials](https://seventhsam.com/blogs/tutorials) - Guides on using Reaticulate for managing samples and setting up Reaper's MIDI editor, especially useful for orchestral composers. [Forum thread](https://forum.cockos.com/showthread.php?t=286323).

### Books

* [The Reaper User Guide](https://www.reaper.fm/userguide.php) - By Geoffrey Francis. The essential guide to recording, editing and mixing with Reaper. Over 400 pages.

### Videos

* [Daniel Lumertz Talk](https://www.youtube.com/@daniellumertztalk5989) - ReaScript and adaptive music tutorials. ["How To Reascript" playlist](https://www.youtube.com/playlist?list=PLifav5PqCOlDkw4BmFmAZMmNDL7tSkxvi) ([forum thread](https://forum.cockos.com/showthread.php?t=290071)).
* [IDDQDSound](https://www.youtube.com/@IDDQDSound) - Tutorials, tips, sound design, and scripting.
* [Let's Talk About Reaper](https://www.youtube.com/channel/UCJjlFrOs2btJuErqrNu98Dg) - Myk Robinson's channel. Videos about Reaper, drums, guitar, home studio magic, and more.
* [Reaper Mania](https://www.youtube.com/@REAPERMania) - The home of Kenny Gioia's Reaper Tutorials. [Facebook group](https://www.facebook.com/groups/193889884315689).
* [Reapertips](https://www.youtube.com/@reapertips_plus) - Alejandro Hernandez's YouTube channel. Tips, tricks and tutorials.
* [The Reaper Blog](https://www.youtube.com/c/thereaperblog) - Jon Tidey's YouTube channel. Release news, tips, tricks and tutorials. [Facebook group](https://www.facebook.com/groups/reaperblogcommunity/).
* [X-Raym's Tutorials](https://www.youtube.com/@XRaym) - X-Raym's tutorials, demos and making-of. [ReaScript Course playlist](https://www.youtube.com/playlist?list=PL7M70tQL6s1IOYycGilaHLs5G4vOcyLF8).

## Community

### Forums

* [Cockos Incorporated forums (official)](https://forum.cockos.com/)
* [r/Reaper subreddit](https://www.reddit.com/r/Reaper/) - An unofficial Reddit community for and by users of Reaper.

### Chats

#### Discord

* [Cockos Reaper Users](https://discord.gg/gR2uqTdzej) - An older server by Audbol, originated form the Reaper forums.
* [The Unofficial Reaper Users Group](https://discord.gg/TqBwsaJdWp) - A server started by Myk Robinson from "Let's Talk About Reaper" YouTube channel.

#### Matrix

* [#reaper\_general:matrix.org](https://matrix.to/#/#reaper_general:matrix.org) - General discussion about the Reaper DAW.

# Awesome Web sites with stars

* [ReaLinks](https://www.realinks.net/) - Showcase of tools and stuffs created by user community. Curated by X-Raym.
* [The Reaper Accessibility Wiki](https://reaperaccessibility.com) - A community-maintained wiki written in an accessible format for screen readers. Tips, scripting, and tutorials.

***

<!-- footnotes -->

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-13._
