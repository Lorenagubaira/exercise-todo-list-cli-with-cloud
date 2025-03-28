<!--hide-->
# ¡Lista de tareas pendientes CLI sincronizada con la nube!
<!--endhide-->

<p align="center"><img src="https://github.com/breatheco-de/todo-list-cli-with-cloud/blob/master/preview.gif" width="500" /></p>

Hoy construirás una lista TODO usando API's para sincronizarla con la nube.

Practicarás:
1. Listas / arrays de Python.
2. Diccionarios de Python.
3. Usar el paquete requests para la comunicación de API.
4. Protocolo HTTP.

Vamos a usar la [API de TODO de BreatheCode](https://playground.4geeks.com/apis/fake/todos/) para cargar y descargar los TODO, por favor consulta las lecciones de HTTP y REST como una investigación de fondo rápida para el proyecto.

- Obtener TODO llamando: `[GET] /todos/user/<username>`
- Inicializar la lista TODO: `[POST] /todos/user/<username>`
- Actualizar tu lista TODO: `[PUT] /todos/user/<username>`

<how-to-start>
  
## 🌱 Cómo comenzar este proyecto

No clones este repositorio porque usaremos una plantilla diferente.  

Recomendamos abrir la el `Python boilerplate`, utilizando una herramienta de aprovisionamiento como [Codespaces](https://4geeks.com/lesson/what-is-github-codespaces) (recomendado) o [Gitpod](https://4geeks.com/lesson/how-to-use-gitpod). Alternativamente, puedes [clonar el repositorio de GitHub](https://4geeks.com/how-to/github-clone-repository) en tu computadora local utilizando el comando `git clone`.  

Este es el repositorio que necesitas abrir o clonar:  

```sh
$ git clone https://github.com/4GeeksAcademy/flask-rest-hello
```

💡 Importante: recuerda crear un nuevo repositorio, actualizar el remoto (`git remote set-url origin <your new url>`) y cargar el código a tu nuevo repositorio `add`, `commit` y `push`.

### Pasos 

1. Instala los paquetes de dependencia escribiendo:

```sh
$ pipenv install --python 3
```

2. Entra a tu entorno virtual escribiendo:

```sh
$ pipenv shell
```

3. Puedes ejecutar el proyecto escribiendo:

```sh
$ python src/app.py
```

4. También puedes ejecutar las pruebas para el proyecto:

```sh
$ python src/test.py
```

</how-to-start>

## 📝 Instrucciones

- Tu aplicación debe funcionar desde la línea de comandos [así](https://github.com/breatheco-de/todo-list-cli-with-cloud/blob/master/preview.gif).
- El usuario debe poder agregar nuevas tareas.
- El usuario puede agregar tantas tareas como desee.
- El usuario puede eliminar tareas especificando la posición de la tarea en la lista.
- La aplicación debe poder guardar los TODO en la nube usando la [API de TODO de BreatheCode](https://playground.4geeks.com/apis/fake/todos/)
- La aplicación debe poder descargar (cargar) los TODO desde la [API de TODO de BreatheCode](https://playground.4geeks.com/apis/fake/todos/)


