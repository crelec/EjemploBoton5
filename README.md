# Ejemplo Uso BusIn, BusOut y escritura en el puerto Serial.

## Introducción
El siguiente programa muestra el uso de BusIn Y BusOut como una alternativa a la hora de trabajar con multiples pines de la tarjeta, para esto se utiliza un primer 
ejemplo aplicativo que consiste en mostrar un dato de tipo caracter en puerto serial y tambien la representación en binario por leds a partir del BusOut. El segundo 
ejemplo aplicativo consiste en utilizar el BusIn para recibir un dato de tipo binario y realizar la representación en leds a partir del BusOut de ese número,
adicionalmente se mostró ese dato de entrada en decimal a partir de puerto serial.



## Montaje

Para controlar el dato de entrada se utilizó un Dip Switch de ocho posiciones, y para mostrar la salida se hizo uso de un arreglo de 8 leds.

![datosBusDipSwitch_bb](https://user-images.githubusercontent.com/59096507/210120516-af186664-08a5-420b-822f-278885f72d65.jpg)

