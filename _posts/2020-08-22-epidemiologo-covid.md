---
layout: post
title: La historia de un epidemiologo no convecional y emprendedor (Parte I)
date: 2020-08-31 22:00:00 +0000
author: David
keywords: covid
category: virus
image: "/uploads/the_triumph_of_death_by_pieter_bruegel_the_elder.jpg"
description: Historia sobre como ha vivido un epidemiólogo digital el confinamiento
  y publica en Nature una solución para los rebrotes del COVID-19-
comments: true

---
Te voy a contar como un **epidemiólogo computacional**, como yo, está viviendo  toda esta situación de incertidumbre, de locura colectiva y conseguido a portar mi granito de arena a una solución al problema actual de los rebrotes. Pero antes quiero darte un poco de contexto.

Soy David Martín-Corral Calvo, doctorando en computación social y epidemiológica. Entrego mi tesis en los próximos meses. Esta siendo un parto de 6 años. Y además soy emprendedor y cofundador de [Zensei, una clínica virtual respiratoria basada en datos.](https://zenseiapp.com) 

Parece que estoy de moda, pero hoy solo te voy a hablar sobre mi faceta científica. La emprendedora la dejo para otro día.

Empezamos.

En diciembre del 2019 aparece un nuevo virus, llamado [SARS-Cov-2](https://es.wikipedia.org/wiki/SARS-CoV-2), que causa problemas respiratorios, ahora conocemos la enfermedad que provoca como la COVID-19.

Desde las primeras noticias que tuve de su existencia, empecé a monitorizar diariamente los casos en China y los casos importados que iban apareciendo en otros países. Al principio, algo escéptico, no era la primera pandemia que se originaba en los últimos en Asia. Sabíamos del riesgo, pero nunca pensamos que llegaríamos a donde estamos hoy. Todo era incierto.

Me gusta expresar mi situaciones emocionales con cuadros. En ese momento, antes de que empezara toda esta locura y por motivos personales, y me sentía identificado con _Vanitas_ (1636), de [Antonio de Pereda](https://es.wikipedia.org/wiki/Antonio_de_Pereda "Antonio de Pereda"). El cuadro es una alegoría de la vanidad. Es decir, la importancia de lo material es mínima, la muerte nos alcanza a todos.

![Vanitas – HiSoUR Arte Cultura Historia](https://i2.wp.com/www.hisour.com/wp-content/uploads/2018/04/Vanitas.jpg?fit=960%2C739&ssl=1)

Este estado emocional me hacía estar preparado para lo que venía y poner foco en lo importante.

A principios de Marzo, el virus nos acechaba y el contagio comunitario estaba ya presente. Después de estudiar durante casi 6 años un doctorado en epidemiología y sociología computacional y comportamiento humano, algo sé del tema, podía aportar y tenía la responsabilidad moral de ayudar. Teníamos señales que nos confirmaban lo que podía pasar y lo que se nos venía encima.

Azul, curva oficial de la gripe para la campaña de 2019-2020, rojo, búsquedas en google sobre la gripe, podemos ver perfectamente el cambio de comportamiento, la curva debería haber seguido una dinámica parecida a la de la gripe ofocial. Amarillo, [predicción del modelo de la gripe que tenemos en Zensei. ](https://zenseiapp.com/gripe/gripe-sintomas-tratamiento-curar-evitar-epidemia-ahora/)

![](/uploads/screen-shot-2020-08-20-at-12-50-55.png)

#### **Última semana de Febrero y primera semana Marzo**

A mi madre ya la venía avisando, que a lo mejor deberían ella y mi padre empezar a pensar en mudarse conmigo a la granja familiar (Me he criado y llevaba viviendo desde Octubre después de vivir 11 años fuera de Toledo) y que hiciéramos algún tipo de compra. Yo ya tenía asumido que ibamos a estar 60 días.

De hecho un amigo, cuando paso todo, me dijo: "David, tío, ha pasado exactamente todo lo que dijiste". Claro, todas las curvas epidémicas son iguales. Y cuando hablaba por videollamadas y les comentaba a amigos todo lo que iba a pasar, les cambiaba la cara y me decían: "Callaté, no queremos saberlo". No sé. La mente humana funciona así.

#### **Semana del estado de alarma**

**9 de Marzo. Lunes.**

Hicimos simulacro de trabajo en remoto en mi empresa.

**10 de Marzo. Martes.**

Última vez que fui a Madrid, vivo en una granja en medio del campo en Toledo.

Me puse en contacto con mi director de tesis, Esteban Moro, reside en Boston, y con Manuel García-Herranz, colaborador y amigo, que reside en Nueva York, trabaja en UNICEF y es experto en pandemias. Estaba a su servicio para todo lo que necesitaran.

**11 de Marzo. Miércoles.**

Nos cierran la oficina de Google for Startups en Madrid hasta nueva orden.

**12 de Marzo. Jueves.**

Se desata la locura. Se empiezan a movilizar recursos de forma espontánea en Madrid. Pero como pollos sin cabeza, muchos egos intentando ponerse medallas.

**13 de Marzo. Viernes.**

_Medio día_

Mi nombre le llega a algún político. Consulto con mi director de tesis, [Esteban Moro](https://twitter.com/estebanmoro), que hago. Me dice: “Dediquemos nos a lo que sabemos hacer” y así hicimos.

_Media tarde_

Asaltamos a puerta fría a [Yamir Moreno](https://twitter.com/cosnet_bifi?lang=en) y [Alberto Aleta](https://twitter.com/SrAleta). Les ponemos en antecedentes. Yo venía trabajando desde Enero del 2019 en un modelo epidemiológicos multicapa con datos reales de movilidad del área metropolitana de Boston para ver diferencias de transmisión de la gripe en entre clases sociales. El modelo estaba basado en una metodología desarrollada por ellos en un artículo publicado en Diciembre del 2018. Nos pusimos a trabajar, Alberto tuneó el modelo para el COVID y empezamos a hacer simulaciones con los datos reales que estábamos utilizando de Boston.

El utilizar datos reales de movilidad de una área metropolitana como Boston de 6M de personas, eran ideales para poder inferir estrategias que puedan ser utilizadas en otras áreas metropolitanas en cualquier parte del globo.

_Nueve de la noche_

Me escribe una de las principales operadoras de telecomunicación con quien habíamos hablado hace año y medio antes. Desde mi empresa Zensei intentamos hacer una propuesta para administraciones públicas de una plataforma epidemiológica con datos de telecomunicaciones. Ahora si, un día antes del estado de alarma querían hacer una propuesta para la Comunidad de Madrid y querían que fuera como experto.

Les dije que no. Su visión era muy local, la mía era global y me había unido al grupo correcto de personas para tener un impacto a nivel mundial.

**14 de Marzo. Sábado.**

Declaración del estado de alarma

Empiezo a trabajar con Alberto, no nos conocíamos. Él en Zaragoza y yo desde Toledo. Siempre será mi compañero de trinchera de la campaña del COVID.

Empezamos a preparar el modelo, los datos y las estrategias de salida para ver cómo podemos volver a reconectar todo. Durante cuánto tiempo, qué medidas de distanciamiento social. Cuando todo estaba empezando, nosotros ya estábamos pensando a 3 o 4 meses vista.

Empiezan los días de locura trabajando, haciendo horario español y estadounidense, pocas horas de sueño.

**16 de Marzo. Lunes.**

Trabajando desde mi habitación en la granja.

![](https://lh3.googleusercontent.com/40yZbMtSrc_LaSMmNb1V9_qSS81nws2E_JrM9duBu-hEhcQI_lOduNgInrR4RPdzSEzkU02r9Qz9maZ7aiGrCMhTOkr7ON7EcRVA_QEgFPrOVQWpjSgdelmlWVO2_p-9RawpWoNTTYJ2-3BXUIxPKt_2kLnEDY_a5_MxBxh3iH1RmBEVDYNzdfrW0GTLvAUtTfLc1iwpBUA9fegc7a2vFpmgukRlabWLb7FbdezjmMVMAUrSp0SUn4ry9eU6F2bI7H5-6Zqax6E9f79mepv4ZNc0KaqDGZrYIqL_UJGnQyzdcdOfAK0lRwVQ0ddad46zdVUun0Fw5wkan_QD7YzzI01y_igDfPSe3pWEVAEknfug2z7Mxo0i_qDk6si8d4KF9NJ9qyMwBPIIDlnFXar145s-O7I9enuMFLf0ed2KpvNxkJO1rQPVOGe5kxXUc0KD7ecNq8xffV5fgpvTq2oKyhSTM0H8aIhUVnaPLWcC45mk62_hLl0vlsCDfWo5OXiyKv9M8BHH7r6jDJQNR8k4gRDmUDchWJ-Bu9qjpVWlt2JJxe9zkggzKhX0MxVli59eIogU9QSo13U92S9f0vW6nH27ETGX5vbZiGDUihwtLut8v-hFILBVCSUy1XbEIqK4oJUGU_pI7mp--YVhqcMwJ8Jz2_PqwVTA2cos2ZcUZhHo2KD3rAZoRb0OafQ5z6k=w735-h979-no?authuser=0)

Mi estado y el de otra mucha gente durante el confinamiento podía ser explicado por el cuadro titulado [condición humana](https://en.wikipedia.org/wiki/The_Human_Condition_(Magritte)) de [René Magritte](https://en.wikipedia.org/wiki/Ren%C3%A9_Magritte). Estábamos encerrados con nuestro pensamiento (cuadro) a través de una venta mirando el exterior.

![The Human Condition, 1933 by Rene Magritte](https://www.renemagritte.org/images/paintings/the-human-condition.jpg)

Y a mí que me gusta observar el comportamiento humano, podía ver que cuadro tenía todas y cada una de las personas con las que hablaba. No me cansaba de decirles que socializaran, ya fuera hablando con amigos y familiares, por teléfono, chat, videoconferencia, como fuera. Somos seres sociales y necesitamos esas interacciones para un buen estado de salud.

**22 de Marzo. Domingo.**

Empezamos a tener los primeros resultados consistentes de las simulaciones y las estrategias de distanciamiento social. Ya determinamos que la probabilidad de rebrotes y segunda ola era alta pese al confinamiento.

Publicamos este primer informe.
[https://covid-19-sds.github.io/](https://covid-19-sds.github.io/)

Se lo presentamos a quién más sabe de estas cosas. Alex Vespignani. Ve potencial, nos ponemos a trabajar para mejorar el modelo y los resultados e identificar una estrategia óptima para minimizar los rebrotes y la segunda ola de contagios, con el objetivo de no saturar el sistema hospitalario. Definimos los niveles óptimos del famoso Test, Trace and Isolate. Testear, Trazar y Aislar.

**6 de Mayo. Miércoles.**

Después de casi un mes de trabajo sin parar enviamos el manuscrito del artículo a Nature. Los revisores nos lo rechazan. Nos invitan a enviarlo Nature Human Behaviour. Una subrevista de Nature.

#### **Termina el estado de alarma.**

Salgo a desfogarme.

Tenía tantas ganas de patinar, que me vine arriba saltando bordillos, me di un trompazo monumental montando con el skate y me dejé la muñeca tocada, todavía estoy recuperándome. Menos mal que no me rompí ningún hueso. Fue una temeridad por mi parte.

**5 de Agosto. Miércoles.**

Después de muchas revisiones. El artículo es publicado en Nature Human Behaviour. Aquí puedes acceder.

[Modelling the impact of testing, contact tracing and household quarantine on second waves of COVID-19](https://www.nature.com/articles/s41562-020-0931-9.epdf?sharing_token=itW75rYaCm6fRP4rDkJov9RgN0jAjWel9jnR3ZoTv0MLrFAv4IoCVan9pnzRUjws17XD5c9eFPRjdQalW_PlN1diAsH2Stgnr-G-hwDVRa-bRNAD0DMsdBmBds_Sm2KNwy9CIWJGXpY8_q1uWy9YeJzfmvGIKOMIFgcxqIMT7Rg%3D)

Resumen los no entendidos del estudio:

* Necesitamos identificar mediante tests al menos el 50% de los casos positivos.
* Necesitamos trazar los contactos de al menos el 40% de los contactos de los casos positivos para aislarlos y cortar las cadenas de contagio.

Mi primer artículo como coautor, publicado en [Nature Human Behaviour](https://www.nature.com/nathumbehav/) y retuiteado por [Eric Topol, reputado cardiólogo y autor de Deep Medicine](https://drerictopol.com/). Muy orgulloso de mi aportación y de aprender a cómo hacer ciencia de los mejores.

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">If you <a href="https://twitter.com/hashtag/TestTraceIsolate?src=hash&ref_src=twsrc%5Etfw">#TestTraceIsolate</a> right, then reopening can be done right. New modeling report <a href="https://twitter.com/NatureHumBehav?ref_src=twsrc%5Etfw">@NatureHumBehav</a> <a href="https://t.co/8IkEODt7af">https://t.co/8IkEODt7af</a> by <a href="https://twitter.com/cosnet_bifi?ref_src=twsrc%5Etfw">@cosnet_bifi</a> and collaborators <a href="https://t.co/cyyXeMhTn2">pic.twitter.com/cyyXeMhTn2</a></p>— Eric Topol (@EricTopol) <a href="https://twitter.com/EricTopol/status/1291012030594334721?ref_src=twsrc%5Etfw">August 5, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

En contra.

Solo vi una película durante todo el confinamiento. Roma de Fellini.

Emocionalmente cuando vi este cuadro de [Marc Eemans](https://fr.wikipedia.org/wiki/Marc_Eemans) de la vanguardía belga, me encanto. Justo como me sentía, un desnudo emocional para prepararme para el futuro.

![](https://lh3.googleusercontent.com/wBw9FJPIOBTDRXCIUvpSpYLAdmdRn3ZMTVbKOzGK2prUzyjVjo2bBwTK7EhifwEF7SYp2bqbdaAqo1MoPWbhDxBw-NbRWIlq9K4eNAnFVrFBzBXL6pLWxZm0QJqFzTHSGRuQJd-1apl42AS1u7O-vDBZHdzKg_G_O2rLIyEG897WFh-JBYOsu9mfPm8WFv2G-DpIhmHRjxpKH_Cntm7y2w7XHILfCRqUYS9xWvVG8z46flM6Eghwaa3Gm1uOTZd43qfq8_UpuirOyoiIc7UHBayBRcSuwF46ufggqXfzIiJQ8t0joyNWFBf8olUPIvpaKDaruEK9bYzHdy6PMo1Imm9_QkZuQQkRm4Gc6EyMvqnk73WJ51_w-KyIfZfhJc7WQ0ziK7XCtGGdG4OyGVQ4qDZQu1DhHwE8HpojMXqLfabRzo5UiUxpfW8bZ_PzrAYlxmKIbHM4_A5I-of3mApA3rqP4L02_Dym22DEQRULwn1FVjKxMgZVWtrr5PMBoWPRze48odad9pkuJXzWrJbMREk61MJcg4km_K36-TexG7e79MMSHrDdZ7Bvx06G3MVoMhmViYrxOD6hlTPCD_tmWVwOaPRarey2nPixnhKBS4Jr4oqQkab7px20ufkHDnNT3nN_gQ_y5gyalsu3VZ4-gBTeJ15ogDA0sqBUlm8_QXXK3mt65tnfvJoHKPLZRQ4=w735-h979-no?authuser=0)

Vale.

Durante todo ese tiempo pasaron muchas más cosas, que hicieron que mis niveles de cortisoles, hormona del estrés, fueran muy altos y afectaran mucho a mi estado anímico. Como supongo también te pasó a tí durante el confinamiento.
Como ves un poco en el ojo del huracán he estado y estoy. No soy Fernando Simón, ni tengo su presión mediática, pero si una presión emocional algo parecida desde otro punto de vista. Y esto todavía no ha acabado.

Por eso ahora mismo, según te escribo, el cuadro que mejor representa mi estado emocional es el [Amanecer](https://en.wikipedia.org/wiki/Dawn_(painting)) de Odd Nerdrum. Representa un amanecer a una nueva era sin recursos y con una sociedad sin rumbo.

![](https://webartacademy.com/wp-content/uploads/2010/08/Web_Art_Academy_Dawn_-Odd_Nerdrum.jpg)

Por último, el cuadro de [Ofelía](https://en.wikipedia.org/wiki/Ophelia_(painting)) Sir [John Everett Millais](https://en.wikipedia.org/wiki/John_Everett_Millais), creo que es el sentimiento de muchos de nosotros. Y parte de la situación actual es debido a lo que representa el cuadro. La muerte de la naturaleza, Ofelia personaje de Hamlet de William Shakespeare, por la locura de su enamorado, en este caso la especia humana. En en el caso de la obra literaria es el príncipe Hamlet.

![John Everett Millais - Ophelia - Google Art Project.jpg](https://upload.wikimedia.org/wikipedia/commons/thumb/9/94/John_Everett_Millais_-_Ophelia_-_Google_Art_Project.jpg/1920px-John_Everett_Millais_-_Ophelia_-_Google_Art_Project.jpg)

Esto me lleva al tema de la disolución del ego como solución al problema actual. Pronto escribiré todo lo que estoy estudiando sobre el tema.

Bien.

Es suficiente por hoy.

En los próximos días escribiré sobre mi otra mitad, mi faceta emprendedora y cómo monté un equipo en remoto durante el confinamiento, para  lanzar la clínica virtual respiratoria basada en datos de Zensei, a la vez que por las noches trabajaba como científico.

Si montar una empresa y hacer una tesis doctoral son difíciles emocionalmente, hacerlo a la vez lo es más.

Si crees que mi historia es interesante, te agradecería que la compartieras. Necesito darme a conocer para poder lanzar con éxito [Zensei, nuestra clínica virtual respiratoria](https://zenseiapp.com) y así ayudar a millones de personas a evitar los horribles síntomas respiratorios, del covid, la gripe, el asma, la EPOC y otras muchas más enfermedades respiratorias.