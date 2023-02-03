# Primer día con Git y Github

Comandos de linux utiles
```ksh
ls -la => lista todos los archivos
pwd => muestra la ruta del directorio


Lista de comandos de git

* Para poder ver la version de git
* ejecutamos en nuestra terminal: 


```bash
git --version
git -v
```

* Para configurar el correo y  nombre (sólo la 1era vez en mi maquina)


```bash
git config --global user.email. "micorreo@gmail.com"
git config --global user.name "Mi nombre"
```

* Para ver la configuracion de git
```bash
git config -l
git config --list
```
* Para inicializar el repositorio
```bash
git init
```

* Comandos de git
```git
git status => ver el estado del 
git add . => agregar todos los archivos al stage(prepararlos para el commit)
```

* Crear el registr de los cambios realizados
```bash
git commit -m "feat:name_branch : describe change"
```

* Ver el historial de cambio
```bash
git log
```

* Para poder ver el detalle de un commit especifico usamos
```bash
git show id-de-commit
```


* Para modificar una rama local
```bash
git branch -M main
```
