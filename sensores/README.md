# Sensor PIR

- ¿Como funciona?
  
  Su funcionamiento es detectar a personas/ objetos cuál detectar su rango actue para "X" cosa por ejemplo si quieres que cuando el sensor PIR detecte alguien o algo mande una señal para que un reproductor de música haga un  sonido se puede hacer.

- ¿Para qué sirve?
  
  Sirve para detectar alguien o algo dependiendo del rango ajustado que le pongas cual se puede modificar con un destornillador para que detecte desde cierto rango para que su función sea más eficiente.

- ¿Como funciona el programa?
  
  El funcionamiento del programa es que desde arduino nos diga si detecta alguien o algo desde el panel de información que arduino nos puede proporcionar aparte de incluido que cuando detecte se encienda un diodo LED y se apage cuando no incluyendo que el programa tiene lectura analogica y variables dentro para facilitar su funcionamiento.

- ¿De que esta compuesto?
  
  Estaría compuesto de cables, una placa Arduino, un diodo LED, una resistencia, Sensor PIR, tabla placa protoboard

# Sensor de humedad

- ¿Como funciona?

  Funciona conectando el negativo al GND y el rojo a 5V para concluir que el amarillo econectada a una placa de arduino y protoboard y que se marque a un pin de una placa para tener la informacion y para concluir que al final de su compuesto de una especia de clavija cual se unde en la tierra para que envie la información

 ![sensor humedad](pictures/sensor_humedad_montaje.jpg)


- ¿Para qué sirve?
  
Sirve para medir la humedad de cualquier elemento y cuya información que extrae lo mande a otro dispositivo.

- ¿De que componentes esta hecho?

   Tiene placa de arduino, placa protoboard, cableado y por ultimo en sensor de humedad.
  
- ¿Como funciona el programa?
  
El funcionamiento de nuestro programa es que cuando detecte una humedad mande la información al panel de arduino del monitor constantemente para asi comprobar cualquier cambio de humedad que hay en ese material. El programa funciona de lectura analogica que incluye dos variables cual se le puede llamar de tu gusto con deun inicio de serial begin en el setup y para que el loop en el analogic read siempre lea el sensor y lo envíe a serial print para que salga los datos que envía al sensor al monitor de la consola con un retardo de 500 milisegundos.

  ![sensor humedad](pictures/sensor_de_humedad.png)


  [![](https://img.youtube.com/vi/R8Fm3tOMFYk/0.jpg)](https://www.youtube.com/watch?v=R8Fm3tOMFYk)


# Sensor presión

- ¿Como funciona?
  
Funciona conectando a una placa arduino y protoboard junto a una resistencia a GND, 5V y a un Pin (ejempl: 8) para que al presionar el circulo con la mínima presión que tu programes lo detecte y envíe la información a la placa de arduino o al monitor en la pantalla con la cifra que el sensor de presión detecte.

- ¿Para qué sirve?

Sirve para detectar una presión cual a detectar una mínima presión envíe la información a la placa y así la placa con esa información haga una cosa o otra. Pero su función es enviar la información a la placa.

 ![sensor presión](pictures/sensor_presion.jpg)


- ¿De qué componentes está hecho?

Está compuesto de cableado, placa protoboard, placa arduino, resistencia, sensor de presión.

- ¿Como funciona el programa?

Funciona con tres variables cuales son el valor de presión y el pin, la presión el void setup solo contiene un serial begin 9600 y el void loop valora la presión con analogRead y map ajusta la presión para que sea menos o más sensible a la presión que se le aporta y usa un SerialPrinting para que los datos que detecte la placa de presión lo mande a la pantalla de la consola de monitor de arduino con un delay de 500 milisegundos.

![sensor presión](pictures/sesnsor_presion2.png)

[![](https://img.youtube.com/vi/3YupFbgY81k/0.jpg)](https://www.youtube.com/watch?v=3YupFbgY81k)

# Sensor LDR

- ¿Como funciona?

Funciona con la placa arduino conectada a la protoboard para que el 5v a través de una resistencia llegue a la parte positiva de la LDR y despues la negativa esté directamente conectada a la parte negativa asi concluyendo y comprobando si detecta luz y cuanta intensidad de ella.

 ![sensor LDR](pictures/ldr_real.jpg)


- ¿Para que sirve?
  
  Sirve para saber cuánta luminosidad detecta en una habitación y la intensidad de la luz.

- ¿De qué componente esta hecho?

Placa arduino, placa protoboard, resistencia, cableado y sensor LDR

- ¿Como funciona nuestro programa?

Nuestro programa funciona con 3 variables una es el pin, la luminosidad y la intensidad de la luminosidad en el void setup estará el serial begin 9600 y en el void loop un analogread para saber si la LDR detecta luz o no un map para saber la intensidad que la LDR está detectando y un serialprinting para que los datos que detecta la LDR salga ahí en la pantalla de la consola de la aplicación de programación de arduino terminando con un delay de 500 milisegundos. 

 ![sensor LDR](pictures/ldr_code.png)

 [![](https://img.youtube.com/vi/Yh9sCnXlxm4/0.jpg)](https://www.youtube.com/watch?v=Yh9sCnXlxm4)


# Sensor de agua

- ¿Como funciona?

Funciona solo con una placa arduino y el sensor de agua sumergiendolo en cualquier recipiente claramente conectado a un pin, GND y 5v

- ¿Para qué sirve?

Para saber cuantá agua hay en un recipiente

- ¿De qué componente está hecho?

Placa arduino, cableado y sensor de agua

- ¿Como funciona nuestro programa?

funciona con 3 variables uno de pin, otro del sensor de agua y la cantidad de ella en el void setup esta en serialbegin 9600 y en el serial loop esta el analogread cual es el pin map cual es la cantidad exacta de agua que detecta y serial priting que muestra los datos que detecta en sensor en la pantalla de la consola terminando con un delay de 500 milisegundos

 ![sensor agua](pictures/sensor_agua.png)


# Sensor temperatura lineal

- ¿Como funciona?

Funciona conectando a la placa de arduino conectado  al cableado para que el sensor de temperatura lineal pueda detectar los datos y poder leerlo por ejemplo en la pestaña de la consola  de arduino de su app.

- ¿Para qué sirve?

Para detectar temperaturas de una forma lineal en nuestro entorno.

- ¿De qué componente está hecho?

Placa de arduino, sensor de temperatura lineal con cableados.

- ¿Como funciona nuestro programa?

Como los demás,  Ponemos dos variantes y en el void setup añadimos un serialbegin9600 y el void loop un analogicread cual lee a la variante PIN y cual equivale a la temperatura es la información que la variante PIN más map y termina con Serial  pritting que al ver el valor de temperatura lo envía a la consola de la app de arduino víendo el valor de temperatura que envia cual termina con un delay de 500 milisegundos.

 ![sensor temperatura lineal](pictures/programacion_temperaturalineal_iker,adrian.png)
