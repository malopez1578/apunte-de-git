## curso git desde 0

Sistema de contro de versiones para el mantenimiento eficiente y confiable de archivos

###Zonas de Git
1. Directorio de trabajo
2. Area de preparación
3. Directorio Git

### Flujo de trabajo
1. Modificas una serie de archivos en tu directorio de trabajo.
2. Preparas los archivos, añadiendolos a tu area de preparación.
3. Confirmas los cambios, lo que toma los archivos tal y como estan en el area de preparacion y almacena esa copia instantanea de manera permanente en tu ditectorio Git

### Configurando Git por primera vez
 ```
 git config --global user.name "Miguel Lopez"
 git config --global user.email malopez1578@gmail.com
 git config --global core.editor code
 git config --list
```
### comandos CMD
cd desktop\curso git
cd desktop\curso git> code .

### primeros paso

git initial = inicia el repositorio
git status = revisa el estado del repositorio
git add <"file"> agrega archivos al repositorio
git commit -m "mensaje descripcion cambios" = guarda los archivos en el repositorio
git status diff = muestra la diferencia entre archivos a cargar
git statur diff -staff= diferencia entre dos archivos pendientes a cargar con el mismo nombre
git add .=agrega todos los archivos
git reset HEAD <"file">= saca los archivos de la zona de preparación
.gitignore = Patrones de nombres de archivos que Git ignorara
git commit -a -m= saltar la zona de preparacion
git rm =elimina archivos rastreados del repositorio y de nuestro directorio de trabajo
git checkout --<"file">= recuperar archivos borrados
git mv file_from file:to= renombra un archivo
 
 ### nos muestra el historia de commits
 
git log --oneline = nos muestra el historial en una solo linea
git log --graph = muestra las ramificaciones del historial
git log --pretty=format = nos asigna el formato que indiquemos
git log after = "aaaa/mm/dd/ hh:mm:ss"
git log before = "aaaa/mm/dd/ hh:mm:ss" nos muestra el historial en el tiempo que nosotros le indiquemos

### comandos para deshacer

git commit --amend = abre la configuracion del mensaje del ultimo commit

git reset HEAD <"file"> = deshace la preparacion
git chackout -- <"file"> = deshace los cambios hechos y avanza en el tiempo

### etiquetas

git tag = listar las etiquetas que existen

### etiquetas ligeras
git tag mi etiqueta = crea una etiqueta al ultimo commit

### etiquetas anotadas
git tag -a v1.0 -m "my version 1.0" 
git show = para ver las etiquetas y cambios echos en el commit

### filtrar etiquetas

git tag -l "v1*" = filtra las etiquetas de acuerdo a las referencias

<<<<<<< HEAD
### crear nuevas ramas

git branch crea eamas en el commit ubicado

### fusiones

git merge otra_rama = incorpora otra_rama en la actual

git branch -d nombreRama = elimina las ramas que ya han sido fusiinadas

git branch -D nomnreRama = se fuerza el borrado, se pierden los cambios

git tag -d etiquetaNombre = elimina la etiqueta seleccionada

### git remote

vinculamos nuestro repositorio con gibhub

git branch --no-merged = nos muestra cuales ramas no han sido fusionadas

git branch --merged = nos muestra las rams que han sido fusionadas a la rama actual

=======
### Ramas

git branch = crea nuevas ramas
se pasa a las ramas con checkout
git chackout -b crar y saltar a la nueva rama
>>>>>>> testing


