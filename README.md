# Programas requeridos:
* Visual Studio 2019 Community (C++ Libraries)
Link:
https://visualstudio.microsoft.com/es/downloads/
* CLion v2020.2.3
Link:
https://www.jetbrains.com/clion/download/#section=windows
* Git-Kraken 
link:
https://www.gitkraken.com/download

# Funcionamiento del Cliente/Servidor
## Servidor:
* Se debe ejecutar en el compilador, en caso de Clion (Mayus + F10)
* Debe estar abierto antes que el cliente para recibir las instrucciones
* Recibe una instruccion de tipo String que convierte en un grafo, con el cual calcula la distancia más corta entre los vertices.
* Devuelve el grafo con las distancias más cortas entre los vertices.
## Cliente:
* Se debe ejecutar en el compilador, en caso de CLion (Mayus + F10)
* Se debe enviar el tamaño del grafo seguido de el grafo que se quiera evaluar
* La instruccion que debe seguir el siguiente formato: (4,4){{0,5,INF,10},{INF,0,3,INF},{INF,INF,0,1},{INF,INF,INF,0}} y se debe presionar ENTER para enviar la instrucion al Server.
* Como respuesta el enviara la instruccion de vuelta para confirmar que ha sido enviada.
## Documentacion Doxygen
* https://r3dp4r4d153.github.io/DATOS_II_TAREA_EXTRACLASE_I/html/index.html
