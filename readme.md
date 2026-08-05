![Downloads](https://img.shields.io/github/downloads/themockster/fvtt-token-action-hud-sf2e/latest/module.zip?color=2b82fc&label=DOWNLOADS&style=for-the-badge)

# Token Action HUD Starfinder 2e

Token Action HUD is a repositionable HUD of actions for a selected token.

This module is a **Starfinder Second Edition** (`sf2e`) port of [Token Action HUD Pathfinder 2e](https://github.com/Larkinabout/fvtt-token-action-hud-pf2e).

# Features
- Make rolls directly from the HUD instead of opening your character sheet.
- Use items from the HUD or right-click an item to open its sheet.
- Move the HUD and choose to expand the menus up or down.
- Unlock the HUD to customise layout and groups per user, and actions per actor.
- Add your own macros, journal entries and roll table compendiums.
- Starfinder-specific support:
  - **Computers** and **Piloting** skills
  - **Resolve Points** resource
  - Skill actions via the SF2e/PF2e `game.pf2e.actions` API (including Hack, Drive, Access Infosphere, etc.)
  - Take a Breather when Stamina/Resolve is available

# Installation

## Method 1
1. On Foundry VTT's **Configuration and Setup** screen, go to **Add-on Modules**
2. Click **Install Module**
3. Search for **Token Action HUD Starfinder 2e**
4. Click **Install** next to the module listing

## Method 2
1. On Foundry VTT's **Configuration and Setup** screen, go to **Add-on Modules**
2. Click **Install Module**
3. In the Manifest URL field, paste:
   ```
   https://github.com/themockster/fvtt-token-action-hud-sf2e/releases/latest/download/module.json
   ```
4. Click **Install**

# Required Modules

## Token Action HUD Core
Token Action HUD Starfinder 2e requires the [Token Action HUD Core](https://foundryvtt.com/packages/token-action-hud-core) module.

## socketlib
Token Action HUD Core requires the [socketlib](https://foundryvtt.com/packages/socketlib) library module.

## Starfinder Second Edition
Requires the official [Starfinder Second Edition](https://foundryvtt.com/packages/sf2e) system for Foundry VTT.

# Recommended Modules
Token Action HUD uses the [Color Picker](https://foundryvtt.com/packages/color-picker) library module for its color picker settings.

# Rules Reference
Starfinder 2e rules content is documented on [Archives of Nethys — Starfinder 2e](https://2e.aonsrd.com/).

# Support

For a guide on using Token Action HUD, go to: [How to Use Token Action HUD](https://github.com/Larkinabout/fvtt-token-action-hud-core/wiki/How-to-Use-Token-Action-HUD)

For questions, feature requests or bug reports, please open an issue on this repository.

Pull requests are welcome. Please include a reason for the request or create an issue before starting one.

# Acknowledgements

Thank you to the Community Helpers on Foundry's Discord who provide tireless support for people seeking help with the HUD.

Based on the original Token Action HUD PF2e work by Larkinabout, Drental, ^ and stick, and Silvertower.

# License

This Foundry VTT module is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/) and this work is licensed under [Foundry Virtual Tabletop EULA - Limited License Agreement for module development](https://foundryvtt.com/article/license/).
