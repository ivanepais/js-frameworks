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






||