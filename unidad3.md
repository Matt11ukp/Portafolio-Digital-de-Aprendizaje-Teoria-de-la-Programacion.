# Unidad 3

## Contenidos de la unidad 3

### Modularidad

Es la técnica de programación que consiste en dividir un problema grande y complejo en partes más pequeñas y manejables llamadas módulos o funciones. Esto permite que el código sea más legible, fácil de depurar y, sobre todo, reutilizable. [2]

#### 1. Paso de parámetros por valor

Consiste en enviar una copia del valor de una variable a la función. Cualquier cambio que se realice dentro de la función no afectará a la variable original, ya que la función trabaja con su propia copia local.

**Ejemplo de paso por valor:**

**Codigo en C:**

<div align="center">
  <img width="500" height="auto" alt="Captura de pantalla Codigo por Valor" src= "https://github.com/user-attachments/assets/1b21b91c-0e62-45d6-a856-77df898471cc" />
</div>

**Prueba en terminal:**

<div align="center">
  <img width="500" height="auto" alt="Captura de pantalla Codigo por Valor" src= "https://github.com/user-attachments/assets/19cc57cd-2307-4a16-b1f6-428e430a5621" />
</div>

#### 2. Paso de parámetros por referencia

En este caso, no se envía el valor, sino la dirección de memoria de la variable (usando punteros). Esto permite que la función acceda directamente al dato original y lo modifique de forma permanente.

**Ejemplo de paso por referencia:**

Programa que intercambia los valores de dos variables utilizando sus direcciones de memoria.

**Codigo en C:**

<div align="center">
  <img width="500" height="auto" alt="Captura de pantalla Codigo por Referencia" src= "https://github.com/user-attachments/assets/dafd2110-dec5-4c25-95a9-bd3695fbea5b" />
</div>

**Prueba en terminal:**

<div align="center">
  <img width="400" height="auto" alt="Diagrama de flujo Paso por Referencia" src= "https://github.com/user-attachments/assets/e3f0d8ee-33c6-40a6-83e2-3ff7dc13ea7d" />
</div>

---

### Arreglos (Arrays)

Un arreglo es una estructura de datos que permite almacenar una colección de elementos del mismo tipo bajo un solo nombre. Se accede a cada elemento mediante un índice numérico. [2]

#### 1. Arreglos Unidimensionales (Vectores)

Es una lista de elementos dispuestos en una sola dimensión. Es una fila de casilleros donde cada uno guarda un dato y tiene un número de posición que siempre empieza en 0.

**Ejemplo de arreglo unidimensional:**

**Codigo en C:**

<div align="center">
  <img width="500" height="auto" alt="Captura de pantalla Arreglo Unidimensional" src= "https://github.com/user-attachments/assets/48b65e1b-7b2c-4d2a-ad80-e20801d315ea" />
</div>

**Prueba en terminal:**

<div align="center">
  <img width="500" height="auto" alt="Captura de pantalla Codigo por Valor" src= "https://github.com/user-attachments/assets/6efb7c15-58e6-4a7c-a614-100a045fee3d" />
</div>

#### 2. Arreglos Multidimensionales (Matrices)

Son arreglos de dos o más dimensiones. El más común es el de dos dimensiones (matriz), organizado en filas y columnas.

**Ejemplo de arreglo bidimensional:**

**Codigo en C:**

<div align="center">
  <img width="500" height="auto" alt="Captura de pantalla Arreglo Bidimensional" src= "https://github.com/user-attachments/assets/b54e7b6b-e055-42b5-927f-86bb5a54bb58" />
</div>

**Prueba en terminal:**

<div align="center">
  <img width="500" height="auto" alt="Captura de pantalla Codigo por Valor" src= "https://github.com/user-attachments/assets/f01e5f8a-fc94-4e66-84c8-528045bc8cc6" />
</div>

#### 3. Tridimensionales

Son arreglos de tres dimensiones que se pueden visualizar lógicamente como un cubo de datos o un conjunto de matrices apiladas (páginas). Para acceder a un elemento específico, se requieren tres índices: el primero para la capa o página, el segundo para la fila y el tercero para la columna. [2]

**Ejemplo de arreglo bidimensional:**

**Codigo en C:**

<div align="center">
  <img width="500" height="auto" alt="Captura de pantalla Arreglo Bidimensional" src= "https://github.com/user-attachments/assets/2dd7c0e1-b426-435a-a5c3-e07a9c225bf0" />
</div>

**Prueba en terminal:**

<div align="center">
  <img width="500" height="auto" alt="Captura de pantalla Codigo por Valor" src= "https://github.com/user-attachments/assets/ecaa152d-f057-439e-98cc-4ad700481902" />
</div>

---

### Principales dificultades en la aplicación de los contenidos

El mayor reto fue comprender el concepto de punteros para el paso por referencia, la sintaxis de los asteriscos (`*`) y (`&`) me confundio al principio. 

### Reflexión crítica de los aprendizajes de la unidad

Esta unidad cambió mi forma de estructurar programas. Entendí que la modularidad no es solo ordenar el codigo, sino una forma de pensar: dividir para vencer. Aprender a usar arreglos me permitió dejar de crear variables individuales (`nota1`, `nota2`) para pasar a manejar variables similares en una sola. 

### Tareas entregadas

#### ACD

  ACD 1. Proyecto Académico Integrador (Proximo a entregarse)
  
  ACD 2. Control de aprendizaje sobre python (Realizado en el EVA)
  
  ACD 3. Control de aprendizaje sobre modularidad y estructura de datos (Realizado en el EVA)

#### APE

- APE 1. Construcción de funciones y procedimientos en un lenguaje de programación ----> [APE1](https://drive.google.com/drive/folders/1dNGzPZFYzlfbAznxiagkTNDJuo54yEWN?usp=sharing)

- APE 2. Implementación de funciones utilizando el paso de parámetros por valor y por referencia Archivo (Practica de laboratorio en riplet)

#### AA

- AA 1. Curso Fundamentos de Python 1. Computación UNL ----> [AA1](https://drive.google.com/drive/folders/1oW-5p5qvN2Y64vZSBM03ieXl8Sc9gmgx?usp=sharing)

-------------------

- **Ingrese aquí para volver a la página principal -->** [página principal](Index.md)
