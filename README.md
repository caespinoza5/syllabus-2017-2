# syllabus

IIC2343 Arquitectura de Computadores (I/2016)
Proyecto Semestral
Implementación y programación de un computador básico

1. Motivación:
El objetivo principal de este curso es que el alumno entienda qué es un computador, conozca cuáles son
sus partes y sus funcionesciones y sea capaz de realizar programas para el computador. Para lograr adquirir
estos conocimientos y habilidades se requiere por una parte adquirir el conocimiento teórico y conceptual de
lo que es un computador, pero también ser capaz de llevarlo a la práctica. El proyecto semestral corresponde
a la parte práctica del curso, en la cual los alumnos deberán implementar un computador básico completo
y desarrollar programas ocupando su computador.

2. Descripción:
El proyecto consiste, en su primera etapa, en implementar un computador básico a nivel de hardware,
utilizando los conocimientos vistos en clases. Dado que implementar todos los componentes del computador
directamente con componentes físicos supera las habilidades enseñadas en el curso, se utilizarán FPGAs,
que son componentes de hardware que permiten programar en software los circuitos para luego traspasarlos
automáticamente al hardware y emularlos.

En particular, se ocupará para desarrollar el proyecto la placa de desarrollo Basys3 de Digilent, la cual
cuenta con un FPGA Xilinx Artix-7, una pantalla LED, botones e interruptores. Esta placa puede ser
programada mediante el ambiente de desarrollo Vivado WebPack de Xilinx, a través del cual se deberán
programar los componentes del computador, para luego enviarlos a la placa, que se encargará automáticamente
de generar las conexiones necesarias para construir la representación física de dichos componentes.
De esta forma, los alumnos trabajarán a nivel lógico sólo con elementos de software, pero podrán probar sus
componentes con hardware real.

El proyecto consistirá en entregas incrementales que permitirán a los alumnos construir poco a poco el
computador, yendo a la par con la materia vista en el curso. Una vez que se complete un computador funcional
se agregará el elemento de programación del computador, para lo cual se les pedirá escribir programas
que puedan ser ejecutados en este, cumpliendo distintas funciones según sean solicitadas. Estos programas
irán aumentando en dificultad a través de las entregas, según las nuevas capacidades que se vayan agregando
en paralelo a el computador.

Al analizar el semestre los alumnos habrán desarrollado un computador enteramente funcional, con la
mayor parte de los elementos fundamentales vistos en el curso. Adicionalmente, habrán también desarrollado
diversos programas escritos en el lenguaje propio de su computador, los cuales variarán desde programas
simples de prueba a programas más avanzados con interacción del usuario.

3. Metodología:
El proyecto será realizado en grupos de 5 alumnos, y estará divido en 5 entregas incrementales y
todas son obligatorias excepto por la entrega 5, por lo que es fundamental que se avance lo solicitado en
todas las entregas para no quedarse atrás. En cada entrega se solicitará enviar los archivos de los componentes
de hardware implementados, un informe evaluado y, cuando corresponda, los archivos de los programas
desarrollados. Todos los archivos solicitados deben estar presentes en la rama Master de un repositorio Git
que se les asignará.

Al comenzar el semestre se le entregará a cada grupo una placa de desarrollo, la cual podrán usar fuera
de la universidad. La placa debe ser tratada con sumo cuidado para evitar dañarla, y deberán
devolverla al final del semestre en las mismas condiciones en que fue entregada.

4. Evaluación
Cada entrega del proyecto se evaluara de forma grupal y se ponderara por un porcentaje de coevaluacion
para calcular la nota de cada alumno.

Dado lo anterior, dentro de las primeras 24 horas posteriores a cada entrega, todos los alumnos
deberan completar de forma individual y obligatoria el formulario web que los ayudantes pondran a su
dispocicion, repartiendo un maximo de 4 puntos, con hasta un decimal, entre sus compa~neros. La suma de
todos los puntos obtenidos por el integrante, sp, será utilizada para el calculo de la nota de cada entrega, lo
que puede hacer que este repruebe el curso.

La nota de cada entrega se calcula de la siguiente forma:
NotaEntregaindividual = mn(kg  NotaEntregagrupal;NotaEntregagrupal + 0; 5)
donde,

kg = sp+3

Los alumnos que no cumplan con enviar la coevaluacion en el plazo asignado tendran un descuento de
0.5 puntos en su nota de la entrega correspondiente.

La nota individual del proyecto se calcula de la siguiente forma:
NotaP royectoindividual = E10.15 + E20.25 + E30.3 + E40.2 + E50.1

Pero, si no realizan la entrega 5:

NotaProyectoindividual = (E10.15+E20.25+E30.3+E40.2+E50.1)/0.9

5. Planificación:

El calendario tentativo de las entregas y sus ponderaciones se presentan a continuación:

Entrega 1: Entrega: Viernes 1 de Abril a las 23:59 horas. (15%)
Entrega 2: Entrega: Viernes 22 de Abril a las 23:59 horas. (25%)
Entrega 3: Entrega: Viernes 20 de Mayo a las 23:59 horas. (30%)
Entrega 4: Entrega: Viernes 17 de Junio a las 23:59 horas. (20%)
Entrega 5: Entrega: Viernes 1 de Julio a las 12:00 horas. (10%)

Se realizarán ayudantías especialmente enfocadas en capacitar a los alumnos en el uso de las herramientas
de software y hardware necesarias en el proyecto. El calendario tentativo de las ayudantías se presenta a
continuación. Se avisará durante el semestre si se realizarán ayudantías adicionales a las aquí indicadas.

Ayudanta 1: Lunes 28 de Marzo.
Ayudanta 2: Lunes 18 de Abril.
Ayudanta 3: Lunes 16 de Mayo.
Ayudanta 4: Lunes 30 de Mayo.

6. Contacto:

Francesca Lucchini - flucchini@uc.cl

