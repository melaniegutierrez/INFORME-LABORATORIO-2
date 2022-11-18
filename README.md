# INFORME LABORATORIO 2

### 1. OBJETIVO

Comprobar experimentalmente el Análisis de Mallas, mediante la replicación física de un circuito mixto además te calculos teóricos y simulados, con el fin de demostrar la teoria expuesta en clase conjuntamente con investigaciones para un mejor diseño de circuitos que cumplan con nuestras necesidades. 

### Objetivos específicos

- Identificar las diferentes trayectorias de mallas, mediante la simulación previa del circuito en la aplicación tinkercad para poder medir corrientes en dichas trayectorias de manera correcta.

- Compilar datos de medida de diferentes circuitos fisicos, mediante la manipulación de tres circuitos fisicos diferentes y un multimetro para demostrar los margenes de error existente tanto en cicruitos simulador, fisicos y los valores teoricos. 

- Identificar el uso correcto de los componentes físicos de un circuito con el fin de armar circuitos mixtos ordenados para poder identificar mallas fuera de representaciones esquematicas, sino de circuitos palpables.

### 2. MARCO TEORICO

![](https://github.com/melaniegutierrez/INFORME-LABORATORIO-2/blob/main/An%C3%A1lisis%20de%20mallas.jpeg)

### 3. EXPLICACIÓN DEL PROCEDIMIENTO

Malla 1 (R1 – R2)

![](https://github.com/melaniegutierrez/CAP-LAB-2/blob/main/m11.png)

Malla 2 (R2 – R3 – R4)

![](https://github.com/melaniegutierrez/CAP-LAB-2/blob/main/m21.png)

Malla 3 (R4 – R5)

![](https://github.com/melaniegutierrez/CAP-LAB-2/blob/main/m31.png)

**Procedimientos**

![](https://github.com/melaniegutierrez/CAP-LAB-2/blob/main/c1.png)

**Calculos Teóricos**

![](https://github.com/melaniegutierrez/CAP-LAB-2/blob/main/p1.png)

### 4.RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

Tabla 2.1. Resultados obtenidos para el circuito de la figura 2.1.

| **MALLA** | **RESULTADOS ANALITICOS** | **VRESULTADOS EXPERIMENTALES** | **VRESULTADOS SIMULADOS** |
| :-------------: | :-------------: | :-------------: | :-------------: |
| 1 | 2.8 mA| 2.50 mA| 2.8 mA|
| 2 | 0.1 mA| 0.19 mA| 0.1 mA |
| 3 | -1.07 mA | -1.58 mA| -1.07 mA |

Cálculo de errores

Teóricos en relación de los simulados.

![](https://github.com/melaniegutierrez/CAP-LAB-2/blob/main/e1.png)

Los porcentajes de error con relación a los simulador son cero debido a que estamos tratando con valores ideales, es decir sin caidas de energia y con medidas exactamente iguales.

Teóricos en relación de los experimentales.

![](https://github.com/melaniegutierrez/CAP-LAB-2/blob/main/e2.png)

Con respecto a los datos experimentales y teoricos tenemos margenes de error relativamente altos, esto debido a que no trabajamos con valores ideales en un circuito físico, asi que debido a que no se usan fuentes de voltajes extacto, ademas existe perdida de energia debido a factores externos. 

### 5. VIDEO

Link: https://youtu.be/hNtZnViwcsM

### 6. CONCLUSIONES

- Con los conocimientos previos de las leyes de kirchoff, se pudo realizar el análisis de las corrientes de mallas en los diferentes nodos, además realizando los cálculos analíticos, y armando el circuito en físico, que en este caso, hay que tener en cuenta que los valores medidos experimentalmente, no son exactamente los mismos a los simulados, debido a que al tener fuentes de voltaje no ideales, el voltaje al aumentar o disminuir, proporcionalmente lo hará la corriente, cumpliendo la ley de ohm.

- Las importancia de saber diferenciar las mallas de un circuito eléctrico, radica en que a través de ese análisis es posible identificar las diferentes corrientes que circulan por cada malla del circuito ya que la malla es un circuito cerrado por lo cual su valor será constante en cada una de las mallas.

 - Dentro del area de electronica las bases teoricas son muy importantes, es decir para tener una mejor comprension de como funciona una malla, debido a que conlleva un estudio analitico desde leyes de ohm hasta leyes de Kirchhoff.  

### 7. BIBLIOGRAFIA 

Khan Academy. (2022). Khanacademy.org. https://es.khanacademy.org/science/physics/circuits-topic/circuits-resistance/a/ee-kirchhoffs-laws

‌
Guía de estudio 7: Mallas y Nodos. (n.d.). http://www.inet.edu.ar/wp-content/uploads/2020/07/ELECTRONICA_Gu--a07-Mallas-y-Nodos.pdf



‌





