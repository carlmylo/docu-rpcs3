---
title: Configuración Rapida
sidebar: espanol_sidebar
permalink: gs_quick_config_es
folder: espanol
tags: [empezando, espanol]
summary: "La pagina central para configuraciones rápida de RPCS3"
series: "Empezando"
weight: 6
toc: false
---

Estos archivos son para personas que quieren jugar sin hacer tanta configuración. Como quiera recomiendo que hagas una [[configuración personalizada]](https://carlmylo.github.io/docu-rpcs3/custom_config_es){:target="_blank"} para ajustar todo a lo mejor que pueda tu computadora.  
**DEBES de tener** [[**Rock Band 3 Deluxe instalado**]](https://carlmylo.github.io/docu-rpcs3/gs_init_es#rock-band-3-deluxe){:target="_blank"} o no te va ir mal. Si no lo tienes instalado en este momento, no estás leyendo la guía.

## Perfiles de Configuraciones Rápidas

Abajo están los archivos para instalar una configuración rápida. Descarga lo que queda bien con tu computadora.

* [[Configuración recomendada]](https://github.com/carlmylo/docu-rpcs3/raw/gh-pages/downloads/customconfigs/recommended_es.zip){:target="_blank"} - Esta configuración es para computadoras que son igual (o mejor) que [los requisitos recomendados](https://carlmylo.github.io/docu-rpcs3/gs_reqs_es#una-computadora){:target="_blank"}.
* [[Configuración mínima]](https://github.com/carlmylo/docu-rpcs3/raw/gh-pages/downloads/customconfigs/minimum_es.zip){:target="_blank"} - Esta configuración es para computadoras que son igual (o mejor) que [los requisitos mínimos](https://carlmylo.github.io/docu-rpcs3/gs_reqs_es#una-computadora){:target="_blank"}.

## Como Usar

Para usar estos archivos, **haz click en las configuración que quieres bajar y luego extrae los archivos en la carpeta donde esta RPCS3**. Las carpetas se combinaran si lo hiciste bien.
El ejemplo abajo enseña la configuración recomendada (recommended.zip) siendo instalada.

![Una animación de "config" y "dev_hdd0" de "recommended.zip" siendo arrastrado a la carpeta de RPCS3.](https://carlmylo.github.io/docu-rpcs3/images/cust/quickconf.gif "Recommended.zip")

Todavía vas a tener que configurar [[tus instrumentos y controles]](https://carlmylo.github.io/docu-rpcs3/ctrls_es){:target="_blank"}. [[Micrófonos]](https://carlmylo.github.io/docu-rpcs3/custom_config_aud_es){:target="_blank"} y [[guitarras PS3 Mustang o teclados RB3 con receptores]](https://carlmylo.github.io/docu-rpcs3/adv_passthrough_es){:target="_blank"} también requieren configuración adicional.

<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#detallesconf">Detalles de Configuraciones</a>
                            </h4>
                        </div>
                        <div id="detallesconf" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                                <p>Si quieres saber mas de los ajustes que hacen estas configuraciones:</p>
<h3 id="recomendada">Recomendada</h3>
<ul>
<li><strong>CPU</strong>:
<ul>
<li>SPU Block Size (Tamaño de bloques del SPU): Mega</li>
</ul>
</li>
<li><strong>GPU</strong>:
<ul>
<li>Write Color Buffers (Ingresar búferes de colores): Activado</li>
<li>Framelimit (Limite de fotogramas): Off (Apagado)</li>
<li>Resolution Scale (Nivel de resolución): 150% (1920x1080)</li>
<li>Anisotropic Filter (Filtro anisotrópico): 16x</li>
<li>ZCULL Accuracy (Precisión de ZCull): Relaxed (Fastest) (Relajada (Mas Rápida))</li>
<li>VSync (Sincronización vertical): Activada</li>
</ul>
</li>
<li><strong>Audio</strong>:
<ul>
<li>Audio Buffer Duration (Duración de búferes de audio): 32 ms</li>
</ul>
</li>
<li><strong>System</strong>:
<ul>
<li>Console Language (Lenguaje de sistema): Spanish (Español)</li>
<li>Keyboard Type (Tipo de teclado): Spanish Keyboard (Teclado Español)</li>
</ul>
</li>
<li><strong>Network</strong>:
<ul>
<li>Network Status (Estado de red): Connected (Conectado)</li>
<li>IP Hosts/Switches: Configurado para RBEnhanced</li>
<li>Enable UPNP (Activar UPnP): Activado</li>
</ul>
</li>
<li><strong>Advanced</strong>:
<ul>
<li>Debug Console Mode (Modo de consola saca-errores): Activado</li>
<li>Exclusive Fullscreen Mode (Modo de exclusividad de pantalla llena): Prefer Borderless fullscreen (Preferir pantalla llena sin bordos)</li>
<li>Driver Wake-Up Delay (Retraso de activación de controlador): 20 µs</li>
</ul>
</li>
<li><strong>Emulator</strong>:
<ul>
<li>Show trophy popups (Enseñar notificaciones de trofeos): Desactivado</li>
</ul>
</li>
</ul>
<h3 id="minima">Mínima</h3>
<ul>
<li><strong>CPU</strong>:
<ul>
<li>SPU Block Size (Tamaño de bloques del SPU): Mega</li>
<li>Preferred SPU Threads (Hilos preferidos del SPU): 2</li>
</ul>
</li>
<li><strong>GPU</strong>:
<ul>
<li>Write Color Buffers (Ingresar búferes de colores): Activado</li>
<li>Framelimit (Limite de fotogramas): Off (Apagado)</li>
<li>ZCULL Accuracy (Precisión de ZCull): Relaxed (Fastest) (Relajada (Mas Rápida))</li>
</ul>
</li>
<li><strong>Audio</strong>:
<ul>
<li>Audio Buffer Duration (Duración de búferes de audio): 100 ms</li>
</ul>
</li>
<li><strong>System</strong>:
<ul>
<li>Console Language (Lenguaje de sistema): Spanish (Español)</li>
<li>Keyboard Type (Tipo de teclado): Spanish Keyboard (Teclado Español)</li>
</ul>
</li>
<li><strong>Network</strong>:
<ul>
<li>Network Status (Estado de red): Connected (Conectado)</li>
<li>IP Hosts/Switches: Configurado para RBEnhanced</li>
<li>Enable UPNP (Activar UPnP): Activado</li>
</ul>
</li>
<li><strong>Advanced</strong>:
<ul>
<li>Debug Console Mode (Modo de consola saca-errores): Activado</li>
<li>Exclusive Fullscreen Mode (Modo de exclusividad de pantalla llena): Prefer Borderless fullscreen (Preferir pantalla llena sin bordos)</li>
<li>Driver Wake-Up Delay (Retraso de activación de controlador): 40 µs</li>
</ul>
</li>
<li><strong>Emulator</strong>:
<ul>
<li>Show trophy popups (Enseñar notificaciones de trofeos): Desactivado</li>
</ul>
</li>
</ul>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
</div>
<!-- /.panel-group -->

{% include custom/series_empezando_next.html %}

{% include links.html %}