Descripción
===========
Los scripts fueron diseñados para trabajar en un sistema GNU & Linux; utilizando el Bash Shell. Todas las pruebas se hicieron
utilizando Fedora 19.

Requerimientos
==============
* bash
* wget
* poppler-utils

Instalación
===========
Instala los cripts en ~/bin.

Hay distribuciones que no tienen a ~/bin en su $PATH. En esos casos, es mejor ponerles en: 

::

    /usr/local/bin

Ambos scripts deben estar en el $PATH.

Recuerda asignarles el permiso de ejecución pertinente:

::

    # para ser ejecutados solo por el usuario:
    chmod u+x ruta/a/ley2txt ruta/a/leyes2github

    # para ser ejecutados por el grupo y el usuario:
    chmod ug+x ruta/a/ley2txt ruta/a/leyes2github

    # para ser ejecutados por quien sea:
    chmod a+x ruta/a/ley2txt ruta/a/leyes2github
