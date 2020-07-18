# Repaso extrusión por barrido y plano de referencia normal

## Repaso extrusión por barrido

En primer lugar vamos a hacer el diseño de un solido utilizando el sistema de barrido de croquis. Vamos a crear un codo de tubo con sección hexagonal como el que vemos en la imagen 1.

<center>

| Imagen 1 |
|:-:|  
| ![Codo a diseñar](../img/05/05-1.png) |
| Codo a diseñar |  

</center>

Para ello vamos a comenzar por crear un nuevo archivo y un boceto en el plano YZ que nos va a marcar la trayectoria de extrusión y las dimensiones del codo. Debe quedar como vemos en la imagen 2. Una vez finalizado el boceto cerramos la tarea.

<center>

| Imagen 2 |
|:-:|  
| ![Boceto en plano YZ para la trayectoria](../img/05/05-2.png) |
| Boceto en plano YZ para la trayectoria |  

</center>

Creamos un nuevo boceto en el mismo body (lo seleccionamos como activo si es necesario) ahora en el plano XZ. Será un hexágono con su centro en el origen de coordenadas y un circulo con centro en el mismo lugar de las dimensiones que vemos en la imagen 3. Una vez finalizado el boceto cerramos la tarea.

<center>

| Imagen 3 |
|:-:|  
| ![Boceto en plano XZ para la forma](../img/05/05-3.png) |
|  |  

</center>

La situación que debemos tener es la de la imagen 4.

<center>

| Imagen 4 |
|:-:|  
| ![Situación con los dos bocetos](../img/05/05-4.png) |
| Situación con los dos bocetos |  

</center>

Seleccionamos la herramienta de barrido de croquis, la de la imagen 5

<center>

| Imagen 5 |
|:-:|  
| ![Herramienta barrido](../img/05/05-5.png) |
| Herramienta barrido |  

</center>

Esto nos despliega la ventana de la imagen 6. Vemos como el objeto es el “Sketch001” y debemos hacer clic en la secuencia que se indica.

<center>

| Imagen 6 |
|:-:|  
| ![Ventana para selecciones de barrido](../img/05/05-6.png) |
| Ventana para selecciones de barrido |  

</center>

Nos aparece de forma inmediata el objeto final tal y como observamos en la imagen 7.

<center>

| Imagen 7 |
|:-:|  
| ![Resultado de la selección de la imagen 6](../img/05/05-7.png) |
| Resultado de la selección de la imagen 6 |  

</center>

Si cerramos la tarea haciendo clic en el botón OK veremos el trabajo terminado (imagen 8) y se observa el efecto del boceto creado para extruir con la forma hexagonal exterior y el orificio circular interior realizados a un tiempo, aunque es evidente que se puede hacer de otras formas esta parece bastante eficaz y no requiere de orificio posterior.

<center>

| Imagen 8 |
|:-:|  
| ![Codo hexagonal final por barrido](../img/05/05-8.png) |
| Codo hexagonal final por barrido |  

</center>

## Herramienta espesor

Vamos a ver el proceso para hacer lo mismo utilizando la herramienta de “Aplicar espesor” que resulta también muy interesante. Está disponible en el menú “Part” y la vemos en la imagen 9.

<center>

| Imagen 9 |
|:-:|  
| ![Herramienta espesor](../img/05/05-9.png) |
| Herramienta espesor |  

</center>

Partimos de la situación que vemos en la imagen 10, donde observamos que el orificio circular está eliminado.

<center>

| Imagen 10 |
|:-:|  
| ![Situación de partida para herramienta espesor](../img/05/05-10.png) |
| Situación de partida para herramienta espesor |  

</center>

Aplicamos una extrusión por barrido del boceto hexagonal siguiendo la trayectoria curva y obtenemos el sólido que vemos en la imagen 11.

<center>

| Imagen 11 |
|:-:|  
| ![Extrusión por barrido perfil hexagonal](../img/05/05-11.png) |
| Extrusión por barrido perfil hexagonal |  

</center>

Ahora nos situamos en el menú “Part”, seleccionamos una cara hexagonal del sólido y hacemos clic en la herramienta espesor citada, vemos como se nos crea el objeto tubo de forma inmediata. Podemos jugar con las diferentes opciones para ver como funcionan. En la imagen 12 vemos una solución que consiste en hacer clic en el botón “Caras” y posteriormente clic en ambas caras hexagonales para seleccionarlas.

<center>

| Imagen 12 | |
|:-:|:-:|   
| ![Espesor entre caras](../img/05/05-12a.png) |![Espesor entre caras](../img/05/05-12b.png) |
| Espesor entre caras: selección | Espesor entre caras: resultado | 

</center>

## Plano de referencia normal a una arista

Vamos a trabajar con el plano normal, que tiene como selecciones válidas las que vemos en la imagen 13. Vamos a obtener el mismo objeto que estamos viendo pero utilizando planos de referencia, en este caso plano de referencia normal a una arista.

<center>

| Imagen 13 |
|:-:|  
| ![Selecciones válidad en plano normal a una arista](../img/05/05-13.png) |
| Selecciones válidad en plano normal a una arista |  

</center>

Si queremos agilizar un poco el tiempo, el archivo creado anteriormente lo podemos copiar y renombrar y así podemos partir del primer boceto ya finalizado eliminando el resto de tareas realizadas.

Vamos a crear un plano normal a una arista, y esta va a ser la trayectoria de extrusión creada en el plano YZ, luego la situación de partida va a ser la que vemos en la imagen 14.

<center>

| Imagen 14 |
|:-:|  
| ![Trayectoria de partida](../img/05/05-14.png) |
| Trayectoria de partida |  

</center>

Con la arista seleccionada desde vista 3D como en la imagen 15 hacemos clic en crear plano de referencia.

<center>

| Imagen 15 |
|:-:|  
| ![Selección de arista (trayectoria) en vista 3D y creación de plano](../img/05/05-15.png) |
| Selección de arista (trayectoria) en vista 3D y creación de plano |  

</center>

Se mostrará una ventana como la de la imagen 16, donde escogemos “Normal a arista” y donde observamos que hay seleccionada una arista. También podemos ver el plano que vamos a crear.

<center>

| Imagen 16 |
|:-:|  
| ![Escogemos opción para el plano](../img/05/05-16.png) |
| Escogemos opción para el plano |  

</center>

Una vez hacemos clic en “OK” el aspecto del plano creado lo vemos en la imagen 17.

<center>

| Imagen 17 |
|:-:|  
| ![Aspecto del plano](../img/05/05-17.png) |
| Aspecto del plano |  

</center>

En la parte inferior de la ventana de tareas del plano tenemos algunas opciones que afectan a la posición y orientación del plano. En las imágenes 18 vemos como hacer un desplazamiento sobre su vector. En este caso la dirección del vector es la positiva del eje Z respecto a los ejes de referencia y por eso la cota es negativa.

<center>

| Imagen 18 |  |
|:-:|:-:|
| ![Opciones de posición del plano](../img/05/05-18a.png) | ![Efecto en la vista 3D](../img/05/05-18b.png) |
| Opciones de posición del plano | Efecto en la vista 3D |

</center>

Si necesitamos cambiar ese valor a positivo (cambiara la dirección del vector) debemos marcar la opción “Voltear caras”, como vemos en las imágenes 19 donde se observa como el mismo valor desplaza al plano justo en la dirección opuesta.

<center>

| Imagen 19 |  |
|:-:|:-:|
| ![Opciones de posición del plano](../img/05/05-19a.png) | ![Efecto en la vista 3D](../img/05/05-19b.png) |
| Opciones de posición del plano | Efecto en la vista 3D |

</center>

Ya estamos en condiciones de crear el mismo boceto que anteriormente, en cualquiera de las formas vistas, para realizar una extrusión por trayectoria. Si seleccionamos el plano de referencia y creamos un nuevo boceto tendremos la situación que vemos en la imagen 20.

<center>

| Imagen 20 |
|:-:|  
| ![Realización de boceto sobre plano creado](../img/05/05-20.png) |
| Realización de boceto sobre plano creado |  

</center>

Creamos el nuevo boceto como el que podemos ver en la imagen 3. Una vez finalizado el boceto aplicamos la extrusión por barrido vista anteriormente y tendremos la situación que vemos en la imagen 21.

<center>

| Imagen 21 |
|:-:|  
| ![Barrido por trayectoria](../img/05/05-21.png) |
| Barrido por trayectoria |  

</center>

Si cerramos la tarea y ocultamos e plano de referencia tenemos el resultado final que vemos en la siguiente 22.

<center>

| Imagen 22 |
|:-:|  
| ![Aspecto final del objeto 3D](../img/05/05-22.png) |
| Aspecto final del objeto 3D |  

</center>

## Centro de masas de una arista

Vamos a ver como situar el plano en el centro de masas de la arista. Para ello creamos un punto en el centro de masas, como vemos en la imagen 23.

<center>

| Imagen 23 |
|:-:|  
| ![Situar plano en centro de masas de arista](../img/05/05-23.png) |
| Situar plano en centro de masas de arista |  

</center>

Ahora tan solo debemos crear el plano y hacer clic en el punto creado y el plano se creará normal a la arista y situado en su centro de masas, como vemos en la imagen 24.

<center>

| Imagen 24 |
|:-:|  
| ![Creación de plano a partir de punto en centro de masas](../img/05/05-24.png) |
| Creación de plano a partir de punto en centro de masas |  

</center>

A partir de este plano ya podemos trabajar de cualquieras de las formas descritas para crear un boceto que tenga como base ese plano.

Para ver mejor la aplicación de esto vamos a partir de una pieza basada en un boceto como el de la imagen 25a que extruiremos 10mm para que quede como en la imagen 25b.

<center>

| Imagen 25a | Imagen 25b |
|:-:|:-:| 
| ![Boceto de partida](../img/05/05-25a.png) | ![Aspecto final](../img/05/05-25b.png) |
| 25a. Boceto de partida | 25b. Aspecto final |  

</center>

La idea es hacer un taladro centrado en la cara curva que atraviese toda la pieza. Inicialmente podríamos pensar en seleccionar la cara y clicar en crear boceto, pero esto no va a funcionar y FreeCAD nos va a mostrar el mensaje de error que vemos en la imagen 26.

<center>

| Imagen 26 |
|:-:|  
| ![Error por selección cara curva como referencia](../img/05/05-26.png) |
| Error por selección cara curva como referencia |  

</center>

Indicándonos de forma muy clara que un boceto no se puede realizar sobre una cara curva.

Vamos a crear un punto en el centro de masas de la parte curva de la pieza, para lo cual seleccionamos la cara y hacemos clic en crear punto, escogiendo centro de masas, tal y como vemos en la imagen 27.

<center>

| Imagen 27 |
|:-:|  
| ![Crear punto en centro de masas de cara curva](../img/05/05-27.png) |
| Crear punto en centro de masas de cara curva |  

</center>

En la imagen 28 observamos que en este caso el centro de masas de esa cara curva está fuera de la pieza a la que pertenece.

<center>

| Imagen 28 |
|:-:|  
| ![Posición del centro de masas en cara curva](../img/05/05-28.png) |
| Posición del centro de masas en cara curva |  

</center>

A continuación vamos a crear un punto de referencia en cada una de las aristas rectas que situaremos en su centro de masas, tal y como se observa en la imagen 29.

<center>

| Imagen 29 |
|:-:|  
| ![Creación de mas puntos en centros de masas de aristas](../img/05/05-29.png) |
| Creación de mas puntos en centros de masas de aristas |  

</center>

Ahora creamos el plano que pasa por tres puntos haciendo clic en uno de los puntos de una arista, en segundo lugar en el punto de la otra arista y en tercer lugar en el punto que representa el centro de masas de la curva y escogemos normal a tres puntos, obteniendo el plano que vemos en la imagen 30. Durante el proceso observamos que FreeCAD va intentando dar soluciones según las selecciones que vamos haciendo.

<center>

| Imagen 30 |
|:-:|  
| ![Plano normal a los tres puntos](../img/05/05-30.png) |
| Plano normal a los tres puntos |  

</center>

Ahora podemos hacer el boceto del taladro pasante que estamos buscando situándolo sobre el plano recién creado, tal y como observamos en la imagen 31.

<center>

| Imagen 31 |
|:-:|  
| ![Creación de boceto para taladro sobre el plano creado](../img/05/05-31.png) |
| Creación de boceto para taladro sobre el plano creado |  

</center>

Vamos a hacer una sencilla comprobación de que el centro del taladro va a estar en el centro esperado y para ello vamos a utilizar los iconos que se explican a continuación.

![Icono de arista vinculada](../img/05/icon-arista-vinculada.png) 

Crear una arista vinculada a una geometría externa. Con esto crearemos dos líneas auxiliares (aparecerán en azul) vinculadas a las aristas rectas de la cara curva. 

![Icono para poner en modo referencia la barra de herramientas](../img/05/icon-modo-refer.png)

Cambiar la barra de herramientas a las restricciones seleccionadas a/desde el modo de referencia. Con esto crearemos cotas constructivas que no crearán ningún conflicto con las dimensiones reales de la pieza. Tanto la barra de herramientas como las cotas creadas se pondrán en azul indicando que son auxiliares. 

Si realizamos las acotaciones que vemos en la imagen 32 podemos observar como efectivamente el centro del agujero va a estar situado en el centro de masas.

<center>

| Imagen 32 |
|:-:|  
| ![Acotaciones para comprobar centro de masas](../img/05/05-32.png) |
| Acotaciones para comprobar centro de masas |  

</center>

Una vez cerrada la tarea anterior hacemos clic en crear vaciado y procedemos según vemos en la imagen 33.

<center>

| Imagen 33 |
|:-:|  
| ![Creación del taladro mediante vaciado](../img/05/05-33.png) |
| Creación del taladro mediante vaciado |  

</center>

El resultado final lo podemos observa en la animación que vemos a continuación en la que se han ocultado tanto los puntos como el plano creados.

<center>

 ![Animación con el resultado final](../img/GIF/05a.gif) 

</center>