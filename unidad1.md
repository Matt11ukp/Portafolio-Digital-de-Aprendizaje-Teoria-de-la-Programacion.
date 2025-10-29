# Unidad 1

## Contenidos de la unidad 1

### Algoritmos, pseudocodigo, y diagramas de flujo
#### Algoritmo
Es una secuencia de pasos lógicamente ordenados y finitos que dan solución a un problema determinado. Estos deben ser precisos, consistentes y finitos 
Pueden ser de dos tipos: 

**1. Cualitativos 🗣️**

Descripción a través de frases y palabras.

**Ejemplo: Hacer palomitas de maiz 🍿**

0. Inicio
1. Coloca una olla pesada en la estufa.
2. Añade el aceite y una sola capa de maíz a la olla.
3. Enciende el fuego a intensidad media-alta.
4. Cubre la olla con una tapa.
5. Mueve la olla constantemente sobre el quemador para distribuir el calor de manera uniforme una vez que el maíz comience a reventar vigorosamente.
6. Continúa moviendo hasta que el sonido de los reventones se haga muy lento.
7. Apaga el fuego inmediatamente.
8. Retira la olla de la estufa y espera a que cese el ruido por completo.
9. Destapa la olla con cuidado.
10. Vierte las palomitas en un tazón.
11. Añade sal.
12. Fin


**2. Cuantitativos 🔢**

Uso de cálculos o fórmulas matemáticas.

**Ejemplo: ¿Qué hacer para sumar dos números?**

0. Inicio.
1. Numero uno: 3.
2. Número dos: 5.
3. Sumar 3 y 5.
4. El resultado es 8.
5. Fin.

- Se puede resolver de varias maneras un mismo algoritmo, dependiendo del ingenio de cada persona [1].

**Componentes de un algoritmo**

**Entrada:** Informacion que se debe ingresar.

**Proceso:** Operacion que se deben realizar para dar solucion al problema.

**Salida:** El resultado del proceso

#### Pseudocodigo
Instrucciones escritas bajo cierta estructura para poder adentrarse al entendimiento de la programacion, es un intermedio del lenguaje natural y el lenguaje de programacion, para esto se uso la herramienta Pseint.
Pseint es una herramienta donde aplicamos fácilmente pseudolenguaje de programación en su versión en español, este está acompañado además de un editor y visor de diagramas de flujo que nos permite centrarnos en el aprendizaje de los conceptos de algoritmos computacionales.
Este programa nos ayuda a que la introducción a un lenguaje de programación sea mucho más llevadera y sencilla, brindándonos varios conceptos de algoritmos computacionales para luego poder adentrarnos a un lenguaje de programación real [2].

- Ingrese a este enlace si desea descargar Pseint en su ordenador --> [Pseint](https://pseint.sourceforge.net/)

#### Diagramas de flujo
Utiliza simbolos y graficas para representar las distintas instrucciones que debe seguir el algoritmo, se hace automaticamente en Pseint al hacer nuestro pseudocodigo

### Programacion por bloques 🧩
La programación por bloques es un enfoque de codificación visual donde los usuarios crean programas arrastrando y uniendo bloques gráficos predefinidos que representan comandos y estructuras de lógica. Elimina la necesidad de escribir código complejo basado en texto y sintaxis, reemplazándolo por un sistema de "rompecabezas" donde solo las piezas lógicamente compatibles pueden encajarse, haciendo asi mas simple el aprendizaje de programacion.

![progbloques](https://github.com/user-attachments/assets/3285c91e-f7ed-43e2-b1a5-f7f0110e665d)

**Ejemplo de pagina para programar por bloques:**

Desafio donde se tiene que indicar las acciones del gato para que se pueda comer un churrasco

![imagenbloques](https://github.com/user-attachments/assets/fe922f10-6b4e-4ef7-b10d-a9f1d46300ae)

![gatoresuelto](https://github.com/user-attachments/assets/481cdf61-9fd2-490c-b0b1-1c4224166a3d)

El gato con las instrucciones logra realizar la accion solicitada

- Ingrese en este enlace para experimentar como es la programacion por bloques --> [PilasBloques](https://pilasbloques.program.ar/online/)

### Pruebas de escritorio

Es una prueba manual que realiza el programador al acabar su codigo, asegurandose de usar correctamente las variables y operaciones para comparar los resultados con los de la maquina y asegurarse que funcione correctamente.

### Ejemplos de algoritmos con estructuras lineales 👇
**Enunciado del Problema**

**Título:** Cálculo de Edad Actual y Edad Futura (Año 2050)

**Descripción:** Escriba un algoritmo que solicite al usuario dos datos enteros:

- El año actual en el que se encuentra.

- Su año de nacimiento.

El programa deberá mostrar:

- La edad actual de la persona.

- La edad que la persona tendrá en el año 2050.

**Solucion en Pseint**

**Algoritmo**

![algoritmo](https://github.com/user-attachments/assets/dfdd9347-d2fd-4fba-9ad0-f5597bb93dc4)

**Ejecucion**

![prueba](https://github.com/user-attachments/assets/3eb15835-8928-42d7-bba0-26f9e04402f1)

**Diagrama de flujo**

![diagrama](https://github.com/user-attachments/assets/2000c269-8c40-44ac-ba37-b71d4ca8fbe8)

**Resolucion en lenguaje C, usando Visual Studio Code 🖥️**

Codigo en C

![codigo](https://github.com/user-attachments/assets/39339cfd-7514-4569-a527-f0051cb74f15)

Terminal mostrando que si funciona el codigo

![terminal](https://github.com/user-attachments/assets/61cf2e66-9846-4a6a-8a51-73d88588aac1)

**Copilacion y ejecucion en lenguaje C.**

Para ejecutar en C, primero copilamos con el comando gcc xxxx.c -o xxxxx, donde xxxx es el nombre de nuestro archivo, una vez copilado lo ejecutamamos con .\xxxx.exe siendo xxxx el nombre con el que copilamos nuestro codigo, con esto ya nos dejara ingresar los datos de entrada y nos mostrar los datos de salida.

Adicionalmente uso el comando cd para dirigirme a la carpeta en donde guardo mis copilaciones y archivos .exe de mis practicas.




**Prueba de escritorio**

Se usaron distintos valores para verificar que el codigo sea consistente con cualquier valor que se le de

![pruebadeescritorio](https://github.com/user-attachments/assets/deb4d53a-cf78-4e17-9ad3-a0c2ec56ba99)


- Si desea ver los ejercicios resueltos en el programa ingrese a este enlace --> [ejercicio de años](https://drive.google.com/drive/folders/1U6hXxmJI3jbLH-En-mNHTkmuQkX8duka?usp=sharing)

### Principales dificultades en la aplicacion de los contenidos 🚧
La principal dificultad aparecio al pasar de pseudocodigo a un lenguaje de programacion real como es C, la estructura era menos parecida al lenguaje natural, teniendo que recordar palabras clave en ingles, recordar siempre usar el ";", como se usan correctamente las mascaras, y otros signos fue un poco dificil al principio, pero resolviendo varios ejercicios uno se va acostumbrando a que errores evitar y como crear el codigo correctamente. ✅

### Reflexion ✨✨
Esta unidad ha sido crucial para entender que la programación es, ante todo, lógica. Aprendí que un algoritmo es la base de todo código y debe ser preciso, consistente y finito. El uso de PseInt y el pseudocódigo fue fundamental, ya que sirvió como un puente de lenguaje natural que me permitió concentrarme en la lógica de Entrada, Proceso y Salida sin preocuparme inicialmente por la sintaxis estricta. La principal dificultad apareció al pasar a C, donde tuve que adaptar mi pensamiento a su estructura rígida y sintaxis. Superar errores iniciales como el uso incorrecto del punto y coma (;), las mascaras (%d), y las reglas de tipos de datos, me enseñó que la única forma de dominar un lenguaje de programación es a través de la práctica constante. Ahora reconozco y sé cómo evitar estos errores comunes, lo cual me prepara mejor para las unidades futuras.

### Evidencia de las tareas entregadas en la unidad 1 📂

Enlace en google drive de las tareas de la unidad 1 --> [Tareas unidad 1](https://drive.google.com/drive/folders/1-_LpqLXI3DvtouSTW_lGGA3PeHprJ-w0?usp=sharing) 

- **Ingrese aqui para volver a la pagina principal -->** [pagina principal](Index.md)
