# Postwork
Subir repositorio postwork1
Lo primero a definir es con que conjunto de datos vas a trabajar.

$ mkdir MiProyecto
$ cd MiProyecto
MiProyecto $

Descarga u obtén el conjunto de datos elegido y colocalo dentro de la carpeta de tu proyecto.
http://files.grouplens.org/datasets/movielens/ml-25m.zip

MiProyecto $ curl -O http://files.grouplens.org/datasets/movielens/ml-25m.zip
[...]
MiProyecto $ unzip ml-25m.zip  # Sólo en caso de requerir descomprimir
MiProyecto $ ml-25m.zip  # Elimina el archivo zip en caso de existir
MiProyecto $
Crea una copia de respaldo de tu proyecto, nunca está de más

MiProyecto $ cd ..
$ cp -a Peliculas Peliculas.1
$ ls
Peliculas Peliculas.1
$
