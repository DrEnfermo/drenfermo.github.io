---
title: De fracasos y de éxitos (III)...
author: R. Trigo aka. Dr. Enfermo
date: 2023-09-09 08:21:36 -00Z
categories: [Blogging]
tags: [blog, knowledge, certificaciones, OSCP, superación, aprendizaje, fallos, éxitos, fracaso, badge, Spanish]
---

## El último OSCP. Al fin. A la tercera fue la vencida (como en mi carnet de conducir).

<p><img src="https://drenfermo.github.io/assets/img/75a558b8-a7f5-4d4b-80d5-728620e54063.png" style="display: block; margin-left: 25%;width: 20%;" alt="OSCP badge RTD"/>
</p>

Para los que habéis leído mis anteriores posts, y os puse en antecedentes de mis pequeños y grandes "fracasos", llegamos aquí a la chicha del examen que (esta vez) sí aprobé.

Comencé el examen a las 9h del 27/07/2021.  No voy a entrar en temas de por qué. Cada uno tiene sus gustos y preferencias. Yo prefiero empezar por la mañana, recién descansado, con un buen cafe, y todo el día por delante.

<p><img src="https://media.giphy.com/media/UFGj6EYw5JhMQ/giphy.gif" style="display: block; margin-left: 3%;width: 70%;" alt="Gif monstruo de la tecla from media.giphy.com"/>
</p>


Desde el principio, seguí el camino que debía seguir para sacar el Directorio Activo. Era necesario "clavarlo" cuanto antes porque os recuerdo que esta vez los 10 puntos de  BoF se habían esfumado. Con el segundo cambio de examen ya no contaba con esta técnica, así que no sabía lo que me iba a encontrar en las otras 3 máquinas. Pero estaba tranquilo. Tiré de **[Autorecon](https://github.com/Tib3rius/AutoRecon)** para las máquinas independientes y me dediqué mientras de lleno al set de **Directorio Activo**. El problema llegó cuando, una vez vulnerada la máquina inicial, a la hora o así,  descubrí que:
1. **Impacket** y **Crackmapexec** son mis tools de referencia para probar infinidad de cosas con Directorio Activo. Desde compartir ficheros, ataques de tickets, Pass The Hash, OverPass The Hash, password spraying, shares, etc. Y no funcionaban como de costumbre. Errores por todos lados.
2. **Chisel**, para pivotar, tampoco funcionaba fino, incluso con una versión nueva. Pequeño consejo: Jamás hagáis eso el día antes de un examen. Es Ley de Murphy. Si puede pasar algo malo con eso, pasará. La máquina debe estar fina desde una semana antes, por lo menos. Y testeada.
3. Así que acabé, después de un rato de desesperación y tras hablarlo con el Proctored team, tirando de una snapshot anterior, tras asegurarme de que había copiado toda mi carpeta de evidencias encontradas a otro sitio, y de ahí después a la snapshot limpia. Otro pequeño consejo: Si instaláis algo que os pueda joder algo, siempre cread una snapshot antes: os puede venir muy bien ahorraros un tiempo precioso.

Finalmente, con contratiempos varios y un descanso forzado para calmarme y reorganizar estrategias (y también con un poco de nerviosismo, para qué negarlo), con la snapshot ya limpia, clavé el Active Directory. Habían pasado casi 11 horas. Se me había ido un poco, sí. ¿Y qué?

Después me fui a por la primera máquina independiente. Y en menos de una hora ya la tenía hecha (usuario y root). La verdad es que lo ví rápido, en la ventana de resultados del autorecon. Y fui a por ello de cabeza. Ahí  me crecí. 60 puntos y me encontraba fresco todavía. Así que no quise descansar, porque el subidón de adrenalina era grande, y sentía que podía aprovecharlo. Además, conociéndome, no hubiera podido dormir. 

Así que me fui a por la siguiente y tras algo menos de 4 horas, me la saqué. Aquí la toma inicial (los 70 puntos del aprobado, si hacía bien el informe) me costó algo más porque no estaba tan a la vista. O sí que lo estaba, como vi después (ya sabéis, la "historia que te cuenta la máquina"), pero yo ya lo había descubierto desde otro enfoque, no el más evidente. Ya tenía 80 puntos, pero era de madrugada. Serían como las 4 de la mañana o así.  Ahí decidí meterme una de estas bebidas energéticas con taurina, azucar por un tubo cafeína y vitaminas (craso error) y continué, porque quería llegar a los 100 puntos y sentía que podía darme otro empujón.

Pero la última máquina se resistía, decidí volver mis pasos sobre todo lo que tenía para asegurarme que no me faltaba nada para luego hacer el informe, y volví de nuevo. Nuevo error. Esta era de las que tenía "mucha mierda que tratar".  Me iba a llevar tiempo, desgranar el heno de la paja. 

Digo que fue un error, porque aquí tenía que haber parado, dejar el brebaje ese edulcorado que no le hacía ningún bien a mi organismo y tumbarme 2 horas. Y  estoy convencido de que lo hubiera conseguido, ya que llegué a encontrar un más que probable punto de entrada. Eso sí, yo ya estaba roto, eran las 8h ya y tenía que hacer un poco de research porque era una técnica que no conocía (aunque estoy convencido de que iban por ahí los tiros). Así que decidí parar. No tenía sentido. En los últimos 20 minutos, antes de finalizar, decidí repasar todas mis adquisiciones, puertos, pantallazos  y demás, una vez más. No quería fastidiarla ahora.

Cuando finalizó mi examen me fui a dormir y estuve durmiendo hasta las 16h o así, que comí tranquilamente, y me puse con el informe. Lo del informe también fue algo de locos porque quería hacerlo tan bien y sin posibles fallos que me tiré hasta casi la hora de entregarlo. Tampoco es que esté muy orgulloso del producto final, y me hubiese gustado hacerlo de otra forma, pero era bastante decente.  De hecho creo que entre mis comprobaciones, cagadas en la exportación al pdf que tuve que corregir, comprobación del has del fichero 7z en el que entregas el informe, el sueño que me hacía ya cometer tonterías,  y demás, lo entregué como 10 minutos antes de la hora. Sufriendo hasta el final. 


El deseado correo comunicándome que había pasado llegó el 1 de agosto, 4 días después de haber entregado el informe. Ni tan mal, tratándose del verano.

<p><img src="https://media.giphy.com/media/3o6UB3VhArvomJHtdK/giphy.gif" style="display: block; margin-left: 3%;;width: 70%;" alt="Gif Jimmy Fallon-Yes!from media.giphy.com"/>
</p>



## Mis éxitos -relativos-. La vida es una caja de bombones. (¿Lo he dicho ya?)

Como he mencionado en las miserias de mi anterior post, antes de mis fracasos, también había obtenido varias certificaciones a la primera. Sin problemas. Eso me hizo confiarme con el OSCP. ¡Qué mala es la soberbia, amiguit@a! 


<p><img src="https://media.giphy.com/media/G3fPad8N68GfS/giphy.gif" style="display: block; margin-left: 3%;width: 70%;" alt="Gif Morgan Freeman- I am God from media.giphy.com"/>
</p>


Ese halo de: "porque yo lo valgo", "porque lo merezco", "porque he hecho muchas máquinas", "porque lo deseo con todo mi corazón".  "Todo el mundo dice que no es para tanto"... 

>¿Cómo? Un momento, ¿Quién dice que no es para tanto? Porque yo solo conozco unas pocas personas a las que les consiento decirme eso a la cara. Y eso porque sé que realmente son unos monstruos, y para ellos no supuso ningún esfuerzo. Porque cuando lo sacaron tenían una experiencia determinada. Pero también muchísima más gente, incluso pentesters y profesionales del sector que se dedican a esto tooodo el santo día, y profesionales del sector que o no se lo han sacado, o lo han suspendido. No es una certificación para entrar en esto. Exige ciertas cosas. Tampoco es la vida real ni te convierte en un "experto". No digo eso. Pero no te la regalan en una tómbola. Comparado con otras del sector, a lo mejor lo sea. Pero si lo crees así, preséntate tú y me lo cuentas...  Es más, aun después de haberla hecho, puedes pensar (como a mí también me ha pasado, dese esa posición de "comodidad"), que no era para tanto. No, claro. Porque ahora ya has aprendido "el camino". Pero mira hacia atrás, mira el viaje que te has pegado hasta llegar a pensar eso. Y luego vuélveme a decir que es fácil, mirándome a los ojos.  Respect! Porque si has llegado hasta ahí, nadie te ha regalado nada. A menos que hayas "hecho trampas". Y entonces eres imbécil.

<p><img src="https://media.giphy.com/media/FbUk0qvOSEWkVYgeyW/giphy.gif" style="display: block; margin-left: 3%; width: 70%;" alt="Gif What an asshole! from media.giphy.com"/>
</p>


Dejando de lado el "calentón", diré que mi primera gran derrota  puso en entre dicho mis propias facultades, y me hizo esmerarme más. Trabajar más. Hacer todavía más máquinas. Cuando me presenté al tercer exámen, había resuelto más de 250 retos en diferentes plataformas (**HTB, THM, overthewire, Proving Grounds, Pentester Labs, vulnhub,...**). Casi toda la famosa **lista de TJNull**, sobre todo en Proving Grounds, porque son máquinas más parecidas a las del examen, que contiene incluso máquinas retiradas de éxamenes. Pero no solo se trata de haber resuelto máquinas. Se trata de entenderlas. De entender "de qué va esto". De ver lo que la máquina te quiere contar. Cada máquina tiene su propia historia (si no es una máquina, chapucera, claro, que también las hay).  Al final incluso repasé la famosa lista de preparación del OSCP en 90 días con las máquinas propuestas por el propio Offensive Security. Y aquí voy a hacer otro inciso:





> Muy mal Offensive Security por recomendar en vuestros propios laboratorios máquinas que serían imposibles de resolver en el exámen, en tiempo y forma, y mucho menos, cuando vosotros mismos publicáis su resolucion usando sqlmap (totalmente prohibido en el exámen) o metasploit (restringido a una sola máquina en el exámen).  Me había encontrado algunas de estas en la lista de TJNull, pero que las sugieran para resolver en el propio estudio para el examen (en la susodicha lista de preparación) me parece un poco demencial. Al menos sugiere en la resolución cómo acometerla sin herramientas de explotación automatizadas. Si tienes h....s, porque la verdad es que la de SQLi a la que me refiero era un Blind SQL basado en tiempo, que tenías que montarte un script de locos para atacarlo, sin utilizar sqlmap ni otras automatizaciones. 

<p><img src="https://media.giphy.com/media/oEOxJXQUq1d2cELqv8/giphy.gif" style="display: block; margin-left: 3%; width: 70%;" alt="Gif Constructive criticism from media.giphy.com"/>
</p>

Así que lo bueno del "fracaso" es que al final, te enseña también a relativizar el éxito en su justa medida. Por ejemplo, nos hace plantearnos las siguientes preguntas:

- ¿Acaso es mejor aquel que llega, ve y vence, o el que a base de sucesivos tropiezos, se labra un camino hasta lograr sus objetivos? Cuantas más veces probemos y tropecemos, más veces nos acostumbraremos a que a veces el éxito solo alimenta nuestro ego, pero no necesariamente nuestro conocimiento, mientras que a cada tropiezo aprendemos algo nuevo, algo que nos hace un poco más "invulnerables" para la siguiente vez. ¡Nos da poderes, amig@s! Nos otorga las armas que necesitaremos para reaccionar más rápido y ser más certeros. Sin embargo la persona que siempre tiene éxito, se estancará en aquello que no le saque de su zona de confort, que no le rete, porque siempre tendrá el miedo a fracasar, y de tropezar, porque la sensación de "pérdida" será aún mayor que para aquel que esté acostumbrado a ello.
- Como consecuencia, relativizaremos los éxitos casi tanto como los fracasos. Otro tropiezo más no es la muerte, ni un éxito nos convierte en dioses. Todo forma parte del camino.

Esto aplicado al OSCP nos haría relativizar varias cosas:

- No. Tener el OSCP no me hace ser un "hacker", como no me convirtió en "hacker" el CompTIA Security +, ni el CEH, ni ninguna certificación hasta la fecha. Ahí fuera hay gente sin ninguna certificación que son auténticos profesionales en el área ofensiva, como hay titulados en FP o gente con apenas el graduado escolar que daría 100.000 vueltas a un Ingeniero. Los títulos son solo eso. Luego hay que arremangarse y trabajar, y demostrarlo cada día. Si no, solo será un papel que diga algo que incluso pueda volverse en nuestra contra con el tiempo. Y eso te lo enseña la vida, no el título. La curiosidad, el esfuerzo y el deseo de mejora continua han de ser lo primero.

- Sí. Por supuesto que estoy orgulloso de haberlo conseguido. Porque no es que me "certifique como hacker". Eso es pura propaganda. Lo que certifica en realidad para mí es:

	- Que me enfrenté a mis miedos y los superé. Y toda superación te hace crecer como individuo.
	- Que supe canalizar lo miedos y las frustraciones pasadas y transformarlos en algo positivo: "¿Qué nuevo reto me voy a encontrar que ponga a prueba lo aprendido? ¡Vamos allá!" 
	- Que puse a prueba mi conocimiento y superé la prueba. 
	- Que supe gestionar mi tiempo lo suficientemente bien para que, antes de que me alcanzase el sueño y el cansancio, lograse mis objetivos.  	
	- Y, sobre todo, que depuré mi metodología hasta el extremo de hacerla lo suficientemente eficiente para aprobar, de tener unas notas claras para acudir allá donde mi memoria no llegaba (sobre todo cuando  empezó a hacer mella el cansancio).  Por poner un solo ejemplo: En mi caso, que siempre había sido de enumerar manualmente, por aquello de saber cómo funcionaban las cosas, comencé a usar autorecon y a usarlo eficientemente, tirando de nmap donde me surgían dudas con máquinas en concreto. Así, me dejaba un escritorio de mi Kali, solo con el navegador web abierto contra la carpeta de resultados del autorecon, y poder echar un vistazo rápido de la enumeración que había ido haciendo la herramienta mientras atacaba el Directorio Activo en la url que tiraba contra los resultados. Si tenía dudas, como ya sabía cómo funcionaban por debajo sus diferentes herramientas, porque las había estudiado independientemente, ahora ya podía "acotar", enumerando potenciales "entry points" de manera concreta o aplicando otros  filtros, como en el caso del fuzzer web, o enumerando, "ya en fino", con nmap. Pero para tener una idea inicial y comenzar a atacar rápidamene a un puerto concreto, o identificar "low hunging fruits" y vadear posibles "rabbit holes", me vino genial. De un plumazo me permitía conocer lo que una máquina tenía expuesto, via web. Me ahorró un montón de tiempo. 

Y Aquí haré un nuevo inciso (el último ya por hoy, lo juro): 

>Al margen del *"Pay Harder"* del que se hace gala Offensive Security, he de reconocer que cuando se habla de la metodología "Try Harder", creo que realmente se refiere a este punto en concreto. Debes encontrar tu propio camino. Tu forma de optimizar tu set de herramientas y tus procesos será vital. Tu forma de "atacar tus propios puntos débiles", de reconocer tus carencias y cubrirlas será vital. Tu forma de gestionar tu tiempo, de regular tus descansos y de saber cuándo tienes que decir: "Hasta aquí he llegado, voy a procurar dormir (o por lo menos descansar) dos horitas, y luego ya veremos", y vencer tus miedos, puede suponer que apruebes, o no. De hecho, en mi caso, estoy convencido de que me habría ayudado a sacar la última máquina, que se me resistió. De haber descansado, estoy convencido de que la habría logrado (de hecho creo que llegué a ver el posible punto de entrada, pero ya estaba demasiado cansado). Saber parar a veces es fundamental. Como en la vida. Siempre prioriza tu estado mental, antes de que lo aprendas de mala manera...


<p><img src="https://media.giphy.com/media/26tncpmgYJm5gp3CE/giphy.gif" style="display: block; margin-left: 3%; width: 70%;" alt="Gif Think! from media.giphy.com"/>
</p>

Y para finalizar... unos consejos. Pero eso ya, en el **[siguiente post](https://drenfermo.github.io/posts/consejos_para_el_OSCP_y_mas_alla/)**