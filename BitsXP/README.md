# BitsXP

This is a custom-written (from scratch) version of expmon for Ashita (Windower doesn't have great EXP addons).

## Preview

![BitsXP](./docs/addon-picture.png)

## Installation

Download this repository and copy + paste the `BitsXP` folder into your Windower addons folder.

## Commands

- `//bxp reset` - Resets the XP session
- `//bxp reload` - Reloads the addon
- `//bxp unload` - Unloads the addon completely
- `//bxp toggle` - Toggles the visibility of the addon
- `//bxp help` - Displays the help information for this addon

## Notes

- There is an option called `resetOnPartyAccept` which does exactly that, it's set to true by default.
- Most things are adjustable in the settings, text colors are probably not.
- If there are issues, please feel free to open an issue on this repository.

## Todo

- Add chaining logic
- Fix 60 minute+ sessions; for example, if there is a 75 minute session, the first 15 minutes should be ignored when calculating the exp / hr.
