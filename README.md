Bitácora del Examen Parcial 1
# Punto 1
a)
Creacion de una carpeta en Desktop
con el nombre examen-parcial-1
Se crea el repositorio local (git init)
b)
Se agregan 4 archivos .py en la carpeta
c)
Se usa el comando (git status) para ver es estado de los archivos
Se usa (git add *.py) para subir todos los .py
Se usa (git commit -m "Notas")

# Punto 2
a)
Se inicia sesion en Github y se crea el repositorio examen-parcial-1
b)
Se creo el repositorio sin README
c)
Se copia el url del repositorio
(https://github.com/ChristopherArgenis/examen-parcial-1)

# Punto 3
a)
Se sube el repositorio local con los comandos:
(git remote add origin https://github.com/ChristopherArgenis/examen-parcial-1.git)
(git branch -M main)
(git push -u origin main)
Despues de este comando se inicia sesion (Se hizo con exito)
b)
Se crea un README.md de forma manual en Github

# Punto 4
a) Para recuperar el README.md se usaron los comandos:
(git branch) Para asegurarme de estar en la rama main
(git pull origin main)

# Punto 5  
a) 
Se modificaron 2 archivos de la carpeta
b)
Se agrego en README.md las instrucciones hasta el momento
c)
Se guardaron en el repositorio, se hizo el respectivo commit.
(git commit -a -m "Se suben los cambios de los prints y README.md")
Y se mandaron a remoto -> Github con el comando:
(git push origin main)

# Punto 6
a) 
En Github se modificaron los archivos print3 y print4
b)
Se agrego al README.md los instrucciones hasta el momento

# Punto 7
a)
Con crea una rama nueva llamada "rama-1" con el comando:
(git branch rama-1)
b)
Me muevo a la rama "rama-1" con el comando:
(git checkout rama-1)
y se crean 2 nuevos archivos.
c)
Se agregaron los nuevos archivos con el comando:
(git add *.py)
d)
Se hacen commit a los nuevos archivos con el comando:
(git commit -m "2 Nuevos archivos creado")
Y se mandan al Github con el comando:
(git push origin rama-1)
e)
Regresando a la rama main con el comando:
(git checkout main)
Se fusiona con el main lo de la rama-1 con el comando:
(git merge rama-1)
f)
Se hizo con exito la fusion.
g)
El README.md tiene todas las instrucciones realizadas
Se sube al repositorio local con el comando:
(git commit -a -m "Se finalizada el README.md")
Se subieron todos los cambios al repositorio de Github con el comando:
(git push origin main)