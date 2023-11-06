# The-Groot
Robotics team The Groot
# (Spanish version) The Groot - WRO-2023
Equipo de Robótica The Groot
Groot es un robot programado para conducir de forma autónoma utilizando sensores y motores del equipo de LEGO Spike Prime.

#### Detalles del equipo:
**Nombre del equipo**: The Groot

**País**: Panamá, Panamá Oeste, Distrito de Capira.

**Miembros del equipo**: Genessis Reinosa, Verónica Chacón y José Guisado.

**Entrenadora**: Keila Chacón 

--------------------

#### Material de ingenieria:
Este repositorio contiene el detalle de la construcción del robot Groot, que participa en la competencia WRO-FUTUROS INGENIEROS en la temporada mundial WRO Panamá 2023.
**Datos**:

**Fotos del Equipo**: Contiene un carrucel de fotos del equipo.
                      Foto formal y foto loca 

**Fotos del Vehículo**: Contiene seis fotos del Robot, desde seis ángulos distintos, el video de la conducción del Robot se encuentra en el siguiente enlace.

**Boceto**: Contiene un esquema detallado de las partes electrónicos y motores de este robot y como se conectan para su funcionamiento. 

**Diagrama de lógica de conectividad**: Contiene una explicación del software, para los sensores y motores que fueron programados para la automatización del Robot.

---------

#### Carrucel de fotos del equipo:
![Carrusel de fotos ](https://github.com/ProfaKeila/The-Groot/assets/112026718/af9ee1f7-a4c2-4ad2-b629-48ccbaddd912)
**Fotos formal del Equipo**
![Formal](https://github.com/ProfaKeila/The-Groot/assets/112026718/a4da87f2-7b3a-4bbd-911e-92c6cf54db18)
**Fotos informal del Equipo**
![Loca](https://github.com/ProfaKeila/The-Groot/assets/112026718/63f75d30-57f7-45ae-bee4-7e51c4b50731)

------------------------------------
------------------------------------

**Fotos del robot:**

(i).	Cara frontal
![Frontal](https://github.com/ProfaKeila/The-Groot/assets/112026718/565fc0f3-e19c-48a5-89e7-a98349901c3d)


(ii).	Cara Posterior
![Posterior](https://github.com/ProfaKeila/The-Groot/assets/112026718/38068042-2f0f-4085-b71f-099bc75f4ae8)


(iii). Cara Izquierda
 ![Izquierda](https://github.com/ProfaKeila/The-Groot/assets/112026718/f1d17d99-e418-4d76-9f06-ac3a15a6f6fc)


(iv).	Cara Derecha
 ![Derecha](https://github.com/ProfaKeila/The-Groot/assets/112026718/485e9fe3-cf48-4354-907a-c4e386d851e8)


(v).	Cara Superior
 ![Superior](https://github.com/ProfaKeila/The-Groot/assets/112026718/c8c30534-8cb0-41ce-a1a0-20afed59f536)


(vi).	Cara inferior
![Inferior](https://github.com/ProfaKeila/The-Groot/assets/112026718/96e52935-4733-4316-a4c3-94e2697c4080)
  
------------------------------------------------
------------------------------------------------

## **Enlace al video en Youtube**:

Diseño del Robot

[![Explain](assets/545.png)](https://youtu.be/4QOwgeUl5-I?si=DpHX9Tr0fYKvHIKd)

**Dando vueltas**

| Izquierda o decrecha con una sola programación | Evitando el obstáculo |
| --- | --- |
| Ángulos de Guiño | Ángulo de guiño y sensor de color |
| [![Left_Video](assets/GreenClick.jpeg)](https://youtu.be/2Pd3Xvt8iUM) | [![Left_Video](assets/GreenClick.jpeg)](https://youtu.be/_-UqVCLI1og?si=oOWh4Tbge2MKK2M2) |
-----------------------------------------------------
| Izquierda | Derecha|
| --- | --- |
| Sensor ultra distancia | Sensor de color |
| [![Left_Video](assets/GreenClick.jpeg)](https://youtu.be/OL6q9jEXpvs) | [![Left_Video](assets/GreenClick.jpeg)](https://youtu.be/B-SupTOlSe8) |
-----------------------------------------------------
**Diagrama esquematico:**
A continuación se presenta un boceto de todos los componentes electrónicos utilizados.

![guif construcción](https://github.com/ProfaKeila/The-Groot/assets/112026718/758c4512-ce66-49e6-b707-334bfb112501) 

**Componentes Electromecanicos:**
El Robot se construyo utilizando el kit de robótica de LEGO Spike Prime. Ahora una breve descripción de cada componente electromecanico utilizado para la creación de este robot autónomo.

**Motores:** 
1.	**Motor trasero Angular grande**: Este  motor interconectado a un engranaje  permite la rotación de las ruedas traseras, dando tracción trasera y torque en el movimiento.
2.	**Motor delantero Angular mediano**: Este motor es el que permite la dirección al robot, y le permite el movimiento en los diferentes sentido.

**Sensores:**
1.	**Sensor Ultrasonico:** Este sensor se utiliza en su mayoría de veces para la medición de distancias y evasión de objetos.
2.	.	**Sensor de color:** cuenta con una alta precisión en su frecuencia de muestreo de 1kHz, lo cual garantiza la obtención de datos precisos para lograr resultados repetibles. Además, tiene la capacidad de detectar 8 colores y medir tanto la intensidad de la luz blanca reflejada como la luz ambiente. Su factor de forma simple permite construirlo y reconstruirlo rápidamente, facilitando su uso y adaptación en diferentes situaciones.
3.	Cámara HuskyLens: tomada como reemplazo de sensor de color del conjunto del Spike Prime, adopta la nueva generación de chips de IA, es utilizada para el reconocimiento de color y forma de objetos llamados obstáculos.

----------------------------------------------------------
**Cerebro o Hub**

Es como un bloque avanzado lleno de asombrosas capacidades, tiene 6 puertos para conectar sensores y motores, una pizarra con 25 luces que puedes personalizar, así como también la posibilidad de comunicarte a través de Bluetooth. Además, cuenta con un altavoz para hacer ruidos y un giroscopio inteligente de 6 ejes que capta movimientos en todas direcciones.
La batería es recargable para mantenerlo en funcionamiento durante un tiempo prolongado antes de necesitar cargarlo. Este dispositivo trae consigo su propio sistema operativo, como un cerebro, que es el MicroPython. También puede almacenar hasta 20 programas.
Las luces incorporadas, dispuestas en una matriz 5x5, añaden un toque visual interactivo, mientras que su capacidad para hablar a través del altavoz y su conexión inalámbrica Bluetooth amplían las posibilidades de diversión.

----------------------------------------------------------
