# **ESTRUCTURAS DE DATOS**
### **Escuela Superior de Cómputo (ESCOM) - IPN**

Repositorio oficial que recopila el código fuente, prácticas y ejercicios desarrollados para la unidad de aprendizaje de **Estructuras de Datos**.

---

## **Descripción General**

Este repositorio contiene implementaciones completas en lenguaje C orientadas al estudio, análisis y aplicación de estructuras de datos fundamentales, gestión dinámica de memoria, algoritmos de ordenamiento, recursividad y modelado de grafos y árboles.

---

## **Estructura del Repositorio**

El proyecto se encuentra organizado en los siguientes directorios y módulos de código:

### **1. Algoritmos**
*   `quicksort.c` — Implementación del algoritmo de ordenamiento rápido por partición.

### **2. Apuntadores**
*   `apuntadores1.c` al `apuntadores20.c` — Serie progresiva de ejercicios sobre aritmética de apuntadores, asignación dinámica de memoria y referencias en C.

### **3. Estructuras de Datos**
*   **Pilas:**
    *   `1-pila1.c` y `2-pila2.c` — Implementaciones base de pilas.
    *   `5.- PilaCabeceraSimple.c` / `16.-PilaNoCabeceraSimple.c` — Variantes de pilas simples.
    *   `10.-PilaCabeceraDoble.c` / `13.PilaCabeceraDoble.c` — Pilas con cabecera doble.
*   **Colas:**
    *   `4-cola.c` — Implementación lineal básica.
    *   `6-colaCiclica.c` — Cola con manejo cíclico.
    *   `7.- ColaCabeceraSimple.c` / `11.- ColaNoCabeceraSimple.c` — Colas simples con y sin cabecera.
    *   `12.-colaCabeceraDoble.c` / `19.- ColaCabeceraDoble.c` — Colas con cabecera doble.
    *   `27.-colacircularElazada.c` — Cola circular enlazada.
    *   `28.-colaEnlazada2.c` — Cola enlazada alternativa.
*   **Listas Enlazadas:**
    *   `3- Lista con arreglo y clave - dato.c` — Lista basada en arreglos con pares clave-dato.
    *   `8-listaenlasada1.c` al `9-listaenlasada2.c` — Primeras aproximaciones a listas enlazadas.
    *   `14-listaenlazada3.C` al `18-listaenlazada6.c` — Operaciones avanzadas y variantes de listas.
    *   `24.-cadenaToListv1.c` y `25.-cadenaToListv2.c` — Conversión y manipulación de cadenas hacia estructuras de listas.
    *   `26.-sumارPolinomio.c` — Aplicación de listas enlazadas para la suma de polinomios.
*   **Tablas Hash:**
    *   `20.-hashV1.c` al `23.-hashV4.c` — Versiones estándar de tablas hash y manejo de colisiones.
    *   `29.-hashComplejoV1.c` al `32.-hashComplejoV4.c` — Implementaciones avanzadas y complejas de esquemas hash.

### **4. Grafos y Árboles**
*   `arbol.c`, `arbol2.c`, `arbol3.c` — Implementación y recorridos de estructuras de árboles binarios.

### **5. Recursividad**
*   `1-factorial.c` — Cálculo recursivo del factorial.
*   `2-exponente.c` — Potencia por recursividad.
*   `3-multiplicacion.c` — Multiplicación mediante sumas sucesivas recursivas.
*   `4-suma.c` — Sumatoria recursiva.
*   `5-longitudCadena.c` — Cálculo de longitud de cadenas sin funciones de biblioteca.
*   `6-mcd.c` — Algoritmo de Euclides para el Máximo Común Divisor.
*   `7-reverse.c` — Inversión recursiva de datos.

---

## **Requisitos de Compilación**

*   Compilador de C compatible con el estándar C99 o superior (GCC, Clang o MSVC).
*   Entorno de ejecución preferente en sistemas tipo UNIX (Linux / macOS) o terminal bash en Windows (MinGW).

---

## **Instrucciones de Uso**

Para compilar y ejecutar cualquier archivo de forma individual mediante la terminal, ejecute la siguiente instrucción:

```bash
gcc -o programa ruta/del/archivo.c
./programa
```