# InformeLaboratorio

1. OBJETIVOS

1.1.	Objetivo general

Entender, comprender y resolver los siguientes ejercicios de laboratorio, mediante el uso de los teoremas de superposición, transferencia máxima y del Teorema de Thevenin.

1.2.	Objetivos especificos

• Aplicar el teorema de superposición al análisis de circuitos

• Aplicar el teorema de Thevenin para simplificar un circuito para su análisis

• Aplicar el teorema de Norton para simplificar un circuito

• Aplicar el teorema de transferencia de potencia máxima

2. MARCO TEÓRICO (RESUMEN)

2.1	TEOREMA DE SUPERPOSICIÓN

Es un método útil para el análisis de circuitos que tienen más de una fuente.

Pasos para aplicar el método de superposición:

Paso 1. Dejar una fuente de voltaje (o de corriente) a la vez en el circuito y reemplazar cada
una de las demás fuentes de voltaje (o de corriente) con su resistencia interna. Para
fuentes ideales, un corto representa resistencia interna de cero y una abertura representa resistencia interna infinita.

Paso 2. Determinar la corriente (o el voltaje) particular que se desea justo como si hubiera
sólo una fuente en el circuito.

Paso 3. Tomar la siguiente fuente que haya en el circuito y repetir los pasos 1 y 2. Hacer esto con cada una de las fuentes.

Paso 4. Sumar algebraicamente las corrientes producidas por cada fuente individual para encontrar la corriente real en una rama dada. (Si las corrientes están en la misma dirección, se suman. Si están en direcciones opuestas, se restan y la dirección de la
corriente resultante será la misma que la presentada por la cantidad más grande de las
cantidades originales.) Una vez determinada la corriente, ya se puede calcular el voltaje mediante la ley de Ohm. 

2.2 TEOREMA DE THEVENIN

Es un método empleado para transformar un circuito lineal de dos terminales en un circuito equivalente con sólo una fuente de voltaje en serie con una sola resistencia. Además, el teorema permite reducir cualquier circuito resistivo lineal de dos terminales a una forma equivalente compuesta por una fuente de voltaje equivalente en serie con una resistencia equivalente. El circuito equivalente de Thevenin siempre aparece en la forma de una fuente de voltaje equivalente en serie con una resistencia equivalente haciendo caso omiso del circuito original que reemplaza. La importancia del teorema de Thevenin es que el circuito equivalente puede reemplazar al circuito original en cuanto a cualquier carga externa. Cualquier resistor de carga conectado entre las terminales de un circuito equivalente de Thevenin tendrá la misma corriente
a través de él y el mismo voltaje entre sus extremos como si estuviera conectado a las terminales.
del circuito original.

Pasos a seguir para aplicar el teorema de Thevenin:

Paso 1. Abrir las dos terminales (eliminar cualquier carga) entre las que se desea encontrar el
circuito equivalente de Thevenin.

Paso 2. Determinar el voltaje (VTH) entre las dos terminales abiertas.

Paso 3. Determinar la resistencia (RTH) entre las dos terminales abiertas con todas las fuentes
reemplazadas por sus resistencias internas (fuentes de voltaje ideales en cortocircuito
y fuentes de corriente ideales abiertas).

Paso 4. Conectar VTH y RTH en serie para producir el equivalente de Thevenin completo del
circuito original.

Paso 5. Reemplazar la carga eliminada en el paso 1 entre las terminales del circuito equivalente de Thevenin. Ahora se pueden calcular la corriente y el voltaje que haya en la
carga utilizando solamente la ley de Ohm. Tienen el mismo valor que la corriente y
el voltaje presentes en la carga del circuito original.

2.3 TEOREMA DE TRANSFERENCIA DE POTENCIA MÁXIMA

La transferencia de potencia máxima desde una fuente hasta una carga  ocurre cuando la resistencia de la carga es igual a la resistencia interna de la fuente. Hay que tener en cuenta que, el teorema de transferencia de potencia máxima es importante cuando se tiene que conocer el valor de la carga con la cual la fuente suministra la máxima potencia. Además, cuando se transfiere potencia máxima a una carga desde una fuente cuando la resistencia de la carga es igual a la resistencia interna de la fuente.

3. EXPLICACIÓN Y RESOLUCIÓN DE EJERCICIOS O PROBLEMAS

Ejercicio 1

![image](https://user-images.githubusercontent.com/104941068/184794322-63e5fcf2-eb88-42a0-b857-b23eba1355e8.png)

Circuito realizado en un laboratorio virtual

![image](https://user-images.githubusercontent.com/104941068/184807334-e6ce6e46-80b5-48d3-a174-b5eccdc38969.png)

![image](https://user-images.githubusercontent.com/104941068/184807866-9f20f567-a482-4ec5-bc1a-8ee1a0e6cea3.png)

Solución

![image](https://user-images.githubusercontent.com/104941068/184807594-1253f26e-cc7a-40af-b410-6413cbac416b.png)

![image](https://user-images.githubusercontent.com/104941068/184810028-28c6470f-606a-43d2-b8c5-031fafecb60c.png)

![image](https://user-images.githubusercontent.com/104941068/184810238-44d835b9-d85d-43fc-a445-bfb6cdd90ea2.png)

Ejercicio 2

![image](https://user-images.githubusercontent.com/104941068/184795996-5f258416-ba03-485d-8570-156a0bd11744.png)

Circuito realizado en un laboratorio virtual

![image](https://user-images.githubusercontent.com/104941068/184808850-a308a97a-1172-49d1-bf81-c6305d96aa5f.png)

![image](https://user-images.githubusercontent.com/104941068/184808941-86bb0976-993d-45d8-b3fb-dbbc9a390083.png)

Solución aplicando el Teorema de Thevenin

![image](https://user-images.githubusercontent.com/104941068/184809043-dc4eeee6-9b10-45d7-89f9-85a4ee4c6e7e.png)

![image](https://user-images.githubusercontent.com/104941068/184809114-63d9c9a5-36ea-4e0f-82ce-2871ec2ef46f.png)

Ejercicio 3

![image](https://user-images.githubusercontent.com/104941068/184796013-f453f5c0-023f-4fe4-b0fb-326de78e3eb0.png)

Circuito realizado en un laboratorio virtual

![image](https://user-images.githubusercontent.com/104941068/184832016-da6ed5e7-14e4-4b68-85f7-319a58cbbfd3.png)

Pasos previos a la solución

![image](https://user-images.githubusercontent.com/104941068/184832405-c7363d58-f537-43f5-80b2-817fc025cde4.png)

![image](https://user-images.githubusercontent.com/104941068/184832926-d65a75f6-50c9-49b6-b05a-7701d10281f7.png)

Solución

![image](https://user-images.githubusercontent.com/104941068/184833498-759ab9ee-f5b7-4eaa-a253-8872923594ee.png)

![image](https://user-images.githubusercontent.com/104941068/184833550-7bcc6a50-60c8-482c-bf7a-c2cb5de75b9b.png)

4. EXPLICACIÓN Y RESOLUCIÓN DE EJERCICIOS O PROBLEMAS

Ejercicio 1

VTH=8.32 V RTH=4.7KΩ

P=IxV P=3.78x8.32

P=31.44mW

Ejercicio 2

I=500-400

I=100mA

Ejercicio 3

VTH=10 V RTH=5Ω

I=909 mA

5. VIDEO

https://youtu.be/UfDs2G1iJy0

6. CONCLUSIONES

• Se logró aplicar el teorema de superposición al análisis de
un circuito.

• Se hizo uso del teorema de Thevenin para simplificar un
circuito para su análisis.

• Se utilizó el teorema de transferencia de potencia
máxima para resolver un ejercicio.

6. BIBLIOGRAFÍA:
FLOYD, T. L. (2008). DISPOSITIVOS ELECTRONICOS (8a. ed.). MEXICO: PEARSON EDUCACION.

RUBRICA

![](https://github.com/doalulema/InformeTarea/blob/main/Tarea.png)
