# Arduino 

## Integrantes
- Sergio Esteban Alarcon Valbuena
- Angel Gabriel Brito Barreto
## Introduccion

En el trabajo de hoy se tratarán temas esenciales sobre Arduino, comenzando por sus inicios, su evolución y las diversas placas que han aparecido a lo largo del tiempo. Además, se subrayará la relevancia de su comunidad mundial, que ha aportado considerablemente al desarrollo y a la innovación de esta plataforma. Se examinará, por último, la manera en que Arduino se ha fortalecido como una herramienta esencial para el desarrollo de soluciones tecnológicas y la educación.


## Que es
Arduino es una plataforma de hardware de código abierto que ha facilitado el acceso a la electrónica y la programación. Su enfoque simple y accesible ha permitido que tanto principiantes como expertos desarrollen proyectos tecnológicos de manera sencilla.

## Para que sirve
1. El Arduino puede recibir datos de:
- Leer información (Entradas)
- Sensores de temperatura 
- Sensores de luz 
- Botones o interruptores
- Sensores de movimiento
Ejemplo: detectar si hay luz o si alguien pasó.

2. Procesar datos

- El microcontrolador analiza la información según el programa que hagas en Arduino IDE.

Ejemplo:
Si hace mucho calor → activar ventilador

3. Controlar dispositivos (Salidas)
- Puede activar o controlar:
- LEDs (encender/apagar o regular brillo)
- Motores (mover objetos)
- Zumbadores (emitir sonido)
- Pantallas (mostrar información)

Ejemplo: encender una luz automáticamente.
## Historia de Arduino
Arduino nació en 2005 en el Interaction Design Institute Ivrea (Italia), creado por un grupo de estudiantes que buscaban una herramienta económica y fácil de usar para el prototipado electrónico. Su primera placa destacó por su simplicidad y por utilizar un entorno de programación basado en Wiring, lo que permitió programar microcontroladores de forma más accesible.

## Creadores

Los principales son:

- Massimo Banzi

- David Cuartielles

- Tom Igoe

- Gianluca Martino

- David Mellis

En resumen:

Ellos desarrollaron Arduino alrededor del año 2005 en Italia, y luego surgieron diferentes versiones, entre ellas el Arduino Uno (2010), que se volvió el más popular.

## Evolución de Arduino
Con el tiempo, Arduino ha lanzado diversas placas con mejoras importantes:
- Duemilanove (2009): Introdujo programación vía USB sin hardware adicional.
- Uno (2010): Se convirtió en el modelo más popular gracias a su rendimiento y facilidad de uso.
- Leonardo (2012): Permitió emular teclado y ratón mediante USB.
- Due (2012): Incorporó arquitectura ARM para mayor potencia.
- Yún (2013): Integró conectividad Wi-Fi para Gproyectos IoT.
- Zero (2014): Ofreció un microcontrolador de 32 bits más avanzado.
- MKR Series (2016): Diseñadas específicamente para Internet de las Cosas.
- Portenta H7 (2020): Orientada a aplicaciones industriales con alto rendimiento.

## Variedades de placas
- Arduino cuenta con múltiples versiones adaptadas a diferentes necesidades:
- Nano y Mini: Compactas para espacios reducidos.
- Pro Mini: Bajo consumo energético.
- Mega: Más pines y memoria para proyectos complejos.
- LilyPad: Diseñada para wearables.
- Esplora: Enfocada en educación interactiva.


## Perifericos que tiene integrados y su funcionalidad
-Microcontrolador (ATmega328P) → el “cerebro”

- Pines digitales (0–13) → para entradas y salidas (encender/apagar cosas)

- Pines analógicos (A0–A5) → para leer valores como temperatura o luz

- PWM (~) → para controlar intensidad (ej: brillo de un LED)

- Puerto USB → para programarlo desde el PC

- Regulador de voltaje → controla la energía que recibe

- LEDs integrados → indican encendido y funcionamiento

- Puerto de alimentación (jack) → para usar batería o adaptador

## Perifericos que necesita externos (Opcionales)

Entrada:
- Botones
- Sensor de temperatura
- Sensor de luz
- Sensor de movimiento

Salida:
- LEDs
- Motores 
- Zumbadores (buzzer) 
- Pantallas LCD
  
Otros componentes básicos:
- Resistencias
- Protoboard (para conexiones)
- Cables

## Ficha técnica de Arduino
| Característica         | Descripción                          |
| ---------------------- | ------------------------------------ |
| Microcontrolador    | ATmega328P                           |
| Voltaje de operación | 5V                                   |
| Voltaje de entrada  | 7–12V                                |
| Pines digitales     | 14 (6 con PWM)                       |
| Pines analógicos    | 6                                    |
| Memoria Flash       | 32 KB (0.5 KB usados por bootloader) |
| SRAM                | 2 KB                                 |
| EEPROM             | 1 KB                                 |
| Velocidad de reloj  | 16 MHz                               |
| Comunicación        | UART, SPI, I2C                       |
| Conexión            | USB tipo B                           |
| Dimensiones         | 68.6 mm x 53.4 mm                    |
| IDE                 | Arduino IDE (basado en C/C++)        |

## Descripción
El Arduino Uno es una de las placas más populares de Arduino. Está diseñada para facilitar el aprendizaje de la electrónica y la programación, permitiendo desarrollar proyectos de manera rápida y sencilla gracias a su arquitectura abierta y su amplio soporte comunitario.

## Comunidad y contribuciones
El éxito de Arduino también se debe a su comunidad global, que comparte proyectos y conocimientos. Esta colaboración ha impulsado la innovación y ha convertido a Arduino en una herramienta clave en la educación tecnológica.

## Conclucion
Arduino ha evolucionado desde un proyecto académico hasta convertirse en una plataforma global. Su enfoque en el código abierto, la accesibilidad y la innovación continúa inspirando a creadores y desarrolladores en todo el mundo.
