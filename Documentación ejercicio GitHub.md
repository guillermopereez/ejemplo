---


---

<h1 id="documentación-ejercicio-github">Documentación ejercicio GitHub</h1>
<p>Esta es la documentación paso por paso del ejercicio de <strong>creación y gestión</strong> de un <strong>repositorio</strong> en <strong>GitHub</strong>.</p>
<h2 id="crear-el-repositorio-en-github">1. Crear el repositorio en GitHub</h2>
<p>El primer paso es <strong>crear</strong> el repositorio. Para ello se debe acceder tu perfil de <strong><a href="https://github.com/">GitHub</a></strong> y entrar donde dice <strong>Repositories</strong> (o <em>Repositorios</em> en español).</p>
<p><img src="https://i.imgur.com/HfHbcHg.png" alt="Captura de pantalla del apartado &quot;Repositorios&quot; de GitHub"></p>
<p>Una vez estamos en la parte de nuestro repositorios, debemos ir a la parte derecha y entrar donde dice <strong>New</strong> (<em>Nuevo</em>).</p>
<p><img src="https://i.imgur.com/4aUM0Q2.png" alt="Captura de pantalla del apartado &quot;New&quot; de tus repositorios en GitHub"></p>
<h3 id="configuración-del-repositorio">Configuración del repositorio</h3>
<p>Una vez estamos en el apartado de creación del nuevo repositorio, debemos ponerle un <strong>nombre</strong>, una <strong>descripción</strong> (opcional) y elegir si queremos que nuestro repositorio sea <strong>público</strong> o <strong>privado</strong>.</p>
<ul>
<li>
<p>Si lo hacemos <strong>público</strong>, cualquier persona podría ver el contenido de dicho repositorio.</p>
</li>
<li>
<p>Si lo hacemos <strong>privado</strong>, solo la persona que crea el repositorio, colaboradores del mismo o personas con acceso autorizado podrán ver lo que contiene.</p>
</li>
</ul>
<h3 id="opciones-de-creación-del-repositorio">Opciones de creación del repositorio</h3>
<p>Después de haber puesto un <em>nombre</em>, una <em>descripción</em>, y escoger entre <em>público</em> o <em>privado</em>, se nos abre una nueva página donde lo primero que nos dicen es si queremos añadir <strong>colaboradores</strong> en nuestro repositorio. No hay que hacerlo necesariamente ahora, ya que mas adelante se pueden añadir desde el apartado de <em>Ajustes</em> del repositorio.</p>
<p>Más adelante, nos da diferentes opciones a la hora de crear el repositorio:</p>
<ul>
<li>
<p><strong>Crear</strong> el nuevo repositorio en nuestra <strong>consola de comandos</strong>, usando los siguientes comandos:</p>
<p><code>echo "# ejemplo" &gt;&gt; README.md</code><br>
<code>git init</code><br>
<code>git add README.md</code><br>
<code>git commit -m "first commit"</code><br>
<code>git branch -M main</code><br>
<code>git remote add origin https://github.com/guillermopereez/ejemplo.git</code><br>
<code>git push -u origin main</code></p>
</li>
<li>
<p><strong>Importar</strong> un repositorio ya creado, usando los siguientes comandos:<br>
<code>git remote add origin https://github.com/guillermopereez/ejemplo.git</code><br>
<code>git branch -M main</code><br>
<code>git push -u origin main</code></p>
</li>
<li>
<p>O la opción que vamos a usar en este ejercicio que es <strong>clonando</strong> el repositorio en nuestra <strong>máquina local</strong>. Para ello vamos a usar los siguientes comandos:<br>
<code>git clone [url]</code><br>
<code>git add archivo.txt</code><br>
<code>git commit -m "Primer commit"</code><br>
<code>git push origin main</code></p>
</li>
</ul>
<p>Una vez hecho esto, ya tendríamos nuestro repositorio listo para empezar a trabajar.</p>
<h2 id="creación-de-ramas-y-pull-request">2. Creación de Ramas y Pull Request</h2>
<p>Una vez está creado el repositorio, vamos a crear dos <strong>ramas</strong>, una para cada archivo.</p>
<p>La primera <strong>rama</strong> es para la parte de la listas de amigos, y se <strong>crea</strong> usando el siguiente <strong>comando</strong>:<br>
<img src="https://i.imgur.com/h5yCHj9.png" alt="Captura del comando para crear una rama"><br>
Y ahora para <strong>entrar en la rama</strong>, usamos este comando:<br>
<img src="https://i.imgur.com/8I2dXni.png" alt="Captura del comando para entrar en una rama"><br>
Una vez estamos en la rama. podemos empezar a hacer los <strong>cambios</strong> en el <strong>archivo</strong>. En este caso, voy a poner los <strong>nombres</strong> y los <em>supuestos</em> <strong>números</strong> de teléfono de 3 amigos:<br>
<img src="https://i.imgur.com/JTPLO5v.png" alt="Captura de los datos introducidos en el archivo"></p>
<p>Una vez hechos los cambios los guardamos usando el comando <code>git add lista_amigos.txt</code> y hacemos el <a href="https://github.com/guillermopereez/ejercicio_github_guillermo_y_karen/pull/1/commits/dd329f637f9dd886a9883cdb4ed538560081a25d">commit</a> <code>git commit -m "texto del commit"</code> .</p>
<p>Ahora, para poder <strong>subir</strong> este cambio desde nuestro repositorio local a GitHub, usamos el siguiente comando:<br>
<img src="https://i.imgur.com/bJTjA6o.png" alt="Captura del comando para subir los cambios"></p>
<h3 id="pull-request">Pull Request</h3>
<p>Ahora, al hacer el <em>push</em> hacia el repositorio remoto, en GitHub saltará un aviso de un <strong>Pull Request</strong>:<br>
<img src="https://i.imgur.com/M9QxPDw.png" alt="Captura del Pull request"></p>
<p>Aquí, los demás <strong>colaboradores</strong> de mi repositorio podrán <strong>votar</strong> si el cambio que estoy proponiendo les parece bien y podrán <strong>comentar</strong> al respecto.</p>

