# GitHub Copilot Commands

## Project Overview

This repository is a decompilation project for **Pokémon Platinum**, a role-playing video game developed by Game Freak and published by Nintendo and The Pokémon Company. Pokémon Platinum was released for the **Nintendo DS** handheld console in 2008.

## Platform Details

- **Game Title:** Pokémon Platinum
- **Platform:** Nintendo DS
- **Release Year:** 2008
- **Developer:** Game Freak
- **Publisher:** Nintendo, The Pokémon Company

## Technical Details

- **Architecture:** ARM (ARM9 and ARM7 processors)
- **Operating System:** Nintendo DS firmware
- **Languages Used:** Primarily C, with some assembly for hardware-specific routines
- **Project Goal:** To reverse-engineer and reconstruct the source code of Pokémon Platinum, making it readable, modifiable, and buildable from source.

## Repository Structure

- `src/` — Contains decompiled C source files - THIS IS VERY IMPORTANT
- `asm/` — Contains assembly code and macros
- `include/` — Header files
- `build/` — Build outputs and binaries - IGNORE THIS IN ALMOST EVERY CASE
- `tools/` — Utility scripts and build tools
- `docs/` — Documentation - THIS IS VERY IMPORTANT

## How to Use

This project is intended for research, preservation, and educational purposes. It allows enthusiasts to study the inner workings of Pokémon Platinum, contribute improvements, and potentially port or modify the game.

## Getting Started

1. Clone the repository.
2. Follow the instructions in `INSTALL.md` to set up your build environment.
3. Use the provided build scripts (`Makefile`, `meson.build`) to compile the project.

## Legal Notice

This project is a fan-driven effort and is not affiliated with or endorsed by Nintendo, Game Freak, or The Pokémon Company. Please respect copyright laws and use this code responsibly.
