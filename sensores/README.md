# Sensor PIR

- ¿Como funciona?
  
  Su funcionamiento es detectar a personas/ objetos cual detectar su rango actue para "X" cosa por ejemplo si quieres que cuando el sensor PIR detecte alguien o algo mande una señal para que un reproductor de musica haga un  sonido se puede hacer.

- ¿Para que sirve?
  
  Sirve para detectar alguien o algo dependiendo del rango ajustado que le pongas cual se puede modificar con un destornillador para que detecte desde cierto rango para que su funcion sea más eficiente.

- ¿Como funciona el programa?
  
  El funcionamiento del programa es que desde arduino nos dija si detecta alguien o algo desde el panel de informacion que arduino nos puede proporcionaraprte de icluido que cuando detecte se encienda un diodo LED y se apage cuando no incluyendo que el programa tiene lectura analogica y variables dentro para facilitar su funcionamiento.

- ¿De que esta compuesto?
  
  Estaria compuesto de cables, una placa Arduino, un diodo LED, una resistencia, Sensor PIR, tabla placa protoboard

# Sensor de humedad

- ¿Como funciona?

  Funciona conectando el negativo al GND y el rojo a 5V para concluir que el amarillo econectada a una placa de arduino y protoboard y que se marque a un pin de una placa para tener la informacion y para concluir que al final de su compuesto de una especia de clavija cual se unde en la tierra para que envie la información

 ![sensor humedad](pictures/sensor_humedad_montaje.jpg)


- ¿Para que sirve?
  
Sirve para medir la humedad de cualquier elemento y cuya informacion que extrae lo mande a otro dispositivo.

- ¿De que componentes esta hecho?

   Tiene placa de arduino, placa protoboard, cableado y por ultimo en sensor de humedad.
  
- ¿Como funciona el programa?
  
El funcionamiento de nuestro programa es que cuando detecte una humedad mande la informacion al panel de arduino del monitor constantemente para asi comprobar cualquier cambio de humeadad que hay en ese material. El programa funciona de lectura analogica que incluye dos variables cual se le puede llamar de tu gusto con deun inicio de serial begin en el setup y para que el loop en el analogic read siempre lea el sensor y lo envie a serial print para que salga los datos que envia al sensor al monitor de la consola con un retardo de 500 milisegundos.

  ![sensor humedad](pictures/sensor_de_humedad.png)


# Sensor presión

- ¿Como funciona?
  
Funciona conectando a una placa arduino y protoboard junto a una resistencia a GND, 5V y a un Pin (ejempl: 8) para que al presionar el circulo con la minima presión que tu programes lo detecte y envie la información a la placa de arduino o al monitor en la pantalla con la cifra que el sensor de presión detecte.

- ¿Para que sirve?

Sirve para dectectar una presión cual a detectar una minima presión envie la información a la placa y asi la placa con esa información haga una cosa o otra. Pero su función es enviar la información a la placa.

 ![sensor presión](pictures/sensor_presion.jpg)


- ¿De que componentes esta hecho?

Esta compuesto de cableado, placa protoboard, placa arduino, resistencia, sensor de presión.

- ¿Como funciona el programa?

Funciona con tres variables cuales son el valor de presión y el pin, la presión el void setup solo contiene un serial begin 9600 y el void loop valora la presión con analogRead y map ajusta la presión para que sea menos o más sensible a la presión que se le aporta y usa un SerialPrinting para que los datos que detecte la placa de presión lo mande a la pantalla de la consola de monitor de arduino con un delay de 500 milisegundos.

![sensor presión](pictures/sesnsor_presion2.png)

# Sensor LDR

- ¿Como funciona?

Funciona con la placa arduino conectada a la protoboard para que el 5v a traves de una resistencia llegue a la parte positiva de la LDR y despues la negativa este directamente conectada a la parte negativa asi concluyendo y comprobando si detecta luz y cuanta intesidad de ella.

 ![sensor LDR](pictures/ldr_real.jpg)


- ¿Para que sirve?
  
  Sirve para saber cuanta luminosidad detecta en una habitación y la intensidad de la luz.

- ¿De que componente esta hecho?

Placa arduino, placa protoboard, resistencia, cableado y sensor LDR

- ¿Como funciona nuestro programa?

Nuestro programa funciona con 3 variables una es el pin, la luminosidad y la intensidad de la luminosidad en el void setup estara el serial begin 9600 y en el void loop un analogread para saber si la LDR detecta luz o no un map para saber la intensidad que la LDR esta detectando y un serialprinting para que los datos que detecta la LDR salga ahí en la pantalla de la consola de la aplicación de programación de arduino. 


 ![sensor LDR](pictures/ldr_code.png)

# Sensor de agua

- ¿Como funciona?



- ¿Para que sirve?



- ¿De que componente esta hecho?



- ¿Como funciona nuestro programa?
