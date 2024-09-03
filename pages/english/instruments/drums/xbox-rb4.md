---
title: "Xbox One/Xbox Series Rock Band 4 Drums"
sidebar: controllers_sidebar
permalink: ctrls_rb4drums_xbox
folder: instruments
toc: false
---

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/plat/xbx.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/cont/rbdrmscontroller.png" alt="Controller" title="Controller"></div>

## NOTES

* Requires installing and running [[**RB4InstrummentMapper**]](https://github.com/TheNathannator/RB4InstrumentMapper/)
* Works with or without the Pro Cymbal expansions.
	* Make sure to tell the game which cymbals are connected in the Drum Options menu.
* Velocity sensitivity doesn't seem to work.
* RPCN Menus (for sending or accepting online invites) may cause a softlock. You may need an alternative input method to navigate these menus, such as a typing keyboard or a gamepad.

## Pad Information

| Handlers | Devices |
|:------------------:|:---------------------:|
| XInput | XInput Pad |

| Device Class | Device Subtype |
|:------------------:|:---------------------:|
| Drums | Rock Band Pro |

## Additional Setup

Please refer to RB4InstrumentMapper's documentation.  
[[Click here to go there]](https://github.com/TheNathannator/RB4InstrumentMapper/blob/main/README.md).

## Mapping

### Controller Emulation Mode: ViGEmBus (RPCS3 compatibility)

This is the recommended mode and should not require any mapping. You simply need to assign the Handler, Device, and Device Class/Type.

### Controller Emulation Mode: ViGEmBus

<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#controller-emulation-mode-vigembus">Advanced Mapping</a>
                            </h4>
                        </div>
                        <div id="controller-emulation-mode-vigembus" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
<p><a href="https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/Xbox%20360%20Rock%20Band%20Drums.7z">[Download Profile]</a></p>
<p>This is not suggested as it requires lots of manual mapping. You should instead use <strong>ViGEmBus (RPCS3 compatibility)</strong>.</p>
<ul>
<li>Rock Band Drums send multiple button presses out at once. For example, a Red pad will send “<code>B</code>” and “<code>Right Stick Click</code>” (which translates to “<code>Circle</code>” and “<code>L3</code>”.) Keep in mind these are needed to the emulator to tell your cymbals apart.
<ul>
<li>It’s strongly suggested to bind an Xbox controller like the Mapping screenshot below then swapping the Device to your Xbox 360 Rock Band Drums.</li>
</ul>
</li>
<li>To bind multiple buttons to one RPCS3 button, hold Shift then click on the RPCS3 button you want to assign multiple buttons to.</li>
</ul>

<table>
<thead>
<tr>
<th align="center"><strong>RPCS3</strong></th>
<th align="center"><strong>Controller</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">Cross</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/gf.png" alt="Green Fret" title="Green Fret"></td>
</tr>
<tr>
<td align="center">Circle</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/rf.png" alt="Red Fret" title="Red Fret"></td>
</tr>
<tr>
<td align="center">Square</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/yf.png" alt="Yellow Fret" title="Yellow Fret"></td>
</tr>
<tr>
<td align="center">Triangle</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/bf.png" alt="Blue Fret" title="Blue Fret"></td>
</tr>
<tr>
<td align="center">L1</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/of.png" alt="Orange Fret" title="Orange Fret"></td>
</tr>
<tr>
<td align="center">D-Pad: Up</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/sbu.png" alt="Strumbar Up" title="Strumbar Up"></td>
</tr>
<tr>
<td align="center">D-Pad: Down</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/sbd.png" alt="Strumbar Down" title="Strumbar Down"></td>
</tr>
<tr>
<td align="center">D-Pad: Left</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/dpl.png" alt="D-Pad: Left" title="D-Pad: Left"></td>
</tr>
<tr>
<td align="center">D-Pad: Right</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/dpr.png" alt="D-Pad: Right" title="D-Pad: Right"></td>
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
<td align="center">PS Button</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/360/home.png" alt="Home" title="Home"></td>
</tr>
<p><div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/maps/xborbdrmsmapping.png" alt="Mapping" title="Mapping"></div></p>
</tbody>
</table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
</div>
<!-- /.panel-group -->


<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/maps/xboxrb4rpcs3map.png" alt="Mapping" title="Mapping"></div>

[[Back to Controllers]](https://rb3pc.milohax.org/english/controllers/)