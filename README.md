# Ship Info Screen (Settlers MyDU Fork)

A heavily modified version of Krengus's Ship Info script, updated with a comprehensive database for all custom fuel tanks on the Settlers MyDU server.

![Main Screen](https://github.com/Krengus/DU_ASTco/assets/93654396/f5942dd9-d864-43f1-9010-5adca121ee92)

## Table of Contents
- [Installation](#installation)
- [About This Fork](#about-this-fork)
- [Core Features](#core-features)
- [Screenshots](#screenshots)
- [Changelog](#changelog)
- [Credits](#credits)

## Installation
1. Link your Core, Databank, Screen(s), and Hub(s) to the programming board in any order.
2. Paste the script and apply the changes.

## About This Fork
This is a fork of the original Ship Info script by Krengus, specifically adapted to work with the wide variety of custom fuel tanks found on the **Settlers MyDU Server**.

The primary focus of this version was to completely rewrite the fuel tank identification system. The original script could not recognize the different rarities and types of modded tanks. This version now includes a robust database and logic to accurately identify over 100 different tank variants by checking their generic name and unique Max HP values, ensuring correct capacity and weight calculations.

## Core Features
- Supports up to 4 linked container hubs.
- Main screen with detailed monitoring for all fuel tanks and hubs.
- Tracks various weight info: container hubs, fuel, docked constructs, and boarded players.
- Repair screen to help locate damaged elements.
- Docked construct screen to view and undock constructs.
- Boarded players screen to view and deboard players.
- Full touch screen and multi-screen support.
- Uses a Databank for persistence between sessions.

## Screenshots
<p align="center">
  <img src="https://user-images.githubusercontent.com/93654396/148534290-fe6fad69-54af-4dc9-9dfb-1d578c011862.png" width="49%">
  <img src="https://user-images.githubusercontent.com/93654396/148816214-c93df243-e73f-4ee8-b8f2-36b6d7978b81.png" width="49%">
  <img src="https://user-images.githubusercontent.com/93654396/148828635-d335d96a-49cf-42af-b739-a87f0670adb7.png" width="49%">
</p>

## Changelog

### v0.1.0 (This Fork - 2025-10-06)
*Updated by kolden*
- **Complete Fuel Tank System Rewrite:**
    - Replaced the original identification logic with a robust system that checks a tank's generic name and its unique Max HP to determine its size and type.
    - Added a comprehensive database containing verified stats (Max HP, Max Volume, Empty Weight) for **all 112 custom fuel tank variants** on the Settlers MyDU server.
    - Corrected all hardcoded data to match verified spreadsheet values, ensuring accurate fuel calculations.
    - Implemented shortened, readable labels for all tank types to improve UI clarity.
- **Calibration:**
    - Added a small calibration adjustment (-5kg) to all empty tank weights to correct for minor discrepancies and prevent negative fuel readings when empty.

---

### Original Script Changes
*Updated by tobitege, 2024-05-30*
- **v0.758** - Fix rocket tank capacity calculation (10% not 20% per talent level).
- **v0.757** - Fix damage status display: ignore < 0.01 hitpoints as this isn't repairable.

## Credits

### Original Author
- This script was originally written and maintained by **Krengus**. All credit for the foundational script and UI goes to him.

### Special Thanks
- To **SilverZero** for his awesome work on modern screen flair, which has been an inspiration. You can find his work [here](https://github.com/d6rks1lv3rz3r0/DU-Modern-Screen-Flair/tree/main).
