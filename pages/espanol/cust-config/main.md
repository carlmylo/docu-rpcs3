---
title: "Configuración Personalizada"
sidebar: espanol_sidebar
permalink: custom_config_es
folder: espanol
toc: false
tags: [conf-pers, espanol]
summary: "Como crear o editar una configuración personalizada de RPCS3"
---

Aunque la configuración rápida es buena para la mayoría de las personas, algunos prefieren hacer sus propios ajustes para sacar el máximo rendimiento de su configuración. Esto involucra crear una configuración personalizada para Rock Band 3.

<ul id="confeditTabs" class="nav nav-tabs">
    <li class="active"><a href="#changecustomconfig" data-toggle="tab">Cambiando una configuración personalizada</a></li>
    <li><a href="#createcustomconfig" data-toggle="tab">Creando una configuración personalizada</a></li>
</ul>
  <div class="tab-content">
<div role="tabpanel" class="tab-pane active" id="changecustomconfig">
<p>Si quieres cambiar una configuración personalizada, <strong>haz click derecho en Rock Band 3</strong> en RPCS3, luego presiona “<strong>Change Custom Configuration</strong>” (Cambiar Configuración Personalizada)<br>
<img src="https://carlmylo.github.io/docu-rpcs3/images/cust/rpcs3customconfigchange.png" alt="Una captura del menú de clic derecho de RPCS3, mostrando &quot;Change Custom Configuration&quot; (Cambiar configuración personalizada) resaltado" title="Change Custom Configuration"></p></div>
<div role="tabpanel" class="tab-pane" id="createcustomconfig">
<p>Si no tienes una configuración personalizada, <strong>haz click derecho en Rock Band 3</strong> en RPCS3, luego presiona “<strong>Create Custom Configuration From Default Settings</strong>” (Crear configuración personalizada basada en la configuración por defecto)<br>
<img src="https://carlmylo.github.io/docu-rpcs3/images/cust/rpcs3customconfig.png" alt="Una captura del menú de clic derecho de RPCS3, mostrando &quot;Create Custom Configuration From Default Settings&quot; resaltado" title="Create Custom Configuration From Default Settings"></p></div>
</div>

**¡Recuerda de hacer click en "Apply" (Aplicar) y luego "Save custom configuration" (Guardar configuración personalizada) después de hacer ajustes!!**
Toma en cuenta que vas a necesitar reiniciar el juego para aplicar mayoría de estos ajustes.  
![Una captura de la configuración personalizada de Rock Band 3 dentro de RPCS3 con el ratón sobre "Save custom configuration".](https://carlmylo.github.io/docu-rpcs3/images/cust/save.png "Settings: [BLUS30463] Rock Band 3")

## Guía de Colores

Esto puede parecer demasiado difícil por la gran cantidad de opciones, pero he coloreado las cosas que vas a ajustar. Todo lo que no esté coloreado debe estar en las opciones predeterminadas.

| COLOR | SIGNIFICADO |
|---|---|
| ![Un cuadro verde con una línea discontinua.](https://carlmylo.github.io/docu-rpcs3/images/cust/biggreen.png "Cuadro verde") | **REQUERIDO** |
| ![Un cuadro azul con contorno punteado.](https://carlmylo.github.io/docu-rpcs3/images/cust/bigblue.png "Cuadro azul") | **Para Rendimiento** |
| ![Un cuadro bronceado con un contorno solido.](https://carlmylo.github.io/docu-rpcs3/images/cust/bigtan.png "Cuadro bronceado") | **Recomendado** |

<br/>

## Custom Configuration

<ul id="configTabs" class="nav nav-tabs">
    <li class="active"><a href="#cpu" data-toggle="tab">CPU</a></li>
    <li><a href="#gpu" data-toggle="tab">GPU</a></li>
    <li><a href="#audio" data-toggle="tab">Audio</a></li>
    <li><a href="#io" data-toggle="tab">I/O</a></li>
    <li><a href="#network" data-toggle="tab">Network</a></li>
    <li><a href="#advanced" data-toggle="tab">Advanced</a></li>
    <li><a href="#emulator" data-toggle="tab">Emulator</a></li>
</ul>
  <div class="tab-content">
<div role="tabpanel" class="tab-pane active" id="cpu">
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/cust/cpu.png" alt="Una captura de la configuración personalizada de CPU para Rock Band 3, mostrando SPU XFloat Accuracy, Thread Scheduler, SPU Block Size, y Preferred SPU Threads resaltados en cuadros azules con contornos punteados." title="CPU"></p>
<ul>
<li><img src="https://carlmylo.github.io/docu-rpcs3/images/cust/smallblue.png" alt="Un cuadro azul con contorno punteado." title="Cuadro azul"> <strong>Rendimiento mejorado, dependiendo en tu sistema</strong>:
<ul>
<li><strong>Cambia el "SPU Block Size"</strong> (Tamaño de bloques del SPU) <strong>a "Mega""</strong> - Para juntar hilos de SPU a ser más pequeños, requiriendo menos núcleos/hilos. También tardara menos tiempo para iniciar el juego, dependiendo en tu sistema.</li>
<li><strong>Cambia el "Preferred SPU Threads"</strong> (Hilos preferidos del SPU) <strong>a “1”, “2”, “3” o “4”</strong> - Puede ayudar a prevenir inestabilidades causadas por sobrecargas de la CPU. <strong>Empieza con 4 y bájalo si no mejora</strong>.</li>
<li><strong>Cambia "Thread Scheduler"</strong> (Programador de hilos) <strong>a “RPCS3 Scheduler”</strong> (RPCS3 Scheduler) <strong>o “RPCS3 Alternative Scheduler”</strong>(Programador alternativo RPCS3) - <strong>¡SOLO PARA CPUs CON MÁS DE 12 HILOS!</strong>Puede ayudar con la distribución de procesos para ayudar con rendimiento.</li>
</ul>
</li>
</ul>
</div>
<div role="tabpanel" class="tab-pane" id="gpu">
    <p><img src="https://carlmylo.github.io/docu-rpcs3/images/cust/gpu.png" alt="Una captura de la configuración personalizada de la GPU de Rock Band 3, resaltando Write Color Settings en un cuadro verde con una línea discontinua, ZCULL Accuracy, Resolution Scale, Anisotropic Filtering, Anti-Alising, Framelimit, Output Scaling y VSync resaltados en un cuadro azul con contorno punteado." title="GPU"></p>
<ul>
<li>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/cust/smallgreen.png" alt="Un cuadro verde con una línea discontinua." title="Cuadro verde"> <strong>REQUERIDO</strong>:</p>
<ul>
<li><strong>Activa "Write Color Buffers</strong> (Ingresar búferes de colores) - Los personajes tendrán rendimiento corrupto sin esta opción.</li>
</ul>
</li>
<li>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/cust/smallblue.png" alt="Un cuadro azul con contorno punteado." title="Cuadro azul"> <strong>Dependiendo en tu PC</strong>:</p>
<ul>
<li><strong>Activa "VSync"</strong> (Sincronización vertical) - Reduce el efecto de rasgado de pantalla y da fotogramas mas estables. Incrementa la latencia pero casi no se puede sentir. <strong>¡No uses esto con "Frame Limit" activado!</strong></li>
<li><strong>Cambia "Frame Limit"</strong>(Limite de fotogramas):
<ul>
<li>A "Off" (Desactivado) si quieres tener fotogramas altas (VBlank Frequency). Esto puede introducir agitación en el rendimiento del juego. Usa esta opción si tienes VSync activada.</li>
<li>"Auto" va usar lo predeterminado de RPCS3.</li>
<li>Recomendamos usando el panel de control de tu tarjeta de gráficas para limitar la fotogramas o utilizar un programa como MSI Afterburner.</li>
<li>Aumentando las fotogramas sobre 60 utiliza muchos más recursos. No es recomendado para sistemas de gama baja.</li>
<li>Fotogramas sobre 60 pueden causar problemas con la detección de vocales.</li>
<li>Recomendamos que desactives VSync dentro de Rock Band 3 Deluxe <br> <code>Menú &gt; Opciones &gt; Configuración Deluxe &gt; Gráficos &gt; VSync</code></li>
</ul>
</li>
<li><strong>Cambia "ZCULL Accuracy"</strong> (Precisión de ZCull) <strong>a "Relaxed"</strong> (Relajada) - Mejora el rendimiento un poco pero puede causar anomalías gráficas.</li>
<li><strong>Ajusta "Anisotropic Filter"</strong> (filtro anisotrópico) a tu gusto y a lo que puede tu computadora. Ayuda con texturas. No debe de afectar el rendimiento tanto.</li>
<li><strong>Ajusta "Resolution Scale"</strong> (Nivel de resolución) a tu gusto y a lo que puede tu computadora. Auméntala para obtener gráficos más nítidos.</li>
<li><strong>Cambia "Output Scaling"</strong> (Algoritmo de resolución) a tu gusto y a lo que puede tu computadora. Esto afecta cómo se va "estirar" la imagen para llegar a la resolución de tu pantalla usando diferentes métodos de interpolación. Puede ayudar a los que tienen su nivel de resolución (mencionado arriba) en 100%.
<ul>
<li>"Nearest" (aproximación) es la interpolación mas cruda. Si la resolución del juego no es exacta a la de tu pantalla, puede resultar en pixelización.</li>
<li>Bilinear (bilineal) es interpolación mas suave. Si la resolución del juego no es exacta a la de tu pantalla, puede resultar en una imagen borrosa.</li>
<li>FidelityFX Super Resolution (FSR) usa calculaciones complejas para mejorar la imagen cuando se estira a la resolución de tu pantalla. Raramente, puede causar anormalidades en la imagen.
<ul>
<li>Puedes usar "RCAS Sharpening Strength" (fuerza de enfoque) abajo para ajustar cuanta fuerza tiene el efecto.</li>
</ul>
</li>
</ul>
</li>
</ul>
</li>
</ul>
</div>
<div role="tabpanel" class="tab-pane" id="audio">
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/cust/audio.png" alt="Una captura de la configuración personalizada de audio de Rock Band 3, que muestra Enable Buffering resaltado en un cuadro verde con una línea discontinua, Audio Out y Audio Buffer Duration resaltados en cuadros azules con contornos punteados, y Microphone Settings, Microphone Type: Standard, Mic1, Mic2, Mic3 y Mic4 resaltados en un cuadro bronceado con contorno solido" title="Audio"></p>
<ul>
<li>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/cust/smallblue.png" alt="Un cuadro azul con contorno punteado." title="Cuadro azul"> <strong>Tweak depending on audio hardware and CPU</strong>:</p>
<ul>
<li><strong>Adjust “Audio Buffer Duration”</strong> depending on system. Ideally you want this as low as possible.
<ul>
<li>Lower values give you less audio latency but use more CPU.</li>
<li>Higher values give you more audio latency but use less CPU.</li>
<li>Vocalists are affected the most by this, as a higher latency creates a distracting echo. Instrument players can use calibration to compensate regardless of audio buffer setting.</li>
<li>You can change this while the game is running, but it will require re-calibrating in Rock Band 3’s system settings.</li>
</ul>
</li>
<li><strong>Change “Audio Out” to “XAudio2” in extremely rare circumstances</strong> - <strong>Most users should stay on Cubeb</strong>, a few users have experienced better performance with XAudio2. Only do this if you absolutely need to!</li>
</ul>
</li>
<li>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/cust/smalltan.png" alt="A tan square with a solid outline." title="Tan Square"> <strong>For Vocalists</strong>:</p>
<ul>
<li><strong>Set Microphone type to Standard or Rocksmith</strong>.</li>
<li><strong>Select an input device in “Mic1”, “Mic2”, and “Mic3”</strong> for vocals. If not playing vocals, Mic1 will be used for voice chat.</li>
<li>Once again, keep in mind that playing with framerates higher than 60 may cause issues with vocal detection.</li>
</ul>
</li>
</ul>
</div>
<div role="tabpanel" class="tab-pane" id="io">
<p><strong>This section is for people playing with USB/MIDI Keyboards, Pro Guitars, or MIDI Drums!</strong></p>
<ul>
<li><strong>If you're not playing with a wired Pro Guitar, Pro Drums, or a USB/MIDI keyboard, you can skip this section.</strong></li>
<li><strong>If you're playing with a PS3 Rock Band 3 Keyboard or wireless PS3 Mustang Pro Guitar,</strong> visit the <a href="https://carlmylo.github.io/docu-rpcs3/adv_passthrough" target="_blank">><strong>[[Passthrough Devices]]</strong></a>section. </li>
</ul>
<p><strong>Make sure your MIDI instrument is connected.</strong> After that, let's go ahead and <strong>focus on RPCS3’s I/O tab.</strong><br>
<strong>YOU MAY HAVE TO MAKE THE WINDOW WIDER TO READ THE OPTIONS!</strong><br>
<img src="https://carlmylo.github.io/docu-rpcs3/images/cust/io.png" alt="A screenshot of Rock Band 3's I/O custom settings, showing Emulated MIDI Devices, device type, and device selection highlighted in tan with a solid outline, and Pad Handler Mode highlighted in blue with a dotted outline." title="I/O"></p>
<ul>
<li><img src="https://carlmylo.github.io/docu-rpcs3/images/cust/smalltan.png" alt="A tan square with a solid outline." title="Tan Square"> <strong>For third party Keyboard, wired Pro Guitar, and Pro Drums players</strong>:
<ul>
<li>🎹 <strong>Keyboard Players: Leave your “Emulated MIDI type” on “Keyboard” and select your keyboard or MIDI interface in the drop-down menu next to it</strong>.</li>
<li>🎸 <strong>Pro Guitar Players: Change your “Emulated MIDI type” from “Keyboard” to “Guitar (17 Frets)” if you have a Mustang Pro Guitar, or “Guitar (22 Frets)” if you have a Squier Pro Guitar, then select your MIDI to USB interface in the drop-down menu next to it</strong>.</li>
<li>🥁 <strong>Pro Drums Players: Change your “Emulated MIDI type” from “Keyboard” to “Drums”, then select your Electronic MIDI Drum Kit or MIDI to USB interface in the drop-down menu next to it</strong>.</li>
</ul>
</li>
</ul>
<p>Revisit the <a href="https://carlmylo.github.io/docu-rpcs3/ctrls_full" target="_blank">[Controllers page]</a> if you need help.</p>
</div>
<div role="tabpanel" class="tab-pane" id="network">
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/cust/network.png" alt="A screenshot of Rock Band 3's Network custom settings, highlighting Network Status (Connected) in green with a dashed outline, IP/Hosts switches (set to rb3ps3live.hmxservices.com=45.33.44.103), PSN Status (RPCN), and Enable UPNP (not checked) highlighted in tan with a solid outline." title="Network"></p>
<ul>
<li>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/cust/smallgreen.png" alt="Un cuadro verde con una línea discontinua." title="Cuadro verde"> <strong>REQUIRED</strong>:</p>
<ul>
<li><strong>Change the Network Status to “Connected” as highlighted in the picture. If left on “Disconnected,” the game will temporarily freeze when browsing the song library.</strong></li>
</ul>
</li>
<li>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/cust/smalltan.png" alt="A tan square with a solid outline." title="Tan Square"> <strong>For online</strong>:</p>
<ul>
<li>You can tick <strong>“Enable UPNP”</strong> or <strong>forward port 9103 (UDP) in your firewall</strong>.</li>
<li>Add Rock Band Enhanced's Server IP.
<ul>
<li>Set IP/Hosts switches to <code>rb3ps3live.hmxservices.com=45.33.44.103</code>.</li>
</ul>
</li>
</ul>
</li>
</ul>
</div>
<div role="tabpanel" class="tab-pane" id="advanced">
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/cust/advanced.png" alt="A screenshot of Rock Band 3's Advanced custom settings, highlighting Driver Wake-Up Delay (1µ) in green with a dashed outline, &quot;Exclusive Fullscreen Mode, VBlank Frequency, and Maximum Number of SPURS Threads highlighted in blue with a dotted outline, and Debug Console Mode highlighted in tan with a solid outline." title="Advanced"></p>
<ul>
<li>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/cust/smallgreen.png" alt="Un cuadro verde con una línea discontinua." title="Cuadro verde"> <strong>REQUIRED</strong>:</p>
<ul>
<li><strong>Change “Driver Wake-up Delay” to “20µ”</strong> to avoid crashing after a few songs. Increase it to “40µ” if the issue persists. If it keeps happening, keep increasing it by increments of 20.</li>
</ul>
</li>
<li>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/cust/smallblue.png" alt="Un cuadro azul con contorno punteado." title="Tan Square"> <strong>Depending on your computer</strong>:</p>
<ul>
<li><strong>Adjust VBlank Frequency</strong> if you want a higher internal framerate. This can make it easier to hit notes but may cause graphical instability and connection issues while online. <strong>It's best left alone</strong> and not recommended to go above 75 Hz if adjusting it for online play. Increasing it exponentially uses more CPU and GPU.
<ul>
<li>Once again, having a higher VBlank can cause issues with vocal detection.</li>
</ul>
</li>
<li><strong>Change “Maximum Number of SPURS Threads”</strong> - May improve performance on older systems with less cores and threads <a href="https://github.com/hmxmilohax/rb3-pc/issues/12#issue-1955946005" target="_blank">[like 4th gen Intel i5 CPUs with 4 cores and 4 threads]</a>.</li>
</ul>
</li>
<li>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/cust/smalltan.png" alt="A tan square with a solid outline." title="Tan Square"> <strong>Strongly Suggested</strong>:</p>
<ul>
<li><strong>Enable “Debug Console Mode”</strong> - Enabling this and “Large Heap” in Rock Band 3 Deluxe will allow Rock Band 3  to have more memory. This means more songs (up to 16000) and increased stability. Everyone should enable this! <a href="https://carlmylo.github.io/docu-rpcs3/adv_himem" target="_blank">[Click here for more information.]</a></li>
<li><strong>Change “Exclusive Fullscreen Mode” to “Prefer borderless fullscreen”</strong> to prevent potential crashes and audio desync when changing from Rock Band 3 to another program while in fullscreen.</li>
</ul>
</li>
</ul>
</div>
<div role="tabpanel" class="tab-pane" id="emulator">
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/cust/emulator.png" alt="A screenshot of Rock Band 3's Emulator custom settings, showing &quot;Show trophy popups&quot;, &quot;Show PPU compilation hint&quot;, &quot;Show Shader Compilation hint&quot;, &quot;Start Games in fullscreen mode&quot;, &quot;Use native user interface.&quot;" title="Emulator"></p>
<p>You can leave this as is if you want, but I would consider changing the following options:</p>
<ul>
<li><img src="https://carlmylo.github.io/docu-rpcs3/images/cust/smalltan.png" alt="A tan square with a solid outline." title="Tan Square"> <strong>Optional tweaks</strong>:
<ul>
<li><strong>"Show trophy popups"</strong> - Mimics the way Trophy notifications appear on the PS3. I personally disable this as the game has its own pop-ups.</li>
<li><strong>"Show PPU compilation hint"</strong> - This creates a popup whenever RPCS3 is compiling units for the PPU. This only comes up once as the “Recompiler (LLVM)” setting in the CPU tab does this when launching the game.</li>
<li><strong>"Show shader compilation hint"</strong> - This creates a popup whenever RPCS3 is compiling shaders. Whether you leave it on or not is up to you, but I should tell you what this means as it is important. When you run PS3 games, it has to compile shaders to “translate” the graphics from a PS3 format to a format your PC can work with. <strong>The game will</strong> appear to <strong>stutter when this happens</strong>. <strong>This happens on ALL computer systems. When it finishes</strong> compiling an effect, <strong>it will usually never happen again</strong>. <strong>The best way to deal with this is</strong> just <strong>to</strong> <strong>play the game</strong> as it will quickly go away. You can also use Rock Band 3 Deluxe's Autoplay modifier to let it go through a few songs in party shuffle and let it compile a decent amount of shaders.</li>
<li><strong>"Start games in Fullscreen mode"</strong> - Switches to Fullscreen when you start Rock Band 3.</li>
<li><strong>"Use Native Interface"</strong> - Removes the pretty displays RPCS3 adds, including notifications and game startup background. It will instead use old school pop-ups. This can also fix a problem with instrument controllers soft locking the game when the keyboard comes up. The native interface also seems to cause slight frame rate drops.</li>
</ul>
</li>
</ul>
</div>
</div>


{% include links.html %}