En este archivo, encontraras información del juego.

# Entrevista a PiX Juegos

Esta entrevista se hizo el 3 de febrero en 2007, aquí esta el link por si te interesa: https://gizmos.republica.com/videojuegos/entrevista-a-pixjuegos.html

Gracias a esta entrevista podemos saber de que los fondos del juego son fotos de algunos amigos de panreyes y gente que contribuyo al juego, además de que hubieron juegos cancelados o que nunca salieron a la luz, como Secret Of PiX. Por cierto, el juego que Carles estaba desarrollando, era probablemente Garnatron, ya que es un shoot em up, como se describe en la entrevista.

# Código fuente de algunos proyectos
El código fuente de PiX Pang + otros proyectos de PiX Juegos, los encontraras aquí: https://github.com/tomiiiiiiiii/pixjuegos
De suerte lo pude guardar a tiempo.. Ya que panreyes saco el código fuente de todos los juegos.
Ahora, si los quieres compilar, ya es trabajo tuyo, lo unico que puedo decirte es que si estás tratando de compilar un juego del 2005 o 2004, usa Fenix 0.83 o 0.84, si quieres compilar un juego del 2006 al 2013, usa BennuGD (ultima release) o Fenix 0.93.

# Versiones no encontradas
Ya he buscado en internet, incluso en la Wayback Machine, pero no hay nada. 

Lo unico que he llegado a encontrar fue la 1.6b (b de beta supongo?), pero no se puede compilar por un error de libreria.
https://archivos.abcdatos.com/programas/Z/Z2691/pixpang16.tar.bz2

Y también la versión 0.6, que en mi opinión, es muy rara.
Esta versión esta en el lugar de releases, es 100% jugable, aunque la verdad no lo recomiendo jugar por el escaso contenido que tiene y lo aburrido que es.
Tiene demasiadas similitudes con la 1.6b, como por ejemplo, fondos iguales, capaz que mismo sonidos (**?**) y entre otros, así que lo considero como una versión vieja de PiX Pang en vez de un juego extra.

En el futuro, veremos si hay nuevas versiones, o simplemente nada.

# Modo Safari
Este modo de juego esta disponible en versiones anteriores a la 2.1 (osea, 2.0 y capaz 1.6b, en la 0.6 este modo ya no esta disponible), ya que fue eliminado en la 2.1. Se trata de lanzar huevos a bolas que aparecen a la derecha de la pantalla, luego de destruir todas las bolas (que generalmente son 200 las que tienes que destruir, o, a veces, un poco menos), peleas contra un personaje que tiene 5 vidas, no es tan complicado, aunque los controles cambian demasiado. Por ejemplo, para apuntar se usa las teclas o el mouse, y para tirar huevos, se usa el click izquierdo, son controles muy diferentes a los del modo aventura.

# Editor de niveles
El mismo nombre lo dice, lo unico que puedo decir es que es muy poco intuitivo, en vez de ser una interfaz, es puro texto, hubiera sido buenisimo un sistema de drag and click pero bueno. Para jugar en niveles personalizados (solo 2.0, ya que en la 2.1 no existe), ve a play, clickea en custom mode y empieza a jugar. Además si no me equivoco, no se puede cambiar de fondo, para hacer esto, se necesita modificar el juego.

# Jugar por LAN
Aunque panreyes haya puesto que se agrego para jugar en la red (probablemente por LAN, imaginate que fueran servidores xd), no hay ninguna forma de activar esto. 
Si quieres jugar con otra persona, solo necesitas que este en tu misma casa y use un ratón, o conecte un joystick y use un programa para hacerlo funcionar. Tal vez el futuro nos dara una solución a esto y lo hara mas fácil, ya que estamos en cuarentena xD.

Por el momento es imposible jugar a travez de LAN o red, esto requiere cambiar el código fuente del juego y obviamente, hacer demasiado trabajo.

# Mejoras para alguna modificación de PiX Pang
Si alguien llega a hacer esto, pues, aquí una lista de mejoras para el juego:
1. ¡Mas fondos y niveles! Seria muy cool la verdad, porque por el momento el juego es muy corto, y los modos extra solo añaden unos minutos extra de juego, con el tema de los fondos, que tengan la misma estetica que usa el juego xD.
2. Editor de niveles, aunque esto existe en la 2.0 (pero no en la 2.1), es muy poco intuitivo y además no se puede cambiar de fondo.
3. Arreglar los bugs de la 2.1, claro.
4. ¿Multijugador LAN? Seria cool, pero no se si BennuGD o Fenix permite eso.
5. El menú de la 2.0, el de la 2.1 no es que sea horrible, pero no me gusta como el de la 2.0

# Notas de los desarrolladores para cambiar el juego (2007)
- Para cambiar los fondos simplemente sustituir los fondos de la carpeta fondos, podéis mirar la resolución de los fondos en los fondos mismos.
- Para cambiar los gráficos del juego ya tendréis que utilizar una herramienta de Fénix, llamada FPG Edit y ya buscaros la vida para sustituir los gráficos de los ficheros FPG en la carpeta FPG. No es muy complicado, simplemente conocerlo un poco. Luego hay algún que otro gráfico en la carpeta cosas.
- Para cambiar las músicas están en la carpeta cd-ogg. Necesitaréis convertir las músicas (wav,mp3,wma,...) al formato OGG, os recomiendo dbPowerAmp.
- Para cambiar los niveles que hay actualmente tenéis que utilizar el editor de niveles integrado en PiX Pang. Los niveles los guarda en la carpeta pantallas, pero luego podéis coger esos mismos niveles y sustituir los de la carpeta tour.
- Para cambiar los sonidos, están en la carpeta wav.
- Y para cambiar el juego directamente tenéis el código fuente en la carpeta src.

# Bugs de la 2.1
1. El primer bug de la 2.0 sigue pasando, solo que esta vez es muy raro que pase. (No se puede arreglar)
2. Salir de la ventana con la tecla **Windows** hara que el mouse se bugee. Esto no pasa en la 2.0 (Para arreglarlo, presiona **Ctrl + Alt + Supr**, clickea en administrador de tareas y termina el proceso BennuGD, si quieres que esto no pase mas, juega en modo ventana)
3. Al cargar una partida, el score y las vidas se resetean, en el caso del score, se resetea a 0, y las vidas se resetean a 10. Puedes aprovechar este bug para no perder en el modo aventura.

# Bugs de la 2.0
Aquí una lista de bugs en la 2.0 que yo conozco.

1. En el modo aventura, cuando se pasa de nivel, algunos fondos se saltan. (No se puede arreglar)
2. Hay bugs de gráficos al cambiar de ventanas, no se si esto es un bug de VMWare Workstation (muy probable) o del juego. (Requiere un reinicio del juego para arreglar)
3. Al elegir al segundo jugador como la computadora, si iniciamos una partida, salimos y elegimos que no queremos ningun segundo jugador, al iniciar otra partida, se escuchara el sonido de disparo infinitamente. (Requiere reinicio del juego para arreglar)
