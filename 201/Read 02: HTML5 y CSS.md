
<img src="https://i0.wp.com/www.namecheap.com/blog/wp-content/uploads/2022/08/What-are-HTML5-and-CSS3-how-are-they-used.png?quality=100" alt="illustration">

# Read 02: HTML5 y **CSS**

### ¿Cuáles son las ventajas del uso de HTML semántico en comparación con el uso de etiquetas genéricas como `<div>`

El HTML semántico utiliza etiquetas que describen el contenido `<header>`, `<article>`, `<nav>`, etc. Esto es mejor que usar solo `<div>` porque:

- Es más fácil entender el código.
- Los motores de búsqueda entienden mejor tu sitio web.
- Las personas con discapacidad pueden usar tu sitio web más fácilmente.

### ¿Qué etiquetas semánticas son esenciales para estructurar correctamente una página web y qué función desempeñan?

- `<header>`: Representa el encabezado de la página, que generalmente contiene el logotipo, el título del sitio y la navegación principal.
- `<nav>`: Define una sección de navegación, ya sea un menú principal u otro conjunto de enlaces.
- `<main>`: Encierra el contenido principal de la página, excluyendo el encabezado, el pie de página y las barras laterales.
- `<article>`: Representa un contenido independiente y autocontenido, como una entrada de blog, un artículo de noticias, etc.
- `<aside>`: Define contenido relacionado con el contenido principal, como una barra lateral, un comentario, etc.
- `<footer>`: Representa el pie de página de la página, que generalmente contiene información de copyright, enlaces a políticas de privacidad, etc.
- `<section>`: Divide el contenido principal en secciones temáticas.
- `<figure>`: Encierra una imagen, un diagrama o un fragmento de código, junto con su leyenda, si la tiene.
- `<figcaption>`: Proporciona una leyenda o descripción para una figura.
Otras etiquetas importantes:
- `<address>`: Define la dirección física de una persona o una organización.
- `<time>`: Representa una fecha y/o hora.
- `<mark>`: Resalta un texto.
- `<details>`: Proporciona información adicional que se puede expandir o contraer.
- `<summary>`: Define el título o resumen de un bloque de detalles.

### ¿Cuál es la función principal de las media queries en CSS y cómo contribuyen al diseño responsivo de una página web?

- La función principal de las media queries en CSS controlar la aplicación del estilo CSS en función al dispositivo donde se accede a la web.

- Las media queries permiten definir reglas CSS que se aplican únicamente cuando se cumplen ciertas condiciones, como el ancho de la pantalla, la orientación (horizontal o vertical), la resolución, el tipo de dispositivo (móvil, escritorio, etc.) o incluso las capacidades de impresión.

```
@media (max-width: 768px) {
  .container {
    width: 90%;
  }
}
```

Esta media query se aplica cuando el ancho de la pantalla es menor o igual a 768px. En este caso, la regla dice que el contenedor tendrá un ancho del 90%

### ¿Cuáles son las diferencias clave entre las unidades absolutas y relativas en CSS, y en qué situaciones es más apropiado utilizar cada tipo?

- Unidades absolutas: Las unidades absolutas tienen un tamaño fijo, independiente del contexto. Algunos ejemplos de unidades absolutas son:
    - **px** *(píxeles)* : El píxel es la unidad más común y representa un punto físico en la pantalla.
    - **cm** *(centímetros)* : Representa un centímetro físico.
    - **mm** *(milímetros)* : Representa un milímetro físico.
    - **in** *(pulgadas)* : Representa una pulgada física.
    - **pt** *(puntos)* : Un punto equivale a 1/72 de pulgada.
    - **pc** *(picas)* : Una pica equivale a 12 puntos.

- Unidades relativas: Las unidades relativas se basan en el tamaño de otros elementos o el tamaño de la ventana del navegador.

    - **em** : Representa el tamaño de la fuente del elemento padre.
    - **rem** : Representa el tamaño de la fuente del elemento raíz (html).
    - **%** *(porcentaje)* : Representa un porcentaje del tamaño del elemento padre.
    - **vw** *(viewport width)* : Representa un porcentaje del ancho de la ventana del navegador.
    - **vh** *(viewport height)* : Representa un porcentaje del alto de la ventana del navegador.
    - **vmin** : Representa el valor mínimo entre vw y vh.
    - **vmax** : Representa el valor máximo entre vw y vh.

<p align="center">
<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" />
</p>