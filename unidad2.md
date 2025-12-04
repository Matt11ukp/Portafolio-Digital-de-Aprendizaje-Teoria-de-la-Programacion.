# Unidad 1

## Contenidos de la unidad 1

### Estructuras condicionales

#### 1. Simples (If)

Si pasa esto, haz esto. Evalúa una condición. Si es verdadera, ejecuta la acción. Si es falsa, no hace nada y el programa sigue su curso.

**Ejemplo de caso if:**

Programa que indica si tu nota es aprobatoria, siempre que sea mayor o igual a 12.

**Codigo en C:**

<div align="center">
  <img width="299" height="73" alt="Captura de pantalla 2025-12-02 164408" src="https://github.com/user-attachments/assets/1b34e036-0805-472a-8bec-ec3e63e7774c" />
</div>

**Diagrama de flujo:**

<div align="center">
  <img width="390" height="205" alt="Captura de pantalla 2025-12-03 165404" src="https://github.com/user-attachments/assets/8cf84411-cbe2-4163-8b9f-3bc8c8e098d9" />
</div>

#### 2. Dobles (If - Else)

Si pasa esto, haz A. Si no, haz B. Si la condición se cumple, toma el primer camino, si no, toma el segundo. 

**Ejemplo de caso if - else**

Programa que identifica que tipo de triangulo es, segun las medidas que se le ingrese.

**Codigo en C:**

<div align="center">
  <img width="793" height="208" alt="Captura de pantalla 2025-12-02 164601" src="https://github.com/user-attachments/assets/27216652-e6ba-471e-80fe-6b0a1abe023c" />
</div>

**Diagrama de flujo:**

<div align="center">
<img width="1000" height="340" alt="Captura de pantalla 2025-12-03 165732" src="https://github.com/user-attachments/assets/c503c49c-e69d-4719-af50-f10e9d1a0ed7" />
</div>

#### 3. Múltiples (Switch)

En caso de ser la opción 1, haz esto; en caso de ser la 2, haz esto otro. Elige un camino específico entre muchas opciones predefinidas.

**Ejemplo de caso switch**

Programa que realiza la operacion entre dos numeros dependiendo que operador se le ingrese.

**Codigo en C:**

<div align="center">
  <img width="676" height="481" alt="Captura de pantalla 2025-12-02 164151" src="https://github.com/user-attachments/assets/4b7e2fc0-8aaa-411a-8763-303407367fd5" />
</div>

**Diagrama de flujo:**

<div align="center">
<img width="1783" height="377" alt="Captura de pantalla 2025-12-03 170052" src="https://github.com/user-attachments/assets/944fc4fb-e4ff-4184-ae48-d471b11f8242" />
</div>

### Estructuras repetitivas

#### 1. Mientras (While)

Mientras la condición sea verdadera, se sigue repitiendo. Evalúa la condición al principio. Si la condición es falsa desde el inicio, el ciclo nunca se ejecuta. Se usa cuando no sabes cuántas veces tendrás que repetir.

**Ejemplo de caso while** 

Programa que muestra la suma consecutiva de todos los numeros del 0 al 5.

**Codigo en C:**

<div align="center">
  <img width="459" height="289" alt="Captura de pantalla 2025-12-02 164029" src="https://github.com/user-attachments/assets/2b8f3e6d-7c60-4146-bc94-a82168607799" />
</div>

**Diagrama de flujo:**

<div align="center">
  <img width="470" height="300" alt="Captura de pantalla 2025-12-04 165027" src="https://github.com/user-attachments/assets/0652a7c6-e2e8-4135-920a-dd8e0f5af1ad" />
</div>

#### 2. Hacer... Mientras (Do While)

Lógica: Hacerlo una vez, y luego revisar si se debe repetir. Evalúa la condición al final. Esto garantiza que el bloque de instrucciones se ejecute obligatoriamente al menos una vez.

**Ejemplo de caso do while**

Programa que usa el do while para contar cuantos numeros positivos ingresa el usuario.

**Codigo en C:**

<div align="center">
  <img width="369" height="168" alt="Captura de pantalla 2025-12-02 164314" src="https://github.com/user-attachments/assets/94aa8aaf-dbcd-4a6b-873f-9fbc1b409924" />
</div>

**Diagrama de flujo:**

<div align="center">
  <img width="438" height="481" alt="Captura de pantalla 2025-12-04 092106" src="https://github.com/user-attachments/assets/2f71975e-97e7-4fed-b9e1-8677ac40dfbc" />
</div>

#### 3. Para (For)

Repitir algo una cantidad exacta de veces. Es un bucle controlado por un contador automático. Es ideal cuando sabes de antemano cuántas vueltas dará el ciclo (como recorrer una lista de 10 alumnos).

**Ejemplo de caso for**

Programa que muestra la tabla de multiplicar del 2.

**Codigo en C:**

<div align="center">
  <img width="505" height="169" alt="Captura de pantalla 2025-12-02 164206" src="https://github.com/user-attachments/assets/4c57a8b3-3e2a-4c2d-86c2-8d7d80ba0aff" />
</div>

**Diagrama de flujo:**

<div align="center">
  <img width="654" height="325" alt="Captura de pantalla 2025-12-04 091851" src="https://github.com/user-attachments/assets/45c3b6fb-8e09-4a9d-875f-bf6e3b1d1775" />
</div>

### Ejercicio combinando estructuras condicionales y repetitivas (Python)

#### Descripcion del problema

Una empresa requiere un programa para automatizar el control de calidad de un lote de baterías recargables destinadas a un sistema de carga solar. El programa debe permitir al usuario ingresar los voltajes medidos, 
validar que sean físicamente posibles, clasificarlas según su estado de carga y generar un reporte estadístico final.

Un número entero que representa la cantidad total de baterías a evaluar, debe ser mayor a 0. Si el usuario ingresa un valor menor o igual a 0, el programa debe pedir el dato nuevamente. Posteriormente, se leerá el Voltaje (V) de cada batería, este voltaje debe estar en el rango de entre 0 y 15. Si el usuario ingresa un valor fuera de este rango, el programa debe solicitar el dato nuevamente hasta que se ingrese un valor válido. Para cada voltaje válido ingresado, se debe determinar el estado de la batería según lo siguiente: 

- Voltaje menor a 5 = Defectuoso

- Voltaje mayor o igual a 5 y menor o igual a 9 = Recuperable

- Voltaje mayor a nueve = Optimo

Al finalizar la lectura de los voltajes de las baterías, el programa debe mostrar la cantidad total de baterías defectuosas, recuperables y optimas, y ademas mostrar el Promedio de voltaje Útil: Este promedio se calcula considerando únicamente las baterías con estado "Recuperable" y "Óptima". 

**Diagrama de flujo**

<div align="center">
  <img width="1029" height="916" alt="Captura de pantalla 2025-12-04 171050" src="https://github.com/user-attachments/assets/c87c6c34-57d8-4f99-aaeb-c516ba2816e5" />
</div>

**Codigo en python**

<div align="center">
  <img width="1084" height="775" alt="Captura de pantalla 2025-12-04 161806" src="https://github.com/user-attachments/assets/fa702d8d-51c8-4d47-940c-3a20e1442f69" />
</div>

<div align="center">
  <img width="1123" height="277" alt="Captura de pantalla 2025-12-04 161818" src="https://github.com/user-attachments/assets/b087f3a6-6a19-4670-b541-c65440a4ca35" />
</div>

**Verificacion**

<div align="center">
  <img width="680" height="296" alt="Captura de pantalla 2025-12-04 171658" src="https://github.com/user-attachments/assets/f5589040-1211-4f0f-aa46-d9900e02de14" />
</div>

<div align="center">
  <img width="639" height="326" alt="Captura de pantalla 2025-12-04 171706" src="https://github.com/user-attachments/assets/ba05bb15-eaea-4a0d-a1f2-b6145e6452f5" />
</div>

### Principales dificultades en la aplicacion de los contenidos

Presente muchos errores de cálculo por no igualar los acumuladores a algun numero, haciendo que mi programa calcule mal al confundirse con memoria basura.
Tambien tuve dudas al decidir cuándo era más eficiente usar los distintos tipos de estructuras, en especial en problemas mas complejos que necesitan anidamiento.

### Reflexion critica de los aprendizajes de la unidad

Al terminar esta unidad, me di cuenta de que programar no se trata solamente de escribir codigo, sino de saber pensar el problema antes de tocar el teclado. Lo que realmente marcó la diferencia para mí fue hacer pruebas de escritorio; simular yo mismo ser la computadora y seguir el código línea por línea fue clave para entender la lógica real detrás de las estructuras condicionales y repetitivas, para asi encontrar errores que no veía en la pantalla. Aprendí que la paciencia, el orden y validar los datos son igual de importantes que la sintaxis para que todo funcione bien.

### Tareas entregadas

#### ACD

- El ACD de esta unidad fue un control de aprendizaje realizado en el EVA.

#### APE

- Enlace en Google Drive con los Ape de la unidad 2 ----> [APE](https://drive.google.com/drive/folders/1pcJizpqSC3AfU0EuePccWKpeScC1vTbE?usp=sharing)

#### AA

- Enlace en Google Drive con los AA de la unidad 2 ----> [AA](https://drive.google.com/drive/folders/1_lKo_arvILV2ngJJwEac6jgtT3F3BKC-?usp=sharing)
-------------------

- **Ingrese aqui para volver a la pagina principal -->** [pagina principal](Index.md)
