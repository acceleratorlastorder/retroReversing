---
layout: post
tags: 
- gamecube
- symbols
- debug
- reverseengineering
title: Nintendo Gamecube Games with Debug Symbols
thumbnail: /public/consoles/Nintendo Gamecube.png
image: /public/consoles/Nintendo Gamecube.png
permalink: /gamecube-debug-symbols
breadcrumbs:
  - name: Home
    url: /
  - name: Nintendo Gamecube 
    url: /gamecube
  - name: Nintendo Gamecube Games with Debug Symbols
    url: #
recommend: gamecube
editlink: /gamecube/GamecubeDebugSymbols.md
---

Gamecube game executable can come in a number of different formats, one is the standard .DOL file (short for dolphin) and the other is the ELF.



# ELF Files

ELF files can contain many debug symbols such as the function, variable and sometimes even file names.

You can normally see the symbols by opening in a dissasembler such as Radare2 or IDA Pro.

## ELF Executables with Debug Symbols

Game Name | Elf File | Number of Symbols | Genre | Youtube
--- | --- | --- | --- | ---
Les Désastreuses Aventures des Orphelins Baudelaire | main.elf | **10,416** | Platformer | 
Disney-Pixar Die Unglaublichen (The Incredibles) (Germany) (Disc 1) | ingc_m.elf | **13,931** | Action | 
Disney's Piglet's Big Game (United Kingdom) | Piglet.elf | **7,951** | Action | 
Finding Nemo (United Kingdom) | GCNemo.elf | **5,600**
Freedom Fighters (United Kingdom) | startup_release.elf | **16,664** | Third-person shooter | 
Frogger Beyond | Frogger.elf | **4,561** | Action | https://www.youtube.com/watch?v=t0DptiBTWPI

# Link Maps
Many Interactive Demo Discs contain link maps which are files that the linker generates and contains the function names. Also in Final Fantasy Crystal Chronicals.

Game Name | Map File | Number of Symbols | Genre | Youtube
--- | --- | --- | --- | ---
Final Fantasy - Crystal Chronicles | dvd/map/stg009/game.MAP | ? | RPG | 