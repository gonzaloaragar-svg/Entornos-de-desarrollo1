1. Explicación de los conceptos básicos

Código fuente: el texto que escribimos nosotros al programar (Python, C...).

Código objeto: una traducción a medias, el ordenador casi lo entiende pero le faltan detalles para funcionar.

Código ejecutable: el archivo final listo para usarse, como un típico .exe.

Fases de un programa (ejemplo: int suma = a + b;):

Análisis léxico: revisa que el término "int" exista en el lenguaje.

Análisis sintáctico: mira la gramática, por ejemplo, que no falte el punto y coma.

Análisis semántico: revisa la coherencia comprobando que "a" y "b" sean números y no letras para poder sumarlos.

Generación de código intermedio: crea una versión simplificada de esa suma.

Optimización: quita cosas redundantes para que el programa vaya más rápido.

Generación de código final: lo pasa todo a ceros y unos para el procesador.

2. Clasificación de lenguajes de programación
Por nivel de abstracción:

Bajo (Ensamblador): Directo al procesador. Rapidísimo pero muy difícil de programar y leer.

Medio (C, C++): Fáciles de entender, pero te permiten tocar cosas delicadas como la memoria del sistema.

Alto (Python, Javascript): Muy cómodos e intuitivos, te olvidas de cómo funciona la máquina por dentro.

Por paradigma:

Imperativo (C, Java): le das al ordenador el paso a paso de lo que tiene que hacer.

Declarativo (SQL, Haskell): le pides el resultado final sin decirle cómo llegar a él.
3. Identificación de paradigmas a partir de ejemplos
Fragmento 1: Imperativo. Detalla exactamente el proceso de recorrer la lista y sumar.

Fragmento 2: Declarativo. Pide directamente los empleados mayores de 30 sin explicar el algoritmo de búsqueda.

Fragmento 3: Declarativo. Solo define matemáticamente el factorial, sin dar instrucciones paso a paso.

Fragmento 4: Imperativo. Vuelve a centrarse en el proceso exacto de comprobar uno por uno.