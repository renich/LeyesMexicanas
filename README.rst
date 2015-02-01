Leyes Mexicanas
===============

Descripción
===========
Compendio de leyes de los Estados Unidos Mexicanos; en texto. Ésta se actualiza, automáticamente, a diario; a las 00:00 GMT.

Chécate el `Índice </federales/txt/%C3%ADndice.txt>`_.

Contexto
========
El Gobierno Mexicano, actualmente, ofrece las leyes por medio del sitio oficial de los Diputados Federales:
http://www.diputados.gob.mx/.

Por lo pronto, solo se ofrece en formatos no-libres y, en algunos casos, en HTML.

Ésto, hace muy difícil saber qué cambios específicos se hicieron a las leyes; en qué día y en qué líneas de la misma ley; haciendo
difícil la comparación de los cambios que surgen con el tiempo.

En el mundo del Software Libre y de Código Abierto; o FOSS, existen herramientas para:

* Control de versiones.
* Conversión de formatos cerrados a formatos abiertos.

Github es una red social que permite publicar proyectos abiertos; sin costo alguno; por medio de la herramienta Git.

Procedimiento
=============
1. Se hace un sondeo por la página de los diputados para capturar la lista de archivos que contiene.
2. Se descarga cada archivo de la lista.
3. Se convierten los archivos a formato de téxto; utilizando el programa pdftotext.
4. Se sincronizan los documentos con el repositorio de Git; haciendo un commit del día.
5. Se publican los cambios en la página de Github.


Autor: 
    Renich Bon Ciric <renich@woralelandia.com>

Licencia: 
    GPLv3 o >
