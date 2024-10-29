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
<h2 id="creación-de-ramas-y-pull-requests">2. Creación de Ramas y Pull Requests</h2>

