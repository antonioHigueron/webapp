# crearRepositorioGitLocal

Crear repositorio desde la cmd, previamente debe estar creado en github.com, gitlab.... para poder enlazarlo y trabajar con él. (main es el nombre de la rama)

echo "# nombreRepositorio" >> README.md

git init

git add README.md

git commit -m "comentario del commit"

git branch -M main

git remote add origin https://github.com/antonioHigueron/crearRepositorioGitLocal.git

git push -u origin main

--------------------------------
También se puede subir el proyecto en local a un repositorio existente, asi:

git remote add origin https://github.com/antonioHigueron/crearRepositorioGitLocal.git

git branch -M main

git push -u origin main

comentario adicional
