# Modulos
## Crear archivos .ko
$ make
## Modulo Ram 
## Cargar Modulo memoria
$ insmod mem_grupo1.ko
## Ver mensajes del Modulo
$ dmesg
## Ver datos 
$ cat /proc/grupo1_ram

#Instar NodeJs y Express
	https://www.youtube.com/watch?v=VHOd-RBj1MA&list=PLvimn1Ins-41lVr-SPWF1mdNTzog05TcA

# Instalar  express-generator
	npm install express-generator -g

# Crear proyecto
	express --view=hbs app
	cd app 
	npm install
	## Si da este error
		"npm notice created a lockfile as package-lock.json. You should commit this file.
		added 64 packages from 78 contributors and audited 151 packages in 19.859s
		found 5 vulnerabilities (1 low, 1 moderate, 3 high)
		 run `npm audit fix` to fix them, or `npm audit` for details"
		##Ejecutar
		npm audit fix 
	## Run proyect (localhost:3000)
		set DEBUG=app:* ; npm start
