# Skyrim Open Behavior Alliance
This repo is used to track changes between mods as well as providing standards in behavior modification in xml format.


## Why SOBA?
In skyrim modding community, most people just do their own thing without the need to bother any other people. However, behavior modification is different due to the behavior related data is stored in several files and modification to it can only be done by modifying it making 1 mod in compatible with another mod changing the same file.

This issue can be solved by [Nemesis Unlimited Behavior Tool](https://github.com/ShikyoKira/Project-New-Reign---Nemesis-Main). However, this is not enough as it only fragmentizes the behavior structure and link them through a strict rule within the system. The base data is still subjected to conflict between mods. While Nemesis can its own conflict resolution method, still only the `winning` modification will be present in the end. Therefore, we have established SOBA to provide a standard in the behavior modification throughout the modding community to minimize conflict.

SOBA includes providing standardized fixes and modifications, so that modders do not need to do the same work previously done by others. Modders can also use this platform github to collaborate and work on bigger projects


## How to use this repo?
Before you start making any modification, start by forking this repository and then make changes to the new fork

### Tweaks/Fixes
Use the [**pull request**](https://www.youtube.com/watch?v=rgbCcBNZcdQ) (click to see how to do it), they will be pull to a new branch

### Specific modification for mod
Fork from this repo. No pull request shall be made. All changes made shall be kept in the other fork.

### Incorporate fixes with your mod
Pull the branch (with the fix you want to incorporate) from the this upstream repository, merge it and then push it to your repository
