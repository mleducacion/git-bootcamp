# Clase 05 - Git 

## Para crear un repositorio de GIT

```sh
git init
```

## Ver en que estado están los archivos y en que área

```sh
git status
```

## Áreas del repositorio de GIT

3 Áreas

* Working Directory (WD): Directorio de trabajo donde se van agregando o quitando los archivos durante el desarrollo
* Staging Area (SA): (Área de control de cambios. Área temporal/intermedia)
* Local Repo (LR): (Una caja donde voy a ir teniendo todas las fotos que vaya sacando)

## Estados de los archivos

* untracked: (Archivos que están en el WD pero GIT no les esta dando seguimiento)
* unmodified: (Archivos que GIT ya esta siguiendo y con respecto al WD, no fueron modificados)
* modified: Archivos que se encuentran en el repositorio (Están siendo seguidos por GIT) pero difieren con lo que se encuentra actualmente en el WD
* staged: Archivos que están en el area temporal/intermedia

# Agrego al área de confirmación el archivo/archivos 

```sh
git add <nombre-archivo>
git add <nombre-archivo> <nombre-archivo> <nombre-archivo>
git add . # Agrega todos los archivos.
```

# Persistimos los cambios agregados al área de confirmación en un commit

```sh
git commit -m "mensaje descriptivo de lo que tiene el commit"
``` 

# Corregir el mensaje del commit

```sh
git commit --amend -m "el mensaje corregido"
```

# Como el timeline de commits

```sh
git log # versión larga
git log --oneline # versión corta
```


