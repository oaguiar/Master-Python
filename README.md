# Master-Python
Create a new repository on the command line

echo "# Master-Python" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/oaguiar/Master-Python.git
git push -u origin main

Push an existing repository from the command line

git remote add origin https://github.com/oaguiar/Master-Python.git
git branch -M main
git push -u origin main

Verificar Cambios
git status

Agregar archivos

Para agregar todos los cambios:

git add .

Si solo quieres agregar un archivo específico:

git add nombre_del_archivo

Hacer un commit con los cambios

git commit -m "Actualización del código y corrección de errores"

Subir los cambios a GitHub

git push origin main