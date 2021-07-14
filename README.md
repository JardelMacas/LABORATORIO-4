# LABORATORIO-4

AUTORES: JERSON CHAMBA-JARDEL MACAS - ESTEFANY RAMOS

**1 . OBJETIVOS**

Objetivos Generales

* Demostrar la validez y eficiencia del analisis de circuitos electricos mediante el teorema de superposicion.

Objetivos Especificos

* Identificar los principios fundamentales que determina el analisis de circuitos electricos por superposicion.
* Analizar los diferentes metodos posibles para manejar los circuitos generados por el teorema de superposicion.

**2.MARCO TEORICO**

![ResumenLab4](https://user-images.githubusercontent.com/84357979/125633158-332ca3c2-f448-409e-8acd-5a87f3a4a46d.jpeg)


**3.EXPLICACIÓN DEL PROCEDIMIENTO**

1. Para dar inicio al desarrollo del laboratorio #4 es necesario tener conocimiento de cómo funciona el teorema de superposición como se muestra en el siguiente diagrama de un circuito.

![image](https://user-images.githubusercontent.com/84357979/125633396-b39e9030-6896-4e14-9dfb-648214ca528b.png)

2. Una vez realizado el análisis del circuito se observa que está dividido en tres mallas además consta de cuatro resistencias (dos en serie y dos en paralelo), y dos fuentes de voltaje. 
3. Continuando con el desarrollo se procede a la revisión del valor de cada componente en el circuito.

![image](https://user-images.githubusercontent.com/84357979/125633490-0f62e8b5-fd13-4d6f-86b2-346c5e77e20b.png)

4. Concluido los pasos anteriores procedemos a armar el circuito conforme se indica en el diagrama esquemático.
5. Se ubica el valor a cada una de las resistencias conforme a lo planteado anteriormente y procedemos a colocarlas en el protoboard de la siguiente manera: 

![image](https://user-images.githubusercontent.com/84357979/125633599-5030d99d-a42d-4508-b5f1-94552150be5e.png)

6.	Una vez terminado el armado del circuito se procede a iniciar la simulación para obtener la corriente con la que está trabajando el circuito como se muestra a continuación.

![image](https://user-images.githubusercontent.com/84357979/125633640-13c38e0b-f34c-4bee-9006-3ca7e33e5644.png)

7.	Ya conectadas las dos fuentes procedemos a calcular el voltaje VA con la ayuda de un multímetro que va conectado en paralelo a la resistencia que deseamos calcular, y además la corriente Ix presente en el circuito, teniendo en cuenta la polaridad del voltaje y el sentido de la corriente. 

![image](https://user-images.githubusercontent.com/84357979/125633691-ed3c7f40-d387-4ee9-a54b-0913bce53bdc.png)

![image](https://user-images.githubusercontent.com/84357979/125633726-e2895733-a39a-41d6-9eec-2961441776b6.png)

8.	De acuerdo al procedimiento del teorema de superposición hacemos “cero” la fuente de voltaje de 12 V (V2) y medimos el voltaje Va y la corriente Ix (La resistencia de Ix también se suprimiría al suprimir la fuente), respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anotamos el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

![image](https://user-images.githubusercontent.com/84357979/125633781-5734e259-9ffc-4b0e-a777-99f69cc9f3ea.png)


9.	De acuerdo al procedimiento del teorema de superposicion hacemos “cero” la fuente de Voltaje de 20 V (V1) y medimos el voltaje Va y la corriente Ix (en este caso si se considera la resistencia correspondiente a Ix), respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcione. Anotamos el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

![image](https://user-images.githubusercontent.com/84357979/125633837-951b2e09-6685-4e7c-9f5f-c8e9a1061540.png)

![image](https://user-images.githubusercontent.com/84357979/125633860-0a4e0de0-69bd-4ff5-b380-8936ed9bc6b2.png)


10.	Finalmente procedemos a medir el circuito analiticamente en el proceso matematico y a comparar resultados. 

**4.RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR**

Empezamos analizando el circuito propuesto, determinando sus componentes y sobre todo el numero de fuentes que este tenga:

![image](https://user-images.githubusercontent.com/84357979/125634055-b590ae58-0e7e-4510-b581-0dd3b1dc710d.png)

Según el teorema de superposición, el número de fuentes determina el número de circuitos a evaluar, en el primer circuito tendremos que cortocircuitar la fuente de 12 V mientras que en el segundo Circuito Tendremos que cortocircuitar la fuente de 20 V.


**Análisis Circuito 1:**
•	Hay que tener en cuenta que al suprimir la fuente de 12 V , deberemos también retirar la resistencia de 470 Ω debido a que la fuente esta en serie con dicha fuente (simulando una fuente de corriente).

![image](https://user-images.githubusercontent.com/84357979/125634235-0460abea-28e6-43c4-9ca3-c9de3dff8543.png)

Al haberse suprimido Rx=470 Ω se puede deducir que la corriente Ix=0 A debido a su ausencia en el presente circuito, mientras tanto el Voltaje de la resistencia de 820 Ω puede calcularse mediante el uso de Resistencias Equivalentes y el principio del divisor de tensión.

![analisis1](https://user-images.githubusercontent.com/84357979/125634393-3a1428df-5026-49fb-b599-ce46c07a6fc2.png)


**Análisis del Circuito 2:**

•	Al desconectar la fuente de 20 V, no es necesario mover ninguna resistencia debido a que la más próxima a la fuente está en serie con la misma (lo cual no simula ningún otro tipo de fuente)

![image](https://user-images.githubusercontent.com/84357979/125635174-95cdf87a-766d-4b3a-a721-62e530ccf6bf.png)

A continuación, aplicamos el método de análisis de mallas para poder evaluar tanto las corrientes como los voltajes que necesitemos del ejercicio.

![image](https://user-images.githubusercontent.com/84357979/125635558-cea0cb52-b1bc-4be9-9a97-1274214620b9.png)

![analisis2](https://user-images.githubusercontent.com/84357979/125635658-62250b18-b7c5-4218-807f-de544fbe4e13.png)

Finalmente Calculamos la corriente Ix y el voltaje VA del presente circuito.

![analisis3](https://user-images.githubusercontent.com/84357979/125635768-504c9506-6c30-411f-bc02-5c0afaa769e6.png)

**Corriente y Voltaje Total**

Finalmente, según el teorema de superposición procedemos a sumar o restar los resistores o voltajes que se midieron de los 2 circuitos para dar con un valor total que represente al mismo resistor dentro del circuito original.

![analisis4](https://user-images.githubusercontent.com/84357979/125635905-0e7cc8e0-1170-4f14-8750-c8eb16b8b322.png)

**Actividades de la Guia**

4.5 Verifique el cumplimiento del Teorema de Superposición y comparte los resultados obtenidos prácticamente con los obtenidos analíticamente. Realice sus conclusiones.

![analisis5](https://user-images.githubusercontent.com/84357979/125636149-3cf67ee6-2cf3-477d-97e9-44eff3d927bd.png)

![analisis6](https://user-images.githubusercontent.com/84357979/125636160-02c108c8-cb74-487a-b453-16612ba7dd1d.png)

**Calculo de Error Porcentual**

![analisis7](https://user-images.githubusercontent.com/84357979/125636392-a0d12fd6-4bff-4e80-b444-73ac80c74122.png)



**5.VIDEO**

Link del Video: https://www.youtube.com/watch?v=z7h-raDsOWU

[![Circuitos Eléctricos || Guía de Laboratorio 4|| Teorema de Superposición](https://img.youtube.com/vi/z7h-raDsOWU/0.jpg)](https://www.youtube.com/watch?v=z7h-raDsOWU)

**5. CONCLUSIONES**

* El numero de fuentes de un circuito electrico determinan cuandos sub-circuitos se deben analizar para obtener los resultados por superposicion.

* En el analisis de un circuito por superposicion se deben tener en cuenta los modelos equivalentes de una fuente de corriente o de voltaje, en esos casos la anulacion de una fuente puede significar tambien la anulacion de un elemento del circuito.

* La solucion de cada sub-circuito se puede manejar con cualquier metodo anteriormente estudiado y aplicando las Leyes de Voltaje y Corriente de Kircchoff.



**6.BIBLIOGRAFÍA**

•  Dorf, R., & Svoboda, J. (2011). Circuitos eléctricos. México: Alfaomega, https://www.mecatronicalatam.com/es/tutoriales/teoria/leyes-de-kirchhoff/

•  Robbins, A. H. (2008). Análisis de Circuitos Teoria y Practica. Santa Fe-Mexico: Cengage Learning.
