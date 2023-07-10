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
* ***semaphore.h***: Biblioteca que trabaja con semáforos, que coordinan el acceso a recursos compartidos.

## Descarga del programa 

* Para descargar el programa haga click en el siguiente [Link](https://github.com/DiegoAraneda98/Tarea-3-Sistemas-Operativos/archive/refs/heads/main.zip)

## Ejecución del programa

* Para poder compilar el programa debemos usar el siguiente comando en la terminal, en el mismo directorio donde se encuentra el código fuente.
```
gcc -o tarea3_ejemplo tarea3_ejemplo.c -lpthread
```

* Para poder correr el programa como tal debemos pasarle unos parametros antes de ejecutarlo de la siguiente manera. Los parametros que son asignados son los siguientes:
 
```
./caja_registradora tiempo_min_cliente tiempo_max_cliente tiempo_min_caja tiempo_max_caja
```

```
./caja_registradora 0 10 5 10
```

## Resultados
```
CAJA 0 ; CLIENTES: 1 ; PRODUCTOS: 3 ; ALMACEN: 6
CAJA 0 ; INICIO RONDA: 0
CAJA 1 ; CLIENTES: 8 ; PRODUCTOS: 2 ; ALMACEN: 6
CAJA 1 ; INICIO RONDA: 0
CAJA 0 ; RONDA: 0 ; Indice almacen 0 produce 1
CAJA 1 ; RONDA: 0 ; Indice almacen 0 produce 1
CAJA 0 ; RONDA: 0 ; Indice almacen 0 consume 1
CAJA 0 ; RONDA: 0 ; Indice almacen 1 produce 2
CAJA 1 ; RONDA: 0 ; Indice almacen 1 produce 2
CAJA 1 ; RONDA: 0 ; Indice almacen 0 consume 1
CAJA 0 ; RONDA: 0 ; Indice almacen 2 produce 3
CAJA 0 ; RONDA: 0 ; Indice almacen 1 consume 2
CAJA 1 ; RONDA: 0 ; Indice almacen 1 consume 2
--------------------
CAJA 1 ; CLIENTES: 8 ; PRODUCTOS: 8 ; ALMACEN: 6
--------------------
CAJA 1 ; INICIO RONDA: 1
CAJA 1 ; RONDA: 1 ; Indice almacen 0 produce 3
CAJA 0 ; RONDA: 0 ; Indice almacen 2 consume 3
--------------------
--------------------
CAJA 1 ; RONDA: 1 ; Indice almacen 0 consume 3
CAJA 1 ; RONDA: 1 ; Indice almacen 1 produce 4
CAJA 1 ; RONDA: 1 ; Indice almacen 1 consume 4
CAJA 1 ; RONDA: 1 ; Indice almacen 2 produce 5
CAJA 1 ; RONDA: 1 ; Indice almacen 3 produce 6
CAJA 1 ; RONDA: 1 ; Indice almacen 2 consume 5
CAJA 1 ; RONDA: 1 ; Indice almacen 3 consume 6
CAJA 1 ; RONDA: 1 ; Indice almacen 4 produce 7
CAJA 1 ; RONDA: 1 ; Indice almacen 5 produce 8
CAJA 1 ; RONDA: 1 ; Indice almacen 4 consume 7
CAJA 1 ; RONDA: 1 ; Indice almacen 6 produce 9
CAJA 1 ; RONDA: 1 ; Indice almacen 7 produce 10
CAJA 1 ; RONDA: 1 ; Indice almacen 5 consume 8
CAJA 1 ; RONDA: 1 ; Indice almacen 6 consume 9
CAJA 1 ; RONDA: 1 ; Indice almacen 7 consume 10
--------------------
CAJA 1 ; CLIENTES: 8 ; PRODUCTOS: 5 ; ALMACEN: 6
--------------------
CAJA 1 ; INICIO RONDA: 2
CAJA 1 ; RONDA: 2 ; Indice almacen 0 produce 11
CAJA 1 ; RONDA: 2 ; Indice almacen 1 produce 12
CAJA 1 ; RONDA: 2 ; Indice almacen 0 consume 11
CAJA 1 ; RONDA: 2 ; Indice almacen 2 produce 13
CAJA 1 ; RONDA: 2 ; Indice almacen 1 consume 12
CAJA 1 ; RONDA: 2 ; Indice almacen 3 produce 14
CAJA 1 ; RONDA: 2 ; Indice almacen 4 produce 15
CAJA 1 ; RONDA: 2 ; Indice almacen 2 consume 13
CAJA 1 ; RONDA: 2 ; Indice almacen 3 consume 14
CAJA 1 ; RONDA: 2 ; Indice almacen 4 consume 15
--------------------
CAJA 1 ; CLIENTES: 8 ; PRODUCTOS: 3 ; ALMACEN: 6
--------------------
CAJA 1 ; INICIO RONDA: 3
CAJA 1 ; RONDA: 3 ; Indice almacen 0 produce 16
CAJA 1 ; RONDA: 3 ; Indice almacen 1 produce 17
CAJA 1 ; RONDA: 3 ; Indice almacen 0 consume 16
CAJA 1 ; RONDA: 3 ; Indice almacen 2 produce 18
CAJA 1 ; RONDA: 3 ; Indice almacen 1 consume 17
CAJA 1 ; RONDA: 3 ; Indice almacen 2 consume 18
--------------------
CAJA 1 ; CLIENTES: 8 ; PRODUCTOS: 9 ; ALMACEN: 6
--------------------
CAJA 1 ; INICIO RONDA: 4
CAJA 1 ; RONDA: 4 ; Indice almacen 0 produce 19
CAJA 1 ; RONDA: 4 ; Indice almacen 0 consume 19
CAJA 1 ; RONDA: 4 ; Indice almacen 1 produce 20
CAJA 1 ; RONDA: 4 ; Indice almacen 1 consume 20
CAJA 1 ; RONDA: 4 ; Indice almacen 2 produce 21
CAJA 1 ; RONDA: 4 ; Indice almacen 3 produce 22
CAJA 1 ; RONDA: 4 ; Indice almacen 2 consume 21
CAJA 1 ; RONDA: 4 ; Indice almacen 3 consume 22
CAJA 1 ; RONDA: 4 ; Indice almacen 4 produce 23
CAJA 1 ; RONDA: 4 ; Indice almacen 5 produce 24
CAJA 1 ; RONDA: 4 ; Indice almacen 4 consume 23
CAJA 1 ; RONDA: 4 ; Indice almacen 6 produce 25
CAJA 1 ; RONDA: 4 ; Indice almacen 5 consume 24
CAJA 1 ; RONDA: 4 ; Indice almacen 7 produce 26
CAJA 1 ; RONDA: 4 ; Indice almacen 6 consume 25
CAJA 1 ; RONDA: 4 ; Indice almacen 8 produce 27
CAJA 1 ; RONDA: 4 ; Indice almacen 7 consume 26
CAJA 1 ; RONDA: 4 ; Indice almacen 8 consume 27
--------------------
CAJA 1 ; CLIENTES: 8 ; PRODUCTOS: 14 ; ALMACEN: 6
--------------------
CAJA 1 ; INICIO RONDA: 5
CAJA 1 ; RONDA: 5 ; Indice almacen 0 produce 28
CAJA 1 ; RONDA: 5 ; Indice almacen 1 produce 29
CAJA 1 ; RONDA: 5 ; Indice almacen 2 produce 30
CAJA 1 ; RONDA: 5 ; Indice almacen 0 consume 28
CAJA 1 ; RONDA: 5 ; Indice almacen 3 produce 31
CAJA 1 ; RONDA: 5 ; Indice almacen 1 consume 29
CAJA 1 ; RONDA: 5 ; Indice almacen 4 produce 32
CAJA 1 ; RONDA: 5 ; Indice almacen 2 consume 30
CAJA 1 ; RONDA: 5 ; Indice almacen 5 produce 33
CAJA 1 ; RONDA: 5 ; Indice almacen 3 consume 31
CAJA 1 ; RONDA: 5 ; Indice almacen 6 produce 34
CAJA 1 ; RONDA: 5 ; Indice almacen 4 consume 32
CAJA 1 ; RONDA: 5 ; Indice almacen 7 produce 35
CAJA 1 ; RONDA: 5 ; Indice almacen 8 produce 36
CAJA 1 ; RONDA: 5 ; Indice almacen 5 consume 33
CAJA 1 ; RONDA: 5 ; Indice almacen 9 produce 37
CAJA 1 ; RONDA: 5 ; Indice almacen 10 produce 38
CAJA 1 ; RONDA: 5 ; Indice almacen 6 consume 34
CAJA 1 ; RONDA: 5 ; Indice almacen 11 produce 39
CAJA 1 ; RONDA: 5 ; Indice almacen 7 consume 35
CAJA 1 ; RONDA: 5 ; Indice almacen 12 produce 40
CAJA 1 ; RONDA: 5 ; Indice almacen 13 produce 41
CAJA 1 ; RONDA: 5 ; Indice almacen 8 consume 36
CAJA 1 ; RONDA: 5 ; Indice almacen 9 consume 37
CAJA 1 ; RONDA: 5 ; Indice almacen 10 consume 38
CAJA 1 ; RONDA: 5 ; Indice almacen 11 consume 39
CAJA 1 ; RONDA: 5 ; Indice almacen 12 consume 40
CAJA 1 ; RONDA: 5 ; Indice almacen 13 consume 41
--------------------
CAJA 1 ; CLIENTES: 8 ; PRODUCTOS: 2 ; ALMACEN: 6
--------------------
CAJA 1 ; INICIO RONDA: 6
CAJA 1 ; RONDA: 6 ; Indice almacen 0 produce 42
CAJA 1 ; RONDA: 6 ; Indice almacen 1 produce 43
CAJA 1 ; RONDA: 6 ; Indice almacen 0 consume 42
CAJA 1 ; RONDA: 6 ; Indice almacen 1 consume 43
--------------------
CAJA 1 ; CLIENTES: 8 ; PRODUCTOS: 14 ; ALMACEN: 6
--------------------
CAJA 1 ; INICIO RONDA: 7
CAJA 1 ; RONDA: 7 ; Indice almacen 0 produce 44
CAJA 1 ; RONDA: 7 ; Indice almacen 1 produce 45
CAJA 1 ; RONDA: 7 ; Indice almacen 2 produce 46
CAJA 1 ; RONDA: 7 ; Indice almacen 0 consume 44
CAJA 1 ; RONDA: 7 ; Indice almacen 3 produce 47
CAJA 1 ; RONDA: 7 ; Indice almacen 1 consume 45
CAJA 1 ; RONDA: 7 ; Indice almacen 2 consume 46
CAJA 1 ; RONDA: 7 ; Indice almacen 4 produce 48
CAJA 1 ; RONDA: 7 ; Indice almacen 5 produce 49
CAJA 1 ; RONDA: 7 ; Indice almacen 3 consume 47
CAJA 1 ; RONDA: 7 ; Indice almacen 6 produce 50
CAJA 1 ; RONDA: 7 ; Indice almacen 7 produce 51
CAJA 1 ; RONDA: 7 ; Indice almacen 4 consume 48
CAJA 1 ; RONDA: 7 ; Indice almacen 8 produce 52
CAJA 1 ; RONDA: 7 ; Indice almacen 5 consume 49
CAJA 1 ; RONDA: 7 ; Indice almacen 6 consume 50
CAJA 1 ; RONDA: 7 ; Indice almacen 9 produce 53
CAJA 1 ; RONDA: 7 ; Indice almacen 7 consume 51
CAJA 1 ; RONDA: 7 ; Indice almacen 10 produce 54
CAJA 1 ; RONDA: 7 ; Indice almacen 11 produce 55
CAJA 1 ; RONDA: 7 ; Indice almacen 8 consume 52
CAJA 1 ; RONDA: 7 ; Indice almacen 12 produce 56
CAJA 1 ; RONDA: 7 ; Indice almacen 13 produce 57
CAJA 1 ; RONDA: 7 ; Indice almacen 9 consume 53
CAJA 1 ; RONDA: 7 ; Indice almacen 10 consume 54
CAJA 1 ; RONDA: 7 ; Indice almacen 11 consume 55
CAJA 1 ; RONDA: 7 ; Indice almacen 12 consume 56
CAJA 1 ; RONDA: 7 ; Indice almacen 13 consume 57
--------------------
--------------------
Tiempo de ejecución: 0.459578723s

```
## Autores
* Diego Araneda  - daranedah@ing.ucsc.cl
* Ignacio Valdebenito - ivaldebenito@ing.ucsc.cl
