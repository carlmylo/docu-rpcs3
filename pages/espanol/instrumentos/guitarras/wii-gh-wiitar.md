---
title: Nintendo Wii Guitar Hero Guitars (WiitarThing)
sidebar: controllers_es_sidebar
permalink: ctrls_ghwtr_wii_es
folder: instrumentos
tags: [wii, guitarras, espanol]
summary: "How to setup Nintendo Wii Guitar Hero guitars on RPCS3."
toc: false
---

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/plat/wii.png" alt="Sistema" title="Sistema"></div>

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/cont/rcmgtrswii.png" alt="Control" title="Control"></div>

## NOTAS:

* Requires installing and running [[**WiitarThing**]](https://github.com/Meowmaritus/WiitarThing){:target="_blank"} along with its dependencies.
* This configuration **requires connecting wirelessly via Bluetooth**. You need a Bluetooth receiver to connect to your computer.
    * It's suggested to mod your guitar into a wired one with a solution like [[RetroCultMods' Solderless DIY RGB Kit]](https://www.etsy.com/listing/1505287559/solderless-diy-rgb-kit-for-guitar-hero){:target="_blank"}.
* Tilt does not work. Various things have been attempted to get it to work, but the weird gyroscope configuration does not work well with RPCS3 and constantly inputs garbage.
* Menús de RPCN (para aceptar y mandar invitaciones para jugar en linea) pueden dejar el juego atorado. Recomendamos que tengas otra manera de controlar estos menús, como [[un teclado de PC o un mando estándar]](https://carlmylo.github.io/docu-rpcs3/ctrls_pads_es){:target="_blank"}.

## Información de Control:

| Handlers | Devices |
|:------------------:|:---------------------:|
| XInput | XInput Pad |

| Device Class | Device Subtype |
|:------------------:|:---------------------:|
| Guitar | Guitar Hero |

## Mapeo

By default, XInput has most things bound correctly. You only need to adjust the following:

**UNMAP THE FOLLOWING** or guitar solos will auto-strum!  
Use Right Click to unmap Botón A.

| **RPCS3** | **XInput** | **Guitar** |
|:--------:|:-----------:|:-----------:|
| L2 | ![Left Trigger](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/360/lt.png "Left Trigger") | Solo Modifier |

**Change the following** or blue and yellow frets will be inverted!

| **RPCS3** | **XInput** | **Guitar** |
|:--------:|:-----------:|:-----------:|
| Square (Cuadro) | ![Botón Y](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/360/y.png "Botón Y") | ![Yellow Fret](https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/yf.png "Yellow Fret") | 
| Triangle (Triangulo) | ![Botón X](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/360/x.png "Botón X") | ![Blue Fret](https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/bf.png "Blue Fret") |

Guitar Hero controllers tend to misbehave and **refuse to map sometimes. If you try mapping Botón A and always get "U+" or something similar, click "Filter Noise"** at the bottom left of the controller configuration window **then try mapping**.

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/maps/gtrwiiwtarmapping.png" alt="Mapeo" title="Mapeo"></div>

<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#mapeo-avanzado">Mapeo avanzado</a>
                            </h4>
                        </div>
                        <div id="mapeo-avanzado" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
<h4 id="profile">Perfil</h4>
<p><a href="https://github.com/carlmylo/docu-rpcs3/raw/gh-pages/downloads/instrument-repo/Xbox%20360%20Guitar%20Hero%20Guitar.7z">[Bajar Perfil]</a></p>

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
<td align="center">Select</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/ts.png" alt="Tilt" title="Tilt Vertical"></td>
</tr>
<tr>
<td align="center">Select</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/ts.png" alt="Tilt" title="Tilt Horizontal"></td>
</tr>
<tr>
<td align="center">Start</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/wii/plu.png" alt="Plus" title="Plus"></td>
</tr>
<tr>
<td align="center">Select</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/wii/back.png" alt="min" title="Minus"></td>
</tr>
<tr>
<td align="center">Botón PS</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/wii/home.png" alt="Home" title="Home"></td>
</tr>
</tbody>
</table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
</div>
<!-- /.panel-group -->

[[Back to Guitars]](https://carlmylo.github.io/docu-rpcs3/ctrls_guitar)

Mapeado por [diogodiogo2]