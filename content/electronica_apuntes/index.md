---
title: "Electronica Apuntes"
date: 2023-12-08T23:16:54-03:00
description: "Apuntes tomados sobre curso de electrónica básica"
---

# Módulo 1
La electrónica nace con la invención del transitor en el 1947.  
Los procesador que tienen las computadoras están basadas en tránsistores.  
Acá parte la electrónica con el desarrollo de circuitos integrado. La idea era meter la mayor cantidad de transistores para hacerlo más pequeño.

##### Ley de Moore


### Electricidad
Conjunto de fenómenos físicos causados por la existencia interacción y movimiento de cargas eléctricas (electrones).

La energía eléctrica se puede convertir en diferentes formas de energía tlaes como: Energía calórica, energía lumínica, energía mecánica, energía química.o

### Carga eléctrica
La materia está compuesta por átomos, estos átomos tienen partículas llamados protones y neutrones 

Electrones: carga negativa,  
Protones: carga positiva,  
Neutrones: no tienen carga  

Partículas con la misma carga se repelen pero partículas con signos contrarios se atraen, o sea un átomo que esté cargado más positivamente y otro átomo que esté con más electrones puede atraer, es decir, el átomo le puede robar electrones al otro que tiene de más, esto es lo que hace que este fénomeno físico la electricidad tenga importancia, el hecho de que los electrones se muevan de un lado al otro.


Los que se pueden desprender de un átomo son los electrones porque los electrones están en la corteza del átomo y son fáciles de desprenderse del átomo.

##### Materiales
Se clasifican en 3.

En estos 3 materiales los electrones de los átomos son fáciles de desprender.
##### Conductor
1. Cobre
2. Latón
3. Acero
4. Metal
5. Bronce
6. Cables
7. Aluminio

Hay varios materiales pero el más usado es el cobre.

##### Aislantes
1. Vidrio
2. Papel
3. Cerámica

Los electrones están aferrados fuertemente a sus átomos, por lo tanto, no permiten el flujo de electrones. Un ejemplo de aislante es el plástico o la madera.

##### Semiconductor
En este tipo de materias está basado toda la electrónica, son materiales por algún efecto fenómeno físico puede cambiar de aislante a conductor, ya sea la luz el calor puede hacer que estos materiales cambien de un estado al otro.
Un ejemplo: panel solar cuando le da el sol el panel produce electricidad.

#### Corriente
La cantidad de electrones que fluye por un material en un instante dado.
Como los átomos pasan de un átomo a otro, a este movimiento se le llama corriente.
La unidad de medida es el Amperio(A) y se representa con la letra "I"

#### Voltaje
Fuerza que hace que estos electrones se muevan. La medida del voltaje es el Voltio y se representa por la letra "V".

#### Resistencia
Oposición que ofrecen los materiales al ser atravesados por una corriente eléctrica.
La unidad de medida es el Ohmio. Se representa con la otra "R".

### Circuito Eléctrico
Es un conjunto de elementos conectados entre sí de tal forma que permitan el paso de la corriente eléctrica para producir algún fenómeno como la luz como el calor como el movimiento.

#### Componentes básicos de un circuito
1. Fuentes de alimentación
2. Control 
3. Carga: es el elemento que va a consumir esa corriente. En este caso sería una bombilla.
4. Cable: el conductor


#### Tipos de circuitos
##### Circuito Abierto
Si cualquier parte de la trayectoria de un circuito se abre, el fluyo de electrones se detiene.


### Durante muchos años se creía que la corriente fluía del terminal positivo al negativo.
## Pero es incorrecto.
## Cuando hay movimiento de electrones la corriente fluye del negativo hacia el positivo

##### Cortocircuito
Esto ocurre cuando la corriente que atraviesa el circuito se desvía por un camino no deseado: hace el camino más corto. A veces suceden cosas como que el cable se pela y hace contacto con otro cablecito y hace que la corriente fluya por un camino más corto.
Un cortocircuito puede causar hasta un incendio.
Cuando hay un corto circuito fluyen más electrones de la batería y los terminales se calientan cuando hay mucho fluyo de energía tienden a calentarse.


#### Ley de Ohm
Es una expresión matemática que relaciona el Voltaje, la Corriente y la Resistencia.
```equation
I=V/R  
```
Significa: La corriente es igual al voltaje dividido la resistencia.

##### El voltaje es la fuerza que empuja los electrones, la corriente es el flujo de electrones, y la resistencia es la oposición que hace un conductor al paso de la corriente.


#### Ejemplo: Un circuito tiene una resistencia de 6 ohmios y la corriente es de 2 Amperios. ¿Cuál es el voltaje de la fuente?
##### Solución
Tenemos los siguientes datos R=6 omega, I=2 A y V=??

Según la ley de Ohm V=I\*R, entonces reemplazando V=2A\*6 omega, por lo tanto, el voltaje del circuito es de 12V.

#### Potencia eléctrica
El trabajo que hace una fuente de alimentación para producir un voltaje que a la vez genera una corriente eléctrica.
Hay un 2% de la energía que se pierde en el cable.
Su medida es Watts (W) y se representa con la letra "P".

#### Ley de Watt
P=V\*I

##### Ejemplo
Un circuito tiene un Voltaje de 12V y la corriente que circula por la carga es de 2 amperios, cual es la potencia entregada por la fuente de voltaje y absorbida por la caga?

#### Solucion:

Según la ley de watt P=V\*I entonces P=12V\*2A=24W por lo tnato, la potencia entregada por la fuente a la carga es de 24W.


##### Circuito Serie
Las cargas se conectan una a continuación de la otra, formando una cadena, de modo que la corriente que circula por un elemento es la misma para todos.
#### Además el voltaje de la fuente se divide en número de cargas.

Carga: es el elemento que va a consumir esa corriente. En este caso sería una bombilla.

La corriente en el circuito en serie es la misma que pasa por todas las bombillas, pero el voltaje se divide.
Por ejemplo si tengo un circuito en serie de una pila conectada a 3 bombillas, si tengo 6 voltios a cada bombilla le va a llegar 2 voltios.

##### En el caso de sistemas de alarma, hay algunos instaladores dicen que pueden conectar dos sirenas en serie, NO!.
Porque la sirena funciona a 110 Voltios, si conectás en serie le llegará 55 voltios a una y 55 a la otra.


#### Circuito paralelo

Las cargas se conectan a la fuente por los mismos puntos de los extremos. En este circuito el voltaje es el mismo para todas las cargas, pero la corriente se divide entre todas las cargas.

### Propiedades de este circuito:
El voltaje es el mismo para todos los componentes, pero la corriente que sale se divide entre los componentes. Si tenés 6 amperios se divide por cada bombilla conectada.



# Módulo 1 (segunda parte)
Watt es sinónimo de vatio.  
Comenzaremos con una lámpara de 100W vatios, conectado a un toma de 110 voltios. 
Para saber cuanta corriente consume esa bombilla. Tenemos **la ley de Watt**.
La corriente será igual a la potencia sobre el voltaje y la potencia son 100 vatios
y el voltaje son 110 voltios.
```
I=P/V = 100W/110V => I = 0,9 Amper
```

Nota: Hay algunos bombillos que producen la misma luz que uno de 100 de vatios y trabajan a menos vatián??
Por ejemplo un bombillo led de 15 vatios alumbra lo mismo que un bombillo de uno de 100 vatios de las lámparas incandecentes antiguas.

```
I=P/V = 15W/110V => I= 0.1 Amper
```
A medida que la energía que consume dismuye vamos a tener menos corriente.

### Por ejemplo planchas:
Mi plancha consume 1000 vatios, la corriente que consumirá esa plancha será potencia sobre el voltaje.

```
I=P/V => 100 Vatios/110V => I= 9 amperes
```

Por ejemplo los televisores antiguos consumian 400, 500 vatios hoy en día las pantallas leds pueden consumir 70 vatios, no llegan ni a 100 vatios.


#### Circuito en serie / paralelo
![circuito_paralelo_en_serie.png](/electronica/circuito_paralelo_en_serie.png)
en este gráfico hay dos bombillas conectadas en serie y otras dos conectadas en paralelo
#### Por qué están conectados en paralelos?
Los terminales de los bombillos estan conectados entre sí

Pero a la vez los dos que están en serie están conectados en serie con los otros dos en paralelo.

#### en cuanto a la corriente
recuenden que si están en serie la corriente es la misma pero cuando llega al circuito en paralelo la corriente se divide y cuando sale del circuito paralelo la corriente que sale es la misma que entró antes de ser dividida.
#### en cuanto al voltaje
se divide cuando es un circuito en serie pero no cuando es un circuito paralelo


##### Corriente alterna y continua
### Corriente Continua (CC o DC)
Siempre es constante y circula siempre en la misma dirección.
Por ejemplo una batería: si mido a través del tiempo tiene 1.5V dos segundos después tengo 1.5V y dos segundos después mide lo mismo. Sin embargo si la conectás a una bombilla será constante pero llegará a un momento que empezará a descargarse. Pero suponiendo que no se le acaba la energía el VOLTAJE es constante.

#### Corriente Alterna (AC o CA)
Cambia alternativamente, circulando primero en una dirección y luego en la dirección contraria. El voltaje en este tipo de fuentes, también cambia de polaridad a lo largo del tiempo y su forma es senoidal.

Una parte de la onda una parte es positiva y otra parte es negativa.

#### Como se produce la corriente alterna?
Esto se produce con un generador que no es más que unos imánes de cada lado.
El imán de un lado tiene una carga contraria al imán del otro lado y en el medio hay una bobina, que girará entre medio de los dos imánes y se produce un flujo de electrones o una corriente a través del alambre.


Cuando el alambre está en posición vertical está en 0 la corriente que fluye por el alambre, pero cuando el alambre empieza a girar de forma horizontal empieza a subir el voltaje hasta que llega a estar completamente horizontal ahí está en el máximo, cuando sigue girando vuelve y baja hasta que llega a 0 y sigue girando en el mismo sentido y se incrementa el voltaje hasta a estar otra vez horizontal el alambre, la bobina del alambre, vuelve y va a 0 cuando se pone otra vez de forma vertical y así consecutivamente va girando va girando va girando.


### Como se produce?
En colombia hay 3 formas: hidroeléctricas, aerogeneradores (producen demasiado poco), y las termoeléctricas (quemar carbón para mover una turbina con la presión de los gases y así se produce energía)
Hay algunas fuentes de energía que son más contaminantes que otras.
Los paneles solares tienen una ineficiencia GIGANTE, se pierde el 80% de la energía sólo transforma el 20%. Y para producir la energía que puede producir una hidroeléctrica con paneles solares tienen que cubrirse áreas MUY GRANDES.

##### Nikola Tesla inventó el generador de corriente alterna
El inventó TODO el sistema. Todo fue inventado por Nikola Tesla. Desde como se genera y como llega a nuestra casa, los transformadores en donde va la corriente, la forma en como llega a la casa las cuerdas la transmisión. Alrededor de hace más de 100 años.
El generador fue patentado en 1981 

Todos el motores de corrientes alterna fueron inventados por Nikola Tesla. Un auto electrico funciona a baterias pero tiene un motor de corriente alterna.


### Conceptos de ondas senoidal
La onda de la corriente alterna tiene una parte positiva y otra negativa.
O una parte está con una polaridad y en la otra tiene otra polaridad.
Este patrón se lo llama ciclo.


**período: tiempo que demora el ciclo.**
**frecuencia: número de ciclos de una onda de que se dan en 1 segundo.**
Se mide en Hertz. Cantidad de ciclos = cantidad de herts.

La frecuencia de la onda que llega a nuestras casas es de 60 hertz, es decir la onda da 60 ciclos en 1 segundo. En europa manejan 50 hertz la frecuencia de la onda alterna es de 50 hertz. En America desde Canadá hasta Argentina es de 60 hertz.

### En que me influye esto?
Se estandariza con los generadores, los generadores funcionan con esa frecuencia.
Nosotros usamos esa frecuencia porque estamos influenciado por estados unidos. 
Nikola Tesla decidió que la frecuencia ideal era 60 hertz. 

Las corrientes funcionan iguales. El único problema con esto es cuando se diseñan circuitos, porque hay que tratar esta onda para que funcione a 50 hertz. 
#### Hay personas que no saben y se llevan un cargador de celular a Europa y el cargador se le daña o se le daña el celular.

#### Como funciona el cargador?
Tratan esta onda alterna para que me produzca un voltaje continuo y me pueda cargar el celular, pero como son diferentes las frecuencias puede dañarlo.
Además los voltajes también son diferentes, en América se maneja 110 voltios en Europa se manejan a 220 voltios.

#### En europa y america los Voltajes y frecuencias son diferentes por eso los cargadores de europa no funcionan.


## Multímetro
Es un instrumento que sirve para medir diferentes magnitudes eléctricas. Entre las que se encuentran: Voltaje, Corriente y Resistencia.

Los multímetros no miden potencia, se miden con patímetro los contadores miden la potencia que se consume en la casa.
#### PERO recuerden que si nosotros tenemos el voltaje y la corriente podemos encontrar la pontencia

![multimetro](/electronica/multimetro.png)
En la parte de arriba a la izquierda vemos una V con una línea constante y una línea punteada, esto quiere decir: voltaje continuo.
En la parte de arriba a la derecha vemos una V con una línea constante y una línea punteada, esto quiere decir:  voltaje alterno.

Si vamos a medir el voltaje en una batería utilizamos voltaje continuo (izquierda).
Si vamos a medir el voltaje en la toma de la casa medimos con el de la derecha.

Luego vemos una A con una línea continua esto es corriente continua.
Algunos multímetros sólo traen para medir corriente continua otros traen corriente continua y alterna.

Y también tenemos el símbolo Omega que esto quiere decir que nos sirve para medir RESISTENCIA. 2000k = 2000 kilo omions

Algunos multímetros tienen más escalas:
200m = 200 milivoltios
2000m = 2000 milivoltios
20 = 20 voltios
200 = 200 voltios
1000 = 1000 voltios

200 voltios de corriente directa es una corriente muy exagerada no se consigue, lo máximo que se consigue en amplificadores de sonido 24, 48 voltios , pero el resto el voltaje en corriente continua son pequeños.

En corriente alterna hay 110voltios en la casa y 220voltios y de ahí se divide a 110.
voltios.


Luego tenemos para medir continuidad y diodo, ese nos sirve para verificar que un cable no esté roto ni quebrado.
También al lado tenemos para medir temperatura con una zonda.
Y al lado tiene un hFe es para medir un valor de un transistor.

Luego tenes 3 borneras en donde se conectan unos cables.


En la primera dice 10 A, esto quiere decir 10 amperios de corriente continua, entonces si yo quiero medir corriente continua tengo que meter la punta ahí.

Abajo nos dice: V (omega) mA (miliamperios) es decir yo puedo medir corriente en miliamperios en la 2da. 

#### Pero si quiero medir voltaje y resistencia  tengo que poner en la bornera 2.
Y tengo una bornera **común** entonces yo tengo dos cables uno rojo y otro negro , el negro va en el común y el rojo se cambia de acuerdo al tipo de corriente o de medida. 
### Lo que más se usa es voltaje y resistencia  y de vez en cuando corriente.


## Medir voltaje
![medir_voltaje](/electronica/medir_voltaje.png)
Para este caso la bombilla es igual que el voltaje de la batería, si tuviera otra bombilla en serie entonces puedo cada uno de las bombillas.

En el COM viene la punta negra y en donde dice V (omega) que es para medir resistencia coloco la punta roja y seleccciono el tipo de corriente o el tipo de medida que voy a hacer, ESTO TENGO QUE HACER ANTES DE CONECTARLE ENERGÍA AL CIRCUITO.
Una vez que está conectado ahí si mido el voltaje sobre el componente que voy a hacer la medida.


Tenemos dos tipos de ondas voltaje continuo y alterno.
Si voy a medir voltaje alterno = derecha superior
Si voy a medir voltaje continuo = izquierda superior

## Medir corriente 
![medir corriente](/electronica/medir_corriente.png)
Se hace en serie con el circuito. No importa la polaridad.
Lo único que va a modificar es el signo. Lo que importa el valor, si te da menos indica que tenés las puntas invertidas pero no importa.

Seleccioná para medir corriente y 
la punta roja cambia a la otra bornera

si yo no sé que corriente voy a medir me voy a la escala más grande, que sería 10 amperios, mido si me da menos simplemente voy ajustando la escala.

Internamente los multímetros tienen un fusible para medir corriente, si la corriente se pasa del valor sólo se quema el fusible pero el multímetro se proteje. Eso pasa cuando no se conoce la medida de la corriente aproximadamente.
Entonces se daña el fusible y hay que cambiarlo.

## Medir resistencia
Nos puede dar valores erróneos. Hay que sacarlo del circuito y desconectar la energía, y desconectar el componente. Porque si el componente queda conectado al circuito también me va a medir la resistencia de la batería que está conectado a la bombilla. Aparte la resistencia no se puede medir con la corriente.

Para medir resistencia el multímetro mandar una corriente al componente y de acuerdo a esa corriente hace un calculo. El multímetro se convierte en una fuente de voltaje y de acuerdo a la corriente que fluye por el multímetro el hace el cálculo.


Todo esto está explicado con una demostración en el siguiente video en el minuto 54:48: [https://youtube.com/watch?v=xXyYZK2Qx94](https://youtube.com/watch?v=xXyYZK2Qx94)

### Precauciones con el multímetro
1. Mantenerlo siempre apagado
2. Colocarle unas buenas baterias porque las baterias chinas se sulfatan muy rápido y el ácido de las baterias dañan los componentes.
3. Si se lo guarda en caja de herramientas, protéjalo dentro de un estuche.
4. Antes de cualquier medición verifica el selector, el rango, y la perilla.
5. Cuando cambiás de una posición a otra, o el rango del multímetro, **no hacerlo con el multímetro conectado**.
6. Si no conocés el valor de lo que vas a medir siempre utilizá la escala más alta.

Hay una pinza voltiamperimetrica esta diseñada para medir corriente. No viene para escalas pequeñas. Y sólo sirve para corriente alterna. Utiliza el mismo principio del generador cuando yo a una corriente alterna le coloco la pinza ese movimiento de esa onda senosoidal me produce un campo magnetico , la pinza tiene una especie de iman que me va a detectar ese campo magnetico que se está moviendo en esa onda y producirá una medida.


# Módulo 2
Pinza voltiamperimétrica se usa par trabjar con grandes voltajes.
Si tengo un cable meto la punta en uno de los cables en la pinza y me lo va a medir no necesito conectar cables. 

#### Simbología
![simbología](/electronica/simbologia_1.png)
![simbología](/electronica/simbologia_2.png)
![simbología](/electronica/simbologia_3.png)
Todos los componentes de la electrónica tienen un símbolo
1. Resistencia o resistor parace una onda en forma de cierra. No tiene polaridad.
Letra en esquema: R
2. LDR: Foto resistencia. No tiene polaridad.
Cuando le da la luz cambia la resistencia en función a la luz.
3. Pot: Potenciometro: es una resistencia también variable, en las patitas de los extremos está la resistencia y la de la mitad varía para un lado o para el otro.
4. Condensador cerámico: 
5. Condensador o capacitor electrolítico:
La difererencia entre dos los es que el condensador cerámico NO tiene polaridad y el electrolítico sí tiene.
6. Interruptor: hay muchos tipos de interruptores dependiendo a si tienen un contacto abierto y otro cerrado.
Interruptor deslizante
Interruptor codillo
7. Pulsador
8. Relé: lo que se vé en la imágen es una bobina cuando esa bobina se energiza el mueve este conacto que está al lado, de un lado es cerrado y el otro componente es abierto.
9. Transformador: Recibe un voltaje y saca otro voltaje, lo puede elevar o pued bajarlo. Trabaja sobre con corriente alterna.
Los transformadores que hay en las centrales hidroeléctricas ellos sacan un voltaje por ejemplo 1000 voltios y eso lo elevan a 13.000 voltios eso es lo que transportan las líneas en las calles los que están más alto. Elevan los voltios para que pueda llegar a las casas a larga distancia.
10. Diodo: 1er componente en donde nace la electronica junto con el transitor.
11. Diodo led: especie de bombillo o iluminación, las lámparas incandecentes están prohibidas. Los florescentes también están desapareciendo porque el precio.
12. Transistor: de baja potencia y de potencia, con el transistor se hace los circuitos integrados. 
13. Circuito integrado
14. Batería

### Diagramas esquemáticos
Los driagramas esquemáticos son la forma universal para representar circuitos electrónicos.

Los diodos leds tienen que tener una especificación de cuantos milímetros es, si es de 1 vatio si es de 0,5 vatio si es de 3mm o 5mm
De 1 vatio hacia abajo hacia abajo se mide en milímetros y de 1 vatio hacia adelante se especifíca por el matial??

En el primer gráfico tiene una bateria pero en el 2do no.
Simplemente yo puedo deicir que todos los componentes que se conectan al positivo deben ir como en una forma de BUS, entonces puedo colocar un palito y una bolita +3.7Voltios.
