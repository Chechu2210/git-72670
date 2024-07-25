## Clase 02 - Git Desarrollo Colaborativo

![alt text](image.png)

## Repaso de comandos para persistir los cambios de archivos dentro del repositorio


```sh
git status
```
```sh
git status --short
```

* ?? significa que esta untracked
```sh
??  clase02/README.md
```

* A significa Staging Area
```sh
A  clase02/README.md
```

## Sacar archivos de staging Area
```sh
git restore --staged 
```

## Agregar de staging Area
```sh
git add .
```
```sh
git add <nombre del archivo>>
```

## Pasar a Local Repository - persistir los cambios. Usar un nombre referencial que me ayude con el contenido

```sh
git commit -m "commit_Name"
```

## Corrección en un Commit.(tanto mensaje como contenido)
```sh
git commit --amend -m "Nombre del commit"
```

## Ver cambios
```sh
git diff
```

## Visualizar instantaneas de los commits
```sh
git log #versión larga
git log --oneline #versión corta
git log --oneline -2 #ver una cantidad limitada de commits

```

## Salir de GIT LESS

```sh
q
```
## Separar un commit
```sh
git add --patch
```
