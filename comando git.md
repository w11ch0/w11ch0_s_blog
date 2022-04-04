
# Comandos de Git

`CONFIGURAR QUIEN SOY YO A GIT`
> git config

> git config --global user.name "Mauricio Montes"

> git config --global user.email "jmauricio.montes@gmail.com"


`Configuración por defecto de Git`
> git config --list

> git config --list --show-origin

`1. Crear Carpeta e Inicializar el repositorio`
> git init

`2. Para saber el estado del proyecto en ese momento`
> git status

`3. Agregar archivos al proyecto  `
> git add hostoria.txt

> git add .

`4. sacar archivo del rom`
> git rm historia.txt

`5. eliminar archivo del STAGED`
> git rm --cached historia.txt


`6. Vuelve al punto 3`


`7. Mandar los archivos al repositorio`
> git commit -m "Mensaje a Escribir"


`8. Log de Historial`
> git log historia.txt

`9. Muestra los cambios que ha tenido un archivo`
> git show

`10. Ver diferencias entre un cambio y otro cambio del archivo`
> git diff 0dd31cd452d7e65a6aa90609ed74f034dd625b1c 2edc9e1012f27b83ebe74133b2f4e8419c2eb5b3

`10. Volver a una version específica`
> git reset 0dd31cd452d7e65a6aa90609ed74f034dd625b1c --soft

`11. Borrar Todo vuelve `
> git reset 0dd31cd452d7e65a6aa90609ed74f034dd625b1c --hard

`12. Verificar como era cierto archivo`
> git checkout 0dd31cd452d7e65a6aa90609ed74f034dd625b1c historia.txt

`13. actualiza archivos modificados previamente ya que se ha realizado commit`
> git commit -am "mensaje...."

`14. Nombrar a una rama`
> git branch NombreDeRama

`15. Cambiarse a una rama`
> git checkout NombreDeRama

`16. Fusionando las ramas`
> git merge cabecera 

`17. Si no se sabe la rama`
> git branch



`esto volvera a un archivo a su estado solicitado, por lo tanto verificamos...`
> git status 

`volvemos a llamar la rama que queremos del archivo y volveremos a verlo tal cual la ultima modificacion`
> git master historia.txt









-----------



`Otros: Despues de hacer cambios, ejecutar estos comandos`



> git status

> git add .

> git commit -m "Mensaje a Escribir"

> git push -u origin master


