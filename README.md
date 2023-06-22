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
Ejemplo resultado

```
## Autores
* Diego Araneda  - daranedah@ing.ucsc.cl
* Ignacio Valdebenito - ivaldebenito@ing.ucsc.cl
