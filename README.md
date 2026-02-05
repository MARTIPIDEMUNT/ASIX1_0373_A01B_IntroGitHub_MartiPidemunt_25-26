# ASIX1_0373_A00_IntroGitHub
## Primer repositorio en ASIX1 del curso 25-26 en la aplicacion
### Es primera toma de contacto con github
#### Soy Martí Pidemunt

<a href="./imagenes/imagen_random.jpg">Enlace a imagen</a>
Esto está en __negrita__
Esto está en **negrita**

Esto está en _cursiva_
Esto está en *cursiva*

__*TEXTO*__
**__TEXTO__**

ABRIR ETIQUETA 1
     ABRIR ETIQUETA 2
        contenido
     CERRAR ETIQUETA 2
CERRAR ETIQUETA 1

1. Elemento 
    * Elemento desordenado 1.1
    * Elemento desordenado 1.2
2. Elemento 2
    * Elemento desordenado 2.1
    * Elemento desordenado 2.2
3. Elemento 3
    * Elemento desordenado 3.1
    * Elemento desordenado 3.2

* Elemento desordenado 1
* Elemento desordenado 2
* Elemento desordenado 3

regooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooqejnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnngnernognerneroreverjvernvnervvnerovnerrvnenrvnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnn 

<p>Esto es un parrafo</p>

[link](https://stackoverflow.com/questions/41345160/display-link-url-in-markdown/ "Manual oficial de Markdown")

![alt text](./imagenes/iniesta.png/ "Imagen random de un archivo")

| *Jugador* | Equipo | Nombre |
|------------:|:---------------:|:--------------|
| 32 | Lakers | Magic Jonhson |
| 33 | Celtics | Larry Bird |
| 23 | Bulls | Michael Jordan |

```html
<!DOCTYPE html>
<!-- Define el tipo de documento HTML5 -->

<html lang="es">
<!-- Idioma del documento -->

<head>
<meta charset="UTF-8">
<!-- Permite usar caracteres especiales -->

<meta name="viewport" content="width=device-width, initial-scale=1.0">
<!-- Hace la web adaptable a móviles -->

<title>Primera pagina</title>
</head>

<body>

<a href="#imagen1">Enlace a Imagen uno</a>
<!-- Enlace interno dentro de la página -->

<h1>Hola mundo</h1>
<!-- Encabezado principal -->

<h2>Mi primera pagina web</h2>

<p>Lorem ipsum dolor sit amet...</p>
<!-- Párrafo -->

<br>
<!-- Salto de línea -->

<hr>
<!-- Línea separadora -->

<p><em>Texto enfatizado</em></p>
<!-- Texto en cursiva -->

<p><strong>Texto importante</strong></p>
<!-- Texto con importancia semántica -->

<ol>
<!-- Lista ordenada -->

<li>Primer elemento
    <ol>
        <li>SubElemento 1.1</li>
        <li>SubElemento 1.2</li>
    </ol>
</li>

</ol>

<ul>
<!-- Lista desordenada -->

<li>Elemento</li>

</ul>

<img id="imagen1" src="./imagenes/imagen1.jpg" alt="Foto ejemplo">
<!-- Imagen con identificador -->

<a href="./viajes.html">Viaje a NYC</a>
<!-- Enlace a otra página -->

</body>
</html>
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>tablas</title>
</head>
<body>
<table border="1">
<!-- Tabla con borde -->

<h2>Tabla Clasificatoria Maratón BCN</h2>
<!-- Título de la tabla -->

<thead>
<!-- Encabezado tabla -->
<tr>
<th>ORDEN</th>
<th>ATLETA</th>
<th>TIEMPO</th>
</tr>
</thead>

<tbody>
<!-- Cuerpo tabla -->

<tr>
<td>1</td>
<td>Michel Eaton</td>
<td>2:23:00</td>
</tr>

<tr>
<td rowspan="2">2</td>
<!-- Une filas -->
<td colspan="2">Andrea Bocelli</td>
<!-- Une columnas -->
</tr>

</tbody>
</table>

<form action="URLdeDestino.html" method="GET">
<!-- Formulario que envía datos -->

<label>Username:</label>
<input type="text" name="username" required>
<!-- Campo obligatorio -->

<fieldset>
<!-- Agrupa campos -->

<legend>Carnet conducir</legend>

<input type="radio" name="carnet" value="si"> SI
<input type="radio" name="carnet" value="no"> NO

</fieldset>

<select name="Nacionalidad">
<!-- Lista desplegable -->
<option>España</option>
<option>Peru</option>
</select>

<textarea rows="5"></textarea>
<!-- Área de texto -->

<button type="submit">Enviar</button>

</form>

</body>
</html>

git init
# Inicializa repositorio
<img src="./imagenes/git_init.jpg">
git add .
# Añade archivos al staging
<img src="./imagenes/git_add.jpg">
git commit -m "Añadidas líneas al README"
# Guarda cambios
<img src="./imagenes/git_commit.jpg">
git push origin main
# Sube cambios a GitHub
<img src="./imagenes/git_push_origin-main.jpg">
# Clonar repositorio
<img src="./imagenes/git_clone.jpg">
git clone https://github.com/usuario/repositorio.git


<!DOCTYPE html>
<html lang="es">

<head>
<meta charset="UTF-8">
<title>Apuntes Markdown GitHub y HTML</title>
<link rel="stylesheet" href="./css/markdown.css">

</head>

<body>

<h1>Apuntes completos</h1>

<section>

<!-- Comentario: Encabezados Markdown -->

<h2>Etiquetas básicas de Markdown</h2>

<h3>Encabezados</h3>

<p>Sirven para organizar documentos.</p>

<pre>
# H1
## H2
### H3
#### H4
##### H5
###### H6
</pre>

<!-- Comentario: Estilos de texto Markdown -->

<h3>Estilos de letra</h3>

<ul>
<li>Cursiva : *texto* o _texto_</li>
<li>Negrita : **texto** o __texto__</li>
<li>Tachado : ~~palabra~~</li>
<li>Anidar estilos : **palabra1 _palabra2_**</li>
</ul>

</section>

<section>

<!-- Comentario: Enlaces Markdown -->

<h3>Enlaces</h3>

<pre>
[Link](https://google.com/ "Título opcional")
</pre>

<p>Texto entre corchetes : texto visible</p>
<p>Texto entre paréntesis : dirección del enlace</p>

<!-- Comentario: Imágenes Markdown -->

<h3>Imágenes</h3>


</section>

<section>

<!-- Comentario: Tablas Markdown -->

<h3>Tablas Markdown</h3>

<table>

<tr>
<th>Tables</th>
<th>Are</th>
<th>Cool</th>
</tr>

<tr>
<td>col 3 is</td>
<td>centered</td>
<td>1600</td>
</tr>

<tr>
<td>col 2 is</td>
<td>centered</td>
<td>12</td>
</tr>

</table>

</section>

<section>

<!-- Comentario: Listas verificación Markdown -->

<h3>Listas verificación</h3>

<ul>
<li>☐ A</li>
<li>☑ B</li>
<li>☐ C</li>
</ul>

</section>

<section>

<!-- Comentario: Crear repositorio GitHub -->

<h2>Crear repositorio GitHub</h2>

<ol>

<li>Entrar en https://github.com</li>
<img src="./imagenes/inicio_sesion_github.jpg">
<li>Crear cuenta</li>
<img src="./imagenes/crear_cuenta_github.jpg">
<li>Crear repositorio nuevo</li>
<img src="./imagenes/1-Paso_crear_repositorio.jpg">
<img src="./imagenes/2-Paso_Crear_repositorio.jpg">
</ol>


</section>

<section>

<!-- Explicación de GitHub creacion Pages -->

<h2>GitHub Pages</h2>

<p>
GitHub Pages : servicio de GitHub que permite publicar páginas web gratis usando repositorios.
</p>

<!-- Comentario: Requisitos para usar GitHub Pages -->

<h3>Requisitos</h3>

<ul>
<li>Tener cuenta en GitHub</li>
<li>Tener repositorio creado</li>
<li>Tener archivo index.html</li>
<img src="./imagenes/tener_repositorio_creado_index.jpg">

</ul>

<!-- Comentario: Pasos para crear GitHub Pages -->

<h3>Pasos para crear una página web con GitHub Pages</h3>

<ol>

<li>Entrar en el repositorio</li>
<li>Ir a Settings</li>
<img src="./imagenes/setings.jpg">

<li>Entrar en Pages</li>
<img src="./imagenes/entrar_pages.jpg">
<li>En Source seleccionar :
Branch : main  
Folder : root  
</li>

<li>Guardar cambios</li>
<img src="./imagenes/main_root.jpg">
</ol>

<!-- Comentario: Enlace generado automáticamente -->

<h3>Dirección de la página web</h3>

<p>
GitHub genera una URL con formato :
</p>

<pre>
https://github.com/MARTIPIDEMUNT/-Segura-Pidemunt-Marti_ASIX1_0373_25-26_AE5
</pre>

<!-- Comentario: Ejemplo real -->

<p>
Ejemplo :
</p>

<pre>
https://martipidemunt.github.io/ASIX1_0373_A00_IntroGitHub
</pre>
</section>
<section>

<!-- Comentario: Introducción HTML -->

<h2>Introducción a HTML</h2>

<p>
HTML : lenguaje estándar para crear páginas web.
</p>

<h3>Significado HTML</h3>

<ul>
<li>HyperText : enlaza contenidos</li>
<li>Markup : utiliza etiquetas</li>
<li>Language : sigue normas</li>
</ul>

</section>

<section>

<!-- Comentario: Elementos HTML -->

<h3>Elementos HTML</h3>

<ul>
<li>Etiqueta apertura : &lt;p&gt;</li>
<li>Contenido : texto o elementos</li>
<li>Etiqueta cierre : &lt;/p&gt;</li>
</ul>

<pre>
&lt;p&gt;Contenido&lt;/p&gt;
</pre>

</section>

<section>

<!-- Comentario: Atributos HTML -->

<h3>Atributos HTML</h3>

<pre>
&lt;p class="editor-note"&gt;Texto&lt;/p&gt;
</pre>

<p>class : nombre del atributo</p>
<p>editor-note : valor del atributo</p>

</section>

<section>

<!-- Comentario: Estructura básica HTML -->

<h2>Estructura básica HTML</h2>

<pre>
&lt;!DOCTYPE html&gt;
&lt;html&gt;
&lt;head&gt;
&lt;title&gt;Página&lt;/title&gt;
&lt;/head&gt;
&lt;body&gt;
Contenido
&lt;/body&gt;
&lt;/html&gt;
</pre>

<p>DOCTYPE : tipo documento</p>
<p>html : elemento raíz</p>
<p>head : metadatos</p>
<p>body : contenido visible</p>

</section>

<section>

<!-- Comentario: Listas HTML -->

<h2>Listas HTML</h2>

<h3>Lista desordenada</h3>

<ul>
<li>Elemento 1</li>
<li>Elemento 2</li>
</ul>

<h3>Lista ordenada</h3>

<ol>
<li>Elemento A</li>
<li>Elemento B</li>
</ol>

</section>

<section>

<!-- Comentario: Rutas HTML -->

<h2>Rutas</h2>

<h3>Ruta absoluta</h3>

<img src="/imagenes/Google_logo.jpg">
<pre>
<img>
</pre>

<h3>Ruta relativa</h3>

<pre>

<img src="./imagenes/Google_logo.jpg">
</pre>

</section>

<section>

<!-- Comentario: Enlaces HTML -->

<h2>Enlaces</h2>

<a href="https://google.com">Enlace externo</a>

<br>

<a href="./index.html">Enlace interno</a>

</section>

<section>

<!-- Comentario: Formularios HTML -->

<h2>Formularios</h2>

<form>

<label>Nombre :</label>
<input type="text">

<br>

<label>Email :</label>
<input type="email">

<br>

<input type="submit">

<h3>Checkbox</h3>

<input type="checkbox"> Deportes
<input type="checkbox"> Música

<h3>Radio</h3>

<input type="radio" name="genero"> Rock
<input type="radio" name="genero"> Pop

</section>

<section>

<!-- Comentario: Select HTML -->

<h2>Select</h2>

<select>
<option>España</option>
<option>México</option>
<option>Argentina</option>


</select>

</section>

<section>

<!-- Comentario: Textarea HTML -->

<h2>Textarea</h2>

<textarea rows="4"></textarea>

</form>
</section>

<section>

<!-- Comentario: Tablas HTML -->

<h2>Tablas HTML</h2>

<table border="2px">

<thead>
<tr>
<th>Nombre</th>
<th>Edad</th>
<th>Ciudad</th>
</tr>
</thead>

<tbody>
<tr>
<td>Ana</td>
<td>25</td>
<td>Madrid</td>
</tr>
</tbody>

</table>

</section>
<h1>Apuntes CSS</h1>
<a href="./apuntes_css.html">Enlace interno</a>
</body>
</html>



