---
title: De fracasos y de éxitos (IV)-Consejos para el OSCP...y más allá.
author: R. Trigo aka. Dr. Enfermo
date: 2023-09-10 08:35:42 -00Z
categories: [Blogging]
tags: [blog, knowledge, certificaciones, OSCP, superación, aprendizaje, consejos, Spanish]
---

## Consejos para el OSCP... o tu carnet de conducir. Me es indiferente.

<p><img src="https://media.giphy.com/media/jzHFPlw89eTqU/giphy.gif" style="display: block; margin-left: 3%; width: 70%;" alt="Gif Samurai from media.giphy.com"/></p>


No soy muy de aconsejar. Porque básicamente odio que me aconsejen si no he pedido que lo hagan. Me parece demasiado "paternalista". Pero con mi "peque" empezó a crecer en mi ese "cansino sentido paternalista". Los que sois padres me comprendréis. En realidad intentamos evitarle al otro el que no caiga en los mismos errores en los que nosotros caímos. No es más que eso y generalmente lo comprendemos cuando llegamos ya a una edad (aunque no deje de ser cansino, lo reconozco). Así que espero que me perdonéis. Ahí van:

### <u>Consejo 1</u>: Sé fiel a tu metodología y tus herramientas. Domínalas e incorpora otras solo cuando realmente las hayas probado y te sientas cómodo con ellas.

Este ha de ser el punto de partida. Cuida tus herramientas y tu máquina. Que sean una extensión de ti mismo. Cuando incorpores otra herramienta, pruébala bien, antes  para asegurarte de que te pueda servir... Tener  un buen backup y un buen sistema de snapshots o imágenes es también crítico. ¡Ah! Y no actualices nada nuevo el día antes del examen! Recuerda que si puede fallar, fallará.

### <u>Consejo 2</u>:  Aprende a gestionar bien tu tiempo, de trabajo y de descanso (esto para todo)

El OSCP es una certificación sobre todo exigente en cuanto al tiempo (Sólo dispones de 23:45 horas para hacerte 70 puntos). Y a mi juicio, la Gestión del Tiempo es un 80% del examen.  Eso significa no solo que tienes que aprender a gestionar el tiempo de "eficiencia" en cuanto a la resolución de cada máquina, sino sobre todo, el tiempo de descanso. Porque no conozco ninguna persona que después de 12 horas seguridad, no empiece a fallar. Y eso que yo suelo concentrarme tanto, que muchas veces, si no hubiese alguien a mi lado para recordármelo, o no me lo propusiese,  ni comería. Me ha pasado.  Y es  un error de cara al examen. Así que cuida tu cuerpo y tu mente, y descansa. Date un par de horas para hacer algo. Y a no ser que estés a punto de conseguir un hito, levántate, ve al baño, a beber agua, a estirarte, a hacer algo de ejercicio. Lo que quieras. Pero oxigénate y desconecta. Aunque solo sean 10 o 20 minutos. Luego sigue. Y cuando te venza el sueño, duerme. A veces recuperas mucho mejor con 1 o 2 horas de sueño, que si empleas ese tiempo luchando contra él para seguir enumerando. La solución está ahí (a no ser que no hayas enumerado bien o la máquina tenga un fallo), pero tu cansancio te impide verla. Deciros que yo aún estoy trabajando esto así que...

### <u>Consejo 3</u>: No pienses tampoco demasiado: Keep it simple!

 No te compliques la vida. Es cierto que algunas máquinas son jodidas, pero piensa que el examen realmente está hecho para que te saques todo en un tiempo razonable. Hay gente que se lo hace en 8 o 12 horas. No te compares nunca con esa gente, pero eso te da una pista de que muchas veces perdemos el tiempo imaginándonos un escenario mucho más complicado del que realmente es. Si tienes el conocimiento mínimo verás que pensar de manera sencilla te evita un montón de quebraderos de cabeza y "rabbit holes", o pistas falsas que te lleven a callejones sin salida. 

### <u>Consejo 4</u>: Puede que las máquinas no se hayan iniciado bien.

Si has enumerado exhaustivamente, hasta la saciedad, y no ves el "punto de entrada", y tú crees que estás lo suficientemente preparado para el exámen, reinicia la máquina y vuelve a empezar la enumeración. He leído mucho sobre casos en los que un puerto (el que luego les permitía entrar en la máquina) no apareció hasta que no reiniciaron la máquina varias veces. Y yo mismo creo que tenía que haber reiniciado alguna, antes de desesperarme, en algún examen, tras revisar mis notas con posterioridad. Y lo que no sabía pero me han dicho recientemente: Puedes hablar con el "Proctored Team" para que revisen el estado de una máquina, por si está bien para avanzar en el exámen (sin darte más pistas) o necesita un reinicio, si así lo crees. Esto es muy interesante, para evitarte lidiar con el dilema de: "¿Seré yo,  o será la máquina?" Aprovechadlo.

### <u>Consejo 5</u>: Los exploits tampoco son excesivamente complejos. Pero puede que tengas que retocar alguno.

En los casos en los que realmente, hay que hacer "research", o investigar, tampoco suele ser algo excesivamente complejo. Muchas veces se trata de hacer la búsqueda con las palabras adecuadas, sin mayores complicaciones. Recuerda enumerar tecnologías empleadas, nombres de servicios, etc. que veas. Es cierto que a veces vas a encontrar varios puertos con varios servicios diferentes que pueden conducirte mediante su explotación conjunta a entrar en la máquina. Pero no va a ser tampoco un festival. No te emociones. No te limiites solo a searchsploit y exploit-db. Github tiene buenas PoCs, también.  Si estás lo suficientemente preparado, tú mismo te vas a dar cuenta. Ese es el motivo por el que en el OSCP siempre te dicen "Enumera, Enumera y Enumera... ", como parte de esa mentalidad "Try Harder". 
  
Como dije antes, al margen de la ironía y de por lo que mucha gente ataca a este slogan (y en lo que yo coincido hasta cierto punto), es porque realmente no se entiende que esa frase esconde un significado sencillo: Construye tu propio toolset en base a la metodología, comprende esa metodología y hazla tuya. Y, sobre todo enumera, porque la fase de reconocimiento, junto con la de reporting, son las fases que se suelen menospreciar o minusvalorar más en este negocio, cuando prácticamente lo son TODO...

### <u>Consejo 6</u>: Enumera bien. Y si no encuentras nada, y las máquinas están bien, vuelve a enumerar. Pule tu técnica de enumeración.

Cuando domines ya nmap manualmente, no está de más que empieces a usar otras tools de enumeración. Yo mismo fui muy reacio a usar autorecon durante un tiempo. Pero no está nada mal hacerlo cuando dominas las herramientas que esta tool usa, para ahorrarte tiempo y hacer el trabajo gordo por ti, mientras atacas otras máquinas. Luego ya, acota o filtra mejor, sobre lo que tienes, si no te da la pista para entrar a la primera. 


### <u>Consejo 7</u>: La mentalidad es importante, y la importancia de aprobar es relativa. Disfruta como si de otro reto más se tratase.

El OSCP es otro "papel" más. Hay que reconocer su importancia como la de otras certificaciones del sector, por supuesto. Pero no deja de ser  parte del proceso de aprendizaje continuo. Porque este es solo un paso más. Hay que estar siempre aprendiendo, superándose, ya sea a través del reconocimiento que aportan estas certificaciones, o de manera independiente. Estudia. Practica. Tropieza. Levántate. Perfecciona. Asimila. Y vuelta a empezar. Es un ciclo. Como en la ingeniería del software: Plan. Do. Check. Act...

### <u>Consejo 8</u>: Tener un conjunto de notas bien tomadas es fundamental. TUS propias notas.
Tan importante como ir adquiriendo tu propio "toolset" de herramientas que vayas dominando, es el hecho de tomar buenas notas. Da igual la plataforma que uses para la toma de notas, pero invierte tiempo en ella. No puedes confiar al 100% en tu cerebro. Y menos a medida que avanzan los años y vas metiendo más cosas en tu cabeza, o vas dejando de trabajar con determinadas herramientas para trabajar con otras. En este sentido, y más en Tecnología, es imperativo contar con buenas notas y pulir continuamente el proceso de mejora de esas notas para no perderte luego en ellas. La organización es vital. Y te lo dice alguien que ha sido un desastre en cuanto a organización toda su vida y  un "Diógenes digital", hasta que descubrí que en nuestro trabajo, eso es una habilidad más demandada que cualquier otra habilidad técnica que puedas tener.  Y te salvará el culo más de una vez. Luego si quieres, lo que no cubran tus notas lo puedes cubrir con otros repositorios o con el propio HackTricks. 

Recuerda además que en el examen, cuanto mejor estén tus notas (sobre todo los pantallazos y notas relativas a cómo llegaste a ese paso, y los fundamentales para aprobar que sirven coomo pruebas o evidencias de tu "foothold" inicial y tu escalada de privilegios), más fácil lo tendrás para el report o informe a entregar. ¡Y trabaja también el informe!

### <u>Consejo 9</u>: No tengas miedo al fracaso o al tropiezo nunca: abrázalo como parte del camino del aprendizaje. Aprende de tus errores para mejorar.
No tengas miedo al fracaso o el tropiezo. Piénsalo como parte del proceso de mejora continua. El miedo al fracaso lleva a la inmovilización. Y no moverse es lo peor que te puede pasar, sobre todo en el mundo cambiante que nos rodea. Como sociedad en los próximos años, y más en tecnología, vamos a tener que empezar a pensar en la idea de ser "eternos aprendices" y no "gurús permanentes". Piensa además en toda la cantidad de grandes inventos y mejoras que se hubiese dado la humanidad si se hubiese tenido miedo a dar ese primer paso. ¿Qué es lo que te puede pasar? ¿Que te caigas? Pues te levantas. Aquí, que yo sepa, el baile no se acaba hasta que no pare la música. Y ahí si que no te tendrás que preocupar por no tropezar...

### <u>Consejo 10</u>: Quiérete más.
Tropezar no es malo. Lo importante es curarse de las heridas y seguir adelante. Tu peor enemig@, tu mayor crític@ puedes ser tu mism@. 

<br />

---

En el **[siguiente y último post de esta serie](https://drenfermo.github.io/posts/Mis_recursos_para_el_OSCP_y_mas_alla/)**, intentaré daros los recursos de los que yo he aprendido, en este camino de estudio (no solo para el OSCP sino en general, válido para otras certificaciones como el PNPT, eJPT, eCCPT, eWPT, etc.). Espero que podáis sacarles provecho y os resulten interesantes. Yo todavía sigo con el proceso, así que...

