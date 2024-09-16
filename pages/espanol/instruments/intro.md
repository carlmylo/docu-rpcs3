---
title: Instrumentos y Controles
sidebar: espanol_sidebar
permalink: ctrls_es
folder: espanol
tags: [controles, espanol]
summary: "Como configurar controles y instruments en RPCS3."
toc: false
---

Puedes usar una variedad de insturmtns con Rock Band 3 en RPCS3. Below is a list of instruments verified to work with Rock Band 3 on RPCS3 with their respective mapping.

Controllers have been given a "Compatibility" rating depending on whether or not they have issues and/or missing features.

| SHAPE | MEANING |
|---|---|
| ![A red triangle.](https://raw.githubusercontent.com/carlmylo/docu-rpcs3/gh-pages/images/instruments/compat/bad.png "Red Triangle") | **Bad Compatibility** |
| ![A green square.](https://raw.githubusercontent.com/carlmylo/docu-rpcs3/gh-pages/images/instruments/compat/okay.png "Green Square") | **Okay Compatibility** |
| ![An orange circle.](https://raw.githubusercontent.com/carlmylo/docu-rpcs3/gh-pages/images/instruments/compat/great.png "Orange Circle") | **Great Compatibility** |

## Mapping

**Click on the Pads icon at the top of RPCS3**.

![A screenshot of RPCS3, showing the cursor over the Pads menu.](https://carlmylo.github.io/docu-rpcs3/images/instruments/rpcs3pad.png "Pads")

On the instrument pages, click on the instrument's icon or the **"[CLICK HERE]"** link to be taken to their respective pages for more information.

* If you are planning on plugging in multiple instruments, _you must set them on different ports_ (Player 1, Player 2, etc).
* PS3 guitar, drum controllers, and MIDI Pro Adapters **for the Rock Band series** are plug and play and require no additional setup.

**If your controller isn't being detected, click "Refresh". If that doesn't solve it, restart RPCS3.**

Once you've finished configuring, **remember to click "Save".**

## Using Profiles

<div markdown="span" class="alert alert-info" role="alert"><i class="fa fa-info-circle"></i> <b>This is not recommended if you're using multiple controllers at once. </b> {{include.content}}</div>

Profiles are premade setup files made by the community. They are drag and drop files which have preconfigured mappings for various instruments.

1. Download the .7z file in the folder for the instrument(s) you want to use.
2. Extract the .7z file.
3. Drag the `input_configs` folder into the `configs` folder where you have RPCS3 in.

![A GIF of a user dragging the Wii Rock Band Guitar configuration into their RPCS3 folder.](https://raw.githubusercontent.com/carlmylo/docu-rpcs3/gh-pages/images/instruments/instrepoinstall.gif "Installing a configuration from the Instrument Repo")

After that, you can select the profile in the **"Pads"** menu.

![A screenshot of RPCS3's Gamepad Settings, showing the cursor over a profile.](https://carlmylo.github.io/docu-rpcs3/images/instruments/rpcs3padprofile.png "Gamepad Settings")

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

## Contributing

Do you have a controller we don't have documentation on? Want to help expand this list further? Contact me (@carlmylo) on [**[the Milohax discord]**](https://discord.gg/milohax){:target="_blank"} or [[open an issue]](https://github.com/hmxmilohax/rb3-pc/issues/new){:target="_blank"}.  
The following information is needed:
* Instrument brand and model (Guitar Hero Les Paul)
* Adapter(s) used (RetroCultMods V3 Adapter)
* Platform for instrument (Nintendo Wii)
* Bindings for every button (Green Fret = Cross)
* Bindings file
	* (`RPCS3\config\input_configs\global\ProfileName.yml`) if it's with the global "Pads" menu
	* (`RPCS3\config\input_configs\BLUS30463\Default.yml`) if it's made in "Custom Gamepad Configuration"
* Screenshot of Custom Gamepad Configuration

{% include links.html %}