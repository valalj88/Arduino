# ARDUINO

---
<details>
<summary>Introducción Arduino</summary>
<p align="center">
<img src="https://github.com/valalj88/Web-de-recetas-con-buscador-inteligente/blob/main/Archivos/BannerArduino.jpg" alt="Mi banner" width="800" height="200">
  </p>
<br>

**¿Que es arduino?**
<br>
	Es una plataforma de hardware y software libre usada para crear proyectos electrónicos de forma fácil para principiantes y expertos.
<br>

**¿Cuáles son sus características más importantes?**
<br>
	Arduino destaca por ser una plataforma de código abierto, fácil de usar, con su propio entorno de programación (IDE) y una amplia comunidad que brinda soporte.

**¿Cuál es el origen de Arduino?**
<br>
	Arduino fue creado en 2005 en el Instituto IVREA, en Italia, como una herramienta para estudiantes de diseño sin conocimientos técnicos en electrónica y programación. Sus fundadores son: Massimo Banzi, David Cuartielles, Tom Igoe, Gianluca Martino y David Mellis 		desarrollaron Arduino como una plataforma de hardware libre y de bajo costo, con el objetivo de facilitar la creación de proyectos interactivos.
<br>
	El nombre "Arduino" proviene de un bar en Ivrea frecuentado por los fundadores, que también toma el nombre de un rey italiano.
	
**¿Qué modelos de Arduino hay? Haz una tabla donde especifiques para cada modelo: microcontrolador, voltaje, pines digitales, entradas analógicas, memoria, reloj.**
<br>

<table>
  <tr>
    <th>Modelo</th>
    <th>Microcontrolador</th>
    <th>Voltaje de operación</th>
    <th>Pines digitales</th>
    <th>Entradas analógicas</th>
    <th>Memoria Flash</th>
    <th>Frecuencia de reloj</th>
  </tr>

  <tr>
    <td>Arduino Uno R3</td>
    <td>ATmega328P</td>
    <td>5V</td>
    <td>14</td>
    <td>6</td>
    <td>32 KB</td>
    <td>16 MHz</td>
  </tr>

  <tr>
    <td>Arduino Mega 2560</td>
    <td>ATmega2560</td>
    <td>5V</td>
    <td>54</td>
    <td>16</td>
    <td>256 KB</td>
    <td>16 MHz</td>
  </tr>

  <tr>
    <td>Arduino Nano</td>
    <td>ATmega328P</td>
    <td>5V</td>
    <td>22</td>
    <td>8</td>
    <td>32 KB</td>
    <td>16 MHz</td>
  </tr>

  <tr>
    <td>Arduino Leonardo</td>
    <td>ATmega32u4</td>
    <td>5V</td>
    <td>20</td>
    <td>12</td>
    <td>32 KB</td>
    <td>16 MHz</td>
  </tr>

  <tr>
    <td>Arduino Due</td>
    <td>AT91SAM3X8E (ARM Cortex-M3)</td>
    <td>3.3V</td>
    <td>54</td>
    <td>12</td>
    <td>512 KB</td>
    <td>84 MHz</td>
  </tr>

  <tr>
    <td>Arduino Micro</td>
    <td>ATmega32u4</td>
    <td>5V</td>
    <td>20</td>
    <td>12</td>
    <td>32 KB</td>
    <td>16 MHz</td>
  </tr>

  <tr>
    <td>Arduino MKR1000</td>
    <td>SAMD21 Cortex-M0+</td>
    <td>3.3V</td>
    <td>8</td>
    <td>7</td>
    <td>256 KB</td>
    <td>48 MHz</td>
  </tr>

  <tr>
    <td>Arduino Nano 33 IoT</td>
    <td>SAMD21 Cortex-M0+</td>
    <td>3.3V</td>
    <td>14</td>
    <td>8</td>
    <td>256 KB</td>
    <td>48 MHz</td>
  </tr>
</table>

**¿Para qué sirve un Arduino?**

La principal utilidad que se le da a un arduino es la automatización que esto sirve para controlar las luces por ejemplo de una casa, sensores, motores etc.. que esto puede hacer que podamos abrir una puerta de un parking de un garaje con un mando pero también se les puede dar otras funciones como para el aprendizaje básico de de la programación o en un nivel mas avanzado tambien lo podriamos utilizar en el área de IoT que lo que podemos hacer con esto es recoger los datos de los sensores de los arduino y mandarlos a la nube.

En resumen esta tecnología cada vez está creciendo más gracias a la integración que está teniendo en diferentes ámbitos ya que si nos paramos a pensar estamos rodeados de esta tecnología.

**¿Qué lenguaje utiliza?**

Arduino usa un lenguaje C/C++, pero adaptado para que sea más fácil de entender y usar ya que esto muchas veces se utiliza para el aprendizaje o para gente que está empezando a programar. Se usa principalmente en el entorno llamado Arduino IDE, donde escribes y juntas la información envías el código a la placa.

Este lenguaje solo permite controlar un par de objetos básicos como: Luces Leds,Rgb, Motores servos o DC,Sensores de temperatura,humedad o ultrasonido, Pantallas Lcd o Oled y por ultimo para comunicaciones como Bluetooth, Wi-fi etc….

**¿Qué es el Arduino IDE?**

Es el programa que usas en el ordenador para escribir, compilar y cargar código en una placa Arduino y este software es totalmente gratuito.
</details>

<details>
<summary>Actividades</summary>
<br>
<details>
<summary>Actividad_1</summary>
<br>

## Blink
**(1) Objetivo de la práctica**

En una placa de arduino ESP32 tenemos que conseguir que un led parpadee constantemente .

**(2) Material y explicacion de cada componente**
- Un led
- Dos Jumpers
- Una Resistencia 

**(3) Esquema del circuito como se muestra mas abajo**

<img src="https://github.com/valalj88/Web-de-recetas-con-buscador-inteligente/blob/main/Archivos/Actividades/1/%20CircuitoA1.png" alt="Página Tareas" width="700">

**(4) How To + Codigo explicado: uso de las variables, funciones y demas componentes del codigo**

<img src="https://github.com/valalj88/Web-de-recetas-con-buscador-inteligente/blob/main/Archivos/Actividades/1/CodigoA1.png" width="500">

**(5) Video de la practica**

https://github.com/user-attachments/assets/66268bca-320a-4598-8e20-6374dae1f2a2


**(6) Imagen para la entrada del blog o proyecto**

<img src="https://github.com/valalj88/Web-de-recetas-con-buscador-inteligente/blob/main/Archivos/Actividades/1/FotoA1.png" alt="Página Tareas" width="700">

</details>

<details>
<summary>Actividad_2</summary>
<br>
	
## A2-led+button

**(1) Objetivo de la práctica**

En una placa de arduino ESP32 tenemos que conseguir que al pulsar el boton se encienda el led y se apague cuando soltemos en la primera parte y en la segunda tiene que hacer función de lámpara, cuando pulsemos se enciende y tendremos que volver a pulsar para que se apague.

**(2) Material y explicación de cada componente**
- 4 Jumpers
- 3 Resistencias
- 1 Leds
- 1 Boton

**(3) Esquema del circuito como se muestra mas abajo**

<img src="https://github.com/valalj88/Web-de-recetas-con-buscador-inteligente/blob/main/Archivos/Actividades/2/image.png" alt="Página Tareas" width="700">

**(4) How To + Codigo explicado: uso de las variables, funciones y demas componentes del codigo**

**Boton Parte 1:**

#define PIN_LED    2
#define PIN_BUTTON 13
void setup() {
  pinMode(PIN_LED, OUTPUT);
  pinMode(PIN_BUTTON, INPUT);
}

void loop() {
  if (digitalRead(PIN_BUTTON) == LOW) {
    digitalWrite(PIN_LED,HIGH);
  }else{
    digitalWrite(PIN_LED,LOW);
  }
}

**Lampara parte 2:**

#define PIN_LED    2
#define PIN_BUTTON 13

bool ledState = LOW;          // Estado actual del LED
bool lastButtonState = HIGH;  // Estado anterior del botón

void setup() {
  pinMode(PIN_LED, OUTPUT);
  pinMode(PIN_BUTTON, INPUT);
}

void loop() {
  bool buttonState = digitalRead(PIN_BUTTON);

  if (lastButtonState == HIGH && buttonState == LOW) {
    ledState = !ledState;              // Cambia el estado del LED
    digitalWrite(PIN_LED, ledState);
    delay(200);                        // Anti-rebote simple
  }

lastButtonState = buttonState

}
--

**(5) Video de la practica**

https://github.com/user-attachments/assets/284d87e3-51cc-4833-aa10-a21d4093001c

**(6) Imagen para la entrada del blog o proyecto**

<img src="https://github.com/valalj88/Web-de-recetas-con-buscador-inteligente/blob/main/Archivos/Actividades/2/IMG_1893.jpg" alt="Página Tareas" width="700">

</details>

<details>
<summary>Actividad_3</summary>
<br>
	
## A3-led_RGB

**(1) Objetivo de la práctica**

En esta Actividad aprenderemos cómo controlar un LED RGB y observaran que puede emitir diferentes colores de luz (usaremos LED RGB para crear una luz multicolor). También podrán entender la función random así como el concepto de gradiente y su aplicación en la actividad.


**(2) Material y explicación de cada componente**
- 4 Jumpers
- 3 Resistencias
- 1 Led RGB

**(3) Esquema del circuito como se muestra mas abajo**

<img src="https://github.com/valalj88/Web-de-recetas-con-buscador-inteligente/blob/main/Archivos/Actividades/2/image.png" alt="Página Tareas" width="700">

**Parte 1**
**(4) How To + Codigo explicado: uso de las variables, funciones y demas componentes del codigo**

**Boton Parte 1:**

const byte ledPins[] = {4, 0, 2};   // Pines RGB
const byte chns[] = {0, 1, 2};      // Canales PWM

void setup() {
  for (int i = 0; i < 3; i++) {
    // Asocia pin + canal + frecuencia + resolución
    ledcAttach(ledPins[i], 1000, 8);
  }
}

void loop() {
  for (int i = 0; i < 256; i++) {
    setColor(wheel(i));
    delay(30);
  }
}

void setColor(long rgb) {
  ledcWrite(ledPins[0], 255 - ((rgb >> 16) & 0xFF)); // Rojo
  ledcWrite(ledPins[1], 255 - ((rgb >> 8) & 0xFF));  // Verde
  ledcWrite(ledPins[2], 255 - (rgb & 0xFF));         // Azul
}

long wheel(int pos) {
  pos = pos % 256;

  if (pos < 85) {
    return ((255 - pos * 3) << 16) | ((pos * 3) << 8);
  } 
  else if (pos < 170) {
    pos -= 85;
    return ((255 - pos * 3) << 8) | (pos * 3);
  } 
  else {
    pos -= 170;
    return ((pos * 3) << 16) | (255 - pos * 3);
  }
}

**Parte 2:**

const uint8_t PIN_R = 4;
const uint8_t PIN_G = 0;
const uint8_t PIN_B = 2;

void setup() {
  ledcAttach(PIN_R, 1000, 8);
  ledcAttach(PIN_G, 1000, 8);
  ledcAttach(PIN_B, 1000, 8);
}

void loop() {
  // Color 1: Azul dominante
  setRGB(50, 50, 255);
  delay(3000);

  // Color 2: Verde amarillento
  setRGB(180, 255, 50);
  delay(3000);
}

void setRGB(uint8_t r, uint8_t g, uint8_t b) {
  // Ánodo común → valores invertidos
  ledcWrite(PIN_R, 255 - r);
  ledcWrite(PIN_G, 255 - g);
  ledcWrite(PIN_B, 255 - b);
}

}

**Parte 3**

const byte ledPins[] = {2, 0, 4}; // Pinos RGB GPIO2, GPIO0, GPI04 
const byte chns[] = {0, 1, 2}; // Canales PWM

void setup() {
	for (int i = 0; i < 3; i++) {
ledcAttach (ledPins[i], 1000, 8);
	}
}

void loop() {
	for (int i = 0; i < 256; i++) {
		setColor(wheel(i));
		delay(20);
	}
}

void setColor(long rgb) {
	int red = (rgb >> 16) & 0xFF; 
	int green (rgb >> 8) & 0xFF; int blue rgb & 0xFF;

	ledcwrite(ledPins[0], red); // Rojo 
	ledcWrite(ledPins [1], green); // Verde 
	ledcWrite(ledPins [2], blue); // Azul

}

long wheel (int pos) {
	pos = pos % 256;
	
	if (pos85) {
		// Rojo -> Verde
		return ((255 - pos * 3) << 16) | ((pos * 3 ) << 8);
	}else if (pos < 170) {
		// Verde -> Azul
		pos- 85;
		return ((pos * 3) << 16) | ((255 - pos * 3) << 8) | (pos * 3);
	} else {
		// Azul -> Rojo
		pos = 170;
		return ((pos* 3) << 16) (255 - pos 3);
	}
}

--

**(5) Video de la practica**



https://github.com/user-attachments/assets/d3f503d3-ed57-47f2-aca4-5ad668606159



**(6) Imagen para la entrada del blog o proyecto**

<img src="https://github.com/valalj88/Web-de-recetas-con-buscador-inteligente/blob/main/Archivos/Actividades/3/CircuitoA3.jpeg" alt="Página Tareas" width="700">

**(7) Preguntas**

**Que observa tras cargar y correr el código del programa con respecto a lo que vimos antes. Explique la diferencia y argumente que es el gradiente y que es lo que hace (En el código) que en este ejercicio se pueda observar.**

Al cargar y ejecutar este programa se observa que el LED RGB cambia de color de manera suave y continua, pasando gradualmente por diferentes tonalidades (rojo, verde, azul y combinaciones intermedias).
Diferencia con lo visto antes
Antes, normalmente:
Los LEDs cambiaban bruscamente de un color a otro

O se encendían/apagaban en valores fijos

En este ejercicio:
El cambio de color es progresivo

No se perciben saltos entre colores

Se genera un efecto visual continuo

Esto ocurre porque ahora se usan valores intermedios de PWM y no solo encendido/apagado.

<br>

**¿Que es un gradiente?**

Un gradiente es una transición gradual entre valores, en este caso, entre colores.
En un LED RGB:
Cada color (R, G, B) puede variar su intensidad

Al cambiar esas intensidades poco a poco, se crea un gradiente de color

Explique que es el tipo de dato long y su diferencia con el int y porque se utiliza en el ejercicio.

¿Qué es el tipo de dato long? ¿Diferencia con int y por qué se usa?
Tipo de dato int
Tamaño: 16 bits en Arduino clásico

Rango: -32,768 a 32,767
Tipo de dato long
Tamaño: 32 bits
Rango: -2,147,483,648 a 2,147,483,647

<br>

**Explique el funcionamiento de la función wheel de manera general.**

Funcionamiento general de la función wheel
La función wheel(int pos):
Recibe un valor entre 0 y 255

Devuelve un color RGB codificado en un long

Funcionamiento general
Divide el rango 0–255 en tres secciones

En cada sección:

Un color baja su intensidad

Otro color la aumenta

<br>

**Busque en las referencias para que se utiliza la función ledcWrite() además indique cual es la salida de esta función y qué significado tiene en el código.
Buscar información de cada función del script en: https://www.arduino.cc/reference/en/ ?
¿Para qué sirve?
Escribe un valor PWM en un pin**

Controla la intensidad de una señal

Salida de la función
No devuelve ningún valor

Su efecto es físico: modifica la señal del pin

Significado en el código
En este ejercicio:
Controla la intensidad de cada color del LED RGB

Valores bajos → más brillo (ánodo común)

Valores altos → menos brillo


</details>

<details>
<summary>Actividad_4</summary>
<br>
	
## A4-led_bar

**(1) Objetivo de la práctica**

En esta Actividad aprenderemos cómo poner en funcionamiento una barra de leds, en la que probaremos el efecto de “Kitt” del coche fantástico, iluminando los leds con efecto movimiento de izquierda a derecha con rebote en bucle.


**(2) Material y explicación de cada componente**
- 10 Jumpers
- 10 Resistencias
- 1 Barra de leds

**(3) Esquema del circuito como se muestra mas abajo**

<img src="https://github.com/valalj88/Web-de-recetas-con-buscador-inteligente/blob/main/Archivos/Actividades/4/EsquemaCircuitoA4.jpg" alt="Página Tareas" width="700">

**(4) How To + Codigo explicado: uso de las variables, funciones y demas componentes del codigo**


<img src="https://github.com/valalj88/Web-de-recetas-con-buscador-inteligente/blob/main/Archivos/Actividades/4/C%C3%B3digoA4.png" alt="Página Tareas" width="700">

--

**(5) Video de la practica**

https://github.com/user-attachments/assets/f37fa5d1-2595-4d97-8c5e-56573ac8b5ab

**(6) Imagen para la entrada del blog o proyecto**

<img src="https://github.com/valalj88/Web-de-recetas-con-buscador-inteligente/blob/main/Archivos/Actividades/4/ImagenCircuitoA4.jpeg" alt="Página Tareas" width="700">

</details>

<details>
<summary>Actividad_5</summary>
<br>
	
## A5-Serial-IO

**(1) Objetivo de la práctica**

La comunicación serial es un método de transferencia de datos en el que la información se envía de manera secuencial, un bit a la vez, a través de un solo conductor o un par de conductores.
En otras actividades hemos visto como la comunicación serial nos permitía subir información a la placa ESP32. Hay varios conceptos que tenemos que tener claros para esta comunicación: tramas, baud rate y la sincronización.
La información se organiza en tramas. Cada trama suele comenzar con un bit de inicio y terminar con uno o más bits de parada. Estos bits ayudan al receptor a sincronizarse y a saber dónde comienza y termina cada trama.

La velocidad a la que se transmiten los bits se mide en baudios (baud rate). Representa la cantidad de cambios de estado (de 0 a 1 o de 1 a 0) por segundo. En Arduino se llama “Upload speed” y lo cneontramos en “Herramientas”. Por ejemplo, a una velocidad de 9600 baudios, se transmiten 9600 bits por segundo.

La sincronización es crucial en la comunicación serial, los dispositivos deben estar configurados para interpretar los bits en el momento correcto. La secuencia de bits y la velocidad deben ser conocidas y acordadas entre el transmisor y el receptor mediante protocolos. Algunos ejemplos son UART (Universal Asynchronous Receiver/Transmitter) y SPI (Serial Peripheral Interface).

## PARTE 1

Para esta práctica vamos simplemente a probar como funciona la comunicación de la placa con el ordenador para, en próximas prácticas, explotar esta funcionalidad. 

**(2) Material y explicación de cada componente**

- Placa conectada a PC vacía

**¿Que debemos hacer?**

Para poder observar la salida de información, debemos acudir a herramientas > Monitor serie y aparecerá una pestaña extra junto a la de “salida” por la que siempre leemos las incidencias con la placa.
Pon el monitor serial en “115200 baud” para que funcione.

**PREGUNTAS**

**1 ¿Que aparece en serial monitor?**

Texto configurado en el programa

Tiempo en segundos

Mensajes repetitivos si están dentro del loop()


**2 Pulsa los botones de boot+EN que hay en la placa de Arduino, ¿qué ocurre? Ahora pulsa solo EN, ¿qué ha ocurrido? ¿para qué nos puede servir esto?**

BOOT + EN → La placa entra en modo programación (modo carga).

Solo EN → La placa se reinicia (reset).

**2.1¿Para qué sirve?**

Reiniciar el programa cuando hay errores.

Forzar el modo carga si el ordenador no detecta bien la placa.

**3 ¿Qué indica la linea de código “Serial.begin(115200);”?**

Indica que se inicia la comunicación serial a una velocidad de 115200 baudios.
Serial.begin() → Inicia la comunicación.

115200 → Velocidad de transmisión en bits por segundo.

**4 Averigua que significa “%.1f s\n“.**

% : Indicador de formato


.1f : Número decimal con 1 cifra después del punto


s : Se añade la letra “s” (segundos)


\n :  Salto de línea


## PARTE 2

Una pantalla LCD1602 típica puede mostrar 2 líneas de caracteres en 16 columnas y es capaz de mostrar números, letras, símbolos, código ASCII, etc. A continuación, puedes ver los pines de los que dispone:
Como puedes ver son muchos pines para tener controlados así que se simplifica en la versión I2C, que conecta la entrada en serie y la salida en paralelo, lo cual nos permite usar solo 4 líneas para operar la pantalla:
El chip IC de serie a paralelo utilizado en este módulo es PCF8574T (PCF8574AT), y su dirección I2C predeterminada es 0x27(0x3F).

**(2) Material y explicación de cada componente**

- 4 jumpers de tipo hembra-macho
- La pantalla LCD


**¿Que debemos hacer?**

Revisa la información del capítulo 20 del libro:
Conecta la pantalla tal y como se muestra en el circuito anterior
En el Arduino IDE incluye la librería que puedes encontrar en Github, busca el paquete de LiquidCrystal_I2C.zip y añádelo al IDE para que funcione.
Pon el “Upload speed” de “Herramientas>Upload speed” a 115200
NO utilices el puerto 12 de la GPIO 
Usa el código que encuentres en el capítulo.


**PREGUNTAS**

**1 Revisa las conexiones en el circuito eléctrico:**

SCL			13
SDA			14
VCC			Positivo
GND			Negativo


**2 ¿Que hace la función “lcd.print()”? ¿Y “lcd.clear”?**

Clear: Borra completamente la pantalla.
Print: Muestra texto o números en la pantalla LCD.

**3 Por último, busca como conseguir que el mensaje de la primera fila se desplace de izquierda a derecha o a la inversa.**

lcd.setCursor(columna, fila); →  (0,0)

---

**(3) How To + Codigo explicado: uso de las variables, funciones y demas componentes del codigo**

![IMG_4096](https://github.com/user-attachments/assets/e151ca5a-6804-4411-8e1f-2a84a261569c)


---

**(4) Imagen para la entrada del blog o proyecto**

![IMG_4097](https://github.com/user-attachments/assets/560cd874-8285-4490-b55a-38453728319b)

---

## PARTE 3

Un higrotermógrafo es un instrumento de medición utilizado para registrar y monitorizar las variaciones de temperatura y humedad relativa en el tiempo. 

Su diseño combina las funciones de un termógrafo (para medir la temperatura) y un higrógrafo (para medir la humedad relativa).
En nuestro proyecto utilizaremos el dispositivo DHT11 que tiene 4 pines de los cuales el SDA es el que registra los datos por el pin, el VCC y el GND son los que le ofrecen la energía y cierran el circuito.

**PREGUNTAS**

**1 Primero prueba que el código funciona por monitor serial. Prueba a soplar sobre el sensor para modificar los valores de humedad.**

Aumenta la humedad relativa

Puede variar ligeramente la temperatura

**2 Busca que hace esta linea “DHTesp dht; “ al principio del código. ¿Que es un objeto en programación y que es lo que hace?**

Es una instancia de una clase.

Permite usar funciones asociadas al sensor.

**3 Prueba a codificar los valores para que muestre en la primera fila la temperatura en grados Kelvin y en la segunda fila en grados Farenheit.**

Programalo de tal forma que se muestre algo así:
Temp: 303,15ºK
Temp: 86ºF

![IMG_4100](https://github.com/user-attachments/assets/72f4873f-d5ca-4519-ad0f-16c7a8d7c1b6)


**(3) Esquema del circuito como se muestra mas abajo**

<img width="521" height="376" alt="Captura de pantalla 2026-02-20 125136" src="https://github.com/user-attachments/assets/0800ce39-9887-4042-90f0-b48cf460ad66" />


**(4) How To + Codigo explicado: uso de las variables, funciones y demas componentes del codigo**


![IMG_4099](https://github.com/user-attachments/assets/8a8c7e0b-c0af-43f1-b6ec-191ef4b2fb51)

--

**(5) Video de la practica**


https://github.com/user-attachments/assets/3ae8ab58-ef58-4ff9-9a7f-d11ce1928cf6


**(6) Imagen para la entrada del blog o proyecto**

![IMG_4100](https://github.com/user-attachments/assets/57bcbda4-c379-429e-b5b5-933865f0b885)

</details>

<details>
<summary>Actividad_6</summary>
<br>
	
## A6-WIFI

**(1) Objetivo de la práctica**

El objetivo principal de esta práctica es aprender a configurar y utilizar la conectividad WiFi del ESP32 en distintos modos de funcionamiento, comprendiendo cómo se comunica un dispositivo IoT dentro de una red.

---

## PARTE 1

El objetivo del modo Station es aprender a configurar el ESP32 como cliente WiFi, conectándolo a una red inalámbrica existente (router), obteniendo una dirección IP automática mediante DHCP y verificando la comunicación con otros dispositivos de la red.

**(2) Material y explicación de cada componente**

- Placa conectada a PC vacía

**¿Que debemos hacer?**

Tienes que poner el SSID y la PASSWORD de una red WiFi. A continuación, abre el serial monitor y lo pones a 115200 baudios. Una vez hecho esto, compilas el script previamente escrito.


**PREGUNTAS**

**¿A qué red te has podido conectar? Es 5G, 2.4G? Explica.**

El ESP32-S3 solo es compatible con redes 2.4 GHz, no con 5 GHz.
Por tanto, la conexión debe realizarse a una red 2.4G.

La diferencia principal:
2.4 GHz → Mayor alcance, menor velocidad.
5 GHz → Mayor velocidad, menor alcance.
ESP32 trabaja únicamente en banda 2.4 GHz.

**Verifica el uso de las librerías que aparecen en el código. ¿Son necesarias las tres: WiFi.h, WiFiClient.h, WiFiClientSecure.h)?**

Para este ejemplo básico solo es necesaria WiFi.h.
Las otras dos no son imprescindibles si no realizamos conexiones TCP o HTTPS.

**¿En qué casos utilizaría las librerías de arduino WiFiClient.h y WiFiClientSecure.h?**

WiFiClient.h → Cuando queremos que el ESP32 actúe como cliente y se conecte a un servidor (por ejemplo enviar datos a una API REST).

WiFiClientSecure.h → Cuando la conexión es HTTPS (segura con certificado SSL).

**¿Es posible seleccionar el canal de comunicación de la WiFi? Argumenta.?**
	
En modo Station no directamente (lo gestiona el router).
En modo Access Point sí podemos hacerlo con:
WiFi.softAP(ssid, password, channel);
En 2.4 GHz los canales van del 1 al 13.

**Prueba la conectividad entre un dispositivo como e PC o el móvil a la IP que te brinda el ESP32.**

Una vez obtenida la IP del ESP32:

- Abrimos navegador.

- Escribimos la IP mostrada en el Monitor Serie.

- Si hay servidor web cargado, accederemos correctamente.

<img width="1919" height="1037" alt="image (4)" src="https://github.com/user-attachments/assets/eff79e49-aa16-4369-bfd9-af4c55c12f43" />

---

## PARTE 2

El objetivo del modo Access Point (AP) es aprender a configurar el ESP32 como punto de acceso WiFi, creando su propia red inalámbrica independiente del router.

**(2) Material y explicación de cada componente**

- Placa conectada a PC vacía

**¿Que debemos hacer?**

En este caso vamos a configurar nuestro ESP32 pero esta vez como un Access Point. Cuando el ESP32-S3 selecciona el modo AP, crea una red de punto de acceso que está separada de Internet y espera para que se conecten otros dispositivos WiFi. 


**PREGUNTAS**

**¿Cuál es el uso de softAPConfig? Argumenta**

WiFi.softAPConfig(local_IP, gateway, subnet);

- IP estática del ESP32

- Gateway

- Máscara de subred


Sirve para controlar la red creada por el ESP32.

**¿Cómo puedo conocer la cantidad de dispositivos conectados a mi AP? Para ello investiga el uso de WiFi.softAPgetStationNum() y añade las líneas necesarias al código.**

WiFi.softAPgetStationNum();


**¿Qué método me permite visualizar la dirección IP de la interfaz de red del punto de acceso?**

WiFi.softAPIP()

**¿Qué nos permite la opción c_str() en el código?**

WiFi.softAPmacAddress().c_str();


---

**(3) How To + Codigo explicado: uso de las variables, funciones y demas componentes del codigo**

<img width="1919" height="1033" alt="image (5)" src="https://github.com/user-attachments/assets/a8dae836-14fb-42f7-a956-7d45d5bb3b30" />

---


## PARTE 3

**(1) Objetivo de la práctica**

El objetivo del modo AP + Station es aprender a combinar ambos modos de funcionamiento simultáneamente, permitiendo que el ESP32:

Se conecte a Internet a través del router.

Cree su propia red WiFi para otros dispositivos.

Actúe como puente de comunicación entre redes.

**(2) Material y explicación de cada componente**

- Placa conectada a PC vacía

**PREGUNTAS**

Compila y testea la conexión.
Añade el código correspondiente para acceder a la página web

**(3) How To + Codigo explicado: uso de las variables, funciones y demas componentes del codigo**

<img width="1919" height="1017" alt="image (6)" src="https://github.com/user-attachments/assets/9df2ce3a-97ab-4243-9f6e-1d143d41cb63" />

--


## PARTE 4

**(1) Objetivo de la práctica**

El objetivo de este apartado es implementar un servidor web en el ESP32, comprendiendo el funcionamiento básico del protocolo HTTP y la creación de páginas web dinámicas desde el microcontrolador.

Cuando alguien se conecta a nuestro servidor se invoca una función y otra cuando se genera un error. Estas funciones las podemos llamar como queramos pero mejor si utilizamos la denominación estándar. Por supuesto, que las tenemos que crear y agregar como otras funciones que ya hemos utilizado.


**(2) Material y explicación de cada componente**

- Placa conectada a PC vacía

**PREGUNTAS**

**Explica brevemente los diferentes parámetros que se envían en las líneas siguientes: 
server.send(200, "text/html", SendHTML("Hola a todos")); 
server.send(404,"text/plain", "No hay respuesta");**

server.send(200, "text/html", SendHTML("Hola a todos"));

- 200 → Código HTTP correcto (OK)

- text/html → Tipo de contenido

- SendHTML("Hola a todos") → Contenido enviado


server.send(404,"text/plain", "No hay respuesta");

- 404 → Error, página no encontrada

- text/plain → Texto simple

- "No hay respuesta" → Mensaje mostrado

**Añade las líneas de código correspondientes al servidor web. Cambia el puerto de comunicación de la página web.**


**(3) How To + Codigo explicado: uso de las variables, funciones y demas componentes del codigo**

<img width="1919" height="1010" alt="image (7)" src="https://github.com/user-attachments/assets/da2da2f4-5b4f-4267-a08a-8e032dbb58cb" />

--


**(6) Imagen para la entrada del blog o proyecto**

![IMG_4173](https://github.com/user-attachments/assets/8c7457c7-f19e-4d28-9e9d-a97222a2cd94)

</details>
</details>

<details>
	<summary>PROYECTO</summary>
<br>
<details>
	<summary>LINKS</summary>
https://es.aliexpress.com/item/1005008005112441.html?spm=a2g0o.productlist.main.3.49815PYP5PYPU4&algo_pvid=c9df27e4-4ec3-462e-a19c-4d10c06e8dc6&algo_exp_id=c9df27e4-4ec3-462e-a19c-4d10c06e8dc6-		2&pdp_ext_f=%7B%22order%22%3A%225285%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%2114.16%210.99%21%21%21111.74%217.80%21%40211b6a7a17721932195753311ea003%2112000043231311504%21sea%21ES%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3Aa26c3c1%3Bm03_new_user%3A-29895%3BpisId%3A5000000197846831&curPageLogUid=MiK9wu0n3W2F&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005008005112441%7C_p_origin_prod%3A

https://docs.sunfounder.com/projects/summary-of-fun-projects/en/latest/arduino/stacker_blocks2.0.html

https://youtu.be/FvsWhVsc19c

</details>

<details>
	<summary>Briefing de ideas</summary>

# PROYECTO: STACK GAME ARCADE CON ESP32 WROVER

## Presentación de la Idea

El proyecto consiste en el desarrollo de un videojuego tipo **Stack Game Arcade** visualizado en una **matriz de LEDs**.

El juego simula la clásica máquina arcade donde una fila de bloques luminosos se mueve horizontalmente de derecha a izquierda sobre una matriz LED. El jugador debe presionar un botón para detener la fila e intentar alinearla con la fila anterior. Las partes que no coincidan se eliminan. El objetivo es llegar hasta la parte superior sin perder todos los bloques.

El sistema estará compuesto por:

- Una matriz LEDs
- Un botón de control
- La placa ESP32 Wrover
- Botón para jugar
- LCD Screen
- Estructura física tipo mini-arcade decorada

El proyecto combina **programación, electrónica y diseño físico**, integrando lógica de videojuegos en hardware embebido.

---

# Objetivos del Proyecto

## Objetivo General

Desarrollar un videojuego interactivo en una plataforma embebida utilizando una **ESP32** y una **matriz LED**.

## Objetivos de Aprendizaje

Este proyecto nos permitirá:

- Comprender el uso de microcontroladores avanzados (ESP32)
- Implementar control de matrices LED
- Aplicar estructuras de programación utilizando videojuegos como ejemplo
- Gestionar entradas digitales mediante botones
- Trabajar con temporización sin bloquear el programa
- Diseñar un sistema completo desde hardware hasta software

Además, mejora habilidades en:

- Resolución de problemas
- Diseño modular
- Depuración de errores
- Planificación de proyectos tecnológicos

---

# Requisitos Técnicos

## Hardware

- **Placa:** ESP32 Wrover
- **Matriz LED:**
  - Opción 1: 8x8 con **MAX7219**
  - Opción 2: 8x8 **WS2812B (Neopixel)**
- 1 botón pulsador
- Resistencias (10kΩ para pull-down si no se usa pull-up interno)
- Protoboard
- Cables Dupont
- LCD Screen
- Cable USB
- (Opcional) Buzzer
- (Opcional) Caja de cartón o madera para estructura arcade

## Software

- **Arduino IDE**
- Soporte para **ESP32 Wrover**

### Librerías posibles

- `MD_MAX72XX` (para MAX7219)
- `Adafruit_NeoPixel` (para WS2812B)
- `SPI.h` (si se usa MAX7219)

Otros componentes usados en el desarrollo:

- Botón
- Matriz LEDs
- Jumpers macho-hembra

---

# Material Adicional

- Cartón o madera para carcasa
- Pistola de silicona
- Material de oficina para diseño frontal
- Impresiones decorativas

Estos materiales pueden obtenerse en:

- Tiendas de electrónica
- Amazon
- Ferreterías
- Papelerías

---

# Metodología de Trabajo

## Fases del Proyecto

### Fase 1: Diseño

- Definir tamaño de matriz
- Definir reglas exactas del juego
- Diseñar esquema de conexiones
- Planificar estructura del código

### Fase 2: Montaje Hardware

- Conectar matriz LED
- Conectar botón
- Verificar alimentación
- Realizar pruebas básicas de encendido

### Fase 3: Programación Base

- Inicializar matriz
- Mostrar patrón simple
- Leer botón correctamente
- Crear movimiento horizontal automático

### Fase 4: Lógica del Juego

- Implementar almacenamiento de filas en arrays
- Comparar fila actual con la anterior
- Recortar bloques no coincidentes
- Detectar **Game Over**
- Implementar sistema de puntuación

### Fase 5: Mejoras

- Añadir sonido
- Aumentar velocidad progresiva
- Animación de Game Over
- Guardar récord

### Fase 6: Documentación

- Capturas del montaje
- Explicación del código
- Esquemas eléctricos
- Conclusiones

---

# Recursos Disponibles

## Referencias Técnicas

- Documentación oficial de **ESP32**
- Tutoriales de matrices LED
- Ejemplos incluidos en las librerías
- Foros de Arduino
- Ejemplos en GitHub

## Videotutoriales

Buscar en YouTube:

- "ESP32 LED matrix tutorial"
- "Stack game Arduino project"
- "MAX7219 Arduino example"
- "Neopixel matrix ESP32"

---

# Conceptos Clave a Revisar

- Arrays bidimensionales
- Máquina de estados
- Temporización con `millis()`
- Interrupciones (opcional)
- Gestión de memoria en ESP32

---

# Desafíos y Soluciones Previstas

### Problema 1: Rebote del botón

**Solución:**  
Implementar *debounce* por software utilizando temporización.

### Problema 2: Parpadeo en la matriz

**Solución:**  
Actualizar la matriz solo cuando sea necesario y evitar delays largos.

### Problema 3: Desincronización del movimiento

**Solución:**  
Usar control de tiempo basado en `millis()`.

### Problema 4: Consumo de corriente en WS2812B

**Solución:**  
Limitar el brillo y usar una fuente de alimentación estable.

### Problema 5: Dificultad en la comparación de filas

**Solución:**  
Usar operaciones **AND bit a bit** si las filas se representan como enteros.
</details>
<details>
	<summary>Plan De Trabajo</summary>
	
## 📊 Diagrama de Gantt – Proyecto Stack Game Arduino

| Fase / Semana | 10-16 Mar | 17-23 Mar | 24-30 Mar | 31 Mar-6 Abr | 7-13 Abr | 14-20 Abr | 21-27 Abr | 28-30 Abr | 1-3 May |
|---------------|-----------|-----------|-----------|--------------|----------|-----------|-----------|-----------|---------|
| Planificación y documentación | ██████ | ██████ |  |  |  |  |  |  |  |
| Diseño en simulador / Código base | ██████ | ██████ | █ |  |  |  |  |  |  |
| Espera recepción piezas (AliExpress) |  | ██████ | ██████ | █ |  |  |  |  |  |
| Montaje del hardware |  |  | ██████ | ██████ |  |  |  |  |  |
| Programación del juego |  |  |  | ██████ | ██████ |  |  |  |  |
| Mejoras y optimización |  |  |  |  |  | ██████ | ██████ |  |  |
| Documentación final |  |  |  |  |  |  |  | ██████ |  |
| Margen de seguridad |  |  |  |  |  |  |  |  | ██████ |
  </tr>
</details>

<details>
	<summary>Esquema eléctrico y materiales utilizados</summary>

# ESQUEMA ELÉCTRICO

---

<img src="https://github.com/valalj88/Arduino/blob/main/Captura%20de%20pantalla%202026-03-13%20123832.png" alt="Página Tareas" width="700">

---

# MATERIALES UTILIZADOS

A continuación se describen los componentes electrónicos utilizados en el proyecto y la función que cumplen dentro del sistema.

### ESP32 Wrover
La **ESP32 Wrover** es el microcontrolador principal del proyecto. Se encarga de ejecutar el programa del videojuego, controlar la matriz de LEDs, leer las entradas del botón y gestionar la lógica del juego. Actúa como el cerebro del sistema.

<img src="https://github.com/valalj88/Arduino/blob/main/Archivos/Esp32.png" alt="Página Tareas" width="700">

### Matriz LED 8x8
La **matriz de LEDs** es el elemento visual principal del juego. En ella se mostrarán los bloques que se mueven horizontalmente y que el jugador debe alinear para avanzar niveles. Permite representar gráficamente el funcionamiento del videojuego Stack Game.

<img src="https://github.com/valalj88/Arduino/blob/main/Archivos/MatrizLED.png" alt="Página Tareas" width="700">

### Pantalla LCD
La **pantalla LCD** se utilizará para mostrar información adicional al jugador, como la puntuación, el nivel actual o mensajes del sistema como *Game Over* o *Inicio del juego*. Esto mejora la experiencia del usuario al proporcionar información clara durante la partida.

<img src="https://github.com/valalj88/Arduino/blob/main/Archivos/LCDScreen.png" alt="Página Tareas" width="700">

### Botón Pulsador
El **botón pulsador** permite la interacción del jugador con el sistema. Cuando el jugador presiona el botón, se detiene la fila de bloques en movimiento para intentar alinearla con la fila anterior.

<img src="https://github.com/valalj88/Arduino/blob/main/Archivos/Boton.png" alt="Página Tareas" width="700">

### Resistencias (10kΩ)
Las **resistencias** se utilizan para estabilizar la señal del botón. En este proyecto se pueden utilizar como resistencias **pull-down** o **pull-up** para evitar lecturas erróneas cuando el botón no está presionado.

<img src="https://github.com/valalj88/Arduino/blob/main/Archivos/Resistencias.png" alt="Página Tareas" width="700">

### Protoboard
La **protoboard** permite montar el circuito electrónico sin necesidad de soldar los componentes. Facilita realizar pruebas, modificaciones y ajustes durante el desarrollo del proyecto.

<img src="https://github.com/valalj88/Arduino/blob/main/Archivos/Protoboard.png" alt="Página Tareas" width="700">

### Jumpers
Los **cables Dupont** se utilizan para realizar las conexiones entre la ESP32, la matriz LED, el botón, la pantalla LCD y la protoboard. Permiten transmitir las señales eléctricas entre los distintos componentes del circuito.

<img src="https://github.com/valalj88/Arduino/blob/main/Archivos/Jumpers.png" alt="Página Tareas" width="700">

### Cable USB
El **cable USB** se utiliza para alimentar la placa ESP32 desde el ordenador y para cargar el programa desarrollado en el microcontrolador mediante el Arduino IDE.

<img src="https://github.com/valalj88/Arduino/blob/main/Archivos/CableUSB.png" alt="Página Tareas" width="700">

</details>
</details>
