# HTML & CSS

## HyperText Markup Language

### Contenido:

- [Bases de HTML](#bases-de-hTML)
- [Secciones](#secciones)
- Elementos de línea
- Atributos
- Enlaces
- Listas
- Listas
- Tablas
- Otras etiquetas importantes
- Formularios
- Contenido Embebido
- Etiquetas meta y accesibilidad
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

---

## Referencias

- [Oficial W3C](https://www.w3.org/TR/html52/introduction.html)
- [Mozilla Developer Network](https://developer.mozilla.org/es/docs/Web/HTML)
- [Validación de código HTML](https://validator.w3.org/)
