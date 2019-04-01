#Comandos 

#Version 
git --version

#Ayuda
git --help

#Configuración
git config --global "user.name"
git config --global "user.email"

#creación del repositorio
git init

#estatus del repositorio
git status

#Agregar archivos 
git add -A

#Para registrar los cambios
git commit -m "comentario descriptivo" 

#Ver hitorial de commit
git log

##Ver historial 2
git log --oneline --decorate --all --graph

##Agregar archivos especificos
git add "extension del archivo"

##Alias a los comandos 
git config --global alias.alias "comando"

##Regresar a un commit anterior
git reset --hard "id del commit"

##Crear una nueva rama 
git branch "nombre de la rama"

##Cambiar a otra rama
git checkout "nombre de la rama"

##Unir ramas 
git merge "nombre de la rama"

##Eliminar archivo 
git rm "nombre del archivo"

##Tag
Son una refereancia a un commit especifico 

##Creacion de un tag
git tag "Nombre del tag"
