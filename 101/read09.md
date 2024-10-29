# READ 09: Introducción a Javascript

<img src="../Blog/assets/jsCover.png" alt="illustration a man and his laptop" alt ="destiny image">

## 1 ¿Cuáles son los diferentes tipos de datos que se pueden utilizar en JavaScript y cómo se diferencian entre sí?

- **Booleano:** `true` y `false`.
- **null:** Una palabra clave especial que denota un valor nulo. (Dado que JavaScript distingue entre mayúsculas y minúsculas, `null` no es lo mismo que `Null`, `NULL` o cualquier otra variante).
- **undefined:** Una propiedad de alto nivel cuyo valor no está definido.
- **Number:** Un número entero o un número con coma flotante. Por ejemplo: `42` o `3.14159`.
- **BigInt:** Un número entero con precisión arbitraria. Por ejemplo: `9007199254740992n`.
- **String:** Una secuencia de caracteres que representan un valor de texto. Por ejemplo: `"Hola"`
- **Symbol:** Un tipo de dato cuyas instancias son únicas e inmutables
- **object:** Una estructura de datos que contiene datos e instrucciones para trabajar con datos.

## 2 ¿Cómo se utilizan las estructuras condicionales `if` y `else` en JavaScript, y qué propósito cumplen dentro de un programa?

Imagina que estás jugando un videojuego. Hay momentos en los que tienes que tomar decisiones, ¿verdad? Pues en programación, la palabra clave `"if"` es como un punto de decisión para tu programa. Le dice al programa: **"Si pasa esto, haz esto, pero si no, haz otra cosa".**
Es como un camino con bifurcaciones: si la condición es verdadera, el programa toma un camino, y si es falsa, toma otro. Así, puedes hacer que tu programa se comporte de manera diferente según las circunstancias.

Por ejemplo: Si un niño quiere entrar a un juego:

```javascript
if (niño.edad >= 3) {
  niño.accedeAlJuego = true;
} else {
  niño.accedeAlJuego = false;
}
```

O de forma más concisa:

```
if (niño.edad >= 3) {
  console.log("El niño puede acceder al juego");
}
```

Mientras tanto, el else brinda una alternativa a la condición inicial cuando la condición inicial (if) es falsa.<br>
Ejemplo:

```
if (age >= 18) {
  console.log("Puedes votar");
} else {
  console.log("NO puedes votar");
}
```

if  y else controlan el flujo de toma de decisiones basado en un juego o set de condiciones que determinan qué bloque de código será ejecutado dependiendo de si la condición es verdadera o falsa.

## 3 ¿Cuáles son los diferentes tipos de operadores en JavaScript y cómo se utilizan los operadores aritméticos para realizar cálculos?

1. Suma (+): Suma dos operandos.
Ejemplo: 5 + 3 = 8
1. Resta (-): Resta el segundo operando del primero.
Ejemplo: 10 - 5 = 5
1. Multiplicación (*): Multiplica dos operandos.
Ejemplo: 4* 2 = 8
1. División (/): Divide el primer operando por el segundo.
Ejemplo: 10 / 2 = 5
1. Módulo ( % ): Devuelve el residuo de una división.
Ejemplo: 10 % 3 = 1 (10 dividido por 3 deja un residuo de 1)
1. Exponenciación ( **): Eleva el primer operando a la potencia del segundo.
Ejemplo: 2** 3 = 8 (2 elevado a la potencia de 3 es 8)
1. Más Unario (+): Convierte una cadena a un número.
Ejemplo: + "10" = 10
1. Menos Unario (-): Niega un número.
Ejemplo: -5 = -5

# 4 ¿Cómo se declara una variable en JavaScript y cuáles son las diferencias entre var, let y const en cuanto a su alcance y mutabilidad?

<h3>var</h3>
Alcance: Funcional. Esto significa que una variable declarada con var está disponible en todo el ámbito de la función en la que se declara.
Mutabilidad: Mutable. Puedes cambiar el valor de una variable var después de haberla declarado.
Ejemplo:

```
function miFuncion() {
  var nombre = "Juan"; // Disponible dentro de la función miFuncion()
  console.log(nombre); // Imprime "Juan"
  nombre = "Pedro"; // Se puede modificar el valor
  console.log(nombre); // Imprime "Pedro"
}
```

let
Alcance: Bloque. Esto significa que una variable declarada con let está disponible dentro del bloque de código (entre llaves {}) en el que se declara.
Mutabilidad: Mutable. Puedes cambiar el valor de una variable let después de haberla declarado.
Ejemplo:

```
if (true) {
  let edad = 25; // Disponible solo dentro del bloque if
  console.log(edad); // Imprime "25"
  edad = 30; // Se puede modificar el valor
  console.log(edad); // Imprime "30"
}

// console.log(edad); // Error: edad no está definida fuera del bloque if
```

const
Alcance: Bloque. Al igual que let, una variable const está disponible dentro del bloque de código en el que se declara.
Mutabilidad: Inmutable. El valor de una variable const no se puede cambiar después de haberla declarado.
Ejemplo:

```
const apellido = "Pérez"; // Disponible solo dentro del bloque if
console.log(apellido); // Imprime "Pérez"

// apellido = "García"; // Error: No se puede modificar el valor
```

| Tipo     | Alcance      | Mutabilidad   | Notas                                          |
| -------- | ------------ | ------------- | ------------------------------------------------ |
| `var`    | Funcional    | Mutable       | Obsoleto, se recomienda usar `let` o `const` |
| `let`    | Bloque       | Mutable       | Se puede reasignar un nuevo valor                |
| `const`  | Bloque       | Inmutable      | No se puede reasignar un nuevo valor             |
