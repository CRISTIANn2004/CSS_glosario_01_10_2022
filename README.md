# Glosario de css

### **Estructura** 

```css
selector{
    propiedad: valor;
}
```

##### **selector:** el selector lo que hace es seleccionar la parte o las partes que  nosotros queremos cambiar del HTML, y acomodarlo a nuestro estilo. 

**propiedad:** la propiedad es lo que nosotros queremos cambiar al HTML, cambiarlo a nuestro estilo, como color, tamaño, ancho, grosor etc, la propiedad mas cansilla es (color).

**valor:**  el valor es como lo queremos cambiar de ese HTML, como el color, red seria el color mas cansillo, luego esta tipo texto etc.

   

### Selectores:

**Universal *:** este selector es el universal agarra todo lo que hay en el HTML

```css
*{
color:red; 
}
```

**De tipo:** este tipo selector selecciona por elemento (puede ser el nombre ) el que nosotros queramos, EJ: h1, input etc

**Clase . :** este selector selecciona por clases, grupos que armemos y se arma con un (.)

```css
.titulo{
    colo:red;
}
```

  HTML:

```html
<h1>hola me llamo cristian</h1>
     <h2 class= "titulo"> mi nombre es cristian andres silva muñoz</h2>
<p class= "titulo"> cambia por clase el que puse fue (titulo)</p>
```

**Id #:** este selector selecciona por un ID, y como cualquier ID este tiene que ser único solo lo puede tener uno solo elemento, es como cualquier CC, TI, y este se arma con un (#)

```css
#hola{
    color:red;
}
```

 HTML:

```html
<h1>hola me llamo cristian</h1>
     <h2 id="hola"> mi nombre es cristian andres silva muñoz</h2>
<p id="hola"> cambia por clase el que puse fue (titulo)</p>
```

**Por atributo []:** este selector selecciona por atributo (<h2 perro= "pug"> </h2>),  y este se arma con un unos corchetes []

```css
[perro ="pug"]{
    color:red;
}
```

HTML:

```html
<h1>hola me llamo cristian</h1>
    <h2 perro="pug"> mi nombre es cristian andres silva muñoz</h2>
<p perro="pug"> cambia por clase el que puse fue (titulo)</p>
```

**Descendiente:** este selector selecciona, las etiquetas, eventos, clases etc, que estén dentro de un contenedor puede ser una etiqueta,  (<h2> <p> acá selecciona a los p  </p> </h2>) y se arma colocando primero el contendor (h2)y luego lo que queremos seleccionar (p) 

```css
h2 p {
    color: red;
}
```

HTML:

```html
<h2><p> hola me llamo cristian</p></h2>
    <h2><b> mi nombre es cristian andres silva muñoz</b></h2>
<p> cambia por clase el que puse fue (titulo)</p>
```

### **Especificidad:** 

la especificidad es la lógica que tiene nuestro pc, en como hacen algo mas relevante de las demás cosas, si le hacemos 5 cambios a nuestro css el va dejar el ultimo cambio que le hicimos ya que fue lo mas importante que hicimos en la lógica del pc

- Quiero que le de prioridad a un cambio, y que siga : por eso existe la jerarquía, donde !important es al que mas alto esta, y pseudo-lenguaje es el menos importante      

  | lo mas importante |                 |                     |                                  |   menos menos importante    |
  | :---------------: | --------------- | ------------------- | -------------------------------- | :-------------------------: |
  |    !important     | estilo en línea | id(identificadores) | clases, pseudo-clases, atributos | elementos, pseudo-elementos |

  