
# lab #6: Enlazando mi proyecto con GitHub:
*.md Mark Down

Julian Rafael Ureña Marte #23

* [x] Crear cuenta en GitHub
* [x] Crear un repositorio en GitHub - Nombre del repo = js-curso-23-5B.
* [x] Cambiar el nombre de mi rama local master -> main.
* [x] Agregar cambios a la zona de preparacion **git add**
* [x] Confirmar los cambios **git commit -am "primer commit remoto**
* [x] Agregar mi repositorio remoto a mi repositorio local **git remote add origin url_remote**
* [x] Subir mis cambios al remoto **git push -u origin main**
* [x] Comprobar que mi remoto temga los ultimos cambios agregados.

# lab #8.1: Istalaciones de paquetes.

Julian Rafael Ureña Marte #23.

* [x] Istalar paquetes de codigo con NPM.
* [x] Istalar **yargs** con el comando **npm istall yargs**.
* [x] Agregar archivo **.gitignore**.
* [x] Editar archivo **.gitignore** para ignorar la carpeta **node_modules**.
* [x] Editar archivo **.gitignore** para ignorar el archivo **package-lock.json**.
* [x] Istalar **colors** con el comando **npm i color** cambio install por i.
* [x] Confirmar mi **package.json** tenga las dependencias de **yargs** y **colors**.
* [x] Usar comando **git add .** para preparar los cambios.
* [x] Usar comando **git commit -am "Istalar paquetes Yargs y Colors**.
* [x] Usar comando **git push** para subir mis cambios al remoto.

# Lab #8.2: Creacion y Organizacion del proyecto:

Julian Rafael Ureña Marte #23.

* [x] Crear el archivo **node-CLI/app.js**
    * [x] Hacemos **git add .**
    * [x] Hacemos **git commit -am "Crea app.js**
    * [x] Hacemos **git push**
* [x] Crear directorio **node-CLI/tools** con:
    * [x] Crear **node-CLI/tools/index.js**
    * [x] Crear **node-CLI/tools/argvs.js**
    * [x] Crear **node-CLI/tools/files.js**
    * [x] Crear **node-CLI/tools/options.js**
    * [x] Crear **node-CLI/tools/task.js**
* [x] Crear directorio **node-CLI/db** con
    * [x] Crear **node-CLI/db/task.json**
    * [x] Hacemos **git add .**
    * [x] Hacemos **git commit -am "Crea tools settings"**
    * [x] Hacemos **git push**

# Lab #8.3 Trabajando con ficheros en Node:

Julian Rafael Ureña Marte #23.

* [x] Empezamos a trabajar con **files.js**
    * [x] Importamos paquetes **Path y Colors**

* [x] Usamos paquetes importados en nuestro codigo con la funcion **loadTask()**
    * [x] Exportamos nuestra funcion **loadTask()**
    * [x] Pruebas de loadTask.
    * [x] Hacemos **git add .**
    * [x] Hacemos **git commit -am "Crea funcion loadTask()**
    * [x] Hacemos **git push**

* [x] Usamos paquetes importados en nuestro codigo con la funcion **saveTask()**
    * [x] Exportamos nuestra funcion **saveTask()**
    * [x] Pruebas de saveTask.
    * [x] Hacemos **git add .**
    * [x] Hacemos **git commit -am "Crea funcion saveTask()**
    * [x] Hacemos **git push**

# Lab #8.4 Trabajando con opciones de Yargs:

Julian Rafel Ureña Marte #23.

* [x] Empezamos a trabajar con **options.js**
  * [x] Creamos los objetos para nuestros comandos:
        * description
        * title
        * completed
        * erased
  * [x] Creamos las opciones para nuestros comandos:
        * opcionsCreate
        * opcionsUpdate
        * opcionsErase
  * [x] Exportamos nuestras opciones
  * [x] Hacemos **git add .**
  * [x] Hacemos **git commit -am "Configura argvs con opciones para los comandos"**
  * [x] Hacemos **git push**

  # Lab 8.5 Trabajamos en funciones para los tasks o tareas:

  Julian Rafael Ureña Marte #23.

  * [x] Empezamos a trabajar con task.js
        * [x] Creamos funciones para trabajar los tasks: **createTask, updateTask, eraseTask**
        * [x] Exportamos nuestras funciones
        * [x] Hacemos **git add .**
        * [x] Hacemos **git commit -am "Configura argvs con opciones para los comandos"**
        * [x] Hacemos **git push**

 # Lab 8.6 Trabajamos con la configuracion de Yargs:

Julian Rafael Ureña Marte #23.

* [x] Empezamos a trabajar con el fichero **argvs.js**
    * [x] Agregamos los comandos que usara Yargs.
    * [x] Exporto el proyecto argvs para nuestro proyecto.

* [x] Empezamos a trabajar con **index.js**
    * [x] Importamos y exportamos nuestras herramientas.

* [x] Hacemos **git add .**
* [x] Hacemos **git commit -am "Exportar tools components**
* [x] Hacemos **git push**

# Lab 8.7 Trabajamos con nuestra aplicacion principal:

Julian Rafael Ureña Marte #23.

* [x] Empezamos a trabajar con el fichero **app.js**
* [x] Importamos las herramientas ```tasks argv``` y el paquete ```colors```
    * [x] Usamos estructura ```switch```
        * [x] Filtramos los comandos ```create update delete```
* [x] Hacemos **git add .**
* [x] Hacemos **git commit -am "Finaliza proyecto-pruebas de funcionamiento**
* [x] Hacemos **git push**