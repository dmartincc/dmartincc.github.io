---
layout: landing
title:  "🙋‍♂️ Hola, soy David."
date: 2018-10-06 00:00:00 +0200
permalink: /
---

Un Don Nadie que no tiene __ni p*** idea de casi nada.__

Por eso sigo aprendiendo día a día.

Sueño desde pequeño con hacer algo que pueda ayudar a millones de personas.

No sé si podré ayudarte en algo, porque no sé de casi nada. 

Pero tengo unas ganas locas de aportar valor.

Aquí te contaré mi aprendizajes que ido teniendo a lo largo de mi vida y sobre las cosas que sé algo.

¿Aquí te dejo mi principal aprendizaje hasta ahora?

__Piensa más en los demás y menos en tí.__

Practicalo, seguro que te va mucho mejor.

## **¿Sobre qué sé algo?**

Saber, saber, lo que se dice saber, más bien poco. Pero seguro que puedo aportar algo en:

💻 [**Productividad**](/oficina). Proyectos en los que trabajo e intento ganarme la vida. Data science, startups, diseño de producto y productividad. Ganar más con menos.
<div>
{% for post in site.categories['oficina'] | limit : 1 %}
    <p>
      <b>Último artículo:</b>
      <a itemprop="url" href="{{ post.url | relative_url }}">
        {{ post.title | escape }}
      </a>
    </p>
{% endfor %}
</div>

🔬 [**Lab**](/lab). Estudio un Doctorado en Ingeniería Mátemática. Aprendo sobre datos, salud, comportamiento humano y computación social.
<div>
{% for post in site.categories['lab'] | limit : 1 %}
    <p>
      <b>Último artículo:</b>
      <a itemprop="url" href="{{ post.url | relative_url }}">
        {{ post.title | escape }}
      </a>
    </p>
{% endfor %}
</div>

📵 [**Móvil**](/móvil). El móvil es una gran herramienta, pero está diseñado para mantenernos enganchanos. Aquí te cuento como utilizar el móvil de forma saludable.
<div>
{% for post in site.categories['móvil'] | limit : 1 %}
    <p>
      <b>Último artículo:</b>
      <a itemprop="url" href="{{ post.url | relative_url }}">
        {{ post.title | escape }}
      </a>
    </p>
{% endfor %}
</div>

🧬 [**Genética**](/genética). De pequeño soñé con ser ingeniero genético. Me quedé en ingeniero.
<div>
{% for post in site.categories['genética'] | limit : 1 %}
    <p>
      <b>Último artículo:</b>
      <a itemprop="url" href="{{ post.url | relative_url }}">
        {{ post.title | escape }}
      </a>
    </p>
{% endfor %}
</div>

🏊‍♂️ **Piscina**. He nadado en 20 años más de 10.000km. Lo único que he conseguido ha sido marearme dando virajes.
<div>
{% for post in site.categories['piscina'] | limit : 1 %}
    <p>
      <b>Último artículo:</b>
      <a itemprop="url" href="{{ post.url | relative_url }}">
        {{ post.title | escape }}
      </a>
    </p>
{% endfor %}
</div>

🎸 **Local de ensayo**. Toco música lo-fi para oídos con telarañas. Un día soñé con ser una rock star y la novia que tenía lo jodió.
<div>
{% for post in site.posts | last | limit : 2 %}
	{% if post.category == 'local de ensayo' %}
    <p>
      <b>Último artículo:</b>
      <a itemprop="url" href="{{ post.url | relative_url }}">
        {{ post.title | escape }}
      </a>
    </p>
	{% endif %}
{% endfor %}
</div>

🐐 **Granja**. Me he criado en una granja con vacas, cabras, caballos, gallinas, huerto, etc. Intento aprender de mi padre por si hay un holocausto.
<div>
{% for post in site.categories['granja'] | limit : 1 %}
    <p>
      <b>Último artículo:</b>
      <a itemprop="url" href="{{ post.url | relative_url }}">
        {{ post.title | escape }}
      </a>
    </p>
{% endfor %}
</div>

💭 **Mi mundo**. Pienso luego existo, pero de forma inconexa y de esto no sé nada de nada.
<div>
{% for post in site.categories['mi mundo'] | limit : 1 %}
    <p>
      <b>Último artículo:</b>
      <a itemprop="url" href="{{ post.url | relative_url }}">
        {{ post.title | escape }}
      </a>
    </p>
{% endfor %}
</div>

## **Mis 30 segundos de gloria**

Hola, ¿qué tal? Yo una vez fuí a un campamento. Otro día hice un curso de escritura con Espido Freire y me puse a escribir.

Además de eso, soy un ingeniero granjero que estudió para llevar la empresa familiar. Pero no sé si algún día se materilizará.

Ahora me dedico a eso de los datos y productos digitales.

Soy de Toledo, España. Y no de Toledo de Ohio.

Vivo en Madrid. Antes he vivido en Ploiesti, Edimburgo, Glasgow, Barcelona y ahora sueño con vivir en la playa con mi chica.

Ah! Soy y he sido profe en varias universidad y escuelas de negocio. Enseñar, enseñar,... ayudo a descubrir el mundo. 

Cosas de la vida. Estuve el 10 de septiembre de 2011 en la terraza de una de las Twin Towers en NY.

## **Mis proyectos pasados**

Cosa que he intentado que no han funcionado o si.

❌ **ethinker**, 2014. Algo parecido a lo que están haciendo mis amigos de [Graphext](https://graphext.com/), pero mucho peor. FALLIDO.

❌ **itoutfits**, 2015. Agregador de itgirls para explotar los datos. FALLIDO.

❌ **helth.ai**, 2016. Un asistente de salud via email. FALLIDO.

✅ [**Politibot**](http://politibot.io), 2016. Ayudé a un robot a que cuente historias sobre política. FUNCIONANDO.

## **Mis proyectos en los que estoy trabajando**

¿En qué estoy trabajando ahora mismo? Espero que funcionen.

👷 [**Zensei**](https://zenseiapp.com), desde Abril del 2017. Estoy dedicando mis ahorros, energia y tiempo a ayudar millones de personas con problemas respiratorios. Deje una oferta de trabajo en NY por Zensei. WIP.

👷 [**Blog personal**](/blog), desde Septiembre del 2018. Me he propuesto escribir semanalmente sobre algo interesante en este blog y monetizarlo en el largo plazo. WIP.

👷 **Doctorado**, estudio la dinámica de las epidemias sobre redes sociales con datos y machine learning. Me gusta meter miedo con historias de epidemias.

## **Mis proyectos de futuro y sueños**

No tengo ni idea, pero me gustaría algún día:

🎓 Terminar mi doctorado y escribir un libro sobre él.

🎸 Volver a tocar la guitarra a diario y montar un nuevo grupo.

🥚 Vender un servicio de subscripción de huevos a domicilio.

🎹 Aprender a tocar el sintentizador para hacer ruido.

🏄‍♂️ Aprender a surfear y a montar el skate. 

🥗 Construir un invernadero bajo tierra.

🐬 Nadar con delfines.

🎨 Pintar y hacer escultura.





