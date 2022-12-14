# clase 02

## Estado de los Archivos

* untracked

* unmodified

* modified

* staged

## git log
Me muestra las fotos que les fui sacando al proyecto
```
git log 
```
* Version corta
```
git log --oneline
```
## git diff
Me permite visualizar los cambios entre el working directory y la ultima  foto(commit).
```
git diff
```
## git ammend
me permite agregar cambios al ultimo commit, se trata de emmendar un error, solo funciona en el ultimo commit
* Primero se debe ejecutar el git add
* Hacer el commit
* Despues se abre un editor de texto(nano), donde debemos guardar los cambios y luego salir.

```
git --ammend
```