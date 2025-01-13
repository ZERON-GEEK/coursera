## Explorar la sintaxis de Python

Python es un lenguaje de programación flexible que se utiliza en una amplia gama de campos, como el desarrollo de software, el aprendizaje automático y el análisis de datos. Python es uno de los lenguajes de programación más populares para los profesionales de los datos, por lo que familiarizarse con su sintaxis y semántica fundamentales será útil para su futura carrera. En esta lectura, aprenderás sobre la sintaxis y la semántica de Python, así como dónde encontrar recursos para ampliar tu aprendizaje.
### El lenguaje de Python
Las personas utilizamos el lenguaje para comunicarnos y darnos instrucciones. Los ordenadores hacen lo mismo, excepto que utilizan lenguajes como Python, C++ y Java. Así que, para comunicar instrucciones al ordenador, los programadores necesitan organizar ideas y conceptos en un lenguaje que éste entienda.

La sintaxis de Python incluye palabras que representan objetos y órdenes, así como signos de puntuación que dan a las palabras estructura, jerarquía y contexto. Juntas, las palabras y la puntuación comunican ideas y procesos, lo que se conoce como semántica. La semántica es el significado que transmite la sintaxis. La mejor manera de aprender sintaxis y semántica es a través de la exposición. Practica la codificación y familiarízate y siéntete cómodo leyendo el código de otras personas. Además, hay algunas convenciones generales que los profesionales utilizan para ayudar a mantener la uniformidad estilística dentro del lenguaje.

Las lenguas de codificación se parecen a las lenguas habladas en que tienen una forma de clasificar las palabras según su función. Por ejemplo, las frases en inglés se componen de sustantivos, verbos, preposiciones, etc. Éstos son algunos de los conceptos básicos:

* **Variables:** Representan datos almacenados como cadenas, tuplas, diccionarios, listas y objetos (nota: en futuras lecturas se explicarán estas categorías)

* **Palabras clave:** Palabras especiales que se reservan para fines específicos y que sólo se pueden utilizar para esos fines
```
1   in
2   not
3   or
4   for
5   while
6   return
```
* **Operadores:** Símbolos que realizan operaciones con objetos y valores

```
1   +
2   - 
3   * 
4   / 
5   ** 
6   % 
7   // 
8   > 
9   < 
10  ==
```
* **Expresiones:** Combinación de números, símbolos y variables para calcular y devolver un resultado tras la evaluación

* **Funciones:** Un grupo de sentencias relacionadas para realizar una tarea y devolver un valor


```python
def to_celsius(x):
   '''Convert Fahrenheit to Celsius'''
   return (x-32) * 5/9


to_celsius(75)
```
* **Sentencias condicionales:** Secciones de código que dirigen la ejecución del programa basándose en condiciones especificadas
```python
number = -4


if number > 0:
   print('Number is positive.')
elif number == 0:
   print('Number is zero.')
else:
   print('Number is negative.')
```

ASÍ COMO seguramente descubrirás, Python genera errores de sintaxis para palabras clave y sintaxis utilizadas incorrectamente.

	Ejemplo: 

```python 
print(This will throw an error because I didn’t make it a string.)
```
## Reglas y convenciones de nomenclatura
Al asignar nombres a los objetos, los programadores se adhieren a un conjunto de reglas y convenciones que ayudan a estandarizar el código y hacerlo más accesible para todos. Éstas son algunas de las reglas y convenciones de nomenclatura que debes conocer:

* Los nombres no pueden contener espacios.
* Los nombres pueden ser una mezcla de caracteres en mayúsculas y minúsculas.
* Los nombres no pueden empezar por un número, pero pueden contener números después del primer carácter.
* Los nombres de variables y funciones deben escribirse en snake_case, lo que significa que todas las letras son minúsculas y las palabras se separan con un guión bajo.
* Los nombres descriptivos son mejores que las abreviaturas crípticas porque ayudan a otros programadores (y a ti) a leer e interpretar tu código. Por ejemplo, nombre_alumno es mejor que sn. Puede parecer excesivo cuando lo escribes, pero cuando vuelvas a tu código lo encontrarás mucho más fácil de entender.

Tim Peters, programador de Python, escribió este ya famoso "poema" de principios rectores para la codificación en Python:

**El Zen de Python**
Lo bonito es mejor que lo feo.

Lo explícito es mejor que lo implícito.

Lo simple es mejor que lo complejo.

Lo complejo es mejor que lo complicado.

Plano es mejor que anidado.

Esparcido es mejor que denso.

La legibilidad cuenta.

Los casos especiales no son tan especiales como para romper las reglas.

Aunque la practicidad gana a la pureza.

Los errores nunca deben pasar en silencio.

A menos que se silencien explícitamente.

Ante la ambigüedad, rechaza la tentación de adivinar.

Debe haber una -y preferiblemente sólo una- forma obvia de hacerlo.

Aunque esa manera puede no ser obvia al principio, a menos que seas holandés.

Ahora es mejor que nunca.

Aunque a menudo "nunca" es mejor que "ahora mismo".

Si la aplicación es difícil de explicar, es una mala idea.

Si la implementación es fácil de explicar, puede ser una buena idea.

Los espacios de nombres son una gran idea: ¡hagamos más!


Finalmente, es útil marcar la 
Guía de estilo PEP 8 para Python
 para poder consultarla cuando sea necesario. Esta lectura tiene un alcance limitado, y PEP 8 es un recurso más exhaustivo para asuntos relacionados con el estilo. PEP son las siglas de Python Enhancement Proposals (Propuestas de Mejora de Python). Se trata de un catálogo de formas de mejorar o estandarizar Python como lenguaje. Dado que Python es código abierto, PEP ofrece un marco para guiar a los desarrolladores y crear consenso en torno a las ideas. Es un recurso útil y fiable.

### Puntos clave
La sintaxis y la semántica son los elementos que dan forma y significado a un lenguaje, incluido Python. Una gran parte del aprendizaje de un nuevo lenguaje consiste en familiarizarse con su sintaxis y su semántica. Gran parte de esto viene a través de la exposición y la práctica, pero hay algunos principios rectores y recursos que pueden ayudarte en el camino. Si aprendes las reglas para nombrar objetos y construyes un banco de recursos que puedas consultar como guía, seguramente progresarás como aprendiz de Python. A medida que te familiarices con Python, podrás comunicarte más eficientemente con las computadoras y hacer más con tus herramientas de Análisis de datos

## Recursos para obtener más información
Aquí tienes algunos recursos útiles que te ayudarán a familiarizarte con Python:

* Biblioteca de referencia de Python

  * Tipos de datos incorporados

  * Funciones integradas

* Operadores de Python

