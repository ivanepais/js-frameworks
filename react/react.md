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








