|| React

	React es una popular biblioteca de JavaScript, no un framework en el sentido tradicional, que se utiliza para crear interfaces de usuario interactivas y dinámicas en aplicaciones web	

	Desarrollado por Facebook y se lanzó por primera vez en 2013. Inicialmente, se creó para abordar los desafíos de construir interfaces de usuario complejas y de alto rendimiento en Facebook e Instagram. 

	Su objetivo era proporcionar una forma eficiente de manejar la actualización del DOM (Document Object Model) de una página web cuando los datos cambian sin necesidad de recargar toda la página.


	Estructura: 

		Componentes: 

			React se basa en la idea de descomponer la interfaz de usuario en componentes reutilizables. 

			Estos componentes pueden representar partes individuales de la interfaz, como botones, formularios o listas, y se pueden componer para crear interfaces de usuario complejas.


		Virtual DOM:

			React utiliza un Virtual DOM para optimizar el rendimiento. 

			En lugar de actualizar directamente el DOM del navegador cuando cambian los datos, React actualiza primero un árbol de objetos virtual y luego compara este árbol con el DOM real, realizando solo las actualizaciones necesarias. 

			Esto reduce la carga en el navegador y mejora la velocidad de la aplicación.

		
		Unidireccionalidad de datos: 

			React promueve el flujo de datos unidireccional, lo que significa que los datos fluyen en una dirección específica a través de la aplicación, lo que facilita el seguimiento de los cambios y la depuración.


		Reactividad: 

			React permite crear interfaces de usuario reactivas que responden a los cambios en los datos de manera eficiente


		JSX: 

			JSX es una extensión de JavaScript que permite escribir componentes de React utilizando una sintaxis similar al HTML.

			Facilita la creación de interfaces de usuario declarativas y legibles.


		Renderización en el lado del servidor (Server-Side Rendering - SSR): 

			React es compatible con la renderización en el lado del servidor, lo que permite que las páginas se rendericen en el servidor y se envíen al navegador.

			Esto mejora la velocidad de carga inicial y la optimización para motores de búsqueda.


		React Native: 

			React se puede utilizar para desarrollar aplicaciones móviles nativas para iOS y Android a través de React Native. 

			Esto permite a los desarrolladores utilizar las mismas habilidades y componentes para crear aplicaciones móviles y web.



|| Características: 
	
	Componentes: 

		Los componentes son la unidad básica de construcción en React.

		Puedes crear componentes de React para representar partes específicas de la interfaz de usuario, como botones, encabezados, formularios, etc.


    JSX (JavaScript XML): 

    	JSX es una extensión de JavaScript que se utiliza en React para describir cómo se deben renderizar los componentes. 

    	Permite escribir código HTML-like dentro de JavaScript.


    Estado (State): 

    	React permite a los componentes tener un estado interno que puede cambiar a lo largo del tiempo. 

    	El estado es una parte fundamental para crear componentes reactivos.


    Propiedades (Props): 

    	Las props son los mecanismos que permiten que los componentes de React se comuniquen entre sí. 

    	Son datos que se pasan de un componente padre a un componente hijo.


    Ciclo de vida (Lifecycle): 	

    	Los componentes de React tienen un ciclo de vida que consta de varios métodos predefinidos, como 'componentDidMount', 'componentDidUpdate', y 'componentWillUnmount', que te permiten controlar el comportamiento de los componentes en diferentes etapas de su existencia.


    Renderizado condicional: 

    	React permite el renderizado condicional, lo que significa que puedes mostrar o ocultar componentes o elementos en función de condiciones lógicas.


    Eventos: 

    	React permite manejar eventos como clics de mouse, cambios de entrada, etc., utilizando manejadores de eventos JSX.


    Reconciliación y Virtual DOM: 	
    	
    	React utiliza un Virtual DOM para optimizar las actualizaciones de la interfaz de usuario.

    	Cuando los datos cambian, React compara el Virtual DOM con el DOM real y actualiza solo las partes que han cambiado, en lugar de volver a renderizar toda la página.


    Fragmentos (Fragments): 

    	Los fragmentos son una forma de agrupar múltiples elementos hijos sin agregar un nodo adicional al DOM.


    Refs: 

    	Las refs se utilizan para acceder al DOM o a elementos de un componente directamente desde el código de React.


    Context API: 

    	La Context API permite pasar datos a través del árbol de componentes sin tener que pasar propiedades manualmente a través de todos los niveles de componentes.	


    Portales (Portals): 

    	Los portales en React te permiten renderizar un componente en un nodo DOM fuera de la jerarquía de componentes actual. 

    	Esto es útil para casos como modales que deben aparecer por encima de otros elementos sin afectar la estructura DOM de la aplicación



|| Instalar y Ejecutar
	
	1. Instalar Node.js y npm.

	2. Crear una aplicación React

		Instalar Create React App de forma global en tu sistema. 

		Esto lo necesitas hacer solo una vez:

		```
			npm install -g create-react-app

		```			

		Crear app: 

		```
			npx create-react-app my-react-app

		```	

		Creará una nueva carpeta llamada "my-react-app" en tu directorio actual con la estructura y archivos iniciales de una aplicación React.


	3. Ejecutar la aplicación React

		Una vez que hayas creado tu aplicación React, puedes ejecutarla. 

		Navega a la carpeta de tu proyecto usando el comando "cd". 

		```
			cd my-react-app

		```

		Iniciar la aplicación:

		```
			npm start

		```

		Iniciará un servidor de desarrollo y abrirá tu aplicación en un navegador web. 

		Si no se abre automáticamente, puedes acceder a ella en http://localhost:3000 en tu navegador.


	4.  Desarrollar la App: 

		Editando los archivos en la carpeta "src" de tu proyecto. 

		Los cambios se reflejarán automáticamente en el navegador mientras trabajas.



|| Bibliotecas para React


	React Router: 

		React Router es una biblioteca que se utiliza para la navegación en aplicaciones de una sola página (SPA). 

		Proporciona un enrutamiento declarativo para crear rutas y gestionar la navegación en una aplicación React.


    React Redux: 

    	React Redux es una biblioteca que se utiliza para gestionar el estado de la aplicación en aplicaciones React.

    	Implementa la arquitectura de gestión de estado basada en Flux y proporciona un almacén de estado centralizado.


    Axios o Fetch: 

    	Estas bibliotecas se utilizan para realizar solicitudes HTTP desde una aplicación React a un servidor o API externa.

    	Ayudan a manejar las solicitudes y respuestas de manera eficiente.


    Styled-components o Emotion: 

    	Estas bibliotecas permiten
    	utilizar CSS en JS para estilizar componentes React.

    	Proporcionan una forma de definir estilos de componentes de manera dinámica y reutilizable.


    React Native: 

    	React Native es un marco de desarrollo de aplicaciones móviles que permite crear aplicaciones móviles nativas para iOS y Android utilizando React y componentes de interfaz de usuario nativos.


    React Helmet: 

    	React Helmet se utiliza para gestionar etiquetas de encabezado HTML (como título, metadescripción, etc.) en aplicaciones React. 

    	Es útil para la optimización de motores de búsqueda (SEO).


    React Query o Apollo Client:

    	Estas bibliotecas se utilizan para gestionar datos y realizar consultas a una API GraphQL desde una aplicación React.

    	Facilitan la gestión del estado y las solicitudes de datos.


    React Testing Library o Enzyme: 

    	Estas bibliotecas se utilizan para escribir pruebas unitarias y de integración para componentes React.

    	Facilitan la creación y ejecución de pruebas.


    React Bootstrap o Material-UI: 

    	Estas son bibliotecas de diseño que proporcionan componentes preestilizados basados en React para crear interfaces de usuario con estilos coherentes y atractivos.


    React Spring o Framer Motion: 	
    	
    	Estas bibliotecas se utilizan para crear animaciones fluidas y atractivas en aplicaciones React.
	


|| Sintaxis para manipular React

	
	1. Create React App: 

		```
			npx create-react-app mi-aplicacion-react
			cd mi-aplicacion-react

		```

		Creará una app de ejemplo llamada "create react app" en una carpeta con el mismo nombre. 


	2. React Component: 

		Habrá una carpeta "src", donde podemos crear archivos js como por ej: "MyComponent.js"

		```jsx

			import React from 'react';

			function MiComponente() {
			  return (
			    <div>
			      <h1>Hola, mundo!</h1>
			      <p>Este es mi primer componente de React.</p>
			    </div>
			  );
			}

			export default MiComponente;

		```

		Define un componente de función React llamado "MiComponente" que renderiza un título (<h1>) y un párrafo (<p>) en JSX.


	3. Renderizar el componente en la aplicación: 

		En la carpeta "src" creamos un index.js

		```jsx

			import React from 'react';
			import ReactDOM from 'react-dom';
			import MiComponente from './MiComponente';
			import './index.css';

			ReactDOM.render(
			  <React.StrictMode>
			    <MiComponente />
			  </React.StrictMode>,
			  document.getElementById('root')
			);

		```

		Importa el componente "MiComponente" que creaste y lo renderiza dentro del elemento con el ID "root" en el archivo HTML principal de la aplicación


	4. Ejecutar la aplicación

		En la carpeta del proyecto ejecutamos: 

		```
			npm start

		```

		El servidor del desarrollo ejecturá el componente con sus elementos. 



||	React Hooks
	
	Característica de React 16.8 que permite que los componentes funcionales gestionen el estado y otras características previamente disponibles solo en componentes de clase. 

	Los React Hooks son funciones especiales que te permiten "enganchar" el estado y el comportamiento de React a componentes funcionales sin necesidad de convertirlos en componentes de clase.
	

	1. useState: 

		Este Hook permite a los componentes funcionales gestionar el estado local.

		Puedes utilizarlo para declarar y actualizar variables de estado en tus componentes funcionales.

		```
		import React, { useState } from 'react';

		function Contador() {
		  const [contador, setContador] = useState(0);

		  return (
		    <div>
		      <p>Contador: {contador}</p>
		      <button onClick={() => setContador(contador + 1)}>Incrementar</button>
		    </div>
		  );
		}

		export default Contador;

		```


	2. useEffect: 

		Este Hook se utiliza para realizar efectos secundarios en componentes funcionales, como suscripciones a datos, actualizaciones del DOM y gestión de temporizadores.

		Es similar al ciclo de vida componentDidMount, componentDidUpdate y componentWillUnmount en componentes de clase

		```
		import React, { useState, useEffect } from 'react';

		function DatosEnTiempoReal() {
		  const [datos, setDatos] = useState([]);

		  useEffect(() => {
		    // Realizar una solicitud a una API o configurar una suscripción en este efecto
		    // Actualizar datos cuando sea necesario
		    return () => {
		      // Realizar limpieza cuando el componente se desmonta
		    };
		  }, []); // El segundo argumento es un arreglo de dependencias

		  return (
		    <div>
		      {/* Mostrar los datos */}
		    </div>
		  );
		}

		export default DatosEnTiempoReal;

		```


	3. useContext: 

		Este Hook permite acceder al contexto de React dentro de un componente funcional. 

		Puedes usarlo para acceder a datos compartidos globalmente sin necesidad de pasarlos a través de props

		```
		import React, { useContext } from 'react';

		const MiContexto = React.createContext();

		function ComponenteHijo() {
		  const valor = useContext(MiContexto);
		  return <p>Valor del contexto: {valor}</p>;
		}

		function App() {
		  return (
		    <MiContexto.Provider value="Hola desde el contexto">
		      <ComponenteHijo />
		    </MiContexto.Provider>
		  );
		}

		export default App;


		```

	Hay otros Hooks como useReducer, useRef, useCallback, useMemo, entre otros, que te permiten abordar diferentes aspectos de la lógica de tus componentes funcionales.

	Han simplificado en gran medida la escritura y el mantenimiento de componentes funcionales en React, lo que los hace más poderosos y versátiles que nunca. 

	Te permiten separar la lógica de estado y efectos secundarios de la representación de la interfaz de usuario, lo que facilita la creación de componentes más reutilizables y comprensibles.



|| Context API

	Permite compartir datos o estado entre componentes de manera eficiente sin necesidad de pasar props a través de cada nivel de la jerarquía de componentes. 

	Es especialmente útil cuando tienes datos que son necesarios en muchos lugares de tu aplicación, como datos de autenticación, preferencias del usuario o datos de tema.


	Consta de tres partes principales:


	1. React.createContext: 

		Este método se utiliza para crear un nuevo contexto.

		Debes proporcionar un valor predeterminado que se utilizará cuando no haya un proveedor correspondiente en la jerarquía de componentes

		```
		const MiContexto = React.createContext(defaultValue);

		```


	2. Proveedor (Provider): 

		El componente Provider se utiliza para envolver una parte de tu aplicación con un contexto específico y proporcionar un valor para ese contexto. 

		Este valor estará disponible para todos los componentes que estén dentro de ese Provider.

		```
		<MiContexto.Provider value={miValor}>
		  {/* Componentes que pueden acceder a miValor */}
		</MiContexto.Provider>

		```


	3. Consumidor (Consumer): 

		El componente Consumer se utiliza para consumir y acceder al valor proporcionado por el Provider. 

		Puedes utilizar el Consumer dentro de cualquier componente que necesite acceder a los datos del contexto

		```
		<MiContexto.Consumer>
		  {valor => (
		    // Utiliza el valor proporcionado por el contexto aquí
		  )}
		</MiContexto.Consumer>

		```

	Ejemplo de uso de Context API: 

	```
	import React, { createContext, useContext, useState } from 'react';

	// Paso 1: Crear un contexto con un valor predeterminado
	const MiContexto = createContext();

	function App() {
	  // Paso 2: Definir el estado que deseas compartir a través del contexto
	  const [miEstado, setMiEstado] = useState('Este es un valor desde el contexto');

	  return (
	    // Paso 3: Proporcionar el valor del contexto utilizando un Provider
	    <MiContexto.Provider value={miEstado}>
	      <ComponenteHijo />
	    </MiContexto.Provider>
	  );
	}

	function ComponenteHijo() {
	  // Paso 4: Consumir el valor del contexto utilizando un Consumer o el hook useContext
	  const valorDelContexto = useContext(MiContexto);

	  return (
	    <div>
	      <p>Valor del contexto: {valorDelContexto}</p>
	    </div>
	  );
	}

	export default App;


	```

	'App' proporciona un valor a través del 'Provider' y 'ComponenteHijo' lo consume usando el hook 'useContext'. 

	Los datos de contexto se pasan automáticamente desde 'App' hasta 'ComponenteHijo' sin necesidad de pasar props explícitamente.


	La API de Context en React es útil para administrar datos globales de manera eficiente y reduce la necesidad de pasar props a través de múltiples niveles de componentes, lo que simplifica la gestión del estado en aplicaciones grandes y complejas.



|| Clean Boilerplate
	
	Estructura de inicio de proyecto o plantilla que proporciona una base organizada y simplificada para comenzar a desarrollar una aplicación React, sin la necesidad de configurar todo desde cero.


	Características: 

		1. Estructura de carpetas organizada:

			Esto puede incluir carpetas para componentes, estilos, imágenes, rutas, servicios, etc


		2. Configuración inicial:

			Puede incluir configuración inicial de herramientas y dependencias comunes utilizadas en proyectos de React, como Webpack, Babel, ESLint, Prettier y gestión de paquetes con npm o Yarn.

		
		3. Estilos y CSS: 

			Puede proporcionar un sistema de estilos básico o una configuración para el uso de CSS, CSS-in-JS, Sass, o cualquier otra metodología de estilos.


		4. Gestión de rutas: 

			Puede incluir una configuración inicial para la gestión de rutas en tu aplicación React, a menudo utilizando bibliotecas como React Router


		5. Manejo de estado: 

			Puede proporcionar una estructura inicial para gestionar el estado global de la aplicación, ya sea utilizando el Context API de React, Redux u otra biblioteca de gestión de estado


		6. Ejemplos de componentes: 

			Para guiar a los desarrolladores y personalizar sus componentes.  


		7. Pruebas: 

			Puede incluir configuraciones y ejemplos iniciales para escribir pruebas unitarias y de integración utilizando bibliotecas como Jest y React Testing Library


		8. Documentación: 

			Para ayudar a los desarrolladores a comprender cómo utilizar la plantilla y personalizarla según sus necesidades.



|| Componentes

	Unidad fundamental y reutilizable de la interfaz de usuario de una aplicación. 

	Puedes pensar en los componentes como bloques de construcción que representan partes individuales de la interfaz de usuario de tu aplicación, como botones, encabezados, formularios, elementos de lista, barras laterales, etc.


	1. Componentes de Clase: 

		Se usaban antes de React 16.8, los componentes de clase eran la forma principal de crear componentes en React. 

		Estos componentes se definen como clases de JavaScript y heredan de la clase React.Component. 

		Tienen un ciclo de vida que consta de varios métodos, como render, componentDidMount, componentDidUpdate, y componentWillUnmount.

		```jsx

		import React, { Component } from 'react';

		class MiComponente extends Component {
		  render() {
		    return <p>Soy un componente de clase</p>;
		  }
		}

		export default MiComponente;
	
		```


	2. 

		Forma más sencilla y moderna de definir componentes en React.

		Son funciones de JavaScript que devuelven elementos JSX para representar la interfaz de usuario. 

		Con la introducción de los hooks, los componentes funcionales también pueden manejar el estado y los efectos secundarios de manera efectiva

		```
			import React from 'react';

			function MiComponenteFuncional() {
			  return <p>Soy un componente funcional</p>;
			}

			export default MiComponenteFuncional;

		```

		En ambos casos, los componentes en React pueden recibir datos de entrada llamados "props" (propiedades) que les permiten ser configurados y personalizados cuando se utilizan en otros componentes

		```
		<MiComponente nombre="Ejemplo" edad={30} />

		```

		Dentro del componente, puedes acceder a estas propiedades usando this.

		props en los componentes de clase o como argumentos en los componentes funcionales.


		Los componentes promueven la encapsulación y la separación de preocupaciones al dividir la lógica de la interfaz de usuario en componentes individuales.

		Esto hace que React sea una biblioteca poderosa para crear aplicaciones web y móviles interactivas y escalables.



|| JSX 

	"JavaScript XML", es una extensión de JavaScript que se utiliza en React para describir cómo se debe renderizar la interfaz de usuario de una aplicación. 

	JSX permite escribir código que se asemeja al formato de HTML dentro de JavaScript, lo que hace que la definición de componentes de React sea más legible y declarativa.


	1. Sintaxis parecida a HTML: 

		Elementos con etiquetas HTML

		```jsx

		const elemento = <h1>¡Hola, mundo!</h1>;

		```


	2. Expresiones JavaScript: 

		Puedes incluir expresiones JavaScript encerrándolas en llaves {}. 
		
		Esto te permite incorporar lógica dinámica dentro de tus elementos JSX	

		```
		const nombre = "Juan";
		const elemento = <h1>Hola, {nombre}</h1>;

		```


	3. Atributos y propiedades: 

		Puedes utilizar atributos y propiedades en elementos JSX de la misma manera que lo harías en HTML

		```
		const link = <a href="https://www.ejemplo.com">Enlace</a>;

		```


	4. Componentes personalizados:

		Los componentes personalizados se escriben en JavaScript y se utilizan como si fueran elementos HTML.

		```
		const MiComponente = () => <p>Soy un componente personalizado</p>;

		const elemento = (
		  <div>
		    <h1>¡Hola, mundo!</h1>
		    <MiComponente />
		  </div>
		);

		```

		Se define un parrafo con una función 'MiComponente' y al 'elemento' le pasamos está función que se unirá al titulo de 'elemento'. 


	5. renderizado condicional: 

		Utilizar declaraciones condicionales y operadores lógicos dentro de JSX para renderizar elementos condicionalmente.

		```	
		const mostrarMensaje = true;

		const elemento = (
		  <div>
		    {mostrarMensaje && <p>Mensaje de ejemplo</p>}
		  </div>
		);

		```

		Dentro de las llaves de expresiones {} íncluimos lógica, como 'mostrarMensaje' es verdadero se muestra un parrafo. 


	6. Mapeo de listas: 

		Utilizar métodos como 'map()' para mapear una lista de datos a elementos JSX. 

		Esto es comúnmente utilizado para generar listas dinámicas

		```
		const datos = ["Manzana", "Banana", "Cereza"];

		const lista = (
		  <ul>
		    {datos.map((item, index) => (
		      <li key={index}>{item}</li>
		    ))}
		  </ul>
		);

		```

		Mostrará los elementos por indice, como estan definidos.


	7. Eventos:

		Puedes asignar manejadores de eventos a elementos JSX usando la misma sintaxis que en HTML.	

		```jsx

		const handleClick = () => {
		  alert("Hiciste clic en el botón");
		};

		const boton = <button onClick={handleClick}>Haz clic</button>;

		```
		En las llaves de lógica incluimos la función que se activará en el elemento 'boton'


	8. Comentarios: 

		Utilizando la sintaxis '{/* comentario */}'

		Dentro de los elementos jsx. 



|| Elementos y componentes

	
	Elemento: 

		Es una descripción liviana de lo que debería aparecer en la interfaz de usuario. 

		Los elementos son la unidad más básica en la representación de la interfaz de usuario de una aplicación React y se utilizan para crear componentes y estructurar la jerarquía de la interfaz de usuario.

		Son inmutables, lo que significa que una vez que se crean, no se pueden modificar. 

		Si deseas cambiar la interfaz de usuario, debes crear nuevos elementos o actualizar el estado de un componente que contiene elementos.

		```
		const elemento = React.createElement(
		  tipo,        // Tipo de elemento (como una etiqueta HTML o un componente personalizado)
		  props,       // Propiedades del elemento (opcional)
		  ...hijos      // Elementos secundarios (opcional)
		);

		```

		1. Tipo (type):

			El tipo del elemento especifica qué tipo de elemento se está representando. 

			Puede ser una cadena que represente una etiqueta HTML (como "div", "h1", "p") o un componente personalizado (una función o clase de React).

   		
   		2. Props (propiedades): 

   			Las propiedades son un objeto que contiene información adicional que se pasa al elemento. 

   			Estas propiedades son configurables y pueden utilizarse para personalizar el elemento o para proporcionar datos necesarios para su renderización. 

   			Por ejemplo, en un elemento de una etiqueta HTML, las propiedades podrían incluir className, id, onClick, etc.

    	
    	3. Hijos (children): 

    		Los hijos son otros elementos de React que se anidan dentro del elemento principal. 

    		Pueden ser elementos simples, otros elementos compuestos o incluso fragmentos (fragmentos son elementos especiales que no generan un nodo HTML adicional en el DOM). 

    		Los hijos son la forma en que se crea la estructura de árbol de la interfaz de usuario.


    	```
    	const elemento = React.createElement('p', { className: 'mi-paragraph' }, '¡Hola, mundo!');

    	```

    	Es una estructura de datos que representa un tipo de elemento (como una etiqueta HTML o un componente personalizado), sus propiedades (props) y sus hijos.



    Componente: 

    	es una entidad más compleja y reutilizable que puede contener elementos y lógica de representación.

		Los componentes son instancias de clases o funciones de JavaScript que extienden o implementan la funcionalidad de React.

		Pueden manejar el estado interno, recibir props, contener lógica y realizar renderizado personalizado.

		Los componentes son la forma principal de crear interfaces de usuario en React, y pueden contener una jerarquía de elementos y otros componentes.

		Son reutilizables y se pueden usar múltiples veces en la aplicación.


		1. Componente Legacy

		```
		import React, { Component } from 'react';

		class MiComponente extends Component {
		  render() {
		    return <p className="mi-paragraph">¡Hola, mundo!</p>;
		  }
		}

		```


		2. Componente Moderno

		```
		import React from 'react';

		function MiComponenteFuncional() {
		  return <p>Soy un componente funcional</p>;
		}

		export default MiComponenteFuncional;

		```



|| JSX Rules

	Reglas y convenciones que debes seguir al escribir código JSX para que sea válido y funcione correctamente en React. 


	1. Etiquetas Deben Ser Cerradas o Autocerradas: 

		Las etiquetas JSX deben cerrarse correctamente, al igual que en HTML. 

		Puedes usar etiquetas de cierre como <div></div> o etiquetas autocerradas como <input />. 


	2. Nombre de Componentes Inician con Mayúscula:

		Los nombres de componentes personalizados deben comenzar con una letra mayúscula. 

		Esto ayuda a React a distinguir entre componentes y elementos HTML. 

		Por ejemplo, '<MiComponente />'' es un componente personalizado, mientras que '<div />' es un elemento HTML.


	3. Llaves para Expresiones JavaScript: 

		Puedes insertar expresiones JavaScript dentro de elementos JSX utilizando llaves {}. 

		Esto permite incluir variables, llamadas de funciones y expresiones dentro del JSX. 

		Por ejemplo, '<p>{variable}</p>'.


	4. Propiedades Utilizan CamelCase: 

		Cuando se especifican propiedades en JSX, debes utilizar la convención de nomenclatura de camelCase en lugar de kebab-case. 

		Por ejemplo, 'className' en lugar de 'class', 'onClick' en lugar de 'onclick', etc.


	5. Uso de class vs. className: 

		Para aplicar clases CSS a elementos JSX, debes utilizar la propiedad 'className' en lugar de class, ya que 'class' es una palabra reservada en JavaScript.


	6. Un Solo Elemento Raíz: 

		Un componente JSX debe tener un solo elemento raíz. 

		Esto significa que si tienes varios elementos, deben estar contenidos en un solo elemento contenedor: 

		```jsx

		<div>
		  <p>Elemento 1</p>
		  <p>Elemento 2</p>
		</div>
	
		```

		No permitido: 

		```	
		<p>Elemento 1</p>
		<p>Elemento 2</p>

		```

	
	7. Elementos y Componentes Personalizados: 

		Puedes utilizar tanto elementos HTML como componentes personalizados en JSX. 

		Por ejemplo, puedes usar '<div />' y '<MiComponente />' en el mismo código JSX.


	8. Comentarios en JSX: 

		Utilizando la sintaxis '{/* Comentario */}'. 

		Los comentarios no se renderizan en la salida final.


	9. Validación de Propiedades: 

		Siempre debes validar las propiedades (props) que recibe un componente personalizado para garantizar que sean del tipo esperado y contengan los datos necesarios.


	10. Evitar Expresiones Complejas: 

		Es mejor evitar colocar expresiones JavaScript complejas dentro de las llaves en JSX. 

		Si la lógica se vuelve demasiado complicada, es preferible moverla a funciones o métodos fuera del componente.	



|| Nested Components

	Páctica de colocar un componente dentro de otro componente para construir interfaces de usuario más complejas al agrupar componentes más pequeños y reutilizables.


	Jerarquía de Componentes: 

		En una aplicación React, los componentes se organizan en una jerarquía, donde un componente principal (padre) puede contener componentes secundarios (hijos).

		Esto crea una estructura en árbol de la interfaz de usuario.


	Composición: 
	
		Los componentes anidados se utilizan para componer la interfaz de usuario. 

		Puedes pensar en ellos como piezas de LEGO que se combinan para formar una construcción más grande y compleja.


	Reutilización: 

		Un beneficio clave de los componentes anidados es la reutilización. 

		Puedes definir componentes pequeños y especializados una vez y utilizarlos en múltiples lugares de tu aplicación. 

		Esto ahorra tiempo y evita la duplicación de código.


	Mantenimiento: 

		Los componentes anidados facilitan el mantenimiento de la aplicación. 

		Si necesitas realizar cambios en una parte de la interfaz de usuario, puedes hacerlo en el componente correspondiente sin afectar otras partes de la aplicación


	División de interfaz en Componentes: 

		Ejemplo en una lista de tareas: 

		1. App: 

			El componente principal que contiene toda la aplicación.


			2. Header: 

				Un componente que muestra el encabezado de la lista de tareas.


			3. ListaDeTareas: 

				Muestra la lista de tareas y contiene elementos de tarea individuales.				

				4. Tarea: 

					Componente hijo que representa una tarea individual con su estado (completa o incompleta).


			5. FormularioDeNuevaTarea: 	

				Un componente que permite al usuario agregar nuevas tareas a la lista.


		Refleja la organización lógica de la interfaz de usuario de la aplicación y permite la reutilización de componentes como 'Tarea' y 'FormularioDeNuevaTarea' o cualquiera que sea hijo de 'App' en otros lugares de la aplicación si es necesario.



|| JSX CSS

	Formas de aplicar estilos a tus componentes en React puede variar según tus preferencias y requisitos específicos. 


	1. Estilos en línea (Inline Styles): 

		Puedes aplicar estilos directamente a elementos JSX utilizando el atributo style.

		```jsx

		const elementoConEstilo = <div style={{ color: 'red', fontSize: '16px' }}>Texto con estilo</div>;

		```

		Es incomodo cuando se aplican estilos complejos o cuando deseas reutilizar estilos en varios lugares


	2. Hoja de Estilos Externos (External Stylesheets): 

		Agrega tus archivos CSS y enlázalos en tu HTML principal. Luego, simplemente asigna las clases CSS a tus elementos JSX utilizando la propiedad 'className'. 

		```jsx

		const elementoConEstilo = <div className="mi-clase-css">Texto con estilo</div>;

		```


	3. Bibliotecas de Estilos: 

		Puedes utilizar bibliotecas de estilos como Bootstrap, Material-UI, Ant Design y otras, que proporcionan componentes React estilizados listos para usar. 


	4. CSS en Módulos (CSS Modules): 

		CSS Modules es una técnica que te permite definir estilos CSS locales a un componente específico en React. 

		Los estilos CSS se importan como módulos y se aplican de manera local al componente, lo que evita problemas de colisión de nombres de clase. 

		```
		import styles from './MiComponente.module.css';

		const elementoConEstilo = <div className={styles.miClase}>Texto con estilo</div>;

		```

	5. Styled Components: 

		Es una biblioteca que te permite definir estilos CSS directamente en tus componentes React utilizando tagged templates literales de JavaScript. 

		```jsx

		import styled from 'styled-components';

		const MiComponente = styled.div`
		  color: red;
		  font-size: 16px;
		`;

		const elementoConEstilo = <MiComponente>Texto con estilo</MiComponente>;

		```

	6. Emotion: 

		Biblioteca popular para estilar componentes en React, similar a Styled Components. 

		Proporciona una sintaxis similar que te permite definir estilos dentro de tus componentes JSX.



|| JSX JavaScript

	Interactúan juntos para crear interfaces de usuario dinámicas  y personalizadas. 

	1. Incorporar JS en JSX: 

		Utilizando llaves {}. 

		Permite evaluar expresiones JavaScript y mostrar su resultado dentro de tu código JSX

		```
		const nombre = "Juan";
		const elemento = <p>Hola, {nombre}</p>;

		```

		Se renderizará mostrando "Hola, Juan"


	2. Expresiones en Llaves: 

		Incluye variables, operaciones aritméticas, llamadas a funciones y más.

		```	
		const numero = 5;
		const elemento = <p>El doble de 5 es {numero * 2}</p>;

		```		

		Renderizará el cálculo de la operación. 


	3. Eventos y Manejadores de Eventos: 

		Puedes agregar un manejador de eventos onClick a un botón

		```	
		function handleClick() {
		  alert("Hiciste clic en el botón");
		}

		const boton = <button onClick={handleClick}>Haz clic</button>;
			
		```
		'onClick' hace posible la ejecución de la función 'handleClick'


	4. Condicionales y Renderizado Condicional:

		Utilizar declaraciones condicionales y operadores lógicos en JSX para controlar la renderización de los elementos. 

		```
		const mostrarMensaje = true;

		const elemento = (
		  <div>
		    {mostrarMensaje && <p>Mensaje de ejemplo</p>}
		  </div>
		);

		```

		Dado que es verdadero, mostrará el elemento 'div' que contiene el mensaje. 


	5. Mapeo de Listas: 

		Utilizar métodos como map() en arrays de JavaScript para mapear elementos JSX y crear listas dinámicas. 

		```
		const datos = ["Manzana", "Banana", "Cereza"];

		const lista = (
		  <ul>
		    {datos.map((item, index) => (
		      <li key={index}>{item}</li>
		    ))}
		  </ul>
		);


		```

		Crea una lista HTML a partir de los elementos del array datos.



|| Props

	Las propiedades son pasadas de un componente padre a un componente hijo y permiten la comunicación y el intercambio de datos entre componentes en una jerarquía de componentes en React.


	1. Pasando Datos a Componentes: 

		Las props son utilizadas para pasar datos, configuraciones y funciones desde un componente padre a un componente hijo.

		Esto permite que los componentes hijos sean configurables y reutilizables, ya que pueden aceptar diferentes datos según cómo se les pasen las props


	2. Props como Objetos: 

		Se pasan a los componentes como un objeto de propiedades. 

		Cada propiedad (clave) del objeto representa una prop, y el valor de esa propiedad es el dato o valor que se pasa al componente hijo

		```
		// Componente padre
		const MiComponentePadre = () => {
		  return <MiComponenteHijo mensaje="Hola desde las props" />;
		};

		// Componente hijo que recibe una prop llamada "mensaje"
		const MiComponenteHijo = (props) => {
		  return <p>{props.mensaje}</p>;
		};

		```


	3. Accediendo a Props: 

		Para acceder a las props en un componente hijo, simplemente se utilizan como propiedades del objeto props. 

		En el ejemplo anterior, props.mensaje se utiliza para acceder al valor de la prop "mensaje".



	4. 	Props Inmutables: 

		Las props son inmutables, lo que significa que no se deben modificar directamente en el componente hijo. 

		Son solo para lectura. 
		
		Si necesitas cambiar datos, generalmente lo haces en el componente padre y luego pasas los nuevos datos a través de las props nuevamente.


	5. Uso de Props en JSX: 

		Las props se pueden utilizar en JSX dentro del componente hijo, lo que permite mostrar dinámicamente datos en la interfaz de usuario basados en las props recibidas

		```
		const MiComponenteHijo = (props) => {
		  return <p>{props.mensaje}</p>;
		};

		```

	6. Valores Predeterminados para componente hijo: 

		En caso de que no se pasen desde el componente padre. 

		Esto se hace utilizando el patrón 'defaultProps'

		```
		const MiComponenteHijo = (props) => {
		  return <p>{props.mensaje || "Mensaje predeterminado"}</p>;
		};

		MiComponenteHijo.defaultProps = {
		  mensaje: "Mensaje predeterminado",
		};

		```

		Mostrará un mensaje personalizado o en caso de que no esté, mostrará el predeterminado. 


	7. Props como funciones: 

		Además de datos, las props también se pueden utilizar para pasar funciones desde el componente padre al hijo.

		Esto permite que el hijo interactúe con eventos o realice acciones en respuesta a acciones del usuario

		```
		// Componente padre
		const MiComponentePadre = () => {
		  const handleClick = () => {
		    alert("Hiciste clic en el botón");
		  };

		  return <MiComponenteHijo onClick={handleClick} />;
		};

		// Componente hijo que recibe una prop función llamada "onClick"
		const MiComponenteHijo = (props) => {
		  return <button onClick={props.onClick}>Haz clic</button>;
		};

		```


|| Desestructuración de props

	Es una técnica comúnmente utilizada en React para simplificar el acceso a las props pasadas a un componente. 

	La desestructuración de props permite extraer propiedades específicas de un objeto props en lugar de acceder a ellas a través del objeto directamente.

	Hace que el código sea más limpio, al trabajar con muchas props.  

	```
	// Sin desestructuración de props
	function EjemploComponente(props) {
	  return (
	    <div>
	      <p>Nombre: {props.nombre}</p>
	      <p>Edad: {props.edad}</p>
	    </div>
	  );
	}

	// Con desestructuración de props
	function EjemploComponenteConDestructuring({ nombre, edad }) {
	  return (
	    <div>
	      <p>Nombre: {nombre}</p>
	      <p>Edad: {edad}</p>
	    </div>
	  );
	}

	```

	Los dos componentes reciben las mismas props, 'nombre' y 'edad'. 

	Sin embargo, el segundo componente utiliza la desestructuración de props para acceder a estas props de manera más concisa y legible.



|| Props Children

	Se utiliza para pasar componentes, elementos o contenido arbitrario como hijos a un componente React.

	Permite que los componentes sean más flexibles y reutilizables, ya que pueden contener y renderizar contenido adicional proporcionado por el componente padre.
	 
	Se usa cuando deseas envolver contenido dentro de un componente personalizado y luego renderizar ese contenido dentro de la estructura del componente.


	1. Uso de props.children: 

		Por convensión escribimos 'children' dentro de la definicón del componente. 

		```
		function MiComponente({ children }) {
		  return (
		    <div className="contenedor">
		      <p>Este es el contenido del componente:</p>
		      {children}
		    </div>
		  );
		}

		```
		Cualquier contenido que se pase como hijo a este componente se colocarán en la posición de 'children'.


	2. Pasando contenido: 	

		'props.children' puede contener múltiples elementos y componentes. 

		No está limitado a un solo elemento

		```
		<MiComponente>
		  <p>Primer párrafo</p>
		  <p>Segundo párrafo</p>
		</MiComponente>

		```

		ambos párrafos se renderizarán dentro del componente "MiComponente" como parte de "props.children



|| Lista 

	Se refiere a una lista de elementos que se renderizan en un componente. 

	1. Definición y Almacenamiento de Datos: 

		Debes definir los componente que describa lo que vas a hacer. 

		Debes tener algún tipo de estructura de datos en tu estado de React para almacenar la lista de elementos que deseas mostrar. 

		Esto podría ser un array en el estado de tu componente o datos obtenidos de una API o una base de datos.


	2. Mapeo de Datos: 

		Utiliza el método map() de JavaScript para recorrer la lista de elementos y crear dinámicamente un componente para cada uno. 

		Por ejemplo, si tienes una matriz de tareas, puedes utilizar map() para crear un componente Tarea para cada tarea en la lista.

		```jsx

		const listaDeTareas = [
		  { id: 1, texto: 'Hacer compras' },
		  { id: 2, texto: 'Lavar el coche' },
		  { id: 3, texto: 'Hacer ejercicio' },
		];

		const tareas = listaDeTareas.map((tarea) => (
		  <Tarea key={tarea.id} texto={tarea.texto} />
		));

		```
		Tenemos un grupo de elementos 'ListaDeTareas' que se mostrará invidualmente en 'tareas'


	3. Renderizar grupo: 

		Renderizar los componentes generados dentro de un contenedor en tu JSX.

		```
		return (
		  <div>
		    <h2>Lista de Tareas</h2>
		    <ul>
		      {tareas}
		    </ul>
		  </div>
		);

		```


	4. Renderizar Componentes individuales: 

		Asegúrate de que el componente individual (Tarea en este caso) reciba las propiedades necesarias (por ejemplo, el texto de la tarea) y las utilice para mostrar cada elemento de la lista

		```
		function Tarea({ texto }) {
		  return <li>{texto}</li>;
		}

		```


|| Manejo de grupo de elementos

	Debemos tener una lista de elementos implementada correctamente siguiendo buenas prácticas. 

	1. Usa una clave (key) única: 

		Cuando renderizas elementos en una lista en React, cada elemento debe tener una prop key única. 
		
		La clave ayuda a React a identificar y rastrear los elementos de la lista de manera eficiente. 

		Idealmente, la clave debería ser un identificador único asociado al elemento, como un ID de base de datos.

		```
		const listaDeTareas = [
		  { id: 1, texto: 'Hacer compras' },
		  { id: 2, texto: 'Lavar el coche' },
		  { id: 3, texto: 'Hacer ejercicio' },
		];

		const tareas = listaDeTareas.map((tarea) => (
		  <Tarea key={tarea.id} texto={tarea.texto} />
		));

		```


	2. Evita mutar la lista original:

		Al manipular una lista en React, evita modificar la lista original directamente. 

		En su lugar, crea una nueva lista o copia la lista existente y luego realiza las operaciones necesarias. 

		Esto ayuda a mantener la inmutabilidad de los datos, lo que es fundamental para el funcionamiento correcto de React.


	3. Extrae componentes reutilizables: 

		Si los elementos de la lista tienen una estructura y apariencia similares, considera extraer un componente reutilizable para representar cada elemento. 

		Esto mejora la legibilidad y facilita la reutilización del código.


	4. Usa el método map() para renderizar: 

		El método map() de JavaScript es una forma eficiente de recorrer una lista y renderizar elementos dinámicamente en React. 

		Crea una matriz de elementos JSX a partir de la lista y luego renderiza esa matriz.

		
	5. Considera la paginación o la carga dinámica: 

		Si tu lista es muy larga, considera implementar la paginación o la carga dinámica para mejorar el rendimiento.

		Esto implica mostrar solo una porción de la lista a la vez y cargar más elementos según sea necesario.

	
	6. Maneja eventos y acciones de lista: 

		Si tu lista requiere acciones como eliminar elementos, marca como completados, etc., asegúrate de manejar estos eventos de manera adecuada y reflejar los cambios en el estado de la aplicación.

	
	7. Optimización de rendimiento: 

		Si trabajas con listas muy grandes o complejas, puedes considerar técnicas de optimización de rendimiento en React, como el uso de 'React.memo', 'shouldComponentUpdate', o componentes de alto rendimiento como 'react-virtualized' para optimizar el rendimiento de la renderización.



|| Key prop

	Es un atributo especial que se utiliza para identificar de manera única elementos de una lista cuando se realizan operaciones de renderizado, como agregar, actualizar o eliminar elementos.

	Cada elemento en una lista renderizada debe tener una key única para que React pueda realizar un seguimiento de ellos de manera eficiente y garantizar que las actualizaciones se apliquen correctamente.	


	Uso en el Método map(): 

		La prop key se suele asignar en el método map() cuando recorres una matriz o una lista para crear elementos JSX dinámicamente.

		```
		const elementos = datos.map((item) => (
		  <MiComponente key={item.id} dato={item} />
		));

		```


	Actualización de Elementos: 

		Cuando actualizas elementos en una lista, es importante que la key siga siendo única para cada elemento. 

		Si cambias la key de un elemento, React lo considerará como un elemento diferente y realizará una nueva renderización.	



|| Eventos

	Los eventos permiten que los componentes React respondan a las acciones del usuario, como hacer clic en un botón o escribir en un campo de entrada.


	1. Elemento HTML:

		En qué elemento HTML deseas agregar un evento. 

		Puedes agregar eventos a elementos como botones, campos de entrada, elementos de lista, etc. 


	2. Función Manejadora: 

		Crea una función JavaScript que se ejecutará cuando ocurra el evento. 

		Puedes definirla dentro del componente React en el que deseas agregar el evento.

		```
		function handleClick() {
		  alert("Se hizo clic en el botón");
		}

		```


	3. Agrega el Evento al Elemento JSX: 

		Utiliza el JSX de React para agregar el evento al elemento HTML deseado.

		Debes utilizar la sintaxis especial de React para asignar la función manejadora como un controlador de eventos. 

		Por ejemplo, para un botón que ejecute la función handleClick cuando se hace clic:

		```
		<button onClick={handleClick}>Haz clic</button>

		```

		onClick es el nombre del evento, y handleClick es la función manejadora que se ejecutará cuando ocurra el evento.


	4. Renderizar el componente: 

		Asegúrate de que el componente en el que estás trabajando esté completo y renderizando adecuadamente.

		```jsx

		import React from "react";

		function MiComponente() {
		  function handleClick() {
		    alert("Se hizo clic en el botón");
		  }

		  return (
		    <div>
		      <button onClick={handleClick}>Haz clic</button>
		    </div>
		  );
		}

		export default MiComponente;

		```



|| Operador de separación: 

	Se utiliza comúnmente para pasar todas las propiedades de un objeto a un componente.

	```
	const objetoProps = { prop1: "valor1", prop2: "valor2" };

	// Usando el operador de propagación para pasar todas las propiedades
	<MiComponente {...objetoProps} />

	```

	Dentro del componente MiComponente, puedes acceder a prop1 y prop2 como props individuales.


	Combinar objetos: 

		Combinar dos objetos en uno solo. 

		Es útil cuando deseas agregar propiedades adicionales a un objeto sin modificar el original.

		```jsx

		const objeto1 = { prop1: "valor1" };
		const objeto2 = { prop2: "valor2" };

		const objetoCombinado = { ...objeto1, ...objeto2 };

		```

		'objetoCombinado' contendrá ambas propiedades de objeto1 y objeto2.


	Copiar Array: 

		```	
		const arrayOriginal = [1, 2, 3];
		const copiaArray = [...arrayOriginal];

		```

		Cualquier cambio en copiaArray no afectará a arrayOriginal.


	Nuevo elemento: 

		```
		const arrayOriginal = [1, 2, 3];
		const nuevoElemento = 4;
		const arrayActualizado = [...arrayOriginal, nuevoElemento];

		```
		contendrá los elementos de 'arrayOriginal' más el nuevo elemento.


	Copiar el Estado en Componentes:

		Dentro de componentes de clase en React, el operador de propagación se utiliza comúnmente para copiar el estado actual antes de realizar modificaciones en el estado.
		
		Esto es importante para garantizar que el estado no se mute directamente.

		```
		this.setState({ ...this.state, nuevaPropiedad: "valor" });

		```
		Al copiar el estado existente y luego agregar una nueva propiedad, te aseguras de que el estado original permanezca inmutable.


	Puedes utilizarlo para crear copias de objetos, combinar objetos, copiar arrays y realizar otras operaciones de manejo de datos de manera eficiente y segura.



|| useState

	Permite a los componentes de función gestionar el estado local.

	Puedes agregar estado a tus componentes de función sin necesidad de convertirlos en componentes de clase desde React 16.8. 


	1. Importa useState: 

		En la parte superior de tu archivo de componente, debes importar useState desde la librería React.

		```
		import React, { useState } from 'react';

		```


	2. Declara el Estado: 

		Dentro del componente de función, puedes declarar una variable para almacenar el estado y una función para actualizar ese estado utilizando useState. 

		La función useState toma un argumento inicial que es el valor inicial del estado.

		```
		function MiComponente() {
		  // Declaración de estado
		  const [estado, setEstado] = useState(valorInicial);
		  
		  // ...
		}

		```	

		estado: 

			Es la variable que almacena el valor del estado.

    	setEstado: 

    		Es la función que puedes utilizar para actualizar el valor del estado. 

    		Debes llamar a esta función con el nuevo valor del estado cuando desees actualizarlo.


	3. Accede y Actualiza el Estado:

		Ahora puedes acceder al valor del estado (estado) en tu componente y usar la función setEstado para actualizarlo

		```jsx

		function MiComponente() {
		  const [contador, setContador] = useState(0);

		  const aumentarContador = () => {
		    setContador(contador + 1);
		  };

		  return (
		    <div>
		      <p>Contador: {contador}</p>
		      <button onClick={aumentarContador}>Aumentar</button>
		    </div>
		  );
		}

		```
		Usamos 'useState' para mantener un estado llamado 'contador', que se inicializa en 0. 

		Luego, tenemos una función 'aumentarContador' que llama a 'setContador' para actualizar el valor del estado cuando se hace clic en el botón.


	4. Renderiza el Estado: 

		Puedes renderizar el valor del estado en tu JSX utilizando las llaves {}. 

		En el ejemplo anterior, estamos mostrando el valor de contador en el párrafo.


	5. Actualización Inmutable: 

		Es importante recordar que el estado en React debe actualizarse de forma inmutable. 

		Esto significa que no debes modificar directamente el valor del estado, sino que debes crear una nueva versión del estado con el valor actualizado. 

		useState se encarga de esto automáticamente cuando llamas a la función setEstado.



|| Hooks Rules

	Ayudan a garantizar un comportamiento predecible y consistente en tus componentes

	1. Solo en Componentes de Función (Modern): 	

		No se debe intentar usar Hooks en componentes de clase (legacy)


	2. Hooks en el Nivel Superior: 

		Solo deben llamarse en el nivel superior de un componente de función, es decir, no deben usarse dentro de condicionales, bucles o funciones anidadas		
		Deben estar en el orden en el que se llaman y no deben cambiar de orden en re-renderizaciones diferentes.

		```jsx	

		function MiComponente() {
		  const [estado, setEstado] = useState(0); // Correcto
		  if (estado === 1) {
		    const [otroEstado, setOtroEstado] = useState(''); // Incorrecto
		  }
		}

		```

	3. Hooks consistentes: 

	 	Significa que no debes condicionar la llamada a un Hook basándote en alguna lógica. 

	 	Siempre llama a los Hooks en el mismo orden.

	 	```jsx

	 	// Incorrecto - condicional
		if (condicion) {
		  useEffect(() => {
		    // ...
		  }, []);
		}

		// Correcto - siempre llama a useEffect
		useEffect(() => {
		  if (condicion) {
		    // ...
		  }
		}, []);

	 	```


	4. No Llamar Hooks en Funciones Anidadas o Callbacks:

		A menos que estas funciones sean declaradas dentro de tu componente y se ajusten a las reglas de Hooks.

		```	
		function MiComponente() {
		  useEffect(() => {
		    // Correcto: useEffect en función del componente
		  }, []);

		  const miFuncion = () => {
		    useEffect(() => {
		      // Incorrecto: useEffect dentro de una función anidada
		    }, []);
		  };
		}

		```


	5. Usar Hooks en el Órden: 

		Debes usar los Hooks en el mismo orden en cada re-renderización. 

		Esto es importante para que React realice un seguimiento adecuado de los Hooks utilizados y sus estados.

		```	
		const [estado1, setEstado1] = useState('A');
		const [estado2, setEstado2] = useState('B');

		// Correcto
		const [estado1, setEstado1] = useState('A');
		const [estado2, setEstado2] = useState('B');

		// Incorrecto - orden diferente
		const [estado2, setEstado2] = useState('B');
		const [estado1, setEstado1] = useState('A');

		```		

	6. Crear Hooks Personalizados con el Prefijo "use": 

		Si creas tus propios Hooks personalizados, debes nombrarlos con el prefijo "use". 

		Esto es una convención que ayuda a reconocer que es un Hook y seguir las reglas.

		```
		// Correcto - Hook personalizado nombrado con "use"
		function useMiHook() {
		  // ...
		}

		```


|| useState Array


	1. Importar 'useState': 

		Desde React en el inicio del archivo del componente. 

		```
		import React, { useState } from 'react';

		```


	2. Declarar el estado inicial: 

		Variable de estado inicial que contendrá el array. 

		Esto se hace utilizando 'useState' y proporcionando un array vacío o un array con datos iniciales según tus necesidades.

		```	
		const [miArray, setMiArray] = useState([]);

		```


	3. Actualiza el Estado del Array:

		Para agregar o modificar elementos en el array, utiliza la función 'setMiArray' proporcionada por useState. 

		No debes modificar el array directamente, sino que debes crear una nueva copia del array que incluya los cambios que deseas realizar

		```
		// Para agregar un elemento al array
		const agregarElemento = () => {
		  const nuevoElemento = 'Nuevo elemento';
		  setMiArray([...miArray, nuevoElemento]);
		};

		// Para actualizar un elemento en el array por su índice
		const actualizarElemento = (indice) => {
		  const nuevoValor = 'Nuevo valor';
		  const nuevoArray = [...miArray];
		  nuevoArray[indice] = nuevoValor;
		  setMiArray(nuevoArray);
		};

		```

		Estamos utilizando el operador de propagación (...) para crear una copia del array existente y luego agregando un nuevo elemento o actualizando un elemento existente.


	4. Renderizar array: 

		Renderizar los elementos del array en tu JSX utilizando un bucle (como map) para generar elementos de lista o cualquier otro método adecuado según tus necesidades.

		```
		return (
		  <div>
		    <ul>
		      {miArray.map((elemento, indice) => (
		        <li key={indice}>{elemento}</li>
		      ))}
		    </ul>
		  </div>
		);

		```

		Asegúrate de proporcionar una clave (key) única para cada elemento dentro del bucle para ayudar a React a identificar los elementos de la lista de manera eficiente.



|| useState Object

	1. Importar 'useState':

		```
		import React, { useState } from 'react';	

		```

	2.  Declara el Estado Inicial:


		```
		const [miObjeto, setMiObjeto] = useState({});

		```

	3. Actualiza el Estado del Objeto: 

		Agregar o modificar propiedaes, se utilizar la función 'setMiObjeto' creando una copia que incluya los cambios. 

		```
		// Para agregar una nueva propiedad al objeto
		const agregarPropiedad = () => {
		  const nuevaPropiedad = 'nuevoValor';
		  setMiObjeto({ ...miObjeto, nuevaPropiedad });
		};

		// Para actualizar una propiedad existente en el objeto
		const actualizarPropiedad = () => {
		  const nuevaValor = 'nuevoValor';
		  setMiObjeto({ ...miObjeto, propiedadExistente: nuevaValor });
		};

		```

	4. Renderizar Objeto: 

		Renderizar las propiedades del objeto en tu JSX accediendo a ellas directamente desde miObjeto.

		```
		return (
		  <div>
		    <p>Propiedad 1: {miObjeto.propiedad1}</p>
		    <p>Propiedad 2: {miObjeto.propiedad2}</p>
		  </div>
		);

		```



|| useState multiple state values

	Para gestionar múltiples valores de estado dentro de un componente de función. 
	
	Cada llamada a useState crea una variable de estado independiente que puede mantener un valor específico. 

	Esto te permite gestionar varios valores de estado en un solo componente.

	```	
	import React, { useState } from 'react';

	function MiComponente() {
	  // Declaración de múltiples estados
	  const [valor1, setValor1] = useState(0);
	  const [valor2, setValor2] = useState('');
	  const [valor3, setValor3] = useState(false);

	  // ...

	  return (
	    <div>
	      <p>Valor 1: {valor1}</p>
	      <p>Valor 2: {valor2}</p>
	      <p>Valor 3: {valor3 ? 'Verdadero' : 'Falso'}</p>
	      {/* Renderiza y actualiza cada valor de estado según sea necesario */}
	    </div>
	  );
	}

	export default MiComponente;

	```

	Utilizando useState tres veces para declarar tres variables de estado independientes: valor1, valor2 y valor3. 

	Cada variable de estado tiene su propio valor inicial y su función correspondiente para actualizar ese valor (setValor1, setValor2 y setValor3).


	Acceder y actualizar cada uno de estos valores de estado de manera individual. 

	Por ejemplo, para actualizar valor1, puedes llamar a setValor1 con el nuevo valor deseado

	```	
	<button onClick={() => setValor1(valor1 + 1)}>Incrementar Valor 1</button>
	
	```



|| Contador 

	Usando 'useState', el contador aumentará y disminuirá, según los clicks en el botón. 

	```jsx 

	import React, { useState } from 'react';

	function Contador() {
	  // Declaración del estado inicial del contador
	  const [contador, setContador] = useState(0);

	  // Función para incrementar el contador
	  const aumentarContador = () => {
	    setContador(contador + 1);
	  };

	  // Función para decrementar el contador
	  const disminuirContador = () => {
	    setContador(contador - 1);
	  };

	  return (
	    <div>
	      <h1>Contador</h1>
	      <p>Valor actual: {contador}</p>
	      <button onClick={aumentarContador}>Incrementar</button>
	      <button onClick={disminuirContador}>Decrementar</button>
	    </div>
	  );
	}

	export default Contador;


	```
	
	Utilizamos 'useState' para declarar el estado inicial del contador, que se inicializa en 0.
	
	Creamos dos funciones, 'aumentarContador' y 'disminuirContador', que utilizamos para actualizar el estado del contador mediante setContador.




|| Formulario

	Usando 'useState', el formulario consta de un campo de entrada de texto y un botón para enviar el valor del campo de entrada.

	```jsx

	import React, { useState } from 'react';

	function FormularioBasico() {
	  // Declaración del estado para el valor del campo de entrada
	  const [inputValue, setInputValue] = useState('');

	  // Función para manejar el cambio en el campo de entrada
	  const handleChange = (event) => {
	    setInputValue(event.target.value);
	  };

	  // Función para manejar el envío del formulario
	  const handleSubmit = (event) => {
	    event.preventDefault(); // Evita que la página se recargue al enviar el formulario
	    alert(`Valor del campo de entrada: ${inputValue}`);
	  };

	  return (
	    <div>
	      <h1>Formulario Básico</h1>
	      <form onSubmit={handleSubmit}>
	        <label>
	          Ingresa un valor:
	          <input
	            type="text"
	            value={inputValue}
	            onChange={handleChange}
	          />
	        </label>
	        <button type="submit">Enviar</button>
	      </form>
	    </div>
	  );
	}

	export default FormularioBasico;


	```

	'useState' para declarar el estado inicial del valor del campo de entrada, que se inicializa como una cadena vacía.
	
	Creamos dos funciones, 'handleChange' y 'handleSubmit', para manejar los eventos de cambio en el campo de entrada y el envío del formulario, respectivamente.
	
	El campo de entrada (<input>) utiliza el valor de inputValue y llama a 'handleChange' cuando cambia.

	El formulario (<form>) llama a 'handleSubmit' cuando se envía. Usamos event.preventDefault() para evitar que la página se recargue al enviar el formulario y, en su lugar, mostramos un mensaje de alerta con el valor del campo de entrada.



|| useEffect

	Usados para manejar efectos secundarios en componentes de función. 

	Los efectos secundarios son acciones que ocurren después de que el componente se ha renderizado en el DOM y pueden incluir tareas como la suscripción a eventos, solicitudes de red, manipulación del DOM y más.
	
	Permite a los componentes interactuar con el ciclo de vida de React y realizar tareas de efectos secundarios en respuesta a cambios en el estado del componente o a eventos específicos.

	Equivalente a 'componentDidMount', 'componentDidUpdate' y 'componentWillUnmount' antes de React 16.8. 

	```
	useEffect(() => {
	  // Código para manejar efectos secundarios
	}, [dependencias]);

	```

	La primera función dentro de useEffect contiene el código que se ejecutará cuando se active el efecto secundario.

    El segundo argumento de useEffect es un array de dependencias opcional. 

    Las dependencias son variables o propiedades que, cuando cambian, activan la ejecución del efecto. 

    Si el array de dependencias está vacío ([]), el efecto se ejecutará solo después del primer renderizado del componente.


   	1. Efecto que se ejecuta una vez (equivalente a componentDidMount):

   		```
   		useEffect(() => {
		  // Código a ejecutar una vez después del primer renderizado
		}, []);

   		```


   	2. Efecto que se ejecuta en respuesta a cambios en una variable específica:

   		```	
   		useEffect(() => {
		  // Código a ejecutar cuando myVariable cambie
		}, [myVariable]);

   		```


   	3. Efecto que se ejecuta en cada renderizado (equivalente a componentDidUpdate):

   		```
   		useEffect(() => {
		  // Código a ejecutar en cada renderizado
		});

   		```

   	4. Efecto que se ejecuta al desmontar el componente (equivalente a componentWillUnmount):

   		```
   		useEffect(() => {
		  return () => {
		    // Código a ejecutar al desmontar el componente
		  };
		}, []);

   		```


|| useEffect Conditional

	Uso de useEffect en un componente de función con una condición que determina cuándo se debe ejecutar el efecto. 

	Esto permite controlar cuándo se activa el efecto secundario basado en cambios específicos en el estado o en las propiedades del componente.

	Solo se ejecutará cuando la condición especificada en la dependencia del useEffect sea verdadera. 

	Para lograr esto, puedes utilizar una variable de estado o propiedades como parte de la dependencia.


	```jsx

	import React, { useState, useEffect } from 'react';

	function MiComponente() {
	  const [valor, setValor] = useState(0);
	  const [activarEfecto, setActivarEfecto] = useState(false);

	  useEffect(() => {
	    if (activarEfecto) {
	      // Realiza un efecto secundario cuando activarEfecto es verdadero
	      console.log('Efecto secundario activado');
	      // Puedes realizar tareas adicionales aquí
	    }
	  }, [activarEfecto]);

	  return (
	    <div>
	      <p>Valor: {valor}</p>
	      <button onClick={() => setValor(valor + 1)}>Incrementar</button>
	      <button onClick={() => setActivarEfecto(!activarEfecto)}>
	        {activarEfecto ? 'Desactivar Efecto' : 'Activar Efecto'}
	      </button>
	    </div>
	  );
	}

	export default MiComponente;

	```

	Tenemos dos estados: valor y activarEfecto. 

	El efecto secundario dentro de useEffect solo se ejecutará si activarEfecto es verdadero. 

	Cuando hacemos clic en el botón "Activar Efecto", cambiamos el estado de activarEfecto, lo que a su vez controla si se ejecuta el efecto secundario.



|| useEffect Dependency List

	Es un array que contiene variables o propiedades que determinan cuándo se debe ejecutar el efecto secundario dentro de useEffect.

	Solo ejecutará el efecto secundario cuando uno o más de estos valores cambien desde el último renderizado del componente. 

	En otras palabras, el efecto se ejecutará cuando cualquiera de las dependencias en la lista haya cambiado.

	```jsx

	useEffect(() => {
	  // Código del efecto secundario
	}, [dependencia1, dependencia2, ...]);

	```

	Ejemplo: 

	```jsx

	import React, { useState, useEffect } from 'react';

	function MiComponente() {
	  const [valor, setValor] = useState(0);

	  useEffect(() => {
	    console.log('Efecto secundario ejecutado');
	  }, [valor]);

	  return (
	    <div>
	      <p>Valor: {valor}</p>
	      <button onClick={() => setValor(valor + 1)}>Incrementar</button>
	    </div>
	  );
	}

	export default MiComponente;

	```

	[valor] como lista de dependencias en useEffect. 

	Significa que el efecto secundario se ejecutará cada vez que el valor de valor cambie. 

	Cuando hacemos clic en el botón "Incrementar", valor cambia y, como resultado, el efecto secundario se ejecuta y muestra un mensaje en la consola.



|| useEffect Cleanup Function

	La función de limpieza es una función que puedes devolver dentro de un efecto creado con useEffect.

	Esta función de limpieza se ejecuta cuando el componente se desmonta o cuando las dependencias del efecto cambian y se debe ejecutar un nuevo efecto. 

	La función de limpieza es opcional y se utiliza para realizar tareas de limpieza o desmontaje antes de que el componente deje de existir.

	Se especifica como un valor de retorno dentro de la función del efecto en useEffect.


	```jsx

	import React, { useState, useEffect } from 'react';

	function MiComponente() {
	  const [mostrarMensaje, setMostrarMensaje] = useState(true);

	  useEffect(() => {
	    // Efecto secundario que se ejecuta al montar el componente
	    console.log('El componente se ha montado');

	    // Función de limpieza que se ejecuta al desmontar el componente
	    return () => {
	      console.log('El componente se ha desmontado');
	    };
	  }, []); // Lista de dependencias vacía, se ejecuta solo al montar

	  return (
	    <div>
	      {mostrarMensaje && (
	        <button onClick={() => setMostrarMensaje(false)}>Ocultar Mensaje</button>
	      )}
	    </div>
	  );
	}

	export default MiComponente;

	```

	'MiComponente' que tiene un botón para ocultar un mensaje.
	
	Usamos 'useEffect' con una lista de dependencias vacía [], lo que significa que el efecto se ejecutará solo una vez, cuando el componente se monta inicialmente.

	Dentro del efecto, imprimimos un mensaje en la consola cuando el componente se monta.
	
	También proporcionamos una función de limpieza que se ejecutará cuando el componente se desmonte.

	Cuando haces clic en el botón "Ocultar Mensaje" y el estado mostrarMensaje cambia a false, el componente se desmonta y la función de limpieza se ejecuta, lo que imprime "El componente se ha desmontado" en la consola	


	Son útiles para realizar tareas de limpieza, como cancelar suscripciones, detener temporizadores o liberar recursos cuando un componente se desmonta.

	Son una parte importante de la gestión de efectos secundarios en React y ayudan a evitar problemas de memoria y comportamiento inesperado.



|| useEffect Fetch Data

	Se usa para realizar solicitudes de red y obtener datos de un servidor (por ejemplo, mediante una API REST) de manera asíncrona. 

	El patrón común para hacer esto se denomina "useEffect Fetch Data" y es útil cuando deseas cargar datos externos y actualizar el estado de tu componente con esos datos una vez que estén disponibles

	```jsx	

	import React, { useState, useEffect } from 'react';

	function MiComponente() {
	  const [data, setData] = useState([]); // Estado para almacenar los datos
	  const [loading, setLoading] = useState(true); // Estado para controlar la carga

	  useEffect(() => {
	    // Función para realizar la solicitud de datos
	    async function fetchData() {
	      try {
	        const response = await fetch('https://api.ejemplo.com/data'); // Reemplaza la URL con tu API real
	        const jsonData = await response.json();
	        setData(jsonData);
	        setLoading(false); // Cambia el estado de carga a falso
	      } catch (error) {
	        console.error('Error al cargar los datos:', error);
	        setLoading(false); // Cambia el estado de carga a falso incluso en caso de error
	      }
	    }

	    fetchData(); // Llama a la función de solicitud de datos al montar el componente
	  }, []); // Lista de dependencias vacía, se ejecuta solo al montar

	  return (
	    <div>
	      {loading ? (
	        <p>Cargando datos...</p>
	      ) : (
	        <ul>
	          {data.map((item) => (
	            <li key={item.id}>{item.nombre}</li>
	          ))}
	        </ul>
	      )}
	    </div>
	  );
	}

	export default MiComponente;

	```	

	Hemos declarado dos estados, 'data' y 'loading', para almacenar los datos obtenidos y controlar el estado de carga respectivamente.

    Usamos 'useEffect' con una lista de dependencias vacía [], lo que significa que el efecto se ejecutará solo una vez, cuando el componente se monte inicialmente.

    Dentro del efecto, definimos una función 'fetchData' asincrónica que realiza una solicitud a una API (debes reemplazar la URL con la de tu propia API). 

    Cuando se completa la solicitud, actualizamos el estado 'data' con los datos obtenidos y cambiamos el estado 'loading' a 'false' para indicar que la carga ha finalizado.

    Si se produce un error durante la solicitud, manejamos el error y también cambiamos el estado 'loading' a 'false'.

	En el JSX, mostramos un mensaje de carga mientras 'loading' es true, y una lista de datos cuando 'loading' es 'false'. 	


	Este patrón "useEffect Fetch Data" es comúnmente utilizado para cargar datos externos de manera asíncrona en componentes de React.



|| Multiple Returns

	Patrón de diseño en el que un componente de función puede renderizar contenido diferente en función de una condición o de la lógica de tu aplicación. 

	Esto se logra utilizando declaraciones condicionales dentro del componente para determinar qué elementos se deben mostrar en función de ciertas condiciones

	```
	import React, { useState } from 'react';

	function MiComponente() {
	  const [mostrarMensaje, setMostrarMensaje] = useState(false);

	  return (
	    <div>
	      <button onClick={() => setMostrarMensaje(!mostrarMensaje)}>
	        Mostrar/Ocultar Mensaje
	      </button>

	      {mostrarMensaje ? (
	        <p>Este es un mensaje que se muestra cuando mostrarMensaje es verdadero.</p>
	      ) : (
	        <p>El mensaje está oculto. Haz clic para mostrarlo.</p>
	      )}
	    </div>
	  );
	}

	export default MiComponente;

	```	

	'MiComponente' que muestra un mensaje cuando se establece la variable de estado 'mostrarMensaje' en 'true'.

	Cuando hacemos clic en el botón "Mostrar/Ocultar Mensaje", cambiamos el valor de 'mostrarMensaje', lo que causa un re-renderizado del componente.

	Dependiendo del valor de 'mostrarMensaje', se mostrará uno de los dos bloques de JSX condicionalmente	


	Puedes utilizar declaraciones if, operadores ternarios (? :), o cualquier otra lógica de control de flujo de JavaScript para determinar qué contenido se debe renderizar en función de las condiciones de tu aplicación. 

	Este patrón es útil para crear componentes dinámicos y responsivos que se adaptan a diferentes situaciones o estados de la aplicación



|| Multiple Returns: Fetching Data


	Patrón en el que un componente de React muestra diferentes contenidos en función del estado de la carga de datos desde una fuente externa, como una API o una solicitud de red. 

	Este patrón es comúnmente utilizado para proporcionar una experiencia de usuario más informativa mientras se obtienen datos de manera asincrónica.

	Ejemplo: Manejo carga de datos

	```jsx

	import React, { useState, useEffect } from 'react';

	function MiComponente() {
	  const [data, setData] = useState(null); // Estado para almacenar los datos
	  const [loading, setLoading] = useState(true); // Estado para controlar la carga
	  const [error, setError] = useState(null); // Estado para manejar errores

	  useEffect(() => {
	    // Simulación de una solicitud de datos asincrónica
	    setTimeout(() => {
	      fetch('https://api.ejemplo.com/data') // Reemplaza la URL con tu API real
	        .then((response) => {
	          if (!response.ok) {
	            throw new Error('No se pudieron cargar los datos');
	          }
	          return response.json();
	        })
	        .then((jsonData) => {
	          setData(jsonData);
	          setLoading(false); // Cambia el estado de carga a falso
	        })
	        .catch((error) => {
	          setError(error);
	          setLoading(false); // Cambia el estado de carga a falso en caso de error
	        });
	    }, 2000); // Simulación de una demora de 2 segundos
	  }, []);

	  return (
	    <div>
	      {loading ? (
	        <p>Cargando datos...</p>
	      ) : error ? (
	        <p>Error: {error.message}</p>
	      ) : data ? (
	        <div>
	          <h2>Datos Cargados:</h2>
	          <pre>{JSON.stringify(data, null, 2)}</pre>
	        </div>
	      ) : null}
	    </div>
	  );
	}

	export default MiComponente;


	```

	Utilizamos tres estados:'data', 'loading', y 'error' para gestionar el estado de carga de datos y manejar posibles errores durante la solicitud de datos.
    
   	Dentro de 'useEffect', simulamos una solicitud de datos asincrónica que se ejecuta después de que el componente se monta inicialmente. 

    Usamos un temporizador para simular una demora en la solicitud.
    
    Dependiendo del estado de 'loading', 'error', y 'data', mostramos diferentes contenidos en el componente:
        
        Si loading es true, mostramos un mensaje de "Cargando datos...".
        
        Si error contiene un error, mostramos un mensaje de error.
        
        Si data contiene datos válidos, mostramos los datos en una representación JSON.
    
    Usamos operadores ternarios (? :) para determinar qué contenido mostrar condicionalmente.



|| Operadores lógicos y Operador ternario

	Son && (AND), || (OR) y ! (NOT).

	1. && (AND):

		Evaluar si todas las expresiones lógicas en una condición son verdaderas.

		Devuelve true si todas las expresiones son verdaderas y false si al menos una de ellas es falsa.

		```
		if (condicion1 && condicion2) {
		  // Se ejecuta si ambas condiciones son verdaderas
		}

		```


	2. Operador || (OR): 

		Este operador se utiliza para evaluar si al menos una de las expresiones lógicas en una condición es verdadera.

		Devuelve true si al menos una de las expresiones es verdadera y false si todas son falsas.

		```	
		if (condicion1 || condicion2) {
		  // Se ejecuta si al menos una de las condiciones es verdadera
		}

		```

	3. Operador ! (NOT): 

		Este operador se utiliza para invertir el valor de una expresión lógica. 

		Si una expresión es verdadera, ! la convertirá en falsa, y si una expresión es falsa, ! la convertirá en verdadera.

		```
		if (!condicion) {
		  // Se ejecuta si la condición es falsa
		}

		```


	4. Ternario: 

		Permite tomar decisiones basadas en una condición. 

		```
		condicion ? expresion_si_verdadero : expresion_si_falso

		```

		condicion: 

			Una expresión que se evalúa como verdadera o falsa.
	    
	    expresion_si_verdadero: 

	    	El valor o expresión que se devuelve si la condición es verdadera.
	    
	    expresion_si_falso: 

	    	El valor o expresión que se devuelve si la condición es falsa.



|| Mostrar y ocultar componentes

	En función de una condición o un evento específico. 

	Esto se logra utilizando lógica condicional en tu componente para determinar cuándo se debe renderizar o no un componente en particular.	


	1. Condicional: 

	```
	function MiComponente({ mostrarComponente }) {
	  return (
	    <div>
	      {mostrarComponente && <ComponenteVisible />}
	    </div>
	  );
	}

	```
	'ComponenteVisible' se renderiza solo si 'mostrarComponente' es true.


	2. Con CSS: 

		Utiliza CSS para mostrar u ocultar un componente aplicando clases con display: none o visibility: hidden en función de una condición


	```
	function MiComponente({ mostrarComponente }) {
	  return (
	    <div className={mostrarComponente ? 'visible' : 'oculto'}>
	      <Componente />
	    </div>
	  );
	}

	```

	Las clases CSS "visible" y "oculto" se aplican al componente contenedor para mostrar u ocultar el componente interno.


	3. Usando React: 

		Utiliza el estado de React para controlar si un componente se muestra o se oculta. 

		```
		function MiComponente() {
		  const [mostrarComponente, setMostrarComponente] = useState(false);

		  return (
		    <div>
		      <button onClick={() => setMostrarComponente(!mostrarComponente)}>
		        {mostrarComponente ? 'Ocultar' : 'Mostrar'} Componente
		      </button>
		      {mostrarComponente && <ComponenteVisible />}
		    </div>
		  );
		}

		```		



|| Form

	Permite a los usuarios interactuar con la aplicación ingresando datos y enviándolos al servidor o realizando acciones basadas en esos datos. 

	Los formularios son una forma común de recopilar información del usuario, como nombre, contraseña, comentarios, selecciones y más.


	1. Elementos de formulario: 

		Los elementos HTML como <input>, <textarea>, <select>, etc., se utilizan para recopilar datos del usuario. 

		En React, estos elementos se representan como componentes controlados, lo que significa que su valor está vinculado a un estado de React.


    2. Estado de React: 

    	Utilizas el estado de React para mantener y controlar los valores de los elementos del formulario. 

    	Cada vez que un usuario ingresa información en un elemento del formulario, se actualiza el estado de React correspondiente.


    3. Manejo de eventos: 

    	Debes manejar eventos del formulario, como "submit" cuando el usuario envía el formulario y "change" cuando los valores de los elementos del formulario cambian. 

    	Puedes usar funciones manejadoras de eventos para controlar estas interacciones.


    4. Validación: 

    	A menudo, es necesario validar los datos ingresados por el usuario antes de enviarlos al servidor. 

    	Puedes realizar la validación tanto en el lado del cliente (en React) como en el lado del servidor que es la opción más segura. 

    
    5. Envío de datos: 

    	Una vez que el usuario completa el formulario, los datos se envían al servidor para su procesamiento. 

    	Esto generalmente se hace a través de una solicitud HTTP, como una solicitud POST, que puede ser manejada por un servidor web o una API.


    ```jsx

	import React, { useState } from 'react';

	function MiFormulario() {
	  const [nombre, setNombre] = useState('');
	  const [correo, setCorreo] = useState('');

	  const handleSubmit = (event) => {
	    event.preventDefault();
	    // Aquí puedes realizar acciones con los datos, como enviarlos a un servidor
	    console.log(`Nombre: ${nombre}, Correo: ${correo}`);
	  };

	  return (
	    <form onSubmit={handleSubmit}>
	      <label>
	        Nombre:
	        <input
	          type="text"
	          value={nombre}
	          onChange={(e) => setNombre(e.target.value)}
	        />
	      </label>
	      <br />
	      <label>
	        Correo:
	        <input
	          type="email"
	          value={correo}
	          onChange={(e) => setCorreo(e.target.value)}
	        />
	      </label>
	      <br />
	      <button type="submit">Enviar</button>
	    </form>
	  );
	}

	export default MiFormulario;

	```

    Utilizamos el estado de React para controlar los valores de los campos "nombre" y "correo".

    Usamos la función useState para inicializar el estado.

    La función 'handleSubmit' se ejecuta cuando el usuario envía el formulario. 

    Utiliza 'event.preventDefault()'' para evitar que la página se recargue, lo que es el comportamiento predeterminado de un formulario HTML.

    Los valores de los campos de entrada se actualizan mediante el evento 'onChange', que llama a las funciones 'setNombre' y 'setCorreo' para actualizar el estado a medida que el usuario escribe.



|| Controlled Inputs

	En React, los "Controlled Inputs" (entradas controladas) son elementos de formulario cuyos valores están controlados y gestionados por el estado de React. 

	Esto significa que el estado de la aplicación de React es la fuente única de verdad para el valor del elemento de entrada, y cualquier cambio en el valor del elemento se refleja en el estado de React y viceversa.


	1. Crear un estado en React para el valor del elemento de entrada:

		Utiliza 'useState' o el estado de un componente de clase para inicializar y mantener el valor del elemento de entrada.


	2. Asociar el valor del elemento de entrada con el estado de React:

		Establece el valor del elemento de entrada ('value' en un input, 'defaultValue' en un textarea, etc.) igual al valor del estado de React.


	3. Agregar un manejador de eventos para capturar cambios en el elemento de entrada: 

		Agrega un manejador de eventos, como 'onChange', al elemento de entrada. 

		Cuando el usuario interactúa con el elemento de entrada y cambia su valor, el manejador de eventos se ejecuta y actualiza el estado de React con el nuevo valor.


	4. Actualizar el estado de React cuando cambie el valor del elemento de entrada: 

		En el manejador de eventos, actualiza el estado de React con el nuevo valor del elemento de entrada utilizando la función 'setState'.


	```
	import React, { useState } from 'react';

	function MiComponente() {
	  const [texto, setTexto] = useState('');

	  const handleChange = (event) => {
	    setTexto(event.target.value);
	  };

	  return (
	    <div>
	      <input
	        type="text"
	        value={texto}
	        onChange={handleChange}
	      />
	      <p>Texto ingresado: {texto}</p>
	    </div>
	  );
	}

	export default MiComponente;


	```

	Utilizamos el estado de React ('texto' y 'setTexto') para controlar el valor de la entrada de texto.
    
    Asociamos el valor del 'input' con el estado de React al establecer 'value={texto}'.

    Agregamos un manejador de eventos 'onChange' al 'input' que llama a 'setTexto' para actualizar el estado de React cada vez que el usuario escribe en el campo de texto.

    Mostramos el valor del texto en el párrafo debajo del 'input'.



|| Item and List

	Agregar un nuevo elemento a una lista existente o a un conjunto de datos representados en tu aplicación. 

	Esto es una operación común en aplicaciones web y se utiliza para permitir a los usuarios agregar datos, como tareas, mensajes, elementos de compra o cualquier otra cosa que deba registrarse en una lista.


	1. Mantén una lista en el estado: 

		Utiliza el estado de React para mantener y gestionar la lista de elementos. 

		Esto puede hacerse utilizando el hook useState o el estado de un componente de clase.


	2. Crea un formulario para ingresar nuevos elementos: 

		Proporciona un formulario o un campo de entrada donde los usuarios puedan ingresar el nuevo elemento que desean agregar a la lista.


	3. Maneja el evento de envío del formulario: 

		Agrega un manejador de eventos al formulario para capturar cuando el usuario envía el formulario. 

		Esto generalmente se hace mediante un evento "submit".

	
	4. Actualiza el estado para agregar el nuevo elemento: 

		En el manejador de eventos de envío del formulario, actualiza el estado de React para agregar el nuevo elemento a la lista existente.


	5. Renderiza la lista actualizada: 

		Asegúrate de que tu componente React vuelva a renderizar con la lista actualizada. 

		Esto mostrará el nuevo elemento en la interfaz de usuario.


	```jsx

	import React, { useState } from 'react';

	function ListaDeTareas() {
	  const [tareas, setTareas] = useState([]);
	  const [nuevaTarea, setNuevaTarea] = useState('');

	  const agregarTarea = () => {
	    if (nuevaTarea.trim() !== '') {
	      setTareas([...tareas, nuevaTarea]);
	      setNuevaTarea('');
	    }
	  };

	  return (
	    <div>
	      <h2>Lista de Tareas</h2>
	      <ul>
	        {tareas.map((tarea, index) => (
	          <li key={index}>{tarea}</li>
	        ))}
	      </ul>
	      <div>
	        <input
	          type="text"
	          placeholder="Nueva Tarea"
	          value={nuevaTarea}
	          onChange={(e) => setNuevaTarea(e.target.value)}
	        />
	        <button onClick={agregarTarea}>Agregar</button>
	      </div>
	    </div>
	  );
	}

	export default ListaDeTareas;

	```

	Utilizamos el estado de React ('tareas' y 'nuevaTarea') para mantener una lista de tareas y el valor de la nueva tarea que se ingresará.
	
	Cuando el usuario ingresa una tarea y hace clic en el botón "Agregar", llamamos a la función 'agregarTarea', que agrega la nueva tarea a la lista tareas y luego borra el campo de entrada.
    
    La lista de tareas se representa en la interfaz de usuario utilizando un elemento '<ul>' y se actualiza cada vez que se agrega una nueva tarea a través del mapeo de la matriz 'tareas'.



|| Multiple Inputs


    Estado de React: 

    	Utiliza el estado de React para mantener y controlar los valores de los campos de entrada. 

    	Puedes utilizar un objeto o varios estados separados, uno para cada campo.


    Manejadores de eventos: 

    	Asocia un manejador de eventos, como onChange, a cada campo de entrada. 

    	Cuando un usuario interactúa con un campo y cambia su valor, el manejador de eventos se ejecuta y actualiza el estado de React con el nuevo valor.


    Asociación de valores: 

    	Asocia el valor de cada campo de entrada con su respectivo estado en React utilizando la propiedad value (o defaultValue para campos de entrada no controlados).


    Validación y manejo de eventos: 

    	En el manejador de eventos, puedes realizar validación, ejecutar lógica personalizada o realizar otras acciones en función de los valores de los campos de entrada.


    ```jsx

    import React, { useState } from 'react';

	function Formulario() {
	  const [formulario, setFormulario] = useState({
	    nombre: '',
	    correo: '',
	    edad: '',
	  });

	  const handleChange = (event) => {
	    const { name, value } = event.target;
	    setFormulario({
	      ...formulario,
	      [name]: value,
	    });
	  };

	  const handleSubmit = (event) => {
	    event.preventDefault();
	    // Realiza acciones con los valores del formulario
	    console.log(formulario);
	  };

	  return (
	    <form onSubmit={handleSubmit}>
	      <div>
	        <label>
	          Nombre:
	          <input
	            type="text"
	            name="nombre"
	            value={formulario.nombre}
	            onChange={handleChange}
	          />
	        </label>
	      </div>
	      <div>
	        <label>
	          Correo:
	          <input
	            type="email"
	            name="correo"
	            value={formulario.correo}
	            onChange={handleChange}
	          />
	        </label>
	      </div>
	      <div>
	        <label>
	          Edad:
	          <input
	            type="number"
	            name="edad"
	            value={formulario.edad}
	            onChange={handleChange}
	          />
	        </label>
	      </div>
	      <div>
	        <button type="submit">Enviar</button>
	      </div>
	    </form>
	  );
	}

	export default Formulario;


    ```

    Utilizamos un objeto 'formulario' en el estado de React para mantener los valores de los campos de entrada.
    
    Asociamos cada campo de entrada ('nombre', 'correo' y 'edad') con su respectivo estado utilizando la propiedad 'name' y la función 'handleChange' maneja los cambios en los campos de entrada y actualiza el estado correspondiente.
    
    En el manejador de eventos 'handleSubmit', puedes realizar acciones con los valores del formulario, como enviarlos al servidor o realizar validaciones.


|| useRef

	Proporciona una forma de acceder y manipular directamente el DOM (Document Object Model) o elementos de una interfaz de usuario en un componente de React.

	A diferencia del estado, 'useRef' no causa una nueva representación o renderizado del componente cuando cambia, lo que lo hace útil para realizar tareas de manipulación del DOM y almacenar valores que no afectan la representación.


	1. Acceso al DOM: 

		Puedes utilizar useRef para acceder a elementos del DOM directamente.

		Esto es útil para enfocar un campo de entrada, medir dimensiones, o realizar operaciones directamente en elementos HTML.


	2. Almacenamiento de valores persistentes: 

		Aunque useRef no causa una renderización cuando cambia, puedes usarlo para almacenar valores que persisten entre renderizaciones. 

		Esto es útil para mantener valores o datos que no deben causar un nuevo renderizado del componente.

		```jsx

		import React, { useRef } from 'react';

		function MiComponente() {
		  const contadorRef = useRef(0);

		  const incrementarContador = () => {
		    contadorRef.current += 1;
		    console.log(`Contador: ${contadorRef.current}`);
		  };

		  return (
		    <div>
		      <p>Contador: {contadorRef.current}</p>
		      <button onClick={incrementarContador}>Incrementar</button>
		    </div>
		  );
		}

		export default MiComponente;

		```		


	3. Referencias a componentes funcionales: 

		useRef también puede utilizarse para mantener referencias a componentes funcionales, lo que permite acceder a métodos o propiedades del componente hijo funcional desde el componente padre.

		```jsx

		import React, { useRef } from 'react';

		function Hijo() {
		  const mostrarMensaje = () => {
		    alert('Mensaje desde el hijo');
		  };

		  return (
		    <div>
		      <button onClick={mostrarMensaje}>Mostrar Mensaje</button>
		    </div>
		  );
		}

		function Padre() {
		  const hijoRef = useRef();

		  const mostrarMensajeDelHijo = () => {
		    hijoRef.current.mostrarMensaje();
		  };

		  return (
		    <div>
		      <button onClick={mostrarMensajeDelHijo}>Mostrar Mensaje del Hijo</button>
		      <Hijo ref={hijoRef} />
		    </div>
		  );
		}

		export default Padre;


		```


	Cuando se usa 'useRef', el valor de 'ref.current' persiste entre renderizaciones, pero cambiar el valor de 'ref.current' directamente no provocará un nuevo renderizado del componente



|| useReducer

	Se utiliza para gestionar el estado de un componente cuando dicho estado es complejo o cuando las actualizaciones del estado dependen de acciones específicas. 

	En esencia, 'useReducer' es una alternativa a 'useState' que te permite manejar el estado en función de acciones o eventos específicos en lugar de actualizaciones directas del estado.

	Se basa en el concepto de "reducción" (o reducción de datos) que es común en la programación funcional. 

	La reducción implica tomar una lista de valores y reducirla a un solo valor aplicando una función a cada elemento de la lista. 

	En el contexto de React, useReducer permite que el estado del componente sea el resultado de aplicar una función reductora a una serie de acciones.	

	```
	const [state, dispatch] = useReducer(reducer, initialState);

	```

	state: 

		Es el estado actual que se va a gestionar.

    dispatch: 

    	Es una función que se utiliza para enviar acciones al reductor (reducer).

    reducer: 

    	Es una función que especifica cómo se debe actualizar el estado en función de las acciones enviadas.

    initialState: 

    	Es el estado inicial del componente.


    La función 'reducer' toma dos argumentos: 

    	El estado actual y una acción, y devuelve un nuevo estado. 

    	Las acciones son objetos que generalmente contienen un tipo que describe la acción y, opcionalmente, datos adicionales que pueden usarse para actualizar el estado.


    ```
    import React, { useReducer } from 'react';

	// Reducer: Define cómo se actualiza el estado en función de las acciones
	const contadorReducer = (state, action) => {
	  switch (action.type) {
	    case 'INCREMENT':
	      return { count: state.count + 1 };
	    case 'DECREMENT':
	      return { count: state.count - 1 };
	    default:
	      return state;
	  }
	};

	function Contador() {
	  // Inicializa el estado y el reductor
	  const [state, dispatch] = useReducer(contadorReducer, { count: 0 });

	  return (
	    <div>
	      <p>Contador: {state.count}</p>
	      <button onClick={() => dispatch({ type: 'INCREMENT' })}>Incrementar</button>
	      <button onClick={() => dispatch({ type: 'DECREMENT' })}>Decrementar</button>
	    </div>
	  );
	}

	export default Contador;

    ```

    Hemos definido un reductor 'contadorReducer' que actualiza el estado en función de las acciones 'INCREMENT' y 'DECREMENT'.

    Usamos 'useReducer' para inicializar el estado y el reductor en el componente 'Contador'.

    Los botones llaman a 'dispatch' con diferentes acciones cuando se hacen clic, lo que desencadena la actualización del estado en función de las acciones y, a su vez, provoca un nuevo renderizado del componente.



|| useReducer - Refactor

	Reorganizar o mejorar un componente existente que utiliza el hook useReducer para gestionar el estado. 

	El objetivo de este proceso de refactorización es mejorar la legibilidad, el rendimiento o la organización del código del componente sin cambiar su funcionalidad principal.


	```jsx

	import React, { useReducer } from 'react';

	const initialState = { count: 0 };

	const reducer = (state, action) => {
	  switch (action.type) {
	    case 'INCREMENT':
	      return { count: state.count + 1 };
	    case 'DECREMENT':
	      return { count: state.count - 1 };
	    default:
	      return state;
	  }
	};

	const Contador = () => {
	  const [state, dispatch] = useReducer(reducer, initialState);

	  const incrementar = () => {
	    dispatch({ type: 'INCREMENT' });
	  };

	  const decrementar = () => {
	    dispatch({ type: 'DECREMENT' });
	  };

	  return (
	    <div>
	      <p>Contador: {state.count}</p>
	      <button onClick={incrementar}>Incrementar</button>
	      <button onClick={decrementar}>Decrementar</button>
	    </div>
	  );
	};

	export default Contador;

	```



|| useReducer - Add Item

	Agregar elementos a una lista o array en un componente. 

	Esto es útil cuando deseas gestionar una lista dinámica de elementos y necesitas manejar las operaciones de agregar elementos de manera más controlada.


	```jsx

	import React, { useReducer, useState } from 'react';

	// Reducer: Define cómo se actualiza el estado en función de las acciones
	const listaReducer = (state, action) => {
	  switch (action.type) {
	    case 'AGREGAR_ITEM':
	      return [...state, action.payload]; // Agregar el nuevo elemento al final de la lista
	    default:
	      return state;
	  }
	};

	function Lista() {
	  const [lista, dispatch] = useReducer(listaReducer, []);
	  const [nuevoItem, setNuevoItem] = useState('');

	  const agregarItem = () => {
	    if (nuevoItem.trim() !== '') {
	      dispatch({ type: 'AGREGAR_ITEM', payload: nuevoItem });
	      setNuevoItem(''); // Limpiar el campo de entrada después de agregar el elemento
	    }
	  };

	  return (
	    <div>
	      <h2>Lista de Elementos</h2>
	      <ul>
	        {lista.map((item, index) => (
	          <li key={index}>{item}</li>
	        ))}
	      </ul>
	      <div>
	        <input
	          type="text"
	          placeholder="Nuevo Elemento"
	          value={nuevoItem}
	          onChange={(e) => setNuevoItem(e.target.value)}
	        />
	        <button onClick={agregarItem}>Agregar</button>
	      </div>
	    </div>
	  );
	}

	export default Lista;


	```

	Se define el reductor 'listaReducer' que maneja la acción 'AGREGAR_ITEM' para agregar un nuevo elemento a la lista.

	Usamos 'useReducer' para gestionar el estado de la lista y su reductor.
	
	El campo de entrada permite al usuario ingresar un nuevo elemento, y el botón "Agregar" llama a la función 'agregarItem' que envía una acción al reductor para agregar el elemento a la lista.

	El estado del nuevo elemento se limpia después de agregarlo a la lista para permitir que el usuario agregue más elementos fácilmente.


	Este patrón te permite administrar la lógica de agregar elementos de manera más controlada y escalable utilizando useReducer en React.

	Puedes extender este ejemplo para manejar otras operaciones CRUD (Crear, Leer, Actualizar y Eliminar) en una lista de elementos si es necesario.



|| useReducer - Remove Item
	
	```jsx

	import React, { useReducer } from 'react';

	// Reducer: Define cómo se actualiza el estado en función de las acciones
	const listaReducer = (state, action) => {
	  switch (action.type) {
	    case 'AGREGAR_ITEM':
	      return [...state, action.payload]; // Agregar el nuevo elemento al final de la lista
	    case 'ELIMINAR_ITEM':
	      return state.filter((item, index) => index !== action.payload); // Eliminar el elemento por índice
	    default:
	      return state;
	  }
	};

	function Lista() {
	  const [lista, dispatch] = useReducer(listaReducer, []);
	  const [nuevoItem, setNuevoItem] = React.useState('');

	  const agregarItem = () => {
	    if (nuevoItem.trim() !== '') {
	      dispatch({ type: 'AGREGAR_ITEM', payload: nuevoItem });
	      setNuevoItem(''); // Limpiar el campo de entrada después de agregar el elemento
	    }
	  };

	  const eliminarItem = (index) => {
	    dispatch({ type: 'ELIMINAR_ITEM', payload: index });
	  };

	  return (
	    <div>
	      <h2>Lista de Elementos</h2>
	      <ul>
	        {lista.map((item, index) => (
	          <li key={index}>
	            {item} <button onClick={() => eliminarItem(index)}>Eliminar</button>
	          </li>
	        ))}
	      </ul>
	      <div>
	        <input
	          type="text"
	          placeholder="Nuevo Elemento"
	          value={nuevoItem}
	          onChange={(e) => setNuevoItem(e.target.value)}
	        />
	        <button onClick={agregarItem}>Agregar</button>
	      </div>
	    </div>
	  );
	}

	export default Lista;

	```

	Hemos extendido el reductor 'listaReducer' para manejar la acción 'ELIMINAR_ITEM', que elimina un elemento de la lista por su índice utilizando el método 'filter'.
	
	Se ha agregado un botón "Eliminar" junto a cada elemento de la lista, y al hacer clic en él, se llama a la función 'eliminarItem' con el índice del elemento a eliminar.

	La función 'eliminarItem' envía la acción 'ELIMINAR_ITEM' al reductor, lo que provoca la eliminación del elemento correspondiente de la lista
	


|| Prop Drilling

	También conocido como "prop passing" o "prop threading" es una situación en la que los datos o propiedades (props) se pasan a través de múltiples niveles de componentes, desde un componente padre hacia uno o varios componentes hijos, incluso cuando algunos de los componentes intermedios no necesitan esos datos en absoluto. 

	Esto puede hacer que el código sea menos limpio, más propenso a errores y menos eficiente.

	El propósito de las props en React es pasar datos desde un componente padre a sus componentes hijos para que los hijos puedan renderizar y funcionar en función de esos datos.

	Sin embargo, cuando tienes muchos componentes anidados y necesitas que los datos lleguen a un componente profundo en el árbol de componentes, a menudo se pasa el mismo conjunto de datos a través de varios componentes intermedios que no hacen uso de esos datos. 

	Esto se llama prop drilling y puede llevar a problemas como:


	1. Dificultad en el mantenimiento:

		Si necesitas agregar o modificar datos en varios niveles del árbol de componentes, debes actualizar las props en todos los niveles, lo que puede ser propenso a errores y difícil de mantener.


	2. Menos eficiencia: 

		Pasar datos innecesarios a través de múltiples componentes puede afectar negativamente el rendimiento de tu aplicación, ya que aumenta la cantidad de re-renderizaciones que deben ocurrir cuando los datos cambian.


	3. Menos legibilidad: 

		El código puede volverse menos legible y más difícil de seguir si tienes que rastrear las props a través de múltiples niveles de componentes


	Para abordar el problema del prop drilling, puedes utilizar otras técnicas de gestión de estado en React, como el uso de context (Context API) o la implementación de Redux (un contenedor de estado global). 

	Estas técnicas permiten compartir datos de manera más eficiente entre componentes sin tener que pasar explícitamente las props a través de todos los niveles del árbol de componentes



|| Context API

	Es una característica que permite pasar datos a través del árbol de componentes de React sin tener que pasar explícitamente las propiedades a través de cada nivel del árbol. 

	Es especialmente útil cuando deseas compartir datos, como el estado de la autenticación, preferencias del usuario o cualquier otro dato global, entre varios componentes en diferentes niveles de jerarquía.
	

	1. Provider (Proveedor): 

		El componente que proporciona el contexto y los datos a los componentes secundarios. 

		Debes envolver tus componentes con este componente para que puedan acceder al contexto.

    
    2. Consumer (Consumidor): 

    	El componente que consume y accede a los datos del contexto. 

    	Los componentes secundarios que necesitan acceder a los datos del contexto deben ser envueltos en un componente Consumer.


    3. Context Object (Objeto de Contexto): 

    	Un objeto que define el contexto y proporciona los datos que deseas compartir.

    	Puedes crear un objeto de contexto utilizando la función React.createContext().


    ```jsx

    import React, { createContext, useContext, useState } from 'react';

	// 1. Crear un objeto de contexto
	const AuthContext = createContext();

	// 2. Crear un componente Provider que proporciona los datos de contexto
	const AuthProvider = ({ children }) => {
	  const [usuario, setUsuario] = useState(null);

	  const login = (usuario) => {
	    setUsuario(usuario);
	  };

	  const logout = () => {
	    setUsuario(null);
	  };

	  return (
	    <AuthContext.Provider value={{ usuario, login, logout }}>
	      {children}
	    </AuthContext.Provider>
	  );
	};

	// 3. Crear un componente Consumer que consume los datos de contexto
	const UserProfile = () => {
	  const { usuario, logout } = useContext(AuthContext);

	  return (
	    <div>
	      {usuario ? (
	        <div>
	          <p>Usuario: {usuario}</p>
	          <button onClick={logout}>Cerrar Sesión</button>
	        </div>
	      ) : (
	        <p>Inicia sesión</p>
	      )}
	    </div>
	  );
	};

	const App = () => {
	  return (
	    // 4. Envolver tus componentes con el Provider para que puedan acceder al contexto
	    <AuthProvider>
	      <UserProfile />
	    </AuthProvider>
	  );
	};

	export default App;

    ```

    Creamos un objeto de contexto 'AuthContext' utilizando 'React.createContext()'.
    
    Creamos un componente 'AuthProvider' que envuelve a 'UserProfile' con el 'AuthContext.Provider'. 

    Este componente proporciona los datos de autenticación y las funciones de inicio de sesión y cierre de sesión a través del valor del contexto.

    'UserProfile' consume los datos del contexto utilizando 'useContext(AuthContext)'.

    El componente principal 'App' envuelve todos los componentes con 'AuthProvider' para que puedan acceder al contexto.


	La Context API es una forma poderosa de gestionar el estado global y compartir datos entre componentes en React sin tener que utilizar prop drilling (pasar props a través de múltiples niveles de componentes).


|| Custom Hooks - 

	Técnica que te permite reutilizar la lógica de estado y efectos en tus componentes funcionales. 

	Los Custom Hooks son funciones personalizadas que pueden contener lógica de React, como el uso de 'useState', 'useEffect', 'useContext', y otros hooks, y pueden ser compartidas y reutilizadas en diferentes componentes de tu aplicación.


	```jsx

	import { useState } from 'react';

	// Definir un Custom Hook llamado useContador
	function useContador() {
	  const [count, setCount] = useState(0);

	  const incrementar = () => {
	    setCount(count + 1);
	  };

	  const decrementar = () => {
	    setCount(count - 1);
	  };

	  return { count, incrementar, decrementar };
	}

	export default useContador;

	```

	Luego, puedes utilizar este Custom Hook en tus componentes de la siguiente manera:


	```jsx

	import React from 'react';
	import useContador from './useContador';

	function MiComponente() {
	  // Utilizar el Custom Hook useContador
	  const { count, incrementar, decrementar } = useContador();

	  return (
	    <div>
	      <p>Contador: {count}</p>
	      <button onClick={incrementar}>Incrementar</button>
	      <button onClick={decrementar}>Decrementar</button>
	    </div>
	  );
	}

	```

	Puedes reutilizar la lógica de gestión del contador en diferentes componentes sin tener que escribirla nuevamente en cada uno de ellos. 

	Los Custom Hooks pueden ser compartidos en toda tu aplicación o incluso en proyectos diferentes, lo que los hace útiles para abstraer la lógica común y mejorar la modularidad y la mantenibilidad de tu código.


	Al crear Custom Hooks, es importante seguir algunas convenciones:

    	1. El nombre del Custom Hook debe comenzar con "use" para que React lo reconozca como un hook.

    	2. Puedes utilizar cualquier combinación de hooks existentes dentro de tu Custom Hook, lo que te permite combinarlos y crear funciones personalizadas más avanzadas.



|| Custom Hooks - useFetch

	Hook personalizado para gestionar solicitudes de red y recuperación de datos en componentes funcionales. 

	Un Custom Hook llamado "useFetch" es una práctica común que te permite encapsular la lógica de realizar solicitudes HTTP y gestionar el ciclo de vida de una solicitud en un hook reutilizable.


	```jsx 

	import { useState, useEffect } from 'react';

	function useFetch(url) {
	  const [data, setData] = useState(null);
	  const [loading, setLoading] = useState(true);
	  const [error, setError] = useState(null);

	  useEffect(() => {
	    // Función para realizar la solicitud y gestionar los resultados
	    async function fetchData() {
	      try {
	        const response = await fetch(url);
	        if (!response.ok) {
	          throw new Error('La solicitud no fue exitosa');
	        }
	        const jsonData = await response.json();
	        setData(jsonData);
	        setLoading(false);
	      } catch (error) {
	        setError(error);
	        setLoading(false);
	      }
	    }

	    fetchData();
	  }, [url]);

	  return { data, loading, error };
	}

	export default useFetch;

	```

	Este Custom Hook "useFetch" toma una URL como argumento y utiliza 'useState' y 'useEffect' para gestionar el estado de la solicitud. 

	Proporciona tres valores de retorno:

    data: 

    	Los datos recuperados de la solicitud.

    loading: 

    	Un indicador booleano que muestra si la solicitud está en curso.

    error: 

    	Cualquier error que ocurra durante la solicitud


    Utilizar este Custom Hook "useFetch" en tus componentes funcionales para realizar solicitudes HTTP y gestionar la recuperación de datos de una manera más reutilizable y legible:


    ```jsx

    import React from 'react';
	import useFetch from './useFetch';

	function App() {
	  const { data, loading, error } = useFetch('https://jsonplaceholder.typicode.com/posts/1');

	  if (loading) {
	    return <p>Cargando...</p>;
	  }

	  if (error) {
	    return <p>Error: {error.message}</p>;
	  }

	  return (
	    <div>
	      <h1>Título: {data?.title}</h1>
	      <p>Cuerpo: {data?.body}</p>
	    </div>
	  );
	}

	export default App;

    ```

    El componente 'App' utiliza el Custom Hook "useFetch" para realizar una solicitud HTTP y muestra los resultados en función del estado de carga y los posibles errores.



|| PropTypes

	Se utiliza para definir y validar los tipos de propiedades (props) que se esperan en un componente de React. 

	PropTypes proporciona una forma de documentar y asegurar que los componentes de tu aplicación reciban las props correctas y que sean del tipo adecuado.
	
	Documentación: 

		Ayuda a documentar el propósito y los tipos de props que un componente espera recibir, lo que facilita que otros desarrolladores comprendan cómo deben usar el componente.


	Validación: 

		Proporciona una capa de validación en tiempo de ejecución para asegurarse de que las props pasadas a un componente sean del tipo correcto. 

		Esto puede ayudar a detectar errores de forma temprana durante el desarrollo	


	Para usarlo debes importar el paquete prop-types y definir un objeto propTypes como una propiedad estática del componente.

	Luego, puedes declarar el tipo esperado de cada prop como una propiedad dentro de este objeto


	```jsx

	import React from 'react';
	import PropTypes from 'prop-types';

	function Saludo(props) {
	  return <div>Hola, {props.nombre}!</div>;
	}

	// Definir propTypes para el componente
	Saludo.propTypes = {
	  nombre: PropTypes.string.isRequired, // Se espera una cadena y es requerida
	};

	export default Saludo;

	```

	Hemos definido PropTypes para el componente Saludo:

    	'nombre' se espera que sea una cadena (string) y se marca como requerida (isRequired). 

    	Esto significa que si no se proporciona nombre o si no es una cadena, React mostrará una advertencia en la consola durante el tiempo de desarrollo.

	Puedes definir varios tipos de PropTypes, como string, number, boolean, array, object, func, node, element, instanceOf, enum, y más, según tus necesidades. 

	También puedes utilizar PropTypes personalizados para validar propiedades de manera más compleja.

	Es importante mencionar que a partir de React v15.5 en adelante, PropTypes se ha movido a un paquete independiente llamado prop-types. 

	Por lo tanto, es necesario instalarlo y luego importarlo en tus componentes, como se muestra en el ejemplo anterior.	



|| PropTypes - Images

	Validar las propiedades (props) que se pasan a tus componentes, incluidas las propiedades que representan imágenes. 

	Esto te permite documentar y garantizar que las imágenes se proporcionen de la manera correcta en tus componentes.

	Supongamos que tienes un componente que muestra una imagen y deseas asegurarte de que la prop que representa la imagen sea válida y cumpla con ciertos criterios.


	```jsx

	import React from 'react';
	import PropTypes from 'prop-types';

	function Imagen(props) {
	  return (
	    <div>
	      <img src={props.src} alt={props.alt} />
	    </div>
	  );
	}

	Imagen.propTypes = {
	  src: PropTypes.string.isRequired, // Se espera una URL de imagen como cadena y es requerida.
	  alt: PropTypes.string.isRequired, // Se espera un texto alternativo como cadena y es requerido.
	};

	export default Imagen;

	```

	hemos creado un componente llamado Imagen que toma dos props: 'src' y 'alt'. Luego, utilizamos PropTypes para definir los tipos esperados y requeridos para estas props:

    src: 

    	Se espera que sea una cadena ('string') que represente la URL de la imagen, y se marca como requerida ('isRequired'). 

    	Esto garantiza que siempre se proporcione una URL de imagen válida.


    alt: 

    	Se espera que sea una cadena ('string') que represente el texto alternativo de la imagen, y también se marca como requerida ('isRequired'). 

    	Esto asegura que se incluya un texto alternativo adecuado para la accesibilidad.


	Cuando utilizas este componente en tu aplicación y proporcionas las props 'src' y 'alt', React verificará automáticamente si cumplen con las restricciones especificadas en PropTypes. 

	Si no se proporciona una prop requerida o si el tipo de dato es incorrecto, React mostrará advertencias en la consola del navegador durante el desarrollo



|| Proptypes - Default Values

	Definir valores predeterminados (default values) para las propiedades (props) de tus componentes. 

	Esto te permite especificar un valor que se utilizará si no se proporciona una prop en el componente, lo que es útil para manejar casos en los que una prop es opcional pero debe tener un valor predeterminado en caso de que no se le asigne ninguno.

	
	```jsx

	import React from 'react';
	import PropTypes from 'prop-types';

	function Saludo(props) {
	  return <div>Hola, {props.nombre}!</div>;
	}

	// Definir propTypes para el componente
	Saludo.propTypes = {
	  nombre: PropTypes.string,
	};

	// Definir valores predeterminados para las props
	Saludo.defaultProps = {
	  nombre: 'Invitado', // Valor predeterminado si no se proporciona 'nombre'
	};

	export default Saludo;

	```

	Hemos definido un componente Saludo que toma una prop llamada 'nombre'.

	Luego, utilizamos 'propTypes' para especificar que nombre es de tipo 'string'. 

	Además, utilizamos 'defaultProps' para establecer un valor predeterminado de 'Invitado' para nombre. 

	Esto significa que si no se proporciona una prop nombre al componente 'Saludo', se utilizará 'Invitado' como valor predeterminado.

	Cuando utilizas el componente 'Saludo' en tu aplicación y no le proporcionas una prop 'nombre', se mostrará "Hola, Invitado!" en lugar de dejar nombre como indefinido o nulo.



|| React Router


	Biblioteca de enrutamiento diseñada específicamente para aplicaciones web de una sola página (SPA) creadas con React. 

	Facilita la navegación y la gestión de las rutas de una aplicación React, permitiendo a los desarrolladores crear aplicaciones de una sola página que tengan diferentes vistas y URL sin necesidad de recargar la página.


	Gestión de Rutas: 

		React Router permite definir rutas para diferentes vistas o componentes dentro de tu aplicación. 

		Cada ruta se asocia con una URL específica y un componente React correspondiente. 

		Cuando un usuario navega a una URL en particular, React Router se encarga de mostrar el componente correcto sin necesidad de cargar una nueva página.


    Navegación Declarativa: 

    	En lugar de manejar la navegación mediante la manipulación directa del historial del navegador o la recarga de páginas, React Router utiliza una navegación declarativa. 

    	Definir rutas y componentes es tan sencillo como configurar rutas en una tabla de rutas.


    Navegación Anidada: 

    	Puedes anidar rutas y componentes para construir una jerarquía de navegación en tu aplicación. 

    	Esto permite que las vistas sean compuestas y modulares.


    Manejo de Parámetros y Consultas:

    	React Router permite la captura de parámetros dinámicos en las rutas, lo que facilita la construcción de rutas dinámicas. 

    	También admite la gestión de parámetros de consulta (query parameters) que se pueden utilizar para filtrar y personalizar la visualización de datos.


    Manejo del Historial: 

    	React Router maneja automáticamente el historial del navegador, lo que significa que puedes utilizar los botones "Atrás" y "Adelante" del navegador para navegar entre las vistas de tu aplicación SPA sin problemas.


    Protección de Rutas: 

    	Puedes proteger rutas específicas de tu aplicación para garantizar que solo los usuarios autenticados o con ciertos permisos puedan acceder a ellas.


    1. Instalar dependencia React Router: 

    	```
    	npm install react-router-dom

    	```


    2. Configuración básica: 

    Configurar las rutas en tu aplicación utilizando componentes como BrowserRouter, Route, Link, y Switch proporcionados por React Router.

    ```jsx

    import React from 'react';
	import { BrowserRouter as Router, Route, Switch, Link } from 'react-router-dom';

	function Inicio() {
	  return <h1>Página de Inicio</h1>;
	}

	function AcercaDe() {
	  return <h1>Acerca de Nosotros</h1>;
	}

	function Contacto() {
	  return <h1>Contacto</h1>;
	}

	function App() {
	  return (
	    <Router>
	      <div>
	        <nav>
	          <ul>
	            <li>
	              <Link to="/">Inicio</Link>
	            </li>
	            <li>
	              <Link to="/acerca">Acerca de</Link>
	            </li>
	            <li>
	              <Link to="/contacto">Contacto</Link>
	            </li>
	          </ul>
	        </nav>

	        <Switch>
	          <Route path="/acerca">
	            <AcercaDe />
	          </Route>
	          <Route path="/contacto">
	            <Contacto />
	          </Route>
	          <Route path="/">
	            <Inicio />
	          </Route>
	        </Switch>
	      </div>
	    </Router>
	  );
	}

	export default App;

    ```

    Hemos configurado tres rutas (/, /acerca, /contacto) y asignado componentes a cada una de ellas.

    Cuando los usuarios navegan a una URL específica, React Router se encargará de mostrar el componente correspondiente en función de la ruta actual.



|| React Router - Error And Switch Component

	
	Switch: 

		Se utiliza para agrupar múltiples rutas y garantizar que solo una de ellas se represente a la vez. 

		Cuando un usuario navega a una URL, React Router recorre todas las rutas dentro del componente Switch y muestra la primera coincidencia que encuentre.		
	
	Manejo de errores: 

		Se logra a través del uso de una ruta especial que captura cualquier ruta que no coincida con ninguna de las rutas definidas. 

		Esto se hace utilizando una ruta con un patrón de path="*".	

		La ruta <Route path="*"> se coloca al final del componente Switch y se encarga de capturar cualquier URL que no haya coincidido con ninguna ruta previamente definida. 

		Esto permite mostrar una página de "No Encontrado" o cualquier otra lógica de manejo de errores que desees implementar.


		```jsx

		function App() {
		  return (
		    <Router>
		      <div>
		        <Switch>
		          <Route path="/acerca">
		            <AcercaDe />
		          </Route>
		          <Route path="/contacto">
		            <Contacto />
		          </Route>
		          <Route path="/" exact>
		            <Inicio />
		          </Route>
		          <Route path="*">
		            <NoEncontrado />
		          </Route>
		        </Switch>
		      </div>
		    </Router>
		  );
		}

		export default App;

		```



|| React Router - Links

	
	Los enlaces son componentes que se utilizan para navegar entre diferentes vistas o páginas en una aplicación de una sola página (SPA) sin tener que recargar toda la página. 

	El componente 'Link' que se utiliza para crear enlaces dentro de tu aplicación React. 

	Los enlaces funcionan de manera similar a los elementos <a> en HTML, pero en lugar de cargar una página completamente nueva, React Router cambia dinámicamente la URL y renderiza el componente correspondiente asociado con la nueva URL.


	```jsx

	import React from 'react';
	import { BrowserRouter as Router, Link, Route } from 'react-router-dom';

	function Inicio() {
	  return <h1>Página de Inicio</h1>;
	}

	function AcercaDe() {
	  return <h1>Acerca de Nosotros</h1>;
	}

	function Contacto() {
	  return <h1>Contacto</h1>;
	}

	function App() {
	  return (
	    <Router>
	      <div>
	        <nav>
	          {/* Utilizar el componente Link para crear enlaces */}
	          <ul>
	            <li>
	              <Link to="/">Inicio</Link>
	            </li>
	            <li>
	              <Link to="/acerca">Acerca de</Link>
	            </li>
	            <li>
	              <Link to="/contacto">Contacto</Link>
	            </li>
	          </ul>
	        </nav>

	        {/* Configurar rutas */}
	        <Route path="/" exact component={Inicio} />
	        <Route path="/acerca" component={AcercaDe} />
	        <Route path="/contacto" component={Contacto} />
	      </div>
	    </Router>
	  );
	}

	export default App;

	```	

	Cada enlace (<Link>) está vinculado a una ruta específica definida en las rutas (<Route>) de React Router. 

	Cuando un usuario hace clic en uno de los enlaces, React Router se encargará de actualizar la URL y representar el componente correspondiente asociado con esa URL.

	La propiedad 'to' especifica la URL de destino a la que se debe navegar.




|| React Router - URL Params And Placeholder

	Son técnicas que te permiten capturar valores variables en la URL y utilizarlos en tus componentes. 

	Esto es útil cuando deseas crear rutas dinámicas que respondan a valores específicos en la URL, como identificadores de usuario, nombres de producto u otros datos variables.


	URL Params:  

		Se definen en las rutas utilizando dos puntos : seguidos del nombre del parámetro en la ruta


	```
	import React from 'react';
	import { BrowserRouter as Router, Route } from 'react-router-dom';

	function Usuario(props) {
	  const { match } = props;
	  const { id } = match.params; // Capturar el valor del parámetro 'id' de la URL

	  return <h1>Usuario #{id}</h1>;
	}

	function App() {
	  return (
	    <Router>
	      <div>
	        {/* Definir una ruta con un parámetro de URL */}
	        <Route path="/usuario/:id" component={Usuario} />
	      </div>
	    </Router>
	  );
	}

	export default App;

	```

	Hemos definido una ruta que contiene un parámetro de URL llamado id. 

	Cuando un usuario navega a una URL como /usuario/123, React Router captura el valor 123 y lo pasa al componente Usuario a través de las props. 

	Luego, podemos acceder a ese valor utilizando match.params.id.


	Placeholders: 

		Son parte de la URL que actúan como marcadores de posición para valores variables. 

		Estos marcadores de posición se utilizan en la definición de rutas y pueden capturarse dinámicamente como URL Params.


	```
	import React from 'react';
	import { BrowserRouter as Router, Route } from 'react-router-dom';

	function Producto(props) {
	  const { match } = props;
	  const { nombre } = match.params; // Capturar el valor del marcador de posición ':nombre'

	  return <h1>Producto: {nombre}</h1>;
	}

	function App() {
	  return (
	    <Router>
	      <div>
	        {/* Definir una ruta con un marcador de posición */}
	        <Route path="/producto/:nombre" component={Producto} />
	      </div>
	    </Router>
	  );
	}

	export default App;

	```

	Hemos definido una ruta con un marcador de posición ':nombre'.

	Cuando un usuario navega a una URL como /producto/zapatos, React Router captura el valor zapatos y lo pasa al componente Producto como un URL Param. 

	Luego, podemos acceder a ese valor utilizando 'match.params.nombre'



|| React Optimization Warning

	Advertencia que puede aparecer en la consola del navegador durante el desarrollo de una aplicación React.

	Esta advertencia generalmente se presenta cuando React detecta ciertos patrones de uso que pueden llevar a un rendimiento subóptimo o ineficiente en tu aplicación
	

	Se relaciones con situaciones: 


	1. Actualizaciones innecesarias:

		React detecta que un componente se está volviendo a renderizar incluso cuando no ha habido cambios en sus props o estado.

		Esto puede deberse a una configuración ineficiente o a la utilización incorrecta de ciertas características de React, como el uso inadecuado de 'shouldComponentUpdate' o 'React.memo'.

    2. Creación innecesaria de objetos:

    	React nota que se están creando nuevos objetos en cada renderizado de un componente cuando podrían reutilizarse objetos existentes. 

    	Esto puede ocurrir, por ejemplo, al crear funciones anónimas dentro del renderizado de un componente en lugar de definirlas fuera del componente.


    3. Actualizaciones de estado redundantes: 

    	React detecta actualizaciones de estado innecesarias que no cambian el resultado visual del componente. 

    	Esto puede suceder cuando se llama a 'setState' sin un cambio real en el estado.


    4. Otras situaciones de ineficiencia: 

    	Pueden haber otras situaciones en las que React detecta prácticas que pueden llevar a problemas de rendimiento o uso ineficiente de recursos.


    Abordar las advertencias: 


    1. Analizar la advertencia: 

    	Lee detenidamente la advertencia para comprender la causa del problema. 

    	La advertencia suele proporcionar información sobre qué componente o parte del código está causando el problema.


    2. Revisar el código: 

    	Vuelve a revisar el código relacionado con la advertencia y busca patrones de uso ineficiente o actualizaciones innecesarias.

    
    3. Optimizar el código: 

    	Realiza los cambios necesarios en tu código para abordar la advertencia. 

    	Esto puede incluir ajustar el uso de 'shouldComponentUpdate', 'React.memo', evitar la creación innecesaria de objetos o mejorar la gestión del estado.


    3. Usar herramientas de rendimiento: 

    	Utiliza herramientas de rendimiento como React DevTools o herramientas de perfilado para identificar y resolver problemas de rendimiento en tu aplicación.


    4. Pruebas y benchmarking: 

    	Realiza pruebas y benchmarking para asegurarte de que los cambios que realizas para abordar la advertencia no tengan un impacto negativo en el rendimiento de la aplicación.



|| React.memo

	Es una función de React que se utiliza para memoizar (fijar en la memoria) componentes funcionales. 

	La memoización es una técnica de optimización que ayuda a evitar renderizaciones innecesarias de componentes funcionales. 

	Cuando un componente está memoizado con 'React.memo', React lo volverá a renderizar solo si las props que recibe han cambiado en comparación con su última renderización


	```jsx

	import React from 'react';

	// Componente funcional sin memoización
	function MiComponente(props) {
	  return <div>{props.valor}</div>;
	}

	// Componente funcional memoizado
	const MiComponenteMemoizado = React.memo(MiComponente);

	function App() {
	  const valor = 42;

	  return (
	    <div>
	      <MiComponente valor={valor} />
	      <MiComponenteMemoizado valor={valor} />
	    </div>
	  );
	}

	export default App;

	```

	Tenemos 'MiComponente' y su versión memoizada 'MiComponenteMemoizado'.

	Ambos componentes reciben la misma prop 'valor'. 

	Sin embargo, solo 'MiComponenteMemoizado' está memoizado.

	Cuando 'valor' cambia en el componente 'App', React memoiza 'MiComponenteMemoizado', lo que significa que solo se volverá a renderizar si valor cambia. 

	Por otro lado, 'MiComponente' no está memoizado y se volverá a renderizar cada vez que se invoque 'App', independientemente de si valor cambia o no.


	Es útil cuando tienes componentes que reciben props costosas de calcular o cuando deseas evitar renderizaciones innecesarias en componentes que no dependen de props cambiantes.

	'React.memo' solo compara las props de un componente para determinar si debe memoizarlo o no. 

	Si un componente utiliza el estado interno, 'React.memo' no lo protegerá contra actualizaciones innecesarias. 

	En ese caso, puedes utilizar 'useMemo' o 'useCallback' para optimizar aún más el componente.	




|| useCallback

	Hook de React que se utiliza para memoizar funciones en componentes funcionales. 

	Al igual que React.memo para componentes, useCallback ayuda a optimizar el rendimiento al evitar la creación de nuevas instancias de funciones en cada renderizado del componente. 

	En lugar de crear una nueva función en cada renderizado, useCallback garantiza que la misma función se reutilice a menos que las dependencias especificadas cambien.


	```
	const memoizedCallback = useCallback(
	  () => {
	    // Lógica de la función
	  },
	  [dependencias]
	);

	```

	El primer arguento es la función que debes memoizar. 

	El segundo argumento es un array de dependencias. 

	Si alguna de estas dependencias cambia entre renderizaciones, useCallback generará una nueva versión de la función. 

	Si las dependencias no cambian, se reutiliza la función existente.


	```jsx

	import React, { useState, useCallback } from 'react';

	function Boton({ onClick }) {
	  return <button onClick={onClick}>Haz clic</button>;
	}

	function App() {
	  const [contador, setContador] = useState(0);

	  // Utilizar useCallback para memoizar la función de incremento
	  const incrementar = useCallback(() => {
	    setContador(contador + 1);
	  }, [contador]);

	  return (
	    <div>
	      <p>Contador: {contador}</p>
	      <Boton onClick={incrementar} />
	    </div>
	  );
	}

	export default App;

	```

	Hemos definido un componente 'Boton' que recibe una función 'onClick'.

	Luego, en el componente 'App', hemos utilizado 'useCallback' para memoizar la función 'incrementar' que se pasa como 'onClick' al componente 'Boton'.

	Hemos especificado '[contador]'' como dependencia, lo que significa que incrementar se recreará solo cuando contador cambie.

	La memoización de 'incrementar' garantiza que la misma función se reutilice en cada renderizado de 'App', lo que es beneficioso en términos de rendimiento, especialmente en componentes más grandes o en situaciones en las que se pasan funciones como props a componentes anidados.


	'useCallback' es especialmente útil cuando se utiliza con 'React.memo' para evitar renderizaciones innecesarias de componentes y funciones en una aplicación React.



|| useMemo 

	Hook que se utiliza para memoizar valores computados en componentes funcionales. 

	Este hook permite optimizar el rendimiento al evitar el cálculo repetido de un valor a menos que las dependencias especificadas cambien. 

	En otras palabras, useMemo almacena en caché el resultado de una función y solo lo recalcula cuando es necesario debido a cambios en las dependencias.


	```
	const memoizedValue = useMemo(() => {
	  // Cálculos para obtener el valor
	  return valorCalculado;
	}, [dependencias]);

	```

	El primer argumento de useMemo es una función que realiza cálculos para obtener el valor que deseas memoizar.
    
    El segundo argumento es un array de dependencias. 

    Si alguna de estas dependencias cambia entre renderizaciones, useMemo volverá a calcular el valor. 

    Si las dependencias no cambian, se reutiliza el valor previamente calculado.


    ```jsx

    import React, { useState, useMemo } from 'react';

	function App() {
	  const [numero, setNumero] = useState(5);
	  const [multiplicador, setMultiplicador] = useState(2);

	  // Utilizar useMemo para memoizar el resultado del cálculo
	  const resultado = useMemo(() => {
	    console.log('Calculando...');
	    return numero * multiplicador;
	  }, [numero, multiplicador]);

	  return (
	    <div>
	      <p>Número: {numero}</p>
	      <p>Multiplicador: {multiplicador}</p>
	      <p>Resultado: {resultado}</p>
	      <button onClick={() => setNumero(numero + 1)}>Incrementar Número</button>
	      <button onClick={() => setMultiplicador(multiplicador + 1)}>Incrementar Multiplicador</button>
	    </div>
	  );
	}

	export default App;

    ```

    Hemos definido un componente 'App' que tiene dos estados, 'numero' y 'multiplicador'. 

    Hemos utilizado 'useMemo' para memoizar el resultado del cálculo 'numero * multiplicador'. 

    Hemos especificado '[numero, multiplicador]' como dependencias, lo que significa que resultado se recalcula solo cuando uno de estos dos valores cambia.

	La función proporcionada a 'useMemo' se ejecutará solo cuando numero o multiplicador cambien. 

	Esto evita que se realicen cálculos innecesarios cuando no hay cambios en las dependencias.


	useMemo es especialmente útil cuando necesitas realizar cálculos costosos en componentes funcionales y deseas evitar que estos cálculos se repitan en cada renderizado.

	También es útil para evitar renderizaciones innecesarias en componentes que dependen de valores computados.



|| useCallback - Fetch

	'useCallback' se utiliza para memoizar funciones y en el contexto de una solicitud de red, puedes utilizar useCallback para memoizar una función que realiza la solicitud de red y luego pasar esa función como prop a un componente hijo.	


	```jsx

	import React, { useState, useEffect, useCallback } from 'react';

	function ListaDeUsuarios({ cargarUsuarios }) {
	  const [usuarios, setUsuarios] = useState([]);

	  useEffect(() => {
	    cargarUsuarios()
	      .then((data) => setUsuarios(data))
	      .catch((error) => console.error('Error al cargar usuarios', error));
	  }, [cargarUsuarios]);

	  return (
	    <ul>
	      {usuarios.map((usuario) => (
	        <li key={usuario.id}>{usuario.name}</li>
	      ))}
	    </ul>
	  );
	}

	function App() {
	  const [contador, setContador] = useState(0);

	  // Definir una función que realiza la solicitud de red
	  const cargarUsuarios = useCallback(() => {
	    return fetch('https://jsonplaceholder.typicode.com/users')
	      .then((response) => {
	        if (!response.ok) {
	          throw new Error('Error al cargar usuarios');
	        }
	        return response.json();
	      });
	  }, []);

	  return (
	    <div>
	      <h1>Lista de Usuarios</h1>
	      <ListaDeUsuarios cargarUsuarios={cargarUsuarios} />
	      <p>Contador: {contador}</p>
	      <button onClick={() => setContador(contador + 1)}>Incrementar Contador</button>
	    </div>
	  );
	}

	export default App;

	```

	El componente 'ListaDeUsuarios' muestra una lista de usuarios recuperados de una solicitud de red. 

	Hemos definido una función 'cargarUsuarios' utilizando 'useCallback' para memoizarla. 

	Luego, pasamos esta función como prop al componente 'ListaDeUsuarios'.

	El beneficio de memoizar 'cargarUsuarios' es que no se creará una nueva función en cada renderizado de 'App'. 

	En su lugar, la misma función memoizada se reutiliza, lo que puede mejorar el rendimiento y evitar solicitudes de red innecesarias.

	'useCallback' se utiliza aquí para evitar problemas de rendimiento y asegurarse de que la función 'cargarUsuarios' se mantenga constante a menos que cambien sus dependencias. 

	En este caso, no hemos especificado ninguna dependencia en el segundo argumento de 'useCallback' porque la función no depende de ningún valor del componente. 

	Si tu función depende de ciertas variables, debes incluirlas en el array de dependencias para que useCallback reaccione a los cambios en esas variables.


