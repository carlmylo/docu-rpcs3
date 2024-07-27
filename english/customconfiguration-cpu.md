---
title: CPU
sidebar: en_sidebar
permalink: encustom_config_cpu.html
folder: english
---

| COLOR | MEANING |
|---|---|
| ![A green square with a dashed outline.](https://carlmylo.github.io/docu-rpcs3/images/cust/biggreen.png "Green Square") | **REQUIRED** |
| ![A blue square with a dotted outline.](https://carlmylo.github.io/docu-rpcs3/images/cust/bigblue.png "Blue Square") | **Performance Tweaks** |
| ![A tan square with a solid outline.](https://carlmylo.github.io/docu-rpcs3/images/cust/bigtan.png "Tan Square") | **Recommended** |

<br/>

## CPU

![A screenshot of Rock Band 3's CPU custom settings, showing SPU XFloat Accuracy, SPU Block Size, Preferred SPU Threads, and Thread Scheduler highlighted in blue with a dotted outline.](https://carlmylo.github.io/docu-rpcs3/images/cust/cpu.png "CPU")

* ![A blue square with a dotted outline.](https://carlmylo.github.io/docu-rpcs3/images/cust/smallblue.png "Tan Square") **Improved performance, depending on machine**: 
	* **Change "SPU Block Size" to "Mega"** - Ties smaller SPU compiled together, which can help machines with fewer cores/threads. Drastically speeds up game startup time on certain machines.
	* **Change "Preferred SPU Threads" to "1", "2", "3", or "4"** - May help prevent stutter caused by CPU overloads on systems with fewer cores/threads. **Start at 4 and lower it one by one until it improves**.
	* **Change "Thread Scheduler" to "RPCS3 Scheduler", or "RPCS3 Alternative Scheduler"** - **FOR CPUs WITH 12+ THREADS ONLY!** May help with thread distribution to prevent microstutters.

<br/>

{% include links.html %}