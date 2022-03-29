
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
> git los historia.txt

`9. Muestra los cambios que ha tenido un archivo`
> git show




-----------



`Otros: Despues de hacer cambios, ejecutar estos comandos`



> git status

> git add .

> git commit -m "Mensaje a Escribir"

> git push -u origin master


