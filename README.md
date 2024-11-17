# Apuntes-asix1
# MarkDown
## Segundo nivel de encabezado
### Tercero nivel de encabezado
#### Quarto nivel de encabezado
##### Quinto nivel de encabezado

Mis apuntes de *0373* del ciclo de _asix_ o **daw** __**2425**__

Las eqtiquetas de HTML y **_Markdown_** puede anidarse

1. Primer punto de la lista
    1. Primer punto de la sublista
    2. Segundo punto de la sublista

2. Segundo punto de la lista
    * 
3. Tercer punto de la lista

* Primer punto de lista desordenada
- Segundo punto de lista desordenada
+ Tercer punto de lista desordenada


**Como mostrar codigo en un repositorio**
```
<html>
	<head>
		<title>Mi página de ejemplo</title>
	</head>
	<body>
	Aquí va el contenido
	</body>
</html>
```

### Como poner un link
[texto clicable](URL "Titulo opcional")
[Pagina Web Joan23](https://www.fje.edu/ca/jesuites-bellvitge "Titulo opcional")


### Como poner una imagen

![Texto alternativo](Ubicacion de la imagen "Titulo opcional")

![Ronaldiño](https://github.com/MerinoVic115/apuntes-asix1/blob/main/ronaldi%C3%B1o.jpg "Titulo opcional")


|Titulo 1 | Titulo 2 | Titulo 3 |
|----------|:--------------:|------------------:|
|SMX2 |Curso 2423 |25 |
|**ASIX1** |Curso 2425 |33 |
|DAW2 |Curso 2425 |32 |

# Comandos Github

| **Comando**                     | **Descripción**                                                                                     |
|             ------------------- |-----------------------------------------------------------------------------------------------------|
| `git init`                      | Inicializa un nuevo repositorio Git en el directorio actual.                                        |
| `git clone <URL>`               | Clona un repositorio existente desde una URL.                                                       |
| `git add .`                     | Agrega todos los cambios al área de preparación.                                                    |
| `git commit -m "mensaje"`       | Guarda los cambios en el historial del repositorio con un mensaje.                                  |
| `git push`                      | Sube los cambios al repositorio remoto.                                                             |
| `git pull`                      | Descarga y fusiona los cambios del repositorio remoto al local.                                     |


# HTML

## Introducción a html

HTML (HyperText Markup Language), es un **lenguaje de marcas**, es lo mas importante de internet ya que sin html no se vería nada.
HTML define la estructura y el contenido, tiene una estructura lógica y es fácil de interpretar y entender.
No se dedica a ver como se interactúa con el contenido (javascript y etc).
Los elementos de html son bloques de construcción de las paginas web.
HyperText: texto que enlaza otros contenidos
Markup: Todas las webs están construidas en base de etiquetas
Language: HTML es un lenguaje, pero no es un lenguaje de programación, no tiene estructuras de lenguaje de programación, bucles, condiciones, funciones y etc.


## Elementos: 
El contenido esta entre dos etiquetas.

## Atributos: 
Es algo que modifica la etiqueta. El atributo va en la etiqueta de inicio.

## Estructura de html:
Esto es una estructura básica de HTML.
```
<html>
	<head>
		<title>Título de ejemplo</title>
	</head>
	<body>
		<p>¡Esta es mi web!</p>
	</body>
</html>
```

## Elementos de bloque y línea

### Elementos de bloque
Son grandes estructuras independientes que separan contenido.  
Ejemplos: `<h1>` - `<h6>` (encabezados), `<p>` (párrafo), `<br>` (salto de línea), `<hr>` (separador), `<div>`, `<blockquote>`, `<pre>`.

### Elementos de línea
Son pequeñas estructuras que representan trozos de texto dentro de los bloques.  
Ejemplos: `<em>` (cursiva), `<strong>` (negrita), `<a>` (hipervínculos), `<span>`, `<code>`.

---

## Legibilidad y organización del código

La legibilidad del código facilita su comprensión. Es fundamental que el código HTML sea claro y organizado.

### Puntos clave:
- **Usa comentarios.**
- **Aplica indentación del código.**
- **Organiza los archivos en directorios según sea necesario.**

---

## Etiquetas básicas de HTML (Listas)

### Listas desordenadas
Usan `<ul>` (unordered list) con símbolos como círculos, discos o cuadrados.  
**Ejemplo:** `<ul type="disc">`.

### Listas ordenadas
Usan `<ol>` (ordered list) donde el orden importa (como recetas).  
Pueden ser numéricas o alfabéticas.  
**Ejemplo:** `<ol type="1">` para números o `<ol type="A">` para letras.  
**Parámetro:** `start=n` para definir el inicio.

---

## Etiquetas básicas de HTML

**Listas de definición:** Enumeran términos con sus definiciones.
**Formadas por dos elementos:** el término y su definición.

**Etiquetas usadas:**
- dl: Define el inicio y fin de la lista (definition list).
- dt: Representa el término (definition term).
- dd: Contiene la definición del término (definition description).

## Rutas de HTML

- **Ruta absoluta:** Incluye la ruta completa.  
  **Ejemplo:** C:\html\img1.jpg
  
- **Ruta relativa:** Define la ruta desde la ubicación actual.  
  **Ejemplo:** ..\imagenes\img2.jpg



## Validación HTML

Para validar un HTML, utiliza el siguiente enlace:  
[validator.w3.org](https://validator.w3.org/ "Validador de HTML")


## Elementos semánticos en html 5:

`<span>`: permite agrupar contenido en línea.

`<div>`: permite guardar otras etiquetas. 

HTML semántico: Describe el contenido con un significado claro y estructurado.

Elementos como span (contenido en línea) y div (contenido en bloque) no aportan valor semántico, solo estructuran sin indicar el tipo de contenido.

Ventaja del HTML semántico: Proporciona información clara sobre el contenido, facilitando la comprensión y accesibilidad.

Ejemplos de elementos semánticos:

- **header** 
- **footer**
- **article** 
- **section** 
- **nav** 
- **figure**.


## Formulario
El formulario es para recopilar datos del usuario y contiene varios elementos (nombre, password y etc).

Cada formulario debe de tener atributo name, con lo cual se identifica el dato.
Apertura y cierre: form

Atributo común: 
`<action>`: Define la url donde se enviará los datos
`<method>`: especifica el método de envio de datos
`<enctype>`: Define como se codifican los datos

etiqueta *imput*: 
	Se usa para crear diversos campos interactivos.

### Etiqueta input

La etiqueta input se utiliza para crear diversos tipos de campos interactivos en un formulario. Se pueden usar para entradas de texto, contraseñas, correos electrónicos, casillas de verificación, entre otros.

### Atributos comunes de input:
- **type**: Define el tipo de entrada que se debe mostrar (ej. text, password, email, etc.).
- **id**: Identificador único para asociar etiquetas label con el campo de entrada.
- **name**: Nombre del campo de entrada, utilizado al enviar el formulario para identificar el dato.
- **value**: Valor predeterminado que tendrá el campo.
- **placeholder**: Texto que aparece en el campo cuando está vacío, indicando el tipo de dato que se debe ingresar.
- **required**: Indica que el campo debe completarse antes de enviar el formulario.
- **disabled**: Desactiva el campo, evitando que el usuario interactúe con él.
- **readonly**: Hace que el campo sea solo de lectura, evitando modificaciones.

#### Ejemplo:

```
<input type="text" placeholder="Escribe tu nombre" />
<input type="password" />
<input type="email" />
<input type="checkbox" />
```

### Etiqueta `<type="radio">`

Se usa para los botones de opción, permite seleccionar solo una opción dentro de un grupo de opciones con el mismo atributo.

```
<form action="/enviar-datos" method="POST">
  <fieldset>
    <legend>Selecciona tu género musical favorito:</legend>
    <input type="radio" name="pais" value="espana"> España<br>
    <input type="radio" name="pais" value="egipto"> Egipto<br>
    <input type="radio" name="pais" value="kazajistan"> Kazajistán<br>
  </fieldset>
</form>
```

### Etiqueta `<type="checkbox">`

Se usa para los botones de verificación, permite seleccionar múltiples opciones dentro de un formulario.

#### Ejemplo:
```
<form action="/enviar-datos" method="POST">
  <fieldset>
    <legend>Selecciona tus intereses:</legend>
    <input type="checkbox" name="intereses" value="deportes"> Deportes<br>
    <input type="checkbox" name="intereses" value="musica"> Música<br>
    <input type="checkbox" name="intereses" value="lectura"> Lectura<br>
  </fieldset>
</form>
```

### Etiqueta `<textarea>`

La etiqueta textarea se usa para crear áreas de texto donde los usuarios pueden ingresar múltiples líneas. Es especialmente útil para mensajes largos o descripciones detalladas.

Atributos comunes de `<textarea>`:

- name: Especifica el nombre del control que se usará al enviar el formulario.
- id: Identificador único del elemento para asociar con etiquetas <label>.
- rows: Define el número de líneas visibles en el área de texto.
- cols: Define el número de caracteres visibles en cada línea.
- placeholder: Texto visible cuando el campo está vacío, proporcionando una pista sobre el dato esperado.
- required: Indica que el campo debe completarse antes de enviar el formulario.
- readonly: Hace que el área de texto sea solo de lectura.
- disabled: Desactiva el campo, evitando la interacción del usuario.

#### Ejemplo
```
<form action="/enviar-datos" method="POST">
  <label for="comentario">Deja tu comentario:</label>
  <textarea id="comentario" name="comentario" rows="4" cols="50" placeholder="Escribe tu comentario aquí..." required></textarea>
</form>
```

### Etiqueta `<select>`

Se usa para crear menús desplegables en los formularios. Permite al usuario seleccionar una opción de una lista de opciones predefinidas.

#### Atributos comunes:
- **name**: Especifica el nombre del control que se usará al enviar el formulario. Este nombre se enviará al servidor como clave en el par nombre-valor.
- **id**: Identificador único del elemento, que puede usarse para asociarlo con una etiqueta `<label>`.
- **size**: Define el número de opciones visibles en la lista desplegable sin necesidad de desplazarse. Si se omite, se muestra una lista simple.
- **multiple**: Permite seleccionar varias opciones a la vez. Si se especifica, el menú se convierte en una lista múltiple.
- **value**: Indica el valor de la opción.

#### Ejemplo:
```
<select id="pais" name="pais" required>
  <option value="">--Selecciona un país--</option>
  <option value="espana">España</option>
  <option value="mexico">México</option>
  <option value="argentina">Argentina</option>
  <option value="colombia">Colombia</option>
</select>
```

### Etiqueta `<button>`

Se usa para crear varios tipos de botones interactivos en un formulario o una página web. A diferencia de la etiqueta `<input type="submit">`, el contenido del botón `<button>` puede incluir texto, imágenes o incluso HTML adicional.

#### Atributos comunes:
- **type**: Define el tipo de botón. Los valores más comunes son:
  - **submit**: Envía el formulario cuando se hace clic en él. Es el valor predeterminado.
  - **button**: Crea un botón sin una acción predeterminada (generalmente usado con JavaScript).
- **name**: Define el nombre del botón que se enviará con los datos del formulario si el botón tiene el atributo `type="submit"`.
- **disabled**: Desactiva el botón, impidiendo que se haga clic en él.

#### Ejemplo:
```
<form action="/enviar-datos" method="POST">
  <label for="nombre">Nombre:</label>
  <input type="text" id="nombre" name="nombre" required>
  <button type="submit" name="enviar" value="enviar-datos">Enviar</button>
```




