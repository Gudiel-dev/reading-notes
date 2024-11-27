

<img src="https://cdn.ambientimpact.com/public/media/images/Rachel_Andrew_CSS_is_Awesome_meme_header.png" alt="css meme">

# Read 03: CSS Layout


## ¿Qué es el box model en CSS y cuáles son sus componentes principales?

El box modeling es un concepto de cómo los elementos en la web están estructurados en cajas rectangulares. 
 nos da un control preciso sobre cómo se muestran los elementos HTML en una página web.

Entender sus componentes es fundamental para crear diseños web efectivos y profesionales.

### Componentes del modelo de caja:
-   **Content:** Este es el espacio ocupado por el contenido real del elemento, como texto, imágenes o videos.
-   **Padding:** Es el espacio transparente que rodea el contenido del elemento. 
Se utiliza para crear espacio entre el contenido y el borde del elemento. Se define con las propiedades
    -   `padding-top`
    -   `padding-right`
    -   `padding-bottom`
    -   `padding-left`
    -   
-   **Border:** Es la línea visible que rodea el elemento. 
    -   `border-width`
    -   `border-style`
    -   `border-color`
    -   
-   **Marging:** Es el espacio transparente que rodea el borde del elemento. Se utiliza para crear espacio entre los elementos adyacentes.
    -   `margin-top`
    -   `margin-right`
    -   `margin-bottom`
    -   `margin-left`
-   
<img src="https://developer.mozilla.org/es/docs/Learn/CSS/Building_blocks/The_box_model/box-model.png">


## ¿Cuál es la diferencia entre box-sizing: content-box y box-sizing: border-box, y cómo afecta esto al diseño de una página web?

La propiedad box-sizing en CSS controla cómo se calcula el ancho y alto total de un elemento

-   `box-sizing: content-box`:  calcula el ancho y alto total incluyendo el contenido, el relleno y el borde. 
    -   **suma el borde y relleno a la medida inicial dando un valor extra**
    -   **Cálculo del ancho/alto:** El ancho y alto total del elemento se calcula sumando el ancho/alto del contenido, el relleno y el borde.

    -   **Efecto:** Si estableces un ancho de 100px para un elemento con 10px de relleno y 2px de borde, el elemento ocupará un espacio total de 122px (100px + 10px + 10px + 2px + 2px).
    
- `box-sizing: border-box`:
  - Cálculo del ancho/alto: Hace un wrap de todo manteniendo la medida original sin añadir los valores de padding o border
  - Establece un ancho y alto total fijo, y el espacio para el relleno y el borde se "resta" del espacio del contenido.


## ¿Cuáles son las propiedades principales que se utilizan para configurar un contenedor flex y cómo afectan la disposición de los elementos dentro de él?

Las propiedades principales que se utilizan para configurar el Flexbox son las siguientes:

1. **flex-direction:**
   1. `row`: (valor por defecto): Los elementos se alinean horizontalmente, de izquierda a derecha.
   2. `row-reverse`: Los elementos se alinean horizontalmente, de derecha a izquierda.
   3. `column`: Los elementos se alinean verticalmente, de arriba a abajo.
   4. `column-reverse`: Los elementos se alinean verticalmente, de abajo a arriba.
2. `flex-wrap`:Controla cómo se envuelven los elementos si no caben en una sola línea.
   1. `nowrap` **(valor por defecto)**: Los elementos se colocan en una sola línea, incluso si se desbordan del contenedor.
   2. `wrap`: Los elementos se envuelven en múltiples líneas si es necesario.
   3. `wrap-reverse`: Los elementos se envuelven en múltiples líneas, pero en orden inverso.
3. `justify-content`: Controla la alineación de los elementos a lo largo del eje principal.
   1. `flex-start` **(valor por defecto)**: Los elementos se alinean al inicio del eje principal.
   2. `flex-end`: Los elementos se alinean al final del eje principal.
   3. `center`: Los elementos se centran en el eje principal.
   4. `space-between`: Los elementos se distribuyen uniformemente, con el primer elemento al inicio y el último al final.
   5. `space-around`: Los elementos se distribuyen uniformemente, con espacio alrededor de cada elemento.
   6. `space-evenly`: Los elementos se distribuyen uniformemente, con espacio uniforme entre cada
4. `align-items`: Controla la alineación de los elementos a lo largo del eje secundario (perpendicular al eje principal).
   1. `stretch` **(valor por defecto)**: Los elementos se estiran para ocupar todo el espacio disponible en el eje secundario.
   2. `flex-start`: Los elementos se alinean al inicio del eje secundario.
   3. `flex-end`: Los elementos se alinean al final del eje secundario.
   4. `center`: Los elementos se centran en el eje secundario.
   5. `baseline`: Los elementos se alinean según sus líneas de base.
5. `align-content`: Controla la alineación de las líneas múltiples de elementos si `flex-wrap` está configurado en `wrap`
   1. `flex-start` **(valor por defecto)**: Las líneas se alinean al inicio del eje secundario.
   2. `flex-end`: Las líneas se alinean al final del eje secundario.
   3. `center`: Las líneas se centran en el eje secundario.
   4. `space-between`: Las líneas se distribuyen uniformemente, con la primera línea al inicio y la última al final.
   5. `space-around`: Las líneas se distribuyen uniformemente, con espacio alrededor de cada línea.
   6. `space-evenly`: Las líneas se distribuyen uniformemente, con espacio uniforme entre cada línea y los bordes del contenedor.
6. `gap`: Define el espacio entre los elementos flexibles. Puedes usar `row-gap` y `column-gap` para controlar el espacio entre las filas y las columnas, respectivamente.
7. `order`: Controla el orden de los elementos flexibles. Puedes asignar un valor numérico a la propiedad order para cada elemento, y los elementos se ordenarán de acuerdo a estos valores.
8. `flex-grow`: Controla cómo se expanden los elementos flexibles para ocupar el espacio disponible en el contenedor.
9. `flex-shrink`: Controla cómo se encogen los elementos flexibles si no hay suficiente espacio en el contenedor.
10. `flex-basis`: Define el tamaño inicial del elemento flexible antes de que se expanda o se encoja.

## ¿Cómo se utiliza la propiedad flex para controlar el tamaño y el crecimiento de los elementos flexibles dentro de un contenedor?

La propiedad flex en CSS te permite controlar el tamaño y el crecimiento de los elementos flexibles dentro de un contenedor Flexbox. Se compone de tres valores: flex-grow, flex-shrink y flex-basis.
```
flex: <flex-grow> <flex-shrink> <flex-basis>;
```

1. `flex-grow`: Define qué tan grande puede crecer un elemento en proporción a los demás elementos del contenedor cuando hay espacio adicional disponible.

2. `flex-shrink`: Define cuánto puede encogerse un elemento en proporción a los demás cuando el espacio en el contenedor es limitado.

3. `flex-basis`: Define el tamaño inicial de un elemento antes de que se aplique flex-grow o flex-shrink.

## ¿Cuáles son las diferencias entre los formatos de color RGB, RGBA, hexadecimal y HSL en CSS, y en qué situaciones sería más conveniente utilizar cada uno?

## Comparativa de Formatos de Color en CSS

| **Formato**   | **Ventaja principal**                                    | **Inconveniente**                                  | **Usos típicos**                            |
|---------------|----------------------------------------------------------|---------------------------------------------------|---------------------------------------------|
| **RGB**       | Precisión y control directo de los colores               | Sin transparencia, menos intuitivo que HSL       | Colores sólidos, diseños basados en números |
| **RGBA**      | Transparencia integrada                                  | Menos intuitivo que HSL                          | Superposiciones, efectos de transparencia   |
| **Hexadecimal** | Compacto y fácil de compartir                          | Menos legible o ajustable                        | Web estándar, compatibilidad amplia         |
| **HSL**       | Fácil de ajustar tono, saturación y brillo               | No tan compacto como Hex                         | Temas dinámicos, gradientes                 |
| **HSLA**      | Transparencia más intuitiva que RGBA                     | Similar a RGBA                                   | Variantes de colores con opacidad           |



<p align="center">
<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" />
</p>
