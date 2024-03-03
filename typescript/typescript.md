|| TypeScript

	Desarrollado por Microsoft, fue lanzado en octubre de 2012.

	TypeScript se basa en JavaScript y, en esencia, es una extensión de JavaScript que agrega tipos estáticos y otras características modernas al lenguaje.

	Mejora la experiencia de desarrollo en JavaScript al agregar tipos estáticos. 

	Al proporcionar tipos estáticos, TypeScript ayuda a detectar errores en tiempo de compilación en lugar de tiempo de ejecución, lo que puede reducir significativamente los errores.

	Hace que el código sea más róbusto, confiable y fácil de mantener al identificar problemas potenciales antes de que el código se ejecute en un navegador o en un entorno de tiempo de ejecución.
	


|| Instalación y ejecución 
	

	1. Instalar: 

	```	
	npm install -g typescript

	```

	El argumento -g indica que TypeScript se instalará de forma global en tu sistema.


	2. Verificar versión: 

	```
	tsc --version

	```

	
	4. Archivo .ts: 

	```ts

	function saludar(nombre: string) {
    console.log(`Hola, ${nombre}!`);
	}

	saludar("Juan");

	```		


	5. Compilar: 


	```
	tsc miarchivo.ts	

	```

	Generará un archivo JavaScript llamado miarchivo.js que puedes ejecutar en Node.js o en un navegador web.


	6. Ejecutar en node.js: 

	
	```
	node miarchivo.js

	```

	Ejecutará tu programa TypeScript convertido a JavaScript y deberías ver la salida en la terminal.



|| Módulos nativos: 
	
	Toma los módulos estandar de JS. 

	
	Módulos comunes (CommonJS): 

		Este es el sistema de módulos utilizado en entornos como Node.js. 

		Se utiliza principalmente en entornos de servidor y se caracteriza por el uso de 'require' y 'module.exports'.

    
    Módulos de ECMAScript (ES modules):

    	Este es el sistema de módulos introducido en ECMAScript 2015 (ES6). 

    	Se utiliza tanto en el lado del cliente como en el servidor y se caracteriza por el uso de las palabras clave 'import' y 'export'.


    TypeScript también es compatible con varios otros sistemas de módulos y cargadores de módulos de terceros, como AMD (Asynchronous Module Definition), SystemJS y otros.



|| Funciones nativas: 
	
	Toma las funciones de JavaScript. 

    Funciones Globales:

		setTimeout()
		setInterval()
		clearTimeout()
		clearInterval()
		parseInt()
		parseFloat()
		isNaN()
		isFinite()
		encodeURI()
		decodeURI()
		encodeURIComponent()
		decodeURIComponent()
		eval()


	Objeto Array:

		push()
		pop()
		shift()
		unshift()
		slice()
		splice()
		concat()
		join()
		indexOf()
		lastIndexOf()
		forEach()
		map()
		filter()
		reduce()
		reduceRight()
		sort()


	Objeto String:

		charAt()
		charCodeAt()
		concat()
		indexOf()
		lastIndexOf()
		localeCompare()
		match()
		replace()
		search()
		slice()
		split()
		substr()
		substring()
		toLowerCase()
		toUpperCase()
		trim()


	Objeto Math:

		Math.abs()
		Math.ceil()
		Math.floor()
		Math.max()
		Math.min()
		Math.pow()
		Math.random()
		Math.round()
		Math.sqrt()


	Objeto Date:

		new Date()
		Date.now()
		Date.parse()
		Date.UTC()



|| Tipos de datos

	hay varios tipos de datos que se pueden utilizar para definir las características de las variables. Estos tipos de datos incluyen:


    Boolean: 

    	Representa un valor verdadero o falso. 

    	Se declara utilizando la palabra clave 'boolean'.


    Number: 

    	Representa un número, ya sea entero o de punto flotante. 

    	Se declara utilizando la palabra clave 'number'.


    String: 

    	Representa una secuencia de caracteres, como texto. 

    	Se declara utilizando la palabra clave 'string'.


    Array: 

    	Representa una lista de elementos del mismo tipo o de tipos mixtos. 

    	Se puede declarar de dos formas: 

    		tipo[] o Array<tipo>.


    Tuple: 

    	Representa un conjunto de elementos conocidos con tipos definidos. 

    	Se declara utilizando corchetes y cada elemento puede tener un tipo específico.


    Enum: 

    	Representa un conjunto de valores nombrados. 

    	Se declara utilizando la palabra clave enum.


    Any: 

    	Representa cualquier tipo de dato, similar al comportamiento de JavaScript tradicional. 

    	Se utiliza cuando no se conoce el tipo de dato o cuando se desea trabajar con valores dinámicos.


    Void: 

    	Representa la ausencia de un tipo. 

    	Se utiliza generalmente como tipo de retorno de funciones que no devuelven ningún valor.


    Null y Undefined: 

    	Cada uno tiene su propio tipo que lleva su nombre respectivamente. 

    	Generalmente se utilizan como subtipos de otros tipos.


    Never: 

    	Representa el tipo de valores que nunca ocurren. 

    	Se utiliza generalmente como tipo de retorno de funciones que siempre lanzan excepciones o nunca terminan.


    Object: 

    	Representa cualquier valor no primitivo. 

    	Se refiere a cualquier cosa que no sea número, string, boolean, symbol, null o undefined.



|| Sintaxis básica

	
	Tipos de datos y anotaciones de tipo: 

	```ts

	let numero: number;
	let cadena: string;
	let booleano: boolean;
	let lista: number[];
	let tupla: [string, number];
	let cualquierCosa: any;
	let nada: void;
	let nulo: null;
	let indefinido: undefined;

	```


	1. Declaraciones de variables: 

		Las variables se pueden declarar utilizando var, let o const

		```ts
		
		let x: number = 5;
		
		const y: string = "Hola";

		let esCierto: boolean = true;

		```


	2. Estructuras de control: 

	Condicionales y bucles: 

		Las estructuras condicionales permiten ejecutar cierto código dependiendo de una condición.

		```
		if (x > 0) {
		    console.log("x es positivo");
		} else {
		    console.log("x es negativo o cero");
		}

		```

		Switch: 

			Realiza diferentes acciones basadas en diferentes condicioneS. 

		```
		switch (x) {
	    case 1:
	        console.log("x es 1");
	        break;
	    case 2:
	        console.log("x es 2");
	        break;
	    default:
	        console.log("x no es ni 1 ni 2");
		}

		```


		Bucles (Loops): 

			TypeScript soporta bucles como for, while y do-while para iterar sobre conjuntos de datos

		```
		for (let i = 0; i < 5; i++) {
		    console.log(i);
		}

		while (x < 10) {
		    console.log(x);
		    x++;
		}

		```


	4. Funciones: 

		Las funciones se utilizan para realizar tareas específicas. Pueden tomar parámetros y devolver valores.

		```ts	

		function suma(a: number, b: number): number {
	    	
	    	return a + b;
		}

		const resultado = suma(3, 4);
		console.log(resultado);


		function saludar(nombre: string): void {
		    console.log("Hola, " + nombre);
		}

		const saludo = saludar();

		```

		Contiene un tipo de retorno para los parámetros y resultado.


	5. Try-Catch: 

		Se utiliza para manejar errores o excepciones que pueden ocurrir durante la ejecución del programa.

		```
		try {
		    // Bloque de código que podría lanzar una excepción
		} catch (error) {
		    // Manejo de la excepción
		    console.error("Se produjo un error: " + error);
		}	

		```


	6. Interfaces:

		El objeto que usa la interfaz está bajo un contrato en el que solo puede usar sus propiedades y métodos. 

	```ts

	interface Persona {
    	nombre: string;
    	edad: number;
	}

	function imprimirPersona(persona: Persona) {
	    console.log(persona.nombre + " tiene " + persona.edad + " años.");
	}

	let alguien: Persona = { nombre: "María", edad: 25 };
	imprimirPersona(alguien);

	```


	7. Clases: 

	```
	class Persona {
	    nombre: string;
	    edad: number;

	    constructor(nombre: string, edad: number) {
	        this.nombre = nombre;
	        this.edad = edad;
	    }

	    presentarse() {
	        console.log("Hola, soy " + this.nombre + " y tengo " + this.edad + " años.");
	    }
	}

	let persona1 = new Persona("Luis", 35);
	persona1.presentarse();

	```


|| Configuración TypeScript

	
	1. En una carpeta nueva para un proyecto ejecutar: 

		```	
		npm init -y

		```


	2. Instalación local: 

		```
		npm install typescript --save-dev
		
		```


	3. Archivo de configuración .json:

		En la raíz de tu proyecto y agrega la configuración

		```
		{
		  "compilerOptions": {
		    "target": "es5",
		    "module": "commonjs",
		    "outDir": "dist",
		    "strict": true
		  }
		}

		```


	4. Desarrollar App: 

		```ts

		function saludar(nombre: string) {
		    console.log("Hola, " + nombre + "!");
		}

		saludar("Mundo");


		```


	5. Compilar App ts: 

		```	
		npx tsc

		```

		Generará un archivo app.js en la carpeta dist de tu proyecto.


	6. Ejecutar App js: 

		Ejecuta el archivo JavaScript resultante con Node.js

		```
		node dist/app.js

		```


|| Tipo de dato any
	
	Representa cualquier tipo de valor y permite que una variable sea de cualquier tipo en un momento dado.

	Básicamente, any anula la verificación de tipos estáticos de TypeScript y permite que el valor se comporte como un valor de JavaScript normal, sin restricciones de tipoa

	
	```ts
	
	let variable: any = "Hola";
	variable = 5;	
	variable = true;

	```

	Puede presentar algunos problemas:


	1. Pérdida de la verificación estática de tipos: 

		El uso excesivo de any puede anular el propósito principal de TypeScript, que es proporcionar verificación estática de tipos y seguridad durante el desarrollo.

		Sin la verificación de tipos, es más probable que se introduzcan errores en el código.


    2. Falta de información sobre tipos:

    	Al utilizar any, se pierde la información importante sobre el tipo de datos que se esperaba inicialmente, lo que puede dificultar la comprensión del código y su mantenimiento a largo plazo.


    3. Posibles errores en tiempo de ejecución: 

    	Al utilizar any, TypeScript no puede proporcionar advertencias o errores sobre posibles problemas de tipos, lo que puede llevar a errores en tiempo de ejecución difíciles de depurar.


    4. Dificultad en la refactorización y mantenimiento: 

    	La presencia de any puede dificultar la refactorización y el mantenimiento del código, ya que es más difícil rastrear y comprender los tipos de datos en diferentes partes del código.



|| Void

	El uso más común de void es en funciones que no devuelven ningún valor. 

	Esto indica que la función realiza una acción o un proceso, pero no produce un resultado utilizable.

	```ts

	function mostrarMensaje(mensaje: string): void {
	    console.log(mensaje);
	}

	```

	Funciones callback: 

		Indicar que la función de callback no devuelve un valor específico.

	```ts

	function manejarClicBoton(): void {
    console.log("El botón fue clicado.");
	}

	document.getElementById("miBoton")?.addEventListener("click", manejarClicBoton);

	```


	Funciones de cambios de estado: 

		Cuando una función modifica el estado de una aplicación pero no devuelve un valor, se puede utilizar void para indicar que no hay un valor de retorno.
	

	```ts

	function cargarDatosDesdeServidor(): void {
	    // Lógica para cargar datos desde el servidor
	}

	```


	Promesas sin valor de resolución: 

		Promesa que se resuelve sin ningún valor en particular
		

	```ts

	function ejecutarAlgoAsync(): Promise<void> {
	    return new Promise((resolve) => {
	        setTimeout(() => {
	            // Realizar alguna tarea asíncrona
	            resolve();
	        }, 1000);
	    });
	}

	```



|| Inferencia de tipos


	Es la capacidad del compilador de TypeScript para deducir automáticamente el tipo de una variable cuando no se proporciona explícitamente. 

	El compilador infiere el tipo de la variable en función del valor que se le asigna. 

	Esto significa que TypeScript puede analizar y comprender el tipo de datos basado en cómo se utiliza en el código.

	```ts

	let mensaje = "Hola"; // TypeScript infiere que 'mensaje' es del tipo string

	```

	Se debe preferir proporcionar anotaciones de tipo explícitas que dejar actuar a la inferencia de tipos, hace que el código sea más confiable, mantenible y fácil de desarrollar.




|| Buenas prácticas

	
	Utiliza anotaciones de tipo explícitas cuando sea necesario:

		Proporciona anotaciones de tipo explícitas siempre que sea necesario para mejorar la claridad y la legibilidad del código, especialmente en casos donde la inferencia de tipos puede no ser clara.


	Evita el uso excesivo de tipos any:

		Utiliza el tipo any con moderación, ya que puede anular la verificación de tipos estáticos de TypeScript. 

		Intenta ser lo más específico posible con los tipos para mejorar la seguridad y la robustez del código.


	Aplica el principio de "Don't Repeat Yourself" (DRY): 

		Evita la duplicación de código y extrae componentes y funciones comunes en casos donde sea necesario reutilizar el código.

		Esto mejora la mantenibilidad y la legibilidad del código.


	Utiliza interfaces y tipos personalizados: 

		Define interfaces y tipos personalizados para estructuras de datos complejas y componentes reutilizables. 

		Esto mejora la legibilidad del código y proporciona una descripción clara de la forma de los datos.
		

	Utiliza la programación orientada a objetos cuando sea necesario:

		Utiliza clases y herencia de manera apropiada para construir jerarquías de objetos y componentes en el código. 

		Esto puede mejorar la estructura y la organización del código en proyectos más grandes.


	Mantén un estilo de codificación consistente: 

		Sigue las convenciones de nomenclatura y estilo de codificación establecidas para mantener la consistencia en todo el código. 

		Esto facilita la colaboración y comprensión entre los miembros del equipo.


	Realiza pruebas unitarias:

		Implementa pruebas unitarias para probar el comportamiento y la funcionalidad de tu código TypeScript. 

		Esto ayuda a identificar errores y garantizar que el código funcione según lo previsto.


	Actualiza regularmente a las últimas versiones de TypeScript: 

		Mantén tu proyecto al día con las últimas versiones de TypeScript para aprovechar las nuevas características y mejoras de rendimiento que se implementan con cada actualización.



|| Funciones
	
	Se pueden definir de varias maneras. 


	1. Parámetros tipados: 

	```ts
	function sumar(a: number, b: number): number {
    	return a + b;
	}

	```


	2. Parámetros opcionales: 

	```ts

	function saludar(nombre: string, apellido?: string): void {
	    if (apellido) {
	        console.log(`Hola, ${nombre} ${apellido}!`);
	    } else {
	        console.log(`Hola, ${nombre}!`);
	    }
	}

	```


	3. Parámetros por defecto: 

	```ts

	function multiplicar(a: number, b: number = 1): number {
	    return a * b;
	}

	```


	4. Múltiples tipos de retorno: 

	```ts

	function dividir(a: number, b: number): number | string {
	    if (b !== 0) {
	        return a / b;
	    } else {
	        return "No se puede dividir por cero";
	    }
	}

	```	


	5. Funciones como expresiones: 

	```ts

	const producto = function(a: number, b: number): number {
	    return a * b;
	};

	```


	6. Funciones de flecha (arrow functions):

	```ts

	const resta = (a: number, b: number): number => a - b;	

	// Definir una arrow function que duplica un número
	const duplicar = (numero: number): number => {
	    return numero * 2;
	};

	console.log(duplicar(5)); // Salida: 10

	// Definir una arrow function que devuelve un saludo
	const saludar = (): string => "¡Hola, mundo!";

	console.log(saludar()); // Salida: ¡Hola, mundo!

	// Definir una arrow function que devuelve un saludo
	const saludar = (): string => "¡Hola, mundo!";

	console.log(saludar()); // Salida: ¡Hola, mundo!

	// Definir una arrow function que suma todos los números de un array
	const sumarArray = (numeros: number[]): number => {
	    let suma = 0;
	    for (const numero of numeros) {
	        suma += numero;
	    }
	    return suma;
	};

	console.log(sumarArray([1, 2, 3, 4, 5])); // Salida: 15	

	// Definir una función que aplica una transformación a cada elemento de un array
	const transformarArray = (numeros: number[], transformacion: (numero: number) => number): number[] => {
	    return numeros.map(transformacion);
	};

	// Usar una arrow function como argumento para duplicar cada número del array
	const numeros = [1, 2, 3, 4, 5];
	const numerosDuplicados = transformarArray(numeros, (numero) => numero * 2);

	console.log(numerosDuplicados); // Salida: [2, 4, 6, 8, 10]

	```


	7. Sobrecarga de funciones: 

		Permite definir múltiples firmas de función para una misma función. 

		Cada firma de función especifica un conjunto diferente de tipos de parámetros y un tipo de retorno opcional. 

		Esto es útil cuando quieres que una función pueda aceptar diferentes tipos de argumentos y devolver diferentes tipos de resultados basados en esos argumentos.

		Ej. Función duplicar que pueda duplicar diferentes tipos de valores:

	```ts

	function duplicar(valor: number): number {
	    return valor * 2;
	}

	function duplicar(valor: string): string {
	    return valor + valor;
	}

	```

	Juntamos estas dos funciones, en lugar de redefinir la función con un tipo diferente de parámetro, podemos definir varias firmas de función utilizando la palabra clave function y luego la palabra clave declare: 

	
	```ts

	function duplicar(valor: number): number;
	function duplicar(valor: string): string;
	function duplicar(valor: number | string): number | string {
	    if (typeof valor === "number") {
	        return valor * 2;
	    } else {
	        return valor + valor;
	    }
	}

	console.log(duplicar(5));       // Devuelve 10
	console.log(duplicar("Hola"));  // Devuelve "HolaHola"

	```




|| Objetos





|| Type Aliases

