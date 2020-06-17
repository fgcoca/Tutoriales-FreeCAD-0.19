# Body en PartDesign
## Definiciones  
A partir de la versión 0.17 de FreeCAD para trabajar con bocetos es necesario que exista al menos un cuerpo o body, veamos el concepto de cuerpo en que consiste:  

*Un cuerpo PartDesign está diseñado para modelar un solo sólido contiguo. El significado de "contiguo" hace referencia a un elemento hecho en una sola pieza, sin partes móviles o sólidos desconectados. Ejemplos de sólidos contiguos son una tuerca, una arandela y un tornillo (imagen 1.1) en que cada uno es una sola pieza sólida sin partes móviles, por lo que cada uno puede ser modelado por un cuerpo PartDesign.    
Una vez que estos sólidos contiguos se unen en algún tipo de disposición, se convierten en un "ensamblaje", como se observa en la imagen 1.2. En un ensamblaje, los objetos no se fusionan, sino que simplemente se "apilan" o se colocan uno al lado del otro, y siguen siendo partes individuales.*  

| Imagen 1.1 | Imagen 1.2 |  
|:-:|:-:|  
| ![](../img/01/01-1_1.png) | ![](../img/01/01-1_2.png) | 
| Tres sólidos contiguos individuales, cada uno de ellos modelado por un cuerpo PartDesign. | Los tres cuerpos individuales ensamblados |

Al crear un *Body* se crea un objeto *Origin* que incluye los ejes X, Y y Z, y los planos estándar que delimitan el espacio. En la imagen 2 vemos estos elementos.  

| Imagen 2.1 | Imagen 2.2 | Imagen 2.3 |    
|:-:|:-:|:-:|
| ![](../img/01/01-2_1.png) | ![](../img//01/01-2_2.png) | ![](../img/01/01-2_3.png) |
| Ejes y planos. | Solo los ejes.  | Solo los planos. |  

Estos elementos se pueden utilizar como referencias para bocetos y objetos primitivos.  
Cuando hablamos de un cuerpo como un sólido contiguo significa que lo podemos mover como una unidad sin variar las características individuales. Podemos crear múltiples cuerpos para poder crear ensambles. En la imagen 3 vemos el entorno inicial con una figura simple incluida.
<center>  

| Imagen 3 | 
|:-:|  
| ![](../img/01/01-3.png) | 
| Sólido, ejes y planos  |

</center>

## Creación de un boceto
Si estando en el banco de trabajo PartDesign creamos directamente un boceto se creará de forma automática un cuerpo que lo contenga. En cualquier caso se nos va a mostrar la opción de escoger en que plano queremos crear nuestro boceto, como vemos en la imagen 4, donde se ha seleccionado el plano XY.  

<center>

| Imagen 4 | 
|:-:|  
| ![](../img/01/01-4.png) | 
| Selección de plano XY  |

</center>

Vamos a crear nuestro boceto aplicando una restricción de simetría de dos vértices diagonales respecto al origen de coordenadas y las cotas correspondientes. El tipo de restricción diagonal hace que nuestro rectángulo esté centrado al origen de coordenadas. Todas las restricciones aplicadas hacen que nuestro boceto tenga cero grados de libertad, o sea que está totalmente restringido y por ello se muestra en color verde. Se aconseja observar los grados de libertad según vamos aplicando restricciones y tratar de entender como cambian. En la imagen 5 tenemos el resultado.

<center>

| Imagen 5 | 
|:-:|  
| ![](../img/01/01-5.png) | 
| Boceto totalmente restringido  |

</center>

Ya podemos salir de la tarea y proceder a extruir nuestro boceto una determinada longitud, por ejemplo 5 cm, obteniendo el resultado que vemos en la imagen 6.

<center>

| Imagen 6 | 
|:-:|  
| ![](../img/01/01-6.png) | 
| Sólido a partir de extrusión de boceto  |

</center>

## La normal de un plano
Cada plano tiene sus propios ejes de coordenadas X, Y, Z que se conocen como ejes locales y que vemos en la imagen 7.

<center>

| Imagen 7 | 
|:-:|  
| ![](../img/01/01-7.png) | 
| Plano y sus ejes de coordenadas locales  |

</center>

La normal a un plano es un vector perpendicular al mismo que coincide con el eje Z local. En la imagen 8 vemos representado el vector perpendicular al plano XY y se observa como coincide con el eje Z local.

<center>

| Imagen 8 | 
|:-:|  
| ![](../img/01/01-8.png) | 
| Vector normal al plano XY  |

</center>

Cuando creamos un boceto FreeCAD nos sitúa en una vista en la que el vector normal al plano escogido apunta hacia nosotros, como se observa en la imagen 9, donde hemos rotado mínimamente la vista original para que se aprecie el vector normal.

<center>

| Imagen 9 | 
|:-:|  
| ![](../img/01/01-9.png) | 
| Visualización del vector normal al crear boceto   |

</center>

## Tipos de extrusión
La extrusión tipo cota de un boceto se realiza siguiendo la trayectoria del vector normal al plano y puede ser de tres formas posibles, como vemos en la imagen 10.

| Imagen 10 | Extrusión tipo cota en plano XY|
|:-:|---|  
| ![](../img/01/01-10_1.png) | Con valores positivos   |
| ![](../img/01/01-10_2.png) | Con valores negativos   |
| ![](../img/01/01-10_3.png) | Simétrica al plano   |

Uno de los tipos de extrusión aplicables en este ejemplo que en particular resulta útil es el de *Dos dimensiones* que vemos en la imagen 11.

<center>

| Imagen 11 | 
|:-:|  
| ![](../img/01/01-11.png) | 
| Extrusión de tipo dos dimensiones   |

</center>

Esto mismo va a ocurrir con el plano de referencia XZ y su vector normal que coincide con el eje Y, como vemos en la imagen 12 con un sólido triangular.

| Imagen 12 | Extrusión tipo cota en plano XZ|
|:-:|---|  
| ![](../img/01/01-12_1.png) | Con valores positivos   |
| ![](../img/01/01-12_2.png) | Con valores negativos   |
| ![](../img/01/01-12_3.png) | Simétrica al plano   |
| ![](../img/01/01-12_4.png) | Dos dimensiones   |

En la imagen 13 vemos el proceso repetido para el plano YZ y su vector normal, que lógicamente coincide con el eje X. En este caso usamos un cilindro como sólido.

| Imagen 13 | Extrusión tipo cota en plano YZ|
|:-:|---|  
| ![](../img/01/01-13_1.png) | Con valores positivos   |
| ![](../img/01/01-13_2.png) | Con valores negativos   |
| ![](../img/01/01-13_3.png) | Simétrica al plano   |
| ![](../img/01/01-13_4.png) | Dos dimensiones   |

Con los tres sólidos creados podemos hacer una operación booleana de unión y obtener un modelo 3D en el que se ven los cuerpos, los planos de referencia, los vectores normales y por supuesto la cruz de ejes de referencia del sistema. En la imagen 14 lo vemos claramente.

<center>

| Imagen 14 | 
|:-:|  
| ![](../img/01/01-14.png) | 
| Modelo 3D resultado de la unión de tres sólidos   |

</center>

En la animación siguiente vemos el resultado final.

<center>

![](../img/GIF/01a.gif)

</center>
