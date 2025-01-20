## Parte 1:

**git add:** Este comando se utiliza para añadir cambios en el directorio de trabajo al área de preparación (staging area). Básicamente, se marcan los archivos que se quieren incluir en la próxima confirmación (commit). Por ejemplo: *git add nombre_del_archivo*.
Si se quiere añadir todos los cambios en el directorio de trabajo, se puede usar: *git add .*

**git commit -m "mensaje":** Una vez se han añadido los cambios al área de preparación, se utiliza este comando para confirmar esos cambios y guardarlos en el historial del repositorio. El *-m "mensaje"* permite añadir un mensaje descriptivo que explica qué cambios se han realizado. Por ejemplo: *git commit -m "Agregué nueva funcionalidad para el formulario de contacto"*.

**Creación del repositorio:** Los comandos usados para este proceso fueron:
- git init, git add .
- git commit -m "Creé el README como se pide en la primera parte"
- git push --set-upstream https://github.com/sebRedi/CVDS_lab01 master
- Por último, se abrió una interfaz para iniciar sesión.

Para finalizar esta primera parte, haremos un último commit con el mensaje "Finalización de la parte 1".