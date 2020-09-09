---
layout: post
date: 2019/05/10
updated: 2020/02/20
autor: Pulsera de Actividad
title: >
  ¿Como funciona un pulsómetro óptico de muñeca? 
  ¿Cuales son sus ventajas y puntos débiles?
published: true
en_portada: true

description: >
  Aprende como funciona un pulsómetro óptico para poder elegir el mejor.
  ¿Cuales son sus puntos débiles y fuertes? ¿Dan lecturas correctas? 
  ¿Cuales son los mejores?
  
# Imagen que aparece en resumen de posts.
image:
  file: /assets/como-funciona-pulsometro-optico-de-muneca/lectura-de-pulso-con-sensor-optico.webp
  fallback: /assets/como-funciona-pulsometro-optico-de-muneca/lectura-de-pulso-con-sensor-optico.png
  alt: Funcionamiento de un sensor óptico de pulso.
  width: 700
  height: 204
  # Imagen para metadata (Google discover, redes sociales, etc; 16:9 1200x675 | 4:3 1200x900 | 1:1 1000x100)
  16x9: /assets/como-funciona-pulsometro-optico-de-muneca/lectura-de-pulso-con-sensor-optico-16x9.png
  4x3: /assets/como-funciona-pulsometro-optico-de-muneca/lectura-de-pulso-con-sensor-optico-4x3.png
  1x1: /assets/como-funciona-pulsometro-optico-de-muneca/lectura-de-pulso-con-sensor-optico-1x1.png

# @see: https://www.google.com/search?q=optical+pulse+sensor+technology+how+it+works
# @see: https://valencell.com/blog/2015/10/optical-heart-rate-monitoring-what-you-need-to-know/
# @see: https://valencell.com/blog/2017/03/webinar-building-wearable-heart-rate-monitoring/
# @see: https://www.quora.com/How-do-optical-heart-rate-sensors-work
---


Seguro que os habéis preguntado más de una vez como funciona un **pulsómetro de muñeca**. 
¿Como podrá este aparatito **medir mi pulso**? La respuesta es muy sencilla:

> Un **pulsómetro óptico** mide tu pulso simplemente *mirando* y *contando* 
  cuantas veces pasa la sangre por tus arterias.

Parece sencillo ¿no? El pulsómetro emite una luz sobre tu muñeca y a partir de 
la luz reflejada puede saber si el corazón está bombeando en ese momento o no.

{% if page.image %}
<figure markdown="0">
  <amp-img alt="{{ page.image.alt | default: page.title }}" layout="responsive"
           width="{{ page.image.width }}" height="{{ page.image.height }}" src="{{ page.image.file }}">
    {% if page.image.fallback %}
    <amp-img fallback alt="{{ page.img.alt | default: page.title }}" layout="responsive"
             width="{{ page.image.width }}" height="{{ page.image.height }}" src="{{ page.image.fallback }}">
    </amp-img>
    {% endif %}
  </amp-img>
  {% if page.image.alt %}
    <figcaption>
      {{ page.image.alt }}
    </figcaption>
  {% endif %}
  </figure>
{% endif %}

Esta técnica se denomina *fotopletismografía* o *PPG* (de Photo Plethysmo Graphy),
y consiste, como os comentaba, en iluminar los vasos subcutáneos y medir la luz
reflejada, que variará en dependiendo de la cantidad de *hematíes* (glóbulos rojos)
que circulan en cada momento.
Así se consigue **detectar cambios en el volumen de sangre**, que se corresponden 
directamente con cada latido de nuestro corazón.

La mayoría de los **pulsómetros de muñeca** utilizan también el 
**acelerómetro integrado** como ayuda para saber si el pulso se está leyendo bien. 
Incluso algunos utilizan esta información para *interpretar* 
mejor los datos recogidos por el sensor óptico, "maquillando" en cierta medida 
los datos del pulso.


## ¿Pueden leer más cosas a parte del pulso?


Normalmente, estos sensores emiten una luz verde para *ver* cuando circula más sangre,
pero la inclusión de más tipos de luz permite medir más cosas. Por ejemplo, añadiendo
luces rojas e infrarrojas se puede medir la **saturación de oxígeno en sangre** (SpO2).
Como la *oxihemoglobina* (HbO2) y la *desoxihemoglobina* (Hb) absorben de diferente forma
estas longitudes de onda (roja e infrarroja) el dispositivo puede *saber* cuando la
sangre transporta oxígeno o no. 

Realmente un dispositivo de este tipo mide normalmente las *variaciones de 
saturación de oxígeno en sangre* y no el valor concreto de SpO2, pero aún así, 
si detecta una variación amplia puede alertarte de un posible problema de salud.

Adicionalmente, al medir la variación de oxígeno puede saber también cuando estás 
respirando. Un uso muy típico de esto es en las **sesiones de respiración guiadas**
que ofrecen la mayoría de [**dispositivos de calidad**](/mejores-pulseras-de-actividad.html).


## ¿Que factores externos influyen en la correcta lectura del pulso?

Lo primero es la correcta colocación de la pulsera. Bien sujeta y **un par de 
centímetros por encima del hueso de la muñeca**. Es necesario que la pulsera 
no se mueva mucho para no captar luz del exterior que pudiese falsear las lecturas.

<figure markdown="0">
  <amp-img alt="Como ponerse la pulsera de actividad para una correcta medición del pulso." 
      width="700" height="510" layout="responsive"
      src="/assets/como-funciona-pulsometro-optico-de-muneca/como-colocar-la-pulsera-en-la-muneca.webp">
      <amp-img fallback alt="Como ponerse la pulsera de actividad para una correcta medición del pulso." 
          width="700" height="510" layout="responsive"
          src="/assets/como-funciona-pulsometro-optico-de-muneca/como-colocar-la-pulsera-en-la-muneca.png">
      </amp-img>
  </amp-img>
  <figcaption>
    Como ponerse la pulsera de actividad.
  </figcaption>
</figure>


Otros factores que influyen en la lectura son:

* El **color de la piel**. Cuanto más clara es la piel mas precisas serán las lecturas. 
  Incluso la presencia de mucho vello, y obviamente los tatuajes, puede afectar 
  negativamente a las lecturas.
* La **temperatura**, que influye directamente en la perfusión tisular de la sangre. 
  A más frío peores lecturas, ya que el cuerpo enviará menos sangre a las zonas
  superficiales para perder menos calor.
* Los **movimientos irregulares** empeoran la calidad de las lecturas. Esto se debe
  a que muchos pulsómetros "maquillan" por software sus resultados con la 
  información obtenida del acelerómetro integrado, de ahí que funcionen mejor
  en deportes con movimientos rítmicos.


## ¿Que factores de fabricación influyen en la correcta lectura del pulso?

Indudablemente lo primero es la calidad del sensor, pero la precisión de la 
lectura puede mejorarse mediante algoritmos y la incorporación de datos 
de otros sensores.

Realizando un pequeño examen visual a una [**pulsera de actividad**](/mejores-pulseras-de-actividad.html) 
pero podemos saber mucho del **sensor de ritmo cardíaco** si nos fijamos en:

1.  **El tamaño del sensor**. Desgraciadamente el tamaño importa, pero hasta 
  cierto límite. Cuanta mas área pueda "ver" el sensor mejor, pero siempre que 
  la luz de los emisores LED pueda reflejarse en el a través de la piel. 
  En un sensor muy grande algunas zonas pueden quedar a la *sombra* y no 
  servir para nada.

2.  **La potencia de la luz**. Cuanta más potencia más fiables serán las 
  lecturas y menos interferencias de la luz ambiente.

3.  **Las longitudes de onda empleadas**. Usar luces de más colores mejora 
  mucho la calidad de las lecturas. Muchos tienen sólo luz verde, mientras 
  que los más modernos cuentan LEDs infrarrojos y/o azules.

4.  **La distancia entre la luz y el sensor**. Si la luz está muy cerca del 
  sensor, esta puede transmitirse horizontalmente a través de la capa superior 
  de la piel (en vez de reflejarse en la sangre) dando lugar a falsas lecturas. 
  El sensor recibirá demasiada luz y estará "cegado". Esto pasa con 
  sensores pequeñitos de [pulseras baratas](/mejores-pulseras-de-actividad-baratas.html) 
  y empeora muchísimo cuando comienzas a sudar.

5.  **La cantidad de sensores**. Actualmente pocas [**pulseras de actividad**](/mejores-pulseras-de-actividad.html) 
  cuentan con sólo un sensor. Sin embargo, si hay más de uno deben cumplir los 
  puntos previos para obtener buenas lecturas.

6. **Los sensores adicionales**. Por ejemplo, un Apple Watch 4 o posterior 
  incluye unos electrodos de cristal a través de los que puede medir los 
  impulsos eléctricos del corazón. Las [**pulseras de actividad**](/mejores-pulseras-de-actividad.html)  
  y [**relojes deportivos**](/mejores-pulseras-de-actividad.html) 
  equipados con este sensor incluso podrán realizarte un electrocardiograma básico.

7. **La potencia de procesado**. Los datos obtenidos por todos los sensores tienen
  que ser interpretados, procesados y *traducidos*, siendo necesario una CPU 
  potente (para lo que puede caber en una pulsera). Todo esto empeora con la 
  inclusión de más sensores, que si bien mejoran las lecturas introducen más 
  datos que leer y procesar, introduciendo retardos al mostrar los datos.


<figure markdown="0">
  <amp-img alt="Sensor de pulso cardíaco de un Apple Watch I." 
      width="700" height="525" layout="responsive"
      src="/assets/como-funciona-pulsometro-optico-de-muneca/apple-watch-1-sensor-de-ritmo-cardiaco.webp">
    <amp-img fallback alt="Sensor de pulso cardíaco de un Apple Watch I." 
      width="700" height="525" layout="responsive"
      src="/assets/como-funciona-pulsometro-optico-de-muneca/apple-watch-1-sensor-de-ritmo-cardiaco.jpg">
    </amp-img>  
  </amp-img>
  <figcaption>
    Sensor de pulso cardíaco de un Apple Watch I. Fuente: ifixit.com
  </figcaption>
</figure>


## ¿Como son de fiables las lecturas de un pulsómetro óptico?

Han corrido ríos de tinta sobre este tema, y hay multitud de estudios con resultados
dispares. 

Algunos que **el error puede ser del 13%** y otros lo sitúan sobre el 6%. Todo depende
del dispositivo que se analice (no es lo mismo incluir en el estudio 
[pulseras de actividad baratas](mejores-pulseras-de-actividad-baratas.html) 
que [dispositivos premium](/mejores-pulseras-de-actividad.html) ), y del tipo de 
actividad que se monitorice.
Tradicionalmente los pulsómetros ópticos **dan peores resultados cuanto más alta
es la frecuencia cardíaca** o cuanto mayores son las variaciones. Además son un 
poco *lentos*, mostrando un pulso más bajo que el real cuando se inicia la 
actividad o cuando entras en un intervalo de alta intensidad.

Obviamente, **non son dispositivos tan precisos como las bandas pectorales**, pero 
los fabricantes ya han apostado firmemente por ellos, e irán introduciendo novedades
que progresivamente mejoren la precisión de sus lecturas.

Sin embargo, presentan una clarísima ventaja respecto a los dispositivos pectorales:
Pueden **medir tu pulso día y noche**, lo que les permite calcular con precisión
tu estado de forma, tus pulsaciones en reposo, tu frecuencia cardíaca de reserva,
e incluso decidir a que hora del día te conviene más entrenar.


## ¿Qué pulseras de actividad cuentan con un buen pulsómetro?

A continuación os dejamos una recopilación de las [**mejores pulseras de actividad** ](/mejores-pulseras-de-actividad.html)
con un **buen pulsómetro**:

* **Fitbit Charge 3 y 4**, la pulsera de actividad por excelencia.
* **Garmin Vivosmart 4**, la que cuenta con mejor monitorización del sueño.
* **Polar A370**, con la pantalla más grande y en color.
* **Fitbit Inspire HR**, la misma calidad de la Charge 3 pero un poco más económica.


<div class="amz_wrapper amz_wrapper--2cols" markdown="0">
  
  {% include amz/cuadro/fitbit-charge-4-textil.html %}
  
  {% include amz/cuadro/garmin-vivosmart-4.html %}
  
  {% include amz/cuadro/polar-a370.html %}

  {% include amz/cuadro/fitbit-inspire-hr.html %}

</div>

<br><br>

