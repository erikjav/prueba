USAR LA RED DEL MOVIL O DE TU CASA, NO USAR LA RED CORPORATIVO
1- Clonar el repositorio

2- Crear otro rama = git branch nuevaRama

3-Moverse a esa rama y verificar que estamos en otra rama = git checkout nuevaRama

4 - Hacer los cambios que tu veas

5 - git add .

6 - git commit -m "MensajeDescriptivo"

7- Antes de PUSH, siempre actualizar la rama principal: git pull origin master

8 - git push origin nuevaRama

9 - Crear el pull request en github

10- Esperar la aprobacion del admin para aprobar el pull request

11-Moverte a la rama master: git checkout master

12-Fusionar las ramas/se refiere a que sumas los cambios de la rama que ya esta subida,
con la que fusionas: git merge nuevaRama
git pull origin master

	13- Si surgen conflictos, abrir los archivos 
	14- git add .
	15- git commit -m
 
16- git push origin master = para confirmar los cambios.

17-cuando ya esta fusionada las ramas/la rama principal, se puede eliminar la rama desfasada
git branch -D nuevaRama

