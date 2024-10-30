Documentación ejercicio GitHub
Esta es la documentación paso por paso del ejercicio de **creación y gestión** de un **repositorio** en **GitHub**.

## 1. Crear el repositorio en GitHub
El primer paso es **crear** el repositorio. Para ello se debe acceder tu perfil de **[GitHub](https://github.com/)** y entrar donde dice **Repositories** (o *Repositorios* en español).

![Captura de pantalla del apartado "Repositorios" de GitHub](https://i.imgur.com/HfHbcHg.png)

Una vez estamos en la parte de nuestro repositorios, debemos ir a la parte derecha y entrar donde dice **New** (*Nuevo*).

![Captura de pantalla del apartado "New" de tus repositorios en GitHub](https://i.imgur.com/4aUM0Q2.png)

### Configuración del repositorio

Una vez estamos en el apartado de creación del nuevo repositorio, debemos ponerle un **nombre**, una **descripción** (opcional) y elegir si queremos que nuestro repositorio sea **público** o **privado**. 

- Si lo hacemos **público**, cualquier persona podría ver el contenido de dicho repositorio.

- Si lo hacemos **privado**, solo la persona que crea el repositorio, colaboradores del mismo o personas con acceso autorizado podrán ver lo que contiene.

### Opciones de creación del repositorio

Después de haber puesto un *nombre*, una *descripción*, y escoger entre *público* o *privado*, se nos abre una nueva página donde lo primero que nos dicen es si queremos añadir **colaboradores** en nuestro repositorio. No hay que hacerlo necesariamente ahora, ya que mas adelante se pueden añadir desde el apartado de *Ajustes* del repositorio. 

Más adelante, nos da diferentes opciones a la hora de crear el repositorio:

- **Crear** el nuevo repositorio en nuestra **consola de comandos**, usando los siguientes comandos:

	`echo "# ejemplo" >> README.md`
	`git init`
	`git add README.md` 
	`git commit -m "first commit"`
	`git branch -M main`
	`git remote add origin https://github.com/guillermopereez/ejemplo.git`
	`git push -u origin main`

- **Importar** un repositorio ya creado, usando los siguientes comandos:
	`git remote add origin https://github.com/guillermopereez/ejemplo.git`
	`git branch -M main`
	`git push -u origin main`
- O la opción que vamos a usar en este ejercicio que es **clonando** el repositorio en nuestra **máquina local**. Para ello vamos a usar los siguientes comandos:
	`git clone [url]`
	`git add archivo.txt`
	`git commit -m "Primer commit"`
	`git push origin main`

Una vez hecho esto, ya tendríamos nuestro repositorio listo para empezar a trabajar.
## 2. Creación de Ramas y Pull Request
Una vez está creado el repositorio, vamos a crear dos **ramas**, una para cada archivo.

La primera **rama** es para la parte de la listas de amigos, y se **crea** usando el siguiente **comando**:
![Captura del comando para crear una rama](https://i.imgur.com/h5yCHj9.png)
Y ahora para **entrar en la rama**, usamos este comando:
![Captura del comando para entrar en una rama](https://i.imgur.com/8I2dXni.png)
Una vez estamos en la rama. podemos empezar a hacer los **cambios** en el **archivo**. En este caso, voy a poner los **nombres** y los *supuestos* **números** de teléfono de 3 amigos:
![Captura de los datos introducidos en el archivo](https://i.imgur.com/JTPLO5v.png)

Una vez hechos los cambios los guardamos usando el comando `git add lista_amigos.txt` y hacemos el [commit](https://github.com/guillermopereez/ejercicio_github_guillermo_y_karen/pull/1/commits/dd329f637f9dd886a9883cdb4ed538560081a25d) `git commit -m "texto del commit"` .

Ahora, para poder **subir** este cambio desde nuestro repositorio local a GitHub, usamos el siguiente comando:
![Captura del comando para subir los cambios](https://i.imgur.com/bJTjA6o.png)


### Pull Request

Ahora, al hacer el *push* hacia el repositorio remoto, en GitHub saltará un aviso de un **Pull Request**:
![Captura del Pull request](https://i.imgur.com/M9QxPDw.png)

Aquí, los demás **colaboradores** de mi repositorio podrán **votar** si el cambio que estoy proponiendo les parece bien y podrán **comentar** al respecto. Una vez se haya votado y aceptado el cambio, los cambios habrán pasado a la rama **main**.
