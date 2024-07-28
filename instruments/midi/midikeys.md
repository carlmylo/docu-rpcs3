---
title: MIDI Keyboard
sidebar: controllers_sidebar
permalink: ctrls_keys_midi
folder: instruments
toc: false
---

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/plat/midi.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/cont/midikeyscontroller.png" alt="Controller" title="Controller"></div>

## NOTES

* There is no binding file.
* **Do NOT map this instrument via Gamepad Configuration.**
* It is suggested to have a keyboard with **at least 37 keys** or 25 keys and 11 drum pads.
* Your MIDI keyboard needs to:
	* **be set to MIDI Channel 1.**
	* **have modultation and pitch controls.**
	* optionally have a sustain pedal
* Requires the latest version of [[RPCS3]](https://rpcs3.net/download)
* RPCN Menus (for sending or accepting online invites) will cause a softlock. You will need an alternative input method to navigate these menus, such as a typing keyboard or a gamepad.

## Instructions

**If your keyboard has a USB port**, all you need to do is **plug it into your computer**.  

>![A picture of a MIDI controller's back, showing a USB port and a sustain pedal](https://carlmylo.github.io/docu-rpcs3/images/midi/usbkeys.png "USB Keyboard")  

**If your keyboard only has a MIDI output, you will need a MIDI to USB interface**.

>![A picture of a MIDI controller's back, showing a 5-DIN MIDI input and output highlighted in yellow with a solid white outline, and multiple pedal inputs.](https://carlmylo.github.io/docu-rpcs3/images/midi/midikeys.png "MIDI Keyboard")  

Here's an example of a MIDI to USB interface. Most will come with an LED indicator to show activity. **To check that you've plugged it in correctly, you should see "MIDI In" blinking when you press a key**. 

>![A picture of a MIDI to USB interface.](https://carlmylo.github.io/docu-rpcs3/images/midi/miditousb.png "MIDI to USB interface")  

**If you have an audio interface, you may already have a way to plug in MIDI** to your computer, as some audio interfaces come with MIDI inputs. For example, this Scarlett has MIDI connections in the back.  
>![A picture of a Focusrite Scarlett's rear, showing a USB port, and 5-DIN MIDI input and output.](https://carlmylo.github.io/docu-rpcs3/images/midi/midifs.png "Focusrite Scarlett MIDI in/out") 

Find whichever way is the most convenient for you then connect your MIDI Keyboard to your computer.

After that, **right click on Rock Band 3** in RPCS3, then click on “**Change Custom Configuration**”.  

![A screenshot of RPCS3's right click menu, showing "Change Custom Configuration" highlighted](https://carlmylo.github.io/docu-rpcs3/images/cust/rpcs3customconfigchange.png "Change Custom Configuration")

![A screenshot of Rock Band 3's I/O custom settings, showing Emulated MIDI Devices, device type, and device selection highlighted in tan with a solid outline.](https://carlmylo.github.io/docu-rpcs3/images/cust/iod.png "I/O")
* ![A tan square with a solid outline](https://carlmylo.github.io/docu-rpcs3/images/cust/smalltan.png "Tan Square") : 
	* 🎹 Keyboard Players: Leave your “Emulated MIDI type” on “Keyboard” and select your keyboard or MIDI interface in the drop-down menu next to it.

### Mapping

![A picture of a 37 key keyboard, showing the second octave mapped to PlayStation buttons, C3 to E3 under a red color, F3 to B3 under a yellow color, C4 to E4 under a blue color, F4 to B4 under a green color, and C5 under an orange color.](https://carlmylo.github.io/docu-rpcs3/images/midi/keysctrl.png "MIDI Keyboard Reference")

| **Note** | **Button** |
|:--------:|:-------------------:|
| C2 | ![Select](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/sel.png "Select") |
| D2 | ![D-Pad Left](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/dl.png "D-Pad Left") |
| E2 | ![D-Pad Right](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/dr.png "D-Pad Right") |
| F2 | ![D-Pad Up](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/du.png "D-Pad Up") |
| G2 | ![D-Pad Down](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/dd.png "D-Pad Down") |
| A2 | Deploy Overdrive |
| C#2 | ![Triangle](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/t.png "Triangle") |
| D#2 | ![Square](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/s.png "Square") |
| F#2 | ![Circle](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/o.png "Circle") |
| G#2 | ![Cross](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/x.png "Cross") |
| A#2 | ![Start](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/sta.png "Start") |
| Modwheel | Deploy Overdrive |
| Sustain | Deploy Overdrive |
| Pitch Wheel | Whammy/Touch Strip |

### Additional Configuration

> ##### WARNING
>
> _The following steps are for advanced users only. The configuration is a last resort measure for those that absolutely have no way to get a keyboard with more than 25 keys._
{: .block-warning  }

#### Using a computer keyboard along with a 25 key keyboard.

If you insist on using a 25 key keyboard without drum pads, you can use your regular computer keyboard and convert its key presses to the MIDI notes that correspond to the game buttons.
First, [[download loopMIDI]](https://www.tobias-erichsen.de/software/loopmidi.html).

[![A screenshot of loopMIDI's download page.](https://carlmylo.github.io/docu-rpcs3/images/instruments/midictrlloopMIDIdl.png)](https://www.tobias-erichsen.de/software/loopmidi.html "Tobias Erichsen - loopMIDI")

Install loopMIDI. **Launch it after it finishes.**

![A screenshot of loopMIDI's installer.](https://carlmylo.github.io/docu-rpcs3/images/instruments/midictrlloopMIDIinst.png "loopMIDI Setup")

Add two new ports by clicking on the `+` button in the bottom. You should name the ports, too. They've been named "Pro Keys" and "Gamepad" in this example.

![A screenshot of loopMIDI, with a mouse cursor over the Plus symbol for "Add Port". Additionally, "New port name" is highlighted in blue with a dotted outline, with "Pro Keys" typed out in the text field.](https://carlmylo.github.io/docu-rpcs3/images/instruments/midictrlloopMIDIaddport.png "loopMIDI")

Now, [[the `.zip` archive that contains the win64 version of FreePiano]](https://freepiano.tiwb.com/en/).

[![A screenshot of FreePiano's download page.](https://carlmylo.github.io/docu-rpcs3/images/instruments/midictrlfreepnodl.png)](https://freepiano.tiwb.com/en "FreePiano - Advanced virtual MIDI keyboard")

Extract the `.zip` archive somewhere you can easily find it. It was extracted to `C:\Games\freepiano` in this example.

Go to where you extracted FreePiano and run the `freepiano` executable.

![A screenshot showing the FreePiano executable highlighted.](https://carlmylo.github.io/docu-rpcs3/images/instruments/midictrlfreepnodir.png "freepiano.exe")

Assign the keys to your liking as shown in the [**[#mapping]**](#mapping) section above.

There is also a premade profile if you'd like, which you can [**[download here]**](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/rb3gamekeys.map).

To use the preset, place the `rb3gamekeys.map` file in the `keymap` folder located where you extracted FreePiano.

![A screenshot of the profile, named rb3gamekeys.map, in the keymap folder, highlighted.](https://carlmylo.github.io/docu-rpcs3/images/instruments/midictrlfreepnopreset.png "keymap")

Select `rb3gamekeys.map` in the "Keymap" dropdown button to load the premade profile. Likewise, if you made your own profile or edited the premade profile, you can click on **Save** to save your profile.

![A screenshot of FreePiano, with the rb3gamekeys.map profile selected.](https://carlmylo.github.io/docu-rpcs3/images/instruments/midictrlfreepnoselpres.png "rb3gamekeys.map")

The premade profile is mapped like this:

| **Key** | **Action** |
|:--------:|:-------------------:|
| Enter | ![Start](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/sta.png "Start") |
| Shift | ![Select](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/sel.png "Select") |
| Up | ![D-Pad Up](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/du.png "D-Pad Up") |
| Down | ![D-Pad Down](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/dd.png "D-Pad Down") |
| Left | ![D-Pad Left](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/dl.png "D-Pad Left") |
| Right | ![D-Pad Right](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/dr.png "D-Pad Right") |
| A | ![Cross](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/x.png "Cross") |
| S | ![Circle](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/o.png "Circle") |
| D | ![Square](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/s.png "Square") |
| F | ![Triangle](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/t.png "Triangle") |


Once you are done mapping, click on "Instrument" at the top of Freepiano's window and select the "Gamepad" MIDI output, which you made with loopMIDI earlier.

![A screenshot of FreePiano's Instrument dropdown menu, with "Gamepad MIDI" selected.](https://carlmylo.github.io/docu-rpcs3/images/instruments/midictrlfreepnoout.png "Gamepad")

It's suggested you enable "Background input mode", located within the "Options" tab which is accessed by pressing the Wrench icon in the top right side of FreePiano.

![A screenshot of FreePiano, with the "Background input mode" enabled.](https://carlmylo.github.io/docu-rpcs3/images/instruments/midictrlfreepnoback.png "Background input mode")

Now, [[download MIDI-OX]](http://www.midiox.com/moxdown.htm).

![A screenshot of MIDI-OX's website, with the proper download highlighted in blue with a dotted outline.](https://carlmylo.github.io/docu-rpcs3/images/instruments/midictrlmidioxdl.png "MIDI-OX 7.0.2")

Install MIDI-OX.

![A screenshot of MIDI-OX's installer.](https://carlmylo.github.io/docu-rpcs3/images/instruments/midictrlmidioxinst.png "MIDI-OX Setup Wizard")

Open MIDI-OX then navigate to **Options > MIDI Devices**

![A screenshot of MIDI-OX, with the mouse hovering over the MIDI Devices menu, under the Options menu.](https://carlmylo.github.io/docu-rpcs3/images/instruments/midictrlmidioxopts.png "Options > Midi Devices")

In the MIDI Devices Menu, select your keyboard and the port you made in loopMIDI ("Gamepad") for FreePiano in the MIDI Inputs section.
Select the other port you made in loopMIDI ("Pro Keys") in the MIDI Outputs. This will combine both MIDI inputs into a single output.

![A screenshot of MIDI-OX's MIDI Devices, with a keyboard and the Gamepad selected in the MIDI Inputs section and Pro Keys selected in the MIDI Outputs section.](https://carlmylo.github.io/docu-rpcs3/images/instruments/midictrlmidioxcombo.png "MIDI Devices")

Finally, in RPCS3, go to Rock Band 3's Custom Configuration then go to the I/O tab. Select the port that you selected as your output in MIDI-OX ("Pro Keys").

![A screenshot of Rock Band 3's I/O custom settings, showing Emulated MIDI Devices, device type, and device selection highlighted in tan with a solid outline. It is set to "Keyboard - Pro Keys 3"](https://carlmylo.github.io/docu-rpcs3/images/instruments/midictrlrpcs3.png "Settings: [BLUS30463] Rock Band 3")

That's it. Remember to close all **three different programs** when you're not using them because they may cause issues with certain shortcuts on Windows.
You will have to reopen these programs every time you want to play.

[[Back to Controllers]](https://rb3pc.milohax.org/english/controllers/)

Implementation by [[Dark]](https://dark.ski/)
