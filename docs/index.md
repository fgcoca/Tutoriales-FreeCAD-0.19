# Nuevo PartDesign en FreeCAD 0.19. Planos de referencia

## Antes de nada

***
Lo primero que voy a hacer es recomendar seguir las dos temporadas de tutoriales de diseño de piezas con Freecad del gran maestro [Juan González Gómez](https://es.wikipedia.org/wiki/Juan_Gonz%C3%A1lez_G%C3%B3mez), mas conocido como Obijuan, estos son los enlaces a las mismas:  

* [Temporada 1: Tutorial de diseño de piezas con freecad](http://www.iearobotics.com/wiki/index.php?title=Dise%C3%B1o_de_piezas_con_Freecad)  

* [Temporada 2: Tutorial de diseño de piezas con freecad](http://www.iearobotics.com/wiki/index.php?title=Tutorial_Freecad._Temporada_2)  

En la [Obijuan Academy](http://www.iearobotics.com/wiki/index.php?title=Obijuan_Academy) se puede encontrar gran cantidad de información sobre diferentes temáticas pero siempre con el sello carácterístico e inconfundible que le imprime el maestro.

No voy a redundar mas que en agradecer la enorme labor de difusión que realiza cada día tanto en hardware como en software libre.

Es muy conveniente, aunque sea a modo de repaso, seguir este tutorial hasta el final para tener claro el manejo del banco de trabajo “Part Design”:  

* [Tutorial básico de Part Design 0.17](https://wiki.freecadweb.org/Basic_Part_Design_Tutorial_017/es)

**¡¡ GRACIAS !!**

## Que vamos a aprender

***

Vamos a explicar las principales novedades que presenta el banco de trabajo PartDesign y que aparecen a partir de la versión 0.18. En realidad estos serían mis apuntes de los temas tratados.

Aprenderemos a crear las vistas de una determinada pieza y a realizar las acotaciones de la misma tanto en las vistas como en la perspectiva.

Estudiaremos la forma de trabajar con distintos planos de referencia.

Veremos también como limitar las extrusiones y vaciados con estos planos de referencia.

Nos introduciremos en la creación de ensambles.

El apartado 'Tutoriales' es donde se realizan las explicaciones correspondientes en cada uno de los temas tratados. En estos temas van apareciendo difeentes modelos diseñados en 3D que se realizan bien a partir de las fichas establecidas como referencia o bien a partir de las referencias indicadas en la Webgrafía. El apartado 'Archivos 3D' se dedica a suministrar los diseños realizados en formato fuente con FreeCAD 0.19 así como los modelos exportados en formato amf y stl.

Hacer referencia especial a que trabajaremos con las fichas creadas por [profe tecno](https://www.blogger.com/profile/17628412711616354979) en este [enlace](http://esoytec.blogspot.com/). Son fichas de nivel 3º de ESO pero por su simplicidad nos resultan útiles para los fines que se crea este sitio.

Fundamentalmente vamos a trabajar con estas dos versiones de FreeCAD:

* **FreeCAD 0.18** (official 0.18.4 release)
  
    : OS: Ubuntu 18.04.4 LTS
    : Word size of OS: 64-bit
    : Word size of FreeCAD: 64-bit
    : Version: 0.18.16131 (Git) AppImage
    : Build type: Release

* **FreeCAD 0.19** (Pre-release)

    : OS: Ubuntu 18.04.4 LTS
    : Word size of OS: 64-bit
    : Word size of FreeCAD: 64-bit
    : Version: 0.19.21514 (Git) AppImage
    : Build type: Release
