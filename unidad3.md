# Unidad 2

## Contenidos de la unidad 2

### Modularidad

Es la técnica de programación que consiste en dividir un problema grande y complejo en partes más pequeñas y manejables llamadas módulos o funciones. Esto permite que el código sea más legible, fácil de depurar y, sobre todo, reutilizable. [2]

#### 1. Paso de parámetros por valor

Consiste en enviar una copia del valor de una variable a la función. Cualquier cambio que se realice dentro de la función no afectará a la variable original, ya que la función trabaja con su propia copia local.

**Ejemplo de paso por valor:**

Programa que intenta incrementar un precio, pero al ser por valor, el precio original en el main no cambia.

**Codigo en C:**

<div align="center">
  <img width="500" height="auto" alt="Captura de pantalla Codigo por Valor" src="PON_AQUI_TU_ENLACE_A_GITHUB" />
</div>

**Diagrama de flujo:**

<div align="center">
  <img width="400" height="auto" alt="Diagrama de flujo Paso por Valor" src="PON_AQUI_TU_ENLACE_A_GITHUB" />
</div>

#### 2. Paso de parámetros por referencia

En este caso, no se envía el valor, sino la dirección de memoria de la variable (usando punteros). Esto permite que la función acceda directamente al dato original y lo modifique de forma permanente.

**Ejemplo de paso por referencia:**

Programa que intercambia los valores de dos variables utilizando sus direcciones de memoria.

**Codigo en C:**

<div align="center">
  <img width="500" height="auto" alt="Captura de pantalla Codigo por Referencia" src="PON_AQUI_TU_ENLACE_A_GITHUB" />
</div>

**Diagrama de flujo:**

<div align="center">
  <img width="400" height="auto" alt="Diagrama de flujo Paso por Referencia" src="PON_AQUI_TU_ENLACE_A_GITHUB" />
</div>

---

### Arreglos (Arrays)

Un arreglo es una estructura de datos que permite almacenar una colección de elementos del mismo tipo bajo un solo nombre. Se accede a cada elemento mediante un índice numérico. [2]



#### 1. Arreglos Unidimensionales (Vectores)

Es una lista de elementos dispuestos en una sola dimensión. Imagina una fila de casilleros donde cada uno guarda un dato y tiene un número de posición que siempre empieza en 0.

**Ejemplo de arreglo unidimensional:**

Programa que solicita 5 temperaturas y calcula su promedio.

**Codigo en C:**

<div align="center">
  <img width="500" height="auto" alt="Captura de pantalla Arreglo Unidimensional" src="PON_AQUI_TU_ENLACE_A_GITHUB" />
</div>

#### 2. Arreglos Multidimensionales (Matrices)

Son arreglos de dos o más dimensiones. El más común es el de dos dimensiones (matriz), organizado en filas y columnas, similar a una tabla de Excel o un tablero de ajedrez.

**Ejemplo de arreglo bidimensional:**

Programa que llena una matriz de 3x3 con números enteros y muestra la suma de su diagonal principal.

**Codigo en C:**

<div align="center">
  <img width="500" height="auto" alt="Captura de pantalla Arreglo Bidimensional" src="PON_AQUI_TU_ENLACE_A_GITHUB" />
</div>

---

### Principales dificultades en la aplicación de los contenidos

El mayor reto fue comprender el concepto de punteros para el paso por referencia; la sintaxis de los asteriscos (`*`) y ampersands (`&`) suele ser confusa al principio. También tuve dificultades con los arreglos multidimensionales, específicamente al gestionar los ciclos anidados (for dentro de for) para recorrer correctamente las filas y columnas sin exceder los límites del índice.

### Reflexión crítica de los aprendizajes de la unidad

Esta unidad cambió mi forma de estructurar programas. Entendí que la modularidad no es solo "ordenar", sino una forma de pensar: dividir para vencer. Aprender a usar arreglos me permitió dejar de crear variables individuales (`nota1`, `nota2`, etc.) para pasar a manejar conjuntos de datos de forma masiva y eficiente. Me di cuenta de que un buen programador no es el que escribe el código más largo, sino el que sabe reutilizar sus funciones para que el código sea limpio y profesional.

### Tareas entregadas

#### ACD

- Control de aprendizaje sobre funciones y estructuras de datos realizado en el EVA.

#### APE

- Enlace en Google Drive con los APE de la unidad 2 (Modularidad y Arreglos) ----> [APE](https://drive.google.com/tu_enlace_aqui)

#### AA

- Enlace en Google Drive con los AA de la unidad 2 (Ejercicios prácticos) ----> [AA](https://drive.google.com/tu_enlace_aqui)

-------------------

- **Ingrese aquí para volver a la página principal -->** [página principal](Index.md)
