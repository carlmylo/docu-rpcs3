---
title: Guitarras Pro de Rock Band 3
sidebar: controllers_es_sidebar
permalink: ctrls_protar_midi_es
folder: instrumentos
tags: [midi, espanol]
summary: "Como configurar guitarras Pro de Rock Band 3 con RPCS3."
toc: false
---

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/plat/midi.png" alt="Sistema" title="Sistema"></div>

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/cont/rbprotar.png" alt="Control" title="Control"></div>

## NOTAS:

* No existe un perfil para este instrumento.
* **NO mapeés este instrumento por el menú de "Pads".**
* Menús de RPCN (para aceptar y mandar invitaciones para jugar en linea) pueden causar que el juego se quede atorado. Es recomendado tener otra manera de controlar estos menos, como [[un teclado de PC o un mando estándar]](https://carlmylo.github.io/docu-rpcs3/ctrls_pads_es){:target="_blank"}.
* Esto es para los jugadores que tienen sus guitarras PRO conectadas con una una interfaz de MIDI a USB.

## Advertencia de SYSEX:

**¡Necesitas una interfaz de MIDI a USB que tome datos SYSEX!** Consulta el manual o el fabricante de tu interfaz para mas detalles.

| Interfaces de MIDI a USB <br> verificadas |
|:------------------:|
| **M-Audio** <br> Midisport Uno |
| **Roland** <br> UM-ONE mk2 |
| **Focusrite** <br> Scarlett (4i4 o mejor) [Gen 3a] |

## Instrucciones:

To connect your Rock Band 3 Pro Guitar, you will need to connect to the MIDI port on the bottom.

>![A picture of a Rock Band 3 Mustang Pro Guitar, showing a 5-DIN MIDI output highlighted in blue with a dotted white outline.](https://carlmylo.github.io/docu-rpcs3/images/midi/midimustang.png "Rock Band Mustang Pro Guitar")  

>![A picture of a Rock Band 3 Squier Stratocaster Pro Guitar showing a 5-DIN MIDI output highlighted in blue with a dotted white outline.](https://carlmylo.github.io/docu-rpcs3/images/midi/midisquier.png "Rock Band Squier Stratocaster Pro Guitar")  

**Para conectarlo a tu computadora, necesitarás un convertidor/interfaz de MIDI a USB**.

Aquí esta un ejemplo de un adaptador de MIDI a USB. Mayoría tiene una luz LED integrada para mostrar activad. **Para verificar que esta todo enchufado correctamente, debes de ver "MIDI In" parpadeando cuando le toques una nota**.

>![Una imagen de una interfaz de MIDI a USB.](https://carlmylo.github.io/docu-rpcs3/images/midi/miditousb.png "Interfaz de MIDI a USB")  

**Si tienes una interfaz de audio, puede ser que ya tengas un puerto de MIDI** para tu computadora, ya que unas interfaces tienen puertos de MIDIs integrados. Por ejemplo, esta Scarlett tiene conexiones MIDI por detrás.    
>![Una imagen del posterior de una Focusrite Scarlett, mostrando un puerto de USB y un salida/entrada MIDI por puerto DIN de cinco pines.](https://carlmylo.github.io/docu-rpcs3/images/midi/midifs.png "Salida/Entrada MIDI de Focusrite Scarlett") 

Once again, you need [[a Interfaz de MIDI a USB that has SYSEX support]](#sysex-notice)

Find whichever way is the most convenient for you then connect your Rock Band Pro Guitar to your computer.

![Una captura del menú de clic derecho de RPCS3, mostrando "Change Custom Configuration" (Cambiar configuración personalizada) resaltado.](https://carlmylo.github.io/docu-rpcs3/images/cust/rpcs3customconfigchange.png "Change Custom Configuration")

![Una captura de la configuración personalizada de I/O de Rock Band 3, mostrando "Emulated MIDI Devices", tipo de dispositivo y selección de dispositivos resaltados en cuadros bronceados con contornos sólidos.](https://carlmylo.github.io/docu-rpcs3/images/cust/io.png "I/O")

* ![Un cuadro bronceado con un contorno solido.](https://carlmylo.github.io/docu-rpcs3/images/cust/smalltan.png "Un cuadrado bronceado.") :
	* 🎸 **Change your “Emulated MIDI type” from “Keyboard” to “Guitar (17 Frets)” if you have a Mustang Pro Guitar, or “Guitar (22 Frets)” if you have a Squier Pro Guitar, then select your Interfaz de MIDI a USB in the drop-down menu next to it.**

[[Back to Pro Guitars]](https://carlmylo.github.io/docu-rpcs3/ctrls_protars)

Implementation by [[Dark]](https://dark.ski/)