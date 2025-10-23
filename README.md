# Atomic Heart UEVR Plugin
This is a hybrid Lua/PAK mod which adds various UEVR improvements/motion controls to Atomic Heart. The Lua script has been heavily documented for educational purposes.

## VR Mod Features
* 6DOF motion controls.
* Adjusted weapon positions.
* ADS support.  Projectiles are aligned with gun sights.
* Physical melee.
* Floating hands. When holding one-handed items, the off-handed arm is hidden.
* Smooth locomotion. No head bobbing or gun bobbing.
* Activating the Polymer glove will temporarily switch motion controls to the left hand.
* Polymer glove controls remapped to left controller.
* Disable enemy knockback.
* Camera fixes for menus and cutscenes.
* VR fixes for climbing.
* Roomscale movement.
* Remove vignettes.
* Volumetric cloud fix.
* 3D audio fix.
* World map fix.

## Installation
1) Install the nightly build of UEVR from [**HERE**](https://github.com/praydog/UEVR-nightly/releases).
2) Download the latest release of the Atomic Heart UEVR plugin from [**HERE**]. Click "Import Config" in the UEVR UI and navigate to "AtomicHeart-Win64-Shipping.zip" (make sure the filename does not have any numbers in it) and click on it.
3) Navigate to UEVR > Open Global Dir > AtomicHeart-Win64-Shipping > game_folder_files. Move all .pak files to the Atomic Heart \Paks\ folder i.e. C:\Program Files (x86)\Steam\steamapps\common\Atomic Heart\AtomicHeart\Content\Paks
4) Launch Atomic Heart.  Select 'Options' > 'Additional Content' > 'Activate Glove Reskin' and select "Standard".  The Gold Midas Glove does not work properly with this VR mod.
5) Inject the game with UEVR!

## Recommended Mods
* [**UETools**](https://www.nexusmods.com/atomicheart/mods/9): UETools is a powerful mod that brings the developer console back into the game.
* [**Smaller UI and Transparent Inventory Background**](https://www.nexusmods.com/atomicheart/mods/47): Recommend installing "zAHInvBckgr_P" to makes the inventory background 50% transparent.
* [**Unused Dialogues**](https://www.nexusmods.com/atomicheart/mods/147): Restores 199 dialogue lines removed in patch 1.6.0.0 due to complaints about excessive chatter. Brings back short interactions and some plot-relevant dialogue between the protagonist and assistant, aiming to restore the original experience. Works with all languages.

## Configuration
* The VR mod defaults to Left Controller based movement orientation.  If you wish to use HMD based movement, open 'AtomicHeart_VRFix.lua' and change line 5 to: *local MOVEMENT_ORIENTATION = "1"*

## Known Issues
1) The cursor is slightly misaligned when using Nora and Lock puzzles.
2) The Midas Glove Skin DLC will break floating hands.
3) Some button prompts are incorrect.

## Credits
Special thanks to Praydog, Gwizdek, Pande4360, DJ, and Jbusfield.

Feel free to buy me a coffee on [**Patreon**](http://www.patreon.com/ashok0) or [**Ko-Fi**](https://ko-fi.com/ashok0) :coffee:
