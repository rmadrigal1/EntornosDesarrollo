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

