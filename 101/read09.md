# READ 09: Introducción a Javascript
<img src="../Blog/assets/jsCover.png" alt="illustration a man and his laptop" alt ="destiny image">

## ¿Cuáles son los diferentes tipos de datos que se pueden utilizar en JavaScript y cómo se diferencian entre sí?

	- **Booleano:** true y false.
	- ##null:## Una palabra clave especial que denota un valor nulo. (Dado que JavaScript distingue entre mayúsculas y minúsculas, null no es lo mismo que Null, NULL o cualquier otra variante).
	- ##undefined## Una propiedad de alto nivel cuyo valor no está definido.
	- ##Number:## Un número entero o un número con coma flotante. Por ejemplo: 42 o 3.14159.
	- ##BigInt## Un número entero con precisión arbitraria. Por ejemplo: 9007199254740992n.
	- ##String.## Una secuencia de caracteres que representan un valor de texto. Por ejemplo: "Hola"
	- ##Symbol ## n tipo de dato cuyas instancias son únicas e inmutables
	- ##object## Una estrucutra de datos que contiene datos e instrucciones para trabajar con datos.

¿Cómo se utilizan las estructuras condicionales if y else en JavaScript, y qué propósito cumplen dentro de un
programa?
los if se utilizan para validar condiciones. 
Si un niño quiere entrar a un juego.
##if## niño es mayor a 3 años, el niño puede acceder al juego
	##else##
	el niño no podrá entrar al juego
	
	if n > 3:
		niño accede al juego
	else
		niño no puede acceder al juego
Mientras tanto, el else brinda una alternativa a la condición inicial cuando la codición inicial (if) es falsa

If condition A es falsa
then hacer esto

if (age >=18){
	console.log("Puedes votar")
	}else{
	console.log("NO puedes votar")
	}
	

if  y else controlan el flujo de toma de decisiones basado en un juego o set de condiciones que determinan qué bloque de código será ejecutado dependiendo de si la condición es verdadera o falsa.

¿Cuáles son los diferentes tipos de operadores en JavaScript y cómo se utilizan los operadores aritméticos para realizar cálculos?
1. Suma (+): Suma dos operandos.
Ejemplo: 5 + 3 = 8
2. Resta (-): Resta el segundo operando del primero.
Ejemplo: 10 - 5 = 5
3. Multiplicación (*): Multiplica dos operandos.
Ejemplo: 4 * 2 = 8
4. División (/): Divide el primer operando por el segundo.
Ejemplo: 10 / 2 = 5
5. Módulo ( % ): Devuelve el residuo de una división.
Ejemplo: 10 % 3 = 1 (10 dividido por 3 deja un residuo de 1)
6. Exponenciación ( ** ): Eleva el primer operando a la potencia del segundo.
Ejemplo: 2 ** 3 = 8 (2 elevado a la potencia de 3 es 8)
7. Más Unario (+): Convierte una cadena a un número.
Ejemplo: + "10" = 10
8. Menos Unario (-): Niega un número.
Ejemplo: -5 = -5

Tipo     Alcance      Mutabilidad   Notas
var --> funciomal ---> mutable --> Obsoleto, se recomienda usar let o const
let --> Bloque ---> Mutable --> Se puede reasignar un nuevo valor
const --> Bloque --> Inmutable --> No se puede reasignar un nuevo valor

var:
Declaración: var nombreVariable = valor;


let:
Declaración: let nombreVariable = valor;


const:
Declaración: const nombreVariable = valor;

