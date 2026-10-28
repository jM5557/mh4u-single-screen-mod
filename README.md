# Monster Hunter 4 Ultimate - Single-Screen Mod

**AI Disclaimer:** Mod generation done by Claude.ai alongside manual testing via iterative development

# NOTE

This project is a work in progress and being tested as development progresses. It is essentially in an alpha release state, so expect bugs or layouts that are subject to change. We welcome any feedback or bug reports submitted as issues.

# Compatibility

Monster Hunter 4 Ultimate - USA v1.1 (or v1.3.0) [Title ID: 0004000000126300]

Tested on AzaharPlus on Android and SteamOS (other emulators supporting Mods may be possible)

Currently untested on Native PC recompilations.


# Installation

On your emulator of choice open the emulation folder and add the two folders in this repo into your `mods` folder:
- 0004000000126300
- 0004000E00126300

To update, delete these folders and copy them over to the `mods` folder

# Features/Improvements

- **New** Main Menu: Main menu button prompts are now relocated to the top screen

- **New** Wycoon: Wycoon menus are now relocated to the top screen (layout, spacing, and sizing subject to change)

- Quest Lists: The quest list is now positioned on the same top screen as the Quest details pages. This applies to both the Guildmarm's quest lists across all villages and to the Gathering Hub and Elder Hall quest counters.

- World Map: The world map can now be toggled by pressing L+R while in villages and takes up the top-screen (fully controller navigateable and touch-responsive on touch screens)

- Target Cam: The target cam(s) are now visible on the top-screen below the map/above the item bar. These are hidden when the HUD is set to hidden.

- Kitchen/Food Menu: All kitchen/food menus are now displayed on the top-screen side-by-side

- Arena Quests: 
  - For the Arena Bambina's quest list, press the `Select` button to display/hide your leaderboard/timing statistics. 
  - Arena Bambina's quest's main menu was moved from the bottom screen to fill the top screen
  - Arena quest weapon selection screen has the weapon icons/buttons displaying on the top screen
  - Prompt to confirm your weapon selection now displays on the top screen

- Confirmation Buttons: Buttons for "OK", "Cancel" ... etc. are now displayed at the bottom-right corner of the top screen when certain menus are open.
These can be "hidden" by reverting them to the bottom screen by pressing L+R. Press L+R again to have these display on the top-screen again.

# Known Issues

- Main menu character select menu overlaps the Palico in the player model view. Future work will entail shifting the player/palico models over to the right.
- On touch screens the Arena quest prep screens at the top screen replicates the bottom touch screen.
