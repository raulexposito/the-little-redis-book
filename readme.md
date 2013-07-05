## Acerca de ##
The Little Redis Book es un libro introductorio gratuito de Redis.

El libro fue escrito por [Karl Seguin](http://openmymind.net), con la asistencia de [Perry Neal](http://twitter.com/perryneal). La traducción ha sido realizada por [Raúl Expósito](http://raulexposito.com/).

Si te gusta este libro, posiblemente también te guste [The Little MongoDB Book](http://openmymind.net/2011/3/28/The-Little-MongoDB-Book/).

## Licencia ##
El libro puede ser distribuido libremente bajo la licencia [Attribution-NonCommercial 3.0 Unported](<http://creativecommons.org/licenses/by-nc/3.0/legalcode>).

## Traducciones ##
* [Inglés](https://github.com/karlseguin/the-little-redis-book) - Versión original.
* [Ruso](https://github.com/kondratovich/the-little-redis-book)
* [Italiano](https://github.com/sandroconforto/the-little-redis-book) - [pdf](https://github.com/sandroconforto/the-little-redis-book/raw/master/book/redisIt.pdf)
* [Chino](https://github.com/JasonLai256/the-little-redis-book)
* [Japonés](https://github.com/craftgear/the-little-redis-book/)

## Formatos ##
El libro está escrito en [Markdown](http://daringfireball.net/projects/markdown/) y se ha convertido en PDF usando [Pandoc](http://johnmacfarlane.net/pandoc/).

La plantilla TeX hace uso de el [remarcador de sintaxis de Javascript de Lena Herrmann](http://lenaherrmann.net/2010/05/20/javascript-syntax-highlighting-in-the-latex-listings-package).

Los formatos de Kindle y ePub han sido creados usando [Pandoc](http://johnmacfarlane.net/pandoc/).

## Generación de los Libros ##
Los paquetes mencionados a continuación son para Ubuntu. Si usas otro SO o distribución los nombres deben ser similares.

### PDF

#### Dependencias

Paquetes:

* `pandoc`
* `texlive-xetex`
* `texlive-latex-extra`
* `texlive-latex-recommended`

Tienes que tener instaladas [algunas fuentes](https://github.com/karlseguin/the-little-redis-book/blob/master/common/pdf-template.tex#L11).

O puedes cambiarlas por otras si quieres. Ten en cuenta que las fuentes pueden acarrear [problemas de generación](https://github.com/karlseguin/the-little-redis-book/issues/26).

#### Contrucción

Ejecuta `make es/redis.pdf`.

### ePub

#### Dependencias

Paquetes:

* `pandoc`

#### Construcción

Ejecuta `make es/redis.epub`.

### Mobi

#### Dependencias

Paquetes:

* `pandoc`

Debes tener [KindleGen](http://www.amazon.com/gp/feature.html?ie=UTF8&docId=1000765211) instalado también.

#### Construcción

Ejecuta `make es/redis.mobi`.

## Imagen del título ##
Se incluye un PSD de la imagen del título. La fuente utilizada es [Comfortaa](http://www.dafont.com/comfortaa.font).
