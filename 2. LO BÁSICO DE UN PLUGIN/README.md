# Ejemplo: "Un plugin en WordPress es un conjunto de funciones agrupadas que pueden ser añadidas a un sitio web para ampliar sus capacidades. Mi primer plugin constaba de un archivo principal PHP y un archivo README. En la documentación no está, pero descubrí que un buen método es utilizar un cargador de clases (autoloader) para organizar mejor el código y facilitar su mantenimiento a medida que el plugin crece."


- Buenas practicas de estructura de carpetas y archivos

Debes crear la carpeta principal preferiblemente con el nombre de tu plugin, ten en cuenta no usar nombres comunes que puedan generar conflictos con plugins existentes *************

Estructura de carpetas

/mi-plugin
    /assets
        /css
            style.css
        /js
            script.js
        /img
            logo.png
    /includes
        class-mi-plugin.php
        functions.php
    /languages
        mi-plugin-es_ES.mo
        mi-plugin-es_ES.po
    /templates
        form-template.php
    mi-plugin.php
    uninstall.php
    readme.txt

    
