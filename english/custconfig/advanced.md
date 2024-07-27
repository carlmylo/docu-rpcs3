---
title: Advanced
sidebar: english_sidebar
permalink: custom_config_adv.html
folder: english
---

![A screenshot of Rock Band 3's Advanced custom settings, highlighting Driver Wake-Up Delay (1µ) in green with a dashed outline, "Exclusive Fullscreen Mode, VBlank Frequency, and Maximum Number of SPURS Threads highlighted in blue with a dotted outline, and Debug Console Mode highlighted in tan with a solid outline.](https://carlmylo.github.io/docu-rpcs3/images/cust/advanced.png "Advanced")

* ![A green square with a dashed outline.](https://carlmylo.github.io/docu-rpcs3/images/cust/smallgreen.png "Green Square") **REQUIRED**: 
	* **Change "Driver Wake-up Delay" to "20µ"** to avoid crashing after a few songs. Increase it to "40µ" if the issue persists. If it keeps happening, keep increasing it by increments of 20.

* ![A blue square with a dotted outline.](https://carlmylo.github.io/docu-rpcs3/images/cust/smallblue.png "Tan Square") **Depending on your computer**: 
	* **Adjust VBlank Frequency** if you want a higher internal framerate. This can make it easier to hit notes but may cause graphical instability and connection issues while online. **It's best left alone** and not recommended to go above 75 Hz if adjusting it for online play. Increasing it exponentially uses more CPU and GPU.
		* Once again, having a higher VBlank can cause issues with vocal detection.
	* **Change "Maximum Number of SPURS Threads"** - May improve performance on older systems with less cores and threads [[like 4th gen Intel i5 CPUs with 4 cores and 4 threads]](https://github.com/hmxmilohax/rb3-pc/issues/12#issue-1955946005).

* ![A tan square with a solid outline.](https://carlmylo.github.io/docu-rpcs3/images/cust/smalltan.png "Tan Square") **Strongly Suggested**: 
	* **Enable "Debug Console Mode"** - Enabling this and "Large Heap" in Rock Band 3 Deluxe will allow Rock Band 3  to have more memory. This means more songs (up to 16000) and increased stability. Everyone should enable this! [[Click here for more information.]](https://rb3pc.milohax.org/espanol/advancedstuff#add-more-memory-to-rock-band-3)
	* **Change "Exclusive Fullscreen Mode" to "Prefer borderless fullscreen"** to prevent potential crashes and audio desync when changing from Rock Band 3 to another program while in fullscreen.

<br/>

{% include links.html %}