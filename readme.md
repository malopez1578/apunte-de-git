## curso git desde 0

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

git initial = inicia el repositorio
git status = revisa el estado del repositorio
git add <"file"> agrega archivos al repositorio
git commit -m "mensaje descripcion cambios" = guarda los archivos en el repositorio
git status diff = muestra la diferencia entre archivos a cargar
git statur diff -staff= diferencia entre dos archivos pendientes a cargar con el mismo nombre
