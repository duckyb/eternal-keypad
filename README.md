
<div align="center">
  <img src="https://user-images.githubusercontent.com/27895007/137556449-4c22bc49-4566-451d-b1f5-bf977f3b0f48.png"/>
</div>

# ETERNAL Keypad
![github-preview](https://user-images.githubusercontent.com/27895007/139288233-7d9123b4-a197-4697-ad04-7d979d552419.jpg)

## Scope of the project
Eternal Keypad is an **open-source input device for gaming** that can be assembled for **both right and left hand mouse users**.  

Historically there has been a scarcity of input devices for people that use their keyboard with their right hand and the mouse with the left, forcing some people to place their right hand in uncomfortable positions and/or requiring heavy remapping of in-game controls.  
This device aims to fill this gap in the market that companies don't care about because the target is too small to turn a profit.

The device is Pro-micro compatible, so it's easier to build and source components.

## Components list

### For the Keyboard (required)
- x36 through-hole diodes. (I use "1N4148 CDIL" from tme.eu)
- x36 MX style switches
- x1 2u stabilizer
- Keycaps
- x1 Micro controller (Pro-micro or equivalent)

### For the case (recommended)
- x8 M2 Screws (I use "1154095 BOSSARD" from tme.eu)
- x4 M2 standoffs (I use "111X08 DREMEC" from tme.eu)
- 4x Rubber bump-on feet

## Firmware

You can find the firmware in the release section, ready to download and flash.  
If you want to customize it, you can do so using QMK.

![eternal_keypad](https://user-images.githubusercontent.com/27895007/144766801-a8390a4f-9810-4c56-9442-b2406a4ed4ce.png)

Note: 
- The "A" and "D" keys are not mirrored to avoid inverting movement controls with default key-bindings.
- The "FN" key is used to access the missing half of the keyboard
- Holding the 0 key turns WASD into arrow keys
