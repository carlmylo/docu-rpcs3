---
title: Common
sidebar: english_sidebar
permalink: trbl_common
folder: english
---

## Bugged textures

![A screenshot of Rock Band 3, with a character displaying severe texture issues.](https://carlmylo.github.io/docu-rpcs3/images/trbl/wcb.png "Graphical issues")

You did not follow the guide and did not [**[enable Write Color Buffers in the GPU section]**](https://rb3pc.milohax.org/english/customconfiguration/#gpu).

## Flying instruments

![A screenshot of Rock Band 3, with a character experiencing issues with their hat and guitar.](https://carlmylo.github.io/docu-rpcs3/images/trbl/flyinst.png "Graphical issues")

There is a fix being worked on for this. Stay tuned for further development. Join the [**[the Milohax discord]**](https://rb3dx.milohax.org/discord) if you want to help test.

You can use [**[this list]**](https://rb3pc.milohax.org/extra/teleprob) as a reference for which hats, hairsyles, and microphones to avoid.

## [Online] I crash when joining sessions/searching for players

Your router may have issues with RPCS3's UPNP feature. Go to Rock Band 3's Custom Configuration [[Network section]](https://rb3pc.milohax.org/english/customconfiguration#network), and disable "Enable UPNP." You will need to [[search how to port forward in your router]](https://www.noip.com/support/knowledgebase/general-port-forwarding-guide).

## My game feels off.

Run Calibration in Rock Band 3's System Settings if you haven't for some reason. Disable "Dolby Digital" if you enabled it in the same menu.

## My audio is stuttering/choppy

<iframe width="420" height="315"
src="https://www.youtube.com/embed/UoCMEQbNThs">
</iframe> 

* Increase "Audio Buffer Duration" as mentioned in [[the Audio tab of Rock Band 3's Custom Configuration]](https://rb3pc.milohax.org/english/customconfiguration#audio) until the stuttering stops. 100 ms is a great starting point for low end computers. Alternatively, you can check the general performance issues section right below this.

## General performance issues
* Set your computer to the [[High Performance power plan]](https://help.ableton.com/hc/en-us/articles/115000211304-Using-the-High-performance-power-plan-Windows-).
* Go back to the [[Custom Configuration setup section]](https://rb3pc.milohax.org/english/customconfiguration#changing-a-custom-configuration) and apply suggested low performance tweaks.
* Disable Post Effects in Deluxe Settings.
	* `Menu > Options > Deluxe Settings > Graphics`
* If your motherboard has a Realtek audio chip (most computers), try [[installing the latest driver]](https://realtek-download.com/download-hd/). This is a [[known issue]](https://github.com/RPCS3/rpcs3/issues/14648) where using the default "High Definition Audio" driver doesn't use all threads.
* Close out the dedicated Discord client and open it up in your browser or on your phone. You can also try an alternative Discord client [[like Vesktop]](https://github.com/Vencord/Vesktop), but I claim no responsibility for your Discord account.

{% include links.html %}