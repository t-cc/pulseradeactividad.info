---
layout: post
date: 2019/05/23
updated: 2020/02/20
title: ¿Como funciona un pulsómetro óptico de muñeca?
published: true

# Forzar url canonica!!
canonical: /como-funciona-pulsometro-optico-de-muneca.html

# Imagen que aparece en resumen de posts.
image: /assets/como-funciona-pulsometro-optico-de-muneca/lectura-de-pulso-con-sensor-optico.webp
image_fallback: /assets/como-funciona-pulsometro-optico-de-muneca/lectura-de-pulso-con-sensor-optico.png
image_alt: Funcionamiento de un sensor óptico de pulso.
image_width: 700
image_height: 204

# Imagen para metadata (Google discover, redes sociales, etc...)
meta_image: /assets/como-funciona-pulsometro-optico-de-muneca/lectura-de-pulso-con-sensor-optico_lg.png
meta_image_width: 1200
meta_image_height: 334


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
  <amp-img alt="{{ page.image_alt | default: page.title }}" layout="responsive"
           width="{{ page.image_width }}" height="{{ page.image_height }}" src="{{ page.image }}">
    {% if page.image_fallback %}
    <amp-img fallback alt="{{ page.img_alt | default: page.title }}" layout="responsive"
             width="{{ page.image_width }}" height="{{ page.image_height }}" src="{{ page.image_fallback }}">
    </amp-img>
    {% endif %}
  </amp-img>
  {% if page.image_alt %}
    <figcaption>
      {{ page.image_alt }}
    </figcaption>
  {% endif %}
  </figure>
{% endif %}

La mayoría de los **pulsómetros de muñeca** utilizan también el 
**acelerómetro integrado** como ayuda para saber si el pulso se está leyendo bien. 
Incluso algunos utilizan la información del acelerómetro para *interpretar* 
mejor los datos recogidos por el sensor óptico, maquillando en cierta medida 
los datos del pulso.

### ¿Que factores externos influyen en la correcta lectura del pulso?

Lo primero es la correcta colocación de la pulsera. Bien sujeta y **un par de 
centímetros por encima del hueso de la muñeca**. 
Es necesario que la pulsera no se mueva mucho para no captar luz del exterior 
que pudiese falsear las lecturas.

<figure markdown="0">
  <amp-img alt="Como ponerse la pulsera de actividad para una correcta medición del pulso." 
      width="700" height="510" layout="responsive"
      src="/assets/como-funciona-pulsometro-optico-de-muneca/como-colocar-la-pulsera-en-la-muneca.webp">
      <amp-img fallback alt="Como ponerse la pulsera de actividad para una correcta medición del pulso." 
          width="700" height="510" layout="responsive"
          src="/assets/como-funciona-pulsometro-optico-de-muneca/como-colocar-la-pulsera-en-la-muneca.jpg">
      </amp-img>
  </amp-img>
  <figcaption>
    Como ponerse la pulsera de actividad.
  </figcaption>
</figure>


Otros factores que influyen en la lectura son:

* El color de la piel. Cuanto más clara es la piel mas precisas serán las lecturas. 
  Incluso la presencia de mucho vello puede afectar negativamente a las lecturas.
* La temperatura, que influye en la perfusión tisular de la sangre. 
  A más frio peores lecturas.


### ¿Que factores de fabricación influyen en la correcta lectura del pulso?

Indudablemente lo primero es la calidad del sensor, pero la precisión de la 
lectura puede mejorarse mediante algoritmos y la incorporación de datos 
de otros sensores.

Realizando un pequeño examen visual a una **pulsera de actividad** pero 
podemos saber mucho del **sensor de ritmo cardíaco** si nos fijamos en:

1.  **El tamaño del sensor**. Desgraciadamente el tamaño importa, pero hasta 
cierto límite. Cuanta mas área pueda "ver" el sensor mejor, pero siempre que 
la luz de los emisores led pueda reflejarse en el a través de la piel. 
En un sensor muy grande algunas zonas pueden quedar a la *sombra* y no servir para nada.
2.  **La potencia de la luz**. Cuanta más potencia más fiables serán las 
lecturas y menos interferencias de la luz ambiente.
3.  **Las longitudes de onda empleadas**. Usar luces de más colores mejora 
mucho la calidad de las lecturas. Muchos tienen sólo luz verde, mientras 
que los más modernos cuentan LEDs infrarrojos y/o azules.
4.  **La distancia entre la luz y el sensor**. Si la luz está muy cerca del 
sensor, esta puede transmitirse horizontalmente a través de la capa superior 
de la piel (en vez de reflejarse en la sangre) dando lugar a falsas lecturas. 
El sensor recibirá demasiada luz y estará "cegado". Esto pasa mucho con 
sensores pequeñitos de pulseras baratas y empeora muchísimo cuando comienzas a sudar.
5.  **La cantidad de sensores**. Actualmente pocas **pulseras de actividad** 
cuentan con sólo un sensor. Sin embargo, si hay más de uno deben cumplir los 
puntos previos para obtener buenas lecturas.
6. **Los sensores adicionales**. Por ejemplo, un Apple Watch 4 o posterior 
incluye unos electrodos de cristal a través de los que puede medir los 
impulsos eléctricos del corazón. Las **pulseras de actividad** y **relojes deportivos**
equipados con este sensor incluso podrán realizarte un electrocardiograma básico.


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


### ¿Qué pulseras de actividad cuentan con un buen pulsómetro?

A continuación os dejamos una recopilación de las **mejores pulseras de actividad** 
con un **buen pulsómetro**:

* **Fitbit Charge 3**, la pulsera de actividad por excelencia.
* **Garmin Vivosmart 4**, la que cuenta con mejor monitarización del sueño.
* **Polar A370**, con la pantalla más grande y en color.
* **Fitbit Inspire HR**, la misma calidad de la Charge 3 pero un poco más económica.


<div class="amz_wrapper amz_wrapper--2cols" markdown="0">

  <div class="amz_cuadro">
    <h4 class="amz_cuadro__title">Fitbit Charge 3</h4>
      <amp-img alt="Fitbit Charge 3" 
          width="355" height="355" layout="responsive"
          src="/assets/amz/fitbit-charge-3.webp">
        <amp-img fallback alt="Fitbit Charge 3" 
          width="355" height="355" layout="responsive"
          src="/assets/amz/fitbit-charge-3.jpg">
        </amp-img>
      </amp-img>
    <a class="btn amz_cuadro__btn" href="https://amzn.to/2HkF0A7" target="_blank">
      Ver precio en Amazon
    </a>
  </div>

  <div class="amz_cuadro">
    <h4 class="amz_cuadro__title">Garmin Vivosmart 4</h4>
      <amp-img alt="Garmin Vivosmart 4" 
          width="355" height="355" layout="responsive"
          src="/assets/amz/garmin-vivosmart-4.webp">
        <amp-img fallback alt="Garmin Vivosmart 4" 
          width="355" height="355" layout="responsive"
          src="/assets/amz/garmin-vivosmart-4.jpg">
        </amp-img>
      </amp-img>
    <a class="btn amz_cuadro__btn" target="_blank"
      href="https://www.amazon.es/gp/search/ref=as_li_qf_sp_sr_tl?ie=UTF8&tag=pulseradeac06-21&keywords=garmin vivosmart 4&index=aps&camp=3638&creative=24630&linkCode=ur2&linkId=7ea9cef5f6db2fee8ed1995bb036c4b9">
      Ver precio en Amazon
    </a>
  </div>

  <div class="amz_cuadro">
    <h4 class="amz_cuadro__title">Polar A370</h4>
      <amp-img alt="Fitbit Charge 3" 
          width="355" height="355" layout="responsive"
          src="/assets/amz/polar-a370.webp">
        <amp-img fallback alt="Polar A370" 
          width="355" height="355" layout="responsive"
          src="/assets/amz/polar-a370.jpg">
        </amp-img>
      </amp-img>
    <a class="btn amz_cuadro__btn" href="https://amzn.to/38vmgK1" target="_blank">
      Ver precio en Amazon
    </a>
  </div>

  <div class="amz_cuadro">
    <h4 class="amz_cuadro__title">Fitbit Inspire HR</h4>
      <amp-img alt="Fitbit Inspire HR" 
          width="355" height="355" layout="responsive"
          src="/assets/amz/fitbit-inspire-hr.webp">
        <amp-img fallback alt="Fitbit Inspire HR" 
          width="355" height="355" layout="responsive"
          src="/assets/amz/fitbit-inspire-hr.jpg">
        </amp-img>
      </amp-img>
    <a class="btn amz_cuadro__btn" href="https://amzn.to/2tZd1CX" target="_blank">
      Ver precio en Amazon
    </a>
  </div>

</div>

<br><br>

