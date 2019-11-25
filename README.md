

<p align="center"><img width=12.5% src="https://macarteycreacion.com/api/aruppi/logo.png"></p>
<p align="center"><img src="https://macarteycreacion.com/api/aruppi/aruppi.png"></p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Anime Manga](https://img.shields.io/badge/Anime-Manga-red.svg)
![Colaboradores welcome](https://img.shields.io/badge/Android-Compatible-green.svg) [![API](https://img.shields.io/badge/API-23%2B-brightgreen.svg?style=flat)](https://android-arsenal.com/api?level=23)
[![Download](https://img.shields.io/badge/Kotlin-1.3.60-brightgreen.svg?style=flat&logo=kotlin)](https://kotlinlang.org/docs/reference/whatsnew13.html)
[![API](https://img.shields.io/badge/J%C3%A9luchu-1.0.0-blue.svg?style=flat&logo=ello)](https://play.google.com/store/apps/dev?id=7449422814338081261&hl=es_ES)
![Colaboradores welcome](https://img.shields.io/badge/Colaboración-Abierta-green.svg)

Aruppi es una aplicación creada con el fin de proporcionar toda la información de tus animes, mangas y novelas ligeras favoritas, con la posibilidad de guardarlas en la nube. Una aplicación totalmente gratuita y sin anuncios para acercar toda esta cultura a todos los hispanohablantes.

**Todos los animes, personajes y logotipos pertenecen a sus respectivos derechos de autor.**

Desde aquí agradecemos a todas aquellas personas que día a día prueban la aplicación y nos reportan los errores de rendimiento de la aplicación.

<p align="center"><img src="https://macarteycreacion.com/api/aruppi/intro.png"></p>

## Características

A continuación os mostramos las características de la aplicación y su estado actual dentro del desarrollo de la aplicación. Estamos abiertos a nuevas mejoras dentro de la misma, si tenéis alguna sugerencia os invitamos a escribirnos por correo electrónico en: <infoaruppi@gmail.com>. Este es el estado actual de las características de la app:

- [x] **Calendario** - *averiado*	
- [x] **Temporadas**
- [x] **Información de la serie** 
- [x] **Galería por serie**
- [x] **Episodios** - *en proceso*
- [x] **Radio** - *en proceso*
- [x] **PodCast**
- [ ] **Modo Nocturno** - *próximamente*
- [ ] **Ampliación de servidores (Episodios)** - *próximamente*
- [ ] **Wallpapers** - *en construcción*

Aquellas que no tienen ningún estado es porque se ha finalizado su desarrollo (sin contar posibles mejoras o correcciones dentro de dicha sección, puesto que la base está terminada)

## Web

Desde nuestra página web encontrarás los enlaces de descarga de la aplicación (Google Play), además de poder ver una información ampliada de la aplicación, sus características, sus novedades, lanzamiento y muchas otras cosas más. También podréis ver un mini tráiler de la aplicación. La página web tiene soporte desde GitHub Pages, por lo tanto el enlace será muy sencillo de recordar: [https://aruppi.github.io/](https://aruppi.github.io/)

Podéis ver el vídeo desde YouTube o pinchando en la siguiente imagen:
[![Aruppi Tráiler](http://img.youtube.com/vi/K6ROvHb2_xc/0.jpg)](http://www.youtube.com/watch?v=K6ROvHb2_xc "Aruppi Tráiler")

## Herramientas

Aquí os dejamos algunas de las herramientas, servicios o normas que hemos seguido para el desarrollo de la aplicación de android, además de su arquitectura y patrones que se han determinado usar para crear Aruppi.

| Nombre | Descripción | Link |
|--|--|--|
| Kotlin | Lenguaje en el que se ha desarrollado la aplicación, el nuevo lenguaje oficial para el desarrollo de aplicaciones para android (2019) | [https://kotlinlang.org/](https://kotlinlang.org/)|
| Firebase | Plataforma de servicios de Google para el envío de notificaciones, cambios de funcionalidades remotamente desde la app, base de datos, etc | [https://firebase.google.com/](https://firebase.google.com/)|
| OneSignal | Envío de notificaciones a la aplicación tanto push como in-app |[https://onesignal.com/](https://onesignal.com/)|
| Exoplayer | Reproductor de vídeo para reproducir los enlaces de los episodios de forma remota | [https://exoplayer.dev/](https://exoplayer.dev/)|
| Material Design | Se ha seguido las reglas de diseño y patrones de Google, además del estilo de Android 9 |[https://material.io/](https://material.io/)|
| Architecture MVVM | Esta es la arquitectura oficial usada para el desarrollo de la aplicación |-|
| Clean Code | Desarrollo con código limpio, uso de extensiones para favorecer la lectura de código y su comprensión |-|


## Fuentes

Durante el desarrollo de la aplicación hemos obtenido datos de diferentes fuentes, todo ello para obtener los datos de cada serie, además de la obtención de los capítulos de cada serie (sitios webs de terceros). Todas estas fuentes componen la API Oficial de Aruppi, una API REST que agrupa todo tipo de datos de cada serie, además de incluir vídeos, imágenes, etc.
Algunas de las fuentes que hemos usado en dicho desarrollo son las siguientes:

| Nombre | Descripción | Link |
|--|--|--|
| Jikan | Obtención de información de cada serie, manga u otras. También encontramos los datos del calendario y de las series que se mostrarán en cada temporada del año | [https://jikan.docs.apiary.io/#reference/0/search](https://jikan.docs.apiary.io/#reference/0/search)|
| Ryuanime | Obtenemos algunos datos de información de cada serie, de ese modo completamos toda la información posible por serie. | [https://github.com/ChrisMichaelPerezSantiago/ryuanime](https://github.com/ChrisMichaelPerezSantiago/ryuanime)|
| Google Imágenes | Obtención de imágenes según la serie que se ha elegido visualizar, además de la obtención de algunos wallpapers por serie | [https://www.google.es/imghp?hl=es](https://www.google.es/imghp?hl=es)|
| AnimeFLV | Según la serie a la que se realice la consulta de información se le mostrará los diversos capítulos de los que se dispone | [https://github.com/ChrisMichaelPerezSantiago/animeflv](https://github.com/ChrisMichaelPerezSantiago/animeflv)|
| Anitakume | Obtención de PodCast en castellano en los cuales se trata temas de cultura japonesa, noticias de anime o críticas de la misma | [https://www.ivoox.com/podcast-anitakume_sq_f1660716_1.html](https://www.ivoox.com/podcast-anitakume_sq_f1660716_1.html)|
| Listen.moe | Obtención de música 24/7, como puede ser K-Pop o J-Pop | [https://listen.moe/](https://listen.moe/)|

Todas estas fuentes se engloban en una misma API REST realizada por uno de nuestros colaboradores, y de la que podéis ver toda la información en el siguiente enlace: [AruppiServices](https://github.com/aruppi/AruppiServices)

## Colaboradores

Aquí os mostramos aquellas personas que estamos al cargo del desarrollo de la aplicación tanto del front como del backend de Aruppi, os agradecemos mucho vuestro apoyo y los feedbacks que recibimos por todos los usuarios de la app.

<table>
  <tr>
    <td align="center"><a href="https://www.linkedin.com/in/jesusmariacalderon/"><img src="https://avatars0.githubusercontent.com/u/32357592?s=460&v=4" width="75px;" alt="Gabriel Arroyo"/><br /><sub><b>Jéluchu</b></sub></a><br/><sub>Desarrollo Android</sub></a></td>
    <td align="center"><a href="https://www.linkedin.com/in/gabriel-arroyo-pajares-8bb459162/"><img src="https://avatars1.githubusercontent.com/u/22908337?s=88&v=4" width="75px;" alt="CJ R."/><br /><sub><b>Gabriel Arroyo</b></sub></a><br/><sub>Desarrollo .NET</sub></td>
  </tr>
</table>

Si queréis participar en el desarrollo de la aplicación junto a nosotros, os invitamos a que nos escribáis un correo electrónico a:  <infoaruppi@gmail.com>
