# HTML & CSS

## HyperText Markup Language

### Contenido:

- [Bases de HTML](#bases-de-hTML)
- [Secciones](#secciones)
- [Elementos de línea](#elementos-de-línea)
- [Atributos](#atributos)
- [Enlaces](#enlaces)
- [Listas](#listas)
- [Tablas](#tablas)
- [Otras etiquetas importantes](#otras-etiquetas-importantes)
- [Formularios](#formularios)
- [Contenido Embebido](#contenido-embebido)
- [Etiquetas meta y accesibilidad](#etiquetas-meta-y-accesibilidad)
- [Referencias](#referencias)

<br>

## Cascading Style Sheets

### Contenido:

- Bases de CSS
- Box Model
- Position
- Display, pseudoelementos y pseudoclases
- Variables y background
- Textos y tipografias
- Listas, Tablas, imágenes y clip-path
- Colores, Border-radius, sombras, degradados, overflow y float
- Flexbox
- Grid
- Responsive

---

## Bases de HTML

### Vocabulario Web

- **IP (Internet Protocol):** Es el identificador numérico de una página web, es único y representa la dirección donde está el ordenador que contiene esa página web.
- **Dominio web / URL (Uniform Resource Locator):** Es el nombre asociado a la **IP** que utilizamos para solicitar recursos, en nuestro caso un sitio web.
- **DNS (Domain Name System):** Es un servidor cuya principal función es traducir el nombre de dominio a su identificador único.
- **Sitio web:** Es un conjunto de uno o varios recursos web alojados en el mismo dominio.
- **Servidor web:** Es un ordenador cuyo objetivo es servir recursos web.
- **Hosting:** Es el almacenamiento del servidor web. El disco duro donde el servidor guarda los recursos.
- **Petición:** Es la acción de pedir recursos a un servidor.

### ¿Qué es HTML?

- Es un lenguaje de marcado de hipertexto (**H**yper**t**ext **M**arkup **L**anguage).

* HTML no es un lenguaje de programación, es un lenguaje de estructura.
* Es la base con la que están creadas TODAS las páginas web del mundo.
* Cdad etiqueta le dice al navegador y a los motores de búsqueda cuál es la estructura de los documentos, elementos, organización, etc.

### Historia de HTML

- 1989 - Inicio de su desarrollo.
- 1991 - Lanzamiento de la web (se baasa en 3 conceptos. **http**, **html** y **url**).
- 1992 - Lanzamiento de HTML (Nació de SMGL. Creado por Tim Bernes Lee).
- 1994 - Creación de la **_W3C_** (Consorcio que define los estándares de la web).
- 1998 - HTML 4 (Versión que más duró de HTML).
- 1999 - HTML 4.1 - XHTML (actualización del estándar HTML4).
- 2004 - Creación de la **WHATWG (Web Hypertext Application Technology Working Group)**
- 2008 - HTML 5 (Lanzamiento por WHATWG de forma independiente ).
- 2014 - Estándar HTML5 (Lanzado por W3C de forma oficial).

### Sintaxis de HTML

![Estructura](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics/grumpy-cat-small.png)

```html
<etiqueta> Contenido </etiqueta>
```

![Anatomia HTML](https://media.prod.mdn.mozit.cloud/attachments/2014/04/09/7659/a731e40efad1f6e0b728bfcf86c0035b/anatomy-of-an-html-element.png)

### Estructura de un sitio web

```html
<!-- Establece el tipo de estandar del documento (HTML5) -->
<!DOCTYPE html>
<!-- Inicio del documento HTML -->
<html lang="en">
  <!-- Datos que le pasamos al navegador con información de nuestra página -->
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <!-- Representa todo el contenido de nuestra página web -->
  <body>
    <h1>Contenido</h1>
  </body>
</html>
```

## Secciones

### Títulos y párrafos

Los elementos de encabezado implementan seis niveles de encabezado del documento, `<h1>` es el más importante, y `<h6>`, el menos importante. Un elemento de encabezado describe brevemente el tema de la sección que presenta. La información de encabezado puede ser usada por los agentes usuarios, por ejemplo, para construir una tabla de contenidos para un documento automáticamente.  
[Saber más](https://developer.mozilla.org/es/docs/Web/HTML/Elemento/Elementos_T%C3%ADtulos#p%C3%A1gina_de_ejemplo)

### Header, main y footer

- **Header**

El elemento de HTML Header `(<header>)` representa un grupo de ayudas introductorias o de navegación. Puede contener algunos elementos de encabezado, así como también un logo, un formulario de búsqueda, un nombre de autor y otros componentes.

- **Main**

El elemento HTML `<main>` representa el contenido principal del `<body>` de un documento o aplicación. El área principal del contenido consiste en el contenido que está directamente relacionado, o se expande sobre el tema central de un documento o la funcionalidad central de una aplicación. Este contenido debe ser único al documento, excluyendo cualquier contenido que se repita a través de un conjunto de documentos como barras laterales, enlaces de navegación, información de derechos de autor, logos del sitio y formularios de búsqueda (a menos, claro, que la función principal del documento sea un formulario de búsqueda).

- **Footer**

El Elemento HTML Footer `(<footer>)` representa un pie de página para el contenido de sección más cercano o el elemento raíz de sección `(p.e, su ancestro mas cercano <article>, <aside>, <nav>, <section>,<blockquote>, <body>, <details>, <fieldset>, <figure>, <td>)`. Un pie de página típicamente contiene información acerca de el autor de la sección, datos de derechos de autor o enlaces a documentos relacionados.

### Section vs Article vs Aside

- **Section**

Es un contenedor genérico que agrupa contenido que está relacionado. cuando creamos bloques cuyo contenido es parte de un bloque total usaremos section.

- **Article**

Es un contenedor que representa contenido independiente, es decir, podemos leer ese fragmento en cualquier otro sitio y tendría sentido por sí mismo.

- **Aside**

Se utiliza para representar contenido relacionado pero que no forma parte del contenido principal.

## Elementos de línea

- **em** - emphasis
- **strong** - más enfasis
- **small** - Menos enfasis que el texto normal
- **br** - Forzar un salto de línea
- **wbr** - Salto de línea si hiciera falta
- **time** - Se usa para representar un contenido de hora/fecha
- **i** - ítalic
- **b** - bold
- **u** - underline

## Atributos

### Introducción a los atributos

Los atributos son valores adicionales que configuran los elementos y/o ajustan su comportamiento.  
En términos generales hay dos tipos de atributos:

- **Comunes:**
  Su sintaxis es -> atributo="valor"
- **Booleanos:**
  Su sintaxis es -> atributo

## Enlaces

Conocidos también por links popularmente. Su objetivo es conectar una página web con otra página web, con un recurso tanto interno como externo, o con otro sitio web.

Tienen el atributo obligatorio de href, donde le especificamos la ruta del recurso o sitio que queremos obtener.  
También tiene el atributo target, que configura cómo queremos visualizar el recurso o sitio que solicitamos.

### Rutas

**Rutas absolutas:**  
Tienenun protocolo, http o https y son unicas en la red. Se suelen utilizar para rutas externas.

**Rutas relativas:**  
Pueden ser relativas al punto donde nos encontramos o relativas a la raiz del proyecto.  
No usan protocolo.  
Si el recurso se encuentra al mismo nivel (en la misma carpeta) podremos unicamente el nombre del archivo.  
Si necesitamos salir de la carpeta actual usaremos ../ y se pone uno por cada nivel (carpeta)
de la quue queramos salir.

### Atributos

**target:**  
Define donde se abrirá el recurso solicitado. por norma general siempre que useis rutas absolutas pondréis como valor "\_blank"

**download:**  
Atributo booleano, sirve para descargar el recurso solicitado.  
Importante, el recurso debe estar en tu mismo servidor.

## Listas

Como su nombre lo indica sirve para listar contenido. En función del tipo de contenido de nuestra lista tenemos tres tipos de listas:

- **ul** -> **unordered list:** Se utiliza cuando el orden de los elementos no influye.
- **ol** -> **ordered list:** Se utilizan cuando el orden de los elementos es importante.

Cada elemento de la lista se representa con la etiqueta `<li>`, tanto en las **ul** como en las **ol**.

- **dl** -> **definition list:** Se utilizan para hacer lista de definiciones
  - **dt** -> Definition term: El término que vaos a definir.
  - **dd** -> Definition description: la descripción del término.

## Tablas

Las tablas en HTML sirven para mostrar contenido tabulado.

**La estructutara básica de una tabla se compone de:**

- **table** -> Etiqueta que encierra una tabla
- **tr** -> table row, etiqueta que construye una fila
- **td** -> table data, etiqueta que construye una celda

El número de celdas dentro de un td establecerá el número de columbas de la tabla.

#### Título

Los títulos de las tablas se establecen con la etiqueta `<capttion></capttion>`, es una etiqueta opcional, y según la especificación esa etiqueta se coloca justo después de la etiqueta table.

#### Cabecera

las cabeceras de las tablas se establecen con la etiqueta `<thead></thead>`. Dentro tendremos un etiqueta `<tr></tr>` normal, pero en el caso de las celdas, las estableceremos con la etiqueta `<th></th>` en lugar de `<td></td>`.

#### Cuerpo

El contenido de la tabla debe ir dentro de una etiqueta `<tbody></tbody>` para representar eñ cuerpo de la tabla.

#### Pie de la tabla

De forma opcional podemos colocar un `<tfoot></tfoot>` a la tabla para establecer un pie de tabla, esto es algo que algunas tablas tienen como suma de cantidades o total.

### Atributos

Para hacer que las celdas ocupen más de una fila o más de una columna tenemos dos atributos:

- **rowspan:** sirve para que una celda ocupe más de una fila, el valor por defecto es 1

- **colspan:** sirve para que una celda ocupe más de una columna, el valor por defecto es 1

### Columna

Cuando necesitamos seleccionar una columna, tenemos la etiqueta `<colgroup></colgroup>`, que nos permite seleccionar una columna en concreto. Dentro pondremos tantas etiquetas `<col></col>` como columnas tengamos, cada etiqueta `<col></col>` equivaldrá a una columna siguiendo el mismo orden que tienen en la tabla.

Si necesitamos que una etiqueta con agrupe más de una columna, tenemos atributos span, que funciona exactamente igual que rowspan y colspan.

## Otras etiquetas importantes

### Etiquetas de bloque

- **address:** Se utiliza para aportar información de contacto para el article más cercano o para todo el body.
- **blockquote:** Se utiliza para marcar las citas a otros actores o documentos. Se puede incluir el atributo cite para poner un enlace al documento original o fuente.
- **pre:** Se utiliza para tener código preformateado que necesita ser representado igual que se escribió.
- **div:** Se usa como división del documento, semánticamente no significa nada, es un contenedor genérico que se usa generalmente para dar estilos a través de css o para usar algo denominado "delegación de eventos" en javascript.
- **hr:** Horizontal rule, se utiliza para decirle al navegador que vamos a cambiar de tema.

### Etiquetas de línea

- **span:** Es un contenedor de línea, equivalente a div, se suele usar para encerrar palabras o pequeños textos y darles estilo a través de CSS o localizarlos desde javascript- Semánticamente no significa nada
- **q:** Es el quivalente a blockquote, significa quote, por ese el de bloque se llama block - quote. Sirve para poner citas pero en línea.
- **code:** Sirve para encerrar código que queremos representar visualmente, suele ir unido con la etiqueta pre.

[**Entidades especiales en HTML - Código ASCRII**](https://ascii.cl/es/codigos-html.htm)

## Formularios

La estructura básica de un formulario se compone de 4 elemetos:

- **form** -> es la etiqueta que engloba nuestro formulario.
- **label** -> sirve para escribir el nombre del campo a rellenar, debe tener el atributo for el cual se le indica un id que hará será emparejar el label con su input correspondiente.
- **input** -> sirve para crear un campo que permiti´ra al usuario interactuar.
- **button** -> crea un botón que permitirá enviar el formulario.

### Tipos de input

**input type:**

- **button** -> Se comporta igual que un botón `<button></button>`
- **color** -> Se utiliza para especificar un color

---

- **date** -> Se utiliza para introducir una fecha
- **datatime** -> Obsoleto
- **datatime-local**-local -> fecha y hora, no funciona en firefox
- **time** -> Se utiliza para introducir un hora
- **month** -> Se utiliza para introducir un mer
- **week** -> Se utiliza para introducir el número de semana del año

---

- **search** -> Se utiliza para las barras de búsqueda
- **tel** -> Se utiliza para introducir números telefónicos
- **email** -> Se utiliza para introducir un email
- **password** -> Se utiliza para contraseñas
- **url** -> Se utiliza para introducir URLs

---

- **hidden** -> Campo oculto, puede contener valor pero no se mostrará
- **number** -> Se utiliza para valores numéricos
- **range** -> Se utiliza para establecer un rango
- **reset** -> Se utiliza para resetear el formulario
- **submit** -> Se utiliza para enviar el formulario
- **text** -> Valor por defecto

### Inputs de selección

- **radio** -> Permite seleccionar una única opción de una lista de opciones relacionadas.
- **checbox** -> Permite seleccionar varias opciones de una lista de opciones relacionadas.
- **select** -> Crea una lista de opciones donde podemos seleccionar una o varias opciones.

Cada opción irá dentro de una etiqueta `<option></option>`.  
Si tenemos muchas opciones podemos ordenarlas por categorías a través de la etiqueta `<optgroup></optgroup>` con el atributo label para nombrar la categoría.

### Mas elementos de formulario

- **fieldset** -> Se utiliza para agrupar elementos dentro de un formulario.
- **legend** -> Representa una etiqueta para el contenido del fieldset.
- **file** -> Este inpu se utiliza para cargar archivos y enviarlos desde un formulario.
- **meter** -> Representa un valor dentro de un rango conocido.
- **progress** -> Represtenta el progreso de una tarea.
- **textarea** -> Se utiliza para introducir texto en un formulario

### Atributos de los formularios

- **placeholder** -> Da una pista de lo que el usuario tiene que introducir.
- **required** -> Hace que un campo sea obligatorio.
- **readonly** -> Hace que un campo sea de solo lectura.
- **min - max** -> Establece el minimo y máximo de un campo numérico.
- **maxlenght - minlenght** -> Estableche el minimo y máximo de caracteres de un campo de texto.
- **selected** -> Equivale a checked en los select, sirve para establecer un opción por defecto.
- **disabled** -> Desactiva el campo, no se podrá escribir en el autofocus.
- **autofocus** -> Para poner el foco por defecto al cargar el formulario.

### GET VS POST

La diferencia entre los métodos get y post radica en la forma de enviar los datos a la página cuando se pulsa el botón “Enviar”. Mientras que el método GET envía los datos usando la URL, el método POST los envía de forma que no podemos verlos (en un segundo plano u "ocultos" al usuario).

## Contenido Embebido

El contenido embebido es todo el contenido que nos traemos desde fuera. Estos contenidos son los que más pesan (tamñan) añaden a un sitio web.

Los tipos más conocidos son:

- Imágenes
- Audio
- Vídeo
- Iframes

### **IMÁGENES**

Los formatos de imágenes para web los podemos clasificar en 2 tipos:

- Vectoriales
  - svg (recomendado siempre que see pueda)
- Mapa de bits
  - jpg
  - png 8 y 24 (si necesitáis transparencias)
  - gif (si necesitáis una imagen animada)
  - webp (el formato que menos pesa)

**Divice Pixel Ratio**

Es la relación que existe entre los píxeles reales que tiene el dispositivo y los píxeles disponibles para "pintar" contenido.

**DRP** = pixeles reales / pixeles disponibles

## Etiquetas meta y accesibilidad

## Referencias y recursos

- [Oficial W3C](https://www.w3.org/TR/html52/introduction.html)
- [Mozilla Developer Network](https://developer.mozilla.org/es/docs/Web/HTML)
- [Validación de código HTML](https://validator.w3.org/)
- [Convertir una imagen a WebP](https://imagen.online-convert.com/es/convertir-a-webp)
- [Crear Favicon](https://www.favicon-generator.org/)
- [font Awesome](https://fontawesome.com/)
- [The Open Graph protocol](https://ogp.me/)
- [twitter card](https://developer.twitter.com/en/docs/twitter-for-websites/cards/overview/abouts-cards)
