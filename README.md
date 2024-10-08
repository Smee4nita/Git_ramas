# GIT RAMAS (BRANCHES)

## Crear un repositorio
'''
    sh
git init
'''

## Ver el status de los archivos
'''
    sh
git status
'''

## Alias... (formas cortas de ejectar un comando de git)
git config --global alias.st "status --short"

## Ver las diferencias enre el WD y el LR
'''
    sh
git diff
'''

## Ver el contenido de cada commit
'''
    sh
git show <numero-hash>
'''

## Crear una RAMA
'''
    sh
git branch <nombre-rama> # crea una rama y nos deja en la rama actual
git switch feature/ramas # ejemplo
git swith -c <nombre-rama> # crea una rama y nos mueve a la rama que se creo

## Me muevo entre RAMAS

'''
    sh
git switch <nombre-rama>
git switch feature/ramas # ejemplo
'''

