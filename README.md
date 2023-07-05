# The-Groot
Robotics team The Groot
# (Spanish version) The Groot - WRO-2023
Equipo de Robótica The Groot
Groot es un robot programado para conducir de forma autónoma utilizando sensores y motores del equipo de LEGO MINDSTORMS Inventor 51515.

#### Detalles del equipo:
**Nombre del equipo**: The Groot

**País**: Panamá, Panamá Oeste, Distrito de Capira.

**Miembros del equipo**: Genesis Reinosa, Verónica Chacón y José Guisado.

**Entrenadora**: Keila Chacón


#### Material de ingenieria:
Este repositorio contiene el detalle de la construcción del robot Groot, que participa en la competencia WRO-FUTUROS INGENIEROS en la temporada Regional de Panamá 2023.
**Datos**:
**Fotos del Equipo**: Contiene un carrucel de fotos del equipo, formal 3 informal.
**Fotos del Vehículo**: Contiene seis fotos del Robot, desde seis ángulos distintos, el video de la conducción del Robot se encuentra en el siguiente enlace.
**Boceto**: Contiene un esquema detallado de las partes electrónicos y motores de este robot y como se conectan para su funcionamiento. 
**Diagrama de lógica de conectividad**: Contiene una explicación del software, para los sensores y motores que fueron programados para la automatización del Robot.

#### Fotos del equipo:
(i). Foto formal.
![1_EquipoFormal](https://user-images.githubusercontent.com/112026718/186887081-0d170402-4681-420f-b0b5-f59b7845427e.JPG)

(ii). Foto informal.
![2_EquipoInformal](https://user-images.githubusercontent.com/112026718/186887090-ea81ea34-a021-4fab-961d-ed6f01018d9f.JPG)

Fotos del robot:
(i).	Cara frontal
![frontal](https://github.com/ProfaKeila/The-Groot/assets/112026718/42a04998-14ac-4aae-a103-18d1d24857d3)

(ii).	Cara Posterior
![trasera](https://github.com/ProfaKeila/The-Groot/assets/112026718/5beda6c1-b0c8-43f2-b230-fd66f933e21e)

(iii). Cara Izquierda
![lat1](https://github.com/ProfaKeila/The-Groot/assets/112026718/98cf4f8a-d144-44e2-957b-3924b24bd66a)

(iv).	Cara Derecha
![lat2](https://github.com/ProfaKeila/The-Groot/assets/112026718/def411bb-de75-47bf-bd12-34f58ff1e1d1)

(v).	Cara Superior
![hub sup](https://github.com/ProfaKeila/The-Groot/assets/112026718/4e526ebf-06bf-4e72-8857-3ad5700ab727)

(vi).	Cara inferior
![inf](https://github.com/ProfaKeila/The-Groot/assets/112026718/c8fc86aa-ca61-4bdf-86af-cee00f783939)

------------

## **Enlace al video en Youtube**:
Diseño del Robot

[![Alt text](https://youtu.be/wnwVR5ICpu8)

Dando vueltas

Round 1 Fixed center / Ronda 1 Centro Fijo
[![Alt text](https://user-images.githubusercontent.com/112026718/188289446-870fff3d-0013-49d5-9703-20cf0f7fa475.gif)](https://youtu.be/2XueAw2JKws)

Round 1 Mobile Center / Ronda 1 Centro Móvil
[![Alt text](https://user-images.githubusercontent.com/112026718/201544888-fc7a2e47-9dd8-4d0d-9cae-53285449172e.gif)](https://youtu.be/p-i_P51mGfk)

Evitando obstaculos

[![Alt text](https://user-images.githubusercontent.com/112026718/188289545-f1eeb4a0-b45a-4bdb-90fe-f92e0548286c.gif)](https://youtu.be/pBEFuexwxLQ)

Diagrama esquematico:
A continuación se presenta un boceto de todos los componentes electrónicos utilizados.

![guif construcción](https://user-images.githubusercontent.com/112026718/201570555-7cdde8ad-c253-4419-8a43-3e3caded1163.gif)


![Alt text](https://user-images.githubusercontent.com/112026718/201570175-7d4e6c79-e1e1-46af-abbf-3495805a4f43.gif)



Componentes Electromecanicos:
El Robot Matt se construyo utilizando el kit de robótica de LEGO MINDSTORMS Inventor 51515. Ahora una breve descripción de cada componente electromecanico utilizado para la creación de este robot autónomo.

Los alerones funcionan para reducir la resistencia del aire, y descubrimos que al utilizarlo, aumenta la velocidad 40%, dandole mayor rendimiento aerodimanico, además de que permite el enfriamento de los motores, adicional a ello la carga aerodinamica se adhiera al piso, y de mejores giros.

Motores: 
1.	**Motores traseros**: Estos tres motores interconectados en la rueda, en el motor trasero izquierdo en el puerto E, posee un engranaje que permite la rotación de las ruedas traseras, y son los pilares del movimiento del este robot autónomo, por poseer tracción trasera, se utilizan dos para tener mayor tracción y torque en el movimiento.
2.	**Motor delantero**: Este motor es quien le da la dirección al robot, y le permite el movimiento en los diferentes sentido.

Sensores:
1.	Cámara HuskyLens: tomada como reemplazo de sensor de color del set del inventor kit,  adopta la nueva generación de chips de IA, es utilizada para el reconocimiento de color y forma de objetos llamados obstáculos. 
2.	Sensor Ultrasonico: Este sensor se utiliza en su mayoría de veces para la medición de distancias y evasión de objetos.
3.	Sensor Giroscopio: Este sensor se utiliza para precisar giros utilizando mejor los ángulos.
Hub: Este componente es el cerebro del robot, es quien indica a los motores que hacer, y recibe la información de los sensores para tomar las decisiones que vuelven a este robot un vehículo autónomo, para su mejor utilidad contiene un botón de inicio /apagado, y otros dos de izquierda y derecha.
