# ASIX1_0373_A00_IntroGitHub
## Primer repositorio en ASIX1 del curso 25-26 en la aplicacion
### Es primera toma de contacto con github
#### Soy Martí Pidemunt

<a href="Imagen1">Enlace a imagen</a>
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

```html
<p>Esto es un parrafo</p>
```
[link](https://stackoverflow.com/questions/41345160/display-link-url-in-markdown/ "Manual oficial de Markdown")

![alt text](iniesta.png/ "Imagen random de un archivo")

| *Jugador* | Equipo | Nombre |
|------------:|:---------------:|:--------------|
| 32 | Lakers | Magic Jonhson |
| 33 | Celtics | Larry Bird |
| 23 | Bulls | Michael Jordan |


<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Primera pagina</title>
</head>
<body>


    <a href="#imagen1">Enlace a Imagen uno</a>
    <!--Esto es un comentario-->
    <h1>Hola mundo</h1>
    <h2>Mi primera pagina web</h2>
    <h3>Subtitulo</h3>
    <h4>Subsubtitulo</h4>
    <h5>Subsubsubtitulo</h5>
    <h6>Subsubsubsubtitulo</h6>

    <!-- Etiquetas de parrafo -->
    <p>ipsum dolorsit, amet consectetur adipisicing elit. Facere accusamus tempora neque voluptas, alias, eius molestias magni, amet accusantium impedit nesciunt labore quia cupiditate temporibus illum ab blanditiis optio nam.</p>

    <!-- Etiquetas de salto de linea -->
    <br>
    <hr>

    <!-- Etiqueta de destacar y parrafo -->
    <p><em>ipsum dolor</em> sit, amet consectetur adipisicing elit. Facere accusamus tempora neque voluptas, alias, eius molestias magni, amet accusantium impedit nesciunt labore quia cupiditate temporibus illum ab blanditiis optio nam.</p>    
    <p><b>ipsum dolor</b> sit, amet consectetur adipisicing elit. Facere accusamus tempora neque voluptas, alias, eius molestias magni, amet accusantium impedit nesciunt labore quia cupiditate temporibus illum ab blanditiis optio nam.</p>
    <p><strong>ipsum dolor</strong> sit, amet consectetur adipisicing elit. Facere accusamus tempora neque voluptas, alias, eius molestias magni, amet accusantium impedit nesciunt labore quia cupiditate temporibus illum ab blanditiis optio nam.</p>

    <!-- Etiqueta para marcar un trozo de contenido en linea -->
    <p><span>ipsum dolor</span> sit, amet consectetur adipisicing elit. Facere accusamus tempora neque voluptas, alias, eius molestias magni, amet accusantium impedit nesciunt labore quia cupiditate temporibus illum ab blanditiis optio nam.</p>

    <ol>  <!-- Etiqueta para definir una lista ordenada -->
        <li>Primer elemento de la lista</li> <!-- Esto es un elemento, se define con "li" -->
            <ol>
                <li>SubElemento 1.1</li>
                <li>SubElemento 1.2</li>
            </ol>
        <li>Segundo elemento de la lista</li>
        <li>Tercer elemento de la lista</li>
    </ol>

 <ul><!-- Etiqueta para definir una lista desordenada -->
        <li>Primer elemento de la lista</li> <!-- Esto es un elemento, se define con "li" -->
        <li>Segundo elemento de la lista</li>
        <li>Tercer elemento de la lista</li>
    </ul>
    <BR>
    <!-- Etiqueta para insertar imagenes -->
    <img id="imagen1" src="./MULTIMEDIA/IMAGENES/images.jpg" alt="Foto de SOLDIUER BOY" >

    <!-- Etiqueta para insertar enlaces -->
     <br>
     <a href="./VIAJES/NYC/viajes.html">Viaje a NYC</a>


</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>

    <table border="1">
        <thead>
            <tr>
                <th>ORDEN</th>
                <th>ATLETA</th>
                <th>TIEMPO</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1</td>
                <td>Michel Eaton</td>
                <td>2:23:00</td>
            </tr>
            <tr>
                <td rowspan="2">2</td>
                <td colspan="2">Andrea Bocelli</td>

            </tr>
            <tr>

                <td>Steve Carmaikel</td>
                <td>2:50:00</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <td>ORDEN</td>
                <td>ATLETA</td>
                <td>TIEMPO</td>
            </tr>
        </tfoot>
    </table>
    <caption>tabla Clasifcatoria de maraton de BCN</caption>

    <form action="URLdeDestino.html" method="GET">
        <label for="username">Username:</label>
        <input type="text" name="username" id="username" required>
        <br>
        <label for="realname">Nombre real:</label>
        <input type="text" name="realname" id="realname">
        <br>

        <fieldset>
            <legend>Carnet de conducir</legend>
            <label for="carnetsi">SI:</label>
            <input type="radio" name="carnet" value="carnetsi" id="carnetsi">
            <label for="carnetno">NO:</label>
            <input type="radio" name="carnet" value="carnetno" id="carnetno">
        </fieldset>
        <br>
        <fieldset>
            <legend>Gustos musicales</legend>
            <label for="pop">Pop:</label>
            <input type="checkbox" name="musica[]" value="pop" id="pop">
            <label for="heavy">Heavy:</label>
            <input type="checkbox" name="musica[]" value="heavy" id="heavy">
            <label for="pachanga">Pachanga:</label>
            <input type="checkbox" name="musica[]" value="pachanga" id="pachanga">
        </fieldset>
        <br>
    <label for="nacioniladidad">Nacionalidad:</label>
        <select name="Nacionalidad" id="nacioniladidad">
            <option value="españa">España</option>
            <option value="peru">Peru</option>
            <option value="argentina">Argentina</option>
            <option value="chile">Chile</option>
        </select>
        <br>
        <label for="observaciones">Observaciones:</label><br>
        <textarea name="observaciones" id="observaciones" rows="5" cols="30" placeholder="Introduce aqui cualquier observacion que tengas"></textarea>
        <br>
        <button type="submit" name="Enviar" value="enviar">Enviar Datos</button>
    </form>
</body>
</html>

Para subir los cambios al GitHub.
PS C:\Repositorios_Git\ASIX1_0373_A00_IntroGitHub> git init
Reinitialized existing Git repository in C:/Repositorios_Git/ASIX1_0373_A00_IntroGitHub/.git/

PS C:\Repositorios_Git\ASIX1_0373_A00_IntroGitHub> git add .

PS C:\Repositorios_Git\ASIX1_0373_A00_IntroGitHub> git commit -m "Añadidas 2 lines al README"
[main ef1ba7d] Añadidas 2 lines al README
 1 file changed, 2 insertions(+)

PS C:\Repositorios_Git\ASIX1_0373_A00_IntroGitHub> git push origin main
info: please complete authentication in your browser…
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 380 bytes | 27.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/martipidemunt/ASIX1_0373_A00_IntroGitHub.git
   2dfd2b4..ef1ba7d  main -> main

Etiquetas básicas de Markdown

Encabezados. Llevan ya asociado un estilo por defecto cada uno y sirven para iniciar secciones de documentos:

# H1  
## H2  
### H3  
#### H4  
##### H5  
###### H6


Estilos de letra:

Itálica o cursiva: *texto* o _texto_

Negrita: **texto** o __texto__

Tachado: ~~palabra~~ (ALT+126)

Anidar estilos: **palabra1 _palabra2_** (ambas palabras se ven en itálica pero la segunda además en negrita)

Etiquetas básicas de Markdown

Enlaces:

[Link](https://ejemplo.com/ "Título opcional del enlace")


a) Primero se incluye el texto del link entre corchetes y posteriormente el link entre paréntesis.
b) El “título opcional del enlace” es el texto alternativo al pasar el ratón por encima.

Imágenes:

Inline-style:

![alt text](https://github.com/img/icon48.png "Título opcional de la imagen")


Reference-style:

![alt text][logo]
[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

Etiquetas básicas de Markdown

Tablas:

| Tables | Are | Cool |
|---------|:-------------:|------:|
| col 3 is | right-aligned | $1600 |
| col 2 is | centered | $12 |
| zebra stripes | are neat | $1 |


La primera línea son los encabezados de las columnas.
Los dos puntos (ver línea 2) se usan para alinear las columnas (izquierda, centrado, derecha).
No es necesario que estén alineadas verticalmente. Solo a nivel visual para claridad del código.
Se han de poner al menos tres guiones para separar cada encabezado.

Etiquetas básicas de Markdown

Notas al pie de página:
Texto con enlace a nota de pie de página 1

blablablablablablablablablablablablablablabla
blablablablablablablablablablablablablablabla
blablablablablablablablablablablablablablabla

Listas de verificación:

- [ ] A
- [x] B
- [ ] C


(Dejar un espacio en blanco entre los dos corchetes en las que aparezcan vacías)
# SEM2a: Introducción a HTML

Se introduce a la sintaxis, estructura y etiquetas básicas de un documento HTML (`body`, `html`, `title`, `p`, `h1…h6`), listas numeradas/no numeradas y cómo añadir un icono de página, así como la estructura de carpetas de un sitio web.

---

## Documentación

- Introducción a HTML y Fontawesome (resumen)  
- Fundamentos HTML (apuntes extendidos)  
- Mozilla Developer: HTML básico  
- HTML cheat sheet interactivo (ONLINE)  
- HTML cheat sheet (PDF)  
- Convertor PNG a ICO online convertICO  
- Insertar icono de pestaña en HTML  
- Qué es un favicon  

---

## Introducción a HTML

**HTML (HyperText Markup Language)** es el lenguaje de marcado estándar para crear páginas web.  
Lenguaje más importante de Internet dado que sin HTML no se vería nada en el navegador.

HTML define la estructura y el contenido (es decir, si hay una imagen, una lista de elementos, un enlace, un párrafo, un titular, etc...) de las páginas web mediante etiquetas. Es muy adaptable, tiene una estructura lógica y es muy fácil de entender e interpretar.  
**Describe el contenido.**

No se dedica a ver cómo se interactúa con el contenido (JavaScript, PHP, etc.), ni se preocupa por la presentación o estilizado del contenido, es decir, de cómo se ve el contenido (para eso tenemos CSS).

Los elementos HTML son los bloques de construcción de las páginas HTML.  
Cada elemento HTML está delimitado por etiquetas como `<body>`, `<head>`, `<p>`, `<h1>`, etc.

---

## Significado de HTML

Las siglas **HTML** corresponden a *HyperText Markup Language*, que tiene el siguiente significado:

- **HyperText**: texto que enlaza con otros contenidos (hipertexto).  
- **Markup**: marca o etiqueta, ya que todas las páginas web se construyen en base a etiquetas.  
  Ejemplo: `<p>HOLA</p>`  
- **Language**: lenguaje, ya que tiene sus normas y estructura.

> HTML **no es un lenguaje de programación**, sino de marcado.

---

## Elementos HTML

HTML consiste en una serie de **elementos** que usamos para encerrar diferentes partes del contenido, de modo que se vean o comporten de una determinada manera.

Las partes principales de un elemento son:

- **Etiqueta de apertura:** `<p>`
- **Etiqueta de cierre:** `</p>`
- **Contenido:** el texto o elementos dentro
- **Elemento completo:** `<p>Contenido</p>`

---

## Atributos HTML

Los elementos pueden tener atributos.

```html
<p class="editor-note">Mi gato es muy gruñón</p>
Los atributos contienen información adicional sobre el elemento.
En este caso, class es el nombre del atributo y editor-note su valor.

Reglas de los atributos:

Se colocan en la etiqueta de apertura.

Llevan un espacio antes del nombre.

Se escriben como nombre="valor".

Ejemplo de elemento vacío (sin etiqueta de cierre):


<img src="images/firefox-icon.png" alt="Mi imagen de prueba">
Estructura básica de un fichero HTML
Una página HTML básica incluye una declaración DOCTYPE, un elemento html, y dentro de este, un head y un body.


<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>Mi página de prueba</title>
  <link rel="icon" href="favicon.png">
</head>
<body>
  <img src="images/firefox-icon.png" alt="Mi imagen de prueba">
</body>
</html>
Donde:

<!DOCTYPE html> → tipo de documento (requerido)

<html> → elemento raíz

<head> → metadatos

<body> → contenido visible

Listas
Listas desordenadas <ul>
Se usan cuando el orden de los ítems no es relevante.

<ul type="disc">
  <li>Elemento 1</li>
  <li>Elemento 2</li>
</ul>
Tipos posibles: DISC, SQUARE, CIRCLE.

Listas ordenadas <ol>
Se usan cuando el orden sí importa.


<ol type="A" start="3">
  <li>Elemento A</li>
  <li>Elemento B</li>
</ol>
Opciones de type: A, a, I, i, 1.
start y value controlan la numeración.

Listas de definición <dl>
Permiten definir términos y sus descripciones.


<dl>
  <dt>HTML</dt>
  <dd>Lenguaje de marcas diseñado para estructurar textos y relacionarlos en forma de hipertexto.</dd>

  <dt>XML</dt>
  <dd>Metalenguaje extensible de etiquetas.</dd>

  <dt>XHTML</dt>
  <dd>Lenguaje de marcas compatible con XML.</dd>
</dl>
Rutas en HTML
Ruta Absoluta

<img src="https://www.example.com/images/logo.png" alt="Logo de Example">
Ruta Relativa

<img src="images/logo.png" alt="Logo de Mi Sitio">
Ejemplo de estructura de proyecto:

bash
Copiar código
/mi-sitio/
  index.html
  /images/
    logo.png
  /css/
    estilos.css
Enlaces <a>
Permiten crear vínculos entre documentos (hipertexto).

Enlace externo

<p><a href="https://m.joan23.fje.edu/" title="Joan XXIII">Jesuites Bellvitge – Joan XXIII</a></p>
Enlace interno (local)

<div id="menu">
  <a href="index.html" title="Inicio">Inicio</a>
  <a href="secciones/presentaciones.html" title="Fotos">Presentaciones</a>
  <a href="secciones/actividades.html" title="Actividades">Actividades</a>
</div>
Formularios
Sirven para recoger datos del usuario mediante campos y controles.

Etiqueta <form>

<form action="process.php" method="post" enctype="multipart/form-data">
  <label for="name">Nombre:</label>
  <input type="text" id="name" name="name">

  <label for="email">Correo electrónico:</label>
  <input type="email" id="email" name="email">

  <label for="file">Subir archivo:</label>
  <input type="file" id="file" name="file">

  <button type="submit">Enviar</button>
</form>
Atributos comunes:

action: URL de destino

method: get o post

enctype: codificación (para archivos)

target: _self, _blank, etc.

Etiqueta <input>
Tipos comunes:


<input type="text">
<input type="password">
<input type="checkbox">
<input type="radio">
<input type="file">
<input type="number">
<input type="date">
<input type="submit">
<input type="reset">
<input type="url">
Radio y Checkbox

<form action="/enviar-datos" method="POST">
  <fieldset>
    <legend>Selecciona tus intereses:</legend>
    <label><input type="checkbox" name="intereses" value="deportes"> Deportes</label>
    <label><input type="checkbox" name="intereses" value="música"> Música</label>
    <label><input type="checkbox" name="intereses" value="lectura"> Lectura</label>
  </fieldset>
  <button type="submit">Enviar</button>
</form>

<form action="/enviar-datos" method="POST">
  <fieldset>
    <legend>Selecciona tu género musical favorito:</legend>
    <label><input type="radio" name="genero" value="rock" required> Rock</label>
    <label><input type="radio" name="genero" value="pop"> Pop</label>
    <label><input type="radio" name="genero" value="jazz"> Jazz</label>
  </fieldset>
  <button type="submit">Enviar</button>
</form>
Select / Option

<select id="pais" name="pais">
  <option value="">Selecciona un país</option>
  <option value="es">España</option>
  <option value="mx">México</option>
  <option value="ar">Argentina</option>
  <option value="cl">Chile</option>
</select>
Textarea

<form action="/enviar-datos" method="POST">
  <label for="mensaje">Escribe tu mensaje:</label>
  <textarea id="mensaje" name="mensaje" rows="5" cols="40" placeholder="Escribe aquí tu texto..."></textarea>
  <input type="submit" value="Enviar">
</form>
Tablas
Estructura básica

<table border="1" width="100%">
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
Etiquetas principales:

<table> → define la tabla

<thead> → encabezado

<tbody> → cuerpo

<tfoot> → pie

Atributos comunes:

border

align

bgcolor

colspan

rowspan