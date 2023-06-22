# Tarea-3-Sistemas-Operativos
## Cajas registradoras Supermercado
### Esta tarea consiste en implementar el funcionamiento de una o dos cajas registradoras de un supermercado por medio del lenguaje de programación ***C***, en el cual se utilizará las bibliotecas  ***ncurses.h***, ***semaphore.h***, para el control de hebras, y para el manejo de pantalla se utilizara ***ncurses.h***.

## Programas utilizados

* [GitHub Desktop](https://desktop.github.com/) - Herramienta para tener los repositorios en la nube y mantener las versiones.
* [Visual Studio Code](https://visualstudio.microsoft.com/es/) - IDE y editor para la creación del Algoritmo.
* [Remote Viewer]() - Máquina virtual en la cual se compilo y ejecuto el programa.

## Bibliotecas utilizadas

* ***pthread.h***: Biblioteca para el manejo de threads.
* ***unistd.h***: Biblioteca para funciones de sistema Unix.
* ***stdlib.h***: Biblioteca para funciones estándar.
* ***ncurses.h***: Biblioteca para el manejo de la pantalla.
* ***semaphore.h***: Biblioteca para.

## Descarga del programa 

* Para descargar el programa haga click en el siguiente [Link]()

## Ejecución del programa

* Debemos estar en el mismo directorio donde se encuentra el código fuente, para ello se debe escribir el siguiente comando, si es que el archivo se encuentra en el escritorio.
```
cd Desktop/carrera_caballos_2
```
* Luego para poder compilar el programa debemos usar el siguiente comando en la terminal, en el mismo directorio donde se encuentra el código fuente.
```
gcc -o tarea3_ejemplo tarea3_ejemplo.c -lpthread
```

* Para poder correr el programa como tal debemos pasarle unos parametros antes de ejecutarlo de la siguiente manera. Los parametros que son asignados son los siguientes:
* ***capacidad_almacen***:.
* ***rondas***: .
* ***demora_min_productor***:.
* **demora_max_productor***: .
* ***demora_min_consumidor***: .
* ***demora_max_consumidor***: .

```
./ tarea3_ejemplo 1 5 10 10 10 15
```

## Resultados
```
Caballo A: 2 vueltas - 60 metros
Caballo B: 2 vueltas - 60 metros
Caballo C: 2 vueltas - 60 metros
Caballo D: 2 vueltas - 60 metros
Caballo E: 2 vueltas - 60 metros
Caballo F: 2 vueltas - 60 metros
Caballo G: 2 vueltas - 60 metros

Totales: 14 vueltas - 420 metros

Carril 0|A|A-----------------------|2/2 vueltas
Carril 1|B|B-----------------------|2/2 vueltas
Carril 2|C|C-----------------------|2/2 vueltas
Carril 3|D|D-----------------------|2/2 vueltas
Carril 4|E|E-----------------------|2/2 vueltas
Carril 5|F|F-----------------------|2/2 vueltas
Carril 6|G|G-----------------------|2/2 vueltas

Largo de la pista: 30 metros
Numero de vueltas: 2
El ganador es: D
Carrera Terminada!!!!!!

```
## Autores
* Diego Araneda  - daranedah@ing.ucsc.cl
* Ignacio Valdebenito - ivaldebenito@ing.ucsc.cl
