# campusciff - Luis Manuel Muñoz Merino



Ejercicios 01


2.1 Creamos el repositorio campusciff en GitHub
![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/1.png)

2.2 Clonamos nuestro repositorio en local con el comando: 
git clone https://github.com/luismamm/campusciff.git
![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/2.png)

2.3 Al crear el repositorio marcamos crear README.md

2.4 Hacemos commit en el README.md, para ello utilizamos los comandos:
git add . --a , git commit -m "commit inicial"
![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/3.png)
![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/4.png)

2.5 Subimos los cambios hechos al repositorio remoto con el comando:
git push
![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/5.png)

2.6 Creamos en el repositorio local el fichero 'privado.txt' y la carpeta
'privada'
![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/6.png)

2.7 Creamos el archivo .gitignore y dentro de este archivo escribimos:
privada
privado.txt
A continuación utilizamos los comandos: git add . --a , 
git commit -m "archivos ignorados"

![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/7.png)
![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/8.png)
![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/9.png)

2.8 Creamos un fichero '1.txt' y usamos los comandos:
git add . --a , git commit -m "fichero 1.txt añadido"
![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/10.png)
![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/11.png)
![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/12.png)

2.9 Creamos una etiqueta 'v0.1' con el comando: git tag v0.1
![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/13.png)

2.10 Subimos la etiqueta con el comando: git push --tags

![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/14.png)



Ejercicios 02


2.2 Creamos una rama 'v0.2' con el comando: git branch v0.2
Y posicionamos la carpeta de trabajo en la rama creada con el comando:
git checkout v0.2

![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/15.png)
![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/16.png)

2.3 Creamos un fichero '2.txt' en la rama v0.2 y usamos los comandos:
git add . --a , git commit -m "fichero 2.txt añadido"
![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/17.png)
![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/18.png)
![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/19.png)

2.4 Subimos los cambios al repositorio remoto con el comando:
git push --set-upstream origin v0.2
![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/20.png)

2.5 Nos posicionamos en la rama master con el comando: git checkout master
A continuación fusionamos la rama v0.2 en la rama master con el comando:
git merge v0.2 -m "merge v0.2 a master"

![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/21.png)
![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/22.png)

2.6 Estando ya en la rama master, ponemos Hola en el fichero 1.txt.
A continuación utilizamos los comandos: git add . --a , 
git commit -m "mensaje añadido en 1.txt"

![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/23.png)
![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/24.png)
![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/25.png)

2.7 Nos posicionamos en la rama v0.2 con el comando: git checkout v0.2
Ahora ponemos Adios en el fichero '1.txt' y ponemos los siguientes
comandos: git add . --a , git commit -m "mensaje añadido en 1.txt"

![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/26.png)
![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/27.png)
![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/28.png)

2.8 Nos posicionamos ahora en la rama master y hacemos un merge con 
la rama v0.2. Ponemos los comandos: git checkout master , 
git merge v0.2 "merge de v0.2 en master"

![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/29.png)
![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/30.png)

2.9 Listamos las ramas segun el estado con merge y sin merge 
utilizando los siguientes comandos: git branch --merged , 
git branch --no-merged

![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/31.png)
![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/32.png)

2.10 Arreglamos el conflicto haciendo merge.

2.11 Creamos una etiqueta 'v0.2' con el comando: git tag v0.2
Y borramos la rama 'v0.2' con el comando: git branch -d v0.2

![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/33.png)
![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/34.png)

2.12 Listamos los commits de las ramas y los tags con el comando: git log

![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/36.png)

2.13 Creamos una organización llamada: 'campusciff-luismamm'.

![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/37.png)

2.14 Dentro de la organización creada creamos dos teams uno de 
administradores y otro de colaboradores, y metemos en cada uno a dos
de nuestros compañeros.

![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/38.png)
![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/39.png)
![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/40.png)
![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/41.png)

2.15 Creamos un index.html para que la organización lo vea.

![alt text](https://github.com/luismamm/campusciff/blob/master/capturas/42.png)

