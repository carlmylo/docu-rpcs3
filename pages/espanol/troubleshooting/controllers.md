---
title: Controles
sidebar: espanol_sidebar
permalink: trbl_controllers_es
folder: espanol
tags: [resolviendo-problemas, espanol]
summary: "Como resolver problemas comunes con controles."
toc: false
---

<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#atorado-nombrando">Mi juego se queda atorado cuando nombro algo.</a>
                            </h4>
                        </div>
                        <div id="atorado-nombrando" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                                <p>Esto depende mucho del control.</p>
<ul>
<li>Trata de mover la palanca de whammy o el switch de efectos en tu guitarra.</li>
<li>Re-conecta el control.</li>
<li>Abre el menú de "Pads" y ciérralo. Esto va a reiniciar tus controles.</li>
<li>Desactiva "Native Interface" como dijo la guía hagas en la <a href="https://carlmylo.github.io/docu-rpcs3/custom_config_emu_es" target="_blank">[pestaña de Emulator en la configuración personalizada de Rock Band 3]</a>.</li>
<li>Usa un <a href="https://carlmylo.github.io/docu-rpcs3/ctrls_pads_es" target="_blank">[mando o teclado]</a> para cualquier cosa que requiera el teclado virtual.</li>
</ul>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                                        <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#solos-have-auto-strum-enabled">[Guitar Hero guitars] Solos have auto-strum enabled.</a>
                            </h4>
                        </div>
                        <div id="solos-have-auto-strum-enabled" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                                <p>Unbind L2 from your guitar in your gamepad configuration by right clicking it.</p>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/gtrs/solol2.gif" alt="A GIF of a RPCS3's Gamepad Configuration. L2 button is being unbound." title="L2 Unbound"></p>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#my-ps3-rock-band-instrument-controller-shows-up-as-two-controlle">My PS3 Rock Band instrument controller shows up as two controllers.</a>
                            </h4>
                        </div>
                        <div id="my-ps3-rock-band-instrument-controller-shows-up-as-two-controlle" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                                You did <a href="https://carlmylo.github.io/docu-rpcs3/ctrls#mapping" target="_blank">[controller configuration]</a> for a PS3 Rock Band controller, which usually isn’t needed due to passthrough. Just unbind the controller and it should be fine.
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                                        <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#pro-drums-my-e-kit-doesnt-work">[MIDI Drums] My E-Kit doesn't work.</a>
                            </h4>
                        </div>
                        <div id="pro-drums-my-e-kit-doesnt-work" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                                <ul>
                                <li>Windows doesn’t let programs share MIDI devices. If you have anything else open that is using the port (including MIDI Monitor), close it before starting Rock Band 3 in RPCS3.</li>
                                <li>Make sure your E-Kit is mapped correctly and on the right channel (Channel 10). Refer to <a href="https://carlmylo.github.io/docu-rpcs3/ctrls_drums_midi" target="_blank">[the MIDI Drums page]</a> for more help.</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                                        <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#pro-drums-hitting-two-cymbals-registers-as-a-tom">[Pro Drums] Hitting two cymbals registers as a tom.</a>
                            </h4>
                        </div>
                        <div id="pro-drums-hitting-two-cymbals-registers-as-a-tom" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                                This is an infamous Rock Band 3 bug called the “double cymbal glitch” and plagues all versions of Rock Band 3, even console versions. You can try to slightly <a href="https://en.wikipedia.org/wiki/Drum_rudiment#Flam" target="_blank">[flam]</a> the two inputs to get around this.
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                                        <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#midi-keys-my-keyboard-doesnt-work">[MIDI Keys] My Keyboard doesn't work</a>
                            </h4>
                        </div>
                        <div id="midi-keys-my-keyboard-doesnt-work" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                                <ul>
                                <li>Windows doesn’t let programs share MIDI devices. If you have anything else open that is using the port (including MIDI Monitor), close it before starting Rock Band 3 in RPCS3.</li> 
                                <li>Make sure your keyboard the right channel (Channel 1). Refer to <a href="https://carlmylo.github.io/docu-rpcs3/ctrls_keys_midi" target="_blank">[the MIDI Keyboard page]</a> for more help.</li>
                                <li>If you're on a Rock Band 3 keyboard in MIDI mode, you may have activated drum mode by pressing D-Pad Up. Press D-Pad Up again to toggle it off.</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                                        <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#miditar-my-protar-doesnt-work">[Pro Guitar] My guitar doesn't work.</a>
                            </h4>
                        </div>
                        <div id="miditar-my-protar-doesnt-work" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                                <ul>
                                <li>Pro Guitars require a MIDI interface with SYSEX capabilities. Refer to <a href="https://carlmylo.github.io/docu-rpcs3/ctrls_protars" target="_blank">[your Pro Guitar's page]</a> to see which interfaces are confirmed to work.</li>
                                <li>Windows doesn’t let programs share MIDI devices. If you have anything else open that is using the port (including MIDI Monitor), close it before starting Rock Band 3 in RPCS3.</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                                        <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#i-cannot-use-automatic-calibration-in-system-settings">I cannot use Automatic Calibration in System Settings.</a>
                            </h4>
                        </div>
                        <div id="i-cannot-use-automatic-calibration-in-system-settings" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                                Automatic Calibration only works for PS3 Rock Band guitar/bass and Fender Mustang Pro Guitar controllers with passthrough.
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
</div>
<!-- /.panel-group -->

{% include links.html %}