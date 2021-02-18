# HTML & CSS

## HyperText Markup Language

### Contenido:

- Bases de HTML
- Secciones
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

```html
<etiqueta> Contenido </etiqueta>
```

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

---

## Referencias

- [Oficial W3C](https://www.w3.org/TR/html52/introduction.html)
- [Mozilla Developer Network](https://developer.mozilla.org/es/docs/Web/HTML)
