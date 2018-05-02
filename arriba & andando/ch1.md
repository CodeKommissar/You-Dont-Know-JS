# Tu No Sabes JS: Arriba & Andando
# Capítulo 1: En La Programación

Bienvenido a la serie *Tu No Sabes JS* (*TNSJS*).

*Arriba & Andando* es una introducción a varios conceptos básicos de la programación -- por supuesto, nos inclinaremos mas por JavaScript (a menudo abreviado JS) específicamente -- y cómo abordar y comprender el resto de los títulos en esta serie. Especialmente, si apenas estas ingresando al mundo de la programación y/o JavaScript, este libro explorará brevemente lo qué necesitas para ponerte *arriba y andando*.

Este libro comienza explicando los principios básicos de la programación desde un nivel bastante alto. Está principal propósito es si estas comenzando *TNSJS* con poca o ninguna experiencia de programación previa, y estás mirando hacia estos libros para ayudarte a comenzar a lo largo de un camino hacia la comprensión de la programación a través del lente de JavaScript.

El Capítulo 1 debe abordarse como una rápida descripción general de las cosas que sobre las que querrás aprender más y practicar para meterte *en la programación*. También hay muchos otros recursos fantásticos de introducción a la programación que pueden ayudarte a profundizar en estos temas, y te aliento a que aprendas de ellos en adición a este capítulo.

Una vez que te sientas cómodo con los conceptos básicos de la programación en general, el Capítulo 2 te ayudará a familiarizarte con el sabor de la programación en JavaScript. El Capítulo 2 es una introducción acerca de qué trata JavaScript, pero una vez más, no es una guía completa -- para eso son el resto de los libros en *TNSJS*!

Si ya te sientes bastante cómodo con JavaScript, chequea primero al Capítulo 3 como un breve vistazo de qué puedes esperar de *TNSJS*, y luego salta directamente!

## Código

Vamos a empezar desde el principio.

Un programa, a menudo denominado *código fuente* o simplemente *código*, es un conjunto de instrucciones especiales que le indican a la computadora qué tareas debe realizar. Por lo general, el código se guarda en un archivo de texto, aunque con JavaScript también puedes escribir el código directamente en una consola de desarrollador en un navegador, la cual veremos en breve.

Las reglas para las combinaciones de instrucciones validás y el formato en general del código son llamadas un *lenguaje informático*, y a veces denominadas como su *sintaxis*, muy parecido a como el español te indica cómo deletrear palabras y cómo crear oraciones válidas utilizando palabras y signos de puntuación.

### Declaraciones

En un lenguaje informático, un grupo de palabras, números y operadores que realiza una tarea específica es una *declaración*. En JavaScript, una declaración puede verse de la siguiente manera:

```js
a = b * 2;
```

Los caracteres `a` y `b` se llaman *variables* (ver "Variables"), que son como simples cajas en las cuales puedes almacenar cualquiera de tus cosas. En los programas, las variables contienen valores (como el número `42`) que seran utilizados por el programa. Piensa en ellas como marcadores simbólicos de los valores en si mismos.

Por el contrario, el `2` es solo un valor en sí mismo, llamado un *valor literal*, porque está solo sin estar almacenado en una variable.

Los caracteres `=` y `*` son *operadores* (ver "Operadores") -- realizan acciones con los valores y variables tales como la asignación y la multiplicación matemática.

La mayoría de las declaraciones en JavaScript concluyen con un punto y coma (`;`) al final.

La declaración `a = b * 2;` le dice a la computadora, aproximadamente, que obtenga el valor actual almacenado en la variable `b`, multiplica ese valor por `2`, y luego almacena el resultado en otra variable a la que llamaremos `a`.

Los programas son solo colecciones de muchas declaraciones de este tipo, que juntas describen todos los pasos necesarios para llevar a cabo el propósito de tu programa.

### Expresiones

Las declaraciones se componen de una o más *expresiones*. Una expresión es cualquier referencia a una variable o valor, o un conjunto de variable(s) y valor(es) combinados con operadores.

Por ejemplo:

```js
a = b * 2;
```

Esta declaración tiene cuatro expresiones en ella:

* `2` es una *expresión de valor literal*
* `b` es una *expresión variable*, lo que significa obtener su valor actual
* `b * 2` es una *expresión aritmética*, que significa hacer la multiplicación
* `a = b * 2` es una *expresión de asignación*, lo que significa asignar el resultado de la expresión `b * 2` a la variable `a` (más sobre acerca de las asignaciones más adelante)

Una expresión general independiente es también llamada *expresión de declaración*, como la siguiente:

```js
b * 2;
```

Esta forma de expresión de declaración no es muy común ni útil, ya que generalmente no tendría ningún efecto en la ejecución del programa -- obtendría el valor de `b` y lo multiplicaría por `2`, pero luego no haría nada con ese resultado.

Una expresión de declaración más común es una declaración de *expresión de llamada* (ver "Funciones"), ya que toda la declaración es la expresión de llamada a la función en sí:

```js
alert( a );
```

### Ejecutando un programa

Cómo le dicen esas colecciones de declaraciones de programación a la computadora qué hacer? El programa debe *ejecutarse*, también referido como *ejecutar el programa*.

Las declaraciones como `a = b * 2` son útiles para los desarrolladores al leer y escribir, pero en realidad no están en una forma que la computadora pueda comprender directamente. Por lo tanto, se usa una utilidad especial en la computadora (ya sea un *intérprete* o un *compilador*) para traducir el código que se escribe a comandos que una computadora puede entender.

Para algunos lenguajes de computadora, esta traducción de comandos generalmente se realiza de arriba a abajo, línea por línea, cada vez que se ejecuta el programa, lo que generalmente se conoce como *interpretación* del código.

Para otros idiomas, la traducción se realiza de antemano, lo que se conoce como *compilar* el código, por lo que cuando el programa *se ejecuta* más tarde, lo que se está ejecutando es en realidad las instrucciones de la computadora ya compiladas listas para funcionar.

Por lo general, se afirma que JavaScript es *interpretado*, porque el código fuente de JavaScript se procesa cada vez que se ejecuta. Pero eso no es del todo exacto. El motor JavaScript en realidad *compila* el programa sobre la marcha y luego ejecuta inmediatamente el código compilado.

**Nota:** Para obtener más información sobre compilación de JavaScript, consulta los dos primeros capítulos del título *Alcance & Cierres* de esta serie.

## Inténtalo Tú Mismo

Este capítulo presentará cada concepto de programación con simples fragmentos de código, todo escrito en JavaScript (obviamente!).

No puede ser enfatizado lo suficiente: mientras lees este capítulo -- y es posible que debas dedicar tiempo a repasarlo varias veces -- debes practicar cada uno de estos conceptos escribiendo el código por ti mismo. La forma más fácil de hacerlo es abrir la consola de herramientas de desarrollador en tu navegador más cercano (Firefox, Chrome, IE, etc.).

**Consejo:** Normalmente, puedes iniciar la consola de desarrollador con un atajo de teclado o desde un elemento de menú. Para obtener información más detallada sobre cómo iniciar y utilizar la consola en tu navegador favorito, consulte "Mastering The Developer Tools Console" (http://blog.teamtreehouse.com/mastering-developer-tools-console) (en inglés). Para escribir varias líneas en la consola a la vez, usa `<shift> + <enter>` para pasar a la siguiente nueva línea. Una vez que presionas la tecla `<enter>` por sí misma, la consola ejecutará todo lo que acabas de escribir.

Vamos a familiarizarnos con el proceso de ejecutar código en la consola. Primero, sugiero que abras una pestaña vacía en tu navegador. Yo prefiero hacer esto escribiendo `about:blank` en la barra de direcciones. Luego, asegúrate de que tu consola de desarrollador esté abierta, como acabamos de mencionar.

Ahora, escribe este código y ve cómo se ejecuta:

```js
a = 21;

b = a * 2;

console.log( b );
```

Escribir el código anterior en la consola de Google Chrome debería producir algo como lo siguiente:

<img src="fig1.png" width="500">

Vamos, pruébalo. La mejor forma de aprender a programar es comenzar a practicar!

### Salidas

En el fragmento de código anterior, usamos `console.log (..)`. Brevemente, veamos de qué se trata esa línea de código.

Es posible que ya lo hayas adivinado, pero así es exactamente como imprimimos texto (también conocido como *salida* para el usuario) en la consola de desarrollador. Hay dos características de esa declaración que deberiamos de explicar.

Primero, la parte `log( b )` se conoce como una llamada a función (ver "Funciones"). Lo que sucede es que le estamos entregando la variable `b` a esa función, que pide tomar el valor de `b` y lo imprime en la consola.

En segundo lugar, la parte `console` es una referencia de objeto a donde se encuentra la función `log(..)`. Cubriremos los objetos y sus propiedades con más detalle en el Capítulo 2.

Otra forma de crear salidas que puedas ver es ejecutar una declaracón `alert(..)`. Por ejemplo:

```js
alert( b );
```

Si ejecuta eso, notarás que en lugar de imprimir la salida en la consola, muestra un cuadro emergente "OK" con el contenido de la variable `b`. Sin embargo, usar `console.log(..)` generalmente hará que aprender sobre la codificación y ejecutar programas en la consola sea más fácil que usar `alert(..)`, ya que puede mostrar muchos valores a la vez sin interrumpir la interfaz de navegador.

Para este libro, usaremos `console.log (..)` para las salidas.

### Entradas

Mientras hablamos de lo que son las salidas, también puedes preguntarte acerca de las *entradas* (es decir, recibir información por parte del usuario).

La forma más común de que esto suceda es que la página HTML muestre elementos de formulario (como cuadros de texto) en los que el usuario pueda escribir, y luego usar JS para leer esos valores en las variables de tu programa.

Pero hay una forma más fácil de obtener entradas para el aprendizaje simple y propósitos de demostración, como lo que harás a lo largo de este libro. Usa la función `prompt(..)`:

```js
edad = prompt( "Por favor dime tu edad:" );

console.log( edad );
```

Como puedes haber adivinado, el mensaje que pasas a `prompt(..)` -- en este caso, `"Por favor dime tu edad:"` -- se imprime en la ventana emergente.

Esto debería ser similar a lo siguiente:

<img src="fig2.png" width="500">

Una vez que entregues el texto de entrada en la ventana emergente haciendo clic en "OK", observaras que el valor que escribiste está almacenado en la variable `edad`, que luego mostramos como *salida* con `console.log(..)`:

<img src="fig3.png" width="500">

Para mantener las cosas simples mientras aprendemos conceptos básicos de la programación, los ejemplos de este libro no requerirán entradas. Pero ahora que has visto cómo usar `prompt(..)`, si quieres desafiarte a ti mismo, puedes intentar utilizar entradas en tus exploraciones de los ejemplos.

## Operadores

Los operadores son la forma en que realizamos acciones sobre variables y valores. Ya hemos visto dos operadores en JavaScript, el `=` y el `*`.

El operador `*` realiza la multiplicación matemática. Simple, verdad?

El operador `=` igual se usa para la *asignación* -- primero calculamos el valor en el *lado derecho* (valor fuente) del `=` y luego lo ponemos en la variable que especificamos en el *lado izquierdo* (variable objetivo).

**Advertencia:** Este puede parecer un extraño orden inverso para especificar la asignación. En lugar de `a = 42`, algunos podrían preferir voltear el orden de modo que el valor fuente esté a la izquierda y la variable objetivo esté a la derecha, como `42 -> a` (esto no es JavaScript válido!). Desafortunadamente, la forma de orden `a = 42`, y variaciones similares, es bastante frecuente en los lenguajes de programación modernos. Si no se siente natural, dedica un tiempo a practicar ese orden en tu mente para acostumbrarte a él.

Considera:

```js
a = 2;
b = a + 1;
```

Aquí, asignamos el valor `2` a la variable `a`. Entonces, obtenemos el valor de la variable `a` (aún `2`) y le agregamos `1`, lo que da como resultado el valor `3`, luego almacenamos ese valor en la variable `b`.

Si bien técnicamente no es un operador, necesitarás usar la palabra clave `var` en cada programa, ya que es la forma principal en que *declaras* (en otras palabras, *creas*) *var*iables (consulta "Variables").

Siempre deberias declarar la variable por su nombre antes de usarla. Pero solo necesitas declarar una variable una vez por cada *alcance* (ver "Alcance"); después de eso puede usarse tantas veces como sea necesaria. Por ejemplo:

```js
var a = 20;

a = a + 1;
a = a * 2;

console.log( a );	// 42
```

Estos son algunos de los operadores más comunes en JavaScript:

* Asignación: `=` como en `a = 2`.
* Matemáticas: `+` (adición), `-` (substracción), `*` (multiplicación) y `/` (división), como en `a * 3`.
* Asignación Compuesta: `+=`, `-=`, `*=`, y `/=` son operadores compuestos que combinan una operación matemática con asignación, como en `a += 2` (es lo mismo que `a = a + 2`).
* Incremento/Decremento: `++` (incremento), `--`(decremento), como en `a++` (similar a `a = a + 1`).
* Acceso a la Propiedad del Objeto: `.` como en `console.log()`.

   Los objetos son valores que contienen otros valores en ubicaciones con nombres específicos llamadas propiedades. `obj.a` significa un valor de objeto llamado `obj` con una propiedad con el nombre `a`. Alternativamente las propiedades se puede acceder como `obj["a"]`. Ver el Capítulo 2.
* Igualdad: `==` (igualdad-permisiva), `===` (igualdad-estricta), `!=` (no-igualdad permisiva), `!==` (no-igualdad estricta), como en `a == b`.

   Consulta "Valores & Tipos" y el Capítulo 2.
* Comparación: `<` (menor que), `>` (mayor que), `<=` (menor que o igualdad-permisiva), `>=` (mayor que o igualdad-permisiva), como en `a <= b`.

   Consulta "Valores & Tipos" y el Capítulo 2.
* Lógicos: `&&` (y), `||` (o), como en `a || b` que selecciona ya sea `a` *o* `b`.

   Estos operadores se utilizan para expresar condicionales compuestos (ver "Condicionales"), como si `a` *o* `b` es verdadero.

**Nota:** Para obtener más detalles, y cobertura de los operadores que no se mencionan aquí, consulta "Expresiones y operadores" de Mozilla Developer Network (MDN) (https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators).

## Valores & Tipos

Si le preguntas a un empleado de una tienda de teléfonos cuánto cuesta cierto teléfono, y dicen "noventa y nueve con noventa y nueve" (es decir, $99.99), te están dando una cifra real numérica en dólares que representa lo que necesitas pagar (más impuestos) para comprarlo. Si deseas comprar dos de esos teléfonos, facilmente puedes hacer los cálculos mentales para duplicar ese valor y obtener $199.98 como su costo base.

Si ese mismo empleado toma otro teléfono similar pero dice que es "gratis" (quizás haciendo comillas con sus manos), no te estan dando un número, sino otro tipo de representación del costo esperado ($0.00) -- la palabra "gratis."

Cuando más tarde le preguntes si el teléfono incluye un cargador, esa respuesta solo podría haber sido "sí" o "no".

De maneras muy similares, cuando expresas valores en un programa, eliges diferentes representaciones para esos valores en función de lo que planeas hacer con ellos.

Estas diferentes representaciones para los valores se llaman *tipos* en la terminología de la programación. JavaScript tiene tipos incorporados para cada uno de estos llamados valores *primitivos*:

* Cuando necesites hacer matemáticas, quieres un `number` ("número" en español).
* Cuando necesites imprimir un valor en la pantalla, necesitarás un `string` (uno o más caracteres, palabras, oraciones).
* Cuando necesites tomar una decisión en tu programa, necesitas un `boolean`: `true` o `false` ("verdadero" o "falso", respectivamente).

Los valores que son incluidos directamente en el código fuente se llaman *literales*. Los literales `string` están rodeados por comillas dobles `"..."` o comillas simples (`'...'`) -- la única diferencia es la preferencia estilística. Los literales `number` y `boolean` son presentados tal y como están (es decir, `42`, `true`, etc.).

Considera:

```js
"Soy un string";
'Yo tambien soy un string';

42;

true;
false;
```

Más allá de los tipos de valores `string`/`number`/`boolean`, es común que los lenguajes de programación tambien proporcionen *arrays*, *objetos*, *funciones* y más. Cubriremos mucho más sobre valores y tipos a lo largo de este capítulo y el siguiente.

### Conversión Entre Tipos

Si tienes un `número` pero necesitas imprimirlo en la pantalla, debes convertir el valor a un `string`, y en JavaScript esta conversión se llama "coerción". Del mismo modo, si alguien ingresa una serie de caracteres numéricos en un formulario de una página de ecommerce, eso es un `string`, pero si necesitas usar ese valor para hacer operaciones matemáticas, necesitaras hacer uso de la *coerción* para convertirlo a un `number`.

JavaScript proporciona varias facilidades diferentes para forzar coerciones entre *tipos*. Por ejemplo:

```js
var a = "42";
var b = Number( a );

console.log( a );	// "42"
console.log( b );	// 42
```

El uso de `Number(..)` (una función incorporada) como se muestra es una coerción *explícita* de cualquier otro tipo al tipo `number`. Eso debería ser bastante sencillo.

Pero un tema controversial es lo que sucede cuando intentas comparar dos valores que ya no son del mismo tipo, lo que requeriría una coerción *implícita*.

Al comparar el string `"99.99"` con el número `99.99`, la mayoría de la gente estaría de acuerdo en que son equivalentes. Pero no son exactamente lo mismo, verdad? Es el mismo valor en dos representaciones diferentes, dos *tipos* diferentes. Podrías decir que son "permisivamente iguales", no?

Para ayudarte en estas situaciones comunes, JavaScript algunas veces se activará e *implícitamente* coaccionará los valores a los tipos que coincidan.

Entonces, si usas el operador permisivamente iguales `==` para hacer la comparación`"99.99" == 99.99`, JavaScript convertirá el lado izquierdo `"99.99"` a su `number` equivalente `99.99`. La comparación se convierte en `99.99 == 99.99`, lo que es, por supuesto, `true` ("verdadera").

Si bien está diseñado para ayudarte, la coerción implícita puede crear confusión si no te has tomado el tiempo de aprender las reglas que rigen su comportamiento. La mayoría de los desarrolladores de JS nunca lo han hecho, por lo que la sensación común es que la coerción implícita es confusa y perjudica a los programas con errores inesperados, por lo que debe ser evitada. Incluso a veces es llamada un defecto en el diseño del lenguaje.

Sin embargo, la coerción implícita es un mecanismo *que puede aprenderse* y, además, *debe ser aprendida* por cualquiera que desee tomar en serio la programación en JavaScript. No solo no es confusa una vez que aprendas las reglas, sino que tambien puede mejorar tus programas. El esfuerzo bien vale la pena.

**Nota:** Para obtener más información sobre la coerción, consulta el Capítulo 2 de este título y el Capítulo 4 del título *Tipos & Gramatica* de esta serie.

## Code Comments

The phone store employee might jot down some notes on the features of a newly released phone or on the new plans her company offers. These notes are only for the employee -- they're not for customers to read. Nevertheless, these notes help the employee do her job better by documenting the hows and whys of what she should tell customers.

One of the most important lessons you can learn about writing code is that it's not just for the computer. Code is every bit as much, if not more, for the developer as it is for the compiler.

Your computer only cares about machine code, a series of binary 0s and 1s, that comes from *compilation*. There's a nearly infinite number of programs you could write that yield the same series of 0s and 1s. The choices you make about how to write your program matter -- not only to you, but to your other team members and even to your future self.

You should strive not just to write programs that work correctly, but programs that make sense when examined. You can go a long way in that effort by choosing good names for your variables (see "Variables") and functions (see "Functions").

But another important part is code comments. These are bits of text in your program that are inserted purely to explain things to a human. The interpreter/compiler will always ignore these comments.

There are lots of opinions on what makes well-commented code; we can't really define absolute universal rules. But some observations and guidelines are quite useful:

* Code without comments is suboptimal.
* Too many comments (one per line, for example) is probably a sign of poorly written code.
* Comments should explain *why*, not *what*. They can optionally explain *how* if that's particularly confusing.

In JavaScript, there are two types of comments possible: a single-line comment and a multiline comment.

Consider:

```js
// This is a single-line comment

/* But this is
       a multiline
             comment.
                      */
```

The `//` single-line comment is appropriate if you're going to put a comment right above a single statement, or even at the end of a line. Everything on the line after the `//` is treated as the comment (and thus ignored by the compiler), all the way to the end of the line. There's no restriction to what can appear inside a single-line comment.

Consider:

```js
var a = 42;		// 42 is the meaning of life
```

The `/* .. */` multiline comment is appropriate if you have several lines worth of explanation to make in your comment.

Here's a common usage of multiline comments:

```js
/* The following value is used because
   it has been shown that it answers
   every question in the universe. */
var a = 42;
```

It can also appear anywhere on a line, even in the middle of a line, because the `*/` ends it. For example:

```js
var a = /* arbitrary value */ 42;

console.log( a );	// 42
```

The only thing that cannot appear inside a multiline comment is a `*/`, because that would be interpreted to end the comment.

You will definitely want to begin your learning of programming by starting off with the habit of commenting code. Throughout the rest of this chapter, you'll see I use comments to explain things, so do the same in your own practice. Trust me, everyone who reads your code will thank you!

## Variables

Most useful programs need to track a value as it changes over the course of the program, undergoing different operations as called for by your program's intended tasks.

The easiest way to go about that in your program is to assign a value to a symbolic container, called a *variable* -- so called because the value in this container can *vary* over time as needed.

In some programming languages, you declare a variable (container) to hold a specific type of value, such as `number` or `string`. *Static typing*, otherwise known as *type enforcement*, is typically cited as a benefit for program correctness by preventing unintended value conversions.

Other languages emphasize types for values instead of variables. *Weak typing*, otherwise known as *dynamic typing*, allows a variable to hold any type of value at any time. It's typically cited as a benefit for program flexibility by allowing a single variable to represent a value no matter what type form that value may take at any given moment in the program's logic flow.

JavaScript uses the latter approach, *dynamic typing*, meaning variables can hold values of any *type* without any *type* enforcement.

As mentioned earlier, we declare a variable using the `var` statement -- notice there's no other *type* information in the declaration. Consider this simple program:

```js
var amount = 99.99;

amount = amount * 2;

console.log( amount );		// 199.98

// convert `amount` to a string, and
// add "$" on the beginning
amount = "$" + String( amount );

console.log( amount );		// "$199.98"
```

The `amount` variable starts out holding the number `99.99`, and then holds the `number` result of `amount * 2`, which is `199.98`.

The first `console.log(..)` command has to *implicitly* coerce that `number` value to a `string` to print it out.

Then the statement `amount = "$" + String(amount)` *explicitly* coerces the `199.98` value to a `string` and adds a `"$"` character to the beginning. At this point, `amount` now holds the `string` value `"$199.98"`, so the second `console.log(..)` statement doesn't need to do any coercion to print it out.

JavaScript developers will note the flexibility of using the `amount` variable for each of the `99.99`, `199.98`, and the `"$199.98"` values. Static-typing enthusiasts would prefer a separate variable like `amountStr` to hold the final `"$199.98"` representation of the value, because it's a different type.

Either way, you'll note that `amount` holds a running value that changes over the course of the program, illustrating the primary purpose of variables: managing program *state*.

In other words, *state* is tracking the changes to values as your program runs.

Another common usage of variables is for centralizing value setting. This is more typically called *constants*, when you declare a variable with a value and intend for that value to *not change* throughout the program.

You declare these *constants*, often at the top of a program, so that it's convenient for you to have one place to go to alter a value if you need to. By convention, JavaScript variables as constants are usually capitalized, with underscores `_` between multiple words.

Here's a silly example:

```js
var TAX_RATE = 0.08;	// 8% sales tax

var amount = 99.99;

amount = amount * 2;

amount = amount + (amount * TAX_RATE);

console.log( amount );				// 215.9784
console.log( amount.toFixed( 2 ) );	// "215.98"
```

**Note:** Similar to how `console.log(..)` is a function `log(..)` accessed as an object property on the `console` value, `toFixed(..)` here is a function that can be accessed on `number` values. JavaScript `number`s aren't automatically formatted for dollars -- the engine doesn't know what your intent is and there's no type for currency. `toFixed(..)` lets us specify how many decimal places we'd like the `number` rounded to, and it produces the `string` as necessary.

The `TAX_RATE` variable is only *constant* by convention -- there's nothing special in this program that prevents it from being changed. But if the city raises the sales tax rate to 9%, we can still easily update our program by setting the `TAX_RATE` assigned value to `0.09` in one place, instead of finding many occurrences of the value `0.08` strewn throughout the program and updating all of them.

The newest version of JavaScript at the time of this writing (commonly called "ES6") includes a new way to declare *constants*, by using `const` instead of `var`:

```js
// as of ES6:
const TAX_RATE = 0.08;

var amount = 99.99;

// ..
```

Constants are useful just like variables with unchanged values, except that constants also prevent accidentally changing value somewhere else after the initial setting. If you tried to assign any different value to `TAX_RATE` after that first declaration, your program would reject the change (and in strict mode, fail with an error -- see "Strict Mode" in Chapter 2).

By the way, that kind of "protection" against mistakes is similar to the static-typing type enforcement, so you can see why static types in other languages can be attractive!

**Note:** For more information about how different values in variables can be used in your programs, see the *Types & Grammar* title of this series.

## Blocks

The phone store employee must go through a series of steps to complete the checkout as you buy your new phone.

Similarly, in code we often need to group a series of statements together, which we often call a *block*. In JavaScript, a block is defined by wrapping one or more statements inside a curly-brace pair `{ .. }`. Consider:

```js
var amount = 99.99;

// a general block
{
	amount = amount * 2;
	console.log( amount );	// 199.98
}
```

This kind of standalone `{ .. }` general block is valid, but isn't as commonly seen in JS programs. Typically, blocks are attached to some other control statement, such as an `if` statement (see "Conditionals") or a loop (see "Loops"). For example:

```js
var amount = 99.99;

// is amount big enough?
if (amount > 10) {			// <-- block attached to `if`
	amount = amount * 2;
	console.log( amount );	// 199.98
}
```

We'll explain `if` statements in the next section, but as you can see, the `{ .. }` block with its two statements is attached to `if (amount > 10)`; the statements inside the block will only be processed if the conditional passes.

**Note:** Unlike most other statements like `console.log(amount);`, a block statement does not need a semicolon (`;`) to conclude it.

## Conditionals

"Do you want to add on the extra screen protectors to your purchase, for $9.99?" The helpful phone store employee has asked you to make a decision. And you may need to first consult the current *state* of your wallet or bank account to answer that question. But obviously, this is just a simple "yes or no" question.

There are quite a few ways we can express *conditionals* (aka decisions) in our programs.

The most common one is the `if` statement. Essentially, you're saying, "*If* this condition is true, do the following...". For example:

```js
var bank_balance = 302.13;
var amount = 99.99;

if (amount < bank_balance) {
	console.log( "I want to buy this phone!" );
}
```

The `if` statement requires an expression in between the parentheses `( )` that can be treated as either `true` or `false`. In this program, we provided the expression `amount < bank_balance`, which indeed will either evaluate to `true` or `false` depending on the amount in the `bank_balance` variable.

You can even provide an alternative if the condition isn't true, called an `else` clause. Consider:

```js
const ACCESSORY_PRICE = 9.99;

var bank_balance = 302.13;
var amount = 99.99;

amount = amount * 2;

// can we afford the extra purchase?
if ( amount < bank_balance ) {
	console.log( "I'll take the accessory!" );
	amount = amount + ACCESSORY_PRICE;
}
// otherwise:
else {
	console.log( "No, thanks." );
}
```

Here, if `amount < bank_balance` is `true`, we'll print out `"I'll take the accessory!"` and add the `9.99` to our `amount` variable. Otherwise, the `else` clause says we'll just politely respond with `"No, thanks."` and leave `amount` unchanged.

As we discussed in "Values & Types" earlier, values that aren't already of an expected type are often coerced to that type. The `if` statement expects a `boolean`, but if you pass it something that's not already `boolean`, coercion will occur.

JavaScript defines a list of specific values that are considered "falsy" because when coerced to a `boolean`, they become `false` -- these include values like `0` and `""`. Any other value not on the "falsy" list is automatically "truthy" -- when coerced to a `boolean` they become `true`. Truthy values include things like `99.99` and `"free"`. See "Truthy & Falsy" in Chapter 2 for more information.

*Conditionals* exist in other forms besides the `if`. For example, the `switch` statement can be used as a shorthand for a series of `if..else` statements (see Chapter 2). Loops (see "Loops") use a *conditional* to determine if the loop should keep going or stop.

**Note:** For deeper information about the coercions that can occur implicitly in the test expressions of *conditionals*, see Chapter 4 of the *Types & Grammar* title of this series.

## Loops

During busy times, there's a waiting list for customers who need to speak to the phone store employee. While there's still people on that list, she just needs to keep serving the next customer.

Repeating a set of actions until a certain condition fails -- in other words, repeating only while the condition holds -- is the job of programming loops; loops can take different forms, but they all satisfy this basic behavior.

A loop includes the test condition as well as a block (typically as `{ .. }`). Each time the loop block executes, that's called an *iteration*.

For example, the `while` loop and the `do..while` loop forms illustrate the concept of repeating a block of statements until a condition no longer evaluates to `true`:

```js
while (numOfCustomers > 0) {
	console.log( "How may I help you?" );

	// help the customer...

	numOfCustomers = numOfCustomers - 1;
}

// versus:

do {
	console.log( "How may I help you?" );

	// help the customer...

	numOfCustomers = numOfCustomers - 1;
} while (numOfCustomers > 0);
```

The only practical difference between these loops is whether the conditional is tested before the first iteration (`while`) or after the first iteration (`do..while`).

In either form, if the conditional tests as `false`, the next iteration will not run. That means if the condition is initially `false`, a `while` loop will never run, but a `do..while` loop will run just the first time.

Sometimes you are looping for the intended purpose of counting a certain set of numbers, like from `0` to `9` (ten numbers). You can do that by setting a loop iteration variable like `i` at value `0` and incrementing it by `1` each iteration.

**Warning:** For a variety of historical reasons, programming languages almost always count things in a zero-based fashion, meaning starting with `0` instead of `1`. If you're not familiar with that mode of thinking, it can be quite confusing at first. Take some time to practice counting starting with `0` to become more comfortable with it!

The conditional is tested on each iteration, much as if there is an implied `if` statement inside the loop.

We can use JavaScript's `break` statement to stop a loop. Also, we can observe that it's awfully easy to create a loop that would otherwise run forever without a `break`ing mechanism.

Let's illustrate:

```js
var i = 0;

// a `while..true` loop would run forever, right?
while (true) {
	// stop the loop?
	if ((i <= 9) === false) {
		break;
	}

	console.log( i );
	i = i + 1;
}
// 0 1 2 3 4 5 6 7 8 9
```

**Warning:** This is not necessarily a practical form you'd want to use for your loops. It's presented here for illustration purposes only.

While a `while` (or `do..while`) can accomplish the task manually, there's another syntactic form called a `for` loop for just that purpose:

```js
for (var i = 0; i <= 9; i = i + 1) {
	console.log( i );
}
// 0 1 2 3 4 5 6 7 8 9
```

As you can see, in both cases the conditional `i <= 9` is `true` for the first 10 iterations (`i` of values `0` through `9`) of either loop form, but becomes `false` once `i` is value `10`.

The `for` loop has three clauses: the initialization clause (`var i=0`), the conditional test clause (`i <= 9`), and the update clause (`i = i + 1`). So if you're going to do counting with your loop iterations, `for` is a more compact and often easier form to understand and write.

There are other specialized loop forms that are intended to iterate over specific values, such as the properties of an object (see Chapter 2) where the implied conditional test is just whether all the properties have been processed. The "loop until a condition fails" concept holds no matter what the form of the loop.

## Functions

The phone store employee probably doesn't carry around a calculator to figure out the taxes and final purchase amount. That's a task she needs to define once and reuse over and over again. Odds are, the company has a checkout register (computer, tablet, etc.) with those "functions" built in.

Similarly, your program will almost certainly want to break up the code's tasks into reusable pieces, instead of repeatedly repeating yourself repetitiously (pun intended!). The way to do this is to define a `function`.

A function is generally a named section of code that can be "called" by name, and the code inside it will be run each time. Consider:

```js
function printAmount() {
	console.log( amount.toFixed( 2 ) );
}

var amount = 99.99;

printAmount(); // "99.99"

amount = amount * 2;

printAmount(); // "199.98"
```

Functions can optionally take arguments (aka parameters) -- values you pass in. And they can also optionally return a value back.

```js
function printAmount(amt) {
	console.log( amt.toFixed( 2 ) );
}

function formatAmount() {
	return "$" + amount.toFixed( 2 );
}

var amount = 99.99;

printAmount( amount * 2 );		// "199.98"

amount = formatAmount();
console.log( amount );			// "$99.99"
```

The function `printAmount(..)` takes a parameter that we call `amt`. The function `formatAmount()` returns a value. Of course, you can also combine those two techniques in the same function.

Functions are often used for code that you plan to call multiple times, but they can also be useful just to organize related bits of code into named collections, even if you only plan to call them once.

Consider:

```js
const TAX_RATE = 0.08;

function calculateFinalPurchaseAmount(amt) {
	// calculate the new amount with the tax
	amt = amt + (amt * TAX_RATE);

	// return the new amount
	return amt;
}

var amount = 99.99;

amount = calculateFinalPurchaseAmount( amount );

console.log( amount.toFixed( 2 ) );		// "107.99"
```

Although `calculateFinalPurchaseAmount(..)` is only called once, organizing its behavior into a separate named function makes the code that uses its logic (the `amount = calculateFinal...` statement) cleaner. If the function had more statements in it, the benefits would be even more pronounced.

### Scope

If you ask the phone store employee for a phone model that her store doesn't carry, she will not be able to sell you the phone you want. She only has access to the phones in her store's inventory. You'll have to try another store to see if you can find the phone you're looking for.

Programming has a term for this concept: *scope* (technically called *lexical scope*). In JavaScript, each function gets its own scope. Scope is basically a collection of variables as well as the rules for how those variables are accessed by name. Only code inside that function can access that function's *scoped* variables.

A variable name has to be unique within the same scope -- there can't be two different `a` variables sitting right next to each other. But the same variable name `a` could appear in different scopes.

```js
function one() {
	// this `a` only belongs to the `one()` function
	var a = 1;
	console.log( a );
}

function two() {
	// this `a` only belongs to the `two()` function
	var a = 2;
	console.log( a );
}

one();		// 1
two();		// 2
```

Also, a scope can be nested inside another scope, just like if a clown at a birthday party blows up one balloon inside another balloon. If one scope is nested inside another, code inside the innermost scope can access variables from either scope.

Consider:

```js
function outer() {
	var a = 1;

	function inner() {
		var b = 2;

		// we can access both `a` and `b` here
		console.log( a + b );	// 3
	}

	inner();

	// we can only access `a` here
	console.log( a );			// 1
}

outer();
```

Lexical scope rules say that code in one scope can access variables of either that scope or any scope outside of it.

So, code inside the `inner()` function has access to both variables `a` and `b`, but code in `outer()` has access only to `a` -- it cannot access `b` because that variable is only inside `inner()`.

Recall this code snippet from earlier:

```js
const TAX_RATE = 0.08;

function calculateFinalPurchaseAmount(amt) {
	// calculate the new amount with the tax
	amt = amt + (amt * TAX_RATE);

	// return the new amount
	return amt;
}
```

The `TAX_RATE` constant (variable) is accessible from inside the `calculateFinalPurchaseAmount(..)` function, even though we didn't pass it in, because of lexical scope.

**Note:** For more information about lexical scope, see the first three chapters of the *Scope & Closures* title of this series.

## Practice

There is absolutely no substitute for practice in learning programming. No amount of articulate writing on my part is alone going to make you a programmer.

With that in mind, let's try practicing some of the concepts we learned here in this chapter. I'll give the "requirements," and you try it first. Then consult the code listing below to see how I approached it.

* Write a program to calculate the total price of your phone purchase. You will keep purchasing phones (hint: loop!) until you run out of money in your bank account. You'll also buy accessories for each phone as long as your purchase amount is below your mental spending threshold.
* After you've calculated your purchase amount, add in the tax, then print out the calculated purchase amount, properly formatted.
* Finally, check the amount against your bank account balance to see if you can afford it or not.
* You should set up some constants for the "tax rate," "phone price," "accessory price," and "spending threshold," as well as a variable for your "bank account balance.""
* You should define functions for calculating the tax and for formatting the price with a "$" and rounding to two decimal places.
* **Bonus Challenge:** Try to incorporate input into this program, perhaps with the `prompt(..)` covered in "Input" earlier. You may prompt the user for their bank account balance, for example. Have fun and be creative!

OK, go ahead. Try it. Don't peek at my code listing until you've given it a shot yourself!

**Note:** Because this is a JavaScript book, I'm obviously going to solve the practice exercise in JavaScript. But you can do it in another language for now if you feel more comfortable.

Here's my JavaScript solution for this exercise:

```js
const SPENDING_THRESHOLD = 200;
const TAX_RATE = 0.08;
const PHONE_PRICE = 99.99;
const ACCESSORY_PRICE = 9.99;

var bank_balance = 303.91;
var amount = 0;

function calculateTax(amount) {
	return amount * TAX_RATE;
}

function formatAmount(amount) {
	return "$" + amount.toFixed( 2 );
}

// keep buying phones while you still have money
while (amount < bank_balance) {
	// buy a new phone!
	amount = amount + PHONE_PRICE;

	// can we afford the accessory?
	if (amount < SPENDING_THRESHOLD) {
		amount = amount + ACCESSORY_PRICE;
	}
}

// don't forget to pay the government, too
amount = amount + calculateTax( amount );

console.log(
	"Your purchase: " + formatAmount( amount )
);
// Your purchase: $334.76

// can you actually afford this purchase?
if (amount > bank_balance) {
	console.log(
		"You can't afford this purchase. :("
	);
}
// You can't afford this purchase. :(
```

**Note:** The simplest way to run this JavaScript program is to type it into the developer console of your nearest browser.

How did you do? It wouldn't hurt to try it again now that you've seen my code. And play around with changing some of the constants to see how the program runs with different values.

## Review

Learning programming doesn't have to be a complex and overwhelming process. There are just a few basic concepts you need to wrap your head around.

These act like building blocks. To build a tall tower, you start first by putting block on top of block on top of block. The same goes with programming. Here are some of the essential programming building blocks:

* You need *operators* to perform actions on values.
* You need values and *types* to perform different kinds of actions like math on `number`s or output with `string`s.
* You need *variables* to store data (aka *state*) during your program's execution.
* You need *conditionals* like `if` statements to make decisions.
* You need *loops* to repeat tasks until a condition stops being true.
* You need *functions* to organize your code into logical and reusable chunks.

Code comments are one effective way to write more readable code, which makes your program easier to understand, maintain, and fix later if there are problems.

Finally, don't neglect the power of practice. The best way to learn how to write code is to write code.

I'm excited you're well on your way to learning how to code, now! Keep it up. Don't forget to check out other beginner programming resources (books, blogs, online training, etc.). This chapter and this book are a great start, but they're just a brief introduction.

The next chapter will review many of the concepts from this chapter, but from a more JavaScript-specific perspective, which will highlight most of the major topics that are addressed in deeper detail throughout the rest of the series.
