---
title: "Configuración Personalizada: Audio"
sidebar: espanol_sidebar
permalink: custom_config_aud_es
folder: espanol
tags: [conf-pers, espanol]
summary: "Que cambiar bajo la pestaña de Audio dentro de la configuración personalizada de RPCS3"
series: "Configuración Personalizada"
weight: 4
---

![Una captura de la configuración personalizada de audio de Rock Band 3, que muestra "Enable Buffering" resaltado en un cuadro verde con una línea discontinua, "Audio Out" y "Audio Buffer Duration" resaltados en cuadros azules con contornos punteados, y "Microphone Settings", "Microphone Type: Standard", Mic1, Mic2, Mic3 y Mic4 resaltados en un cuadro bronceado con contorno solido.](https://carlmylo.github.io/docu-rpcs3/images/cust/audio.png "Audio")

* ![Un cuadro verde con una línea discontinua.](https://carlmylo.github.io/docu-rpcs3/images/cust/smallgreen.png "Cuadro verde") **REQUERIDO**: 
	* **Activa "Enable Buffering"** (Activar Búfer) - Absolutamente requerido para Rock Band 3. Debería estar activado por defecto, pero si no, actívalo.

* ![Un cuadro azul con contorno punteado.](https://carlmylo.github.io/docu-rpcs3/images/cust/smallblue.png "Cuadro azul") **Dependiendo en tu PC**: 
	* Ajusta el "Audio Buffer Duration" (duración de búferes de audio) dependiendo de tu sistema. 
		* Valores bajos resultan en menos latencia pero más consumo de CPU.
		* Valores altos resultan en más latencia pero menos consumo de CPU.
		* Los que juegan vocales son los más afectados por esto porque latencia alta crea un eco. Los jugadores de instrumentos pueden usar la calibración para compensar.
		* Esto se puede cambiar mientras el juego esta abierto pero **requiere recalibración** en los ajustes del sistema de Rock Band 3.
	* **Cambia "Audio Out"** (Salida de audio) a **"XAudio2"** - **No mas se recomienda cambiar esto para computadoras de baja gama**. Prueba si hace una diferencia porque cambiando a XAudio2 puede causar problemas con sonido.

* ![Un cuadro bronceado con un contorno solido.](https://carlmylo.github.io/docu-rpcs3/images/cust/smalltan.png "Cuadro bronceado") **Para Vocalistas**: 
	* **Cambia "Microphone type"** (tipo de micrófono) **a "Standard" o "Rocksmith"**. "Standard" dejara que tu micrófono se pueda usar para cantar y la chat de voz. "Rocksmith" solo te dejara cantar.
	* Selecciona tu micrófonos en "Mic1", "Mic2" y "Mic3" para las voces. Si no estas jugando vocales, Mic 1 se usara para el chat de voz.
	* Otra vez, tener fotogramas sobre 60 puede causar problemas con la detección de vocales y con la conexión para jugar en linea.

<br/>

{% include custom/series_conf_pers_next.html %}

{% include links.html %}