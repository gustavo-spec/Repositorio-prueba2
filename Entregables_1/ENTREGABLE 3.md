# Problemática (Juan)

## **Contexto**

Según la Organización Mundial de la Salud (OMS) se estima que cada año se realizan más de 1 millón de amputaciones de extremidades a nivel global [\[1\]](https://www.zotero.org/google-docs/?ErxRxm). Si bien, la amputación de miembros inferiores es más frecuente que la de miembros superiores, esta última presenta una incidencia considerable. Particularmente en los Estados Unidos, la pérdida de extremidades superiores afecta a más de medio millón de individuos y se espera que esta cifra se duplique para el 2050 [\[2\]](https://www.zotero.org/google-docs/?8JRbvC).   
En el Perú, se estima que 12 600 personas sufren la amputación de un miembro superior de su cuerpo ya sea por causas congénitas o accidentales [\[3\], \[4\]](https://www.zotero.org/google-docs/?HNRZ98). En cualquier caso, independientemente de la causa, la amputación de miembros superiores es devastadora para los pacientes dado el rol fundamental que cumplen estos miembros en la interacción con nuestro entorno [\[2\]](https://www.zotero.org/google-docs/?SoZfHU). La pérdida de independencia y disminución de la calidad de vida son, en términos generales, consecuencias directas de la amputación de miembros superiores.

**¿Por qué es importante para la Ingeniería Biomédica abordar esta temática?**  
Esta temática es relevante en el campo de la Ingeniería Biomédica, debido a que tiene un impacto significativo en la rehabilitación física y en la salud mental del individuo. En este campo se abarca conocimientos de biomecánica y materiales biomédicos, lo que facilita el desarrollo de prótesis avanzadas. [\[5\]](https://www.zotero.org/google-docs/?grMHuz)

## **Definición del problema específico**

Dentro del contexto en el que se desarrolla esta temática, y considerando que el ámbito laboral es un importante en la vida de una persona, planteamos la siguiente problemática:  
Escasez de prótesis que permitan una adecuada reinserción laboral en pacientes con amputación bilateral de miembros superiores que ocupan cargos administrativos en el Perú. En este caso, nos centraremos en el desarrollo de prótesis de brazo, ya que tendrá un uso más frecuente para el paciente que trabaja en este cargo.

## **Impacto**

Los pacientes con amputación presentan serios desafíos para reincorporarse al ámbito laboral, donde el manejo de dispositivos tecnológicos y buena movilidad es fundamental para este ámbito [\[6\]](https://www.zotero.org/google-docs/?V92ZXr).   
Las prótesis limitadas dificultan la realización de tareas administrativas como escribir en una computadora o manejar documentos. Esto puede reducir la capacidad productiva del individuo y aumentar el estrés laboral [\[7\]](https://www.zotero.org/google-docs/?ZW5Ww5).  
Además, puede afectar al estado emocional del paciente, generando frustración, depresión o ansiedad, ya que sienten que no puede contribuir de manera adecuada en su entorno profesional [\[8\]](https://www.zotero.org/google-docs/?DiCF4x).  
Alrededor del 80% de personas están en edad de trabajar. Sin embargo, su derecho a un trabajo decente, es con frecuencia denegado. Las personas con discapacidad experimentan mayores tasas de desempleo e inactividad económica y están en mayor riesgo de una protección social insuficiente la cual es clave para reducir la pobreza extrema [\[9\]](https://www.zotero.org/google-docs/?O4T4my).

# Propuesta de solución (Renzo y Gustavo)

##  	**Descripción**

Esta propuesta presenta un sistema que integra una prótesis transradial con las propiedades de un mouse inalámbrico, que proporciona una serie de movimientos básicos y control de un punzón. Está prótesis utiliza una combinación de sensores, motores y software para permitir una variedad de movimientos naturales.

## **Características:**

* Sistema que integra una prótesis de mano con las funciones de un mouse inalámbrico.  
* Capacidad para realizar movimientos básicos y control de un punzón.  
* Uso de sensores, motores y software para permitir movimientos naturales.  
* Agarre de gancho y llave en la prótesis, replicando funciones básicas del brazo humano.  
* Integración de un mouse inalámbrico con conectividad universal a través de Bluetooth.  
* Control del cursor, clics y tareas digitales mediante la prótesis.

	**Beneficios**  
Con el objetivo de mejorar la calidad de vida del paciente, se recomienda la adaptación de un brazo protésico con agarre tipo gancho y llave. Esto permitirá recrear algunas de las funciones básicas de un brazo humano, facilitando acciones como el agarre con llave y gancho. , lo que puede ayudar a aliviar molestias como el dolor fantasma. Además, se le instalará un mouse inalámbrico para sus actividades laborales, lo que ofrecerá una serie de beneficios adicionales, tales como:

* Mayor adaptabilidad al uso en computadoras y/o dispositivos electrónicos.(conectividad universal; bluetooth)  
* Ahorro de espacio al instalar un mouse en la prótesis y usarlo en conjunto con una conexión inalámbrica.  
* Interacción directa con la tecnología al controlar el cursor, clicks y realizar tareas digitales sin herramientas extra.  
* Mejora la eficacia en el campo laboral en campos administrativos brindando un control preciso del cursor. (A como lo haría un brazo protésico con un mouse físico)  
* Independencia laboral;dando un control de tareas físicas y digitales.  
* Ahorro de costes, al implementar un sistema de control del cursor  en el brazo en vez de implementar un brazo con pluralidad de mecanismos para maniobrar un mouse físico.


## **Viabilidad técnica**

Debido a la evolución constante y el desarrollo avanzado de las tecnologías involucradas, se obtiene una comprensión y visión más definida hacia el prototipo, lo cual es crucial al evaluar su viabilidad técnica, con aspectos como: 

Sensores mioeléctricos:

* Las prótesis mioeléctricas ya utilizan sensores electromiográficos (EMG) que capturan contracciones musculares para controlar el movimiento de la prótesis.  
* Este mismo principio puede adaptarse para controlar tanto los movimientos del brazo protésico como del cursor de la computadora de forma conjunta, utilizando señales musculares para indicar la dirección y acción deseada.   
* Tecnologías como el I-limb quantum el hero arm, entre otros muy conocidos, han dado resultados muy favorables en experimentación y en el mercado

Módulo Bluetooth:

* El módulo bluetooth es esencial en vista al objetivo de conectarse a un dispositivo electrónico de forma inalámbrica.  
* HC-05: Módulo bluetooth económico, utilizado en mayoría de dispositivos con conexión inalámbrica.  
* SoC nRF52840: Un módulo bluetooth avanzado compatible con múltiples protocolos y con simultaneidad.

Procesador:

* Arduino: En vista de necesidad de una placa que conecte entradas y salidas se decidió por arduino, por sus buenos resultados en prótesis (empresa Open Bionic, Man-o-Matic)  
* Se utilizará para leer las acciones dadas de los sensores y del mecanismo del brazo, para diferenciar entre uso normal y uso laboral(bluetooth)

Motor:

* Servomotor: Utilizado en la mayoría de prótesis con tecnología EMG  
* Las tecnologías actuales en motores y actuadores ya han demostrado su efectividad en prótesis avanzadas, lo que sugiere un equilibrio factible en la prótesis mencionada.

Diseño (Estructura): 

* Se busca un diseño con estructura 3D, ya que la aplicación que se busca es de una mano con funcionalidad bluetooth, para ello integrando sensores de lectura distintos a los sensores normales de movimiento regular.  
* De forma que se pueda reducir el peso de la prótesis en vista del esfuerzo diario que supone el usarlo durante una jornada laboral se utiliza un material más ligero, a la vez que cuando se use en la función de mouse, este estará apegado a una superficie para mantener un mejor control del cursor.  
* El diseño 3D se planea con materiales utilizados anteriormente, que hayan mostrado resultados positivos en su uso, tales como el nylon 12( the hero arm) o el Ultra Fuse PLA Apricot Skin- 1,75mm.

# Coherencia (Micaela y Laura)

## **Contexto del proyecto**

Actualmente, existe un creciente cambio en las tendencias de empleo debido al incremento del uso de tecnologías que han terminado por establecer un conjunto nuevo de habilidades necesarias para el trabajador [\[10\]](https://www.zotero.org/google-docs/?9CISxd). En vista de esto y considerando que, además, la mayor parte de individuos con amputación adquirida de miembros superiores están empleados en trabajos mentalmente demandantes que precisamente se benefician del uso de tecnología [\[10\]](https://www.zotero.org/google-docs/?pahQRO), es necesario la invención de prótesis de miembro superior que tengan en cuenta los requerimientos del mercado laboral actual y permitan al paciente retomar su empleo aprovechando el dispositivos electrónicos.

Nuestra propuesta de solución se basa en una prótesis para la parte superior del paciente que integra una mano con propiedades de un mouse inalambrico, esta propuesta la elaboramos en base al contexto general de nuestra paciente, que es una mujer que perdió sus extremidades superiores e inferiores, por lo que, la dejó incapacitada para realizar sus actividades cotidianas con normalidad en especial su trabajo, por lo tanto, nuestra propuesta está mayormente dirigida a que la paciente pueda continuar con su trabajo sin complicaciones. 

Como explicamos anteriormente, la ingeniería biomédica combina principios de ingeniería, medicina y biología, por lo que, nuestra prótesis implica el diseño mecánico basado en la necesidades y posibilidades del cuerpo humano. **Se hace uso de tecnología avanzada como sensores, sin embargo**, el diseño del prototipo no solo se basa en el aspecto estético sino también en la parte de su funcionalidad y que sea elaborado directamente para el paciente con necesidades específicas, es por ello, que la biología y medicina está siempre presente ante la elaboración de una prótesis**.** Este tipo de prótesis contribuye a la rehabilitación de pacientes, mejorando su calidad de vida y autonomía. De manera que, esto es un objetivo fundamental de la ingeniería biomédica, que busca desarrollar tecnologías que faciliten la reintegración social y laboral del paciente.

**Objetivos**   
Nuestro proyecto tiene como objetivo general que la paciente pueda realizar sus actividades cotidianas con total normalidad, de esa forma, desarrollar una prótesis de brazo que integre funciones de escritura y manejo de computadora, permitiendo a la paciente recuperar su capacidad de trabajar de manera eficiente y cómoda sin complicaciones.

Como objetivos específicos tenemos que nuestra propuesta permite darle la movilidad necesaria a la paciente con una facilidad de uso que permita desarrollar un sistema intuitivo que facilite a la paciente aprender a utilizar la prótesis rápidamente, minimizando la curva de aprendizaje. De igual manera, que presente un diseño ergonómico que se ajuste cómodamente a la anatomía de la paciente, garantizando un uso prolongado sin causar fatiga y que sea elaborado con materiales resistentes y fáciles de mantener, asegurando su longevidad y funcionalidad.

Que la prótesis presente un control personalizable posibilitando a que el paciente ajuste el rango de movimiento de la prótesis para adaptarse a su estilo de trabajo y comodidad, de esa manera, puede realizar su trabajo con tranquilidad.

## **Justificación**

Nuestra propuesta, a diferencia de otras alternativas en el mercado, está orientada específicamente a lograr una reinserción laboral de pacientes amputados en un mercado en el que el uso de tecnologías se ha vuelto una necesidad. No existen alternativas accesibles que verdaderamente permitan al usuario hacer uso de dispositivos como un computador con comodidad. Proponemos una opción que facilite la interacción del paciente amputado con un dispositivo electrónico, sin la necesidad de implementar un sistema de control y mecanismo muy complejo que obligue a elevar los precios.

## **Alineación** 

Nos enfocamos en que nuestra propuesta de solución esté dirigida a que la paciente pueda regresara sus actividades cotidianas con normalidad y que pueda continuar con su trabajo, ya que, es su fuente de ingresos en su hogar, es por ello, que la prótesis permitirá que recupere la funcionalidad perdida, facilitando su reintegración al entorno laboral. La propuesta de solución es necesaria en este caso ya que implica un mouse inalambrico, debido a que, la paciente trabaja con dispositivos electrónicos especialmente las computadoras, por ello, la implementación de un mouse le permitirá tipear la información que desee sin demasiado esfuerzo. 

# Resumen

El problema se basa en una paciente quien ha perdido sus miembros superiores e inferiores dejándola sin posibilidades de realizar sus actividades cotidianas como usualmente realizaba en especial su trabajo. Su trabajo consistía en el uso de aparatos electrónicos como la computadora concretamente en tipear información es debido a esto que nuestra propuesta de solución se basa en la creación de una prótesis de brazo que no solo sea estéticamente sino también funcional, en este caso implementar una mano con propiedades de un mouse inalámbrico que le proporcione a la paciente realizar su trabajo con normalidad.

Nuestros puntos clave son el que la parte más importante es hacer que la paciente pueda regresar a su vida laboral porque es su fuente de vida y pueda realizar sus actividades cotidianas por consiguiente nuestra propuesta de solución es relevante, porque dirigimos nuestro principal objetivo a que la protesis pueda realizar movimiento de dedos

Los resultados que esperamos obtener son una mejora de calidad de vida en la paciente en este caso que sea capaz de realizar sus tareas administrativas de manera eficiente, aumentando su autonomía y facilitando su reincorporación laboral, que además de integrar funciones de un mouse inalambrico a la prótesis se espera que la usuaria sea capaz de controlar su computadora de manera fluida mejorando su productividad. Por otro lado, los resultados que esperamos en la prótesis es que le permita a la paciente realizar una gama de movimientos que puedan imitar la funcionalidad de una mano humana como el agarre o la manipulación de los objetos siendo el más importante la interacción con dispositivos digitales,

Con respecto a su proceso de testeo se utilizarán pruebas de uso donde se observará la interacción de la prótesis en diversas tareas administrativas como escribir, manipular objetos, etc, también se usarán entrevistas y encuestas para obtener datos cualitativos y cuantitativos.

# 

# Bibliografía

[https://elperuano.pe/noticia/71659-manos-de-esperanza](https://elperuano.pe/noticia/71659-manos-de-esperanza)

[\[1\]	K. Amaya, L. Farro, y R. Lazarte, “Resolución Directoral N.° 009-2024-SA-DG-INR \- Normas y documentos legales \- Instituto Nacional de Rehabilitación \- Plataforma del Estado Peruano”. Consultado: el 17 de septiembre de 2024\. \[En línea\]. Disponible en: https://www.gob.pe/institucion/inr/normas-legales/5088554-009-2024-sa-dg-inr](https://www.zotero.org/google-docs/?VJp3Qy)  
[\[2\]	E. B. Saltzman, J. T. J. Jerome, y R. G. Gaston, “Current Concepts and Management of Upper Limb Amputees”, *J. Hand Microsurg.*, vol. 15, núm. 4, pp. 245–246, sep. 2023, doi: 10.1055/s-0043-1773775.](https://www.zotero.org/google-docs/?VJp3Qy)  
[\[3\]	“Investigadores de la PUCP fabrican prótesis de mano para mejorar calidad de vida de personas con discapacidad”. Consultado: el 17 de septiembre de 2024\. \[En línea\]. Disponible en: https://www.gob.pe/institucion/concytec/noticias/341401-investigadores-de-la-pucp-fabrican-protesis-de-mano-para-mejorar-calidad-de-vida-de-personas-con-discapacidad](https://www.zotero.org/google-docs/?VJp3Qy)  
[\[4\]	“Manos de esperanza”. Consultado: el 17 de septiembre de 2024\. \[En línea\]. Disponible en: https://elperuano.pe/noticia/71659-manos-de-esperanza](https://www.zotero.org/google-docs/?VJp3Qy)  
[\[5\]	A. Torres Velásquez, C. A. Díaz León, L. F. García Muriel, y M. L. Toro Hernandez, “EL APORTE DE LA BIOMECÁNICA Y LA INGENIERÍA EN REHABILITACIÓN EN LA INGENIERÍA BIOMÉDICA DE LA EIA-CES”, *Rev. Ing. Bioméd.*, vol. 1, núm. 2, pp. 10–13, dic. 2007\.](https://www.zotero.org/google-docs/?VJp3Qy)  
[\[6\]	N. Sarroca Becerrica, “Estudio del comportamiento muscular y estabilidad en pacientes amputados transtibiales. Análisis del impacto de la amputación en la imagen corporal, la autoestima y su calidad de vida”, nov. 2020, Consultado: el 17 de septiembre de 2024\. \[En línea\]. Disponible en: https://hdl.handle.net/20.500.14352/11242](https://www.zotero.org/google-docs/?VJp3Qy)  
[\[7\]	R. Atherton y N. Robertson, “Psychological adjustment to lower limb amputation amongst prosthesis users”, *Disabil. Rehabil.*, vol. 28, núm. 19, pp. 1201–1209, oct. 2006, doi: 10.1080/09638280600551674.](https://www.zotero.org/google-docs/?VJp3Qy)  
[\[8\]	O. Horgan y M. MacLachlan, “Psychosocial adjustment to lower-limb amputation: a review”, *Disabil. Rehabil.*, vol. 26, núm. 14–15, pp. 837–850, ago. 2004, doi: 10.1080/09638280410001708869.](https://www.zotero.org/google-docs/?VJp3Qy)  
[\[9\]	“Discapacidad y trabajo | International Labour Organization”. Consultado: el 19 de septiembre de 2024\. \[En línea\]. Disponible en: https://www.ilo.org/es/resource/discapacidad-y-trabajo](https://www.zotero.org/google-docs/?VJp3Qy)  
[\[10\]	C. Lee, S. Engdahl, A. Riegger, A. Davis, B. M. Kelly, y D. H. Gates, “Employment Status in Individuals with Upper-Limb Amputation: A Survey of Current Trends”, *JPO J. Prosthet. Orthot.*, vol. 34, núm. 2, p. 79, abr. 2022, doi: 10.1097/JPO.0000000000000366.](https://www.zotero.org/google-docs/?VJp3Qy)

