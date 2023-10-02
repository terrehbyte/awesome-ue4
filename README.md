# Awesome UE4

This is a curated collection of articles, assets, and libraries that have
been created for use with Unreal Engine 4.

Suggestions and recommendations are welcome to be filed via the GitHub issue
tracker for this repository. For more information, see the
[contribution guidelines](CONTRIBUTING.md).

Inspired by [awesome-unity](https://github.com/RyanNielson/awesome-unity),
[awesome-design](https://github.com/gztchan/awesome-design),
[awesome-cpp](https://github.com/fffaraz/awesome-cpp).

**Contents**

- [Awesome UE4](#awesome-ue4)
  - [Assets](#assets)
    - [3D Modeling and Tools](#3d-modeling-and-tools)
    - [Analytics](#analytics)
    - [Animations](#animations)
    - [Artificial Intelligence](#artificial-intelligence)
    - [Audio](#audio)
    - [Build](#build)
    - [Editor Extensions](#editor-extensions)
    - [Forks](#forks)
    - [Gameplay](#gameplay)
    - [Networking](#networking)
    - [Sample Projects](#sample-projects)
    - [Scripting](#scripting)
    - [User Interface](#user-interface)
    - [Utilities](#utilities)
  - [Resources](#resources)
    - [Coding](#coding)
    - [General](#general)
    - [Style and Conventions](#style-and-conventions)
- [License](#license)

## Assets

### 3D Modeling and Tools
- [ARTv1](https://www.unrealengine.com/marketplace/maya-tools) - Specialized tools and scripts for use with Autodesk Maya.
- [ARTv2](https://www.jeremyernst.com/artv2) - Experimental scripts for skeleton, rig, and animation authoring in Autodesk Maya.
- [VelocityGridExport](https://www.orbolt.com/asset/Benny::UE4_velocitygridexporter) - A tool to export vector fields out of Houdini.

### Analytics
- [GameAnalytics Integration](https://github.com/GameAnalytics/GA-SDK-UNREAL) - Plugin for integrating with GameAnalytics services.

### Animations
- [Animation Starter Pack](https://www.unrealengine.com/marketplace/animation-starter-pack) - A basic set of character animations for humanoid shooters.

### Artificial Intelligence
- [tensorflow-ue4](https://github.com/getnamo/tensorflow-ue4) - Train and use TensorFlow in your UE4 project

### Audio
- [FMOD UE4 Integration](https://www.fmod.com/resources/documentation-ue4?version=2.1&page=welcome.html) - Plugin for integrating FMOD assets for realtime playback in-engine.
- [Wwise Unreal Plug-in](https://www.audiokinetic.com/library/edge/?source=UE4&id=index.html) - Plugin for integrating Wwise assets for realtime playback in-engine.

### Build
- [LoadingScreen](https://github.com/ue4plugins/LoadingScreen) - Plugin for creating simple loading screens with movies and advice text.

### Forks
- [NVIDIA GameWorks](https://github.com/NvPhysX/UnrealEngine) - A fork of UE4 offering various integrations of NVIDIA's GameWorks package.
  - Note: Your GitHub account must be a part of the [Epic Games organization](https://www.unrealengine.com/ue4-on-github) in order to view this.

### Gameplay
- [ue4-targetsystemplugin](https://github.com/mklabs/ue4-targetsystemplugin) - Dark Souls inspired lock-on/targeting system for cameras
- [PBCharacterMovement](https://github.com/ProjectBorealis/PBCharacterMovement) - Recreation of HL2 movement in UE4 (from Project Borealis)
- [OpenLand](https://github.com/GameDev4K/unreal-open-land) - An OpenSource Unreal Landscape Auto Material

### Networking
- [Epic Online Services](https://dev.epicgames.com/en-US/services) - Leverage Epic's game services for your own game (e.g. analytics, player data, player help desk, matchmaking)
- [PingPlugin](https://github.com/DescendentStudios/PingPlugin) - ICMP ping hosts with Blueprint nodes
- [TwitchAuth](https://github.com/fivefingergames/TwitchAuth) - In-game Twitch authentication plugin
- [VaRest](https://github.com/ufna/VaRest) - A simple REST API client with support for automatic JSON deserialization.

### Editor Extensions
- [UE4GitPlugin](https://github.com/SRombauts/UE4GitPlugin) - Integrates Git as a source control provider.
  - The initial release, v1, was integrated into the engine in engine version 4.7.
- [UE4PlasticPlugin](https://github.com/SRombauts/UE4PlasticPlugin) - Integrates PlasticSCM as a source control provider.
- [UnrealFastNoise](https://github.com/midgen/UnrealFastNoise) - A runtime noise generation plugin based on the excellent [FastNoise from Auburns](https://github.com/Auburns/FastNoise).

### Sample Projects
- [Epic Games' Learning Resources](docs/epicsamples.md) - Sample content and projects provided by Epic Games.
- [Epic Survival Game Series](https://github.com/tomlooman/EpicSurvivalGameSeries) - C++-based survival game project - completed version of [Tom Looman's tutorial](https://www.tomlooman.com/survival-sample-game-for-ue4/section-one/)

### Scripting
- [SkookumScript](https://github.com/EpicSkookumScript/SkookumScript-Plugin) - Plugin for integrating SkookumScript as a scripting language.
- [Unreal.js](https://github.com/ncsoft/Unreal.js) - Plugin for integrating JavaScript as a scripting language.
- [UnrealEnginePython](https://github.com/20tab/UnrealEnginePython) - Plugin for integrating Python as a scripting language.

### Utilities
- [BlueprintUE](https://blueprintue.com/) - Paste and share UE Blueprints with others (like Pastebin, but for your Blueprints)
- [Joy Machine's Repo of _Things_](https://github.com/joymachinegames/joymachine-public) - Collection of modular gameplay scripts for UE4 and tools relating to game development.
- [UE4 Console Variables and Commands](https://digilander.libero.it//ZioYuri78/) - Quick reference for CVars and Commands available in stock UE4 with help text

## Resources

### Coding
- [C++ Coding Standard](https://docs.unrealengine.com/latest/INT/Programming/Development/CodingStandard/index.html) - The Epic Games C++ Coding Standard.
- [Gameplay Framework Reference](https://docs.unrealengine.com/latest/INT/Gameplay/Framework/QuickReference/index.html) - A high-level view of the concepts you'll work with in UE4.
- [GASContent](https://github.com/Pantong51/GASContent) - Collection of notes and references for working with UE4's Gameplay Ability System
- [Setting Up Visual Studio for UE4](https://docs.unrealengine.com/latest/INT/Programming/Development/VisualStudioSetup/index.html) - A guide for installing and configuring the advanced Unreal Build Tool. (UBT)
- [SubsystemBrowserPlugin](https://github.com/aquanox/SubsystemBrowserPlugin) - Exposes subsystem properties to the editor
- [ue4-gitignore](https://github.com/MOZGIII/ue4-gitignore) - Example `.gitignore`, `.gitattributes` configuration for UE4 development with Git LFS
- [Unreal Engine 4 for Unity Developers](https://docs.unrealengine.com/latest/INT/GettingStarted/FromUnity/) - A mapping of Unity3D concepts to Unreal Engine 4 concepts.
- [Unreal Engine 4 Network Compendium](http://cedric-neukirchen.net/2017/02/14/multiplayer-network-compendium/) - A guide for authoring networked gameplay in Unreal.

### General
- [Community Content, Tools and Tutorials](https://forums.unrealengine.com/forumdisplay.php?12-Community-Content-Tools-and-Tutorials) - The community resources pool on the Unreal Engine forums.
- [Unreal C++](https://unrealcpp.com/) - A large collection of tutorials covering common features implemented in C++
  - [Harrison/unrealcpp](https://github.com/Harrison1/unrealcpp) contains source code for all of the tutorials contained above
- [Unreal Development Guides and Tips](https://github.com/JaredP94/Unreal-Development-Guides-and-Tips) - Collection of tutorials from basic to optimizing your code and your development workflow with UE4
- [Unreal Engine Blog](https://www.unrealengine.com/en-US/feed/all) - Main feed for all news relating to Unreal Engine
  - [Unreal Engine Technology](https://www.unrealengine.com/en-US/feed/tech-blog) - Deep-dives and technical showcases on features or strategies used by select studios
- [UnrealSlackers](http://unrealslackers.org/) - A Discord community of individuals working in UE4
- [Reuben Ward](https://www.youtube.com/c/ReubenWardTutorials/) - Reuben provides both short and long-form tutorials covering a variety of topics involving gameplay and related systems
- [Tom Looman](https://www.tomlooman.com/) - Tom's blog provides a mixture of tutorials and personal development updates on the work he's doing

### Style and Conventions
- [UE4 Style Guide](https://github.com/Allar/ue4-style-guide) - A reference style guide for organizing and naming your project and code.

# License

This is also reflected in [LICENSE.md](LICENSE.md) for visibility.

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Terry Nguyen](https://terrehbyte.com) has
waived all copyright and related or neighboring rights to this work.
