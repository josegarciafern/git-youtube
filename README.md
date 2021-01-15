# Comandos útiles de Git

1. git init
2. git add . : Toma todos los archivos y los prepara para una fotografía, pasan al stage
3. git reset . : Da marcha atrás al git add . , elimina los ficheros del Stage
4. git commit -m "Mensaje": Crea la foto de los ficheros del stage
5. git checkout -- . Regresa al último commit
6. git log : Muestra la información de los commit
7. git commit --amend : Modifica el último commit. Tecla i para insertar y para salir esc :wq!
8. git checkout -b <nombreRama> : Crea una rama
9. git branch : Muestra las ramas y en la cual estoy posicionado
10. git checkout master : Se posiciona en la rama master
11. git branch -d <nombreRama> : Borra la rama
12. git push : Despliegue en el recurso remoto