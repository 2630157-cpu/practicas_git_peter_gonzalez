# Peter Dali González Gaytan 

## *Matricula*:2630157

### Creación y sincronización de repositorios con Git y GitHub

###OBJETIVO

Crear un repositorio local utilizando Git, sincronizarlo con un repositorio remoto en GitHub y comprobar el flujo de trabajo en ambos sentidos:
lo que hicimos en este ejercicio fue crear una carpeta desde cero y metewr le un archivo de texto llamado datos.txt y un archivo markdown, con el objetivo de poder sincronizar github con el repositorio local 

### Comandos de Git utilizados:

* git init

* git branch -M main

* git status

* git add .

* git commit -m "Primer commit"

* git remote add origin URL_DEL_REPOSITORIO

* git remote -v

* git push -u origin main

* git pull origin main

  *git init* sirve para inicializar el repositorio de git
  *git branch -M main* es para configurar la rama principal donde se van a subir nnuestros commits
  *git status* es para ver en que zona están nuestros archivos o documentos
  *git add .* es para pasar nuestros archivos de la zona de untracked files zone
  *git commit -m "primer commit* sirve para pasar nuestros archivos o docs de la zona de staiging y convertirlos en commits
  *git remote add origin URL_DEL_REPOSITORIO* es para poder vincular nuestro repositorio local con un repositorio en github
  *git remove -v* para verificar que el anterior comando si funciono
  *git push  -u origin main* para enviar nuestro repositorio local a github
  *git pull origin main* para descargar los cambios realizados en github

  ### Explicación de como se creo el repositorio local

  yo desde power shell me meti a desktop puse mkdir practicas_git_peter_gonzales luego presione enter, despues cd . y escogi la carpeta que cree e
  despues puse git init despues git branch -M main despues en archivo cree los dos archivos que me pedian y despues los meti a la carpeta luego
  en power shell puse git status después git add . para pasar los archivos a la staiging zone y después puse el comando git commit -m "primer commit"
  para que los archivos se volvieran commits.

  ### Explicación de la sincronizacion

  para la sincronizaciopn batalle bastante primero debemos tener los commits despues en github abrir un repositorio publico
  sin licencia datos.txt y README.md despues de crearlo copeamos el url y en power shell ponemos este comando git remote add origin URL_DEL_REPOSITORIO
  despues ponemos git remove -v para checar que todo haya salido bien, volvemos al repositorio de gthub para ver los camobios ya que sincronizamos las
  dos cuentas.

  ###Explicacion de gthub a local

  en GitHub solo modificamos archivo guardamos nos pasamos a power shell y ponemos el comando git pull origin main para descargar todo los
  cambios hechos en GitHUB

  ### Descripción de los archivos contenidos en el repositorio

  *Datos.txt*: Es un archivo de texto que contiene frases claves donde hice los cambios de repositorio local a GitHub y vicervesa
  *README.md*: Es un archivo en formato markdown que contiene toda las especificaciones que me pidieron en la tarea

   ### Conclusion:
  que estubo dificil pq no puse atencion cuando nos enseño lo de las llaves pero todo lon demas ests a easy 

  
  

