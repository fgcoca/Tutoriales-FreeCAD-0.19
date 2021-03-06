# Plano de referencia fijado a objetos

Vamos a explicar como crear planos de referencia fijados a los objetos denominados “Plano XY, Plano XZ y Plano ZY” representados en la imagen 1. Ya hemos vistos que cuando creamos un cuerpo o body se crea un elemento denominado “Origin” que contiene los tres planos y los tres ejes de referencia del sistema de coordenadas.

<center>

| Imagen 1 |
|:-:|  
| ![Planos de referencia](../img/04/04-1.png) |
| Planos de referencia |  

</center>

Si hacemos clic en crear un nuevo plano de referencia, esto va a mostrar por defecto un plano en el de referencia XY y se abrirá la ventana de parámetros para seleccionar y con los modos de fijación, pero lógicamente sin tener ninguna referencia seleccionada, como vemos en la imagen 2.

<center>

| Imagen 2 |
|:-:|  
| ![Ventana de parámetros plano de referencia](../img/04/04-2.png) |
| Ventana de parámetros plano de referencia |  

</center>

Si dejamos el cursor, por ejemplo, sobre la opción de “Objetos de XY” se mostrarán los tipos de fijación que estarán disponibles y que vemos en la imagen 3.

<center>

| Imagen 3 |
|:-:|  
| ![Tipos de fijación disponibles](../img/04/04-3.png) |
| Tipos de fijación disponibles |  

</center>

Si en esta situación cerramos la tarea clicando en OK se nos mostrará una advertencia como la que vemos en la imagen 4.

<center>

| Imagen 4 |
|:-:|  
| ![Creación de plano de referencia inamovible](../img/04/04-4.png) |
| Creación de plano de referencia inamovible |  

</center>

Si hacemos clic en “Yes” se nos crea un plano en XY pero que estará fijado al plano XY de referencia y no podremos moverlo, como vemos en la imagen 5.

<center>

| Imagen 5 |
|:-:|  
| ![Plano re referencia inamovible fijado al de referencia](../img/04/04-5.png) |
| Plano re referencia fijado al de referencia XY |  

</center>

Vamos a repetir la operación de crear un plano de referencia pero esta vez vamos a seleccionar uno de los planos de referencia del sistema y podemos observar como el plano que se va a crear queda atado al plano de referencia seleccionado y además con valores de movimiento editables, como se observa en la imágen 6.

<center>

| Imagen 6 |
|:-:|  
| ![Plano re referencia movible fijado al de referencia](../img/04/04-6.png) |
| Plano re referencia **movible** fijado al de referencia |  

</center>

Pues bien, lo que vamos a ver a continuación es como fijar el plano de referencia a “Objetos de XY, de XZ o de YZ”. Como inicio vamos a diseñar la pieza número 3 de las fichas de referencia utilizando un plano de referencia para ello. El aspecto de la figura a diseñar en la ficha es el de la imagen 7.

<center>

| Imagen 7 |
|:-:|  
| ![Pieza número 3 de la ficha 1](../img/04/04-7.png) |
| Pieza número 3 de la ficha 1 a diseñar |  

</center>

Realizamos un croquis sobre el plano XZ de las dimensiones que vemos en la imagen 8a y lo extruimos 60 mm para obtener algo similar a lo de la imagen 8b.

<center>

| Imagen 8a | Imagen 8b |
|:-:|:-:|
| ![Croquis inicial pieza 3 - ficha 1](../img/04/04-8a.png) | ![Pieza 3 - ficha 1 inicial](../img/04/04-8b.png) |
| Croquis inicial pieza 3 - ficha 1 | Pieza 3 - ficha 1 inicial |  

</center>

Para crear el trozo que falta vamos a utilizar un plano que crearemos seleccionado el plano XY de referencia y que desplazaremos 60mm en el eje Z para situarlo a la altura del rectángulo superior. Esto lo vemos en la imagen 9. Es evidente que se puede hacer creando el croquis directamente sobre la cara, pero para ver el funcionamiento de este tipo de planos resulta perfectamente válido.

<center>

| Imagen 9 |
|:-:|  
| ![Plano de referencia fijado a XY desplazado](../img/04/04-9.png) |
| Plano de referencia fijado a XY desplazado |  

</center>

Seleccionando el plano creado y clicamos en boceto para tener uno nuevo como vemos en la imagen 10.

<center>

| Imagen 10 | |
|:-:|:-:|  
| ![Boceto con dimensiones](../img/04/04-10a.png) | ![Boceto finalizado](../img/04/04-10b.png) |
| Boceto con dimensiones | Boceto finalizado |

</center>

Simplemente queda extruirlo y tenemos finalizada la pieza con una parte creada a partir de un plano de referencia, tal y como vemos en la imagen 11.

<center>

| Imagen 11 |
|:-:|  
| ![Pieza 3 - ficha 1 finalizada](../img/04/04-11.png) |
| Pieza 3 - ficha 1 finalizada |  

</center>

Es evidente que esta misma situación podemos conseguirla de otras formas incluso más sencillas, pero la ventaja que tiene hacerlo mediante un plano es que el trozo creado puede recibir tareas independiente del objeto global relativas por ejemplo a la orientación del plano. En la imagen 12 vemos como hemos rotado el plano en dos ejes y como lo hace la figura.

<center>

| Imagen 12 | |
|:-:|:-:|  
| ![Ejes de rotación: Del desvío = Z; Paso = Y y Lanzar = X](../img/04/04-12a.png) | ![Rotación del plano de referencia](../img/04/04-12b.png) |
| Ejes de rotación: Del desvío = Z; Paso = Y y Lanzar = X | Rotación del plano de referencia |  

</center>

Otro aspecto importante a tener en cuenta cuando trabajamos con planos de referencia es la forma de selección y hay que saber que no es lo mismo seleccionar objetos desde la ventana 3D que desde la vista combinada. Si hacemos un clic en alguna parte de un boceto en la ventana 3D solamente seleccionamos una parte del objeto (imagen 13a), pero en cambio si hacemos clic sobre el objeto en vista combinada el objeto se selecciona entero (imagen 13b).

<center>

| Imagen 13a | Imagen 13b |
|:-:|:-:|  
| ![Selección desde ventana 3D](../img/04/04-13a.png) | ![Selección desde vista combinada](../img/04/04-13b.png) |
| Selección desde ventana 3D | Selección desde vista combinada |

</center>

Aunque si podemos hacer un clic sobre un objeto de la parte 3D y una vez seleccionado otro clic sobre el mismo objeto y quedará seleccionado completo.

Si escogemos una arista del boceto y clicamos en crear plano de referencia tendremos la situación de la imagen 14.

<center>

| Imagen 14 |
|:-:|  
| ![Creación de plano de referencia a partir de selección de arista](../img/04/04-14.png) |
| Creación de plano de referencia a partir de selección de arista |  

</center>

En cambio si seleccionamos el boceto entero (un objeto) y hacemos lo mismo tendremos la situación que vemos en la imagen 15.

<center>

| Imagen 15 |
|:-:|  
| ![Creación de plano a partir de seleccionar el objeto boceto]() |
| Creación de plano a partir de seleccionar el objeto boceto |  

</center>

Esto mismo ocurre cuando tenemos un sólido y seguimos los mismos procedimientos.

Cuando hemos visto los tipos de referencia las combinaciones de referencia posibles (imagen 16) eran “Cualquiera” que es lo visto hasta ahora y “Cónica” que vamos a tratar a continuación.

<center>

| Imagen 16 |
|:-:|  
| ![Tipos de combinaciones de referencia](../img/04/04-16.png) |
| Tipos de combinaciones de referencia |  

</center>

Recodemos que una sección cónica o simplemente cónica es la curva resultante de la intersección entre un cono y un plano y que pueden ser una de las cuatro que vemos en la imagen 17.

<center>

| Imagen 17 |
|:-:|  
| ![Cónicas](../img/04/04-17.png) |
| Cónicas |  

</center>

Vamos a crear por ejemplo el boceto de una elipse y un círculo y lo hacemos creando un nuevo body, como vemos en la imagen 18.

<center>

| Imagen 18 |
|:-:|  
| ![Bocetos de cónicas](../img/04/04-18.png) |
| Bocetos de cónicas |  

</center>

Vamos a ver las diferencias entre seleccionar desde la ventana 3D y desde la vista combinada. Si hacemos clic en la elipse, por ejemplo, y creamos un nuevo plano de referencia la tarea que se nos abre nos muestra opciones de fijación relacionadas con curvas (Frenet, Concéntrico,...), aunque también nos muestra las opciones vistas hasta ahora de Objetos XY, XZ e YZ. La imagen 19 muestra lo dicho.

<center>

| Imagen 19 |
|:-:|  
| ![Opciones de fijación a curvas](../img/04/04-19.png) |
| Opciones de fijación a curvas |  

</center>

Esto es así porque no están seleccionados todos los objetos (lo vemos en “Seleccionar”) sino solo la elipse.

Si ahora hacemos la selección del boceto desde la vista combinada quedarán seleccionados todos los objetos y la ventana muestra solo los Objetos XY, XZ e YZ y la selección es del boceto completo, como vemos en la imagen 20.

<center>

| Imagen 20 |
|:-:|  
| ![Selección de cónicas desde vista combinada](../img/04/04-20.png) |
| Selección de cónicas desde vista combinada |  

</center>

Si por cualquier circunstancia al intentar crear el plano se nos muestra un mensaje como el de la imagen 21.

<center>

| Imagen 21 |
|:-:|  
| ![Error por no tener activo un body](../img/04/04-21.png) |
| Error por no tener activo un body |  

</center>

Nos dirigimos a la vista combinada y situamos el cursor sobre el cuerpo que queremos poner como activo y haciendo clic con el botón secundario se muestran las opciones (imagen 22), basta con escoger la de cambiar a cuerpo activo y ya estaría.

<center>

| Imagen 22 |
|:-:|  
| ![Poner activo un body](../img/04/04-22.png) |
| Poner activo un body |  

</center>
