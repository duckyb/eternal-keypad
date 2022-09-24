# <img src="https://gist.githubusercontent.com/duckyb/282c2221d859f8134c1b1f0cf4622656/raw/97affc98d0d71566fa6ccb604eef31af2c36752a/eternal-keypad-logo.svg" height="50" alt="eternal_keypad_logo"/> ETERNAL Keypad
![ek-preview-rounded](https://user-images.githubusercontent.com/27895007/167808526-7cf01c83-1738-40c4-bed5-d04d67a561a3.png)

<div class="shields">
  <a href="https://github.com/duckyb/eternal-keypad/releases">
    <img src="https://img.shields.io/github/downloads/duckyb/eternal-keypad/total?color=success&style=flat-square">
    <img src="https://img.shields.io/github/v/release/duckyb/eternal-keypad?include_prereleases&color=success&style=flat-square">
  </a>
  <img src="https://img.shields.io/github/license/duckyb/eternal-keypad?style=flat-square&color=success">
  <a href ="https://discord.gg/3erEKm3uht">
    <img src="https://discordapp.com/api/guilds/914228133786439740/widget.png?style=shield">
  </a>
</div>

### Sponsors

<span class="sponsors">
  <a href="https://shop.beekeeb.com/product/eternal-keypad-kit/">
    <img src="https://user-images.githubusercontent.com/27895007/192096782-2ca086d8-54a3-42fd-a67b-0f1e25f1ffbc.png" height="50"/>
  </a>
</span>

## Scope of the project
Eternal Keypad is an **open-source input device for gaming** that can be assembled for **both right and left hand mouse users**.  

Historically there has been a scarcity of input devices for people that use their keyboard with their right hand and the mouse with the left, forcing some people to place their right hand in uncomfortable positions and/or requiring heavy remapping of in-game controls.  
This device aims to fill this gap in the market that companies don't care about because the target is too small to turn a profit.

The device is Pro-micro compatible, so it's easier to build and source components.

## Features

⭕ Standard layout in a half-size form factor (all your keys are still there!)  
⭕ Ortholinear/grid layout for additional comfort  
⭕ Bluetooth support (nice!nano, battery, zmk, power switch)  
⭕ Hotswap with Kailh Sockets  
⭕ RGB Underglow  
⭕ 3 macro buttons  
⭕ Easy to build  
⭕ Files for FR4 or laser cut plate case included  

## How can I make this?
<a href="https://youtu.be/vkTpa7AnWUo" target="_blank">
  <img src="https://gist.githubusercontent.com/duckyb/337340baa1f0c8bcc06fef7b3b57242b/raw/97e6e0748dd1b8a3fb54fac0a88e84e6b6e0e10a/build-guide-button.svg" height="44">
</a>

### Components list (latest PCB version)

#### For the Keyboard (required)
- 1× [ETERNAL Keypad PCB](https://github.com/duckyb/eternal-keypad/releases/latest)
- 36× through-hole or surface-mount diodes. (I use "1N4148 CDIL" from tme.eu)
- 36× MX style switches
- 36× Kailh Hotswap Sockets
- 1× Stabilizer (2u)
- 36× Keycaps (The set pictured above is "Honey & Milk XDA")
- 1× Micro controller (Pro-micro or equivalent)

Optionals:
- 8× WS2812B RGB LEDs
- 1× Slider switch (for wireless)
- 1× LiPo battery (type: 301230, for wireless)

#### For the case (recommended)
- 1× [ETERNAL Keypad switch plate & bottom plate](https://github.com/duckyb/eternal-keypad/releases/latest)
  - If you want to have underglow RGB you should order a laser cut bottom plate from acrylic, using the included `.dxf` file. If you don't care about underglow you can get an FR4 bottom plate PCB using the gerber file.
- 8× M2 Screws (I use "1154095 BOSSARD" from tme.eu)
- 4× M2 standoffs (diameter: 3mm, length: 8mm)
- 4× Rubber bump-on feet

### Buy as DIY Kit

It might be more convenient to purchase this project as a kit, check out the [vendors page](./vendors.md).

## FAQ

Check the [dedicated page](./FAQ.md)

## Firmware

<a href="https://github.com/qmk/qmk_firmware/tree/master/keyboards/eternal_keypad" target="_blank">
  <img src="https://qmk.fm/assets/images/badge-small-light.svg" height="44"/>
</a>
<a href="https://www.caniusevia.com/">
  <img src="https://user-images.githubusercontent.com/27895007/167814873-be7de892-754b-4b6b-976c-8983c1baf8e2.svg" height="44"/>
</a>
<a href="https://zmk.dev/">
  <img src="https://user-images.githubusercontent.com/27895007/188517482-3f93cafe-685a-4de9-9aee-ba4bfa29cb89.svg" height="44"/>
</a>

You can find firmwares in the [release section](https://github.com/duckyb/eternal-keypad/releases/latest), ready to download and flash.  
If you want to customize them, you can do so using QMK, ZMK or VIA.

![eternal_keypad](https://user-images.githubusercontent.com/27895007/144766801-a8390a4f-9810-4c56-9442-b2406a4ed4ce.png)

Note: 
- The "A" and "D" keys are not mirrored to avoid inverting movement controls with default key-bindings.
- The "FN" key is used to access the missing half of the keyboard
- Holding the 0 key turns WASD into arrow keys

## Additional Resources

- 3D Printed case by chewiedies → [View on Thingiverse](https://www.thingiverse.com/thing:5329104)
