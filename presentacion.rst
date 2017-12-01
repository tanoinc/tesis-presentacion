:title: Defensa: Tesina de Licenciatura (Luciano Coggiola)
:author: Luciano Coggiola
:description: Defensa Tesina de grado: "Mi Universidad: una aplicación móvil para mejorar la experiencia de usuario de los estudiantes de la Universidad Nacional de La Plata". Tesina de Licenciatura en Informática de Luciano Coggiola.
:keywords: presentación, tesina, unlp, facultad de informática, defensa, mi universidad, luciano coggiola, app, móvil
:css: estilos/unlp.css
      estilos/presentacion.css

.. header::
    .. image:: imagenes/logos/unlp_logo.png
    .. image:: imagenes/logos/facultad_informatica_logo.png

----

:id: principal

Tesina de Licenciatura
======================

"Mi Universidad: una aplicación móvil para mejorar la experiencia de usuario de los estudiantes de la Universidad Nacional de La Plata."
----------------------------------------------------------------------------------------------------------------------------------------
Autor: Luciano Coggiola.

Directores: Javier Díaz, Paola Amadeo.

Asesor Profesional: Alejandra Osorio.

.. note::
  Realizar presentación personal:
    - Nombre
    - Presentar directores, y AP y comentar cual es mi relacion laboral
    - Cespi -> Acceso a Sistemas universitarios.

----

:id: introduccion
:data-y: r1000

Introducción
============

* **Smartphones:** *amplio uso*.

  * **Tecnologías:** *GPS, notificaciones, cámara...* 

* Sistemas abiertos. 

**Comunicación**: mejora UX.

**Integración de servicios**: Interfaz genérica

.. note::

  - **Amplio uso**: La penetración de smartphones: 24% de la población, propietarios -> alta dependiencia. El 71% de estos, accede a Internet todos los días desde su teléfono inteligente, y no sale de su casa sin llevarlo. Implicación: Presencia: quienes incluyan tecnologías móviles como parte central de su estrategia, se beneficiarán de la oportunidad de atraer a estos nuevos usuarios conectados en forma permanente.
  - **Mayor comunicación**
  - **Tecnologías**: GPS, lector de huellas, notificaciones, acelerometro, camara -> integracion de tecnologias
  - Universidades utilizan sistemas abiertos -> Solucion disponible a otras universidades.

  **Comunicacion**: enriquezca entre los alumnos y la entidad -> mejorar su experiencia de usuario

----

:data-y: r0
:data-x: r1400

Objetivos
=========

Desarrollo de aplicación móvil
------------------------------

Integración de servicios para mejorar:

    * **Comunicación** entre alumnos, Universidad y Dependencias.

    * **Sociabilización** de contenidos

    * **Presencia** de la UNLP.

.. note::

    Integración para esta tesina: Moodle y guarani con app.


----

:id: objetivos_especificos

Objetivos específicos
=====================

Analizar:

* Contexto y aplicaciones existentes

* Herramientas para desarrollo de apps móviles.

* Servicios existentes (UNLP)

Desarrollar:

* Aplicación móvil

* API de integración

* Plugin Guaraní

* Plugin Moodle

Verificar Usabilidad.

.. note::

  - apps existentes en Argentina y el mundo para determinar las caracterısticas mas relevantes de este desarrollo
  - herramientas existentes: desarrollo app, multiplataforma, aprovechando tecnologias
  - integracion servicios UNLP
  - Desarrollo App: comunicar/representar info
  - API: interfaz genérica, segura
  - guaraní: contribución a universidades
  - moodle: idem, open source.
  - tecnicas de usabilidad para verificar el impacto en el uso de la herramienta. Estas permiten obtener un feedback de los potenciales usuarios

----

:data-y: r1000
:data-x: 0
:id: cap_1

Contexto
========

----

:id: cap_1_oss
:data-x: r500
:data-y: r0
:data-scale: 0.1

Sistemas Operativos móviles
===========================

.. image:: imagenes/presentacion/so_uso.png
    :height: 250em

.. note::
  - "Si pensamos en una app", debemos analizar implementacion a quien está enfocada (tesis)
  - Google Analytics: 01/2017 a 09/2017 en UNLP (guarani, cespi). Fechas pico de uso.
  - comentar sobre versiones: 4.4 o superiores (94%).
  - Enlazar con "algunas aplicaciones existentes"

----

:id: cap_1_apps
:data-y: r100
:data-x: r0

Aplicaciones universitarias existentes
======================================

* **UNLP y Argentina**: Informática UNLP, Jursoc UNLP, UNLP ART

.. image:: imagenes/presentacion/unlp_info.png
    :height: 200em

.. image:: imagenes/presentacion/unlp_jursoc.png
    :height: 200em

* **Otros paises**: Kurogo, Harvard, Oxford

.. note::

  - Novedades, aulas y horarios (de materias), info institucional y academica.
  - jursoc: Ubicacion de edificio GPS, nros sorteo.
  - ART: tels útiles, trámites.
  - Resaltar Kurogo: plataforma (Modo Labs) para crear apps móviles. Modular. Calendario, mensajeria, Biblioteca, emergencias, comedor, estacionamiento.

----

:data-y: r0
:data-x: r250

Principales características
===========================

* Novedades

* Planificación estudiantil

* Geolocalización

* Presencia Universitaria

.. note::
  - novedades: : diversidad en la forma de comunicacion en la universidad. Multiples apps. "pull to refresh".
  - planificacion estudiantil: Apps: Timetable (administrar tareas, examenes, sincronizar calend.)
  - Geoloc.: : < costos y > acceso red => Uso de geoloc. 
  - presencia: presente en los dispositivos moviles (smartphones y tablets), ámbito de las aplicaciones y tiendas virtuales, estableciendo un canal de difusion de contenidos.


