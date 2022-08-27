# Estilos en Línea
Lo añades directamente a la etiqueta de apertura del html.
Ej: `<h2 style = "color: blue">"Texto"</h2> `

# Elemento style
Añadimos el elemento < style> en < head> para describir el estilo.
Ej: < head>
	< style>
		h2{
			color:blue;
		}
	< /style>
< head>`


# Archivo css

Definimos un archivo y vinculamos el html y el css

# Estilo en linea
< h2 **style = " color: blue"**> "texto" < /h2>

# Creando un archivo CSS
< link href = "style.css" rel = "sylesheet">

# Selectores CSS

h2 {
	color: blue;
}

los selectrores definen sobre qué elementos se aplicará un conjunto de reglas CSS.

-Selector de tipo: selecciona todos los elementos que coinciden con el nombre del elemento especificado. (el ejemplo q tenemos arriba).

-Selector universal. Selecciona TODOS los elementos
`` *  {

``}

- Selectores de clase: Selecciona todos los eleemntos que tienen el atributo class especificado.