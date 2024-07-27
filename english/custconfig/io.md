---
title: I/O
sidebar: english_sidebar
permalink: custom_config_io
folder: english
---

**This section is for people playing with USB/MIDI Keyboards, Pro Guitars, or MIDI Drums!**
* **If you're not playing with a wired Pro Guitar, Pro Drums, or a USB/MIDI keyboard,** [[**skip** over **this section**].](https://carlmylo.github.io/docu-rpcs3/custom_config_net)  
* **If you're playing with a PS3 Rock Band 3 Keyboard or wireless PS3 Mustang Pro Guitar,** [[**skip** over **this section**].](https://carlmylo.github.io/docu-rpcs3/custom_config_net)  

**If your keyboard has a USB port**, all you need to do is **plug it into your computer**.  

>![A picture of a MIDI controller's back, showing a USB port and a sustain pedal](https://carlmylo.github.io/docu-rpcs3/images/midi/usbkeys.png "USB Keyboard")  

**If your keyboard only has a MIDI output, you will need a MIDI to USB interface**.

>![A picture of a MIDI controller's back, showing a 5-DIN MIDI input and output highlighted in yellow with a solid white outline, and multiple pedal inputs.](https://carlmylo.github.io/docu-rpcs3/images/midi/midikeys.png "MIDI Keyboard")  

**The same applies to Rock Band 3 Pro Guitars** as they only have MIDI outputs. However, **they require a MIDI to USB interface with SYSEX support.**

>![A picture of a Rock Band 3 Fender Mustang Pro Guitar, showing a 5-DIN MIDI output.](https://carlmylo.github.io/docu-rpcs3/images/midi/midiprotar.png "Mustang Pro Guitar MIDI Output")  

Here's an example of a MIDI to USB interface. Most will come with an LED indicator to show activity. **To check that you've plugged it in correctly, you should see "MIDI In" blinking when you press a key**. 

>![A picture of a MIDI to USB interface.](https://carlmylo.github.io/docu-rpcs3/images/midi/miditousb.png "MIDI to USB interface")  


**If you have an audio interface, you may already have a way to plug in MIDI** to your computer, as some audio interfaces come with MIDI inputs. For example, this Scarlett has MIDI connections in the back.  
>![A picture of a Focusrite Scarlett's rear, showing a USB port, and 5-DIN MIDI input and output.](https://carlmylo.github.io/docu-rpcs3/images/midi/midifs.png "Focusrite Scarlett MIDI in/out")  

**If everything's connected**, let's go ahead and **focus on RPCS3's I/O tab.**
**YOU MAY HAVE TO MAKE THE WINDOW WIDER TO READ THE OPTIONS!**
![A screenshot of Rock Band 3's I/O custom settings, showing Emulated MIDI Devices, device type, and device selection highlighted in tan with a solid outline, and Pad Handler Mode highlighted in blue with a dotted outline.](https://carlmylo.github.io/docu-rpcs3/images/cust/io.png "I/O")
* ![A tan square with a solid outline.](https://carlmylo.github.io/docu-rpcs3/images/cust/smalltan.png "Tan Square") **For third party Keyboard, wired Pro Guitar, and Pro Drums players**: 
	* 🎹 **Keyboard Players: Leave your "Emulated MIDI type" on "Keyboard" and select your keyboard or MIDI interface in the drop-down menu next to it**.
	* 🎸 **Pro Guitar Players: Change your "Emulated MIDI type" from "Keyboard" to "Guitar (17 Frets)" if you have a Mustang Pro Guitar, or "Guitar (22 Frets)" if you have a Squier Pro Guitar, then select your MIDI to USB interface in the drop-down menu next to it**.
	* 🥁 **Pro Drums Players: Change your "Emulated MIDI type" from "Keyboard" to "Drums", then select your Electronic MIDI Drum Kit or MIDI to USB interface in the drop-down menu next to it**.


Revisit the [[Controllers page]](https://rb3pc.milohax.org/english/controllers) if you need help.

<br/>

{% include links.html %}