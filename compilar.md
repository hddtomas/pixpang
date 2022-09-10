# Tutorial de como compilar PiX Pang

## 2.0 y antes
Requisitos para compilar:
Fenix 0.84 ([Click aquí](https://web.archive.org/web/20050211004716/https://fenix.divsite.net/ "Click aquí") | **Descargas > Fenix-0.84b-win32-binary.zip**)

Requisitos para iniciar:
- PC / Máquina virtual con Windows XP o inferior 
- Por lo menos un poco de conocimiento minimo de lo que vas a hacer

Una vez que tengamos todo esto, se debe ir a la carpeta del juego y luego a la carpeta src, donde deberian estar todos los archivos fuente del juego listos para compilar. Una vez hecho eso, deberiamos encontrar un archivo BAT para compilar el juego, en caso de que este no exista, creamos un archivo bat y ponemos el siguiente código:
```bash
echo off
cls
echo Compilando pixpang.prg
fxc -g pixpang.prg
pause
echo pixpang.prg compilado
pause 
```

Lo que este código hace es compilar el archivo pixpang.prg, el cual contiene todo el código del juego.

Ahora bien, si ejecutamos el archivo BAT, puede que compile el juego o no lo haga, esto dépende mucho de la versión del juego.

En caso de que el juego no compile porque no existe el archivo, este dañado/corrupto o faltan archivos, tenemos que ir al zip que descargamos anteriormente (**Fenix084-win32-binary.zip**) y buscar los archivos FXI.exe, SDL.dll, SDL.mixer.dll y zlib.dll, una vez encontrados, los debemos pasar a la carpeta src, o en la que estamos actualmente.

Ahora bien, si ejecutamos el archivo bat, puede ser que el juego compile o tire el error:
`Cannot load library IMAGE`

En el caso de que tire este error, lo que debemos hacer es nuevamente abrir el archivo zip de Fenix 0.84, ir a dll, ir a image, ir a bin y pasar los 4 archivos que esten dentro a la carpeta src.

Si el juego compilo bien y sin problemas, deberia salir el archivo "pixpang.dcb".

Ahora, vamos a la carpeta base del juego, vayamos al zip nuevamente y pasemos los siguientes archivos (si ya existen, reemplazalos):
FXI.exe, SDL_mixer.dll, SDL.dll, zlib.dll.
También pasamos nuevamente los archivos image (dll > image > bin y los 4 archivos)

Una vez hecho todo esto, hacemos un bat y ponemos lo siguiente:
```bash
fxi pixpang.dcb
```
¡Felicitaciones! Haz logrado compilar un juego en Fenix, siempre que quieras abrir el juego, puedes ejecutar ese comando.

## 2.1
TBD
