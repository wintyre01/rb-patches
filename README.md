Original project by MiloHax. These are my personal modifications to the games.

# rb-patches
 
Lightweight patches to vanilla RB games that add small quality-of-life improvements

</br>

# 📥 Downloads

| Xbox 360 | PlayStation 3 |
| --- | ----------- |
| 📥 [RB1 Patch](https://nightly.link/hmxmilohax/rb-patches/workflows/build/main/RB1-Patch-Xbox.zip) | 📥 [RB1 Patch](https://nightly.link/hmxmilohax/rb-patches/workflows/build/main/RB1-Patch-PS3.zip)  |
| 📥 [TBRB Patch](https://nightly.link/hmxmilohax/rb-patches/workflows/build/main/TBRB-Patch-Xbox.zip) | 📥 [TBRB Patch](https://nightly.link/hmxmilohax/rb-patches/workflows/build/main/TBRB-Patch-PS3.zip) 📥 [PS3 Disc Patch (Required)](https://github.com/hmxmilohax/rb-patches/raw/main/tbrb/dependencies/TBRB-PS3DiscPatch.zip)* |
| 📥 [GDRB Patch](https://nightly.link/hmxmilohax/rb-patches/workflows/build/main/GDRB-Patch-Xbox.zip) | 📥 [GDRB Patch](https://nightly.link/hmxmilohax/rb-patches/workflows/build/main/GDRB-Patch-PS3.zip)** |
| 📥 [LRB Patch](https://nightly.link/hmxmilohax/rb-patches/workflows/build/main/LRB-Patch-Xbox.zip) | 📥 [LRB Patch](https://nightly.link/hmxmilohax/rb-patches/workflows/build/main/LRB-Patch-PS3.zip) |

</br>

> These install exactly the same as the *Deluxe* mods, as usual make sure you back up each game's `default.xex`
>
> *Due to technical reasons, TBRB on PS3 requires a separate "Disc Patch", extract that and overwrite the files where your base game is installed
>
> **For GDRB on PS3, extract and overwrite the files where your base game is installed 

</br>

# 📥 RPCS3 Recommended Settings

| Recommended | Minimum |
| --- | ----------- |
| 📥 [All Games](https://github.com/hmxmilohax/rb-patches/raw/main/_custom_configs/recommended_all.zip) | 📥 [All Games](https://github.com/hmxmilohax/rb-patches/raw/main/_custom_configs/minimum_all.zip) |
| 📥 [RB1](https://github.com/hmxmilohax/rb-patches/raw/main/_custom_configs/recommended_rb1.zip) | 📥 [RB1](https://github.com/hmxmilohax/rb-patches/raw/main/_custom_configs/minimum_rb1.zip) |
| 📥 [TBRB](https://github.com/hmxmilohax/rb-patches/raw/main/_custom_configs/recommended_tbrb.zip) | 📥 [TBRB](https://github.com/hmxmilohax/rb-patches/raw/main/_custom_configs/minimum_tbrb.zip) |
| 📥 [GDRB](https://github.com/hmxmilohax/rb-patches/raw/main/_custom_configs/recommended_gdrb.zip) | 📥 [GDRB](https://github.com/hmxmilohax/rb-patches/raw/main/_custom_configs/minimum_gdrb.zip) |
| 📥 [LRB](https://github.com/hmxmilohax/rb-patches/raw/main/_custom_configs/recommended_lrb.zip) | 📥 [LRB](https://github.com/hmxmilohax/rb-patches/raw/main/_custom_configs/minimum_lrb.zip) |

</br>

> To use these, click on the settings you want to download then extract the ZIP archives in the folder where you extracted RPCS3. It should combine folders automatically if you did it right.
>
> "All Games" includes custom configurations for every game listed here.
>
> In the GIF example below, the “Recommended” requirements settings archive (recommended.zip) was downloaded and its contents were moved into RPCS3’s folder.

</br>

![image](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/quickconf.gif)

</br>

## Patches Applied:

### All:

- Faster boot time
- Faster scrolling
- 1ms calibration increment
- Volume sliders can be muted completely
- Additional practice speeds
- SELECT button restarts current practice section
- Video Overscan enabled by default
- Default difficulty is Expert
- Decensored tracks (with the exception of slurs)
- 2x pedal as default for applicable tracks
- Updated to RB4 Charts with some exceptions
- Strum limit removed
- Reconfigured tiers so that they make some more sense for their games (including overall being the sum of all parts divided by however many parts are in the song)

### RB1:

- Adjustable options via external `config.dta` file:
	- Track Speed
	- Sync Difficulty Speeds
	- Venue FPS
	- Black Background
	- Performance Mode
	- Autoplay (disables saving, online)
	- Vsync
	- Instrument Slots
- Vocal practice mode
- Allow one player in Band Quickplay and Band World Tour
- Reconfigured tiers (making it close to how I have it for Rock Band 2 and 3)
	- Warmup (1-130)
	- Apprentice (131-170)
	- Solid (171-210)
	- Moderate (211-250)
	- Skilled (251-290)
	- Challenging (291-320)
	- Blistering (321-360)
	- Nightmare (361-400)
    - Impossible (401+)

### TBRB:

- Vsync disabled on RPCS3
- "Super Speed" (Breakneck Speed) in Practice mode and Drum Trainer
- Reconfigured tiers (how easy or hard it is for a Beatles track)
	- Beginner (1-200)
	- Apprentice (201-230)
	- Moderate (231-260)
	- Solid (261-290)
	- Tricky (291-320)
	- Challenging (321-350)
	- Demanding (351+)

### GDRB:

- Vsync disabled on RPCS3
- "Super Speed" (Breakneck Speed) in Practice mode and Drum Trainer
- DIY stems for "Chump" and "Longview" re-done with modern technology [by dirk](https://github.com/dirkNlerxst/dirks-rb3-customs/tree/main/MOGG%20Replacements)
- Reconfigured tiers (how easy or hard it is for a Green Day track)
	- Beginner (1-150)
	- Apprentice (151-180)
	- Moderate (181-210)
	- Solid (211-240)
	- Tricky (241-270)
	- Challenging (271-300)
	- Demanding (301+)

### LRB:

- Adjustable options via external `config.dta` file:
	- Track Speed
	- Sync Difficulty Speeds
	- Venue FPS
	- Vsync
	- Instrument Slots
- Songs of any rating can be played
- UGC songs can be played (RBN, customs)
- Any region DLC can be loaded
- All prefabs available
- All Rock Shop items unlocked
- Holiday DLC minifigures
- Vocal practice mode
- Compatible with the PS3 EU 1.0 debug build via patchcreator
- Reconfigured tiers (how easy or hard it is for children, aka the intended audience LOL)
	- First Steps (1-130)
	- Making Headlines (131-170)
	- Rising Star (171-200)
	- Rock Star (201-230)
	- Super Star (231-260)
	- Mega Star (261-300)
	- Out of this World (301+)
