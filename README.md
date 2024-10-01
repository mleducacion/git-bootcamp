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

