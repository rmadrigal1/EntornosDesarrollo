# EntornosDesarrollo

Author: rafael Madrigal

Creaci�n y Modificaci�n de archivos en un repo. (Desde el local al remoto.)

1) Una vez creado en GitHub el repo lo clonamos en local
git clone git@github.com:rmadrigal1/EntornosDesarrollo.git

2) Se modifica un archivo, por ejemplo el readme.md Si miramos el estado veremos que hay cambios por aplicar
git status

3) Se a�ade al trackin el cambio haciendo el commit
git commit -am "Se a�ade informaci�n"

4) Se suben los cambios al repo remoto
git push origin main

Modificaci�n de archivos en un repo. (Desde el remoto al local.)
1) Modificas el archivo, o lo creas en GitHub, guard�ndo los cambios.

2) Miramos el estado
git status

3) Descargamos los cambios
git fetch

4) Actualizamos archivos
git pull origin main

A�adir archivo al repo. (local a remoto)
1) Se crea el archivo. Ej: archivo1.txt

2) Se a�ade al repo.
git add archivo1.txt

3) Se a�ade los cambios al tracking
git commit -am "Se sube un nuevo archivo"

4) Se suben los cambios
git push origin main
