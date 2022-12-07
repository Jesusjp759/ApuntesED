## **Herramientas de desarrollo**

### 1) Ejecuta el programa "Hola mundo" en los siguientes lenguajes: 

   - bash
   - python
   - php
   - javascript (nodejs)
   - c
   - c++
   - java
   - ruby
   - go
   - rust
   - lisp
   - ensamblador (nasm)

![imagen](https://raw.githubusercontent.com/Jesusjp759/Apuntes_ED/main/Imagenes/holabash.png)
![imagen](https://raw.githubusercontent.com/Jesusjp759/Apuntes_ED/main/Imagenes/holajava.png)
![imagen](https://raw.githubusercontent.com/Jesusjp759/Apuntes_ED/main/Imagenes/holajs.png)
![imagen](https://raw.githubusercontent.com/Jesusjp759/Apuntes_ED/main/Imagenes/holapython.png)

Los paquetes a instalar en Ubuntu son: python, php, nodejs, gcc, g++, openjdk-8-jdk, ruby, golang, rustc , clisp y nasm.

El código fuente para distintos lenguajes de programación está disponible en: https://es.wikipedia.org/wiki/Anexo:Ejemplos_de_implementaci%C3%B3n_del_%C2%ABHola_mundo%C2%BB

Instrucciones en https://github.com/jamj2000/DAW1-ED-HolaMundo.

### 2) Para cada uno de los lenguajes anteriores, indica el proceso realizado para conseguir ejecutar el código: ¿compilación o interpretación?

   - bash: Interpretación
   - python: Interpretación
   - php: Interpretación
   - javascript (nodejs): Interpretación
   - c: Compilación
   - c++: Compilación
   - java: Compilación
   - ruby: Interpretación
   - go: Compilación
   - rust: Compilación
   - lisp: Interpretación
   - ensamblador (nasm): Compilación

### 3) Para cada uno de los lenguajes anteriores, indica el nombre del compilador o interprete utilizado en GNU/Linux.
   
   - bash: Shell
   - python: CPython
   - php: Netbeans
   - javascript (nodejs): Navegador web
   - c: GCC
   - c++: GCC
   - java: GNU Compiler
   - ruby: JIT
   - go: gccgo 
   - rust: Rustc
   - lisp: GCL
   - ensamblador (nasm): GNU Assembler

### 4) Investiga y averigua que extensión tienen los archivos de código fuente de los siguientes lenguajes:

   - bash: .sh
   - python: .py
   - php: .php
   - javascript (nodejs): .js
   - c: .c
   - c++: .cpp
   - java: .java
   - ruby: .rb
   - go: .go
   - rust: .rs
   - lisp: .lisp
   - ensamblador (nasm): .asm

### 6) ¿Qué extensión tienen los archivos de código objeto?
Tienen la extensión .obj, que son archivos intermedios generados por el compilador.

### 7) Lenguaje C. Código en varios archivos. Obtener el código objeto a partir del código fuente de los 3 archivos siguientes:
Escribimos en la consola el comando "gcc -c main.c datos.c suma.c" y si después escribimos el comando "ls" para comprobar los archivos, además de los del enunciado, nos devuelve main.o datos.o y suma.o

### 8) Lenguaje C. Código en varios archivos. Obtener el código binario ejecutable a partir del código objeto de los 3 archivos anteriores:
Para obtener el código binario ejecutable usaremos el comando "gcc -o ejemplo main.o datos.o suma.o" y nos devuelve un nuevo archivo llamado ejemplo con el código binario ejecutable. 

## BIBLIOTECAS

### 11) Bibliotecas. Define que se entiende por biblioteca o librería y los tipos que existen.
Es un conjunto de implementaciones funcionales codificadas en un lenguaje de programación. Existen los siguientes tipos:
- Bibliotecas estáticas
- Bibliotecas dinámicas
- Bibliotecas remotas

### 12) Bibliotecas. ¿Qué tipo es el más utilizado actualmente? ¿Por qué?
Las bibliotecas dinámicas porque la carga dinámica permite al sistema operativo aplicar algoritmos que mejoren el rendimiento del sistema cuando se carguen estas bibliotecas. Además, al estar compartidas, basta con mantener una copia en memoria para todos los programas que la utilicen. En resumen, facilitan la gestión y el aprovechamiento de la memoria del sistema.

