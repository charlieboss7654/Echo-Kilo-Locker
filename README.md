# Echo Kilo Locker

This is a clean, immersive, and fully integrated locker UI system for FiveM!

## Features
- Seamless wardrobe access using `ox_target` zones
- UI-based selection of preset and personal outfits
- Save and delete personal outfits (stored per-player)
- Scrollable, searchable interface with a modern look
- locker closing sound effect
- Each location can have different lockers, containing different outfits!

## Installation

1. Drag and drop the folder into your `resources/` directory  

2. Add the following to your `server.cfg`:

  ensure EKS_Locker


3. Ensure these requirements are running:

   - ox_lib - https://overextended.github.io/ox_lib/
   - ox_target - https://github.com/overextended/ox_target

4. (Optional) Edit `config.lua` to define:

   - Target zone locations
   - Preset outfits per department/group

## Notes

- Saved personal outfits are only visible to the player who saved them.
- Preset outfits can be grouped and assigned by zone (e.g., LSPD, EMS, etc.)
- Sound file `lockerclose.ogg` must exist in your `sounds/` folder and be supported by your sound system.

## Support

Need help or custom features? Open a ticket through EKS.

https://discord.gg/busQ9w6dqa
