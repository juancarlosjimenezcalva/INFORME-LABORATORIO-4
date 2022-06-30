# INFORME LABORATORIO 4

## OBJETIVOS

### OBJETIVO GENERAL

Resolver el circuito eléctrico por medio de su análisis y aplicación del Teorema de Superposición con la finalidad de obtener los valores solicitados (Va e Ix)

### OBJETIVOS ESPECIFICOS

-	Elaborar el circuito eléctrico mixto en el simulador Tinkercad y físico.
-	Aplicar el Teorema de Superposición en el circuito eléctrico elaborado para encontrar los valores Va e Ix

## MARCO TEÓRICO

El teorema de superposición solo se aplica en circuitos eléctricos lineales, por tanto.

### Circuito eléctrico lineal

Un circuito eléctrico lineal es cuando no existe ningún cambio en los valores de los componentes electrónicos, considerándolo todo aquel que se encuentre exclusivamente por componentes en los cuales la amplitud de la corriente que circula por estos es directamente proporcional a la amplitud de la tensión que existe en sus terminales.

### Características de un circuito eléctrico lineal

Debe cumplir con las propiedades de homogeneidad y aditiva, es decir, que cualquier variación que se haga en la entrada del circuito se debe repetir en la respuesta del mismo.

Está formado por elementos de tipo lineal, en los cuales la corriente que los atraviesa es directamente proporcional a la diferencia de tensión que se establece entre sus terminales.

Debe existir una relación proporcional lineal entre la causa y efecto del circuito. (Xnomind, 2020)

En la figura 1, se observa como es un circuito eléctrico lineal.

![image](https://user-images.githubusercontent.com/105565683/176576054-9d558ece-43f3-4779-8fff-ed12c4cec144.png)
Figura 1 – Circuito eléctrico lineal

### Teorema de Superposición

El método de superposición es de gran utilidad para determinar los valores en un circuito con múltiples fuentes dejando una fuente a la vez y reemplazando las demás fuentes por sus resistencias internas.

Por tanto, el teorema de superposición postula que:

Según Floyd, en cualquier rama dada de un circuito con múltiples fuentes, la corriente puede calcularse al determinar en esa rama particular las corrientes producidas por cada fuente que actúa sola, con todas las demás fuentes reemplazadas por sus resistencias internas. La corriente total en la rama es la suma algebraica de las corrientes individuales presentes en dicha rama. 

Los pasos para aplicar el método de superposición son:

#### Paso 1

Dejar una fuente de voltaje (o de corriente) a la vez en el circuito y reemplazar cada una de las demás fuentes de voltaje (o de corriente) con su resistencia interna. Para fuentes ideales, un corto representa resistencia interna de cero y una abertura representa resistencia interna infinita.

#### Paso 2

Determinar la corriente (o el voltaje) particular que se desea justo como si hubiera sólo una fuente en el circuito.

#### Paso 3

Tomar la siguiente fuente que haya en el circuito y repetir los pasos 1 y 2. Hacer esto con cada una de las fuentes.

#### Paso 4

Sumar algebraicamente las corrientes producidas por cada fuente individual para encontrar la corriente real en una rama dada. (Si las corrientes están en la misma dirección, se suman. Si están en direcciones opuestas, se restan y la dirección de la corriente resultante será la misma que la presentada por la cantidad más grande de las cantidades originales.) Una vez determinada la corriente, ya se puede calcular el voltaje mediante la ley de Ohm. (Floyd, 2007)

Con estos pasos, el Teorema de Superposición nos ayuda a encontrar:

-	Valores de tensión, en un nodo de un circuito, que tiene más de una fuente independiente.
-	Valores de corriente, en un circuito con más de una fuente independiente.

## EXPLICACIÓN DEL PROCEDIMIENTO

### ELABORACIÓN DEL CIRCUITO

#### MATERIALES

![image](https://user-images.githubusercontent.com/105565683/176578002-83fb5c00-8977-4024-bb5a-080be24c5f15.png)

![image](https://user-images.githubusercontent.com/105565683/176578063-21998df8-f7f8-4868-b3d8-7310ac941f91.png)

#### PROCESO

1.	Ubicamos las resistencias como se muestra en el esquema del circuito.

![image](https://user-images.githubusercontent.com/105565683/176578571-db8ed61c-afad-4681-8651-24b4ea2239fe.png)

2.	Conectar las resistencias por medio de los cables de acuerdo con el esquema, que cumpla con el circuito mixto.

![image](https://user-images.githubusercontent.com/105565683/176578736-d1704f2e-f2fc-4294-91b1-1e5a71223457.png)

3.	Conectamos las fuentes de voltaje C.D. (en caso de simulador), de acuerdo al esquema, en los polos positivo y negativo de las resistencias.

![image](https://user-images.githubusercontent.com/105565683/176579039-43d51a84-f76b-4e8d-af4d-277659cf7df8.png)

#### CIRCUITO FISICO

Siguiendo el mismo proceso, armamos el circuito físico:

![image](https://user-images.githubusercontent.com/105565683/176579178-9ba5ec4b-202b-4c27-b90e-3809f81c90b3.png)

### MÉTODO DE SUPERPOSICIÓN

![image](https://user-images.githubusercontent.com/105565683/176579398-0656fb52-24ac-4115-8a5b-84f0128d94a9.png)

![image](https://user-images.githubusercontent.com/105565683/176579442-52624b17-0695-4d73-be84-d63223ea047c.png)

![image](https://user-images.githubusercontent.com/105565683/176579492-e562dbea-fe5b-4b89-b822-eb07caf3cf30.png)

![image](https://user-images.githubusercontent.com/105565683/176579513-3a42723d-c018-407b-b797-97709f112edd.png)

![image](https://user-images.githubusercontent.com/105565683/176579545-e62a19c6-f42c-4f6f-b737-04c6f48b8058.png)

![image](https://user-images.githubusercontent.com/105565683/176579561-bdaec4ca-2beb-408e-9956-247310fe81fd.png)

![image](https://user-images.githubusercontent.com/105565683/176579590-08f7b689-29a0-451d-bd05-d22a5c06a961.png)

![image](https://user-images.githubusercontent.com/105565683/176579632-da083505-2263-4dfe-adf0-0e9f10ee68ac.png)

![image](https://user-images.githubusercontent.com/105565683/176579652-4fe94527-8144-4250-95f5-2cc8d206dbfb.png)

## RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

### MEDICIONES DE VOLTAJE Y CORRIENTE

1. Medir el voltaje en VA del circuito con el multímetro.

![image](https://user-images.githubusercontent.com/105565683/176580047-1e8a2784-5cbb-4d10-b059-9bbf8b2727ac.png)

2. Medir la corriente en Ix del circuito con el multímetro.

![image](https://user-images.githubusercontent.com/105565683/176581062-fdcfb65c-49ce-466f-a3f6-090d85c5847c.png)

3. Comparar los resultados obtenidos de voltaje y corriente, en VA Y Ix.

Para el circuito físico se utilizaron baterías y pilas para las fuentes de voltaje, siendo de 6 V y 9 V, por ende, existirá una ligera diferencia entre los resultados, también se tomarán en cuenta los resultados obtenidos en ambos circuitos del grupo.



### RESULTADOS

## VIDEO



## CONCLUSIONES

-	Se utilizó un análisis y comprensión adecuado del esquema proporcionado para la elaboración del circuito, de tal forma que respete tanto la polaridad del voltaje como el sentido de la corriente.
-	El Teorema de Superposición es de gran utilidad para el análisis y cálculo de valores en circuitos que tengan dos o más fuentes, debido que, al aplicar dicho teorema, su resolución es más sencilla.

## BIBLIOGRAFÍA

Floyd, T. (2007). Principios de circuitos eléctricos. Octava edición. México: Pearson Educación.

Xnomind. (18 de Enero de 2020). Teorema. Obtenido de https://www.teorema.top/teorema-de-superposicion/
