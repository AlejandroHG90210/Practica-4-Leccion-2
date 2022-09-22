<html>
      <head>
        <!-- Required meta tags -->
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    
        <!-- Bootstrap CSS -->
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.3.1/dist/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    
        <title>Practica #4 Lab. Programacion Web</title>
      </head>
      <body>
        <nav class="navbar-expand-lg bg-light">
            <div class="container-fluid">
                <center> <b><h1>Laboratorio de Programacion Web</h1></b></center>
              </div>
            <div class="right">
              <div align="right">
                <a href="https://alejandrohg90210.github.io/index.github.io/">
                <input type="button" value="Click INDEX"/>
              </a>
            <h2><p align=left>Practica #4</p></h2> 
              </div>
     </div>
        </nav>
     <H3>ACTIVIDAD 4: LECCION 2 Conceptos básicos de HTML, XHTML y CSS </H3>
     <center><img src="p4.gif" width="400" height="150"></center>
<p><b>Objetivos: </b></p>
<p>En esta lección conocerás los conceptos básicos de HTML, XHTML y CSS. Juntos, estos tres sistemas de codificación conforman la estructura y el estilo visual de las páginas web.</p>
<p><b>Lenguajes Web</b></p>
<p>En esta lección vamos a conocer los elementos básicos de dos lenguajes: HTML y CSS. Aunque tienen distinta sintaxis y reglas, depende fuertemente uno del otro. Al finalizar esta lección podrás saber cómo crear paginas sencillas HTML, añadir imágenes, crear enlaces de una página a otra y modificar su aspecto en pantalla utilizando CSS. </p>
<p>Este tema es enormemente extenso y muchos de los principios básicos que se explican aquí te enseñarán a crear sitios web de calidad con los medios disponibles en este momento, al tiempo que te preparan para el futuro, al avanzar las nuevas funcionalidades de HTML5. </p>
<p><b>La estructura de la página web se basa en HTML</b></p>
<p>Los documentos HTML utilizan la extensión .htm o .html. Esta extensión avisa al navegador web o a un dispositivo como un teléfono móvil, que en este archivo hay contenido HTML y dicho contenido se restituye en la ventana del navegador o la pantalla del dispositivo siguiendo las reglas del lenguaje HTML.</p>
<p>Las etiquetas se utilizan para definir el contenido de una página HTML. Estas etiquetas quedan enmarcadas dentro de los símbolos &quot;menor que&quot; (&lt;) y &quot;mayor que&quot; (&gt;) y se ponen al principio y al final de un objeto o texto utilizado en la página HTML. Aquí vemos un ejemplo de dos etiquetas de título con textos en ellas. Las etiquetas no se muestran en pantalla, pero todos los navegadores saben que el texto entre las etiquetas es un título de primer nivel:</p>
<pre class="code">&lt;h1&gt;Welcome to Worldwide Apparel's intranet&lt;/h1&gt;</pre>
<p>En este ejemplo, el &lt;h1&gt; es la etiqueta de apertura, y &lt;/h1&gt; la etiqueta de cierre. A toda esta línea de código la denominamos &quot;elemento&quot;. Más concretamente, nos referiríamos a ella como un &quot;elemento de título de nivel 1&quot; o también &quot;elemento heading 1&quot; si preferimos utilizar el nombre en inglés original.</p>
<p>HTML y XHTML están estrechamente relacionados. Existe una lista de reglas definidas por el World Wide Web Consortium (organismo de normalización que también se conoce como W3C) que especifican los límites de HTML y XHTML.</p>
<p><b> Cómo se representa el código HTML en el navegador</b></p>

<p> Para entender mejor la relación entre el código HTML y lo que vemos en el navegador al abrir el archivo, en este ejemplo se muestra la conexión entre ambos: </p>
<ul>
<li><b> Doctype. </b>Esta línea indica al navegador que debe interpretar todo el código que sigue de acuerdo con un conjunto de reglas específico.</li>
<li><b> Elemento HTML. </b>Este elemento contiene a los demás y le indica al navegador que contiene un documento HTML. </li>
<li><b> Elemento HEAD. </b>En esta sección aparece información sobre la página, pero no se muestra en la pantalla. </li>
<li><b> Elemento TITLE. </b>Cualquier contenido dentro de las etiquetas "title" se muestra en la parte superior del navegador. </li>
<li><b> Elemento BODY. </b> Todo el contenido dentro del body se muestra en la ventana principal del navegador. </li>
<li><b> Elemento HEADING 1. </b>El primero de seis elementos de cabecera. </li>
<li><b> Elemento IMAGE: </b>enlaza a un archivo de imagen y la muestra en pantalla. </li>
<li><b> Elemento PARAGRAPH: </b>por defecto, el navegador añade un salto antes y después de este elemento, que suele contener varias líneas de texto.</li>
<li><b> Elemento STRONG: </b> el texto dentro de él se muestra en negrita.</li>
<li><b> Elemento ORDERED LIST: </b>abre una lista de elementos en forma de líneas numeradas por orden.</li>
<li><b>Elemento LIST: </b>cada línea con esta etiqueta recibe automáticamente un número ordinal empezando por el 1.</li>
</ul>
CONCLUSION
<p>En esta práctica pudimos ver algunos aspectos intermedios de las practicas anteriores de las lecciones de MSDN lo cual aquí pudimos ver algunos conceptos básicos los cuales son de gran ayuda debido que aquí te los explican de manera detallada lo cual te hace verlo de una manera más simple o sencilla para que tengas un conocimiento más claro de estos conceptos de los temas que son HTML, XHTML y CSS lo cual estos lenguajes tienen una similitud entre si al momento de utilizarlos en un documento para una página web, ya que unos son solamente adaptaciones para uno y otro lo cual todo este tema tiene una relación en cuanto a los lenguajes vistos.</p>
<p><b> Detalles de la sintaxis de XHTML</b></p>
<p>Hay una diferencia esencial entre HTML 4.0 y XHTML 1.0 – los dos estándares más recientes publicados por el W3C (World Wide Web Consortium). Tal y como está definido el XHTML, las páginas escritas en XHTML se pueden ver también en los navegadores que muestran las páginas HTML actuales. Las etiquetas y atributos de XHTML y HTML siguen siendo las mismas, pero la sintaxis del código XHTML es más estricta. </p>
<p>Las diferencias más importantes entre XHTML y HTML son estas:</p>
<ul>
<li>En XHTML, todas las etiquetas deben escribirse en minúsculas.</li>
<li>XHTML exige que todas las etiquetas de apertura lleven su correspondiente etiqueta de cierre, es decir, siempre debe existir una etiqueta al principio y otra al final de cualquier elemento, sea un título, párrafo, imagen u otro.</li>
<li>XHTML exige que el anidamiento de etiquetas (su inclusión unas dentro de otras), siga unas reglas estrictas. En el ejemplo siguiente, la etiqueta &lt;em&gt;, que se utiliza para enfatizar un texto, se abre dentro de la etiqueta de título &lt;h1&gt;. Por tanto, tiene que cerrarse antes de que se cierre el elemento &lt;h1&gt;:</li>
</ul>
<pre class="code">&lt;h1&gt; Esta es la intranet de &lt;em&gt;Worldwide Apparel&lt;/em&gt;. Bienvenido&lt;/h1&gt;</pre>
<p><b> Doctype indica al navegador qué debe esperar</b></p>
<p>Al inicio de toda página web debe aparecer una declaración Doctype. La declaración de &quot;tipo de documento&quot; le aporta pistas al navegador sobre el tipo de información que se va a encontrar en la página. Puesto que las especificaciones de HTML y XHTML son distintas, el navegador sabe así qué lenguaje va a interpretar y representar. El navegador restituye la página empezando por la primera línea y va avanzando de principio a fin, por lo que esta indicación en la primera línea de todas tiene pleno sentido. Aunque no es obligatoria, es una buena práctica empezar siempre utilizando doctype al principio de nuestras páginas. La declaración doctype en HTML 4.01 tiene este aspecto:</p>
<pre class="code">&lt;!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "<a href="http://www.w3.org/tr/html4/loose.dtd" data-linktype="external">http://www.w3.org/TR/html4/loose.dtd</a>"&gt;</pre>
<p>Cuando un navegador lee una declaración Doctype, espera que todo en la página sea conforme con el lenguaje indicado. Si la página es totalmente conforme con las especificaciones, se considera válida.</p>
<p><b>El W3C y la validación de la página </b></p>
<p>W3C es la abreviatura con la que se conoce al World Wide Web Consortium una organización sin ánimo de lucro cuyo objetivo consiste en orientar la evolución de la Web. El W3C ofrece directrices y reglas para especificaciones como HTML y XHTML. Una forma de definir la validez del código HTML o XHTML que generamos es utilizar el servicio online de validación del W3C, que es gratuito. </p>
<p>Ya que sabemos que una página utiliza un XHTML válido, sabemos también que si tenemos problemas al representarla en pantalla, no se deben al código XHTML. Sabemos que no faltan etiquetas y que todas ellas están bien escritas. </p>
<p> El proceso seguido puede ser útil para resolver errores, ya que nos facilita la detección de cualquier problema de sintaxis.</p>
<p><b> Otras ventajas del diseño basado en estándares</b></p>
<p> La validación de páginas del W3C es el aspecto más tangible de un diseño web conforme a estándares, pero hay también otras ventajas importantes al crear páginas bien estructuradas: </p>
<ul>
<li><b> Menos código: </b>el uso de HTML y CSS nos permite crear páginas similares con menos líneas de código, es decir, menos trabajo para el desarrollador y tiempos de descarga menores para el visor.</li>
<li><b> Mantenimiento más sencillo: </b>tener menos código supone un mantenimiento más sencillo, y esto beneficia tanto al que escribe el código como a cualquier otra persona que después deba encargarse de su mantenimiento y revisión. </li>
<li><b> Accesibilidad: </b> los documentos creados de forma semántica, es decir, que utilizan la etiqueta HTML más adecuada a su función en cada momento, pueden facilitar la lectura y navegación a personas con discapacidad visual y los usuarios que los visitan encuentran la información más fácilmente.</li>
<li><b> Optimización para motores de búsqueda: </b>Las páginas web que incluyen secciones claras e identificadas de forma lógica, tanto a nivel de código como de contenidos, facilitan la labor a los motores de búsqueda a la hora de indexarlas y clasificarlas puesto que con un contenido organizado y bien identificado resulta más fácil evaluar el contexto temático y la relevancia de la información que ofrecen. </li>
<li><b> Compatibilidad: </b>los sitios web que independizan la estructura con respecto al estilo se adaptan mucho más fácilmente a dispositivos móviles y formatos de pantalla variados. </li>
</ul>
<p><b>Estructura HTML</b></p>
<p>Uno de los conceptos más importantes que debemos dominar a la hora de diseñar contenidos web es la estructura anidada de los documentos HTML. Por lo general tenemos que empezar por diseñar la estructura HTML de la página para después continuar con los estilos, aplicando CSS.</p>
<p>En este ejemplo podemos ver los elementos más básicos que nos vamos a encontrar en prácticamente toda página web:</p>
<pre class="code">&lt;html&gt; <br/>     &lt;body&gt; <br/>     &lt;/body&gt; <br/>&lt;/html&gt;</pre>
<p>El elemento &lt;body&gt; está anidado (incluido) dentro del elemento &lt;html&gt;. En términos de programación, &lt;body&gt; está colocado entre la etiqueta de apertura &lt;html&gt; y la de cierre &lt;/html&gt;, y por eso decimos que las etiquetas anidadas son las que se encuentran entre otras etiquetas de apertura y cierre. Ambos elementos, &lt;body&gt; y &lt;html&gt;, forman la estructura básica de toda página web. </p>
<p>El contenido dentro de la etiqueta body es la parte visible de la página, ya que es lo que se muestra en la ventana del navegador.</p>
<pre class="code">&lt;html&gt;<br/>     &lt;body&gt;<br/><br/> Aquí están los recursos internos y el centro de información de los empleados de Worldwide Apparel<br/><br/>      &lt;/body&gt;<br/>&lt;/html&gt;</pre>
<p>En los documentos HTML parte del contenido se muestra en pantalla dentro de la ventana del navegador, pero hay otra parte del código que queda oculta, aunque es de gran utilidad para el navegador, para los motores de búsqueda y para el desarrollador. Algunos ejemplos de este código oculto son los scripts que sirven para añadir interactividad a la página, o también el código que ayuda a los buscadores a clasificar el documento, y los estilos que definen el aspecto de la página. Este código suele aparecer dentro del elemento &lt;head&gt;, el cual a su vez, está anidado dentro de las etiquetas &lt;html&gt;.
Un ejemplo:</p>
<pre class="code">&lt;html&gt;<br/>     &lt;head&gt;<br/>     &lt;/head&gt;<br/>     &lt;body&gt;<br/><br/> Aquí están los recursos internos y el centro de información de los empleados de Worldwide Apparel<br/><br/>      &lt;/body&gt;<br/>&lt;/html&gt;</pre>
<p>En este ejemplo, todavía no tenemos nada dentro del elemento &lt;head&gt;. Puedes ver que está anidado dentro del elemento &lt;html&gt;, pero no dentro del elemento &lt;body&gt;. El elemento &lt;head&gt; se abre y se cierra antes de que empiece el elemento &lt;body&gt;. Por su parte, el elemento &lt;body&gt; contiene texto, pero le falta un contexto y por ello los buscadores no podrán determinar si se trata de un título, una lista, un párrafo, un comentario o un contenido de cualquier otra naturaleza. Para definir el texto como párrafo, se utiliza la etiqueta &lt;p&gt;:</p>
<pre class="code">        &lt;html&gt;<br/>             &lt;head&gt;<br/>                  &lt;/head&gt;<br/>             &lt;body&gt;<br/>                 &lt;p&gt; The internal resource and information center for all employees of Worldwide Apparel &lt;/p&gt;<br/>             &lt;/body&gt;<br/>        &lt;/html&gt;</pre>
<p>El elemento paragraph ahora queda anidado dentro del elemento &lt;body&gt; que, a su vez, está anidado dentro del elemento &lt;html&gt;.</p>
<p><b> Insertar imágenes en HTML</b></p>
<p>Para colocar imágenes dentro de un documento HTML se utiliza la etiqueta <img>. Al igual que ocurre con la etiqueta <a>, la etiqueta de imagen por sí sola no hace nada. Depende del valor de los atributos que especifiquemos, que indican qué imagen se debe mostrar y cómo ha de hacerse.</p>
<p>Aquí te mostramos como insertar una imagen en un documento HTML</p>
<ol>
<li>Mueve el cursor hacia el primer párrafo y sitúalo inmediatamente después de la etiqueta de cierre &lt;/p&gt;. Pulsa Intro para pasar a la línea siguiente. Escribe &lt;img /&gt;</li>
<p>La etiqueta de imagen es una categoría especial dentro de las etiquetas HTML, de las que admiten el autocierre. No necesitamos escribir por separado etiqueta de apertura y cierre: con una sola es suficiente, pero es importante que la escribamos bien. Así se cumplen los requisitos de sintaxis de XHTML y el archivo de imagen que vamos a utilizar se indicará en el espacio que queda entre img y /.</p>
<li>Mueve el ratón a la derecha de la palabra img, inserta un espacio en blanco y escribe src=&quot;&quot;.</li>
<p>src es la abreviatura del atributo source (origen), y tenemos que indicar un valor para él, que es la dirección URL de la imagen que queremos mostrar dentro de la página.</p>
<li>En el interior de las comillas de src= escribe images/familysitting.jpg.</li>
<p>El código quedaría así:</p>
<pre class="code">&lt;img src="images/familysitting.jpg" /&gt;</pre>
<p>Esta línea le indica al navegador que busque dentro de la carpeta images y presente en pantalla el archivo familysitting.jpg.</p>
<p>El atributo alt representa el texto alternativo a la imagen, y es obligatorio añadirlo para mantener la validez de la página. Este atributo es muy útil para las personas que utilizan sistemas de lectura de pantalla para navegar por la Web, ya que permite convertir a voz el texto indicado como valor. También sirve para dar un contenido al espacio vacío que se genera cuando, por cualquier razón, la imagen no se puede representar.</p>
<li>Sitúa el cursor a la derecha de la comilla de cierre que sigue al nombre de archivo familysitting.jpg e inserta un espacio en blanco, y después escribe alt=&quot;&quot;.</li>
<li>Dentro de las comillas del paso anterior, escribe Familia sentada en unos escalones.</li>
<li>En el menú Archivo, selecciona Guardar y después abre el archivo en el navegador.</li>
<p>Tanto el atributo src como el alt son obligatorios bajo XHTML. Hay también otros atributos, opcionales, que podemos utilizar.</p>
<li>Regresa al editor de textos y pon el cursor a la derecha de las últimas comillas que siguen al atributo alt, inserta un espacio y escribe lo siguiente: width=&quot;296&quot; height=&quot;250&quot;. Estos dos atributos indican al navegador las dimensiones que tendrá esta imagen en pantalla (ancho y alto respectivamente).</li>
</ol>
<p>El empleo de atributos opcionales</p>
<p>Muchos de los atributos opcionales se encuadran dentro de lo que se denomina &quot;buenas prácticas&quot;. Las buenas prácticas son un concepto amplio, que se utiliza para describir la manera generalmente aceptada de hacer las cosas en el diseño y programación para la Web. Hay, en general, razones de sentido común detrás de las buenas prácticas: por ejemplo, al indicar la altura y la anchura se crea un espacio para la imagen, y permanece aún en el caso de que la imagen no se haya descargado, debido a la lentitud de la conexión. Si no se crea este placeholder con una anchura y altura prefijadas, el aspecto y distribución de los elementos en pantalla va cambiando a medida que se cargan las imágenes.</p>
<p><b>El papel de CSS </b></p>
<p>CSS (Cascading Style Sheets) utiliza un lenguaje distinto de HTML. CSS nos permite aplicar estilos de manera coherente a los distintos elementos de las páginas del sitio web, de modo que los títulos, listas y párrafos pueden verse igual en todas y cada una de las páginas.</p>
<p><b>Definir un estilo para los títulos</b></p>
<p>Para hacernos una idea de cómo funciona CSS vamos a crear una regla CSS sencilla que cambia el estilo de un título en la página. En el archivo 02_index_work.html ya tenemos el texto &quot;Welcome to Worldwide Apparel's intranet&quot; dentro de una etiqueta &lt;h1&gt;. Puede que una de las mejores maneras de entender la acción de CSS sea ver cómo se aplica el estilo por defecto para este título al escribirlo en pantalla.</p>
<ol>
<li>Dentro del navegador, analiza el texto de título. El estilo y las instrucciones de formato las aportan las &quot;reglas&quot; que el propio navegador aplica por diseño a los elementos &lt;h1&gt; a la hora de presentarlos en pantalla. El tamaño, color y tipo de letra los resuelve el navegador ya que no dispone de otras instrucciones de formato.</li>
<li>En la parte superior de la página busca la etiqueta &lt;title&gt;, y justo debajo de ella, añade una línea nueva, con el siguiente texto:</li>
<pre class="code">
  &lt;style type="text/css"&gt;
</pre>
<li>Pulsa Intro tres veces y después escribe &lt;/style&gt;. En este momento tenemos un elemento de estilo sin contenido alguno, pero nos servirá para insertar ahí una regla con la que vamos a modificar el estilo del elemento &lt;h1&gt;. </li>
<p>El elemento &lt;style&gt; queda dentro de las etiquetas delimitadoras de la cabecera &lt;head&gt; de la página. En HTML todo lo que queda dentro de la sección &lt;head&gt; no se muestra en pantalla. Por ejemplo, también tenemos un elemento &lt;title&gt; en esta sección. Este título aparece en la parte superior de la ventana del navegador, pero no dentro de la página propiamente. </p>
<li>En la línea vacía que hay debajo de la etiqueta de apertura &lt;style&gt;, escribe esto: </li>
<pre class="code">
  h1 {
</pre>
<p>Este es el selector, el que nos dice a qué elemento de HTML queremos aplicar el estilo, y en este caso es el elemento heading 1.</p>
<li>Pulsa Intro y después el tabulador para poner el cursor debajo del signo de la llave en el editor, si es que el propio editor no te posiciona automáticamente en ese lugar. La tabulación es opcional, pero hace que el código CSS se lea mejor.</li>
<li>Escribe este código debajo de h1 {:</li>
<pre class="code">
  color: red;
</pre>
<p>La palabra color se denomina como una propiedad en la sintaxis CSS y la palabra red es el valor que le aplicamos a esa propiedad.</p>
<li>Pulsa Intro otra vez y en la línea siguiente escribe el signo } y ahora tenemos una regla con estas tres líneas:</li>
<pre class="code">
  h1 {<br/>                 color:red;<br/>}
</pre>
<li>Guarda el archivo en disco y visualiza la página en el navegador. La cabecera aparece ahora en color rojo y eso nos indica que hemos escrito bien la regla CSS.</li>
</ol>
<p><b>Notación hexadecimal de color</b></p>
<p>El color, tanto en HTML como CSS, se designa mediante un código de seis caracteres precedido por el signo de almohadilla. A esta notación se le llama código hexadecimal, y es el sistema que se utiliza para identificar y establecer el color de los elementos. Con esta notación podemos reproducir prácticamente cualquier color. Por ejemplo, el color rojo oscuro se representa como #CC0000.</p>
<p>El código se divide en tres pares de dígitos, y cada uno de ellos representa el valor RGB del espectro. Por ejemplo, el color blanco se representa en notación RBG como R:255 G:255 B:255, y su equivalente en HTML en formato hexadecimal es #FFFFFF (siendo FF el equivalente hexadecimal del número 255 decimal, que se repite para los tres pares). Un programa de edición de imágenes como Photoshop nos permite elegir un color concreto de una paleta y obtener directamente su equivalente RGB, tanto decimal como hexadecimal, para insertarlo en una regla CSS.</p>
<p>La regla que acabamos de crear emplea lo que se conoce como &quot;selector de tipo&quot;, puesto que se aplica a todas las apariciones del elemento tipo h1 en el documento. Los selectores de tipo asignan propiedades CSS a cualquier etiqueta HTML del documento. En este caso, a la etiqueta &lt;h1&gt;. Todas las apariciones de &lt;h1&gt; se mostrarán en pantalla con el texto en rojo. Los selectores de tipo también se les suele denominar &quot;selectores de etiqueta&quot;.</p>
<p><b>Los estilos de clase y el elemento &lt;span&gt;</b></p>
<p>Los selectores de etiqueta se utilizan con mucha frecuencia, pero solo se pueden aplicar a elementos HTML. Cuando lo que queremos es modificar el estilo de alguna cosa que no coincide exactamente con una etiqueta, por ejemplo cambiar el color de una única palabra dentro de un párrafo, el selector de etiqueta no es una buena opción. En este caso podemos utilizar el selector de clase, que es una regla CSS que se puede aplicar a cualquier elemento dentro de una página. Los selectores de clase tienen unas opciones de nomenclatura flexibles, pero es muy conveniente utilizar nombres que describan adecuadamente lo que hacen. Por ejemplo, podemos crear selectores de clase como .caption, .imageborder, o .redtext.</p>
<p><b>Tres maneras de utilizar estilos</b></p>
<p>Esta modalidad recibe el nombre de hoja de estilos interna. Además de hojas de estilo internas, también existen las hojas de estilos externas y los estilos aplicados directamente (&quot;inline&quot;).</p>
<p>Una hoja de estilo externa es un documento independiente con la extensión .css. Cuando utilizamos un archivo externo, los estilos se definen en él y en las páginas HTML tenemos que insertar un enlace a dicho archivo. Mientras que las hojas de estilo internas solo se aplican a la página donde residen, las hojas externas se pueden aplicar a múltiples documentos HTML.</p>
<p>Los estilos inline o directos son la tercera posibilidad pero se utilizan mucho menos que las otras dos. En este caso, las reglas se declaran dentro de las propias etiquetas HTML.</p>
<p>Los estilos directos son herramientas potentes porque se superponen tanto a los estilos internos como a los externos, aunque solamente se aplican a una etiqueta cada vez. Por su propia naturaleza, resulta complicado reutilizarlos. Si tuviéramos 50 elementos &lt;h1&gt; en nuestro sitio web y utilizásemos estilos inline, necesitaríamos añadir este código de estilo 50 veces, pero lo peor es que si quisiéramos cambiar el color a verde, tendríamos que buscar las 50 apariciones de este estilo y remplazar la palabra "red" por "green". Los estilos inline son útiles para aplicaciones puntuales o cuando no podemos utilizar una hoja de estilos interna o externa.</p>
<p><b>Cuándo utilizar hojas de estilo internas y externas </b></p>
<p>En las hojas de estilo internas, las reglas CSS quedan escritas directamente dentro del documento utilizando la etiqueta &lt;style&gt;. La hoja de estilos queda ubicada dentro de la sección &lt;head&gt; del documento.</p>
<p>En el caso de las hojas internas, las reglas CSS solo se aplican al documento en donde residen. Por ejemplo, si tenemos un sitio web con 20 páginas y decidimos utilizar hojas de estilo internas, deberemos crear una hoja de estilos dentro de cada una de esas 20 páginas. Un cambio en cualquier regla exigiría modificar todas y cada una de las hojas de estilo internas en dichas páginas para mantener la consistencia.</p>
<p>En las hojas externas las reglas CSS, se guardan en archivos independientes. Podemos asociar un mismo archivo .css a cualquier página HTML, y con ello nos ahorraremos mucho trabajo y ganamos en flexibilidad. Si definimos una regla para el elemento &lt;p&gt; en una hoja de estilo externa, todos los párrafos del sitio web quedan modificados de inmediato.</p>
<p><b>Creación de una hoja de estilos externa</b></p>
<p>Una página HTML no tiene por qué limitarse a utilizar solamente una hoja de estilos externa, y en muchos sitios web de grandes dimensiones, las definiciones de estilos suelen repartirse entre varios archivos, para facilitar su organización y mantenimiento. Podemos incluso utilizar hojas de estilos para funciones concretas, como imprimir una página o visualizar el contenido en dispositivos móviles. Se pueden diseñar hojas de estilo también para que nuestros sitios web sean compatibles con navegadores antiguos.</p>
<ol>
<li>Desde el menú Archivo – Nuevo, selecciona la Plantilla de Estilos CSS y ábrela si tu editor web ofrece esta opción.</li>
<li>Desde el menú Archivo, selecciona "Guardar como" y ponle al archivo el nombre styles.css, y lo guardas dentro de la carpeta HTML5_02lessons folder. Una hoja de estilos CSS lleva la extensión .css, pero en realidad se trata de un archivo de texto plano.</li>
<li>Pasa ahora al documento HTML que hemos utilizado en el último ejercicio (02_index_work.html), pero mantén abierta también la hoja de estilos.</li>
<li>En el documento HTML busca las reglas que has escrito dentro de las etiquetas &lt;style&gt; y selecciónalas con el ratón. No selecciones las etiquetas &lt;style&gt; y &lt;/style&gt;, solo las reglas, a partir de h1 y hasta encontrar el último signo de llaves de cierre (}).</li>
<li>En el menú Edición selecciona Cortar y pasa ahora al archivo styles.css. Si en este archivo aparece algún código, tendrás que sobrescribirlo seleccionándolo y después pegando  las reglas que acabas de seleccionar. Guarda el archivo en el disco.</li>
<p>La hoja de estilos externa funciona como sustituta de las etiquetas &lt;style&gt; del documento HTML.</p>
<li>En el editor, vuelve al archivo 02_index_work.html y guárdalo en disco. Ahora vamos a añadir la etiqueta &lt;link&gt; que apuntará a nuestro archivo styles.css. Este paso es fundamental porque si no vinculamos la hoja de estilos externa, la página HTML se mostrará sin aplicar esos estilos.</li>
<li>Pon el cursor detrás de la etiqueta de cierre &lt;/ style&gt; y pulsa Intro para empezar a escribir en la línea siguiente. Escribe esto: </li>
<pre class="code">
  &lt;link rel="stylesheet" type="text/css" href="styles.css" /&gt;
</pre>
<li>Selecciona Archivo – Guardar y visualiza la página HTML en el navegador. La página debe verse igual que antes, ya que estamos utilizando los mismos estilos. Simplemente ocurre que se aplican desde fuera del documento.</li>
<li>Vamos a crear un nuevo documento HTML y le añadiremos el mismo enlace al archive CSS externo, para ver cómo se aplican las reglas.</li>
<li>Desde el menú Archivo, abre el archive test.html que está en la carpeta HTML5_02lessons. Es un documento que no contiene nada.</li>
<li> Sin salir del editor, vuelve al archivo 02_index_work.html y selecciona todo el elemento &lt;link&gt;</li>
<pre class="code">
  &lt;link rel="stylesheet" type="text/css" href="styles.css" /&gt;
</pre>
<li> Vuelve al documento  test.html, pulsa debajo del elemento &lt;title&gt; y pega (Edición- Pegar) para que añadir la línea anterior.</li>
</ol>
<p><b> En qué consisten los estilos en cascada</b></p>
<p>Hemos visto que hay tres sitios donde podemos indicar reglas CSS: dentro de la propia etiqueta (inline), internamente y en archivos externos asociados. Si surgiera algún conflicto en la definición de estilos entre las declaraciones inline, interna y/o externa, el estilo directo (inline) será el que prevalezca porque es el que más cerca se sitúa del código HTML. La hoja de estilo interna tiene precedencia sobre cualquier otra externa, y las definiciones utilizadas en hojas de estilo externas se utilizan solo si no entran en conflicto con las declaraciones internas o directas.</p>
<p><b>Uso de textos y tipos de letra en la web</b></p>
<p>A la hora de diseñar para la web, podemos formatear el texto de una forma parecida a como se hace en las aplicaciones de procesamiento de textos y diseño publicitario de los equipos de escritorio, pero debemos tener en cuenta algunas diferencias importantes. Cuando especificamos el uso de una fuente concreta, esta fuente ha de estar instalada en el ordenador o el dispositivo del usuario donde se va a restituir la página. Si el ordenador o dispositivo no dispone de esa fuente, el navegador la sustituye por otra.</p>
<p>Puesto que es imposible saber qué fuentes están instaladas en los ordenadores de los usuarios, y debido a la capacidad que tienen los navegadores para sustituir unos tipos de letra por otros, es posible que los resultados obtenidos en ciertos equipos no se correspondan con el diseño que hemos previsto.</p>
<p><b>Tipos de letra de uso común en la web</b></p>
<p>Estas son las Fuentes que podemos utilizar con más confianza en la Web:</p>
<ul>
<li>Arial</li>
<li>Verdana</li>
<li>Georgia</li>
<li>Times New Roman</li>
<li>Courier</li>
<li>Trebuchet</li>
<li>Lucida</li>
<li>Tahoma</li>
<li>Impact</li>
</ul>
<p>La lista es pequeña porque tiene en cuenta las plataformas Mac y Windows y suponemos además que aún acceden a la web muchos ordenadores antiguos.</p>
<p>Una de las soluciones que nos puede ayudar a resolver la falta de tipos de letra variados en la Web es el uso de una &quot;pila&quot; de fuentes, (&quot;font stack&quot; en inglés). En CSS, la pila de fuentes es una lista de varios tipos de letra que puede utilizar el navegador para mostrar texto en pantalla.</p>
<p>Aquí vemos un ejemplo de pila de fuentes CSS:</p>
<pre class="code">font-family:"Helvetica Neue", Helvetica, Arial, sans-serif;</pre>
<p><b>Elección de font-family</b></p>
<p>En este ejercicio vamos a definir una lista de fuentes para toda la página y después declararemos una lista específica para los títulos.</p>
<ol>
<li>Vamos a modificar el estilo del texto en esta página, pero dado que nuestros estilos están ahora declarados en una hoja de estilos externa, tendremos que realizar estas modificaciones en dicha hoja.</li>
<li>Volvamos a nuestro documento <strong>styles.css</strong> que hemos creado en el ejercicio anterior. Ahora mismo tenemos estilos para la etiqueta h1 y para una clase llamada &quot;.red&quot;.</li>
<li> En la parte superior del documento, por encima de la regla del estilo h1, escribe:</li>
<pre class="code">
     body {<br/>font-family:"Trebuchet MS", Tahoma, Arial, sans-serif;<br/>}
</pre>
<li> Guarda el archivo (Menú Archivo – Guardar) y visualiza la página 02_index_work.html en el navegador. Como decíamos antes, el navegador muestra el tipo de letra Trebuchet si la tenemos instalada en el equipo; en caso contrario, lo intenta primero con Tahoma, luego con Arial y finalmente, con cualquier tipo de letra sans-serif.</li>
<li> Vuelve a la hoja de estilos en el editor y debajo justo de la regla para el &quot;body&quot;, añade una nueva regla de estilo para la etiqueta &lt;p&gt; con este contenido:</li>
<pre class="code">
    p {<br/>font-family:Georgia, "Times New Roman", Times, serif;<br/>}
</pre>
<li> Guarda de nuevo el documento y visualiza el archivo 02_index_work.html en el navegador.</li>
</ol>
<p><b>El prometedor futuro de las fuentes</b></p>
<p>La escasez de opciones a la hora de utilizar distintas fuentes en la web ha causado frustración entre los diseñadores Web durante muchos años. Este problema va aliviándose a medida que ciertas empresas han ido creando soluciones para que las páginas puedan verse en un navegador con los tipos de letra especificados por los creadores.</p>
<p>El panorama de las fuentes está cambiando, sin embargo, con la aparición de las llamadas &quot;web fonts&quot; y, en concreto, con la funcionalidad @font-face de CSS. Ahora es posible añadir una gran variedad de tipos de letra y tener la certeza de que nuestras páginas se podrán ver tal y como pretendemos.</p>
<p><b>Cambiar el tamaño del texto con CSS</b></p>
<p>Cuando utilizamos CSS para formatear textos para la web, disponemos de algunas opciones para establecer su tamaño y su grosor. La propiedad CSS que controla el tamaño del texto se llama font-size.</p>
<p>Podemos modificar el valor de la propiedad font-size de varias formas:</p>
<ul>
<li><b>Tamaño absoluto:</b> se trata de una serie de palabras clave que indican tamaños predefinidos de letra. Los tamaños nominados escalan de acuerdo con las preferencias del usuario con respecto a la letra. Los valores posibles xx-small, x-small, small, medium, large, x-large y xx-large.</li>
<li><b>Longitud:</b> Es un número seguido de un indicador del sistema de medida (cm, mm, in, pt, o pc) o bien un de unidades relativas (em, ex, o px).</li>
<li><b>Porcentaje:</b> Un entero seguido del signo de porcentaje (%). El valor es un tanto por ciento del tamaño de letra del objeto padre.</li>
<li><b>Tamaño relativo</b>: una serie de palabras clave que se interpretan como relativas al tamaño de letra del objeto padre. Los valores posibles son larger y smaller.</li>
</ul>
<p>La elección de la unidad de medida para el tamaño de la letra en una página web es importante y no es tan fácil como parece. La principal dificultad en este sentido tiene que ver con la resolución de la pantalla y las distintas maneras en que, a lo largo del tiempo, los navegadores han resuelto la presentación de los textos.</p>
<p>El texto en monitores pequeños a menudo tiene un aspecto distinto de como aparecen en monitores de gran formato; con un poco de previsión podemos resolver este problema, imaginando el efecto en cada caso.</p>
<p><b>Las medidas en pixels y puntos no son la mejor opción para el tamaño </b></p>
<p>Seguramente te manejarás muy bien usando los pixels como unidad de medida. La propiedad font-size en CSS nos permite utilizar ambas unidades. En el siguiente ejemplo, el selector CSS muestra una regla de párrafo con puntos y la segunda, una regla de párrafo basada en pixels:</p>
<pre class="code">p {<br/>   font-size:12pt;<br/>  }</pre>
<p>(regla CSS de tamaño de letra basada en puntos)</p>
<pre class="code">p {<br/>   font-size:12px;<br/>  }</pre>
<p>(regla CSS de tamaño de letra basada en pixels)</p>
<p>Aunque la unidad "points" está soportada, su uso es una mala práctica y no se recomienda en el diseño de páginas Web. Los puntos son un sistema de medida pensado para la imprenta de papel que indica una unidad absoluta de medida que no tiene una equivalencia exacta en pantalla. Los pixels, por su parte, son la unidad de medida que se suele emplear en los gráficos por ordenador. Los tamaños y resoluciones de pantalla se expresan en pixels.</p>
<p><b> Uso de una combinación de porcentaje y medida &quot;em&quot;</b></p>
<p>Una forma de resolver el problema del cambio de tamaño de los textos que causa el uso de pixels consiste en aplicar otras unidades de medida.</p>
<p>Una unidad de medida es el small:</p>
<pre>font-size:small;</pre>
<p>El valor "small" es una unidad de medida absoluta, llamada "palabra clave". Los navegadores web tienen tamaños predefinidos asignados a las palabras clave y, aunque algunos prefieren las palabras clave porque así se evitan tener que usar unidades</p>
<pre>font-size:100%</pre>
<p>Este paso nos sirve para definir expresamente que el tamaño de letra para el cuerpo es el mismo que tiene predefinido el navegador.</p>
<pre>p {
 font-size:1 em;
 }
</pre>
<p>La unidad de medida llamada "em" es muy parecida a los pixels en el sentido de que está pensada para variar la escala. La diferencia principal es que los "ems" no dependen de la resolución del monitor, mientras que los pixels sí</p>
<pre>1 em = 100% = 16 pixeles</pre>
<p>Aquí tenemos que el tamaño de letra para el párrafo es de 1em, el tamaño de fuente para el cuerpo es 100% y el tamaño de fuente por defecto para el navegador es de 16 pixels.</p>
<p><b> Auto estudio</b></p>
<ol>
<li>Añade otro título debajo del último párrafo en el archivo 02_index_work.html con esto:</li>
<pre class="code">
    &lt;h2&gt; Worldwide Apparel volunteer opportunities &lt;/h2&gt;  
</pre>
<li>Crea un estilo para la etiqueta en tu hoja externa de estilos que defina este rótulo con letra de color naranja.</li>
</ol>
<p><b>Repaso</b></p>
<ol>
<li><b>¿Qué es un doctype y qué relación tiene con la validación de las páginas web?</b></li>
<p>Un doctype es una declaración que se hace al principio de los documentos HTML. Los navegadores web la utilizan para saber qué lenguaje de markup y qué versión se utilizan en la página. La validación de páginas comprueba la conformidad de la sintaxis del código respecto de las especificaciones del doctype declarado. La validación de las páginas es una buena opción para detectar problemas como etiquetas que faltan o errores de tipografía en el código.</p>
<li><b>En el siguiente código XHTML, ¿cuál es el atributo y qué valor tiene? ¿Qué otros atributos podríamos encontrar con frecuencia en un elemento img como este?</b></li>
<pre class="code">&lt;img src="images/familysitting.jpg"/&gt;</pre>
<p>En esta línea de código, el atributo es src y su valor es &quot;images/familysitting.jpg&quot;. El atributo src y su valor están anidados dentro de la etiqueta &lt;img&gt;. Este atributo contiene un vínculo a un archivo de imagen que se mostrará en pantalla. Otros ejemplos de atributos para imágenes son alt, que aporta un texto alternativo a la imagen para uso en dispositivos como sintetizadores de voz o lectores de pantalla, y los atributos width y height, que indican el tamaño que debe tener la imagen dentro de la página.</p>
<li><b>Indica la finalidad de las hojas de estilo externas y alguna de las ventajas que ofrece su utilización.</b></li>
<p>Una hoja de estilos CSS externa es un documento de texto con extensión .css. Este documento contiene reglas CSS que definen el aspecto de los elementos HTML. Puesto que las hojas de estilos externas se pueden asociar a múltiples páginas web, nos permiten disponer de un lugar centralizado para la definición de estilos de todo un sitio web. Una de las ventajas es que podemos modificar el aspecto de todo el sitio web con un solo cambio en una regla CSS. Otras ventajas pueden ser la posibilidad de utilizar múltiples hojas de estilos para facilitar su mantenimiento posterior e indicar hojas de estilo específicas para imprimir el documento o para optimizar su presentación en dispositivos móviles.</p>
</ol>
<p><b>Preguntas de la Practica</b></p>
<ol>
<li><b>¿Que es un XML y para qué sirve?</b></li>
<p>Es un lenguaje de marcado y sirve para definir un conjunto de reglas para la codificación de documentos.</p>
<li><b>¿Que características tiene un documento HTML?</b></li>
<ul>
<li>Puede ser creado y editado con cualquier editor básico de textos.</li>
<li>Es multiplataforma, o sea, puede ser visualizado por cualquier navegador de cualquier sistema operativo.</li>
<li>No diferencia entre mayúsculas y minúsculas.</li>
<li>Utiliza etiquetas o marcas, que consisten en breves instrucciones de comienzo y final, mediante las cuales se determina la forma en la que debe aparecer en su navegador el texto así como también las imágenes y demás elementos en la pantalla del ordenador.</li>
<li>Cada elemento de un documento HTML consta de una etiqueta de comienzo, un bloque de texto y una etiqueta de fin.</li>
<li>Lenguaje estático.</li>
<li>Es utilizado para la creación de páginas web.</li>
<li>Los documentos HTML son documentos de hipertexto que aparecen enlazando a otros documentos.</li>
<li>Es un estándar reconocido por todo el mundo y cuyas normas define un organismo sin animo de lucro llamado World Wide Web Consortium, más conocido como W3C.</li>
</ul>
<li><b>¿Qué es y para qué sirve un archivo XHTML?</b></li>
<p> Es una reformulación del lenguaje HTML que ahora pasa a ser compatible con el estándar XML, considerándose que se incluye en la familia de los Lenguajes de Marcado y este se utiliza para generar documentos y contenidos de hipertexto generalmente publicados en la Web.</p>
</ol>
 <br>
        <br>
        <h4> Conclusiones </h4>
        <br>
        <b><p>Diego Alberto Oliva Gonzalez </p></b>
        <p>Para esta practica aprendimos la estructura del html,a como insertar imagenes y los estilos que un html puede manejar, esto nos sirve mucho de conocimiento ya que podemos aplicarlos para futuros proyectos qje tengamos y podamos hacer todo con una mayor facilidad con los conocimientos que adquirimos anteriormente con esta lectura</p>
        <b><p>Edrik Alejandro Hernandez Garcia </p></b>
        <p>En esta práctica pudimos ver algunos aspectos intermedios de las practicas anteriores de las lecciones de MSDN lo cual aquí pudimos ver algunos conceptos básicos los cuales son de gran ayuda debido que aquí te los explican de manera detallada lo cual te hace verlo de una manera más simple o sencilla para que tengas un conocimiento más claro de estos conceptos de los temas que son HTML, XHTML y CSS lo cual estos lenguajes tienen una similitud entre si al momento de utilizarlos en un documento para una página web, ya que unos son solamente adaptaciones para uno y otro lo cual todo este tema tiene una relación en cuanto a los lenguajes vistos.</p>	
        <b><p>Carlos Alberto Salazar Beltran </p></b>
        <p>Como conlucion sobre estos conceptos basicos de HTML, XHTML Y CSS son importente ya estos codigos sirben para loselemento muy importante del lenguaje HTML son los atributos de cada etiqueta, que representan opciones que modifican su comportamiento por defecto. Los atributos se incluyen junto con la etiqueta correspondiente, dentro de los símbolos &lt;&gt;. Las etiquetas de final nunca incluyen atributos. </p>
        <b><p>Jesus Ruben Balleza Rojas </p></b>
        <p>Esta practica estuvo muy interesante, y a la ves me sirvio como recordatorio, porque te vienen explicando todo lo de HTML y la diferencia con XHTML. La practica me sirvio para recordar  porque te explican desde lo mas basico, cosa que ya habia visto en la clase de programacion web, mas sin embargo, vienen cosas que yo en lo personal desconocia, como por ejemplo las medidas, ya que yo siempre he trabajado con pixeles, desocnocia los puntos  y a la propiedad font.size que son muy utiles, en especial esta ultima al momento de desarrollar paginas web.</p>
        <b><p>Diana Nahomi Santos Ortega  </p></b>
        <p>En esta práctica nuevamente obtuvimos nuevos conocimientos muy interesantes como en las practicas anteriores ya que cada una se conecta en cierta forma con la otra y nos permite comprender con mayor facilidad cada uno de los conceptos que se muestran detalladamente abarcando los temas del HTML, XHTML y CSS, gracias a eso es como nosotros estamos aclarando cada vez mas nuestras dudas y poniendo en practica todo lo aprendido que es una de las cosas más importantes. </p>
        <br>
        <br>
            <h4>Elaborado por:</h4>
            <table class="default">
              <div class="container-fluid">
                  <tr>
                    <b>
                    <th><h5>Nombre:</h5></th>
                    <th><h5><center>Hora</center></h5></th>
                  </b>
                  </tr>
                  <tr> 
                    <td>Edrik Alejandro Hernandez Garcia</td>
                    <td><center>M5</center></td>
                  </tr>
                  <tr>
                    <td>Diego Alberto Oliva Gonzalez</td>
                    <td><center>M5</center></td> 
                  </tr>
                  <tr>
                      <td>Diana Nahomi Santos Ortega</td>
                      <td><center>M5</center></td>
                  </tr>
                  <tr>
                    <td>Carlos Alberto Salazar Beltran</td>
                    <td><center>M5</center></td>
                  </tr>
                  <tr>
                    <td>Jesús Rubén Balleza Rojas</td>
                    <td><center>M5</center></td>
                  </tr>
              </div>
                </table>
            <!-- Optional JavaScript -->
        <!-- jQuery first, then Popper.js, then Bootstrap JS -->
        <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
        <script src="https://cdn.jsdelivr.net/npm/popper.js@1.14.7/dist/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.3.1/dist/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
   </body>
</html>
