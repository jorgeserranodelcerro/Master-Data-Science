# Linea de Comandos

Aquí dejo algunos de los comandos que hemos aprendido.


+ ls --> lista los ficheros y directorios de una ruta, si no le indicamos ruta se realiza sobre la carpeta en la que nos encontramos.
+ cat --> muestra por pantalla el contenido de un fichero.
+ cp <origen> <destino> --> copia un fichero de la ruta de origen a la ruta de destino.
+ mv <origen> <destino> --> mueve un fichero de la ruta de origen a la ruta de destino.
+ rm <fichero> --> elimina el fichero en cuestión.
+ mkdir <nombre> --> crea un directorio con el nombre indicado.
+ cd <directorio> --> cambia nuestro directorio actual por el que indicamos.
+ chmod <permisos> <fichero> --> cambia los permisos sobre un fichero.
+ touch <fichero> --> crea un fichero.
+ wc --> cuenta las palabras, lineas y byte de un fichero.
+ head <fichero> --> Muestra las primeras lineas de un fichero.
+ tail <fichero> --> Muestra las últimas lineas de un fichero.
+ find --> Busca un fichero por nombre y/o tipo fichero y/o tamaño y/o última modificación, etc.
+ | --> el uso del pipe nos sirve para encadenar distintos comandos.	
+ uniq --> nos devuelve o elimina (depende los parametros) los duplicados.
+ sort --> ordena las lineas de un texto. Podemos indicarle el delimitador en un fichero csv.
+ cut --> podemos decir el delimitador y nos podemos quedar con las columnas que queramos.
+ paste --> concatena horizontalmente.
+ tr --> el típico replace de otros lenguajes, nos permite cambiar o borrar un patrón.
+ grep --> nos permite quedarnos solo con las lineas que cumplen un patrón.
+ zip/unzip, zipinfo, ... --> Comando para trabjar con ficheros comprimidos
+ Jobs en background, matar proceso ...
+ Shel Cript --> Hemos creado nuestro propio script con parametros de entrada y lo hemos ejecutado desde la consola. Además,  lo hemos añadido al PATH.


# CSVKIT
Hemos visto una serie de comandos para trabajar con CSVs. Algunos ejemplos son:
+ csvlook --> Nos permite ver un ficheros csv como una tabla.
+ csvstat --> Nos devuelve las estadisticas sobre casa columna del csv.
+ csvcut --> lo mismo que teniamos en el comando cut.
+ csvgrep --> similar al comando grep pero sobre un csv.
+ csvsort --> ordenad las columnas de un csv.
+ csvsql --> genera la sentencia CREATE TABLE del csv del lenguaje sql indicado.

# GIT
![alt x](esquema_Git.png)

# CHEAT SHEETS
![alt x](git.pdf)
![alt x](Linux01.pdf)
![alt x](Linux02.pdf)
