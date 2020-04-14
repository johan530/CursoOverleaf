# Procedimiento para subir el deber
1. Crear/Acceder cuenta de Github
2. Hacer un Fork al repositorio OverleafLatex
3. Descargar el proyecto Estudiante/CursoOverleaf
```
git clone https://github.com/LeninGF/CursoOverleaf.git

```
4. Crear una rama con su nombre abreviado
```
git checkout -b NombreEstudiante

```
4. En la carpeta deber, colocar la carpeta con los archivos del proyecto latex
```
git status
git add deber/archivo.tex
git add deber/referencias.bib
git commit -m "archivos modificados por "
git push origin NombreEstudiante
```
5. Todos sus cambios les ejecuta push en su rama, no en la rama master.
6. Genera un **Pull Request** al dueño del repositorio. 
