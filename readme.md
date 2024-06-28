# Box Model
## Cada elemento dentro de la web esta representado por una caja rectangular que esta compuesta por varios componenetes:
- Conetenido: Area donde se muestra el contenido
- Padding espacio entre el contenido y el borde (INTERNO)
- Border Un contorno al rededor del contenido y del padding (INTERNO)
- Margin Espacio (EXTERNO) que separa un elemento de otro
## Selector universal
- El Selector universal es el *
```css
*{
    /* En esta line de codigo hacemos que el border y el padding que le agregemos a cualquier elemento no se vean afectados tanto en el widht y height */
    box-sizing: border-box; 
}
```
## Colapsado de margenes verticales
- Al aplicar un espacio entre cada caja usamos el margin y como es de forma vertical prevalece el de mayor tamaño
```css
.div1{
    margin-bottom: 80px;
}
.div2{
    margin-top: 50px;
}
```
## margin -