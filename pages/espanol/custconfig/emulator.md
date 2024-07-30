---
title: Emulator
sidebar: espanol_sidebar
permalink: custom_config_emu_es
folder: espanol
---

![A screenshot of Rock Band 3's Emulator custom settings, showing "Show trophy popups", "Show PPU compilation hint", "Show Shader Compilation hint", "Start Games in fullscreen mode", "Use native user interface."](https://carlmylo.github.io/docu-rpcs3/images/cust/emulator.png "Emulator")

You can leave this as is if you want, but I would consider changing the following options:
* ![A tan square with a solid outline.](https://carlmylo.github.io/docu-rpcs3/images/cust/smalltan.png "Tan Square") **Optional tweaks**: 
	* **"Show trophy popups"** - Mimics the way Trophy notifications appear on the PS3. I personally disable this as the game has its own pop-ups.
	* **"Show PPU compilation hint"** - This creates a popup whenever RPCS3 is compiling units for the PPU. This only comes up once as the "Recompiler (LLVM)" setting in the CPU tab does this when launching the game.
	* **"Show shader compilation hint"** - This creates a popup whenever RPCS3 is compiling shaders. Whether you leave it on or not is up to you, but I should tell you what this means as it is important. When you run PS3 games, it has to compile shaders to "translate" the graphics from a PS3 format to a format your PC can work with. **The game will** appear to **stutter when this happens**. **This happens on ALL computer systems. When it finishes** compiling an effect, **it will usually never happen again**. **The best way to deal with this is** just **to** **play the game** as it will quickly go away. You can also use Rock Band 3 Deluxe's Autoplay modifier to let it go through a few songs in party shuffle and let it compile a decent amount of shaders.
	* **"Start games in Fullscreen mode"** - Switches to Fullscreen when you start Rock Band 3.
	* **"Use Native Interface"** - Removes the pretty displays RPCS3 adds, including notifications and game startup background. It will instead use old school pop-ups. This can also fix a problem with instrument controllers soft locking the game when the keyboard comes up. The native interface also seems to cause slight frame rate drops.

<br/>

{% include links.html %}