# SDT HKS Repository
Contains pre-configured HKS files for Sekiro: Shadows Die Twice.

HKS (HavokScript) files act as a interface script between inputs and animations, controlling the 'behavior' of the source entity
- **c0000.hks**: the script for the player character.
- **c9997.hks**: the generic script for all enemy characters.

These HKS files were decompiled with katalash's [DSLuaDecompiler](https://github.com/katalash/DSLuaDecompiler) and then tweaked to include and use global variables for all the ENV and ACT commands, making it a lot easier to understand the scripts.

# Credits
- katalash: DSLuaDecompiler
- Vawser: conversion of the ENV and ACT variables, inclusion of helper functions.
