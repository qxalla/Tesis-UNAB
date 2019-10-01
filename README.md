# Plantilla LaTeX para memorias UNAB
Formato de Tesis en LaTeX para la Facultad de Ingeniería de Universidad Andrés Bello, Chile.

## Uso

Para usar esta plantilla tan sólo debe:

* cambiar parámetros básicos como autor y fecha en el documento de configuración (`config.tex`),
* modificar los archivos de apoyo (portada, resumen, capítulos, etc.) que desee, y
* compilar el documento maestro `tesis.tex` (usando una consola LaTeX o su editor favorito)

### Acerca de la Bibliografía
La bibliografía está contenida en el archivo `bibliography.bib`, y los estilos bibliográficos están en el archivo `thesis_unab.bst` (que básicamente es una castellanización de las normas APA, *American Psychological Association*).

**Nota:** Las normas APA requieren que todas las entradas bibliográficas (incluyendo **webpage**) tengan un año (*year*) definido. Si al compilar ve referencias extrañas en lugar de los nombres de los autores de artículos citados, entonces lo más probable es que tenga un problema con el año de una de sus referencias.

**Recomendación:** Ocupe un editor bibliográfico como Mendeley o BibDesk.

## Plataformas Soportadas

Esta plantilla es independiente de la plataforma empleada (Windows, Mac o Linux), sin embargo, debe tener cuidado con la codificación de caracteres por defecto.

### Codificación de caracteres (UTF-8)
La plantilla en LaTeX (`tesis.tex`) fue escrita usando una codificación de caracteres UTF-8 o *unicode*. MS Windows (y en ocasiones MAC OSX) ocupan por defecto otro tipo de codificación. Por esto, asegúrese que el editor LaTeX que esté ocupando esté configurado para usar UTF-8; o, puede cambiar la codificación de la plantilla de UTF-8 a Windows-1252 (o Mac Roman).

**NOTA:** No mezcle archivos con codificaciones diferentes o los resultados no serán los esperados.

## Licencia

> The MIT License (MIT), 2016

**Nota:** Las imágenes son propiedad intelectual de la Universidad Andrés Bello.
