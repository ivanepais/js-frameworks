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

		Puedes utilizarlo para declarar y actualizar variables de estado en tus componentes funcionales

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

				Muestra la lista de tareas y contiene elementos de tarea individuales				

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


|| Destruir props


	



