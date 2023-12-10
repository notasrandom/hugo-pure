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
![sin bateria positivo negativo](/electronica/sin_bateria_positivo_negativo.png)
Simplemente yo puedo deicir que todos los componentes que se conectan al positivo deben ir como en una forma de BUS, entonces puedo colocar un palito y una bolita +3.7Voltios.

En los diagramas tengo que tener dos representaciones una es la parte simbólica, pero en cada componente yo tengo que una representacion que es como el listado. Si yo tengo dos resistencias tengo que saber el valor de cada una.

#### Características
Los componentes se representan por un símbolo
Las conexiones se representan mediantes líneas rectas
Para indicar una conexión entre líneas, se dibuja un punto
Para indicar dos líneas no conectadas entre sí, se coloca un semicírculo.
Los componentes se identifican con símbolos alfanuméricos.
Los diagramas deben ir acompañados con el listado de componentes.

A veces se cloca el número pero no la magnitud.
Por ejemplo en los condenzadores que tienen 22 microFaradios


#### Protoboard
Casi todos tienen la misma configuración.
Los puntos que van de forma horizontal van conectados y los que van de forma vertical son los buses también van unidos todos desde el inicio hasta el final.
En la mitad hay una separación crea una separacion entre los dos grupos de columnas.

El protoboard no es un componente electronico que se coloque en un diagrama.
Se usa el protoboard porque no se necesita hacer un circuito en una tarjeta y soldarlo. Antes de montar un circuito podés probarlo en la protoboard.

Por ejemplo quiero probar el sistema que activa un relevo puedo usar un protoboard y luego hace el circuito, también es fácil cambiar si es que un componente deja de funcionar.

#### armado
para armar un circuito en el protoboard solo se debe insertar los componentes electrónicos a utilizar verificando su diagrama de conexión, después conectar los puntos distantes de los componentes utilizando cables finos como los del cable UTP o cable multipar.

![Positivo Negativo en la protoboard](/electronica/positivo_negativo.png)
En la imágen el positivo está en el lado del cable rojo y el negativo en el cable negro y hay un cable que extiende el bus negativo a la parte baja del otro bus de la protoboard que es negativo, entonces directamente puedo conectar los componentes en la parte inferior. Esa es la forma de poner negativo en dos lados. También se puede hacer lo mismo con el positivo.

### Precauciones
1. Tenga a mano todos los componentes para armar el circuito porque a veces te falta algo y cuando volvés ya no te acordás el montaje que hiciste. Anotalo.
2. No corte demasiado los componentes (las patitas). 
3. No conecte componentes que produzcan calor.
El protoboard es de plástico tiene el contacto metálico pero la cubierta es de plástico.
4. No conecte cables o componentes cuyos terminales tengan un diámetro exagerado.
Cuando el diametro del cable es muy grueso se dabará el orificio del componente y el concacto si le meto un cable más grueso se va a abrir y se va a arruinar.
5. No monte circuitos que utilicen corriente alterna con voltajes altos.
Porque el aislamiento que tiene el protoboard no funcionaría si el voltaje fuese muy alto.


Hay circuitos que funcionan a 110voltios.
Los sistemas de control de los motores que son de 110 o que son de 220, lo que hacen es tomar la onda alterna la manipulan y luego se la envían al motor, entonces esos circuitos no es recomendable montarla en protoboard porque trabajan con voltajes muy altos. 

![/electronica/circuito_p.png](/electronica/circuito_p.png)
![/electronica/circuito.png](/electronica/circuito_protoboard.png)
### Que hace el circuito?
Pongo el dedo sobre el LDR y se prende el LED.
El positivo es la primera linea (está marcado con un signo más)
El negativo es la segunda linea (está marcado con un signo menos)


En lugar del LED puedo colocar un relevo y hacer que las luces de la calle se prendan cuando cae la noche.

##### Hay que tener siempre el consumo de CORRIENTE para saber que corriente tiene que tener la batería.

### Clasificación de los componentes electrónicos
#### Pasivos
no le aportan nada, en el sentido de que no amplifican la señal, simplemente funcionan oponíendose al paso de la corriente o al paso del voltaje. Son pérdidas.
1. Resistor o resistencia: Componentes pasitvos, le restan a la corriente.
Recuerden ley de ohm: la corriente es igual al voltaje sobre la resistencia. Entre más resistencia menos corriente, el voltaje es igual se resisiste a la corriente.

#### Tenemos dos tipos:
1. Resistencias fijas
2. Resistencias variables: como por ejemplo la fotoresistencia cambia su resistencia con la luz.
![/electonica/supercial.png](/electronica/supercial.png)
##### Tiene un código de colores, el más usado es el código de 4 colores 
Hay una resistencia de precisión se utiliza para equipos muy sofisticados.
![colores resistencia](/electronica/resistencia_colores.png)
El multiplicador es el número que le multiplo a los dos primeros.
### La cuarta banda: Tolerancia
Ese valor puede ser un poquito para arriba o un poquito para abajo.
Puede variar hacia arriba o hacia abajo (es el margen de error) 5% dorado 10% plateado.

#### Electromecánicos
Pueden ser componentes que necesiten una acción mecánica externa o interna.
Externa: alguien necesita meterle mano
Interna: se hace desde el circuito.
#### Activo
nos pueden dar amplificacion por ejemplo

### montaje
montaje normal: se inserta en el circuito y lo sueldo por el otro lado 
pero hay otros componentes que se colocan superficialmente sobre las tarjetas ese tipo de componente son de montaje superficial.
1. Montaje de insercción también conocido como componentes trujol
2. Montaje superficial componentes SMD


### Codificación de resistencias
Una resistencia tiene el siguiente código de colores, azul gris rojo y dorado. Cuál es su valor?

La primera banda azul es 6, la 2da banda gris es 8, la 3era banda rojo es x100 y la tolerencia es 5% o sea x0.1.
El valor es: 68x100=6800 omega = 6.8K omega
La tolerancia es 6800x0,1 = 680### Codificación de resistencias


## Ejercicio
#### Una resistencia tiene el siguiente código de colores, azul gris rojo y dorado. Cuál es su valor?

La primera banda azul es 6, la 2da banda gris es 8, la 3era banda rojo es x100 y la tolerencia es 5% o sea x0.05.
El valor es: 68x100=6800 omega = 6.8K omega
La tolerancia es 6800x0,05 = 340 omnios.


### Video 4 (fin de la unidad 2)
Una forma de ver que no hay una fuga: apagá todas las luces bajar todos los braquers y el disco del costado se tiene que quedar quieto 
## Resistencias y Condensadores
Si coloco más corriente del que puede funcionar un LED se puede quemar entonces se usan los resistencia. Ustedes pueden probar conectar un LED a 12 voltios y lo vas a quemar. La resistencia se usa para limitar la corriente a través del LED.
Se puede limitar la resistencia, pero hay circuitos en donde se utlizan como divisor de voltaje.
### Potenciómetro
Tipo de esistencia variable que permite modificar su valor mediante el movimiento.
##### Tipos
![/electronica/potenciometro.png](/electronica/potenciometro.png)
el azul cuadrado y tiene una perilla metálica estos potenciometros son de precisión.
y el 3ero la resistencia es lineal, se usa mucho en los sistemas de sonido.

### Fotoresistencia
Varía la resistencia en base a la cantidad de luz incidente.

Las fotoceldas tienen el componente Fotorrresistencia LDR internamente.
Simplemente la atan a un circuito para que trabaje a 110voltios o 220.

A veces la resistencia es simbolizada con un cuadradadito

### Condensador o capacitor
Les dan valores a la corriente para que entre a un circuito integrado.
Aparato que almacena energía es como una batería pero de corto tiempo de retención, pero la diferencia es que un concensador dura segundos.
Si lo dejo cargado a un condensador se descarga muy rápido. 
#### Como se compone?
![capacitor](/electronica/capacitor.png)
Tiene dos láminas y un material dieléctrico, como almacena la energía? en forma de cargas electricas electrones, es un voltaje si conecto 110voltios el almacena 110 voltios si le conecto 5 voltios almacena 5 voltios. Almacena como voltaje.
La capaidad de almacenar energía se llama capacitancia, y el valor que se da a la capacitancia es el microfaradio.
El faradio es una medida muy grande para un condensador, entonces usamos microfaradios (uf 1x10^-6), nanofaradios(nf 1x10^-9), picofaradios(pf 10x10^-12)

La energía de un rayo tiene millones de faradios
#### Tipos de condensadores fijos y variables
Condensadores variables en los radios había que graduarlo bien para que la emisora no se perdiera.
Hoy en día no se usa porque las radios son digitales, se utilizan condensadores finos. Los condensadores pueden ser polarizados y no polarizados.

#### Fijos y cerámicos
##  Cerámicos
Estos condensadores son fijos , no polarizados. Están constituidos por un disco de material cerámico y se fabrican para capacidades pequeñas, por debajo de 1uf
Este tipo de condensadores se fabrican en capacidades muy pequeñas, casi de 1 microfaradio para abajo.

Hay dos, montaje de montaje y otro de superficial.


## Condensador cerámico

![condensador ceramico](/electronica/ceramico.png)

Antes era por colores pero están especificados por voltaje y por capacidad de almacenamiento que es en faradios.


![condensador ceramico](/electronica/ceramico_.png)
microfaradio = 10 a la -6 (se multipla por 0.000001)
nanofaradio = 10 a la -9
picofaradio = 10 a la -12

Si quiero subir de posición me corro a la izquierda la coma y si quiero bajar me corro a la derecha.


###### por ejemplo tenemos un condensador de 0,1 microfaradios quiero expresar esa medida en nanofaradios entonces voy a correrme a la derecha 3 posiciones la coma.

* 0,1 microfaradios
* 0,100|000
* es decir que sería 1 y dos ceros después de la coma: 100 nanofaradios.

#### Un condensador de poliester trabaja igual que un condensador cerámico

### Condensador Electrolíticos
![condensador](/electronica/condensador_electroliticos.png)

Son fijos polarizados. Están constituidos por dos finas láminas de aluminio separadas por una capa de papel humedecido con un líquido llamada electrolítico.

Y es mucho más fácil identificarlo pueden dicen por en la imagen 3300 microfaradios. Los condensadores cerámico y electrolítico son los más usados.


#### Condensador electrolíticos en continua
Al conectarle una fuente de voltaje CC no existirá ningún paso de corriente a través de él, debido al dieléctrico (aislante); sin embargo, se produce una acumulación de cargas elećtricas en sus placas.

Una vez que se carga el condensador se apaga (se abre) y no deja pasar corriente de un lado al otro.
![condensador electrolítico en continua](/electronica/condensador_ele.png)

### Condensador electrolíticos en alterna
Cuando un condesadador es conectado a un voltaje alterno, en el primer medio ciclo el condensador se carga y en siguiente medio ciclo se descarga para cargarse con polaridad contraria.
En corriente alterna se abre, en continua no. En corriente alterna deja pasar la corriente. (es como una impedancia es como una resistencia)

### bobina o inductor
se utiliza en circuitos de radiofrecuencia
obtaculisa el paso de corriente
en el caso del condensador: almacena energía en forma de corriente.
en el caso de la bobina: almacena energía en forma de corriente.
el condensador son similares porque almacenan energía simplemente el voltaje en la bobina es 0 y la corriente en el condensador es practicamente 0, el condensador se carga lento y se usan para que no hayan cambios bruscos de voltaje. 

La inductancia se utilizan para cambios bruscos de corriente, en arranque de motores, para que no haya consumo de corrientes repetentinos.

Se usa para crear circuitos occilantes.
La bobina cuando la atravieza una corriente genera un campo magnético.

Nikola Tesla hizo torre tower para transmitir energía inalámbrica.

## Componentes electromecánicoss
Son componentes que requieren algún accionamiento mecánico externo o interno, como la luz como el calor o un movimiento mecánico.
#### Conductor
1. Dos tipos. 
Cable:  un solo conductor grueso
Alambre: varios conductores flexibles
también tenemos como cable de fibra óptica que llevan una luz o cables coaxiales que son cables telefónicos. Los conductores se identifican mediante un calibre: se usa AWG se utiliza desde Canadá hasta Argentina.
![cables](/electronica/cables.png)
Si yo compro un cable que está con norma AWG y me dice que el cableado 16 tiene 3.7 amperios EL VA A RESPETAR eso. Pero si compro en cualquier lado el amperaje máximo seguramente va a ser de 1 amperio y cuando lo conectes se prenderá fuego el cable porque no aguante 3 amperios.

La cubierta de los cables tienen protección para que cuando se caliente no se prenda fuego.

Esa es la diferencia entre cables que cumplen la norma y los que no.

Hay algunos cables que vienen en una aliacion de cobre con aluminio y son una basura.
Los mejores cables: es todo de cobre.

2. **Interruptor**  
![interruptores](/electronica/interruptores.png)

Son componentes que permiten o interrupen el paso de CORRIENTEN por un circuito.
El interruptor 4 viene con una capacidad de corriente (1 o 2 amperios)
![interruptores](/electronica/interruptores_circuito.png)
El primer interruptor lo apretás y genera el paso de corriente y en el otro lado es un relé (el relé está dentro de los interruptores y es mecánico)
3. Relé
![electrónica relé](/electronica/rele.png)
Es una especie de interruptor electromecánico, conformado por una bobina y unos contactos que hacen de interruptor, pero el accionamiento de ese interruptor lo hace una bobina interamente el relay tiene una bobina q al darle voltaje acciona los contactos, tiene 3 contactos uno común y otro cerrado (estan unidos el cerrado y el común) y otro normalmente abierto. Entre el contacto abierto y el común no hay paso de energía.

Con el multímetro se puede medir la bobina casi siempre estará por 300 omnios 400 omnios, un contacto me va a medir cerrado y el otro contacto me va a medir abierto. Un contacto me mide que la resistencia es de 1 2 omnios y el otro contacto no me mide resistencia. Y en la bobina me mide 200, 300 400 omnios dependiendo de la bobina.

En las letras que tiene el relé me dice que es de 12 voltios, y me dice que la capacidad es de 10 amperios a 250Voltios
O sea yo puedo conectar una bombilla a corriente alterna y funciona a 200 voltios y q tenga un consumo de 10 amperios.
Lo mismo para 125 voltios - 10 amperios.
Lo mismo para 28 voltios - 10 amperios.
Lo mismo para 30 voltios - 10 amperios.

#### Por qué nosotros no recomendamos conectarle cargas tan altas?
Cuando los electrones quieren pasar todos a la vez se genera fricción y se produce chispas. Si laburás con corriente muy altas en 6 meses ya se daña.
10 amperios es la capacidad máxima.
Si yo le pongo 10 amperios cada vez que esta palanquita pasa y va al otro lado es un golpe y en realidad lo q hace es un corto en el contacto (chispa) 
los contactos soportan 10 de amperios pero para prolongar la vida útli es recomendable trabajarlos a 50% de su capacidad máxima.

Explicación en la hora 01:20:40 del video 4: [https://yt.oelrichsgarcia.de/watch?v=k0Mtr-Wc4AE&list=PLKxOqr8Lfq-zJkoot8vtQgmILOi1fAEQR&index=3](https://yt.oelrichsgarcia.de/watch?v=k0Mtr-Wc4AE&list=PLKxOqr8Lfq-zJkoot8vtQgmILOi1fAEQR&index=3)

![rele circuito](/electronica/rele__.png)

##### Este circuito es una fotocelda.
Vemos como se conecta el relé, a la derecha tenemos dos contactos el que está abajo es el común y le conectamos una corriente de voltaje y una lámpara.

### Como probar un relé?
Para probar que el relé funciona tenés que poner el multímetro en continuidad que es el símbolo de internet inalámbrico. Podemos probarlo al relé en continuidad o en resistencia.

ponelo en continuidad y medí entre los dos extremos de abajo y te va a dar 400 más o menos que está bien, y si medís el terminal de la mitad y un extremo superior te va a pitar si está en continuidad del otro lado no te va a medir nada. Si lo ponés en omnios (2k) te va a dar 383 más o menos la medida de la bobina y si ponés el negro en la mitad y el rojo en el extremo superior te va a medir una resistencia muy chica 0.01 y del otro lado NO nos mide NADA ( te tira 1 como resultado)

lo último que se daña en este tipo de componentes es el sistema de control

### Fin del módulo 2


# Video 5 - Módulo 5
#### Componentes Activos
Son aquellos que pueden controlar voltajes y corrientes o realizar amplificación. Son los principales responsables de la revolución de la electrónica moderna. Entre ellos tenemos los **diodos** , **transistores* y **circuitos integrados**.

## Materiales Tipo N y P
#### Semiconductores
Silicio y germanio son los más utilizados.
Los componentes como el cobre los átomos de cobre en la última línea o en el última capa el átomo de cobre tiene 1 sólo electrón entonces ese electrón es el que se va a desplazar a otro átomo para generar esa corriente que se mueve en un conductor de cobre cuando le aplicamos una fuente de voltaje.

En el átomo de silicio como el de germanio tienen 4 electrones en su capa externa y eso permite hacer enlaces con otro átomos, a esto se le llama enlaces covalentes. 

Cuando se mira un cristal de silicio los átomos de silicio van todos unidos.
##### Empezaron a hacer pruebas y se crearon dos tipos de materiales uno de tipo N y otro de tipo P.
Se crearon con un procceso químico que se llama dopaje q es inyectarle a un átomo o a un cristal de silicio un átomo de antimonio y el rojo es el átomo de bora, estos átomos en la última capa no tienen 4 electrones sino que tienen 5. 

El átomo de antimonio comparte 1 electrón con el átomo de silicio entonces los dos comparten los electrones y eso crea un enlace covalente. Para compartir neesita uno para este lado y el otro para el otro lado, necesita 4 electrones que necesitan para hacer un enlace covalente con cada átomo de silicio.

Y se hace una estructura que se llama red cristalino y la estrcutura natural del silicio es así, simplemente que se hace un proceso químico y le inyectan un átomo diferente al de silicio en el material tipo N (tiene un electrón de más)

En el tipo P tiene 1 electrón menos.

###### Los semiconductores tipo P o N por si solos no tienen mayor utilidad práctica. Para que estos materiales sean útiles deben unirse en diferentes configuraciones y es así como se crean los componentes semiconductores.
Porque el material tipo N tiene exceso de electrones y al tipo P le faltan electrones, cuando se unen los dos hay un flujo de electrones de un material al otro creando una corriente. Entonces este material se puede comportar como un circuito abierto o uno cerrado.

##### De acá nace el DIODO
Es la unión de un material tipo P y un material tipo N
Material tipo N: Exceso de carga de electrones (carga negativa)
Material tipo P: Faltan electrones (carga positiva)


La función del diodo: dejar pasar corriente en 1 sentido y bloquearla en el esentido contrario.
El diodo es una especie de compuerta.

#### Polarización del diodo.
El diodo permite conectarlo de cualquiera de las dos formas pero si yo conecto el positivo en un terminal o al otro terminal tengo algo que se llama polarización directa y polarización indirecta.
### Los términales del diodo tienen nombres: ánodo(tipo P- positivo) y cátodo (tipo n - negativo)
 
###### Si yo conecto una fuente de voltaje y el postiivo va al ánodo quiere decir que está en polarización directa.
#### El diodo se comporta como un conductor
Si yo conecto el diodo al contrario o sea el positivo lo conecto en el cátodo entonces tengo polarización inversa, qué pasa en la polarización inversa? No hay paso de corriente.


Polarización directa el positivo de la fuente del ánodo del diodo 
Polarización indirecta el positivo de la fuente está en el cátodo del diodo.

### diodo rectificador
###### estos diosdos están diseñados específicamente para convetir corrientes AC en corrientes DC. A este proceso se le llama rectificación y se utiliza para diseñar fuentes de alimentación
![diodo rectificador](/electronica/diodo_rectificador.png)

Esta es la gráfica del funcionamiento del diodo
desde el eje y (corriente) para adelante es voltaje positivo
 y del eye y para atras es voltaje negativo o polarización inversa.

Polarización directa: conectá el voltaje positivo al ánodo y si ese voltaje supera los 0,7 voltios la corriente empieza a subir.

Si yo midiera voltaje cuando está polarización directa hay 0.7 voltios.
Y en polarización inversa yo le puedo poner 10 voltios 40 voltios hasta que llega al voltaje de RUPTURA, que viene especificado para cada diodo.


Para el diodo rectificador no es bueno trabajar con la parte negativa hay otros q sí.


![diodo electrónica](/electronica/diodo__.png)

La rayita que tiene hace referencia al cátodo, el otro lado es el ánodo

Una forma de idenitificar los diodos "1N" , el 1N hace referencia a que es una union y el 4004 hace referencia a la especificación.   
Para el diodo 4004 lo máximo que soporta es 1 amperio.  
Si yo le pongo más corriente se va a quemar.  
En el sistema europeo se utiliza BY254.  

1N4001 Soporta 50V
1N4002 Soporta 100V
1N4003 Soporta 200V
1N4004 Soporta 400V
Y así hasta 0007 que soporta 1000 V

Este voltaje hace refererencia a la poralización inversa.


Una vez que el diodo empieza a conducir corriente su terminales tiene voltaje 0,7  que se llama voltaje UMBRAL 

![diodo rectificador ejemplo](/electronica/diodo_rectificador_ejemplo.png)
Minuto 14:30

##### Esa es la utilidad más práctica del diodo rectificador.
Cuando viene la corriente alterna sólo me dejará pasar postiivo, el negativo no me dejará pasar , porque es como si el diodo estuviera inverso.

Sirve para evitar que la gente conecte al revez un cargador a un equipo electrónico, oprque hay componentes que no soportan voltaje inversos. Hay componentes como un circuito integrado que si conecto 5 voltios al revez se quema. Entonces ese diodo te protege.

El diodo sólo deja pasar cuando yo le conecto el positivo al ánodo y al cátodo el negativo.
Si le conecto al cátodo la entrada de una corriente me la va a bloquear.

### Diodo zener
Cuando es polarizado inversamente, su corriente es cero hasta que alcanza un voltaje de referencia Vz. A partir de ese momento el diodo conduce corriente y la tensión entre sus terminales es constante e igual a Vz.

Está diseñado para trabajar en la zona de ruptura, si lo conecto en polarización directa funciona como un diodo rectificador, pero si lo conecto inversamente entrará en la zona de ruptura, a diferencia de los diodos retificadores este diodo no se daña.


Explicación en el minuto 20:20 del video 5 [https://youtube.com/watch?v=QzeGroGeVXA](https://youtube.com/watch?v=QzeGroGeVXA)

`
Por ejemplo si conseguís diodos zener de 3,7 voltios el símbolo del diodo zener es parecido al diodo rectificador pero tiene las lineas suavizadas, como viborita.
Crea un voltaje en los terminales, el voltaje empieza a subir a 1 voltios no pasa nada a 2 3 no pasa nada, cuando llega a 5 voltios entra a la zona de ruptura.
`

Cuando el positivo le llega al cátodo se llama polarización inversa.
#### El crea una referencia de voltaje , el voltaje que supere los 5 voltios el lo estabiliza a 5.
Si yo tengo 10 voltios, el sólo me va a dejar 5 voltios.
Sirve para regular/estabilizar un voltaje.

La corriente máxima de un diodo zener en general es 5 miliamperios.

Los diodos zener vienen por vatillaje ,tenés de 1 vatio de medio vatio, tiene que ver con la corriente que deja pasar. En donde P=VxI , y la I=P sobre V. Ahí se puede sacar la corriente máxima que soporta el diodo.


### LED (Light Emmiting Diode)
Son diodos construídos con arseniuro de galio fosfato (GaAsP) y emiten luz cuando se conectan en polarización directa.
#### Antiguamente era
una resistencia que se calentaba

Usa fotones, estas particulas que se llaman fotones, es el mismo efecto que se utlizan para los paneles solares, es el efecto contrario.  
En el panel solar los fotones entran a un material semiconductor y se transforma en corriente y bueno ahora son unos electrones que circulan de un lado a otro y se produce un fotón.  
  
# Los leds similitud con los paneles solares  
### LED  
Unos electrones que circulan de un lado al otro y producen un fotón  
### Panel solar  
Unos fotones que llegan y se transforman en electrones.  
  
![led](/electronica/led.png)  
### El diodo led tien dos capas de material P y N  
  
## Que es lo diferente a la bombilla de edison?  
Se puede producir en toda la gama de colores, estos son creados por un material semiconductor a señuro de galio sulfatado  
  
### Terminales led  
La terminal más corta es el cátodo (-)    
La parte plana del encapsulado indica el cátodo (-)    
La parte más grande en el interior es el cátodo (-)    
Medir con el multímetro en el rango de diodos    
  
El cátodo es más corto que el ánodo  
  
La parte plana del LED es el cátodo  
Y la parte interior de un led el contacto más grueso o más grande es el cátodo.  
  
Una bombilla emite más calor que luz, de la energía que le entrego a la bombilla el 80% se va en calor y 20% se va en luz.  
Por eso antes las bombillas eran utilizadas para hacer licuadoras, calentadores para criar pollos, las usaban como calentadores, porque producían más calor que luz.  
  
#### Los rayos catódicos fueron un boom cuando se crearon  
pero ahora es todo led  
incluso las lámparas florescentes que fueron un reemplazo de las bombillas incandecentes, también están dejando de fabricarse, ya es casi todo LED.  
  
#### Protección de LED  
Los LED deben protegerse con una resistencia en serie, para limitar su corriente a un valor seguro. También deben protegerse contra voltajes inversos.  
  
  
##### Propiedades de los leds  
Para que emita luz debe poralizarse en corriente continua, en polarización no funciona. Polarización directa: es decir cuando conecto el positivo al ánodo y el nagativo al cátodo.  
  
  
Hay que controlar la corriente que atraviesa en un led, porque los leds tienen una corriente específida, en este caso trabajan entre 20 miliamperios y 30 miliamperios. Si coloco menos corriente puede prender pero me va iluminar menos.   
Los leds al igual que los diodos rectificadores, se activan a cierto voltaje. De acuerdo al color de led determina el voltaje a que pueden manejar, están en un rango de 1,82 voltios y a 3 voltios  
  
  
##### Un led de 4 5 voltios ya no está en ese rango  
La tecnología led está en el rango de 2 a 3 voltios  
y la corriente está entre 20 y 30 miliamperios.  
  
  
#### Protección de LED  
Para calcular la resistencia, se resta el voltaje de LED (2V aprox.) al de la fuente. Por ejemplo si el voltaje de la fuente es 12 V, entonces el voltaje de la resistencia es 10V. Luego se ysa la ley de ohm.  
  
Si excedo de 3 voltios se puede quemar, si conecto polarización inversa con 5 voltios se quema.  
  
![protección led](/electronica/proteccion_led.png)  
Como es un circuito serie la corriente es la misma para todos los componentes y el voltaje se divide. Entonces yo a la fuente principal le resto los 2 voltios y nos va a quedar que la resistencia van a quedar 10 voltios.  
  
Y sabemos que la corriente que circula por el led va a ser de 20 miliamperios.  

```
V=IxR
R = V sobre I = 10 V sobre 20 mA
Resistencia = 10 V sobre 0,02 amperes
Resistencia = 500 omnios (omega)
```

No se consigue 500, se pueden conseguir 510 omnios o 470 omnios.  
No va a variar mucho funcionan los dos.

### Como conectar dos leds en SERIE
![electronica diodo leds en serie](/electronica/diodo_leds_serie.png)

##### Como calcular para una tira de LED
Sabemos que cada diodo necesita activarse con 2 Voltios
##### Cual es el voltaje que va a caer en la resistencia?
12 Voltios menos 6 voltios

según la ley de ohm
```
resistencia = voltaje sobre corriente = 6 voltios sobre 20 miliamperios
330 omnios o 270 omnios
```
si tengo 1 resistencia y 1 diodo led

```text
Resistencia = Voltaje / Corriente = 6v / 20 m A
R = 6 / 0,02 = 300 omnios
```
si tengo 1 resistencia y 3 diodos leds

No se consigue 300, se pueden conseguir 330 omnios o 270 omnios.  
No va a variar mucho funcionan los dos.

![electronica diodos](/electronica/diodos_en_seriee.png)

I = V sobre R = 6v sobre 510 
I = 0,011
I = 11 mA (miliamperios)




