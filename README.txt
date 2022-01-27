Autor de la Vaina: eljavo


-Antes de nada:
Si tu antivirus detecta un virus aqui, apagalo un rato o ponle una excepción o algo. Si no encuentras el .exe probablemente lo haya eliminado.


-Como lo ejecuto?
Sigue la siguiente ruta: Image2Ascii->py->main->
Dentro de la carpeta main busca el archivo "Image2Ascii.exe".
Ese es el ejecutable, para no andar buscandolo te recomiendo hacerle un acceso directo (btn dcho) y llevartelo donde quieras.


-Ejecucion:
Al ejecutar el .exe tendras que seguir los siguientes pasos:
	*Localizar tu imagen: recomiendo haberla movido al escritorio para ahorrarte errores de permisos o acceso. No se que formatos traga y cuales no pero si se rompe y le has metido algo raro ya sabes por que es, jpg, jpeg, png, no te rayes.

	*Especificar el modo de impresion: (0/1) si tu lector de texto este que estas usando p.ej tiene fondo blanco escribe 1, si es negro 0. Esta opcion invertirá la forma de entender los caracteres. Si lo haces mal la imagen saldrá en "negativo".

	*Especificar el contraste: Puedes hacer un pequeño preedit de contraste para mejorar la calidad del resultado. Si introduces 1, se queda como está, si introduces más, aumenta el contraste y menos disminuye. Para que te hagas una idea yo suelo meterle entre 1 y 1.7 pero todo es jugar.

	*Especificar el ratio de compresion: Se trata de cuanto quieres comprimir la imagen sobre la original. Si quieres dejarla igual, ponlo al 1, si quieres a la mitad, ponlo al 0.5 etc... Cuanto mas bajo este valor, menos caracteres escribirá. Recomiendo poner ratios bajos de forma que se aprecien los caracteres. Para ello lo mejor es que pruebes ya que depende del tamaño de la imagen original. Ten encuenta que este es el parametro que establece la complejidad del algoritmo y es cuadratico, en cristiano, cuanto le cueste a tu pc ejecutarlo depende de este parametro y el tamaño de la imagen y la progresion no es lineal, si lo pones al 0.5 no tarda el doble que a 0.25, tarda muchisimo mas.


-Donde estan las letritas??
Una vez completada la renderizacion tu texto se encontrará en la carpeta "out" dentro de la carpeta general "Image2Ascii". El archivo se llama "canvas.txt" puedes llevartelo cambiarle el nombre modificarlo, eliminarlo o lo que quieras, eso si, si no te lo llevas la proxima ejecucion se sobrescribirá.

Para ver la imagen debes abrir el ".txt" y cambiar la fuente a "consolas" y hacer "ctrl,-" para alejarte, tambien puedes jugar con el tamaño de fuente y negrita.

Creo que eso es todo.

Saludos

eljavo®