---
title: "Xbox One Rock Band 4/Fortnite Festival Guitars"
sidebar: controllers_es_sidebar
permalink: ctrls_rb4gtr_xbox_es
folder: instrumentos
tags: [xbox-one, guitarras, espanol]
summary: "How to setup Xbox One Rock Band 4/Fortnite Festival guitars on RPCS3."
toc: false
---

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/plat/xbx.png" alt="Sistema" title="Sistema"></div>

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/cont/rb4gtrscontroller.png" alt="Control" title="Control"></div>

## NOTAS:

* Requires installing and running [[**RB4InstrummentMapper**]](https://github.com/TheNathannator/RB4InstrumentMapper/){:target="_blank"} along with its dependencies.
* This profile works for Xbox One Fender Stratocaster, Fender Jaguar, and PDP Riffmaster guitars.
	* Fender Stratocaster and Fender Jaguar guitars require a Microsoft Xbox Wireless Adapter.  
	![Microsoft Xbox Wireless Adapter for Windows 10](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/xbox/receiver.png "Microsoft Xbox Wireless Adapter for Windows 10")  
	* PDP Riffmaster guitars require their respective dongle.  
	![PDP Riffmaster Wireless Receiver](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/xbox/riffrec.png "PDP Riffmaster Wireless Receiver")  
* If you have a Jaguar guitar, you may need to install a [[firmware update]](https://bit.ly/2UHzonU){:target="_blank"} to connect it to the receiver. [[Click here for more information]](https://bit.ly/2UHzonU){:target="_blank"}.
* Menús de RPCN (para aceptar y mandar invitaciones para jugar en linea) pueden dejar el juego atorado. Recomendamos que tengas otra manera de controlar estos menús, como [[un teclado de PC o un mando estándar]](https://carlmylo.github.io/docu-rpcs3/ctrls_pads_es){:target="_blank"}.

## Información de Control:

| Handlers | Devices |
|:------------------:|:---------------------:|
| XInput | XInput Pad |

| Device Class | Device Subtype |
|:------------------:|:---------------------:|
| Guitar | Rock Band |

### Configuración Adicional:

Por favor lee la documentación de RB4InstrumentMapper.  
[[Haz click aquí para leerla]](https://github.com/TheNathannator/RB4InstrumentMapper/blob/main/README.es.md){:target="_blank"}.

## Mapeo:

### Controller Emulation Mode: ViGEmBus (RPCS3 compatibility)

Este es el modo recomendado porque no requiere configuración adicional. Solo requiere que elijes la información de control correcta (Handler, Device y Device Class/Type).

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/maps/gtrxomapping.png" alt="Mapeo" title="Mapeo"></div>

<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#controller-emulation-mode-vigembus">Mapeo avanzado</a>
                            </h4>
                        </div>
                        <div id="controller-emulation-mode-vigembus" class="panel-collapse collapse noCross (Cruz)Ref">
                            <div class="panel-body">
<p><a href="https://github.com/carlmylo/docu-rpcs3/raw/gh-pages/downloads/instrument-repo/Xbox%20Rock%20Band%20Guitar.7z">[Bajar Perfil]</a></p>
<p>Esto no es recomendado porque requiere muchos ajustes manuales. Deberías usar el modo <strong>ViGEmBus (RPCS3 compatibility)</strong>.</p>
<p>The effects switch (pickup selector) was only able to be bound to the top half or the bottom half. The bottom half was chosen in the profile so it could be disabled.</p>

<table>
<thead>
<tr>
<th align="center"><strong>RPCS3</strong></th>
<th align="center"><strong>Controller</strong></th>
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
<p><div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/maps/gtrxboxrbmapping.png" alt="Mapeo" title="Mapeo"></div></p>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
</div>
<!-- /.panel-group -->

[[Back to Guitars]](https://carlmylo.github.io/docu-rpcs3/ctrls_guitar)

Mapeado por [[gonakil1ya]](https://linktr.ee/Gonakil1ya){:target="_blank"}