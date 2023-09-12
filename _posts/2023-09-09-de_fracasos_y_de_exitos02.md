---
title: De fracasos y de éxitos (II)...
author: R. Trigo aka. Dr. Enfermo
date: 2023-09-08 08:00:19 -00Z
categories: [Blogging]
tags: [blog, knowledge, certificaciones, OSCP, superación, aprendizaje, fallos, éxitos, fracaso, Spanish]
---

##  De fracasos y de éxitos (II). Mis pequeños fracasos o, como yo prefiero llamarlos, tropiezos. La vida es una caja de bombones.


<p><img src="https://media.giphy.com/media/gig4qXlZDkAuY/giphy.gif" style="display: block; margin-left: 3%; width: 70%;" alt="Gif Forrest Gump from media.giphy.com"/>
</p>


Los que habéis leído mi **[post anterior](https://drenfermo.github.io/posts/de_fracasos_y_de_exitos01/)**, conocéis ya, a grandes rasgos, mi *background* o experiencia pasada. *Mis circunstancias y yo*. Vosotros tendréis las vuestras. Os emplazo a que reflexiones sobre lo bueno y lo malo que os haya hecho aprender. En mi caso, ahora empezaremos con lo que nadie quiere oír: Las ***hostias*** (perdón, pero no se me ocurría otra forma más "gráfica" de representarlo)

El *Alzheimer* es una enfermedad infame.  En general toda enfermedad limitante o incapacitante es mala. Había sufrido indirectamente los dos cánceres de mi padre (el último de ellos lo mató) y me había dejado una marca indeleble en el alma. Esas cosas siempre lo hacen. Pero cicatrizó. Realmente pienso que los que descubran cómo "hackear" a esas enfermedades algún día, ese maldito día, ellos sí que serán unos auténticos héroes, y yo podré morirme tranquilo. El caso es que ahora mi madre (que es la que había estado al lado de mi padre todo el tiempo, dicho sea de paso), junto con mi mujer y mi hija, eran mis prioridades en lo personal: Mi fortaleza inexpugnable.

Pero esa parte de la fortaleza se fue al carajo cuando descubrí que mi madre empezaba a tener problemas (serios) con la memoria a corto plazo. Ella siempre había dicho que no le tenía miedo a la muerte,  pero sí que no quería perder la memoria como su madre, mi abuela. 

**¿No querías té? Pues toma dos tazas.**

Ya no podía (ni quería) seguir dando el doscientos por cien en un trabajo que de por sí ya no me acababa de llenar del todo, aunque había pagado mis facturas y me había hecho seguir formándome, de lo que siempre estaré agradecido, como del resto de mis ocupaciones anteriores, por supuesto.

Además, el hecho de verme forzado a abandonar el teletrabajo para volver a la oficina, sin haber acabado de solucionar el tema de mi madre (de aquella no podía dejarla sola), y además con mi propia familia viviendo en un sitio y yo con mi madre en otro, con un máster que había empezado 3 o 4 meses antes y ya no podía seguir como yo quería, me llevó a la determinación de "eliminar incógnitas" de la ecuación, por el bien de los que me rodeaban y el mío propio, ya que mi estabilidad mental y emocional se estaba también empezando a resquebrajar. Así que hablé con mis jefes y renuncié. Dejé mi trabajo. La sensación de vértigo era evidente, pero me permitió avanzar.

Así, todavía algo tocado, me levanté de nuevo. Soy un tipo bastante racional que había hecho algo "un poco" irracional (sobre todo en este país, donde la política es: "a mí, que me echen", todo hay que decirlo también). Pero lo hecho me permitió solucionar temas de papeles, médicos y demás. Además, continué mis estudios "robando muchas horas al sueño", y a partir de Julio del 2021, que mi madre ya empezó a ir a un Centro de Dia hasta por la tarde-noche, aunque seguía estando ahí, ya no era a tiempo total, me pude poner a tope con ello y, finalizar el máster.

Con el máster venía sólo un mes de laboratorios de la plataforma de Offensive Security para la obtención del OSCP, y yo veía que necesitaba mucha más práctica. Había hecho máquinas de vulnhub y HTB, sin mucho éxito sobre todo en las de HTB, practicado con los labs del máster, y me había sacado una certificación a base de mucha teoría y algo de práctica de Cybrary, basada en Pentesting así como la propia de eLearning Junior Penetration Tester (eJPT) que había empezado a estudiar con eLearning Security y acabó siendo después INE (esta sí que la recuerdo como eminentemente práctica y muy recomendable para empezar, muy asequible).  

Tuve que rascarme el bolsillo, una vez más, y pagar un mes adicional, si quería seguir practicando con el material de Offsec. No importa. Me quedaba colchón (¿He dicho antes que, salvo en formación, gasto poco?)

Había también empezado a estudiar en paralelo haciendo cositas de Pentesterlabs, TryHackme, y visionar vídeos de resoluciones de máquinas de S4vitar, IPPSec, etc.  Pero durante esos dos meses de laboratorio me centré en leerme y comprender el temario de OSCP, así como resolver los labs, y pegarme con las máquinas que no podía resolver en los crípticos foros del OSCP. No recuerdo haber dormido tan poco ni cuando nació mi peque.

Finalmente, tuve que renunciar a mis 10 puntos extras del OSCP, que de aquella se tenían que conseguir haciendo un informe anexo con la resolución de al menos 10 máquinas, así como los más de 100 ejercicios que había que mandar resueltos, del temario.  Quise priorizar la práctica sobre la teoría y me dediqué en cuerpo y alma a los labs hasta que transcurrieron los 2 meses. Resultado: 60 de las 75 máquinas de las 3 redes a atacar, conseguidas. 

¿Parecía un buen ratio, para aprobar, no? Pues no, amig@s mí@s.

Además, he de decir que tuve que afrontar un "pequeño cambio de última hora", a laboratorio cerrado (y dinero pagado) para examinarme: En 7 años no habían hecho ninguna modificación al OSCP. Pues desde ese momento cambiaba la dinámica del examen. Hasta ahora no había entrado Diectorio Activo. Pues ahora iban a meter un set de 3 máquinas en Directorio Activo (con o sin pivoting) y 3 máquinas stand alone, es decir, una máquina adicional, más Directorio Activo y pivoting.... ¡Ah! Y hasta ahora, el Buffer Overflow (BoF) no iba a contar 20 puntos si lo conseguías (acceso directo con perfil de administración a la máquina tras su explotación). Si no que, una vez explotado, tendrías que escalar privilegios. 

**Genial.**

Aquí hago un inciso ("Ya está el charlas este otra vez"):

>"Bravo, Offensive Security por querer avanzar en estos años, y seguir estando a la vanguardia del negocio donde una vez estuvisteis. Bravo por querer mejorar vuestros laboratorios y plataformas, y dotarles de mayor estabilidad. Y bravo por cambiar el sistema para conseguir esos 10 puntos, porque era infumable, para los que tenían que corregir, y sobre todo para los estudiantes. Bravo también por ese "Sueño de unos meses de verano", que creásteis al abrir una formación gratuita y en abierto en Twitch con tips de preparación para el OSCP (oro puro, sobre todo la parte de Directorio Activo), aunque se acabó pronto y volvísteis a vuestra política del "Pay Harder". Eso sí, podríais haberos estirado un poco más con los nuevos cambiosy haber extendido esa oportunidad para los estudiantes que teníamos el sistema antiguo y estábamos preparándonos el examen, pero que ya no tuvimos acceso al nuevo temario ni a los nuevos laboratorios. Gracias. "


He de decir que hasta ese momento (creo que eso lo han mejorado bastante después), los dos sets que había visto en los labs de Directorio Activo, así como el de ejemplo, eran de risa. Casi no explotabas realmente Directorio Activo. Eran una suerte de máquinas conectadas donde si acaso, pivotabas y explotabas vulnerabilidades de una a otra, o robabas hashes con mimikatz y los empleabas en la siguiente. Poco más. 

Nuevamente adaptarse o morir. Me esmeré en estudiar y hacerme sets de máquinas de Directorio Activo para estar a la altura en el examen. Y lo conseguí. O al menos eso creía yo. Pero no.

### Primer batacazo: 50 puntos.

El día del (primer) examen, estaba hiper-motivado. Preparado, no. Lo siguiente: Me iba a comer el OSCP con patatas. 


<p><img src="https://media.giphy.com/media/efn8Gilna2C7bzi0Tl/giphy.gif" style="display: block; ; margin-left: 3%; width: 70%;" alt="Gif Rambo from media.giphy.com"/>
</p>


De hecho, logré ventilarme el set de Directorio Activo, aunque me costó más de lo que me hubiese gustado (12 horas por pensar más de la cuenta, cuando todo era bien fácil, la verdad). Ya tenía 40 puntos. 


No quise descansar porque había perdido demasiado tiempo en AD: había tenido que descargarme además y compilar una versión de chisel porque no me funcionaba bien la que tenía, así como algún que otro tropiezo más y, como ya he dicho, mucho "overthinking". 

Luego me puse con la máquina de Buffer Overflow. Eso es pura metodología y si has hecho unos cuantos, los del OSCP están tirados. De hecho son 10 puntos asegurados. Creedme (o lo eran, hasta que dejaron de pedirlo en los exámenes de la certificación, que fue el siguiente cambio en la certificación que llegué a comer con patatas, comprensible por otra parte). Así llegué a los 50 puntos,

<p><img src="https://media.giphy.com/media/IsmtGDdJfpWwg/giphy.gif" style="display: block; ; margin-left: 3%;  auto;width: 70%;" alt="Gif Commando from media.giphy.com"/>
</p>


**Y adiós, muy buenas**. No pude escalar privilegios en la máquina del BoF y tuve igual suerte con las otras dos máquinas "stand-alone". Además no descansé en 24 horas salvo para ir al servicio y poco más. ¡Hasta comía en le sitio!. Mal. Muy mal.

<p><img src="https://media.giphy.com/media/10fxZavhBFXsUE/giphy.gif" style="display: block; ; margin-left: 3%; width: 70%;" alt="Gif Tired from media.giphy.com"/>
</p>

Creo que pasé por todas las "etapas del duelo", con el puñetero examen: Negación ("No, si estoy bien", Ira ("Es que los de Offsec,... las máquinas... Los reset.... No es justo", Negociación ("Si es que tenía que haber hecho esto o aquello...", Depresión ("Soy un mierda. No valgo para esto", y finalmente, aceptación. Lo malo es que hice el examen siguiente estando todavía en plena fase de Depresión y yo sin saberlo. No esperé  lo suficiente. No aprendí lo suficiente. Me surgieron más dudas y perdí la confianza en mí mismo. A ello se unieron otros factores externos, con guerra de Ucrania de por medio e incertidumbre de si nos iba a caer un pepinaco por tener bases de la OTAN en España, la subida de precios de todo, mis ahorros ya empezaban a escasear, el hecho de mirar a vece a mi madre y contemplar a una extraña, etc. 

No estoy justificándome en absoluto. Cada uno somos nosotros y nuestras circunstancias. Eso me ha hecho ser mejor persona, y no juzgar a los demás sin intentar ponerme antes en sus zapatos. Solo quiero aseverar que quizás no era el mejor momento para presentarme. NO se trata de cuando tú quieres, sino cuando puedes. De cuándo ha llegado tu momento, y eso debes aprender a verlo. Y yo NO estaba centrado, solo quería quitarme el mundo de encima. 

Así que esta vez el batacazo fue monumental. Solo saqué los 10 puntos del Buffer Overflow. Todavía me da vergüenza reconocerlo, pero sí. Así fue. Ni siquiera saqué el Directorio Activo, donde las 3 máquinas estaban, para más INRI en la misma red. Empecé el examen ya derrotado. Y eso que había estudiado más, había practicado más, había mejorado mi sistema de notas. Pero no me veía capaz. La sombra negra de la duda se había cernido sobre mí. ¿Y si no valgo para esto? 


<p><img src="https://media.giphy.com/media/xT9DPlQl5wKmvtcuek/giphy.gif" style="display: block; ; margin-left: 3%; width: 70%;" alt="Gif Good Bye Dreams! from media.giphy.com"/>
</p>


Soy un tío muy exigente conmigo mismo, y si hay algo con lo que he aprendido a convivir es con la duda permanente. Me gustaría decir que es "El Síndrome del Impostor", pero es que a veces me siento que soy un verdadero impostor. Es lo que tiene ser un eterno aprendiz de todo y maestro de nada. Si ves mi currículum, pensarás que soy un crack. Y no miento en absoluto (de hecho he quitado cosas). He tocado todos esos palos, pero no me considero un auténtico profesional en casi ninguno de ellos. Por eso quería especializarme en algo que me apasiona por encima de todo lo demás, y que me permite tirar de ese perfil tecnológico. Afortunadamente tengo a mi alrededor gente que tiene mejor concepto de mí que yo mismo, y su apoyo me sirve de acicate para ser mejor cada día, porque si no...

Realmente aquí si que estuve a punto de tirar la toalla. Incluso lo hable con mi mujer seriamente. Me animó a seguir. Eso y mi pasión por esto. Si es que a mí esto en realidad me gusta, joder. Y mucho. Eso me hizo levantarme de nuevo.: "No sé si valgo para esto, pero si no lo hago de nuevo y me quito la espina de esta decepción, jamás lo sabré", me dije.

Y seguí adelante. Me saqué el AWS Cloud Pentester Professional de Pentester Academy con exámen y certificación incluídos. Entre medias estudié un muy buen curso de DevSeOps, y el bootcamp de Certified Red Team Professional, que me dió aún más tablas para Directorio Activo.... Pero suspendí el examen. Y eso en las certis de Pentester Academy es raro, porque si estudias el temario y realmente te aplicas, el examen es un trámite.¿No? Pues no. Eso es lo que yo creía. Pero no. Otras 24 horas de examen (de verdad que ese modelo de exámen me mata: "Señores eso es reventar a la gente porque sí, que yo en mi trabajo paro y me voy a dormir, aunque sean 3 horas!"). Así me quedé atascado en una máquina por no hacer una cosa sencilla en la 3a máquina, creo recordar. Y me entró el pánico. Y  cuando, después del examen descubrí lo que había sido , me tiraba de los pelos. 

<p><img src="https://media.giphy.com/media/5AVgmIw7iAzdK/giphy.gif" style="display: block; margin-left: 3%; auto;width: 70%;" alt="Gif MJFox Back2TheFuture from media.giphy.com"/>
</p>


Este otro tropiezo me hizo darme cuenta de otra cosa crucial, a la hora de obtener certificaciones:
- El error que cometí en esta me serviría después para sacarme el set de Directorio Activo del OSCP. Así de claro. Me enfrenté a un dilema muy similar y supe lo que tenía que hacer, porque ya había fallado antes en algo parecido. La práctica hace al maestro, que dicen. Cuando más practiques, cuanto más falles y aprendas de tus errores, mejor te saldrá la próxima vez.
- Siempre aprendes algo nuevo, algo diferente que creías que sabías, hasta que te enfrentas a ello y descubres que a lo mejor, no lo tenías tan asimilado. Te hace trabajar más, estar más alerta, más preparado para la próxima vez.
- ¿Qué es lo peor que te puede pasar? No es para tanto. Te vuelves a presentar habiendo depurado lo que crees que hiciste mal, y ya está. No estás llevando una central nuclear, donde miles de vidas dependan de ti Es solo una prueba. Y las pruebas son solo eso. A veces también prueban nuestra resistencia,, nuestra tolerancia a la frustración.

A estas alturas os creeréis que ya tenía todo dominado, ¿no?

Pues no. Ahí no acabó la cosa. Tenía previsto presentarme a finales de este año, en enero. Lo veía como mi última oportunidad, antes de empezar a trabajar, porque ya no quería demorarlo más. Ya me lo sacaría después, trabajando. Pero en diciembre, otro revés:  Una hernia ciática brutal y totalmente incapacitante. Tanto que me asustaron diciendo que "parecía un tumor", porque se había salido todo el líquido del disco y estaba oprimiendo directamente la raíz del nervio ciático. Estaba cojo, con unos dolores que me hacían llorar, literalmente. No había noche que no me quisiese arrancar la pierna de cuajo, y eso que estaba dopado hasta las cejas con 3 Enamplus (Enantium + Tramadol) diarios. Finalmente, cuando me operaron en febrero (dos clavos en la espalda de recuerdo), aprendí una lección muy dura: nunca dejes tu salud de lado. Ejercita tu espalda, tus piernas, tus músculos. Pasar demasiada hora sentado sin hacer ejercicio, solo pendiente de mi formación, me había pasado factura. Y tuve además que retrasar la fecha del examen, que es justo lo que no pretendía.


<p><img src="https://media.giphy.com/media/vtRy1NnXV3aqQ/giphy.gif" style="display: block; margin-left: 3%;  auto;width: 70%;" alt="Gif I wanna die - shot - blam! from media.giphy.com"/>
</p>


Así, finalmente, en Julio de este 2023, ya recuperado, me presenté. Pero algo había cambiado. Era como el papel de Morgan Freeman, cuando, después de haber pasado 40 años entre rejas, en "Cadena Perpetua", intentando que le concediesen la libertad, mira frente a frente a los responsables de liberarle o no, y cuando le preguntan si cree que está rehabilitado, por enésima vez, les contesta aquello de: "¿Rehabilitado? Pues déjeme pensar. Para serle sincero no tengo ni idea de lo que significa eso..." Y suelta su discurso para mí, sublime. Pues así iba: Me importa una mierda si apruebo o suspenso. Me importa una mierda si es un filtro para Recursos Humanos. Porque yo voy a acabar trabajando de eso. No sé si hoy , mañana o dentro de un mes o un año. Me da igual. Así que voy a salir ahí y voy a hacer lo que sé hacer, lo que me apasiona, como si fueran una de esas máquinas que ya he hecho, porque sé que tengo mi método, que he interiorizado mi técnica. Y si no lo sé lo buscaré. Me adaptaré. Como he hecho hasta ahora toda mi vida.  Ahí me veía yo, como Morgan Freeman diciendo ""¿Certificado? Es solo una palabra de mierda. Así que rellene sus formularios hijo, y no me haga perder más el tiempo".


Es más, me importaba una mierda meter la pata en las redes. A partir de ahora iba a procurar estar más activo y empezar a subir cosas para devolverle a la Comunidad todo lo positivo que yo había tomado de ella, para procurar enseñar mi camino y seguir aprendiendo con ello. ¿Que me equivocaba y metía la pata? Pues volvería a levantarme. No me iba a "esconder" más. Había aprendido que a veces no se puede crecer si no lo haces en compañía. Aunque eso aparentemente te pueda hacer más "visible", más "vulnerable". Pero tú decides hasta dónde quieres que te afecten los factores externos. El miedo paraliza. No más miedo.

<p><img src="https://media.giphy.com/media/fulprGaN6Tp2o/giphy.gif" style="display: block; ; margin-left: 3%; auto;width: 70%;" alt="Gif Morgan Freeman - The Shawshank's Redemption  from media.giphy.com"/>
</p>



Y esta vez aprobé. Porque realmente me importaba una mierda. Quería solo divertirme con lo que había aprendido. Era solo un reto más. 

Pero eso ya... en el **[siguiente post](https://drenfermo.github.io/posts/de_fracasos_y_de_exitos03/)**.