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

SEM2a: Introducción a HTML

Se introduce a la sintaxis, estructura y etiquetas básicas de un documento HTML (body, html, title, p, h1…h6, listas numerada/no numerada y cómo añadir un icono de página), así como la estructura de carpetas de un sitio web.

Documentación:

Introducción a HTML y Fontawesome (resumen)

Fundamentos HTML (apuntes extendidos)

Mozilla Developer: HTML básico

HTML cheat sheet interactivo (ONLINE)

HTML cheat sheet (PDF)

Convertor PNG a ICO online convertICO

Insertar icono de pestaña en HTML

Qué es un favicon

Introducción a HTML

HTML (HyperText Markup Language) es el lenguaje de marcado estándar para crear páginas web.
Lenguaje más importante de Internet dado que sin HTML no se vería nada en el navegador.

HTML define la estructura y el contenido (es decir, si hay una imagen, una lista de elementos, un enlace, un párrafo, un titular, etc...) de las páginas web mediante etiquetas, es muy adaptable, tiene una estructura lógica y es muy fácil de entender e interpretar.
DESCRIBE EL CONTENIDO.

No se dedica a ver cómo se interactúa con el contenido (Javascript, PHP, etc...), ni se preocupa por la presentación o estilizado del contenido, es decir, de cómo se ve el contenido (para eso tenemos CSS).

Los elementos HTML son los bloques de construcción de las páginas HTML.

Cada elemento HTML está delimitado por etiquetas, como <body>, <head>, <p>, <h1>, etc.

Introducción a HTML

Las siglas de HTML corresponden con “HyperText Markup Language”, que tiene el siguiente significado:

HyperText, cuyo significado es hipertexto, que no es más que un texto que enlaza con otros contenidos, que pueden ser otro texto u otro archivo. Esto es la base del funcionamiento de la web tal y como la conocemos, que no es más que páginas y recursos interconectados.

Markup, que significa marca o etiqueta, ya que todas las páginas web están construidas en base a etiquetas, desde las primeras versiones hasta las últimas etiquetas de HTML5.
Un ejemplo de una etiqueta HTML es la que identifica a un párrafo, que se compone de la etiqueta, el contenido de la etiqueta y el cierre del párrafo: <p>HOLA</p>.

Language, cuyo significado es lenguaje, porque HTML es un lenguaje, es decir, tiene sus normas, tiene su estructura y una serie de convenciones que nos sirven para definir tanto la estructura como el contenido de una web.
Algo importante a tener en cuenta y con lo que no hay que confundirse, es que aunque HTML sea un lenguaje no quiere decir que sea un lenguaje de programación.
HTML no lo es, ya que no tiene estructuras de lenguaje de programación, como los bucles, las condiciones, las funciones, etcétera.

Introducción a HTML (elementos)

Es decir, que HTML no es un lenguaje de programación; es un lenguaje de marcado que define la estructura de su contenido. HTML consiste en una serie de elementos que usarás para encerrar diferentes partes del contenido para que se vean o comporten de una determinada manera.

Esto implica que la información a mostrar ha de ir “etiquetada” para formar elementos que el navegador web sepa interpretar de qué tipo de información se trata y cómo tal sepa cómo representarlos.

Las partes principales del elemento son:

La etiqueta de apertura: consiste en el nombre del elemento (en este caso, p), encerrado por paréntesis angulares < > de apertura y cierre. Establece dónde comienza o empieza a tener efecto el elemento —en este caso, dónde es el comienzo del párrafo—.

La etiqueta de cierre: es igual que la etiqueta de apertura, excepto que incluye una barra de cierre / antes del nombre de la etiqueta. Establece dónde termina el elemento —en este caso dónde termina el párrafo—.

El contenido: este es el contenido del elemento, que en este caso es sólo texto.

El elemento: la etiqueta de apertura, más la etiqueta de cierre, más el contenido equivale al elemento.

Introducción a HTML (atributos)

Los elementos pueden también tener atributos:

<p class="editor-note">Mi gato es muy gruñón</p>


Los atributos contienen información adicional acerca del elemento, la cual no quieres que aparezca en el contenido real del elemento. Aquí class es el nombre del atributo y editor-note el valor del atributo.
En este caso, el atributo class permite darle al elemento un nombre identificativo, que se puede utilizar luego para apuntarle al elemento información de estilo y demás cosas.

Los atributos siempre se incluyen en la etiqueta de apertura de un elemento y deben tener siempre:

Un espacio entre este y el nombre del elemento (o del atributo previo, si el elemento ya posee uno o más atributos).

El nombre del atributo, seguido por un signo de igual (=).

Comillas de apertura y de cierre, encerrando el valor del atributo.

Puedes también colocar elementos dentro de otros elementos. Esto se llama anidamiento.

Algunos elementos no poseen contenido, y son llamados elementos vacíos. Por ejemplo, el elemento

<img src="images/firefox-icon.png" alt="Mi imagen de prueba">


posee dos atributos, pero no hay etiqueta de cierre </img> ni contenido encerrado.

Estructura básica de un fichero HTML

Una página HTML básica incluye una declaración DOCTYPE, un elemento html, y dentro de este, un head y un body.

El head contiene metadatos y enlaces a hojas de estilo y scripts, mientras que el body contiene el contenido principal de la página web.

Un ejemplo de estructura básica de HTML (1/4)

Estructura:

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

<!DOCTYPE html> indica el tipo de documento. Es un preámbulo requerido.

<html></html> el elemento raíz.

<head></head> contenedor de metadatos (no visible en la página).

<body></body> contiene el contenido visible por los visitantes de la página.
Etiquetas básicas de HTML
Listas

Las listas desordenadas son aquellas en las que el orden de los ítems no es relevante, como en una lista de compras.
Estas son encerradas en un elemento <ul> (unordered list).
Se puede escoger el símbolo tipográfico indicándolo en la etiqueta <ul>.
Las opciones posibles son:

<ul type=DISC>

<ul type=SQUARE>

<ul type=CIRCLE>

Las listas ordenadas son aquellas en las que el orden sí es relevante, como en una receta.
Estas son encerradas en un elemento <ol> (ordered list).
Se puede escoger el tipo al enumerar una lista; por defecto es numérica y las otras opciones disponibles son:

A <ol type=A>

b <ol type=a>

III <ol type=I>

x <ol type=start=10>

1 <ol type=1>

Añadiendo el parámetro start=n se fuerza la numeración a partir de un determinado valor.
Añadiendo el parámetro value=n se fuerza a que el elemento tenga el número de orden que indiquemos.
Cada elemento de la lista se coloca dentro de un elemento <li> (list item).

Etiquetas básicas de HTML
Listas de definición

Las listas de definición se caracterizan por ser una enumeración de definiciones de términos.
Por lo tanto, los ítems de las listas de definición están formados por dos elementos: el término y su definición.

Para marcar el inicio y final de la lista usamos la etiqueta <dl> (definition list);
para cada uno de los términos se usa la etiqueta <dt> (definition term),
y para cada una de las definiciones se usa la etiqueta <dd> (definition description).

<dl>
  <dt>HTML</dt>
  <dd>Lenguaje de marcas diseñado para estructurar textos y relacionarlos en forma de hipertexto.</dd>

  <dt>XML</dt>
  <dd>Metalenguaje extensible de etiquetas. No es realmente un lenguaje en particular, sino una manera de definir lenguajes para diferentes necesidades.</dd>

  <dt>XHTML</dt>
  <dd>Lenguaje de marcas con las mismas funcionalidades que el HTML y que cumple con las especificaciones del XML.</dd>
</dl>

Etiquetas básicas de HTML

En HTML, cuando necesitamos enlazar a otros archivos (ya sean documentos HTML, hojas de estilo CSS o imágenes),
podemos usar rutas para especificar la ubicación de estos archivos.
Existen dos tipos de rutas: absolutas y relativas.

Ruta Absoluta

Una ruta absoluta especifica la ubicación completa del archivo en la web, comenzando desde el dominio.
Es útil cuando el archivo se encuentra en un servidor diferente o en una ubicación específica de la web.
Por ejemplo, si queremos enlazar a una imagen que está en un servidor externo, usamos una ruta absoluta:

<img src="https://www.example.com/images/logo.png" alt="Logo de Example">

Ruta Relativa

Una ruta relativa especifica la ubicación del archivo en relación con la ubicación del documento actual.
Es útil para mantener una estructura de enlaces clara dentro de un mismo sitio web.
Las rutas relativas pueden ser simples y facilitar el mantenimiento del sitio, especialmente cuando los archivos se trasladan o reorganizan.

Ejemplo de estructura:

/mi-sitio/
  index.html
  /images/
    logo.png
  /css/
    estilos.css


Para enlazar a la imagen logo.png desde el archivo index.html,
usarías una ruta relativa:

<img src="images/logo.png" alt="Logo de Mi Sitio">


En este caso, images/logo.png es una ruta relativa que indica que el archivo logo.png se encuentra en el directorio images dentro del mismo directorio que index.html.

Etiquetas básicas de HTML
Enlaces (<a>)

El éxito de la WWW (World Wide Web) es la capacidad de saltar de un documento a otro mediante enlaces.
El sistema que nos permite esta navegación se llama hipertexto.
La etiqueta HTML para crear estos enlaces es <a>.
Es una etiqueta de línea, ya que podemos colocar enlaces rodeados de texto.

Para indicar cuál es el destino de nuestro enlace usamos el atributo href.

Enlaces a páginas externas

Si queremos hacer un enlace a una página externa a nuestra aplicación web, como por ejemplo para enlazar al sitio web
https://m.joan23.fje.edu/, pero el texto que queremos que aparezca en el navegador es simplemente “Jesuites Bellvitge – Joan XXIII”.
El código que debemos introducir es el siguiente:

<p><a href="https://m.joan23.fje.edu/" title="Joan XXIII">Jesuites Bellvitge – Joan XXIII</a></p>

Enlaces a páginas locales

Si el enlace que queremos hacer está dirigido a un documento local nuestro, podemos usar la ruta relativa al archivo al cual queramos enlazar en el atributo href. Por ejemplo:

<div id="menu">
  <a href="index.html" title="Volver a la página de inicio">Inicio</a>
  <a href="secciones/presentaciones.html" title="Fotos de la web">Presentaciones</a>
  <a href="secciones/actividades.html" title="Actividades actuales">Actividades</a>
</div>

Formularios

Los formularios web nos sirven para interactuar con el usuario y para que este usuario pueda transmitirnos información.
Esta información se puede procesar de diferentes maneras según las necesidades de la aplicación web.

Técnicamente, un formulario no es más que un fragmento de código HTML que contiene unos elementos característicos llamados controles o campos.
Tenemos varios tipos de control: campos de texto, campos de contraseña, botones de opción (radio buttons), casillas de verificación (checkbox), campos para introducir archivos, listas de selección, áreas de texto y botones.

Cada uno de los controles de un formulario debe tener el atributo name, con el cual se identifica el dato que se quiere enviar.

Etiquetas de formularios (<form>)
TAG	Descripción	Atributos comunes	Ejemplo
<form>	Se utiliza para crear formularios que permiten al usuario enviar datos a un servidor o realizar alguna acción en una página web.	action: Define la URL donde se enviarán los datos del formulario para su procesamiento. Es el destino al que apunta el formulario.
method: Especifica el método de envío de datos.
enctype: Define cómo se codifican los datos antes de ser enviados al servidor. Se utiliza principalmente cuando se suben archivos.
target: Indica dónde se debe mostrar la respuesta al enviar el formulario:
• _self (por defecto): la respuesta se carga en la misma ventana.
• _blank: abre la respuesta en una nueva pestaña o ventana.	html <form action="process.php" method="post" enctype="multipart/form-data"> <label for="name">Nombre:</label> <input type="text" id="name" name="name"> <label for="email">Correo electrónico:</label> <input type="email" id="email" name="email"> <label for="file">Subir archivo:</label> <input type="file" id="file" name="file"> <button type="submit">Enviar</button> </form>
Etiquetas de formularios (<input>)
TAG	Descripción	Atributos comunes	Ejemplo
<input>	Se utiliza para crear diversos tipos de campos interactivos en un formulario.	type: Define el tipo de entrada que se desea mostrar.
id: Identificador único para el campo, que se puede usar para asociar el <label> con el campo de entrada.
name: Nombre del campo de entrada, que se utiliza al enviar el formulario.
value: Valor predeterminado del campo o el valor enviado al servidor si el campo no es interactivo.
placeholder: Texto que aparece en el campo cuando está vacío.
required: Indica que el campo debe completarse antes de enviar el formulario.
disabled: Desactiva el campo.
readonly: Hace que el campo sea solo de lectura.	html <input type="text"> <input type="password"> <input type="checkbox"> <input type="radio"> <input type="file"> <input type="number"> <input type="range"> <input type="date"> <input type="search"> <input type="submit"> <input type="reset"> <input type="url">
Etiquetas de formularios (input type radio y checkbox)
<input type="radio">	<input type="checkbox">
Botón de opción, se agrupa con otros de mismo nombre.	Casilla de verificación, permite selecciones múltiples.
html <form action="/enviar-datos" method="POST"> <fieldset> <legend>Selecciona tus intereses:</legend> <label><input type="checkbox" name="intereses" value="deportes">Deportes</label> <label><input type="checkbox" name="intereses" value="música">Música</label> <label><input type="checkbox" name="intereses" value="lectura">Lectura</label> </fieldset> <button type="submit">Enviar</button> </form>	html <form action="/enviar-datos" method="POST"> <fieldset> <legend>Selecciona tu género musical favorito:</legend> <label><input type="radio" name="genero" value="rock" required>Rock</label> <label><input type="radio" name="genero" value="pop">Pop</label> <label><input type="radio" name="genero" value="jazz">Jazz</label> </fieldset> <button type="submit">Enviar</button> </form>
Etiquetas de formularios (select/option)
TAG	Descripción	Atributos comunes	Ejemplo
<select>, <option>	Se utiliza para crear menús desplegables en los formularios. Permite al usuario seleccionar una opción de una lista de opciones predefinidas.	name: Especifica el nombre del control que se usará al enviar el formulario.
id: Identificador único del elemento.
size: Define el número de opciones visibles en la lista desplegable.
multiple: Permite seleccionar varias opciones a la vez.
value: Indica el valor de la opción.	html <select id="pais" name="pais"> <option value="">Selecciona un país</option> <option value="es">España</option> <option value="mx">México</option> <option value="ar">Argentina</option> <option value="cl">Chile</option> </select>
Etiquetas de formularios (textarea)
TAG	Descripción	Atributos comunes	Ejemplo
<textarea>	Se usa para crear un área de texto en la que los usuarios pueden ingresar múltiples líneas de texto. Es útil para mensajes largos o descripciones detalladas.	name: Especifica el nombre del control que se usará al enviar el formulario.
id: Identificador único.
rows: Define el número de líneas visibles.
cols: Define el ancho del área de texto.
placeholder: Texto de ayuda.
readonly: Solo lectura.
disabled: Desactiva el campo.	html <form action="/enviar-datos" method="POST"> <label for="mensaje">Escribe tu mensaje:</label> <textarea id="mensaje" name="mensaje" rows="5" cols="40" placeholder="Escribe aquí tu texto..."></textarea> <input type="submit" value="Enviar"> </form>
Etiquetas de Tablas (1/3)
TAG	Descripción	Atributos comunes	Ejemplo
<table>	Define el inicio de una tabla en HTML.	border: Define el grosor del borde.	<table border="1" width="100%">
<thead>	Agrupa el encabezado de la tabla.	No tiene atributos especiales.	
<tbody>	Agrupa el contenido principal de la tabla.	No tiene atributos especiales.	
<tfoot>	Agrupa el pie de la tabla, útil para resúmenes.	No tiene atributos especiales.	
Etiquetas de Tablas (2/3)
TAG	Descripción	Atributos comunes	Ejemplo
<tr>	Define una fila en la tabla.	align: Alinea el contenido en la fila (left, right, center).
bgcolor: Define el color de fondo de la fila.	<tr align="center" bgcolor="#efefef">
<th>	Define una celda de encabezado en una tabla. Por defecto el texto dentro de un <th> se muestra en negrita, alineado al centro.	colspan: Define cuántas columnas abarca la celda.
rowspan: Define cuántas filas abarca la celda.	<th colspan="2">
<td>	Define una celda de datos dentro de una fila de la tabla.	align: Alinea el contenido dentro de la celda (left, right, center).
rowspan: Abarca varias filas.	<td align="right" colspan="3">