Sponsors or Patrons who contribute $5 per month will get access to pre-release (new) versions of the mod menu. 
- If you sponsor more than $5 a month, GitHub might not automatically invite you to the private repository. 
  - In that case, just open an issue on this repository using the account you're sponsoring with, and I'll send you an invite.
- If you're already a sponsor and accepted the invite to the repository, you can access it by [clicking here](https://github.com/sneakyevil-org/SD-ModMenuSponsor).
- If you would like to be a sponsor you can join by [clicking here](https://github.com/sponsors/sneakyevil).

# Changelog

__v2.3.5:__
> - Added Allow Move Controls option under Free Camera while Enable Player flag is enabled.

__v2.3.4:__
> - Added Freeze option in Game Options.

__v2.3.3:__
> - Added Rainbow color option for menu.

__v2.3.2:__
> - Added Vehicle Option:
>     - Paint Texture
>         - Place PNG files in the `data/SModMenu/vehicle_textures` directory.

__v2.3.1:__
> - Added Vehicle Option:
>     - Neons 

__v2.3.0:__
> - Added Vehicle Option:
>     - Physics Definition:
>         - Max Speed
>         - Engine:
>             - Minimum RPM
>             - Optimum RPM
>             - Maximum RPM
>             - Clutch Slip RPM
>             - Torque
>             - Torque Factor At Min RPM
>             - Torque Factor At Max RPM
>         - Wheel Friction:
>             - Front & Rear
>         - Brakes:
>             - Front & Rear Wheel Torque
>         - Aerodynamics:
>             - Air Density
>             - Frontal Area
>             - Drag Coefficient
>             - Lift Coefficient
>         - Steering:
>             - Speed Sensitivity
>             - Max Angle
>             - Front & Rear Wheel Percentage

__v2.2.0:__
> - Added NPC Options:
>     - Ignore Player
>     - Spawn Options:
>         - Fighting Class
>         - Scale
> - NPCs will ignore player by default while using Free Camera.

__v2.1.2:__
> - Added option to Invoke Cutscenes under Game Options.

__v2.1.1:__
> - Added Green Screen under Game Options.

__v2.1.0:__
> - Added option to Invoke Game Slices under Game Options.
>     - This can be used to invoke a missions/scenarios/scripts.
> - Added Infinite Face Meter under Player Options.
> - Added "Drunken Fist" option for Force Outfit Behavior.
> - Added DLC Fists Effect under Player Options.

__v2.0.6:__
> - Added World Options:
>     - Unlock Doors
>     - Actions:
>         - Kiss
>         - Escort
>         - Switch Two Chin's Gate

__v2.0.4:__
> - Added option to allow props to be spawned for Model Changer.
> - Added scale option for NPCs.
> - Added option to flip vehicle.
> - Added option to disable ramming cooldown for Vehicle.
> - Added option to change NPCs damage multiplier.
> - Added Death Touch under Player Options.

__v2.0.3:__
> - Added option to change Game Seconds per second under World Options.
> - Added option to change Game Speed under Game Options.

__v2.0.2:__
> - Added Audio Feedback.
> - Added toggle to enable ragdoll with Invulnerable Option.

__v2.0.1:__
> - Fixed issue with saved settings not been loaded.
> - Added additional check to prevent menu running while not been in the game.
> - Added new feature called `Attached FX` for Weapon & Vehicle Options.
> - Added Nearest Vehicle options under Teleport Options.
> - Added an option to change toggle key for menu.

__v2.0.0:__
> The version 2.0.0 has been developed with an entirely new codebase, mainly due to the new SDK and the old codebase being a mess.
> 
> - **Presets like Clothing, Vehicle Colors are not compatible with previous version!**
> - **Added an option to save most settings between game sessions.**
> - Option to adjust hue that changes the entire menu colors.
> - Gamepad buttons are mapped to keyboard inputs, allowing them to be assigned to keybind options.
>     - The option will display the mapped keyboard input instead of the actual gamepad button.
> - Using Free Camera during a cutscene no longer disables the player character.
> - Spawned weapons no longer despawn if the limit has not been reached.
> - The clothing list has been reworked, and previously missing names have been corrected to match the actual outfit names.
> - No Clip under Player Options now works inside vehicles.
> - **Fixed an issue with some NPCs that had broken models when spawned.**
>     - This mainly affects characters used only in cutscenes.
>     - This also applies for Model Changer.
> - Added toggle for Zodiac Tournament (Punch Sound FX) under Game Options.
> - **Model Changer should no longer cause the game to get stuck on infinite loading screen when starting missions.**
> - The character list in Model Changer and NPC Spawner has been reworked.
> - **The Character Presets in the Game Options let you create new characters using existing game assets, mix head and body parts, and customize various properties.**
> - Added an option to disable melee durability under Weapon Options.
> - Added an option to change clothing color.
> - Added an option to toggle super mass under Player Options.
> - Changed logic of Move Speed under Player Options.
> - Added an option to change swim speed under Player Options.
> 
> **NOTE:** This version has missing features from previous version, if there is some missing feature that you would like to get back please open a new issue within this repository so I could know what to prioritize in future.
