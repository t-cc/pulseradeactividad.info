---
layout: post
title: ¿Como funciona un pulsómetro óptico de muñeca?
published: true
image: /assets/images/2019/05/lectura-de-pulso-con-sensor-optico.jpg
image_width: 700
image_height: 204
# @see: https://www.google.com/search?q=optical+pulse+sensor+technology+how+it+works
# @see: https://valencell.com/blog/2015/10/optical-heart-rate-monitoring-what-you-need-to-know/
# @see: https://valencell.com/blog/2017/03/webinar-building-wearable-heart-rate-monitoring/
# @see: https://www.quora.com/How-do-optical-heart-rate-sensors-work
---

Seguro que os habéis preguntado más de una vez como funciona un pulsómetro de muñeca. ¿Como podrá este aparatito 
medir mi pulso? La respuesta, por lo menos a groso modo es muy sencilla:

> Un pulsómetro óptico mide tu pulso simplemente *mirando* y *contando* cuantas veces pasa la sangre por tus arterias.

Parece sencillo ¿no? Bien, realmente no es tan sencillo, pero ese es el principio básico. Así de simple, el pulsómetro 
emite una luz sobre tu muñeca y a partir de la luz reflejada puede saber si el corazón está bombeando en ese momento o no.

<amp-img width="700" height="204" layout="responsive"
alt="Lectura de pulso con un sensor óptico" 
src="/assets/images/2019/05/lectura-de-pulso-con-sensor-optico.webp">
    <amp-img fallback width="700" height="204" layout="responsive"
        alt="Lectura de pulso con un sensor óptico" 
        src="/assets/images/2019/05/lectura-de-pulso-con-sensor-optico.jpg"></amp-img>
</amp-img>

La mayoría de los **pulsómetros de muñeca** utilizan también el **acelerómetro integrado** como ayuda para saber si
el pulso se está leyendo bien. Incluso algunos utilizan la información del acelerómetro para *interpretar* mejor los
datos recogidos por el sensor óptico, maquillando en cierta medida los datos del pulso.

### ¿Que factores externos influyen en la correcta lectura del pulso?

Lo primero es la correcta colocación de la pulsera. Bien sujeta y un par de centímetros por encima del hueso de la
muñeca. Es necesario que la pulsera no se mueva mucho y no capte luz del exterior que pudiese falsear las lecturas.


<amp-img alt="Como ponerse la pulsera de actividad para una correcta medición del pulso." 
    width="700" height="510" layout="responsive"
    src="/assets/images/2019/05/como-colocar-la-pulsera-en-la-muneca.webp">
    <amp-img fallback alt="Como ponerse la pulsera de actividad para una correcta medición del pulso." 
        width="700" height="510" layout="responsive"
        src="/assets/images/2019/05/como-colocar-la-pulsera-en-la-muneca.jpg">
    </amp-img>
</amp-img>


Otros factores que influyen en la lectura son:

* El color de la piel. Cuanto más clara es la piel mas precisas serán las lecturas. Incluso la presencia de mucho vello
puede afectar negativamente a las lecturas.
* La temperatura, que influye en la perfusión tisular de la sangre. A más frio hace peores lecturas.


### ¿Que factores de fabricación influyen en la correcta lectura del pulso?

Indudablemente lo primero es la calidad del sensor, pero la precisión de la lectura puede mejorarse mediante algoritmos
y la incorporación de datos de otros sensores.

Realizando un pequeño examen visual a una **pulsera de actividad** no vamos a saber nada acerca de los algoritmos que
usa internamente, pero podemos saber mucho del **sensor de ritmo cardíaco** si nos fijamos en:

1.  El tamaño del sensor. Desgraciadamente el tamaño importa, pero hasta cierto límite. 
Cuanta mas área pueda "ver" el sensor mejor.
2.  La potencia de la luz. Cuanta más potencia más fiables serán las lecturas y menos interferencias de la luz ambiente.
3.  Las longitudes de onda empleadas. Usar luces de más colores mejora mucho la calidad de las lecturas. Muchos tienen 
sólo luz verde, mientras que los más modernos cuentan con más colores.
4.  La distancia entre la luz y el sensor. Si la luz está muy cerca del sensor, esta puede transmitirse horizontalmente 
a través de la capa superior de la piel (en vez de reflejarse en la sangre) dando lugar a falsas lecturas. El sensor 
recibirá demasiada luz y estará "cegado". Esto pasa mucho con sensores pequeñitos de pulseras baratas (xiaomi, etc) y
empeora muchísimo cuando comienzas a sudar.
5.  La cantidad de sensores, pero sólo si estos son lo suficientemente grandes.



<amp-img alt="Sensor de pulso cardíaco de un Apple Watch I." 
    width="700" height="525" layout="responsive"
    src="/assets/images/2019/05/apple-watch-1-sensor-de-ritmo-cardiaco.webp">
    <amp-img fallback alt="Sensor de pulso cardíaco de un Apple Watch I." 
        width="700" height="525" layout="responsive"
        src="/assets/images/2019/05/apple-watch-1-sensor-de-ritmo-cardiaco.jpg">
    </amp-img>
</amp-img>
