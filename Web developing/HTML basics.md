# HTML elements
is defined by a start tag and an end tag:
**EX:**
`` < tagname> Content goes here < /tagname> ``
**Some tag examples**

![[Pasted image 20220429123937.png]]

## Html page structure
A web browser basically reads the HTML code without the tags, it uses them to know HOW to display it

![[Pasted image 20220429124228.png]]

## Clases
Para incluir una clase en html, por ejemplo de css, vamos a usar:

< ejemplo class = "ejemplo">
< /ejemplo>

## Listas

< ul> unordered list
< li> list item
Sale de esta forma:
- fdsafds
- f da
- fdsafdsa

< ol> ordered list
Sale de esta forma
1. fdsa
2. fda
3. fdafdsa


## Enlaces:

< a href="destino del enlace"> es un link (anchor en ingles)
para abrir el enlace en otra pestaña nueva:
< a href ="destino del enlace"  target = "_blank" rel = "noopener noreferrer">
Si el valor es _blank se va a abrir en una pestaña nueva
Y añadimos el rel con ese valor para evitar problemas de seguridad con la vulnerabilidad TabNabbing

Para poner un enlace que no lleve a ningun lado
< a href = "#">


Para conectar dos elementos dentro de una pagina (saltar de un sitio a otro mediante un enlace)
< a href="#parrafo-1">

< h3 id ="parrafo-1">

Aqui saltariamos de un index que pone parrafo-1 al parrafo-1

## Imagenes:

< img src = "fuente de la imagen.jpg" alt ="descripcion de la imagen si NO consigue cargar la imagen"> 

## Imagenes como enlaces:

< a href ="enlace">< img src = "fuente de la imagen.jpg" alt ="descripcion de la imagen si NO consigue cargar la imagen"> < /a>

## Para comentar en html:
<!-- contenido del comentario -->

## Letra negrita, cursiva, o tachado
Si rodeamos una palabra con < strong> "PALABRA" < /strong> nos mostrara la letra en negrita.
Si rodeamos una palabra con  < em> "PALABRA" < /em> 
Si rodeamos la palabra con < s> "PALABRA" < /s>

## Horizontal rule
Añade una linea horizontal. < hr>

## Formularios

< form action = "/enviar-respuesta"> 

  < input type = "text" placeholder =" texto" required>
  < button type = "submit"> Enviar < /button>
  
< /form>

### Botones de Radio

< form action = "/enviar-respuesta"> 

  < label for ="opcion1">< input id ="opcion1" type = "radio" > Opcion 1 < /label>
  < label for = "opcion2"> < input  id = "opcion2" type = "radio" > Opcion 2 < /label>
  
  < button type = "submit"> Enviar < /button>
  
< /form>
**Para seleccionar solo 1 opcion**

< form action = "/enviar-respuesta"> 

  < label for ="opcion1">< input id ="opcion1" type = "radio" name="grupo1"> Opcion 1 < /label>
  < label for = "opcion2"> < input  id = "opcion2" type = "radio" name ="grupo1" > Opcion 2 < /label>
  
  < button type = "submit"> Enviar < /button>
  
## Salto de linea

< br>

## Casillas de verificacion 

< input type ="checkbox">

El atributo checked 

< input type ="checkbox" checked>


< input type ="radio"... ... value ="opcion1">

le envia al servidor el valor: opcion1

## Etiqueta small
Hace el texto pequeño
< small> 
	texto
< /small>
