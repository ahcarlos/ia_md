# Práctica Inteligencia Artificial: Coche Autónomo
###Guía de ejecución del archivo.jar


Al ejecutar el archivo, se mostrará un panel con dos botones: **Manual** y **Automático**.
1. Haciendo click sobre *Manual* se desplegará más abajo dos campos para rellenar con el número de filas
y número de columnas deseadas. Al presionar el botón **Calcular** se generará el tablero.

2. Haciendo click sobre el botón **Automático** se generará un tablero de dimensiones aleatorias
de a lo sumo 200x200.

Una vez  tenga el panel de la matriz generado, hay que elegir una posición para el _coche_
y una posición para la _meta_. Para ello hay que:

1. Identificar la casilla deseada para el coche.
    * Hacer click sobre la casilla hasta que aparezca la imagen: ![Imagen coche](http://banot.etsii.ull.es/alu4605/images_ia/coche3.png "Coche")

2. Identificar la casilla deseada para la meta.
    * Hacer click sobre la casilla hasta que aparezca la imagen: ![Imagen meta](http://banot.etsii.ull.es/alu4605/images_ia/meta2.png "Meta")


El botón **Menú Inicio** permite volver al panel inicial para seleccionar el tamaño de la matriz ssegún la modalidad **Manual** y **Automático**.

El botón **A*** llevará a cabo el algoritmo A* de tal manera que se encontrará el camino de menor coste entre el coche y la meta. 
(Se pintará en rojo dicho camino encontrado). Si no se encuentra dicho camino porque no es accesible, saldrá un mensaje que lo indica.

El botón **A* recogiendo pasajeros** llevará a cabo el algoritmo A* de tal manera que recogerá a tres pasajeros y los llevará hacia
el destino, es decir, la meta. En el paso intermedio de recoger un pasajero, aparecerá un cuadro de información. Pulsar en aceptar y
se continuará con la ejecución.