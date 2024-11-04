<img src="https://programadorviking.com.br/wp-content/uploads/2022/12/DOM-Document-Object-Model.png" alt="image showing off DOM structure and its relationship with a html structure.">

# Read 11: Introducción al DOM y Proyectos

## 1- ¿Qué es el DOM?

- El DOM vendría a ser el mapa que nos permite navegar por la estructura de nuestra web y hacer los cambios necesarios donde sea requerido.

## 1. Describe brevemente la relación entre el DOM y JavaScript.

JavaScript a traves del DOM le da vida a las páginas web, permitiéndolas ser interactivas y dinámicas.

JavaScript utiliza al DOM como puente para interactuar con un documento HTML accediendo a:
- Elementos HTML
- Modificar contenido
- Cambiar estilos
- Agregar eventos

## 1. ¿Qué método usarías para seleccionar un elemento del DOM por su ID y cómo se utiliza?
```jsx

 // Elemento HTML con ID “mi-elemento” 

 <div id = “mi-elemento”> Enter Tech </div>

// selección del elemento por su ID 

const miElemento = document.getELementById(”mi-elemento”);

// Impresión del elemento

console.log.(miElemento);

// Cambiar contenido del elemento

 miElemento.innerHTML = “Nuevo contenido”;

 ```

## 1. ¿Qué método utilizarías para cambiar el color de fondo de un elemento en el DOM y cómo se implementaría?

```jsx
// forma simple
style.backgroundColor

// completa
miElemento.style.backgroundColor = "#FF0000"; // Rojo
```

```jsx
// Supongamos que tienes un elemento HTML con el ID "mi-elemento"
<div id="mi-elemento">Hola, mundo</div>

// Selecciona el elemento por su ID
const miElemento = document.getElementById("mi-elemento");

// Cambia el color de fondo a rojo
miElemento.style.backgroundColor = "red";
```

<p align="center">
<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" />
</p>