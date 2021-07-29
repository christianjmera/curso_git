# Curso GIT
## Christian Zuñiga

<img src="https://prep.soyhenry.com/00-PrimerosPasos/img/github_PNG15.png"
 width="500"
 heigth="">

### Configure Git for the first time
```bash
git config --global user.name "Christian Javier Zuñiga Mera"
git config --global user.email "email@email.com.co"

```
### My code is ready to be pushed
```bash
git init
git add --all
git commit -m "Initial Commit"
git push -u origin HEAD:master

```

### Comandos GIT
```bash

1. git clean = Es un método útil para eliminar los archivos sin seguimiento
   en un directorio de trabajo del repositorio.

2. git reset = Se utiliza sobre todo para deshacer los cambios del índice del
   entorno de ensayo.

3. git revert = Sirve para deshacer cambios efectuados en el historial de 
   confirmaciones de un repositorio.

4. git mv = Renombrar un archivo

```

## BRANCH - MERGE
``` bash

1. git branch = Te permite crear, renombrar y eliminar ramas, así como cambiar su nombre. 

2. git checkout = Te permite desplazarte entre las ramas creadas por git branch.

3. git merge = Permite tomar las líneas independientes de desarrollo creadas 
   por git branch e integrarlas en una sola rama.

4. git stash = Almacena temporalmente o guarda en un stash los cambios que hayas 
   efectuado en el código en el que estás trabajando para que puedas trabajar en 
   otra cosa y, más tarde, regresar y volver a aplicar los cambios más tarde.

5. git tag = Sencillamente es una cadena arbitraria que apunta a un commit específico. 
   Puede decirse que un tag es un nombre que puedes usar para marcar un punto 
   específico en la historia de un repositorio.

```

## ACTUALIZAR PROYECTOS
```bash

1. git clone = Para obtener una copia de un repositorio Git existente.

2. fit fetch = Un comando principal que se usa para descargar contenidos desde un
    repositorio remoto

3. git pull = Se emplea para extraer y descargar contenido desde un repositorio remoto 
    y actualizar al instante el repositorio local para reflejar ese contenido.

```

## COMPARACION
``` bash

1. git show = Puede mostrar un objeto Git de una manera simple y legible por humanos. 
    Normalmente se usaría esto para mostrar la información sobre una etiqueta o un commit.

2. git diff = Es un comando multiusos de Git que, cuando se ejecuta, lleva a cabo una 
    función para establecer las diferencias en los orígenes de datos de Git.Dichos orígenes
    de datos pueden ser confirmaciones, ramas y archivos, entre otras posibilidades.

3. git shortlog = se utiliza para resumir la salida de git log . Toma muchas de las 
    mismas opciones que el comando git log pero, en lugar de enumerar todos las commits, 
    presentará un resumen de los commits agrupados por autor.

```

## METODO DE REPARACION AVANZADA
``` bash

1. git cherry-pick = es un potente comando que permite que las confirmaciones arbitrarias 
   de Git se elijan por referencia y se añadan al actual HEAD de trabajo. La ejecución 
   de cherry-pick es el acto de elegir una confirmación de una rama y aplicarla a otra.

2. git rebase =La fusión mediante cambio de base es una de las dos utilidades de Git 
   que se especializa en integrar cambios de una rama a otra. 

```

## COMANDO EXTRA DE GIT
``` bash

1. git blame = El comando git blame sirve para examinar el contenido de un archivo
   línea a línea y ver cuándo se ha modificado cada línea y quién es el autor de 
   las modificaciones.

2. git grep = Se envía con un comando llamado grep que le permite buscar fácilmente
   a través de cualquier árbol o directorio de trabajo con commit por una cadena o 
   expresión regular.

3. .gitignore = es un archivo de texto que le dice a Git qué archivos o carpetas 
   ignorar en un proyecto.

4. git alias = Sirve para crear un comando en GIT 
   "git config --global alias.nom_comando 'accion comando'" 


```