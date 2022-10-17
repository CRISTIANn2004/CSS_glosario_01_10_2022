# Glosario de css

#### **Estructura** 

```css
selector{
    propiedad: valor;
}
```

##### **selector:** el selector lo que hace es seleccionar la parte o las partes que  nosotros queremos cambiar del HTML, y acomodarlo a nuestro estilo. 

**propiedad:** la propiedad es lo que nosotros queremos cambiar al HTML, cambiarlo a nuestro estilo, como color, tamaño, ancho, grosor etc, la propiedad mas cansilla es (color).

**valor:**  el valor es como lo queremos cambiar de ese HTML, como el color, red seria el color mas cansillo, luego esta tipo texto etc.

   

#### Selectores:

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
<h2 class= titulo> mi nombre es cristian andres silva muñoz</h2>
<p class= titulo> cambia por clase el que puse fue (titulo)</p>
```

**Id #:** este selector selecciona por un ID, y como cualquier ID este tiene que ser único solo lo puede tener uno solo elemento, es como cualquier CC, TI, y este se arma con un (#)

```css
#hola{
    color:red;
}
```

 HTML:

```html
<h2 id="hola"> mi nombre es cristian andres silva muñoz</h2>
<p id="hola"> cambia por clase el que puse fue (titulo)</p>
```

