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

Mayor de edad: Booleam

Dinero ahorrado: num

Deudas: num


3️⃣ Traduce a código JavaScript las variables del ejemplo anterior y deja tu código en los comentarios.

![image](https://user-images.githubusercontent.com/83262052/180662292-dce66724-e398-48b9-b41b-db5ee0da325b.png)

4️⃣ Calcula e imprime las siguientes variables a partir de las variables del ejemplo anterior:

Nombre completo (nombre y apellido)
Dinero real (dinero ahorrado menos deudas)

![image](https://user-images.githubusercontent.com/83262052/180662342-8bf45bc6-253b-4b20-9efa-ba485ee24c2a.png)



                                                                  Funciones
1️⃣ Responde las siguientes preguntas.

¿Qué es una función?

Es un conjunto de sentencias que se ejcuta con variables (parametos y argumentos).

¿Cuándo me sirve usar una función en mi código?

Sirve para "automatizar" un procedimineto, y asi optimizar el codigo. 

¿Cuál es la diferencia entre parámetros y argumentos de una función?

El parametro es lo que la funcion llama, mientras el argumento es lo que nosotro le asignamos a la funcion.


2️⃣ Convierte el siguiente código en una función, pero, cambiando cuando sea necesario las variables constantes por parámetros y argumentos en una función:

const name = "Juan David";
const lastname = "Castro Gallego";
const completeName = name + lastname;
const nickname = "juandc";

console.log("Mi nombre es " + completeName + ", pero prefiero que me digas " + nickname + ".");

![image](https://user-images.githubusercontent.com/83262052/180662570-05403dbd-3456-4e16-8eca-2be34175d482.png)


                                                                  Condicionales
1️⃣ Responde las siguientes preguntas en la sección de comentarios:

¿Qué es un condicional?

Es una expresion que nos permite evaluar si es verdadero o no. 

¿Qué tipos de condicionales existen en JavaScript y cuáles son sus diferencias?

Existe IF, ELSE IF,  ELSE y el SWITCH, la diferencia entre ellas es que if y else se usa en casos de que ((IF)si es esto es cierto has (bloque de codigo), (ELSE IF) (si esta otra cosa) es cierta has (bolque de datos), ((SI NO) ELSE HAZ ESTO);
Mientras que el SWITCH se utiliza para evualuar cada caso (verifica si el caso 1 se cumple, si no se cumple pasa al caso dos y asi sucesivamente) 

¿Puedo combinar funciones y condicionales?
Si, si se puede combinar dentro de las  funciones las condicionales. 

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


![image](https://user-images.githubusercontent.com/83262052/180663027-1454bcda-b616-4a79-93cb-8a4edfed6e60.png)


3️⃣ Replica el comportamiento de tu condicional anterior con if, else y else if, pero ahora solo con if (sin else ni else if).

💡 Bonus: si ya eres una experta o experto en el lenguaje, te desafío a comentar cómo replicar este comportamiento con arrays u objetos y un solo condicional. 😏
 aun no soy un experto en el lenguaje xD 
 
                                                                    Ciclos
1️⃣ Responde las siguientes preguntas:

¿Qué es un ciclo?

 Es una repetitiva de iteracion finita. 

¿Qué tipos de ciclos existen en JavaScript?

existen FOR, WHILE.

¿Qué es un ciclo infinito y por qué es un problema?
Un ciclo inifinito es cuando una sentencia no se cumple y queda el ciclo ejecutandose infinitamente creando asi un BUG. Es problema ya que el codigo no se termina ejecutando  corrtectamtente.

¿Puedo mezclar ciclos y condicionales?

SI,si se puede. 


2️⃣ Replica el comportamiento de los siguientes ciclos for utilizando ciclos while:

for (let i = 0; i < 5; i++) {

    console.log("El valor de i es: " + i);
    
}


for (let i = 10; i >= 2; i--) {

    console.log("El valor de i es: " + i);
    
}

![image](https://user-images.githubusercontent.com/83262052/180663524-c526335c-1e70-494b-9201-5a6d90c8d405.png)



3️⃣ Escribe un código en JavaScript que le pregunte a los usuarios cuánto es 2 + 2. Si responden bien, mostramos un mensaje de felicitaciones, pero si responden mal, volvemos a empezar.

💡 Pista: puedes usar la función prompt de JavaScript.

![image](https://user-images.githubusercontent.com/83262052/180666259-d195f3d8-7080-4db1-8d10-6ca9674bd287.png)


Listas
1️⃣ Responde las siguientes preguntas:

¿Qué es un array?

Es una estructura de datos de tipo objeto.

¿Qué es un objeto?

es un conjunto de datos relacionados con multiple variables y sus valores, es como una especie de caja donde se almacena  muhcas variables y sus  valores. 

¿Cuándo es mejor usar objetos o arrays?

es mejor usar objetos cuando la cantidad de variables es muy alta. 

¿Puedo mezclar arrays con objetos o incluso objetos con arrays?

si se puede.

2️⃣ Crea una función que pueda recibir cualquier array como parámetro e imprima su primer elemento.


3️⃣ Crea una función que pueda recibir cualquier array como parámetro e imprima todos sus elementos uno por uno (no se vale imprimir el array completo).
4️⃣ Crea una función que pueda recibir cualquier objeto como parámetro e imprima todos sus elementos uno por uno (no se vale imprimir el objeto completo).
