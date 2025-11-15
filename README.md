# Taller – Evaluación de Rendimiento (Paralelismo con fork, POSIX Threads y OpenMP)
Este repositorio contiene el desarrollo del taller de evaluación de rendimiento, donde se trabajó el algoritmo clásico de multiplicación de matrices para comparar varias formas de paralelismo. Las implementaciones se realizaron usando procesos con fork(), hilos POSIX (pthread) y dos variantes con OpenMP, con el fin de observar cómo cambia el tiempo de ejecución según el tipo de paralelización y el tamaño de las matrices.


---

## 1. Estructura del repositorio

```text
Fork/
    main.c
    funciones.c
    funciones.h
    Makefile

Pthreads/
    main.c
    funciones.c
    funciones.h
    Makefile

OMP_Simple/
    main.c
    funciones.c
    funciones.h
    Makefile

OMP_Filas/
    main.c
    funciones.c
    funciones.h
    Makefile
