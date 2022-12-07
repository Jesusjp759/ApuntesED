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
- datos.c
//-------------
// datos.c
//-------------

char *mensaje="Hola a todos y todas";
int  num1 = 8;
int  num2 = 10; 

- suma.c
//-------------
// suma.c
//-------------

int suma (int a, int b) {
  return a + b;
}

- main.c
//-------------
// main.c
//-------------

/#include <stdio.h>

int suma (int a, int b);

extern char *mensaje;
extern int  num1, num2;

int main(){
  printf("%s\n", mensaje);
  printf("%d\n", suma (num1, num2) );
  return 0;
}

