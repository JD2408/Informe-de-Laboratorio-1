# Informe de Laboratorio 1
### Fundamento de circuitos Eléctricos 
#### Ing. Darwin Omar Alulema Flores
#### Integrantes: Padilla Kevin, Samueza David, Avilés Kevin
 
 ## 1. OBJETIVOS
***Objetivo General***

- Explicar y demostrar experimentalmente la Ley de Kirchhoff de Voltajes y la Ley de
Kirchhoff de Corrientes.

 ***Objetivos Específicos***
- Utilizar de forma adecuada el software de simulaciòn (Tinkercad), teniendo encuenta el codigo de colores para los cabales, el orden de los componentes y la estetica de los circuitos.
- Comparar la diferencia que existe entre los valores medidos con los valores calculados, atraves del calculo de error.
- Aplicar los conocimientos para realizar correctamente las  medidas con el multimetro, diferenciando entre paralelo y serie.

## 2. MARCO TEÓRICO
![Ley de Ohm](https://user-images.githubusercontent.com/93794279/141377003-72a0d14b-321a-4e29-ae8c-9a9fa71518fe.png)
![Diagrama en blanco](https://user-images.githubusercontent.com/93794279/141377036-d6c7cd48-c0b8-41dd-a021-cf236a355833.png)
![leyes](https://user-images.githubusercontent.com/93794279/141381476-3df8411d-99f1-402a-9b93-6cc6aaa9d255.png)

## 3. EXPLICACIÓN DEL PROCEDIMIENTO
*Materiales*
1. Tener una cuenta en la plataforma Tinkercad

Debido a la pandemia no podemos realizar el laboratorio con equipo fisico, por eso hacemos uso de esta plataforma, dentro de esta necesitaremos traer de la biblioteca los siguientes componentes:
- Suministro de energía
- Protoboard
- Resistencia
- Multímetro
2. Calculadora Básica

*Procedimiento Experimental*

1. Crear una nuevo entorno 2D en tinterkad.

![1](https://user-images.githubusercontent.com/93794279/141382346-0c75dec9-d713-419f-a017-0bab941f88e0.PNG)

2. Observar y analizar como es el circuito que se va a armar.

![3](https://user-images.githubusercontent.com/93794279/141382688-402a85d8-c65b-4461-b8bf-49e969e9bdd4.PNG)

3. Escoger el codigo de colores correcto para cada resistencia.

![4](https://user-images.githubusercontent.com/93794279/141382819-57b13589-ea8c-41a7-a30b-7b025c5816f7.PNG)

4. Armar el circuito, taer el suministro de energía y configurarlo para 10 V.

![5](https://user-images.githubusercontent.com/93794279/141382948-9da3ced8-95a9-4eb6-89e8-461c11389d4b.PNG)

5. Realizar las mediciones correctas con el multímetro, tener en cuenta si es voltaje, amperaje o resistencia.

**Medicion de voltaje**


![6](https://user-images.githubusercontent.com/93794279/141383194-19738490-949c-4d05-ac8b-c89000223a7a.PNG)


**Medicion de resistencia**


![7](https://user-images.githubusercontent.com/93794279/141383412-6d6bfdee-9c29-43c5-bccc-facaec58f71c.PNG)


**Medicion de amperaje**


![8](https://user-images.githubusercontent.com/93794279/141383579-88a62a26-f2a4-4572-85cd-cc5a0e00ca6a.PNG)


### Tabla 1

*Procedimiento del cálculo*

Este procedimiento se debe hacer en 2 subprocesos

- Cálculo de la Resistencia Equivalante

![Diagrama en blanco](https://user-images.githubusercontent.com/93794279/141407909-0b0b1a56-3fed-48c2-b580-0b9ff3d815ca.png)

   1. Para encontrara Ra se sumara la R3 y R4, ya que estan en serie.

![2](https://user-images.githubusercontent.com/93794279/141407943-58048c76-f24b-4870-9e5f-145ea2fc4569.PNG)

   
   2. Cálculamos la resistencia Rb, teniendo encuenta que R2 y Ra son paralelas.

![3](https://user-images.githubusercontent.com/93794279/141407974-ed562b28-2712-4fd5-8899-4c2ac703270f.PNG)
   
   3. Finalmente tenemos Req si sumamos las resitencias R1, Rb Y R5, que estan en serie.

![4](https://user-images.githubusercontent.com/93794279/141408035-acf32cbb-635b-4df2-bba7-ed28120bca76.PNG)
   
   4. Encontramos la resistencia total aplicando ley de Ohm.

![i](https://user-images.githubusercontent.com/93794279/141408106-9d2cd9f3-a1b3-4817-914c-6cd2191708c3.PNG)
  
  
- Cálculo de los voltajes y corrientes de cada resistencia.
  
  1. Empezare a calcular partiendo desde el 3 subcircuito, entonces se sabe que la corriente en serie se mantiene, por lo que es la misma en las resistencias R1,Rb Y R5. Teniendo en cuenta ese dato y al usar la ley de Ohm, se puede encontrar fácilmente los voltajes de cada resistencia.

![1 1](https://user-images.githubusercontent.com/93794279/141408988-66591014-1459-4736-8006-6bf1ba65e1e4.PNG)


  2. En el subcircuito 2, se abre la Rb y se divide en R2 y Ra, como estan en paralelo el voltaje se mantiene, entonces se encontrara la intensidad de corriente en el R2 y Ra aplicando ley de Ohm.

![2](https://user-images.githubusercontent.com/93794279/141408257-64bad28a-3895-4b25-badd-68be9b21d9f7.PNG)



  3. A continuación la Ra se divide en R3 y R4, estando estas en serie, dando a entender que la intensidad sera la misma, para finalizar calculamos el valor de volataje en R3 y R4.

![3](https://user-images.githubusercontent.com/93794279/141408279-6a70baef-a74b-4d8e-b487-595304d707cd.PNG)

### Tabla 2
 Aquí se deberá aplicar la LVK, la cual nos establece que si sumamos las caidas del voltaje de resultado obtendremos el voltaje total, entonces se debera escoger las direfentes trayectorias en las que se aplicara la ley.
 
 
 **Trayectoria 1**

 
 
 **Trayectoria 2**
 
 
 
 **Trayectoria 3**
 
 
 
 
 ### Tabla 3
 
 Aquí se deberá aplicar la LCK, la cual nos establece que si sumamos las intensidades de corriente que entran a un nodo debe ser igual a la suma de intensidades de corriente que salen, entonces se debera escoger las direfentes nodos, ademas de eso considerar la dirección de corriente en el circuito. En este circuito existen 2 nodos importantes y 3 nodos irrelevantes.
 
**Nodo 1**

Este es un nodo importante, surge de la interección entre el R1  como corrientes de entrada  ;  R3 y R1 como corriente de salida.

**Nodo 2**

Este es un nodo irrelevante, ya que solo tiene un corriente de entrada y una de salida, en este caso la corriente de R3 y la de R4.

**Nodo 3**

Nodo importante. Ingresa la intensidad de R4 y R2 y  se obtine la intensidad de R5.

**Nodo 4**

Nodo irrelevante. Ingeresa la corriente total y sale la corriente de R1.

**Nodo 5**

Nodo irrelevante. Ingeresa la corriente de R5 y sale a corriente total .

## 4. RESPUESTA A INTERROGANTES Y CÀLCULO DEL ERROR

***Tabla 1***

![Primera tabla](https://user-images.githubusercontent.com/93794279/141390004-aeadd126-aa7f-4d41-81de-5e08692ce932.png)


***Tabla 2***

![Tabla-2](https://user-images.githubusercontent.com/93794279/141391353-4692e866-5b2c-4484-8291-0b29d8037b74.png)


***Tabla 3***

![Tabla-3](https://user-images.githubusercontent.com/93794279/141391516-fd86ae71-0241-4edb-ae80-02aa1c41b21c.png)


***Cálculo de Error***

## 5. VIDEO



## 6. CONCLUSIONES

- Se puede decir qeu los valores de corriente y voltaje determinados por leyes de Kirchhoff son muy aproximados a los valores experimentales, con errores menores al 10% en su mayoría.
- Se concluyó que Tinkercad es un software que nos permite realizar simulaciones de circuitos en 2D muy parecidos a la vida real, es una plataforma perfecta para principiantes en la creacion de circuitos.
- Se ratifico que las tecnicas correctas de  mediciones para el voltaje y la resitencia son en paralelo, mientras que las de intensidad de corriente son en serie
- En base a los resultados obtenidos se puede concluir que por lo menos en circuitos pequeños como este, los  resultados medidos son casi exactos a los calculados.

## 7. BIBLIOGRAFÍA

1. Las leyes de Kirchhoff (artículo). (n.d.). Khanacademy.Org. Retrieved November 12, 2021, from https://es.khanacademy.org/science/physics/circuits-topic/circuits-resistance/a/ee-kirchhoffs-laws

2. Fluke. (2016, October 31). ¿Qué es la ley de Ohm? Fluke.Com. https://www.fluke.com/es-ec/informacion/blog/electrica/que-es-la-ley-de-ohmç

3. Nilsson, J. W., & Riedel, S. A. (2006). Circuitos electricos (Vuelapluma, Trans.; 7th ed.). Pearson Educacion.




