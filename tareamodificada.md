#Tarea de procesadores
###MICROPROCESADORES
Un microcontrolador es un es un circuito integrado programable, capaz de ejecutar las órdenes grabadas en su memoria. Está compuesto de varios bloques funcionales, los cuales cumplen una tarea específica. Son diseñados para disminuir el coste económico y el consumo de energía de un sistema en particular. 

Por ejemplo, un microcontrolador típico tendrá un generador de reloj integrado y una pequeña cantidad de memoria **RAM y ROM/EPROM/EEPROM/FLASH**, significando que para hacerlo funcionar, todo lo que se necesita son unos pocos programas de control y un cristal de sincronización

![imagen](http://partesde.com/wp-content/uploads/2017/01/microprocesador-710x471.jpg)

###MICROCONTROLADORES
El microprocesador es un chip, un componente electrónico cuyo interior esta formado por miles y miles de transistores, cuya combinación permite realizar el trabajo que tenga encomendado el circuito o chip.Los micros, suelen tener forma de cuadrado o rectángulo negro, y van bien sobre unelemento llamado zócalo (socket en ingles), soldados en la placa, o metidos dentro de unaespecia de cartucho que se conecta a la placa base (aunque el chip en si esta soldado en elinterior de dicho cartucho)

![imagen](https://www.dynamoelectronics.com/1724-large_default/microcontrolador-pic18f452.jpg)


#####CARACTERISTICAS Y DIFERENCIAS ENTRE MICROCONTROLADOR Y MICROPROCESADOR 

| Caracteristicas     | Microcontrolador        | Microprocesador |
| ------------- |:-------------:| -----:|
| CPU     | El  microcontrolador  es  igual de bruto que un micro, por lo cual solamente realiza sus funciones con lo que tiene (datos) y su algoritmo o programa establecida. | Es una de sus funciones principales, la cual se encarga de dirigir sus operaciones. |
| Memorias RAM y ROM      | Son dispositivos externos que lo complementan para su óptimo funcionamiento.      |   Las incluye en un solo circuito integrado. |
| Velocidad de Operación | Rápida     |    Lenta  en  comparación  con  la de un microprocesador || 
| Tamaño    | La  configuración  mínima básica de un Microprocesador está constituida por un Micro de 40 Pines, Una memoria RAM de     28     Pines,     una memoria ROM de 28 Pines y un  decodificador  de direcciones  de  18  Pines,  lo cual lo convierte en un circuito bastante engorroso.     |   El Microcontrolador incluye todo  estos  elementos  en  un solo Circuito Integrado por lo que  implica  una  gran  ventaja en varios factores,   como por ejemplo, la disminución en el tamaño  del  circuito  impreso por  la  reducción  de  los circuitos externos. |
| Costos   | Para el Microprocesador, el costo es muy alto en la actualidad.   |   El   costo   para   un   sistema basado en Microcontrolador es mucho menor. |
| Interferencias   | Son más susceptibles a la interferencia electromagnética debido a su tamaño y a su cableado externo que lo hace más propenso al ruido.      |   El alto nivel de integración reduce los niveles de interferencia electromagnética |


###System on a Chip o Soc

Un System on a Chip (SoC) es un circuito electrónico que integra todos los componentes necesarios en un ordenador y otros sistemas electrónicos. Estos comprenden una GPU (procesador de gráficos), CPU (una unidad de procesamiento central),  controlador de memoria, circuitos de administración de energía, un controlador USB, conectividad inalámbrica (WiFi, GPS, Bluetooth, radio FM, 2G / 3G / 4G LTE) y más. Estos componentes están soldados de forma permanente en la placa base y, como tales, difieren de los ordenadores comunes cuyas piezas pueden reemplazarse en cualquier momento dado

![imagen](https://hardzone.es/app/uploads/2018/03/soc-system-on-a-chip.jpg)


####Ventajas de un SoC

El uso de un SoC supone una mayor integración de los componentes en una única pieza de silicio, esto tiene varios beneficios como una reducción en el coste de fabricación final del dispositivo que lo implementa, así como un menor consumo de energía. Esto último es muy importante en los smartphones, ya que la capacidad de su batería es bastante limitada. Otra ventaja de los SoC es que todos los componentes que integra están muy cerca unos de otros, lo que supone una mayor velocidad a la hora de comunicarse entre ellos, ofreciendo un mejor rendimiento.

Toda nueva tecnología es desarrollada con el objetivo de facilitar la vida al usuario final ofreciendo productos con los mejores estándares, pero no siempre el 100% de las funciones son adecuadas, estos son algunos puntos sobresalientes, y otros no tanto, en los chips SoC:
* Sin lugar a dudas la integración de todos los componentes en un solo chip es su principal ventaja al permitir tener todo el poder en un tamaño reducido.
* Mejores canales de comunicación entre todos los dispositivos
 + Máxima eficiencia
+ En caso de fallo de alguno de los componentes será muy difícil su reemplazo ya que el SoC esta soldado a la board.
* El aumento del calor al tener tantos componentes en un solo circuito puede llegar a afectar su optimo desempeño.


###Single Board Computer o SBC

Las siglas SBC quieren decir, Single Board Computer o Pc de placa única. Esto quiere decir que a diferencia de los ordenadores tradicionales, los pc’s SBC son placas que contienen todos o la mayor parte de los componentes de un ordenador.


**La principal característica** de los SBC u ordenadores con placas SBC son sus reducidas dimensiones. Mientras un pc mini-ITX está montado sobre una placa con unas medidas de 17 x 17 cm. Aproximadamente, los minipc’s o los ordenadores SBC están montados sobre placas con medidas inferiores, desde tamaños relativos a un usb hasta medidas similares a una tarjeta de visita como la Raspberry Pi que mide 8,5 x 5,3 cm.


**Otra de las características** de las placas SBC es su precio. Por lo general las placas SBC son muy económicas, tanto que algunos proyectos que usan estas placas son más económicos que su equivalente estándar. Normalmente estas placas no suelen sobrepasar los 100 dólares aunque siempre hay alguna excepción.


 
**Una tercera característica** de las placas SBC es que ofrecen poca potencia, aunque esto es relativo. Es verdad que una placa SBC no se puede comparar a una placa mini-ATX con un procesador i3 o i7, pero esto no significa que no podamos hacer nada. Actualmente todas las placas SBC ofrecen una potencia más que suficiente para el mundo de la ofimática, del desarrollo e incluso del mundo multimedia. Por desgracia aún no hay ninguna placa SBC que nos permita tener un uso puro para videojuegos

![imagen](https://images-na.ssl-images-amazon.com/images/I/61fg%2BWT1kKL._SX355_.jpg)

####Ejemplos de placas SBC
* **Raspberry** Pi. La placa SBC más popular se llama Raspberry Pi. Es una pequeña placa que cuenta con varias versiones y que tiene una amplia comunidad. El proyecto nació para buscar hardware económico y libre para enseñar computación en los colegios de primaria. Actualmente y gracias a su comunidad se puede hacer casi cualquier cosa con esta placa, desde un servidor hasta un clúster pasando por ser el hardware de una pesada tablet.
* **BeagleBone Black**. Es la alternativa estadounidense a Raspberry Pi. Por lo general no suele existir mucha diferencia entre la potencia de esta placa con el resto, ahora bien, BeagleBone Black puede soportar Ubuntu o funcionar como un accesorio más del Pc tradicional, nosotros decidimos.
* **PcDuino**. Es la placa SBC más libre que existe, si realmente existiese ese titulo. PcDuino está basado en los esquemas de Arduino e incorpora lo necesario para ser una placa SBC, es decir: procesador y memoria ram. A diferencia del resto, PcDuino es bastante grande, alcanza los 12 cm de largo por 6 cm de ancho. El último modelo de esta placa admite y soporta Ubuntu y Android.
* **Pandaboard**. Es posible la menos famosa pero no por ello la menos interesante. Pandaboard tiene una gran comunidad que está creando interesantes proyectos con esta placa SBC. Pandaboard permite la conexión wireless gracias a una antena wireless incorporada a la placa. Característica que otras placas no tienen.


##MODELO DE ARQUITECTURA DE VON NEUMANN

La arquitectura de John Von Neumann se caracteriza principalmente por los procesadores que tiene el mismo dispositivo de almacenamiento tanto para las instrucciones como para los datos. Estos, al ser almacenados en el mismo formato dentro de la memoria, utiliza un único bus de datos para poder mantener contacto con la CPU. Esto crea una eficiencia en la utilización de la memoria, pero al mismo tiempo requiere una ambigüedad para poder reconocer y distinguir los datos.

Un ordenador que posea esta arquitectura emula los siguientes procedimientos:

* Al encender el ordenador y obtener la siguiente instrucción desde la memoria en la dirección indicada por el contador de programa y la guarda en el registro de instrucciones.
- Aumenta el contador de programa y lo guarda en el registro de instrucción.
* Decodifica la instrucción a través de la unidad de control. Ésta es la encargada de coordinar el resto de los componentes de la computadora para realiza cada función determinada.
* Se ejecuta la instrucción. Ésta puede cambiar el valor del contador de programa, permitiendo hacer operaciones repetitivas. El contador puede cambiar también cuando se cumpla una cierta condición aritmética, haciendo que el ordenador pueda “pensar”, haciendo que pueda alcanzar cualquier grado de complejidad a través de la aritmética y de la lógica anteriores.
Hoy en día, la mayoría de las computadoras son construidas con esta arquitectura ya que las capacidades dnámicas del diseño, como la implementacion y la operación de un programa en vez de dos, aunque puede ser más lenta para determinadas tareas, es mas flexible y permite mas conceptos como la programación libre.



![imagen](http://www.electrontools.com/Home/WP/wp-content/uploads/2018/04/VonNeumann.jpg)


## MODELO DE ARQUITECTURA DE HARVARD
A diferencia del modelo de Von Neumann, el modelo de arquitectura de Harvard, que proviene del Harvard Mark I, se diferencia principalmente por la división de las instrucciones de los datos que se comunican con la unidad central de proceso en dos memorias separadas. Esto genera también que se utilicen distintos buses de información. Aunque es común un único bus de direcciones, con un control que pueda diferenciar entre ambas memorias. Al contrario del modelo de arquitectura de John Von Neumann, el modelo de Harvard no requiere de la ambigüedad para poder reconocer los datos, pero no es tan eficiente en la utilización de la memoria. Estos ordenadores siempre se componen por los mismos elementos que los utilizados por el modelo de Von Neumann, excepto por que tiene dos memorias, una utilizada para las instrucciones y otra para los datos, y no una única memoria como el otro modelo.

En este modelo, las instrucciones y los datos se almacenan en cachés diferentes para mejorar el rendimiento. Pero por su contraparte, tiene el inconveniente de tener que dividir la cantidad de memoria caché entre los dos, por lo que funciona mejor sólo en los casos particulares cuando la frecuencia de lectura de instrucciones y de datos es aproximadamente la misma.

Resumidamente, la arquitectura de Harvard se basa en:

* Las instrucciones y los datos se almacenan en caches separadas para mejorar el rendimiento.
* Tienen el inconveniente de tener que dividir las memorias caches entre los dos, por lo que no funciona de la mejor manera, salvo cuando la frecuencia de lectura de instrucciones y de datos es aproximadamente la misma.
* Esta arquitectura suele utilizarse en DSPs, o procesador de seal digital, usados prácticamente siempre en los productos para el procesamiento de audio y vídeo 


![imagen](http://www.electrontools.com/Home/WP/wp-content/uploads/2018/04/Harvard.png)



