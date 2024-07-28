---
title: Common
sidebar: english_sidebar
permalink: trbl_common
folder: english
---

## Bugged textures

![A screenshot of Rock Band 3, with a character displaying severe texture issues.](https://carlmylo.github.io/docu-rpcs3/images/trbl/common/wcb.png "Graphical issues")

You did not follow the guide and did not [**[enable Write Color Buffers in the GPU section]**](https://rb3pc.milohax.org/english/customconfiguration/#gpu).

![A screenshot of Rock Band 3's GPU custom settings, highlighting Write Color Settings highlighted in green with a dotted outline.](https://carlmylo.github.io/docu-rpcs3/images/trbl/common/wcbon.png "GPU")

## Flying instruments

![A screenshot of Rock Band 3, with a character experiencing issues with their hat and guitar.](https://carlmylo.github.io/docu-rpcs3/images/trbl/flyinst.png "Graphical issues")

There is a fix being worked on for this. Stay tuned for further development. Join the [**[the Milohax discord]**](https://rb3dx.milohax.org/discord) if you want to help test.

You can use [**[this list]**](https://rb3pc.milohax.org/extra/teleprob) as a reference for which hats, hairsyles, and microphones to avoid.

## [Online] I crash when joining sessions/searching for players

Your router may have issues with RPCS3's UPNP feature. Go to Rock Band 3's Custom Configuration [[Network section]](https://rb3pc.milohax.org/english/customconfiguration#network), and disable "Enable UPNP." You will need to [[search how to port forward in your router]](https://www.noip.com/support/knowledgebase/general-port-forwarding-guide).

## My game feels off.

Run Calibration in Rock Band 3's System Settings if you haven't for some reason. Disable "Dolby Digital" if you enabled it in the same menu.

## My audio is stuttering/choppy

<iframe width="420" height="315"
src="https://www.youtube.com/embed/UoCMEQbNThs">
</iframe> 

* Increase "Audio Buffer Duration" as mentioned in [[the Audio tab of Rock Band 3's Custom Configuration]](https://rb3pc.milohax.org/english/customconfiguration#audio) until the stuttering stops. 100 ms is a great starting point for low end computers. Alternatively, you can check the general performance issues section right below this.


<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseOne">General performance issues</a>
                            </h4>
                        </div>
                        <div id="collapseOne" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                                <ul>
<li>Set your computer to the <a href="https://help.ableton.com/hc/en-us/articles/115000211304-Using-the-High-performance-power-plan-Windows-">[High Performance power plan]</a>.</li>
<li>Go back to the <a href="https://rb3pc.milohax.org/english/customconfiguration#changing-a-custom-configuration">[Custom Configuration setup section]</a> and apply suggested low performance tweaks.</li>
<li>Disable Post Effects in Deluxe Settings.
<ul>
<li><code>Menu &gt; Options &gt; Deluxe Settings &gt; Graphics</code></li>
</ul>
</li>
<li>If your motherboard has a Realtek audio chip (most computers), try <a href="https://realtek-download.com/download-hd/">[installing the latest driver]</a>. This is a <a href="https://github.com/RPCS3/rpcs3/issues/14648">[known issue]</a> where using the default “High Definition Audio” driver doesn’t use all threads.</li>
<li>Close out the dedicated Discord client and open it up in your browser or on your phone. You can also try an alternative Discord client <a href="https://github.com/Vencord/Vesktop">[like Vesktop]</a>, but I claim no responsibility for your Discord account.</li>
</ul>

.
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
</div>

{% include links.html %}