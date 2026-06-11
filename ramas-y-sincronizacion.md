Ramas y sincronización

git branch
Permite crear, listar y administrar ramas dentro de un repositorio. Las ramas facilitan el trabajo paralelo sin afectar el código principal.

git switch
Permite cambiar de una rama a otra de forma sencilla. También puede utilizarse para crear una nueva rama mediante la opción -c.

git checkout
Permite cambiar entre ramas o restaurar archivos. En versiones recientes de Git, parte de sus funciones fueron separadas en los comandos git switch y git restore.

git pull
Obtiene los cambios desde un repositorio remoto y los integra en la rama local actual.

git push
Envía los commits realizados localmente hacia el repositorio remoto.

git merge
Permite combinar los cambios de una rama con otra. Es una de las formas más utilizadas para integrar el trabajo realizado por distintos integrantes de un equipo. Cuando existen cambios incompatibles entre ramas, Git puede generar conflictos que deben resolverse manualmente antes de completar la integración.