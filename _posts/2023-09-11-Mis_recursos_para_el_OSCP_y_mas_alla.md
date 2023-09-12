---
title: De fracasos y de éxitos (V)-Mis recursos para el OSCP...y en general.
author: R. Trigo aka. Dr. Enfermo
date: 2023-09-11 08:28:21 -00Z
categories: [Blogging]
tags: [blog, knowledge, certificaciones, OSCP, superación, aprendizaje, consejos, recursos, conocimiento, Spanish]
---

## Mis recursos recomendados para preparar el **OSCP**, los que a mí me sirvieron (actualizados al 2023)

<img src="https://media.giphy.com/media/3oFyCVxsQn6RBa0r5u/giphy.gif" style="display: block; margin-left: 3%; width: 70%;" alt="Gif My Precious from media.giphy.com"/>

Tras los típicos **[Consejos sobre la certificación](https://drenfermo.github.io/posts/consejos_para_el_OSCP_y_mas_alla/)**, que valdrían para cualquier otro tipo de preparación, vayamos ahora ya a lo que busca todo el mundo: **La Guía Definitiva.** **El Santo Grial**. **La Piedra Filosofal**. Aquello que me hará "clavar" la certificación. Pues lo siento, pero esa idea no existe, amig@s. Porque el aprendizaje ha de ser flexible y continuo, y debe saber adaptarse a los cambios. Porque no hay nada más cambiante que las nuevas tecnologías y la seguridad que a ellas está ligada. Cada día surgen nuevas vulnerabilidades, y se parchean otras. Las herramientas que ayer te servían, hoy son obsoletas , detectables hasta por el Antivirus más casposo del mercado,  o ya no funcionan como deberían. Y finalmente, porque el camino es tuyo, y sólo depende de ti. Es tu proceso y sus circunstancias.

Sin embargo, en cuanto a formación, yo distinguiría, lo que considero que debemos saber de base, para dedicarnos a esto del hacking ético y el pentesting, ya sea por hobby o profesionalmente, y lo que se realmente necesitamos para el OSCP. 

Comencemos.

### Conocimientos "de base".
Entre las disciplinas que recomendaría como "Pre-requisitos",  lo primero es, empezando por las "habilidades blandas," y siguiendo por las más técnicas:

- **Muchísima tolerancia a la frustración**. No desarrollaré más esto. En realidad ya sabéis a lo que me refiero.
- **Un nivel aceptable de Inglés**. Por lo menos, lo vas a necesitar para poder ver toda la cantidad de material que hay sobre hacking y pentesting en esta lengua. Porque en España hay  muy buenos profesionales sí. Y cada vez mejor material en español. Pero ¿Por qué contentarte con el vaso medio lleno? Así que si no sabes inglés, con la cantidad de recursos que hay en Internet, ya no tienes excusa. ¡Ponte las pilas y me lo agradecerás!
- **Mucha curiosidad**. Cuestiónate todo. Comprende su forma de funcionar, para buscar la forma en la que puede fallar. Lo que descubrí cuando empecé a aprender en esto es que había pasado demasiados años configurando Sistemas, y desarrollando software. Siendo un "buen soldado". Probaba la funcionalidad que se supone que tenía que probar. Y de la forma en la que tenía que probar las cosas. Así que los fallos eran "los esperados". Se corregían y punto.  Hacía lo que se supone que tenía que hacer. Hasta que conecté con esa "curiosidad" semienterrada por años de "institucionalización" (nuevamente una referencia a la que para mí es una gran película: "Cadena Perpetua"). Había perdido esa curiosidad que me había hecho entrar en esto de la Informática, de aprender y aplicar cosas nuevas. De conectar realidades diferentes. Y empecé a tomar contacto con ese "lado". Empecé a preguntarme "¿Y si hago esto en vez de esto...?", sin miedo a provocar el fallo. De hecho, como investigador, debemos averiguar la manera de que las cosas fallan, para que otros indeseables no lo hagan y se aprovechen de esos errores. Debemos forzar la manera en la que el sistema ha sido concebido, tratando de usarlo para aquello que no ha sido pensado.  A veces incluso de las maneras más creativas posibles. Fomenta pues tu lado creativo. Esa es la mejor actitud que puedo recomendarte, en la que yo aún sigo trabajando.
- **Visión global**. La especialización es vital, si no queréis acabar fatal de la cabeza. Algún día os hablaré de las discusiones a cuatro bandas de mi "yo programador" al "yo administrador de sistemas", al "yo defensivo" y al "yo red ofensivo". A tortazo limpio... Pero creo firmemente que una visión "global o general", así, a vista de pájaro, de la Tecnología y sus avances en todos los campos, y no solo en el que nos especializamos, aunque sea sin profundizar en mucho detalle, pero como toma de contacto inicial, es también muy necesario, para no perder perspectiva. En ese sentido, además de los típicos blogs y noticias relacionadas con vulnerabilidades, ataques, parches, y demás, estaría bien seguir algunos canales técnicos (y no técnicos) de otros campos. Vivimos en un mundo interconectado y global. Y hoy más que nunca, el "Efecto Mariposa" de la "Teoría del Caos" está más vigente que nunca.
- **Humildad** para reconocer (y aprender de) los fallos, ayudar y avanzar en equipo. Y **confianza** para defender los aciertos, sin caer en la vanidad. Difícil, ¿eh?
- **Un buen sistema de toma de notas y practicar con él  desde el minuto 0**, como lo harías con el resto de cosas que aprendas. Yo recomendaría **[Obsidian](https://obsidian.md/)**, que trabaja incluso en local, con markdown y tiene una comunidad y muchos plugins interesantes detrás. O si quieres un servicio ya en la nube, **[Notion](https://notion.so)**  es muy buena opción también. Pero si eres de l@s que se apañan todavía con **[CherryTree](https://www.giuspen.net/cherrytree/)**, pues también...
- **Conocimientos básicos de Redes**. Es la base para entender el funcionamiento de puertos, protocolos y servicios. Desde el modelo OSI al TCP/IP. Al menos tener una idea básica.  He dicho básicos, no hace falta que sepas configurar un router CISCO, pero si llegas a eso, probablemente ya tengas un nivel aceptable de conocimiento. Los vídeos gratuitos de **[Professor Messer](https://www.youtube.com/playlist?list=PLG49S3nxzAnlCJiCrOYuRYb6cne864a7G)** son muy buenos. 
- **Funcionamiento básico de los Sistemas Operativos**. Al menos Windows y Linux. Comandos básicos para la configuración, Transferencia de ficheros en uno y otro sistema, manipulación del firewall en línea de comandos, manipulación del AV en línea de comandos. Bash Script básico y PowerShell básico (ahora también tienes **pwsh** en Linux y e incluso WSL (Subsistema de Windows en Linux) en Windows, así que no hay excusa). Y no me refiero a quedarte en el GUI, que también. Aprende a tirar de mucho de línea de comandos...
- **Empleo de técnicas dde Virtualización** con **[VirtualBOX](https://www.virtualbox.org/)**, **[VMWare Player](https://www.vmware.com/es/products/workstation-player.html)**,  **[VMWare Workstation Pro](https://www.vmware.com/es/products/workstation-pro.)** , el **Hyper-V** de Windows 10/11 o **[QEMU](https://www.qemu.org/)**.Lo que quieras para virtualizar entornos. Junto con el uso de contenedores, te puede ayudar a montarte rápidamente tus propios laboratorios. Sobre todo si no dispones de mucho espacio o recursos. Si luego ya dominas cloud con AWS, Azure, GC, o lo que sea, con **Terraform** o similar, ese ya será el siguiente paso para montarte unos labs en condiciones (y ahí prepárate a soltar algo de dinero). Pero con lo básico, para empezar a coste 0, tienes opciones.
- **Empleo de Contenedores**: **Docker**. Por lo mismo. Para probar PoCs, programas, tools, etc. bajándote imagénes de contenedore ya existentes, o creando las tuyas propias, iniciando instancias, probando, parando, y vuelta a empezar.
- **Empleo de Sistemas de control de versiones de código**: Git.  Luego ya, si te gusta más GitLab que GitHub, a tu criterio.
- **Empleo de IDEs para desarrollo**, editores con esteroides o como quieras llamarlos (**VSCode, Notepad++, vim, nvim, ...**)
- **Empleo de algún lenguaje de programación**, por lo menos, sencillo. No voy a entrar en una batalla sobre cual es mejor. Paso de polémicas. Si te sobra el tiempo, C (aunque da miedo), tiene una curva de aprendizaje alta, pero si dominas C (ojo, yo no lo domino ni mucho menos), cualquier lenguaje será coser y cantar. Si no, para scripting y pentesting, con Python te valdría, en un principio.  A mí personalmente también me gusta mucho C#, pero allá cada cual. Rust, Go, Ruby. Tienes para aburrir. Eso sí, si puedes, no hagas lo que yo. Cíñete a uno y apréndelo estrujándolo hasta el límite. Que tocar, he tocado algunos, pero ponme ahora mismo a programar en **C** o **Java** y ya verás qué risa floja me entra. Esto es como todo, cuanto más practiques y mejores notas tomes, y más te pegues con tus creaciones, por pequeñas que sean, mejor. Si nos vamos a lenguajes "web", serían con algo de **HTML5**, **CSS** y **JavaScript** tendrás cubierto el front-end, y con algo de **PHP** los lenguajes de back-end para el lado servidor (sin olvidar las bases de datos, claro). Aunque en el caso de **PHP**, ya tengo mis dudas, porque el abanico de posibilidades se está abriendo mucho más.  con el backend basado en **Python** (como **Laravel** o **Django**m o usando **Flask** para microservicios), **Ruby** (con su **Ruby On Rails**), o infinidad de otros que se unen a los que ya existían con  **Express.js y Node.js**. a los ahora ya clásicos **ASP .NET** (que cuando yo empecé era ASP clásico), y **PHP** o **Java**.  ¡Incluso con stack "serverless"! En definitiva, y sin andarme más por las ramas,por lo menos entender un poco qué es lo que hace un código determinado. Solo tienes que ver que ahora la complejidad de los stacks tecnológicos

### Conocimientos para el OSCP... y más allá
Para el OSCP específicamente, yo me centraría primero en:

- Practicar mucho con **[TryHackme (THM)](https://tryhackme.com/)** todo lo relativo a los temas que luego se tocarán en el **OSCP**, y en hacer máquinas para coger práctica, desde casi el principio y sin miedo. Comenzando con las "guías" de **TryHackme** en sus *"paths"** de Pentesting (**[básico](https://tryhackme.com/path/outline/jrpenetrationtester)** y **[avanzado](https://tryhackme.com/path/outline/pentesting)**) y luego apoyarnos en **[Proving Grounds][https://www.offsec.com/labs/individual]**, de los propios **Offensive Security** y **[HackTheBox](https://www.hackthebox.com/)**. Si no tienes cuenta en estas tres plataformas, corre a hacerte con una.  Y al menos en alguna de ellas, por ejemplo **THM**, yo que tú haría el esfuerzo y me pagaria la suscripción Pro, quitándomelo aunque fuese de la subscripción de *NetFlix* o las cañas del fin de semana, porque merece la pena y, total, no vas a tener tiempo para dedicárselo a estas... Bueno, al menos siempre dedica algo de tiempo para el aire libre, tu familia y cuidar tu cuerpo y tu mente con algo de "evasión". Porque lo vas a necesitar.

- También tienes otras plataformas como:

	- la clásica de **[vulnhub](https://www.vulnhub.com/)** y la más reciente **[Vulnyx](https://vulnyx.com/)**. Te bajas la máquina virtual,  la abres y "juegas". Las máquinas de estas plataformas están categorizadas por su facilidad de resolución, o incluso temática, si tienen write-up (solución publicada) o no, etc.

	- **[HackTheBox Academy](https://academy.hackthebox.com/)** con sus certificaciones de Pentesting y Bug Bounty. Se pasan de lo pedido para el OSCP pero son muy buenos recursos de aprendizaje.

	- **[PentesterLab: Learn Web Penetration Testing: The Right Way](https://www.pentesterlab.com/)**
	
	- **[OverTheWire Wargames](https://overthewire.org/wargames/)**

- En este sentido hay un recurso-guía para el OSCP, que he descubierto recientemente que  tiene muy buena pinta, con enlaces a páginas muy buenas como HackTricks, así como a las plataformas que te he comentado y otros muy interesantes para empezar a prepararte el OSCP antes de contratar el curso propio de Offensive Security:
	
	**[OSCP Trics 2023, from Rodolfo Mariano](https://github.com/rodolfomarianocy/OSCP-Tricks-2023)**


- Especialmente para el OSCP  y si solo podéis quedaros con una plataforma, yo recomendaría, una vez satisfechos los conocimientos esenciales con **TryHackme**, saltar a hacer máquinas en la propia plataforma de [Proving Grounds](https://www.offsec.com/labs/individual/) , tanto en su versión gratuita (**Play**) como en su versión de pago (**Practice**), por 19  dolares mensuales ahora mismo,  porque son máquinas en su mayoría realizadas por los de Offensive Security, os que te van a hacer el examen. Yo me he centrado en ellas, en los últimos tiempos, y me han ayudado mucho a afinar el "mindset" específico de Offensive Security, especialmente a la hora de identificar "rabbit holes". Y también aprender a ver las "conexiones". Con esto me refiero a que toda máquina tiene su historia, su "por qué", y cuando las vas haciendo te vas dando cuenta de la "intencionalidad". No digo que esto no pase en otras plataformas, pero esta es la que más se aproxima al OSCP. Empieza por las **"Easy"**, y luego termina con las **"Avanzadas"**, si tienes tiempo.  Yo si empezase de cero, me intentaría hacer todas las de la [lista de TJNull](https://docs.google.com/spreadsheets/u/0/d/1dwSMIAPIam0PuRBkCiDI88pU3yzrqqHkDtBngUHNCw8/htmlview?pli=1), aunque avanzo que  algunas no te van a caer ni de casualidad. Si te falta tiempo, empieza por eliminar las de *BoF -Buffer Overflow-* y algunas avanzadas, aunque te diría que hagas todas las que puedas. BoF no entra ya en el OSCP, pero te da una buena metodología, y empiezas a tocar algo de Inmunity Debugger y a pederle un poco miedo al ensamblador. Los mejores expertos que conozco, termiman haciendo algo de reversing. Y también para crear ciertos exploits indetectables, más tarde o más temprano, habrá que lidiar con ello. No solo para explotación de BoFs.

- En cuanto a la realización de máquinas, no te agobies, si no sacas alguna. Si te falta tiempo, escoge primero todas aquellas fáciles y medias de las listas mencionadas. Y no te sientas mal si, después de perder horas con alguna, tienes que ver su Write-Up o solucionario. Sobre todo al principio o con máquinas muy concretas. A veces es porque simplemente, te faltará el conocimiento necesario para atacar el problema. En ese caso, yo personalmente considero absurdo darse de cabezazos contra la pared. Lee la solución, asimílala bien. Toma después buenas notas sobre ellas y el nuevo conocimiento que te faltaba o la  pista que te perdiste que te hizo no acertar, y sigue con las siguientes. También dedica un rato de tu tiempo a revisitarlas y afianzar lo aprendido. Sé que muchas veces nos forzamos a seguir, sobre todo si el tiempo apremia. Pero en realidad, es mejor parar y revisar bien el concepto, que seguir y seguir. Porque en una semana, te habrás olvidado probablemente. Y ahí también juega un muy buen papel tener muy buenas notas o apuntes tomados, para poder acudir a ellas siempre (¡y un buen plan de backups para las mismas, por favor, que nos dedicamos a esto!).

- Poco a poco, te irás haciendo con una buena "toolset", con las herramientas que conozcas y aprendas a sentirte confortable con ellas, para: 
	1. Enumeración (**nmap, masscan, autorecon**, etc.), 
	2. Enumeración Y fuzzing de páginas y servicios web, APIS etc. (**dirbuster, nikto, gobuster, feroxbuster, wfuzz, ffuf**,...). Y manejo razonablemente bien de los proxies web **BurpSuite*** (con la Community Edition gratuita, vale, y además no te dejan otra en el exámen) o ZAP Proxy, que también es muy bueno.
	3. Bruteforcing/Password spraying de servicios como ftp, ssh, etc (**hydra, medusa, etc.**)
	4. Wordlists: **secLists** y los propios de la Kali. Aunque para el OSCP, con el **rockyou** para contraseñas de usuarios, y las típicas que verás por ahí de búsqueda de directorios para web (directory-list-2.3-medium.txt, directory-list-lowercase-2.3-medium.txt, big.txt, small.txt, y los típicos de dirbuster), de sobra. ¡Aunque recuerda que también tendrás en casos concretos saber crearte tus propias wordlists!
    5. Crackeo de contraseñas (**john, hashcat**). ¡Y también **frackzip** y las tools **zip2john,rar2john, etc.**!
    6. Para la fase de explotación: Uso de **searchsploit** y **exploit-db**, compilación de binarios -¡en Linux y en Windows!-, o de la web  **[💀 Sploitus - Exploit & Hacktool Search Engine](https://sploitus.com/)**,  **metasploit** (aunque en el OSCP, solo lo podrás usar en una máquina de las stand-alone, como cualquier otra herramienta de explotación automatizada), junto con la creación de reverse shells según los entornos de plataformas y el uso de **msfvenom**, para construir nuestros payloads.	
	7. Para explotación, a parte de mis notas, usaba mucho está web, que te permite configurar la reverse shell en función del lenguaje identificado en el servidor: https://www.revshells.com/
	 8. Para retos crypto, aunque Kali cuenta con varias tools, me gusta mucho [CyberChef](https://gchq.github.io/CyberChef/)
	  
		 En concreto, para descifrar hashes rápidamente en texto plano (¡de ctfs o máquinas de estas plataformas!): 
		- https://crackstation.net/
		- https://dehash.me/
		- https://hashes.com/es/decrypt/hash 

	 9. Importante también es configurarte un entorno de ataque a tu gusto, sentirte cómodo con él, ya sea usando **tmux**, o **terminator**, un terminal con esteroides, como una **kitty con PowerLevel10K y una zsh**, o bien la versión "pelada" de la Kali,  o un Parrot (¡o una Debian con las herramientas que vayas a utilizar!)pero familiarízate con ellas y siéntete bien usándolas. 

- Si volviese a empezar, yo no tendría prisa en apuntarme a la propia **[certificación de Offensive Security](https://www.offsec.com/courses/pen-200/)]** con sus labs, hasta que no entendiese la metodología, tuviese muy clara la fase de enumeración de servicios, conociendo los más importantes, hubiese hecho bastantes máquinas y tuviese ya un nivel de lo que te vas a encontrar ahí. Disfruta del camino, y si puedes hacerlo "sin darte un atracón", mucho mejor. Creo que es una certificación muy cara para tirar el dinero a lo tonto. Además, cuanto más practiques, más fácil resolverás los laboratorios de la inscripción para el examen, y podrás incluso hacerte en un mes todas o casi todas las máquinas. En este punto recomendaría que si puedes, y me has hecho caso en lo anterior, una vez inscrito en el curso, pierdas el tiempo en **ganar esos 10 puntos con las prácticas de los laboratorios y los ejercicios**. Ahora es mucho más fácil no perderlos que cuando yo lo hice, y pueden suponer la diferencia entre aprobar o suspender, además de que muchos de los ejercicios sí pueden resultarte útiles, aunque un poco rollo si has cogido toda la experiencia tal y como te indicado, pero siempre te pueden enseñar algo.

### Directorio Activo

En cuanto a "Grandes Apartados", para **Directorio Activo** recomendaría los siguientes recursos (de menos a más). Con ellos creo que  iríais sobradamente preparados y no solo para el OSCP. Creo que con los dos cuatro primeros puntos, ya cubrirías lo que te pueda caer en el OSCP, de hecho. Sobre todo, y aunque te pueda parecer una chorrada, fíjate bien qué usuarios se han conectado a esa máquina, en el pasado, porque te puede dar pistas, una vez consigas vulnerarla. ¡Por ejemplo si en esa máquina se ha conectado un Administrador del Dominio o uno que te pudiese conducir a la toma del DC!. Y entonces empieza a repetir metodología para escalada y movimiento lateral. Luego practica mucho con mimikatz.exe, para dumpear hashes de memoria, así como crackmapexec e impacket, ya en tu máquina, con conceptos como ataques de asreproast o Kerberoasting. Testea además las contraseñas obtenidas con diferentes usuarios del AD, incluso a nivel de usuario local de la máquina, en las máquinas que componen el Dominio. Si además, te sientes cómodo usando PowerShell para enumerar mejor con PowerView o con el propio Active Directory PowerShell Module, y herramientas de SysInternals como PsExec, etc., creo que esta parte la tendrás ya bajo control. En cuanto a los recursos que recomendaría (sentíos libres de completar con lo que queráis):

1. Esta serie de artículos de Tarlogic: https://www.tarlogic.com/es/blog/como-funciona-kerberos/ explican muy bien el funcionamiento de Kerberos.
2. Esta serIe de vídeos y presentaciones sobre Kerberos y movimientos laterales del gran **Daniel López Jiménez, aka attl4s**, que no tienen desperdicio: https://attl4s.github.io/
3. Esta serie de artículos del gran Daniel **Echeverri Montoya, aka Adastra** en TheHackerWay:
	https://thehackerway.com/2021/10/07/pentesting-en-active-directory-parte-1-conceptos-basicos/
	https://thehackerway.com/2022/10/05/aprende-a-enumerar-dominios-de-active-directory-con-crackmapexec/
	https://thehackerway.com/2023/01/18/10-herramientas-imprescindibles-para-pentesting-en-active-directory/
	https://thehackerway.com/2023/01/25/10-herramientas-esenciales-para-pentesting-en-active-directory-parte-2-de-2/

4.	Toda la parte de Active Directory de este curso (aunque yo me lo haría enterito):
	https://academy.tcm-sec.com/p/practical-ethical-hacking-the-complete-course

5. Este curso gratuito de Seguridad SI y *Joaquín Molina, aka "Kinomakino"* (que os proporcionará lo necesario para el uso de mimikatz en el OSCP):
	[Curso "Acceso a Contraseñas del Sistema y Mitigación mediante modelo Tiers Administrativos"](https://formacion.seguridadsi.com/courses/tiers)
		
6. **Active Directory Methodology de Hacktricks** (quizás es excesivo, pero lo que no aparezca ahí, no creo que te caiga en Active Directory del OSCP, ni de casualidad):
	https://book.hacktricks.xyz/windows-hardening/active-directory-methodology

 7. Igualmente de excesivo, pero también impagable, resulta la también famosa página de PayLoadAllTheThings y su apartado específico de Directorio Activo ([Active Directory Attacks - Payloads All The Things (swisskyrepo.github.io)](https://swisskyrepo.github.io/PayloadsAllTheThingsWeb/Methodology%20and%20Resources/Active%20Directory%20Attack/#summary)) 

 8. La preparación para el **[CRTP (Certified Read Team Professional) de Pentester Academy (ahora Altered Security)](https://www.alteredsecurity.com/post/certified-red-team-professional-crtp)**, y el manejo de PowerView y otras tools eminentemente en PowerShell se sale un poco también de lo que es el OSCP pero tiene un efoque ofensivo-defensivo que también me gusta mucho y te ayuda a entender la explotación de Directorio Activo desde la propia máquina Windows, PS-Remote Sessions, etc. No necesario, pero sí muy interesante. Eso sí, acordaos de que herramientas como PowerUp están prohibidas en el OSCP, al menos en su faceta de "explotación automatizada".
	 
 9. Para practicar, si no te montas tu propio lab de practicas con máquinas virtuales (hay miles de recursos gratis en internet donde te lo explican), tienes esta maravilla:

	https://mayfly277.github.io/posts/GOADv2/

**Orange** tiene para mi y a día de hoy, el "mindmap" más completo y actualizado para hacerte la idea de ataques a Directorio Activo. Excede con mucho, lo que te van a pedir en el OSCP, pero si lo dominas (solo profundizar en detalle sobre ello llevaría meses), no tendrás que preocuparte de nada en este apartado:

https://orange-cyberdefense.github.io/ocd-mindmaps/img/pentest_ad_dark_2023_02.svg



### Web. Enumeración. Fuzzing de directorios, parámetros, API endpoints, vulnerabilidades típicas a explotar y uso de Proxy web.

En cuanto a la parte de Pentesting Web, recomendaría esto, aunque aviso que, como con el apartado anterior, sobre todo los recursos del final,  pueden ser incluso excesivos para el OSCP:

1. [Esta serie de artículos de TheHackerWay para abrir boca](https://thehackerway.com/2022/11/30/10-herramientas-esenciales-para-pentesting-web-parte-1-de-2/)

2. El curso de [Introducción a Hacking] (https://hack4u.io/cursos/introduccion-al-hacking/) de **Marcelo Vázquez, aka S4vitar** (Sí, como lo oyes : *"El Enfant Terrible"*, jejeje). No lo hago por entrar en ninguna polémica, pero lo cierto es que, al margen de críticas varias hacia su persona, que he oído (y leído) en eñ sector durante los últimos tiempos, a mi me parece que ha explotado un nicho muy interesante. Y es muy bueno. Podrás discutir las formas, pero el fondo es impecable. Por lo menos si quieres aprender sobre scripting, en Linux o Python, realización de máquinas varias para la obtención de certificaciones, y más allá... En este sentdio de él recomiendo toda su serie en Twitch y Youtube de máquinas de preparación para el OSCP. Tienes un buscador de máquinas resueltas [aquí](https://htbmachines.github.io/) que enlaza con esos vídeos. Y su Plan de estudios para el OSCP y otras certificaciones, [aquí](https://docs.google.com/spreadsheets/d/1dzvaGlT_0xnT-PGO27Z_4prHgA8PHIpErmoWdlUrSoA/edit#gid=0). A mí me sigue pareciendo el [IPPSec](https://www.youtube.com/@ippsec) español, incluso más allá. Recientemente ha montaod su academia de Hack4you, y su cursos están muy bien, en concreto el que he mencionado arriba puedes sacar más o menos todo lo de web que te puedas encontrar en el OSCP, aunque se echa en falta la parte de Directorio Activo, que promete para una versión avanzada del mismo. Y el de [Introducción a  Linux](https://hack4u.io/cursos/introduccion-a-linux/) es muy potente también.

3. El **[OWASP Top 10](https://owasp.org/Top10/es)** y las **[OWASP Web Security Testing Guide](https://owasp.org/www-project-web-security-testing-guide/)**: Un recurso gratuito pero muy potente.

4. Ya en habla inglesa, el curso ya mencionado arriba de **TCM Security** para Directorio Activo, contiene también lo básico de Web, y para profundizar en APIS **[estos gratuitos de API Security University ](https://www.apisecuniversity.com/)**  y **[este, también de TCM Security enfocado a hacking de APIS](https://academy.tcm-sec.com/p/hacking-apis).** Aunque ese nivel de complejidad de APIS no te va a entrar en el OSCP. Puede que tengas que descubrir algún API end-point o similar, o jugar con ellos, pero poco más allá.

5. La plataforma de **[PentesterLab](https://pentesterlab.com/)** es oro puro y desde hace años (la he mencionado ya anteriormente). Tiene contenidos también gratuitos, y de calidad, blogs interesantes, etc.
	
6. Y para finalizar,  no podía dejar de mencionar el fabuloso curso gratuito de **[PortSwigger Academy](https://portswigger.net/web-security/learning-path)**. Yo todavía estoy en ello, así que, con calmita. Eso ya está un nivel por encima del OSCP, en estos momentos, a nivel web.

### Pivoting. Tunneling. Port Forwarding. 

En esta sección, con lo que te den en el OSCP está bien, pero yo me cuidaría mucho de:

1. Entender realmente cómo funciona un local port forwarding, un remote port forwarding, un dynamic port forwarding, y las casuísticas que te pueden llevar a escoger la realización de uno u otro. Entender cómo usarlo vía ssh, socat y luego ya con otras herramientas, más sencillas, pero después de haber pasado por ahí. Por que si no, te puedes encontrar que has logrado llegar a la máquina destino pivotando, pero por ejemplo, no te funciona bien la shell reversa hasta tu máquina desde esa máquina, o cosas de ese estilo... Aquí recomiendo leer:

	- Este buen post de **Hackplayers**, antiguo pero vigente perfectamnte: https://www.hackplayers.com/2018/05/taller-de-pivoting-tuneles-ssh.html
	- Este post de Pivoting con SSH, de **Juan Antonio González Mena, aka sikumy, de DeepHacking**:
		https://deephacking.tech/pivoting-con-ssh/
	- Este módulo de **HackTheBox Academy** es reciente pero tiene muy buena pinta (no lo he hecho):
		https://academy.hackthebox.com/course/preview/pivoting-tunneling-and-port-forwarding

2. Saber pivotar entre máquinas empleando más de una herramienta, por si acaso te falla una. En mi caso, **[chisel](https://github.com/jpillora/chisel)** me ha ayudado mucho. Pero tienes también **[ligolo-ng](https://github.com/nicocha30/ligolo-ng)**, o **[sshuttle](https://github.com/sshuttle/sshuttle)**. Hay muchas ¡Y recuerda que en Windows tienes formas "nativas" de hacer "Port forwarding"!  

Aún asi, añadiría estos otros recursos interesantes:
- Los siguientes artículos:

	https://deephacking.tech/pivoting-con-chisel/
	
	https://posts.slayerlabs.com/tunneling-quick-guide/

	https://academy.tcm-sec.com/p/movement-pivoting-and-persistence-for-pentesters-and-ethical-hackers

Si dominas la serie de **["Pivoting desde Cero", de S4vitar](https://www.youtube.com/watch?v=L1jSoCcvRY4)**, para preparación del eCPPT,  o te has sacado ya esa certificación, ya dominas probablemente lo que te puedas encontrar en el OSCP.


### Escalada de Privilegios en Linux y Windows.

Para escalada de privilegios, en Linux y Windows recomiendo:
	
 1. Los archiconocidos cursos de TCM Security:
	https://academy.tcm-sec.com/p/linux-privilege-escalation
	https://academy.tcm-sec.com/p/windows-privilege-escalation-for-beginners

2. Los de Tiberius, disponibles en UDEMY:
	https://www.udemy.com/course/linux-privilege-escalation/
	https://www.udemy.com/course/windows-privilege-escalation/

3. Los contenidos que ofrece **TryHackme** en el módulo:
	https://tryhackme.com/module/privilege-escalation

4. Lo que tiene **Hacktricks** correspondiente a Escalada de Privilegios:
	https://book.hacktricks.xyz/linux-hardening/privilege-escalation
	https://book.hacktricks.xyz/windows-hardening/checklist-windows-privilege-escalation

	En este sentido, considero que **Hacktricks** debería ser la Biblia de cabecera de todo el que quiera destacar en Pentesting hoy en día y no solo en cuanto escalada de privilegios, sino en todos los tipos de pentesting y fases del mismo, tanto en cloud, como web, sistemas, Directorio Activo, infraestructuras, etc. **Carlos Polop** es otro monstruo a seguir de cerca (Si no te suenan su proyecto **[PEASS-ng](https://github.com/carlospolop/PEASS-ng/tree/master)** y **[Hacktricks](https://book.hacktricks.xyz/welcome/readme) ya estás tardando). El contenido es tan vasto, que tardaríamos años en dominarlo todo, pero es una muy buena guía de referencia a tener en cuenta.

5. Como colofón, las herramientas fundamentales en escalada de privilegios, relativas a la parte de explotación de binarios, serían básicamente estas dos:

	- Para Linux: **[GTFOBINS](https://gtfobins.github.io/)**  --> En más del 80 por ciento de máquinas de preparación para el OSCP que te puedas encontrar, vas a tener que aprender a manejar esto. Y si no, será abusar de una serie de permisos de escritura en un programa, que se lanza periódicamente desde la crontab, o explotar vulnerabilidades conocidas en un programa. O emplear contraseñas que hemos descubierto por ahí, o reutilizar contraseñas,. No mucho más. Explotar vulnerabilidades de Kernel también. Pero en el examen,  ten en cuenta que este tipo de vulnerabilidades, a no ser que sean muy "estables", tienden a dejarte la máquina echa unos zorros, por lo que si no te funciona, recomendaría siempre reiniciar la máquina. Y siempre usar este tipo de vulnerabilidades como último recurso.
	- Para Windows: **[LOLBAS](https://lolbas-project.github.io/)** --> Idem, aunque esto te valdría para otras certificaciones, incluso para evasión de AV, explotación de dlls de sistema y "weaponing" de herramientas intrínsecas de Windows, etc. 	Lo demás va a ser explotación de servicios vulnerables o programas con vulnerabilidades, empleo de contraseñas encontradas por ahí, abuso de tokens con los archi-conocidos **[Potato Attacks](https://book.hacktricks.xyz/windows-hardening/windows-local-privilege-escalation/roguepotato-and-printspoofer)**, etc.

### Otros recursos interesantes

- Además de lo hasta ahora mencionado, a mí me han gustado mucho los siguientes cursos, algunos no los cuales no he llegado a terminar, porque he ido cogiendo lo que más me gustaba y me iba sirviendo, pero lo que he visto hasta el momento está muy bien. Te aseguro que algunos de ellos aunque ya un poco anticuados, como la de Eduardo Arriols, para mí han sido una referencia:
		
	1. Los cursos de **[Securízame](https://www.securizame.com/)** . De buena calidad, con unas certificaciones que no tienen nada que envidiar a las americanas. Un gran trabajo de **Lorenzo Martínez**.
	2. Los cursos (y ahí tengo predilección por los de SecDevOps y pentesting web) de **Dani Echeverri** en **[The Hacker Way](info@thehackerway.es)**
	3. Los cursos de **[Seguridad SI](Formación SeguridadSi](https://formacion.seguridadsi.com/)**. Muy buenos (incluso algunos gratuitos). Muy buena iniciativa de **Joaquín Molina**.
	4. Cursos en [**UDEMY**](https://www.udemy.com/):
		a. **["Docker y DevOps: De novato a experto"](https://www.udemy.com/course/docker-y-devops-de-novato-a-experto/)**, de **Daniel Echeverri (Adastra)**.		
		b. **["Curso Completo de Hacking Ético y Ciberseguridad"](https://www.udemy.com/course/curso-completo-de-hacking-etico-y-ciberseguridad/)** y **["Curso Avanzado de Hacking Ético y Ciberseguridad"](https://www.udemy.com/course/curso-profesional-de-hacking-etico-y-ciberseguridad)**,  de **Santiago Hernández**
		c. **["Curso Completo de Hacking Ético"](https://www.udemy.com/course/curso-completo-de-hacking-etico)** El temario está un poco desactualizado en cuanto al uso de ciertas herramientas, pero las explicaciones son muy buenas, por un experto en la materia, como es **Eduardo Arriols**.
		d. Toda la serie de **Vonnie Hudson" sobre "How to Hack The Box to your OSCP", empezando por la serie de **["How to hack the box to your oscp"](
		https://www.udemy.com/course/how-to-hack-the-box-to-your-oscp)** (son varios), donde resuelve varias máquinas de **HTB** desde un punto de  vista enfocado al uso e identificación de Ataques, Técnicas y Procedimientos en **MITRE ATT&CK**. Muy interesantes los de **"Advance Privilege Escalation..."** del mismo autor (en inglés, eso sí).
		e. También en inglés, me gustan mucho estos dos docentes en **UDEMY**: **Zaid Sabih**, de *zSecurity*, **(especialmente su **["Learn Bug Bounty Hunting and Web Security Testing"](https://www.udemy.com/course/learn-bug-bounty-hunting-web-security-testing-from-scratch")** y **"Uncle Rat"**, también llamado **"XSS Rat"** y su **["Uncle Rat's Web Application Hacking And Bug Bounty Guide"](https://www.udemy.com/course/uncle-rats-bug-bounty-guide)**
	
- Otro día hablaremos de los libros, que los ahí y muy interesantes, tanto en inglés como en español.
- No quiero finalizar sin recomendaros que hagáis algo que yo no he hecho y también considero un error: Mejor recorrer juntos el camino, que en solitario. Si podéis empezar a formar parte de la comunidad aportando o preguntando, hacedlo. Eso sí, siempre desde la humildad y habiendo investigando un poco por vuestra cuenta porque en este sector sobre todo, no gusta nada que pidas que te le den todo hecho, y si me has leído hasta aquí, no es una carrera a corto plazo en la que vayas a ir de la manita para todo, precisamente. Destacaría iniciativas muy buenas en este preciso momento, aunque hay muchas más:
	- **Securiters**, con la cabeza visible de Marta Barrios (@martrudix), con https://www.securiters.com/hckcmp/ (enfocado a profesionales en femenino).
	- La comunidad general de **Securiters**, con su Canal de Telegram en: https://t.me/ComunidadSecuriters
	- La comunidad de **"The Hacker Way"**, con la cabeza visible de Adastra: https://t.me/TheHackerWay  y su recién creada **Comunidad Web con diferentes sistemas de subscripción** en: https://comunidad.thehackerway.es/

En definitiva, cualquier comunidad en **Twich, Youtube, Telegram, o canal de Discord** donde os sintáis cómodos, con libertad para aportar y recibir ideas, y montar algún grupete para "hacer cosas, de vez en cuando". Aprenderéis un montón y os pondréis al día de forma amena. 
	
Por último, yo, por mi parte, recientemente inicié una serie de **[Posts en Medium](https://medium.com/@drenfermo)** que pretenden tocar muchas cositas par el OSCP y más allá, por si te animas. Están en Inglés, pero intentaré pasar lo más interesante a español en este mismo blogl, así que ¡estad atent@s!


Y hasta aquí. Si habéis llegado hasta el final de estos posts, muchísimas gracias por vuestra paciencia, de corazón. Y recordad que, como decía *Winston Churchill*:

### "El éxito es la capacidad de ir de fracaso en fracaso sin perder el entusiasmo"



