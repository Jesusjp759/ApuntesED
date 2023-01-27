## **Optimización**

### 1) ¿Qué se entiende por hediondez del código? Pon al menos 5 ejemplos.

Son aquellas características del código que lo hacen difícil de entender, modificar o mantener. Indica deficiencias en el diseño y puede ralentizar la producción o aumentar el riesgo de errores. 5 ejemplos pueden ser:

- Falta de comentarios para entender el funcionamiento del código.
- Nombres de variables o funciones confusos y poco intuitivos.
- Código duplicado, es decir, un bloque de código que se repite varias veces a lo largo del proyecto.
- Código no estructurado, escrito sin una estructura lógica.
- Difícil lectura del código, ya sea por un uso excesivo de abreviaciones, falta de espacios, uso inadecuado de mayúsculas, etc.

### 2) ¿Qué tipo de herramienta utilizamos para hacer análisis estático del código?

- Linter: Un linter es una herramienta que analiza el código fuente en busca de errores sintácticos y de estilo. Los linters suelen tener reglas configurables para señalar problemas como nombres de variables no descriptivos, falta de comentarios, indentación incorrecta, entre otros.
- Mediante sitios web para inspección de código (Continuous Inspection) como Scrutinizer o SonarQube

### 3) ¿Qué sitios web nos permiten hacer análisis estático del código o Continuous Inspection?

- Scrutinizer: Es especialmente útil para proyectos de software de código abierto.
- SonarQube: Es una plataforma de análisis estático de código que puede ser utilizada para detectar problemas de calidad, seguridad y rendimiento en el código. Ofrece una interfaz web fácil de usar y puede ser integrada con varias herramientas de control de versiones populares, como Git y SVN.

### 4) Realiza análisis estático de código para las clases del proyecto miapp. Consulta el siguiente enlace: análisis estático con FindBugs
![imagen](https://raw.githubusercontent.com/Jesusjp759/Apuntes_ED/main/Imagenes/findbugs.png)

### 5) Indica al menos un code smell relevante de cada clase. Explica cómo podría solucionarse.

- Dinámico: Bucle infinito, se podría solucionar implementando una condición de salida para el bucle.
- Estático: Clase con demasiados métodos, esto se podría solucionar creando subclases para dividir el número de parámetros.

### 6) ¿Qué es la refactorización?

Es el proceso de cambiar la estructura interna del código sin cambiar su comportamiento externo.

### 7) ¿Qué técnicas se utilizan a menudo a la hora de refactorizar?

- Pruebas unitarias para asegurar que no se rompen las funcionalidades existentes.
- Renombrado, para mejorar la legibilidad del código.
- Extraer método, para eliminar fragmentos repetitivos y convertirlos en métodos independientes.
- Patrón de diseño, para mejorar la estructura del código.
