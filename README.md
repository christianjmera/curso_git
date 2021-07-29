# Curso GIT
## Christian Zuñiga

<img src="https://prep.soyhenry.com/00-PrimerosPasos/img/github_PNG15.png"
 width="500"
 heigth="">

### Configure Git for the first time

```bash
git config --global user.name "Christian Javier Zuñiga Mera"
git config --global user.email "christian.zuniga@codesa.com.co"

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

1. git clean = Es un método útil para eliminar los archivos sin seguimiento en un directorio de trabajo del repositorio.

2. git reset = Se utiliza sobre todo para deshacer los cambios del índice del entorno de ensayo.

3. git revert = Sirve para deshacer cambios efectuados en el historial de confirmaciones de un repositorio.

4. git mv = Renombrar un archivo

5. git branch = Te permite crear, renombrar y eliminar ramas, así como cambiar su nombre. 

6. git checkout = Te permite desplazarte entre las ramas creadas por git branch.

7. git merge = Permite tomar las líneas independientes de desarrollo creadas por git branch e integrarlas en una sola rama.

8. git stash = Almacena temporalmente o guarda en un stash los cambios que hayas efectuado en el código en el que estás trabajando para que puedas trabajar en otra cosa y, más tarde, regresar y volver a aplicar los cambios más tarde.

9. git tag = Sencillamente es una cadena arbitraria que apunta a un commit específico. Puede decirse que un tag es un nombre que puedes usar para marcar un punto específico en la historia de un repositorio.

```