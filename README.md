# EntornosDesarrollo

Author: rafael Madrigal

Creación y Modificación de archivos en un repo. (Desde el local al remoto.)

1) Una vez creado en GitHub el repo lo clonamos en local
git clone git@github.com:rmadrigal1/EntornosDesarrollo.git

2) Se modifica un archivo, por ejemplo el readme.md Si miramos el estado veremos que hay cambios por aplicar
git status

3) Se añade al trackin el cambio haciendo el commit
git commit -am "Se añade información"

4) Se suben los cambios al repo remoto
git push origin main

Modificación de archivos en un repo. (Desde el remoto al local.)
1) Modificas el archivo, o lo creas en GitHub, guardándo los cambios.

2) Miramos el estado
git status

3) Descargamos los cambios
git fetch

4) Actualizamos archivos
git pull origin main

Añadir archivo al repo. (local a remoto)
1) Se crea el archivo. Ej: archivo1.txt

2) Se añade al repo.
git add archivo1.txt

3) Se añade los cambios al tracking
git commit -am "Se sube un nuevo archivo"

4) Se suben los cambios
git push origin main
