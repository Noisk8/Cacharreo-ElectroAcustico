# Cacharreo-ElectroAcustico
Asimtria.org | La Jaquer Es Cool

En el marco de la residencia de Asimtria.org en Platohedro entre otros proyectos desarrollados documentamos el como hacer los dispositovos vistos durante los talleres (Contrucción electroacustica.

1 

En la primera etapa del ciclo de talleres Marco valdivia brindo a los participantes unas palabras y algunos refentes teoricos a cerca de que es el mundo de la electroacustica y como a partir de practicas experimentales podemos acercanos a esa materia.

 1.1 Acercamientos teoricos sobre la electroacustica. 
 
 Referentes:
 
 * ¿Cómo viaja el Sonido? https://www.youtube.com/watch?v=W7Z5S3wPKEQ
 * Fundamentos del sonido https://www.youtube.com/watch?v=NK81fk7fFU8
 * Efecto Piezoléctrico https://www.youtube.com/watch?v=1UMFcOSMJcA
 
 1.2 Construcción de Piezo electrico. 
 
El piezoeléctrico o micrófono de contacto, es un componente que a partir del fenómeno piezoeléctrico, es decir por medio de la presión y/o vibración sobre sí mismo o la superficie que lo soporta, puede contribuir en amplificar y/o registrar ciertos sonidos a partir del contacto, y también puede convertir en sonido las ondas eléctricas, es decir funciona como micrófono y como parlante. 

Para el prototipo conectamos el piezoeléctrico con un jack macho para poder ser conectado a un amplificador. 
 
 Materiales 
 
  * 1 Piezoeléctrico
  * 2 Cables 
  * 1 Jack de 1/4
  
  ![Piezo Conexion](https://github.com/Noisk8/Cacharreo-ElectroAcustico/blob/master/piezo-directo.jpg)
  
Como vemos el piezo es una pieza simple que consta de dos circulos, en el centro uno blanco que es el positivo, y otro circulo amarillento que es la tierra. De ahí con la ayuda de dos cables estaño y cautin sacamos dos terminales de los circulos que luego van conectadas al plug como lo indica la imágen. 
 
2 Construcción de Amplificador e Hidrofono.

2.1 A partir de un chip Lm386 construimos un circuito electronico que permitiera recibir la señal del piezo electrico y amplificar al mismo tiempo. 

Materiales.

* 1 Circuito Integrado Lm386 
* 1 Condensador Ceramico de 104 nf
* 1 Condensador Electrolitico 470 uf
* 1 Portapila de 9V 
* 1 Placa de cobre agujerada
* 4 Cables
* 2 Jack hembra

![Esquemático](https://github.com/Noisk8/Cacharreo-ElectroAcustico/blob/master/g4692.png)

La función de este circuito consiste en amplificar las señales eléctricas que provienen del piezoeléctrico, las señales que recibe son por medio del (IN Pin3) y a través del (OUT pin5) entrega la señal amplificada.

Como podemos observar en el esquemático el pin 3 está dispuesto para recibir señal, en nuestro caso del piezoelectríco, y el pin 5 es el encargado de amplificar, por lo tando debe de ser conectado al parlante o sistema de amplificación.

En este caso vamos a colocar jacks embras de un cuarto en los pines 3 y 5.


2.2 Con la premisa del piezo electrico adaptamos un par de acrílicos para usar el piezoeléctrico como hidrófono.

Materiales.

* 1 Piezoeléctrico con jack
* 2 Laminas de Acrilico de 5cm de diámetro
* Silicona y aplicador

![Foto Hidrofono](https://github.com/Noisk8/Cacharreo-ElectroAcustico/blob/master/hidrofono.jpg)
