# Tutorial de como compilar PiX Pang

## 1.6 hasta 2.0
Requisitos para compilar:
Fenix 0.84 ([Click aquí](https://web.archive.org/web/20050211004716/https://fenix.divsite.net/ "Click aquí") | **Descargas > Fenix-0.84b-win32-binary.zip**)
PiX Pang 1.6  o 2.0 Source (generalmente ya vienen incluidas en el juego)

Requisitos para iniciar:
Máquina virtual con Windows XP (al menos 2 gbs de ram)

Una vez que tengamos todo esto, se debe ir a la carpeta del juego y luego a la carpeta source, donde deberian estar todos los archivos del juego. Una vez hecho eso, deberiamos encontrar un archivo BAT para compilar el juego, en caso de que este no este, creamos un archivo bat y ponemos el siguiente código:
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

Ahora bien, si ejecutamos el archivo BAT, no pasara nada, o simplemente el juego compilara, esto depende de cada versión.

En caso de que el juego no compile porque no existe el archivo, esta dañado/corrupto o faltan archivos, tenemos que ir al zip que descargamos anteriormente (Fenix084-win32-binary.zip) y buscar los archivos FXI.exe, SDL.dll, SDL.mixer.dll y zlib.dll, una vez encontrados, los debemos pasar a la carpeta src, o en la que estamos actualmente.

Ahora bien, si ejecutamos el archivo bat, puede ser que el juego compile o simplemente tire el error:
`Cannot load library IMAGE`

En el caso de que tire este error, lo que debemos hacer es nuevamente abrir el archivo zip de fenix 084, ir a dll, ir a image, ir a bin y pasar los 4 archivos que están dentro a la carpeta src.

Si el juego compilo bien y sin problemas, deberia salir el archivo "pixpang.dcb".

Ahora, vamos a la carpeta base del juego, vayamos al zip nuevamente y pasemos los siguientes archivos (si ya existen reemplazalos):
FXI.exe, SDL_mixer.dll, SDL.dll, zlib.dll.
También pasamos nuevamente los archivos image (dll > image > bin y los 4 archivos)

Una vez hecho todo esto, hacemos un bat y ponemos lo siguiente:
```bash
fxi pixpang.dcb
```
Finalmente, abrelo, y con eso ya deberia abrir el juego, en caso de que no abra, asegurate de que estes usando una máquina virtual.



## 2.1
Próximamente...
