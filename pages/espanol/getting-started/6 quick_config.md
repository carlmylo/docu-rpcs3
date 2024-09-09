---
title: Configuración Rapida
sidebar: espanol_sidebar
permalink: gs_quick_config_es
folder: espanol
tags: [empezando, espanol]
summary: "La pagina central para configuraciones rapida de RPCS3"
series: "Empezando"
weight: 6
toc: false
---

Estos archivos son para personas que quieren jugar sin hacer tanta configuración. Como quiera recomiendo que hagas una [[configuración personalizada]](https://carlmylo.github.io/docu-rpcs3/custom_config_es) para ajustar todo a lo mejor que pueda tu computadora.  
**DEBES de tener** [[**Rock Band 3 Deluxe instalado**]](https://carlmylo.github.io/docu-rpcs3/gs_init_es#rock-band-3-deluxe){:target="_blank"} o no funcionaran a su máximo potencial. Si no lo tienes instalado en este momento, no estás leyendo la guía.

## Perfiles de Configuraciones Rápidas

Abajo estan los archivos para instalar una configuración rápida. Descarga lo que queda bien con tu computadora.

* [[Configuración recomendada]](https://github.com/carlmylo/docu-rpcs3/raw/gh-pages/downloads/customconfigs/recommended_es.zip){:target="_blank"} - Esta configuración es para computadoras que son igual (o mejor) que [los requisitos recomendados](https://rb3pc.milohax.org/espanol/requisitos/).
* [[Configuración mínima]](https://github.com/hmxmilohax/rb3-pc/raw/main/config/customconfig/minimum_es.zip) - Esta configuración es para computadoras que son igual (o mejor) que [los requisitos mínimos](https://rb3pc.milohax.org/espanol/requisitos/).

## Como Usar

Para usar estos archivos, **haz click en las configuración que quieres bajar y luego extrae los archivos en la carpeta donde esta RPCS3**. Las carpetas se combinaran si lo hiciste bien.
El ejemplo abajo enseña la configuración recomendada (recommended.zip) siendo instalada.

![Una animacion de "config" y "dev_hdd0" de "recommended.zip" siendo arrastrado a la carpeta de RPCS3.](https://carlmylo.github.io/docu-rpcs3/images/cust/quickconf.gif "Recommended.zip")

Los jugadores que desean utilizar [[micrófonos]](https://rb3pc.milohax.org/espanol/configuracionpersonalizada#audio), [[guitarras Pro con cable, teclados USB/MIDI, y baterías electrónicas con conexión MIDI]](https://rb3pc.milohax.org/espanol/configuracionpersonalizada#io), o [[guitarras PS3 Mustang o teclados RB3 con receptores]](https://rb3pc.milohax.org/espanol/conexiondirecta/) todavía requieren configuración adicional.

## Detalles de Configuraciones

Se necesitas mas detalles sobre estas configuraciones:

### Recomendada

* **CPU**:
	- SPU Block Size (Tamaño de bloques del SPU): Mega
- **GPU**:
	- Write Color Buffers (Ingresar búferes de colores): Activado
	- Framelimit (Limite de fotogramas): Off (Apagado)
	- Resolution Scale (Nivel de resolución): 150% (1920x1080)
	- Anisotropic Filter (Filtro anisotrópico): 16x
	- ZCULL Accuracy (Precisión de ZCull): Relaxed (Fastest) (Relajada (Mas Rápida))
	- VSync (Sincronización vertical): Activado
- **Audio**:
	- Audio Buffer Duration (Duración de búferes de audio): 32 ms
- **System**:
	- Console Language (Lenguaje de sistema): Spanish (Español)
	- Keyboard Type (Tipo de teclado): Spanish Keyboard (Teclado Español)
- **Network**:
	- Network Status (Estado de red): Connected (Conectado)
	- DNS: Configurado para RBEnhanced
	- Enable UPNP (Activar UPnP): Activado
- **Advanced**:
	- Debug Console Mode (Modo de consola saca-errores): Activado
	- Exclusive Fullscreen Mode (Modo de exclusividad de pantalla llena): Prefer Borderless fullscreen (Preferir pantalla llena sin bordos)
	- Driver Wake-Up Delay (Retraso de activación de controlador): 20 µs
- **Emulator**:
	- Show trophy popups (Enseñar notificaciones de trofeos): Desactivado

## Mínima

- **CPU**:
	- SPU Block Size (Tamaño de bloques del SPU): Mega
	- Preferred SPU Threads (Hilos preferidos del SPU): 2
- **GPU**:
	- Write Color Buffers (Ingresar búferes de colores): Activado
	- Framelimit (Limite de fotogramas): Off (Apagado)
	- ZCULL Accuracy (Precisión de ZCull): Relaxed (Fastest) (Relajada (Mas Rápida))
- **Audio**:
	- Audio Buffer Duration (Duración de búferes de audio): 100 ms
- **System**:
	- Console Language (Lenguaje de sistema): Spanish (Español)
	- Keyboard Type (Tipo de teclado): Spanish Keyboard (Teclado Español)
- **Network**:
	- Network Status (Estado de red): Connected (Conectado)
	- DNS: Configurado para RBEnhanced
	- Enable UPNP (Activar UPnP): Activado
- **Advanced**:
	- Debug Console Mode (Modo de consola saca-errores): Activado
	- Exclusive Fullscreen Mode (Modo de exclusividad de pantalla llena): Prefer Borderless fullscreen (Preferir pantalla llena sin bordos)
	- Driver Wake-Up Delay (Retraso de activación de controlador): 40 µs
- **Emulator**:
	- Show trophy popups (Enseñar notificaciones de trofeos): Desactivado

{% include custom/series_empezando_next.html %}

{% include links.html %}