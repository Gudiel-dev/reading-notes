<img src="https://wpcork.com/wp-content/uploads/2018/10/What-Is-CSS.jpg" alt="css image refference">

# Read 03: Intro a CSS

## Qué es CSS?
CSS es un lenguaje por el cual podemos controlar la forma en que mostramos la información / contenido de una página web manipulando el color, tamaño. etc.
Dicho de otro modo, vendría a ser un kit de herramientas para hacer que la web se vea del modo exacto en que lo teníamos en mente

## ¿Qué analogía NO técnica usarías para explicar la responsabilidad de HTML vs. CSS?

La responsabilidad del HTML vendría a ser algo así como la estructura de una cada sin ningun acabado. Tendríamos una casa con la estructura suficiente para ser
funcional. Por otro lado, el CSS vendría a ser todo el acabado que se implementa como decoración, color de paredes, iluminación etc. Teniendo como resultado el uso de ambos elementos
un lugar que podría ser habitable, y no sólo eso. Sino que, sería acogedor y reconfortante.

## ¿Cuáles son las tres formas de insertar CSS en tu proyecto?
- **External CSS:**
Suele ser el más común e ideal para sitios grandes donde se crea el css de manera separada y se enlaza por medio de un `<link>` dentro del `<head>` del html. Fácil de implementar y su reutilización
```
   <!DOCTYPE html>
   <html>
   <head>
     <title>Mi página web</title>
     <link rel="stylesheet" href="styles.css"> 
   </head>
   <body>
     <!-- Contenido de la página web -->
   </body>
   </html>
```
- **Internal CSS:**
  Usualmente para proyectos pequeños o específicos. Suele ser menos organizado o no amigable a la vista, dificultando su lectura.
Se aplica directamente en el HTML usando la etiqueta `<style>` dentro del `<head>`
```
  <!DOCTYPE html>
   <html>
   <head>
     <title>Mi página web</title>
     <style>
       body {
         background-color: #f0f0f0;
       }
       h1 {
         color: blue;
       }
     </style>
   </head>
   <body>
     <!-- Contenido de la página web -->
   </body>
   </html>
  ```

- **Inline CSS:**
  Se aplica las reglas CSS a directamente a 'elementos' utilizando el atributo style.
Suele ser el menos recomendado dificultando el mantenimiento y organización del mismo.
```
<!DOCTYPE html>
   <html>
   <head>
     <title>Mi página web</title>
   </head>
   <body>
     <h1 style="color: red;">Título de la página</h1>
     <!-- Contenido de la página web -->
   </body>
   </html>
```

## Escribe un ejemplo de una regla CSS que daría texto rojo a todos los elementos <p>.
```
<!DOCTYPE html>
<html>
<head>
  <title>CSS Demo</title>
</head>
<body>
  <h1 style="color: red;">My CSS</h1>
  <p style="color: orange">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent sem justo, ornare vel rhoncus et, 
    elementum eget massa. Aenean fringilla tempus erat, in consectetur orci mattis vel. Lorem ipsum dolor 
    sit amet, consectetur adipiscing elit. Morbi efficitur finibus leo sed semper. Orci varius natoque 
    penatibus et magnis dis parturient montes, nascetur ridiculus mus. Aenean lorem nunc, faucibus vitae 
    tempor quis, euismod sit amet lacus. Sed elementum odio ac rhoncus elementum. Curabitur vestibulum, 
    ligula sed fermentum semper, justo velit mattis metus, sit amet volutpat mauris ipsum vel diam. Fusce 
    neque sapien, accumsan in leo id, mollis iaculis urna. Vivamus finibus gravida turpis vitae elementum.
  </p>
  
  <!-- Contenido de la página web -->
</body>
</html>
```
