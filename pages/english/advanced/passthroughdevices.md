---
title: Passthrough Devices
sidebar: english_sidebar
permalink: adv_passthrough
folder: english
tags: [advanced, english]
summary: "How to add set up passthrough devices for RPCS3."
toc: false
---

If you're playing with a RB3 Mustang Guitar for PlayStation 3 or a RB3 Keyboard PlayStation 3 with their respective dongles, you can connect and play them like on console after a simple setup.

To begin with, make sure you have the correct dongle.

| **Mustang Guitar<br>Dongle** | **Wireless Keyboard<br>Dongle** |
|:------------------:|:---------------------:|
| ![Dongle for the RB3 Mustang Guitar](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/recprotar.png "Dongle for the RB3 Mustang Guitar") | ![Dongle for the RB3 Wireless Keyboard](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/reckeys.png "Dongle for the RB3 Wireless Keyboard") |

After making sure you have the correct dongle, **close out RPCS3** **and plug in the instrument's dongle** to your computer.

Now, [**\[go to Zadig's website\]**](https://zadig.akeo.ie/){:target="_blank"} and **download the latest version, then open it** up.

Click on **Options** then **List All Devices**.  
![A screenshot of Zadig showing "List All Devices" under "Options" highlighted.](https://carlmylo.github.io/docu-rpcs3/images/pass/zadiglistall.png "Zadig: Options: List All Devices")

You should now see devices listed. **Switch it to your Rock Band 3 Pro Instrument**. In this example, we're using the Mustang Pro Guitar, which shows up as "Harmonix RB3 Mustang Guitar for PlayStation® 3".  
![A screenshot of Zadig showing "Harmonix RB3 Mustang Guitar for PlayStation® 3" highlighted in the devices listed.](https://carlmylo.github.io/docu-rpcs3/images/pass/zadigsel.png "Zadig: Harmonix RB3 Mustang Guitar for PlayStation® 3")

**After selecting the right device, you should see the option to replace the driver. _MAKE SURE YOU ARE REPLACING THE DRIVER ONLY FOR THE PRO GUITAR/KEYBOARD!!_** Click Replace Driver.  
![A screenshot of Zadig with "Replace Driver" highlighted.](https://carlmylo.github.io/docu-rpcs3/images/pass/zadigreplace.png "Zadig: Replace Driver")

A warning will appear. **Again, make sure you have selected your RB3 Pro Guitar or keyboard instrument.** After you have made sure, **click** "**Yes**."  
![A screenshot of Zadig warning the user that they're about to modify a system driver, with "Yes" highlighted](https://carlmylo.github.io/docu-rpcs3/images/pass/zadigreplace.png "Zadig: Warning - System Driver")

It will then install the driver. As the program says, it may take a few minutes.  
![A screenshot of Zadig in the middle of a driver install.](https://carlmylo.github.io/docu-rpcs3/images/pass/zadigprogress.png "Zadig: Installing Driver...")


If everything goes well, you will get this message:  
![A screenshot of Zadig telling the user that the driver was installed successfully with "Close" highlighted.](https://carlmylo.github.io/docu-rpcs3/images/pass/zadigdone.png "Zadig: Success")

**Close Zadig** and, **with the dongle** still **connected**, **open up RPCS3** and **open Rock Band 3**.

Turn your controller on and you should see it automatically assign a player number.  
![A picture of a Mustang Pro Guitar with the second player LED lit up.](https://carlmylo.github.io/docu-rpcs3/images/pass/protaron.png "Fender Mustang Pro Guitar: Player 2")

Likewise, in Rock Band 3, you will see the instrument ready to join.  
![A screenshot of Rock Band 3 with a Pro Guitar ready to join.](https://carlmylo.github.io/docu-rpcs3/images/pass/rb3player.png "Rock Band 3: Pro Guitar ready to join")

{% include links.html %}