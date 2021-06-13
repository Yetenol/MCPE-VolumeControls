# Hot to use the volume key to control Minecraft Pocket Edition

## Motivation and my current setup:
Key | Press variant | Action
--- | --- | ---
`Volume up` | short press | `Use item/Place block`
`Volume up` | multiple presses | Repeat `Use item/Place block`
`Volume up` | hold down | `Use item/Place block` every 50ms (customizable)
`Volume down` | single press | `PICK BLOCK`
`Volume down` | long press + hold down | `CROUCH` / `FLY DOWN` <br> Moves entire stack between containers <br> 

## Requirements

## Setup KeyMapper
Download [Key Mapper](https://play.google.com/store/apps/details?id=io.github.sds100.keymapper) from Google Play Store

Apply the following fixes:
* Enable accessability service
* Enable Key Mapper keyboard
* Disable battery optimisation
* Grant permission to change Do Not Disturb mode

Not required:
* Some features need WRITE_SECURE_SETTINGS

Import [keymap_list.json](keymap_list.json)

## Setup Minecraft Pocket Edition
* Switch to keyboard `Key Mapper Basic Input Method`
* Launch Minecraft
* Navigate to `Settings > Keyboard & Mouse`
>* Tap the button next to `Pick Block` (default is Button3)
>* Short press `Volume down`
>* If `PAGE DOWN` is entered everything worked great
>* If nothing happens restart the device and make sure to use the correct keyboard

>* Tap the button next to `Use Item\Place Block` (default is Button2)
>* Short press `Volume up`
>* If `PAGE UP` is entered everything worked great

* Test the controls