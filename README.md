
<div align="center">
  <img src="https://user-images.githubusercontent.com/27895007/137556449-4c22bc49-4566-451d-b1f5-bf977f3b0f48.png"/>
</div>

# ETERNAL Keypad
![git-preview (Small)](https://user-images.githubusercontent.com/27895007/144914161-c3f6f8ba-5b78-4c85-b8e2-320ba73d80ce.png)

<a href="https://github.com/duckyb/eternal-keypad/releases">
  <img src="https://img.shields.io/github/downloads/duckyb/eternal-keypad/total?color=success">
  <img src="https://img.shields.io/github/v/release/duckyb/eternal-keypad?include_prereleases">
</a>

## Scope of the project
Eternal Keypad is an **open-source input device for gaming** that can be assembled for **both right and left hand mouse users**.  

Historically there has been a scarcity of input devices for people that use their keyboard with their right hand and the mouse with the left, forcing some people to place their right hand in uncomfortable positions and/or requiring heavy remapping of in-game controls.  
This device aims to fill this gap in the market that companies don't care about because the target is too small to turn a profit.

The device is Pro-micro compatible, so it's easier to build and source components.

## How can I make this?
<a href="https://youtu.be/vkTpa7AnWUo" target="_blank">
  <img src="https://gist.githubusercontent.com/duckyb/337340baa1f0c8bcc06fef7b3b57242b/raw/97e6e0748dd1b8a3fb54fac0a88e84e6b6e0e10a/build-guide-button.svg" height="44">
</a>

### Components list

#### For the Keyboard (required)
- [ETERNAL Keypad PCB](https://github.com/duckyb/eternal-keypad/releases/latest)
- x36 through-hole diodes. (I use "1N4148 CDIL" from tme.eu)
- x36 MX style switches
- x1 2u stabilizer
- Keycaps (The set pictured above is "Honey & Milk XDA")
- x1 Micro controller (Pro-micro or equivalent)

#### For the case (recommended)
- [ETERNAL Keypad switch plate & bottom plate](https://github.com/duckyb/eternal-keypad/releases/latest)
- x8 M2 Screws (I use "1154095 BOSSARD" from tme.eu)
- x4 M2 standoffs (I use "111X08 DREMEC" from tme.eu)
- 4x Rubber bump-on feet

## Firmware

<a href="https://github.com/qmk/qmk_firmware/tree/master/keyboards/eternal_keypad" target="_blank">
  <img src="https://qmk.fm/assets/images/badge-small-light.svg" width="200"/>
</a>

You can find both firmwares in the [release section](https://github.com/duckyb/eternal-keypad/releases/latest), ready to download and flash.  
If you want to customize it, you can do so using QMK.

![eternal_keypad](https://user-images.githubusercontent.com/27895007/144766801-a8390a4f-9810-4c56-9442-b2406a4ed4ce.png)

Note: 
- The "A" and "D" keys are not mirrored to avoid inverting movement controls with default key-bindings.
- The "FN" key is used to access the missing half of the keyboard
- Holding the 0 key turns WASD into arrow keys
