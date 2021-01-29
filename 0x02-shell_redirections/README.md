0x02-shell_redirections
Un proyecto de introducción a las redirecciones de  I/O y los caracteres especiales en BASH.

Descripciones de los comandos:

0-hello_world: imprime Hello, World, seguido de una nueva línea en la salida estándar.

1-confusion_smiley: muestra una carita confusa "(Ôo) '.


2-hellofile: muestra el contenido del archivo / etc / passwd.


3-twofiles: muestra el contenido de / etc / passwd y / etc / hosts.


4-lastlines: muestra las últimas 10 líneas de / etc / passwd.


5-firstlines: muestra las primeras 10 líneas de / etc / passwd.


6-third_line: muestra la tercera línea del archivo iacta.


7-file: crea un archivo llamado exactamente \ * \\ '"Holberton School" \' \\ * $ \? \ * \ * \ * \ * \ * :) que contiene el texto Holberton School que termina con una nueva línea.


8-cwd_state: escribe en el archivo ls_cwd_content el resultado del comando ls -la. Si el archivo ls_cwd_content ya existe, debe sobrescribirse. Si el archivo ls_cwd_content no existe, créelo.


9-duplicate_last_line: duplica la última línea del archivo iacta.


10-no_more_js: elimina todos los archivos normales (no los directorios) con extensión .js que están presentes en el directorio actual y todas sus subcarpetas.


11-directorios: cuenta el número de directorios y subdirectorios en el directorio actual.


12-newest_files: muestra los 10 archivos más recientes en el directorio actual.


13-único: toma una lista de palabras como entrada e imprime solo las palabras que aparecen exactamente una vez.


14-findthatword: muestra líneas que contienen la raíz del patrón del archivo / etc / passwd.


15-countthatword: muestra el número de líneas que contienen el patrón bin en el archivo / etc / passwd.


16-whatsnext: muestra líneas que contienen la raíz del patrón y 3 líneas después de ellas en el archivo / etc / passwd.


17-hidethisword: muestra todas las líneas del archivo / etc / passwd que no contienen el patrón bin.


Solo 18 letras: muestra todas las líneas del archivo / etc / ssh / sshd_config que comienzan con una letra.


19-AZ: reemplaza todos los caracteres A y c de la entrada a Z y e, respectivamente.


20-hiago: elimina todas las letras c y C de la entrada.


21-reverse: invierte su entrada.


22-users_and_homes: muestra todos los usuarios y sus directorios de inicio, ordenados por usuarios.


100-empty_casks: busca todos los archivos y directorios vacíos en el directorio actual y todos los subdirectorios con las especificaciones:
Solo se deben mostrar los nombres de los archivos y directorios (no la ruta completa)
Los archivos ocultos deben aparecer en la lista
Un nombre de archivo por línea
La lista debe terminar con una nueva línea.
No se permite usar nombre de base, grep, egrep, fgrep o rgrep


101-gifs: enumera todos los archivos con una extensión .gif en el directorio actual y todos sus subdirectorios con las especificaciones:
Los archivos ocultos deben aparecer en la lista
Solo se deben enumerar los archivos normales (no los directorios)
Los nombres de los archivos deben mostrarse sin sus extensiones.
Los archivos deben ordenarse por valores de bytes, pero no distinguen entre mayúsculas y minúsculas
Un nombre de archivo por línea
La lista debe terminar con una nueva línea.
No se permite usar nombre de base, grep, egrep, fgrep o rgrep


102-acróstico: decodifica acrósticos que usan la primera letra de cada línea con las especificaciones:
El mensaje "decodificado" debe terminar con una nueva línea
No se permite usar grep, egrep, fgrep o rgrep


103-the_biggest_fan: analiza los registros de los servidores web en formato TSV como entrada y muestra los 11 hosts o direcciones IP que realizaron la mayoría de las solicitudes con las especificaciones:
Ordene por número de solicitudes, host más activo o IP en la parte superior
No se permite usar grep, egrep, fgrep o rgrep
