# campusciff
# ACTIVIDAD GITHUB
## 2.1 REPOSITORIO CAMPUSCIFF
![img](http://imgfz.com/i/zExgPYt.png)

## 2.2 REPOSITORIO CAMPUSCIFF(II)
Clonamos el repositorio

![img](http://imgfz.com/i/y5npfcH.png)

	git clone https://github.com/miguelj93/campusciff.git

## 2.4 COMMIT INICIAL
Añadir al README.md los comandos utilizados hasta ahora y hacer un commit inicial con el 
mensaje commit inicial

![img](http://imgfz.com/i/4CjNcTR.png)

	git add .
	git commit -m "commit inicial"

## 2.5 PUSH INICIAL
Subir los cambios al repositorio remoto

![img](http://imgfz.com/i/pMARSjb.png)

	git push origin master
    
## 2.6 IGNORAR ARCHIVOS(I)
Crear en el repositorio local un fichero llamado privado.txt y una carpeta llamada 
privada

![img](http://imgfz.com/i/l90vkB7.png)

	touch privado.txt
	mkdir privada

## 2.7 IGNORAR ARCHIVOS(II)
para ignorar el archivo y la carpeta que hemos creado, usamos nano y
escribimos el nombre tanto del archivo como de la carpeta en .gitignore

![img](http://imgfz.com/i/IxgZQ0M.png)

	nano .gitignore
    
## 2.8 AÑADIR FICHERO1.TXT
![img](http://imgfz.com/i/UOHEiGJ.png)

Creamos el fichero1.txt y hacemos commit

	touch fichero1.txt
	git add .
	git commit -m "fichero1 añadido"

## 2.9 Creación del tag v0.1
![img](http://imgfz.com/i/oJqwAlm.png)

	git tag v0.1

## 2.10 Subida del tag
![img](http://imgfz.com/i/bdYH0Rq.png)

	git push --tag origin master
    
## 2.12 USO SOCIAL DE GITHUB
Seguir a compañeros de clase:

![img](http://imgfz.com/i/1x4wSjE.png)

Seguir repositorios de compañeros:

![img](http://imgfz.com/i/VqFlXk0.png)

Añadir una estrella a los repositorios del resto de compañeros:

![img](http://imgfz.com/i/9knUmd6.png)



## Crear tabla
| NOMBRE | GITHUB |
| -- | -- |
| Miriam | https://github.com/MIRIAM-GIT/campusciff.git |
| Rafa | https://github.com/RuFFuS4/campusciff.git |

## 2.14 COLABORADORES
![img](http://imgfz.com/i/9tfkrUn.png)


# Actividad avanzada

## 2.2 Creamos una rama v0.2
![img](http://imgfz.com/i/iUm1ROV.png)

	git branch v0.2

Posicionamos la carpeta de trabajo en esa rama
![img](http://imgfz.com/i/4QzlLy1.png)

	git checkout v0.2

## 2.3 Añadir fichero2.txt
![img](http://imgfz.com/i/0vYOJjA.png)

touch fihcero2.txt

## 2.4 Crear una rama remota v0.2
Subimos los cambios al repositorio remoto

![img](http://imgfz.com/i/wAGcYWt.png)

	git add .
	git commit -m "fichero2.txt añadido"
	git push origin v0.2

## 2.5 Merge directo
Nos posicionamos en la rama master

![img](https://i.imgur.com/roJxVuI.png)

	git checkout master
    
hacer una merge de la rama v0.2 en la rama master

![img](https://i.imgur.com/4wY8pKB.png)

	git merge v0.2 -m "merge de la rama v0.2 en la rama master"

## 2.6 Merge con conflicto(I)
En la rama master poner hola en el fichero1.txt y hacer commit
![img](https://i.imgur.com/NAMs0sg.png)

	nano fichero1.txt
	git add .
	git commit -m "modificado fichero1.txt"

## 2.7 Merge con conflicto(II)
posicionarse en la rama v0.2 y poner adios en el fichero1.txt y hacer commit
![img](https://i.imgur.com/edWkDUU.png)

	git checkout v0.2
	nano fichero1.txt
	git add .
	git commit -m "modificado fichero1.txt v0.2"


## 2.8 Merge con conflicto(III)
posicionarse de nuevo en la rama master y hacer un merge con la rama v0.2
![img](https://i.imgur.com/IiLsphE.png)

![img](https://i.imgur.com/luJj5Yo.png)

	git checkout master
	git merge v0.2
	git add .
	git commit -m "conflicto"

## 2.9 Listado de Ramas
Listar las ramas con merge y las ramas sin merge
![img](https://i.imgur.com/kOIVaWx.png)

	git branch --merge
	git branch --no-merge

## 2.10 Arreglar conflicto
Arreglar el conflicto anterior y hacer un commit
![img](https://i.imgur.com/L1FPWQs.png)

	nano fichero1.txt
	git add .
	git commit -m "arreglar conflicto anterior"

## 2.11 Borrar rama

![img](https://i.imgur.com/qfK27EL.png)

crear un tag v0.2

	git tag v0.2
    
Borrar la rama v0.2    

	git branch -d v0.2
    
## 2.13 CREAR UNA ORGANIZACIÓN
![img](https://i.imgur.com/pLS0OSY.png)



