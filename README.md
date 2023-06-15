# ifix-desarrollo-web

1 - git init ¡En la ruta de mi proyecto, donde tengo el index!
(borrar repositorio inicializado: rm -fr .git)

2 - revisar que la rama sea main. Si no lo es, la cambio con: git branch -M main
(setear main por default: git config --global init.defaultBranch main)

3 - git add . Muevo los cambios al staging area

4 - git commit -m "Primer commit" Muevo los cambios al repository

5 - Vinculo el repo remoto:
5.1 git remote add origin https://github.com/Joaquinviretti/ifix-desarrollo-web.git
5.2 git branch -M main
5.3 git push -u origin main
