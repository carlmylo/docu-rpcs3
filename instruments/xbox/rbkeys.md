---
title: Xbox 360 Rock Band Wireless Keyboard
sidebar: controllers_sidebar
permalink: ctrls_keys_360
folder: instruments
toc: false
---

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/plat/360.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/cont/360rbkeyscontroller.png" alt="Controller" title="Controller"></div>

## NOTES

* There is no binding file.
* **Do NOT map this instrument via Gamepad Configuration.**
* None of the controller buttons will work as intended as the keyboard will be in MIDI mode.
* Requires the latest version of [[RPCS3]](https://rpcs3.net/download)
* RPCN Menus (for sending or accepting online invites) will cause a softlock. You will need an alternative input method to navigate these menus, such as a typing keyboard or a gamepad.

## Instructions

There are two different ways to connect this keyboard. Pick whichever is the most convenient for you:

<ul id="profileTabs" class="nav nav-tabs">
    <li class="active"><a href="#360rec" data-toggle="tab">Xbox 360 Wireless Gaming Receiver</a></li>
    <li><a href="#miditousb" data-toggle="tab">MIDI to USB interface</a></li>
</ul>
  <div class="tab-content">
<div role="tabpanel" class="tab-pane active" id="360rec">
    <h2>Connecting with the Xbox 360 Wireless Gaming Receiver</h2>
<p>You will need an Xbox 360 Wireless Gaming Receiver for Windows to connect your keyboard to your computer.</p>
<blockquote>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/360/receiver.png" alt="Xbox 360 Wireless Gaming Receiver for Windows" title="Xbox 360 Wireless Gaming Receiver for Windows"></p>
</blockquote>
<p>First, <a href="https://www.tobias-erichsen.de/software/loopmidi.html">[download loopMIDI]</a>.</p>
<blockquote>
<p><a href="https://www.tobias-erichsen.de/software/loopmidi.html" title="Tobias Erichsen - loopMIDI"><img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlloopMIDIdl.png" alt="A screenshot of loopMIDI's download page."></a></p>
</blockquote>
<p>Install loopMIDI. <strong>Launch it after it finishes.</strong></p>
<blockquote>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlloopMIDIinst.png" alt="A screenshot of loopMIDI's installer." title="loopMIDI Setup"></p>
</blockquote>
<p>Add two new ports by clicking on the <code>+</code> button in the bottom. You should name the ports, too. It’s been named “Pro Keys” in this example.</p>
<blockquote>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/360ctrlloopMIDI.png" alt="A screenshot of loopMIDI, with a mouse cursor over the Plus symbol for &quot;Add Port&quot;. Additionally, &quot;New port name&quot; is highlighted in blue with a dotted outline, with &quot;Pro Keys&quot; typed out in the text field." title="loopMIDI"></p>
</blockquote>
<p>Now, <a href="https://github.com/TheNathannator/RB3_X360_Keyboard/releases">[download the latest version of RB3_X360_Keyboard by TheNathannator.]</a></p>
<blockquote>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/360ctrlkeysappdl.png" alt="A screenshot of Github, showing a release for RB3_X360_Keyboard, with a cursor hovering the download." title="GitHub: RB3_X360_Keyboard"></p>
</blockquote>
<p>Extract it and open it.</p>
<blockquote>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/360ctrlkeysappopen.png" alt="A screenshot of RB3_X360_Keyboard.exe in its folder, with a cursor hovering it." title="RB3_X360_Keyboard"></p>
</blockquote>
<p>In RB3_X360_Keyboard, set the output type to the port you made earlier and select the port you made earlier.<br>
After that, click the Start button on the right side.</p>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/360ctrlkeysapp1.png" alt="A screenshot of RB3_X360_Keyboard, showing &quot;MIDI&quot; in the &quot;Output Type&quot; section set to &quot;Pro Keys&quot; and highlighted in blue with a dotted outline. &quot;Start&quot; is highlighted in tan with a solid outline" title="RB3_X360_Keyboard"></p>
</div>
<div role="tabpanel" class="tab-pane" id="miditousb">
    <h2>Connecting with a MIDI to USB interface</h2>
    <p>You will need to connect to your keyboard via the MIDI port on the side.</p>
<blockquote>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/midi/rbkeys.png" alt="A picture of a Rock Band 3's Wireless Keyboard, showing a 5-DIN MIDI input and output highlighted in blue with a dotted white outline." title="Rock Band Wireless Keyboard"></p>
</blockquote>
<p><strong>For this, you will need a MIDI to USB interface</strong>.</p>
<p>Here’s an example of a MIDI to USB interface. Most will come with an LED indicator to show activity. <strong>To check that you’ve plugged it in correctly, you should see “MIDI In” blinking when you press a key</strong>.</p>
<blockquote>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/midi/miditousb.png" alt="A picture of a MIDI to USB interface." title="MIDI to USB interface"></p>
</blockquote>
<p><strong>If you have an audio interface, you may already have a way to plug in MIDI</strong> to your computer, as some audio interfaces come with MIDI inputs. For example, this Scarlett has MIDI connections in the back.</p>
<blockquote>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/midi/midifs.png" alt="A picture of a Focusrite Scarlett's rear, showing a USB port, and 5-DIN MIDI input and output." title="Focusrite Scarlett MIDI in/out"></p>
</blockquote>
</div>
</div>


After that, **right click on Rock Band 3** in RPCS3, then click on “**Change Custom Configuration**”.  

![A screenshot of RPCS3's right click menu, showing "Change Custom Configuration" highlighted](https://carlmylo.github.io/docu-rpcs3/images/cust/rpcs3customconfigchange.png "Change Custom Configuration")

![A screenshot of Rock Band 3's I/O custom settings, showing Emulated MIDI Devices, device type, and device selection highlighted in tan with a solid outline.](https://carlmylo.github.io/docu-rpcs3/images/cust/io.png "I/O")

* ![A tan square with a solid outline](https://carlmylo.github.io/docu-rpcs3/images/cust/smalltan.png "Tan Square"):  
	* 🎹 **Leave your "Emulated MIDI type" on "Keyboard" and select your MIDI interface in the drop-down menu next to it.**.

### Additional Information

Since the keyboard controller buttons don't function like they do when connected with a dongle, you will have to shift octaves to access the buttons on the keys.

You can shift octaves with the X and B buttons.

![A GIF of a Rock Band 3 keyboard. When X is pressed, a yellow highlight, showing which notes are being used, shifts down to C to C4. When B is pressed, it shifts up to C3 to C5.](https://carlmylo.github.io/docu-rpcs3/images/instruments/rbkeysoctshift.gif "Octave Shifting") 

#### Using a computer keyboard along with a 25 key keyboard.

If you insist on using a 25 key keyboard without drum pads, you can use your regular computer keyboard and convert its key presses to the MIDI notes that correspond to the game buttons.
First, [[download loopMIDI]](https://www.tobias-erichsen.de/software/loopmidi.html).

[![A screenshot of loopMIDI's download page.](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlloopMIDIdl.png)](https://www.tobias-erichsen.de/software/loopmidi.html "Tobias Erichsen - loopMIDI")

Install loopMIDI. **Launch it after it finishes.**

![A screenshot of loopMIDI's installer.](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlloopMIDIinst.png "loopMIDI Setup")

Add two new ports by clicking on the `+` button in the bottom. You should name the ports, too. They've been named "Pro Keys" and "Gamepad" in this example.

![A screenshot of loopMIDI, with a mouse cursor over the Plus symbol for "Add Port". Additionally, "New port name" is highlighted in blue with a dotted outline, with "Pro Keys" typed out in the text field.](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlloopMIDIaddport.png "loopMIDI")

Now, [[the `.zip` archive that contains the win64 version of FreePiano]](https://freepiano.tiwb.com/en/).

[![A screenshot of FreePiano's download page.](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlfreepnodl.png)](https://freepiano.tiwb.com/en "FreePiano - Advanced virtual MIDI keyboard")

Extract the `.zip` archive somewhere you can easily find it. It was extracted to `C:\Games\freepiano` in this example.

Go to where you extracted FreePiano and run the `freepiano` executable.

![A screenshot showing the FreePiano executable highlighted.](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlfreepnodir.png "freepiano.exe")

Assign the keys to your liking as shown in the [**[#mapping]**](#mapping) section above.

There is also a premade profile if you'd like, which you can [**[download here]**](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/rb3gamekeys.map).

To use the preset, place the `rb3gamekeys.map` file in the `keymap` folder located where you extracted FreePiano.

![A screenshot of the profile, named rb3gamekeys.map, in the keymap folder, highlighted.](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlfreepnopreset.png "keymap")

Select `rb3gamekeys.map` in the "Keymap" dropdown button to load the premade profile. Likewise, if you made your own profile or edited the premade profile, you can click on **Save** to save your profile.

![A screenshot of FreePiano, with the rb3gamekeys.map profile selected.](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlfreepnoselpres.png "rb3gamekeys.map")

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

![A screenshot of FreePiano's Instrument dropdown menu, with "Gamepad MIDI" selected.](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlfreepnoout.png "Gamepad")

It's suggested you enable "Background input mode", located within the "Options" tab which is accessed by pressing the Wrench icon in the top right side of FreePiano.

![A screenshot of FreePiano, with the "Background input mode" enabled.](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlfreepnoback.png "Background input mode")

Now, [[download MIDI-OX]](http://www.midiox.com/moxdown.htm).

![A screenshot of MIDI-OX's website, with the proper download highlighted in blue with a dotted outline.](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlmidioxdl.png "MIDI-OX 7.0.2")

Install MIDI-OX.

![A screenshot of MIDI-OX's installer.](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlmidioxinst.png "MIDI-OX Setup Wizard")

Open MIDI-OX then navigate to **Options > MIDI Devices**

![A screenshot of MIDI-OX, with the mouse hovering over the MIDI Devices menu, under the Options menu.](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlmidioxopts.png "Options > Midi Devices")

In the MIDI Devices Menu, select your keyboard and the port you made in loopMIDI ("Gamepad") for FreePiano in the MIDI Inputs section.
Select the other port you made in loopMIDI ("Pro Keys") in the MIDI Outputs. This will combine both MIDI inputs into a single output.

![A screenshot of MIDI-OX's MIDI Devices, with a keyboard and the Gamepad selected in the MIDI Inputs section and Pro Keys selected in the MIDI Outputs section.](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlmidioxcombo.png "MIDI Devices")

Finally, in RPCS3, go to Rock Band 3's Custom Configuration then go to the I/O tab. Select the port that you selected as your output in MIDI-OX ("Pro Keys").

![A screenshot of Rock Band 3's I/O custom settings, showing Emulated MIDI Devices, device type, and device selection highlighted in tan with a solid outline. It is set to "Keyboard - Pro Keys 3"](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlrpcs3.png "Settings: [BLUS30463] Rock Band 3")

That's it. Remember to close all **three different programs** when you're not using them because they may cause issues with certain shortcuts on Windows.
You will have to reopen these programs every time you want to play.

[[Back to Controllers]](https://rb3pc.milohax.org/english/controllers/)

Research by [[Linos]](https://www.youtube.com/@LinosMelendi)
Wireless connection research by [[gonakil1ya]](https://linktr.ee/Gonakil1ya)