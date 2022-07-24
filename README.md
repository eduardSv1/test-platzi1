# test platzi1
 respuesta del primer test del curso practico basico de JS
 
 1️⃣ Responde las siguientes preguntas:
 
¿Qué es una variable y para qué sirve?

Es el espacio que ocupa en memoria una "palabra " definida.

¿Cuál es la diferencia entre declarar e inicializar una variable?

Al declarar la variable asignamos el nombre de la misma mientras que al  inicializar ademas de asignar el nombre se le asigna un valor. 

¿Cuál es la diferencia entre sumar números y concatenar strings?

Al sumar numero se esta ejecutando una operacion numerica, mientras que concatenar se ejecuta una "operacion" alfabetica.

¿Cuál operador me permite sumar o concatenar?

+

2️⃣ Determina el nombre y tipo de dato para almacenar en variables la siguiente información:

Nombre: String
Apellido: String
Nombre de usuario en Platzi: String
Edad: num
Correo electrónico: String
Mayor de edad: True
Dinero ahorrado: num
Deudas: num

3️⃣ Traduce a código JavaScript las variables del ejemplo anterior y deja tu código en los comentarios.

![image](https://user-images.githubusercontent.com/83262052/180662292-dce66724-e398-48b9-b41b-db5ee0da325b.png)

4️⃣ Calcula e imprime las siguientes variables a partir de las variables del ejemplo anterior:

Nombre completo (nombre y apellido)
Dinero real (dinero ahorrado menos deudas)

![image](https://user-images.githubusercontent.com/83262052/180662342-8bf45bc6-253b-4b20-9efa-ba485ee24c2a.png)



                                                                  Funciones
1️⃣ Responde las siguientes preguntas en la sección de comentarios:
¿Qué es una función?
Es un 
¿Cuándo me sirve usar una función en mi código?
¿Cuál es la diferencia entre parámetros y argumentos de una función?
2️⃣ Convierte el siguiente código en una función, pero, cambiando cuando sea necesario las variables constantes por parámetros y argumentos en una función:
const name = "Juan David";
const lastname = "Castro Gallego";
const completeName = name + lastname;
const nickname = "juandc";

console.log("Mi nombre es " + completeName + ", pero prefiero que me digas " + nickname + ".");
Condicionales
1️⃣ Responde las siguientes preguntas en la sección de comentarios:
¿Qué es un condicional?
¿Qué tipos de condicionales existen en JavaScript y cuáles son sus diferencias?
¿Puedo combinar funciones y condicionales?
2️⃣ Replica el comportamiento del siguiente código que usa la sentencia switch utilizando if, else y else if:
const tipoDeSuscripcion = "Basic";

switch (tipoDeSuscripcion) {
   case "Free":
       console.log("Solo puedes tomar los cursos gratis");
       break;
   case "Basic":
       console.log("Puedes tomar casi todos los cursos de Platzi durante un mes");
       break;
   case "Expert":
       console.log("Puedes tomar casi todos los cursos de Platzi durante un año");
       break;
   case "ExpertPlus":
       console.log("Tú y alguien más pueden tomar TODOS los cursos de Platzi durante un año");
       break;
}
3️⃣ Replica el comportamiento de tu condicional anterior con if, else y else if, pero ahora solo con if (sin else ni else if).
💡 Bonus: si ya eres una experta o experto en el lenguaje, te desafío a comentar cómo replicar este comportamiento con arrays u objetos y un solo condicional. 😏
 
Ciclos
1️⃣ Responde las siguientes preguntas en la sección de comentarios:
¿Qué es un ciclo?
¿Qué tipos de ciclos existen en JavaScript?
¿Qué es un ciclo infinito y por qué es un problema?
¿Puedo mezclar ciclos y condicionales?
2️⃣ Replica el comportamiento de los siguientes ciclos for utilizando ciclos while:
for (let i = 0; i < 5; i++) {
    console.log("El valor de i es: " + i);
}

for (let i = 10; i >= 2; i--) {
    console.log("El valor de i es: " + i);
}
3️⃣ Escribe un código en JavaScript que le pregunte a los usuarios cuánto es 2 + 2. Si responden bien, mostramos un mensaje de felicitaciones, pero si responden mal, volvemos a empezar.
💡 Pista: puedes usar la función prompt de JavaScript.

Listas
1️⃣ Responde las siguientes preguntas en la sección de comentarios:
¿Qué es un array?
¿Qué es un objeto?
¿Cuándo es mejor usar objetos o arrays?
¿Puedo mezclar arrays con objetos o incluso objetos con arrays?
2️⃣ Crea una función que pueda recibir cualquier array como parámetro e imprima su primer elemento.
3️⃣ Crea una función que pueda recibir cualquier array como parámetro e imprima todos sus elementos uno por uno (no se vale imprimir el array completo).
4️⃣ Crea una función que pueda recibir cualquier objeto como parámetro e imprima todos sus elementos uno por uno (no se vale imprimir el objeto completo).
