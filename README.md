# campusciff
Clonamos el repositorio
git clone https://github.com/miguelj93/campusciff.git

Vamos a proceder a hacer el primer commit
git add .
git commit -m "commit inicial"

A continuacion subimos los cambios al repositorio remoto
git push origin master

Creamos el archivo privado.txt y la carpeta privada
touch privado.txt
mkdir privada

para ignorar el archivo y la carpeta que hemos creado, usamos nano y 
escribimos el nombre tanto del archivo como de la carpeta en .gitignore
nano .gitignore

Creamos el fichero1.txt y hacemos commit
touch fichero1.txt
git add .
git commit -m "fichero1 añadido"

Creación del tag v0.1
git tag v0.1

Subida del tag
git push --tag origin master

Crear tabla

NOMBRE				GITHUB
-------------------------------------------------------------
Rafa		https://github.com/RuFFuS4/campusciff.git
-------------------------------------------------------------
Miriam		https://github.com/MIRIAM-GIT/campusciff.git
-------------------------------------------------------------
