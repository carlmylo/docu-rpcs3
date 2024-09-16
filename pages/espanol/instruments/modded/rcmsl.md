---
title: RetroCultMods Solderless Kit Guitars
sidebar: controllers_sidebar
permalink: ctrls_mod_rcmsl
folder: instruments
tags: [xbox-360, midi, english]
summary: "How to connect and configure Xbox 360 Wireless keyboards (MIDI) on RPCS3."
toc: false
---

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/plat/rcm.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/cont/rcmgtrs.png" alt="Controller" title="Controller"></div>

## NOTES

* **This is specifically for the** [**[SOLDERLESS DIY RGB Kit for Guitar Hero Controllers by RetroCultMods]**](https://www.etsy.com/listing/1505287559/solderless-diy-rgb-kit-for-guitar-hero)**!** Please consult your sales receipt to confirm that it is indeed a Solderless DIY RGB Kit for Guitar Hero Controllers by RetroCultMods.

## Pad Information

| Handlers | Devices |
|:------------------:|:---------------------:|
| MMJoystick | Joystick |

| Device Class | Device Subtype |
|:------------------:|:---------------------:|
| Guitar | Rock Band |

## Setup

If you haven't initlized your controller yet, start up RetroCultMod's Programming Tool.

In the start screen, select your Device. It will usually show up as "`Raspberry Pi Pico`".
After that, select your Device Type depending on which RetroCultMod product you have.
Then finally, set Device Variant to "`Default`". **You don't need Auth, Slider, or Joystick** support.
After that, click on Erase and configure and wait for the progress bar to finish.

![A screenshot of RetroCultMods Programming Tool. "Selected Device" is set to Raspberry Pi Pico, "Device Type" is set to "Zeroboard SL (Solderless Kit)", and Device Variant is set to "Zeroboard SL - Default."](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/rcmpt/initsl.png "RetroCultMods Programming Tool")

When it finishes, click on Configure.

![A screenshot of RetroCultMods Programming Tool. "Selected Device" is set to "Zeroboard SL - Default" and the mouse is hovering over "Configure."](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/rcmpt/seldevsl.png "RetroCultMods Programming Tool")

In Controller Settings, set your configuration to the following:
* Swap Switch Face Buttons: (Depends on your guitar)
* Windows Controller Mode: HID Game Controller
* Slider Bar: (Depends on your guitar)
* Tilt: Enabled

![A screenshot of RetroCultMods Programming Tool. The settings reflect exactly what is above.](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/rcmpt/consetsl.png "RetroCultMods Programming Tool")

It's also suggested you calibrate your Whammy to have the best experience. Scroll down to the Whammy section and calibrate it.

**MAKE SURE YOU CLICK ON "`Save Settings`" before closing the program or you will lose progress!**

![A screenshot of RetroCultMods Programming Tool. The cursor is hovering over "Save Settings".](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/rcmpt/savesl.png "RetroCultMods Programming Tool")

## Mappings

* **To map everything correctly, you will need to first map Whammy Down, which is Right Stick: Left in RPCS3. It should show up as X-. After mapping it, click `"Filter Noise"` and map the rest.**

| **RPCS3**          | **Controller** |
|:------------------:|:---------------------:|
| Cross | ![Green Fret](https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/gf.png "Green Fret") |
| Circle | ![Red Fret](https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/rf.png "Red Fret") |
| Square | ![Blue Fret](https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/bf.png "Blue Fret") |
| Triangle | ![Yellow Fret](https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/yf.png "Yellow Fret") |
| L1 | ![Orange Fret](https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/of.png "Orange Fret") |
| D-Pad: Up | ![Strumbar Up](https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/sbu.png "Strumbar Up") |
| D-Pad: Down | ![Strumbar Down](https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/sbd.png "Strumbar Down") |
| D-Pad: Left | ![D-Pad: Left](https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/dpl.png "D-Pad: Left") |
| D-Pad: Right | ![D-Pad: Right](https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/dpr.png "D-Pad: Right") |
| Right Stick: <br/> Left/Right | ![Whammy Bar](https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/wb.png "Whammy Bar") |
| R1 | ![Tilt](https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/ts.png "Tilt") |
| Start | ![Start](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/360/start.png "Start") |
| Select | ![Back](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/360/back.png "Back") |
| PS Button | ![Home](https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/home.png "Home") |

### Passthrough Mode

<div markdown="span" class="alert alert-info" role="alert"><i class="fa fa-info-circle"></i> <b>As of writing this, RPCS3 does not support hotplugging, which means you cannot plug your guitar in AFTER starting RPCS3. Passthrough Mode lets you use your guitar without needing to bind anything but due to the lack of hotplugging (PS3/Emulator preset), you need to start the game up twice. Therefore, this mode is currently not recommended. </b> {{include.content}}</div>

## Profile

[[Download Profile]](https://github.com/carlmylo/docu-rpcs3/raw/gh-pages/instrument-repo/RetroCultMods%20Solderless%20Kit.7z)

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/maps/rcmslmapping.png" alt="Mapping" title="Mapping"></div>

[[Back to Controllers]](https://rb3pc.milohax.org/english/controllers/)

Research by [[Lynxeption]](https://www.youtube.com/@Lynxeption).  
Special thanks to [[@amphobius]](https://twitter.com/amphobius) for additional pictures