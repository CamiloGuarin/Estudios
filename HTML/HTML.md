# HTML
- HTML significa Hyper Text Markup Languaje
- Lenguaje de marcado estándar para crear páginas web
- Describe la estructura de una página web
## Estructura Básica:
```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8" />
  <meta name="description" content="Descripción de la página cuando es buscada en el navegador />
  <meta name="robots"                               
<title>Page Title</title>
</head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```
- La declaración ```<!DOCTYPE html>``` define que el documento es HTML5
- El elemento ```<html>``` es el elemento raíz de una página html
- El elemento ```<head>```contiene metainformación sobre la página html, todo lo que necesita el navegador para que el proyecto pueda cargar de la forma en la que lo hicimos. `charset="UTF-8"`, esto es para que el navegador pueda entender caracteres especiales. `<meta name="robots" content="index,follow" />` esto es para autorizar a los robots de los buscadores a colocar nuestra página en relación con la búsqueda que se hace.
- El elemento ```<title>```indica el título de la página html, se muestra en la barra de título del navegador o en la pestaña de la página
- El elemento ```<body>``` define el cuerpo del documento y contiene todo el contenido visible para la página html
### La declaración <!DOCTYPE>
* La declaración <!DOCTYPE> representa el tipo de documento y ayuda a los navegadores a mostrar las páginas web correctamente y solo aparece una vez en todo el documento y es al principio.
* La declaración para HTML5 es:
```html
<!DOCTYPE html>
```

### Encabezados HTML
Los encabezados html se definen con las etiquetas ```<h1>``` hasta ```<h6>```, donde ```<h1>``` define el encabezado más importante y ```<h6>``` el menos importante.

**Ejemplo:**
  ```html
  <h1>Este es el encabezado 1</h1>
  <h2>Este es el encabezado 2</h2>
  ```
### Párrafos HTML
Los párrafos en html se definen con la etiqueta ```<p>```.

**Ejemplo:**
  ```html
  <p>Este es un párrafo</p>
  ```
### Enlaces HTML
Los enlaces html se definen con la etiqueta ```<a>```.

**Ejemplo:**
  ```html
  <a href="https://github.com/CamiloGuarin/Estudios">Este es un Link</a>
  ```
- El destino del enlace se especifíca con el atributo ```href```.
### Imágene HTML
Las imágenes en html se definen con la etiqueta ```<img>```, el archivo de origen ```src```, el texto alternativo ```alt``` y ```width``` y ```height``` como atributos.

**Ejemplo:**
```html
<img src="https://github.githubassets.com/images/modules/open_graph/github-octocat.png" alt="github.com" width="120" height="170">

