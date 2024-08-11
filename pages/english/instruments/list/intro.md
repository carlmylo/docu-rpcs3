---
title: Instruments and Controllers
sidebar: english_sidebar
permalink: ctrls
folder: english
---

Rock Band 3 on RPCS3 can be configured to be played with a variety of controllers. Below is a list of instruments verified to work with Rock Band 3 on RPCS3 with their respective mapping.

Controllers have been given a "Compatibility" rating depending on whether or not they have issues and/or missing features.

| SHAPE | MEANING |
|---|---|
| ![A red triangle.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc//main/assets/images/instruments/compat/bad.png "Red Triangle") | **Bad Compatibility** |
| ![A green square.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc//main/assets/images/instruments/compat/okay.png "Green Square") | **Okay Compatibility** |
| ![An orange circle.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc//main/assets/images/instruments/compat/great.png "Orange Circle") | **Great Compatibility** |

## Mapping

**Right click on "Rock Band 3" and select "Create Custom Gamepad Configuration"**

![A screenshot of RPCS3's right click menu, showing "Create Custom Gamepad Configuration" highlighted](https://carlmylo.github.io/docu-rpcs3/images/conf/rpcs3pad.png "Create Custom Gamepad Configuration")

Click on the instrument icon or the **"[CLICK HERE]"** link to be taken to their respective pages for more information.

* If you are planning on plugging in multiple instruments, _you must set them on different ports_ (Player 1, Player 2, etc).
* PS3 guitar, drum controllers, and MIDI Pro Adapters **for the Rock Band series** are plug and play and require no additional setup.

**If your controller isn't being detected, click "Refresh". If that doesn't solve it, restart RPCS3.**

Once you've finished configuring, **remember to click "Save".**


## Contributing

Do you have a controller we don't have documentation on? Want to help expand this list further? Contact me (@carlmylo) on [**[the Milohax discord]**](https://discord.gg/milohax) or [[open an issue]](https://github.com/hmxmilohax/rb3-pc/issues/new).  
The following information is needed:
* Instrument brand and model
* Adapter(s) used
* Platform for instrument (Xbox 360, PlayStation 4, etc.)
* Bindings for every button (Green Fret = Cross)
* Bindings file (`RPCS3\config\input_configs\BLUS30463\Default.yml`)
* Screenshot of Custom Gamepad Configuration

## Using Profiles

<div markdown="span" class="alert alert-info" role="alert"><i class="fa fa-info-circle"></i> <b>This is not suggested for people using multiple controllers at once. </b> {{include.content}}</div>

Profiles are premade setup files made by the community. They are drag and drop files which have preconfigured mappings for various instruments.
Before you install, **if you have any bindings in `config\input_configs\BLUS30463`, you should back them up because they will be overwritten.**

1. Download the .7z file in the folder for the instrument(s) you want to use.
2. Extract the .7z file.
3. Drag the `config` folder into the folder you have RPCS3 in.

![A GIF of a user dragging the Wii Rock Band Guitar configuration into their RPCS3 folder.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc//main/assets/images/xtra/instrepoinstall.gif "Installing a configuration from the Instrument Repo")

Most of the time, these controller profiles should work out of the box. If they don't, try changing the controller listed in "`Devices`", next to the "`Refresh`" button until it receives an input. You can edit this while the game is running.

Keep in mind that the profiles are formatted for single players. You will need to add all instruments needed.

Alternatively, you can combine multiple files if you know your way around text editors like Notepad++ or Sublime Text.
Select everything from line 2 to the end of line 86 in the `Default.yml` file of the instrument you want to add, then copy it. 
Paste it into:
* Line 88 to 172 for Player 2
* Line 174 to 258 for Player 3
* Line 260 to 344 for Player 4
* Line 346 to 430 for Player 5
* Line 432 to 516 for Player 6
* Line 518 to 602 for Player 7

{% include links.html %}