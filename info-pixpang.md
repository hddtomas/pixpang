En este archivo, encontraras información sobre PiX Pang.

# Acceder a los archivos de la 2.1 (solo Windows)
Como ya sabran, en PiX Pang 2.1, en vez de venir con una carpeta con todos los archivos del juego y un ejecutable, simplemente viene un ejecutable, que aunque es una opción muy portable, se vuelve díficil obtener algún recurso del juego.
Para acceder a los archivos de la versión 2.1, se debe abrir el juego y luego ir al administrador de tareas, ir a la sección detalles y buscar pixpang.exe, le damos click derecho y luego "Abrir ubicación del archivo", una vez hecho todo eso, ya estaremos en la carpeta del juego, la cual esta ubicada en una parte de la carpeta %temp% de Windows.

# Páginas web anterior al pixjuegos.com que conocemos hoy en día:
Esta es la lista de páginas donde se almacenaban archivos y información de PiX Pang:
https://web.archive.org/web/20061212200727/http://pixpang.pixjuegos.com/web/
https://web.archive.org/web/20050202142303/http://pixpang.nodani.com/
https://web.archive.org/web/20060720190333/http://pixpang.panreyes.com/
https://web.archive.org/web/20031103020916/http://pixpang.cjb.net/

# Origen de los personajes de PiX Pang
https://danigm.wordpress.com/2005/10/26/pix-pang/

Este blog muestra a DaniGM haciendo los personajes de PiX Pang (PiX y PuX).
Curiosidad: Pang Zero (Otro clon de Super Pang) usaba los sprites de los personajes de PiX Pang, hasta que DaniGM les hizo uno:
https://danigm.wordpress.com/2006/09/07/graficos-para-pang-zero/

# Entrevista a PiX Juegos

Esta entrevista se hizo el 3 de febrero en 2007, aquí esta el link por si te interesa y quieres leerlo: https://gizmos.republica.com/videojuegos/entrevista-a-pixjuegos.html

Gracias a esta entrevista podemos saber de que los fondos del juego son fotos de algunos amigos de panreyes y gente que contribuyo al juego, además de que hubieron juegos cancelados o que nunca salieron a la luz, como Secret Of PiX. Por cierto, seguramente el juego que Carles estaba desarrollando, era probablemente Garnatron, ya que es un shoot em up, como se describe en la entrevista.

# Código fuente de algunos proyectos
El código fuente de PiX Pang + otros proyectos de PiX Juegos, los encontraras aquí: https://github.com/tomiiiiiiiii/pixjuegos
De suerte lo pude guardar a tiempo.. ya que panreyes saco el código fuente de todos los juegos, al día de hoy no entiendo porque.

# Versiones no encontradas
Ya he buscado en internet, incluso en la Wayback Machine, pero no hay nada. 

Y también la versión 0.6, que en mi opinión, es muy rara.
Esta versión esta en el lugar de releases, es 100% jugable, aunque la verdad no lo recomiendo jugar por el escaso contenido que tiene y lo aburrido que es.
Esta versión es muy vieja y empezo como un "remake" del Super Pang, pero como vemos al final, paso a ser un clon de Super Pang, así que no, no es un juego aparte.

En el futuro, veremos si hay nuevas versiones. (hasta ahora he encontrado la 1.6c, 1.6b, 1.6d, la 2.0, la 2.1 del 2010, un apk, un mod y nada más).

# Modo Safari
Este modo de juego esta disponible en versiones anteriores a la 2.1 (menos la 0.6), ya que fue eliminada en la 2.1. Se trata de lanzar huevos a bolas que aparecen a la derecha de la pantalla (yendo hacia la izquierda), luego de destruir todas las bolas (que generalmente son 200 o 100 la cantidad de bolas que tienes que destruir), peleas contra un personaje (PuX exactamente) que tiene 5 vidas, no es tan complicado. Este modo de juego es obviamente un extra ya que en los juegos originales de Pang, no existe este modo. 

Aunque parezca que este modo de juego permite un segundo jugador controlado por el mouse / teclado, lamentablemente no es posible.

# Editor de niveles
El editor de niveles te permite crear niveles para el juego en el modo Custom o Adventure mode, el formato de estos archivos es .pang
La interfaz gráfica del editor de niveles es muy poco intuitivo y además se bugea de vez en cuando, así que siempre chequea los niveles que vayas a hacer.

El editor de niveles no permite especificar un fondo para el nivel, esto se debe hacer manualmente.
Para agregar, los niveles creados en el editor de niveles son guardados en la carpeta príncipal del juego.

# Jugar por LAN
Jugar en LAN es imposible, lamentablemente, pero en la 2.0 hay un código para jugar en LAN. Lo más probable es que este incompleto y además no hay ninguna forma de activar este modo, también hay que aclarar que falta la libreria "net.dll", la cual no he conseguido completamente hasta ahora.

# Mejoras para alguna modificación de PiX Pang
Si alguien llega a hacer esto, pues, aquí una lista de mejoras para el juego:
1. ¡Mas fondos y niveles! Seria muy cool la verdad, porque por el momento el juego es muy corto, y los modos extra solo añaden unos minutos extra de juego, con el tema de los fondos, que tengan la misma estetica que usa el juego.
2. Editor de niveles, aunque esto existe en la 2.0 (pero no en la 2.1), es muy poco intuitivo (Además de que, se bugea mucho)
4. ¿Multijugador LAN? En si en la 2.0 existe pero habilitarlo es algo muy costoso.
5. El menú de la 2.0 devuelta a la 2.1

# Notas de los desarrolladores para cambiar el juego (2007)
- Para cambiar los fondos simplemente sustituye los fondos de la carpeta fondos, podéis mirar la resolución de los fondos en los fondos mismos.
- Para cambiar los gráficos del juego ya tendréis que utilizar una herramienta de Fénix, llamada FPG Edit y ya buscaros la vida para sustituir los gráficos de los ficheros FPG en la carpeta FPG. No es muy complicado, simplemente conocerlo un poco. Luego hay algún que otro gráfico en la carpeta cosas. (https://bitbucket.org/dacucar/smart-fpg-editor/src/master/)
- Para cambiar las músicas están en la carpeta cd-ogg. Necesitaréis convertir las músicas (wav,mp3,wma,...) al formato OGG, os recomiendo dbPowerAmp.
- Para cambiar los niveles que hay actualmente tenéis que utilizar el editor de niveles integrado en PiX Pang. Los niveles los guarda en la carpeta pantallas, pero luego podéis coger esos mismos niveles y sustituir los de la carpeta tour. (**NOTA:** No puedes crear jefes ni nada a menos que cambies el código fuente)
- Para cambiar los sonidos, están en la carpeta wav.
- Y para cambiar el juego directamente tenéis el código fuente en la carpeta src. (pixpang.prg y otros archivos)

# Bugs de la 2.1
1. Salir de la ventana con la tecla **Windows** hara que el mouse se bugee. Esto no pasa en la 2.0 (Para arreglarlo, presiona **Ctrl + Alt + Supr**, clickea en administrador de tareas y termina el proceso BennuGD o pixpang.exe, si quieres que esto no pase mas, juega en modo ventana, que es lo más recomendable considerando la baja resolución que inicia el juego)
2. Al cargar una partida, el score y las vidas se resetean, en el caso del score, se resetea a 0, y las vidas se resetean a 10. Puedes aprovechar este bug para no perder en el modo aventura aunque la verdad siento que esto arruina un poco el gameplay.

# Bugs de la 2.0
Aquí una lista de bugs en la 2.0 que yo conozco.

1. Al elegir al segundo jugador como la computadora, si iniciamos una partida, salimos y elegimos que no queremos ningun segundo jugador, al iniciar otra partida, se escuchara el sonido de disparo infinitamente. (Requiere reinicio del juego para arreglar)
2. A veces, si agarras demasiados poderes de ralentización en el modo aventura (y probablemente en niveles personalizados), este puede quedar hasta que termine el nivel.
3. En el nivel 15, el juego se puede crashear. Asegurate de guardar tu partida antes. 
4. Hay veces que las partidas no se guardan, en vez de eso, el juego se crashea.
5. Hay veces que al cargar una partida, el juego se crashea. (Esto no pasa más de una vez)
6. Jugar por mucho tiempo puede causar que los niveles carguen mal y la partida no se guarden correctamente. (Esto pasa cuando se deja un nivel pausado por demasiado tiempo, y con demasiado tiempo me refiero a más de 2 horas) 

# Bugs de la 1.6 beta
1. Al elegir un segundo jugador como computadora y después poner que no queremos a un segundo jugador, el juego lo tomara como que queremos un segundo jugador como computadora (solo pasa especificamente al elegir la computadora).

# Versiones que SI existen pero no sabemos si existen descargas.
PiX Pang 1.5 y PiX Pang 1.4
Que yo sepa estas versiones son imposibles de conseguir.

# Jugar PiX Pang 2.1 con 2 jugadores
Es muy fácil, simplemente conecta un joystick generico y listo, ve a new game y te pondra la elección de 1 jugador o 2 jugadores.

# Personajes navideños
En PiX Pang 2.0 y PiX Pang 2.1, el 24 y 25 de diciembre se activan lo que serían los personajes navideños. Esto aplica para PiX y PuX.
En versiones anteriores no he visto personajes clásicos con un modo clásico (ejem: 1.6a).

# Tiempo bala | Ancla (Curiosidad)
Resulta que el sonido de este poder esta generado por la boca de panreyes + edición de audio.
https://web.archive.org/web/20050206112725/http://pixpang.nodani.com/es/index.php

# ¿Archive de PiX Pang en PSP?

Hoy (27/12/2021) he encontrado un archive de una versión de PiX Pang en PSP.
https://archive.org/details/pix-pang-22.7z

(13/11/2022) Hasta el día de hoy no lo he probado, cuando tenga tiempo (mediados de diciembre probablemente) voy a probar esta versión junto a la de Dreamcast. 

# Modo Debug en PiX Pang 2.0
Hay un modo debug que se activa pulsando las siguientes teclas:
D + B + G y después la M.
(DBG de debug, y M de mode)

# Port de PiX Pang a la Dreamcast
PiX Pang tiene un port a la Dreamcast y es este:
https://www.pixjuegos.com/descargas/pixpang-2.1-dreamcast.zip

También existe un video sobre el port y aquí está (Lanzado desde SDReader):
https://www.youtube.com/watch?v=molav3hI3EQ&ab_channel=DCeric

Este port sinceramente está muy bugeado y no tiene muchas cosas, pero es jugable.

Hace unos años (7 años apróximadamente) fue lanzado un port a la Dreamcast pero esta vez fue porteado con BennuGD, la noticia está aca:
https://dreamcast-news.blogspot.com/2015/08/pixpang-v22.html?spref=tw
(Abajo de todo se puede descargar el port, no lo he probado todavía asi que no puedo asegurar de que funciona)

# Final de PiX Pang
El final está inspirado en un anime llamado Chobits:

![0210](https://user-images.githubusercontent.com/78988582/201530300-3b915005-f7ae-4657-a86b-20ec482ac6ec.jpg)


https://www.youtube.com/watch?v=KfzU_LBaDys&ab_channel=regn13ev


