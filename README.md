# Mud Designer Home

The Mud Designer is a cross-platform multi-user-dungeon game engine that is currently under development. The goal of the engine is to provide a cross-platform MUD engine that ships with a solid set of extensible tools that may be used to build text based MMORPG games.

### What is this repo
---
This repository is the home of the Mud Designer. The Mud Designer is being built from the ground up with extensibility support in mind. The core engine is very light and is not responsible for most of the actual game play. Instead, a game is made up of a series of plugins, with each plugin having their own repository here on Github. You can find all of the repositories associated to the Mud Designer below.

While this project is not very large, I found that having a repository for each of the major components helps enforce lose coupling and increase how extensible the engine actually is.

### The Repositories
---
##### Core engine components
- [The Mud Engine](https://github.com/MudDesigner/MudEngine)

##### Adapters
- [Windows Server: deprecated and will soon be removed](https://github.com/MudDesigner/MudServerAdapter.Windows)
- [Cross-platform server](https://github.com/MudDesigner/Adapter.MudServer/tree/dev-server)

### Documentation
---
There are two types of documentation planned. [Usage documentation](http://muddesigner.readthedocs.org/en/latest/) and API documentation. The API documentation will come at a later date.

If you would like to help out with the usage documentation, feel free to [take a look at the documentation source](https://github.com/MudDesigner/Docs) and issue pull requests!
