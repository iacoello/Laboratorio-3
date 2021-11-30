**“UNIVERSIDAD DE LAS FUERZAS ARMADAS”**

**“ESPE”**

![Logo_ESPE](https://user-images.githubusercontent.com/93800511/140828546-04ee2765-180c-4e68-84cf-8bca73c21c5f.png)

**INTEGRANTES**
* Coello Ismael 
* Paola Morales 
* Andrés Granda
 
**CLASE**
* FUNDAMENTOS DE CIRCUITOS ELECTRICOS **NRC** : 10149

**FECHA DE ENTREGA**
* 2/12/2021
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**3.1. OBJETIVO GENERAL**

Comprobar experimentalmente el Análisis de Nodos desarrollado por mediode las leyes de Kirchoff de nodos  haciendo usodos en sistemas de representacion virtuales, fisicos y teoricos relacionados al armado y analisis de circuitos electrónicos.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**3.2. REQUISITOS PREVIOS**

Se requiere el análisis analítico del circuito mostrado en la figura 3.1., mediante la técnica del análisis de nodos. El valor obtenido de cada voltaje de nodo anótelo en la
tabla 3.1.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**3.3. INFORMACIÓN GENERAL**

El análisis de nodos es una técnica que hace uso de la LCK para expresar corrientes en función de voltajes.
Un nodo es el punto de unión de dos o más elementos.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**3.4. MATERIAL Y EQUIPO REQUERIDO**

![78](https://user-images.githubusercontent.com/93800511/143964444-144a4941-bbeb-4eba-bdd8-5ac136446ab0.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**3.5. MARCO TEÓRICO**

![142921057-ca1f6939-c1be-4cb4-85a4-2bc00deb63ce](https://user-images.githubusercontent.com/93800511/143978078-b99a56b0-fde6-4c8d-a812-883608061667.png)

![Diagrama en blanco (3)](https://user-images.githubusercontent.com/93800511/143981009-4e946440-3798-4914-8fba-59183e640eb3.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**3.6. PROCEDIMIENTO**

**3.6.1. Implemente el circuito que se presenta en la figura 3.1.**

![imagen](https://user-images.githubusercontent.com/93835533/143982374-bd37c80a-659b-4bef-a5ce-0a6096d3cc51.png)


* Circuito Armado

![cir](https://user-images.githubusercontent.com/93835587/143969453-5cf7b4d9-8fe7-4209-bb55-96cff8414839.jpg)

![435e00f5-26e1-428c-86d0-7414ddfa42e8](https://user-images.githubusercontent.com/93800511/143973543-513a4e95-6741-44db-82d9-0975f6adb830.jpg)

**3.6.2. Mida cada uno de los voltajes de nodo y anote los resultados en la tabla 3.1.**

![image](https://user-images.githubusercontent.com/93835587/143969931-1b1205ee-c532-4430-9a51-b47992e78315.png)



**3.6.3. Simule en el software Multisim, Proteus, o cualquier otro simulador, el circuito de la figura 3.1, obteniendo los valores de los voltajes de nodo. Anote los resultados en la tabla 3.1.**

![imagen](https://user-images.githubusercontent.com/93835533/143983282-72415bd6-fbeb-4804-9a3b-0eb60aa585df.png)


**3.6.4. Compare los valores de la tabla 3.1 y realice sus conclusiones.**

![image](https://user-images.githubusercontent.com/93835587/143974630-5ee36c11-3731-41d8-bf48-df9560f92f12.png)


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**3.7. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR**


![diagrama](https://user-images.githubusercontent.com/93835533/143984090-a6f8a82d-8534-49d1-976c-36271f386f53.png)

<img src="https://latex.codecogs.com/svg.image?\\NODO~1\to&space;No~genera~ecuaciones" title="\\NODO~1\to No~genera~ecuaciones" />

<img src="https://latex.codecogs.com/svg.image?\\NODO~2\\&space;I_{1}&plus;I_{2}&plus;I_{3}=&space;0\\\\\frac{V_{1}-V_{2}}{R_{1}}&space;&plus;\frac{V_{0}-V_{2}}{R_{2}}&plus;\frac{V_{3}-V_{2}}{R_{3}}=&space;0\\\\\frac{V_{F1}-V_{2}}{R_{1}}&space;&plus;\frac{V_{0}-V_{2}}{R_{2}}&plus;\frac{V_{3}-V_{2}}{R_{3}}=&space;0\\&space;\\V_{F1}\left&space;(&space;\frac{1}{R1}&space;\right&space;)&plus;V_{3}\left&space;(&space;\frac{1}{R3}&space;\right&space;)-V_{2}\left&space;(&space;\frac{1}{R1}&space;&plus;\frac{1}{R2}&plus;\frac{1}{R3}\right&space;)=&space;0" title="\\NODO~2\\ I_{1}+I_{2}+I_{3}= 0\\\\\frac{V_{1}-V_{2}}{R_{1}} +\frac{V_{0}-V_{2}}{R_{2}}+\frac{V_{3}-V_{2}}{R_{3}}= 0\\\\\frac{V_{F1}-V_{2}}{R_{1}} +\frac{V_{0}-V_{2}}{R_{2}}+\frac{V_{3}-V_{2}}{R_{3}}= 0\\ \\V_{F1}\left ( \frac{1}{R1} \right )+V_{3}\left ( \frac{1}{R3} \right )-V_{2}\left ( \frac{1}{R1} +\frac{1}{R2}+\frac{1}{R3}\right )= 0" />

<img src="https://latex.codecogs.com/svg.image?Remplazamos~datos~en~la~siguiente~ecuacion\\V_{F1}\left&space;(\frac{1}{R1}&space;\right&space;)&plus;V_{3}\left&space;(&space;\frac{1}{R3}&space;\right&space;)-V_{2}\left&space;(\frac{1}{R1}&space;&plus;\frac{1}{R2}&plus;\frac{1}{R3}\right&space;)=&space;0\\12\left&space;(&space;\frac{1}{1800\mho}&space;\right&space;)&plus;V_{3}\left&space;(&space;\frac{1}{2200\mho&space;}&space;\right&space;)-V_{2}\left&space;(\frac{1}{1800\mho&space;}&space;&plus;\frac{1}{470\mho&space;}&plus;\frac{1}{2200\mho&space;}\right&space;)=&space;0\\Obtenemos~la~siguiente~ecuacion&space;\\0,0067V&plus;0,0005\mho&space;^{-1}&space;V_{3}-0,0031\mho^{-1}V_{2}=&space;0" title="Remplazamos~datos~en~la~siguiente~ecuacion\\V_{F1}\left (\frac{1}{R1} \right )+V_{3}\left ( \frac{1}{R3} \right )-V_{2}\left (\frac{1}{R1} +\frac{1}{R2}+\frac{1}{R3}\right )= 0\\12\left ( \frac{1}{1800\mho} \right )+V_{3}\left ( \frac{1}{2200\mho } \right )-V_{2}\left (\frac{1}{1800\mho } +\frac{1}{470\mho }+\frac{1}{2200\mho }\right )= 0\\Obtenemos~la~siguiente~ecuacion \\0,0067V+0,0005\mho ^{-1} V_{3}-0,0031\mho^{-1}V_{2}= 0" />

<img src="https://latex.codecogs.com/svg.image?\\Despejamos~V_{2}~en~las~dos~ecuasiones\\\\V_{2}=&space;\frac{0,005V_{3}&plus;0,0067}{0,0031}&space;\\\\V_{2}=&space;\frac{0,005V_{3}&plus;0,0067}{0,0031}\\&space;\\V_{2}=0,1612V_{3}&space;&plus;2,1613" title="\\Despejamos~V_{2}~en~las~dos~ecuasiones\\\\V_{2}= \frac{0,005V_{3}+0,0067}{0,0031} \\\\V_{2}= \frac{0,005V_{3}+0,0067}{0,0031}\\ \\V_{2}=0,1612V_{3} +2,1613" />




<img src="https://latex.codecogs.com/svg.image?\\NODO~3\\&space;I_{3}&plus;I_{4}&plus;I_{5}=&space;0\\\\\frac{V_{2}-V_{3}}{R_{3}}&space;&plus;\frac{V_{0}-V_{3}}{R_{4}}&plus;\frac{V_{4}-V_{3}}{R_{5}}=&space;0\\\\\frac{V_{2}-V_{3}}{R_{3}}&space;&plus;\frac{V_{0}-V_{3}}{R_{4}}&plus;\frac{F_{2}-V_{3}}{R_{5}}=&space;0\\&space;\\V_{2}\left&space;(&space;\frac{1}{R3}&space;\right&space;)&plus;V_{F2}\left&space;(&space;\frac{1}{R5}&space;\right&space;)-V_{3}\left&space;(&space;\frac{1}{R3}&space;&plus;\frac{1}{R4}&plus;\frac{1}{R5}\right&space;)=&space;0&space;" title="\\NODO~3\\&space;I_{3}&plus;I_{4}&plus;I_{5}=&space;0\\\\\frac{V_{2}-V_{3}}{R_{3}}&space;&plus;\frac{V_{0}-V_{3}}{R_{4}}&plus;\frac{V_{4}-V_{3}}{R_{5}}=&space;0\\\\\frac{V_{2}-V_{3}}{R_{3}}&space;&plus;\frac{V_{0}-V_{3}}{R_{4}}&plus;\frac{F_{2}-V_{3}}{R_{5}}=&space;0\\&space;\\V_{2}\left&space;(&space;\frac{1}{R3}&space;\right&space;)&plus;V_{F2}\left&space;(&space;\frac{1}{R5}&space;\right&space;)-V_{3}\left&space;(&space;\frac{1}{R3}&space;&plus;\frac{1}{R4}&plus;\frac{1}{R5}\right&space;)=&space;0 " />


<img src="https://latex.codecogs.com/svg.image?Remplazamos~datos~en~la~siguiente~ecuacion&space;\\&space;\\V_{2}\left&space;(&space;\frac{1}{R3}&space;\right&space;)&plus;V_{F2}\left&space;(&space;\frac{1}{R5}&space;\right&space;)-V_{3}\left&space;(&space;\frac{1}{R3}&space;&plus;\frac{1}{R4}&plus;\frac{1}{R5}\right&space;)=&space;0\\&space;\\V_{2}\left&space;(&space;\frac{1}{2200\Omega}&space;\right&space;)&plus;8\left&space;(&space;\frac{1}{1500\Omega}&space;\right&space;)-V_{3}\left&space;(&space;\frac{1}{2200\Omega}&space;&plus;\frac{1}{3900\Omega}&plus;\frac{1}{1500\Omega}\right&space;)=&space;0&space;\\Obtenemos~la~siguiente~ecuacion&space;\\0,0053V-0,0014\Omega&space;^{-1}&space;V_{3}-0,0005\Omega^{-1}V_{2}=&space;0&space;" title="Remplazamos~datos~en~la~siguiente~ecuacion \\&space;\\V_{2}\left&space;(&space;\frac{1}{R3}&space;\right&space;)&plus;V_{F2}\left&space;(&space;\frac{1}{R5}&space;\right&space;)-V_{3}\left&space;(&space;\frac{1}{R3}&space;&plus;\frac{1}{R4}&plus;\frac{1}{R5}\right&space;)=&space;0\\&space;\\V_{2}\left&space;(&space;\frac{1}{2200\Omega}&space;\right&space;)&plus;8\left&space;(&space;\frac{1}{1500\Omega}&space;\right&space;)-V_{3}\left&space;(&space;\frac{1}{2200\Omega}&space;&plus;\frac{1}{3900\Omega}&plus;\frac{1}{1500\Omega}\right&space;)=&space;0 \\Obtenemos~la~siguiente~ecuacion&space;\\0,0053V-0,0014\Omega&space;^{-1}&space;V_{3}-0,0005\Omega^{-1}V_{2}=&space;0 " />


<img src="https://latex.codecogs.com/svg.image?\\Despejamos~V_{2}\\\\V_{2}=&space;\frac{0,0014V_{3}-0,0053}{0,0005}&space;\\\&space;\\V_{2}=2,8V_{3}&space;-10,6&space;" title="\\Despejamos~V_{2}\\\\V_{2}=&space;\frac{0,0014V_{3}-0,0053}{0,0005}&space;\\\&space;\\V_{2}=2,8V_{3}&space;-10,6 " />



<img src="https://latex.codecogs.com/svg.image?\\Para~obtener~nuestra~incognita~igualamos~V_{2}\\\\0,1612V_{3}&plus;2,1613&space;=&space;2,8V_{3}-10,6\\\\12,7213=&space;2,6397V_{3}&space;\\\\&space;V_{3}=&space;\frac{12,7213}{2,6397}\\&space;V_{3}=4,82V" title="\\Para~obtener~nuestra~incognita~igualamos~V_{2}\\\\0,1612V_{3}+2,1613 = 2,8V_{3}-10,6\\\\12,7213= 2,6397V_{3} \\\\ V_{3}= \frac{12,7213}{2,6397}\\ V_{3}=4,82V" />

<img src="https://latex.codecogs.com/svg.image?\\Encotramos~V_{2}\\\\V_{2}=2,8V_{3}&space;-10,6\\V_{2}=2,8(4,82)&space;-10,6\\V_{2}=2,82~V&space;" title="\\Encotramos~V_{2}\\\\V_{2}=2,8V_{3}&space;-10,6\\V_{2}=2,8(4,82)&space;-10,6\\V_{2}=2,82~V " />


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**3.8. VIDEOS**

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**3.9. CONCLUCIONES**

En conclución así como en el desarrollo del método de mallas se puede dislimbrar que los procesos para analizar los circuitos por nodos determinan de manera exacta las corrientes y voltajes que atraviezan este cumpliendo las leyes expuestas por Kirchoff, por medio de la practica se logro comprobar la utilidad y veracidad de estas leyes en su totalidad conforme a lo estudiado de manera teorica en clase.  

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**3.10. BIBLIOGRAFÍA**

Floyd, Thomas.L. (s. f.). Floyd Octava Edición principios de circuitos electricos (8va edición, Vol. 1). Prentice Hall. https://latecnicalf.com.ar/descargas/material/electronicaanalogica/Dispositivos%20Electronicos%208va.edicion-%20Floyd.pdf


