---
title: Riffmaster (via Adafruit Feather) Guitar
sidebar: controllers_es_sidebar
permalink: ctrls_mod_riffada_es
folder: instrumentos
tags: [xbox-360, midi, english]
summary: "How to connect and configure Xbox 360 Wireless keyboards (MIDI) on RPCS3."
toc: false
---

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/plat/santroller.png" alt="Sistema" title="Sistema"></div>

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/cont/riffmastercontroller.png" alt="Control" title="Control"></div>

## NOTAS:

* **This is specifically for the** [**[Adafruit Feather RP2040 with USB Type A Host]**](https://www.adafruit.com/product/5723)**!** Please consult your sales receipt to confirm that it is indeed an [[Adafruit Feather RP2040 **with USB Type A Host**]](https://www.adafruit.com/product/5723).
* While you can use the Xbox One Riffmaster too but you should just use [[RB4InstrumentMapper]](https://rb3pc.milohax.org/instruments/xbox/rb4gtrs) for that instead.

## Información de Control:

| Handlers | Devices |
|:------------------:|:---------------------:|
| XInput | Joystick |

| Device Class | Device Subtype |
|:------------------:|:---------------------:|
| Guitar | Rock Band |

## Setup

Download the latest version of Santroller.

[![A screenshot of Santroller's Github download page, hovering over the Windows installer.](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/feather/dlsan.png)](https://github.com/Santroller/Santroller/releases "SantrollerConfigurator")

After downloading Santroller, open "SantrollerConfigurator".

![A screenshot of a cursor hovering over SantrollerConfigurator on a user's desktop](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/feather/opensan.png "SantrollerConfigurator")

Hold the "Boot" button on your Adafruit Feather RP2040 with USB Type A Host if you're plugging it into your computer for the first time.

![A picture of an Adafruit Feather RP2040. Botón A labeled "Boot" is circled in white, red, and black.](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/feather/bootada.jpg "Adafruit Feather RP2040 with USB Type A Host")

In SantrollerConfigurator, set "`Input Type`" to "`USB Adapter`." The Adafruit Feather RP2040 with USB Type A Host should be detected as "`Raspberry Pi Pico`." Click "`Configure`" after doing this.

![A screenshot of SantrollerConfigurator, with a cursor hovering over "USB Adapter," next to "Input Type."](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/feather/sanusb.png "SantrollerConfigurator")

Give it a moment to program initial configuration. When prompted, click on "`Configure`" again.
![A screenshot of SantrollerConfigurator, with a cursor hovering over "USB Adapter," next to "Input Type."](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/feather/sanconf.png "SantrollerConfigurator")

After you've loaded into the configuration page, scroll down to the "`Presets`" section and click to expand it. Once expanded, click on "`Import Settings from File`"

A community made preset exists (courtesy of jnack) to help speed things up. Load it up via the "Import Settings from File" option.  
[[Download the picoconfig preset here]](https://github.com/carlmylo/docu-rpcs3/raw/gh-pages/instrument-repo/RiffmasterFeather.picoconfig)

![A screenshot of SantrollerConfigurator, with a cursor hovering over "Import Settings from File" under the "Presets" configuration.](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/feather/sanpreload.png "Presets")

After loading the preset, **MAKE SURE YOU CLICK ON "`Save Settings`" before closing the program or you will lose progress!**

## Mapeo

Por defecto, XInput tiene mayoría de las cosas configuradas correctamente. Solo necesitas ajustar esto:

| **RPCS3** | **XInput** | **Guitar** |
|:--------:|:-----------:|:-----------:|
| R1 | ![Right Stick](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/360/rs.png "Right Stick") | ![Tilt](https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/ts.png "Tilt") | 
| L2 | ![Palanca derecha presionada](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/360/rsc.png "Palanca derecha presionada") | ![Solo Buttons](https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/solo.png "Solo Buttons") | 
| Right Stick: <br> Down | ![Left Trigger](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/360/lt.png "Left Trigger") | ![Effects Switch](https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/fx.png "Effects Switch") |

<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#mapeo-avanzado">Mapeo avanzado</a>
                            </h4>
                        </div>
                        <div id="advanced-mapping" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">

<table>
<thead>
<tr>
<th align="center"><strong>RPCS3</strong></th>
<th align="center"><strong>Guitar</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">Cross (Cruz)</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/gf.png" alt="Green Fret" title="Green Fret"></td>
</tr>
<tr>
<td align="center">Circle (Circulo)</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/rf.png" alt="Red Fret" title="Red Fret"></td>
</tr>
<tr>
<td align="center">Square (Cuadro)</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/yf.png" alt="Yellow Fret" title="Yellow Fret"></td>
</tr>
<tr>
<td align="center">Triangle (Triangulo)</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/bf.png" alt="Blue Fret" title="Blue Fret"></td>
</tr>
<tr>
<td align="center">L1</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/of.png" alt="Orange Fret" title="Orange Fret"></td>
</tr>
<tr>
<td align="center">D-Pad (Cruceta): Up</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/sbu.png" alt="Strumbar Up" title="Strumbar Up"></td>
</tr>
<tr>
<td align="center">D-Pad (Cruceta): Down</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/sbd.png" alt="Strumbar Down" title="Strumbar Down"></td>
</tr>
<tr>
<td align="center">D-Pad (Cruceta): Left</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/dpl.png" alt="D-Pad (Cruceta): Left" title="D-Pad (Cruceta): Left"></td>
</tr>
<tr>
<td align="center">D-Pad (Cruceta): Right</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/dpr.png" alt="D-Pad (Cruceta): Right" title="D-Pad (Cruceta): Right"></td>
</tr>
<tr>
<td align="center">Right Stick: <br> Left/Right</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/wb.png" alt="Whammy Bar" title="Whammy Bar"></td>
</tr>
<tr>
<td align="center">Right Stick: <br> Up <em>or</em> Down</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/fx.png" alt="Effects Switch" title="Effects Switch"></td>
</tr>
<tr>
<td align="center">L2</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/solo.png" alt="Solo Buttons" title="Solo Buttons"></td>
</tr>
<tr>
<td align="center">R1</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/ts.png" alt="Tilt" title="Tilt"></td>
</tr>
<tr>
<td align="center">Start</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/360/start.png" alt="Plus" title="Start"></td>
</tr>
<tr>
<td align="center">Select</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/360/back.png" alt="Minus" title="Back"></td>
</tr>
<tr>
<td align="center">Botón PS</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/360/home.png" alt="Home" title="Home"></td>
</tr>
</tbody>
</table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
</div>
<!-- /.panel-group -->

### Passthrough Mode

<div markdown="span" class="alert alert-info" role="alert"><i class="fa fa-info-circle"></i> <b>As of writing this, RPCS3 does not support hotplugging, which means you cannot plug your guitar in AFTER starting RPCS3. Passthrough Mode lets you use your guitar without needing to bind anything but due to the lack of hotplugging (PS3/Emulator preset), you need to start the game up twice. Therefore, this mode is currently not recommended. </b> {{include.content}}</div>

## Additional Notes
The picoconfig preset binds a few things for a better experience.
- The "Boot" button on the Adafruit Feather RP2040 with USB Type A Host will act as a guide button as pressing and holding the guide button on the Riffmaster shuts it off.
- D-Pad (Cruceta): Left and Select are swapped as the PlayStation Riffmaster. This is because, by default, the PlayStation Riffmaster has Overdrive activation bound to D-Pad (Cruceta) Left which is very uncomfortable.

If you wish to remove these tweaks, click the "`Remove`" next to the D-pad Left and Back buttons at the bottom of Santroller Configurator.

![A screenshot of SantrollerConfigurator, scrolled to the bottom. There are circles over the "Remove" buttons next to Back and D-pad Left.](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/feather/sanrem.png "SantrollerConfigurator")

After that, go to the "`Usb Host Inputs`" section and enable the original buttons again.

![A screenshot of SantrollerConfigurator, in the "Usb Host Inputs" section. There are circles over the disabled Back and D-pad Left buttons, showing them as disabled.](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/feather/sanhostin.png "Usb Host Inputs")

## Perfil

[[Bajar Perfil]](https://github.com/carlmylo/docu-rpcs3/raw/gh-pages/instrument-repo/Feather%20Riffmaster.7z)

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/maps/360rbgtrsmapping.png" alt="Mapeo" title="Mapeo"></div>

[[Back to Controllers]](https://rb3pc.milohax.org/english/controllers/)

Investigación por [jnackmclain](https://github.com/jnackmclain)