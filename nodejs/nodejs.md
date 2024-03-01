||Node.js

	Es un entorno de ejecución de JavaScript del lado del servidor que se construyó sobre el motor V8 de Google Chrome. 

	Fue creado por Ryan Dahl en 2009 y su desarrollo inicial fue patrocinado por Joyent. 

	El objetivo principal de Node.js era permitir la creación de aplicaciones de red escalables, en particular servidores web.


	Origen:

	Node.js se originó como una solución para superar las limitaciones de rendimiento que tenían las aplicaciones basadas en eventos en ese momento. 

	La visión de Dahl era crear un entorno que pudiera manejar miles de conexiones simultáneas con eficiencia, utilizando un modelo de E/S sin bloqueo y basado en eventos.


	Propósito:

	El propósito principal de Node.js era proporcionar a los desarrolladores una forma de construir aplicaciones de red altamente escalables y rápidas, utilizando JavaScript tanto en el lado del cliente como en el servidor. 

	Al permitir el uso del mismo lenguaje de programación en ambos lados, Node.js facilitó el intercambio de código entre el cliente y el servidor, lo que llevó a una mayor eficiencia en el desarrollo.


	Actualidad:

	En la actualidad, Node.js se ha convertido en una de las tecnologías más populares para el desarrollo de aplicaciones web y móviles. 

	Se utiliza ampliamente en la creación de servidores web, API y otras aplicaciones de red. 

	Su ecosistema robusto está respaldado por una gran cantidad de módulos y paquetes disponibles a través de npm (Node Package Manager), lo que facilita el desarrollo rápido y eficiente.



|| Versiones
	

	Node.js 0.1.0 (2009): 

		La primera versión de Node.js se lanzó en 2009, y su desarrollo inicial se basó en el motor V8 de Google Chrome.


	Node.js 0.4.0 (2010): 

		Esta versión incluyó mejoras significativas en el rendimiento y la estabilidad, lo que permitió a Node.js ganar popularidad en la comunidad de desarrolladores.


	Node.js 0.6.0 (2011): 

		Se introdujeron mejoras en la API y se agregaron nuevas características, lo que ayudó a consolidar aún más la posición de Node.js como una plataforma de desarrollo de servidores web sólida.


	Node.js 0.8.0 (2012): 

		Esta versión incorporó mejoras importantes en el rendimiento y la estabilidad, así como la adición de la API de Streams2 y el sistema de gestión de paquetes npm.


	Node.js 0.10.0 (2013): 

		Esta versión introdujo mejoras de rendimiento adicionales y varias correcciones de errores. 

		También se realizaron mejoras en la estabilidad y en la API.


	Node.js 0.12.0 (2015): 

		Se lanzaron mejoras importantes en el rendimiento y la estabilidad, y se introdujeron nuevas funciones, como la compatibilidad con ECMAScript 6.


	Node.js 4.0.0 (2015):

		La versión 4.0.0 marcó la unificación de las bases de código de Node.js y io.js, un fork temporal de Node.js, lo que resultó en la fusión de las dos bases de código y comunidades.


	Node.js 6.0.0 (2016): 

		Se realizaron mejoras significativas en el rendimiento y la estabilidad, y se introdujeron nuevas características y funcionalidades, como la estabilidad de la API y el soporte a largo plazo (LTS).


	Node.js 8.0.0 (2017): 

		Se introdujeron características importantes, como mejoras en el rendimiento y la estabilidad, la adopción de nuevas características de ECMAScript, y la adición de nuevas APIs y funcionalidades.


	Node.js 10.0.0 (2018): 

		Esta versión incluyó mejoras significativas en el rendimiento y la estabilidad, así como la adopción de nuevas características de ECMAScript y la incorporación de la última versión del motor V8 de Google.


	Node.js 12.0.0 (2019): 

		Se lanzaron mejoras importantes en el rendimiento y la estabilidad, así como la adopción de nuevas características de ECMAScript y la adición de nuevas API y funcionalidades.


	Node.js 14.0.0 (2020): 

		Esta versión incorporó mejoras importantes en el rendimiento y la estabilidad, así como la adopción de nuevas características de ECMAScript y la adición de nuevas API y funcionalidades



|| Características: 

	JavaScript en el servidor: 

		Node.js permite a los desarrolladores utilizar JavaScript tanto en el lado del cliente como en el del servidor, lo que simplifica el intercambio de código y datos entre el cliente y el servidor.


	E/S sin bloqueo y basada en eventos:

		Utiliza un modelo de E/S sin bloqueo y basado en eventos, lo que permite a Node.js manejar un gran número de conexiones simultáneas sin agotar los recursos del sistema.


	Velocidad y rendimiento: 

		Gracias al motor V8 de Google Chrome, Node.js proporciona un rendimiento rápido y eficiente, lo que lo hace ideal para aplicaciones de tiempo real y de alta carga de trabajo.


	Amplio ecosistema: 

		Node.js cuenta con un amplio ecosistema de paquetes y módulos disponibles a través de npm (Node Package Manager), que facilita la integración de funcionalidades adicionales en las aplicaciones y acelera el proceso de desarrollo.


	Escalabilidad: 

		La capacidad de manejar una gran cantidad de solicitudes simultáneas lo convierte en una opción ideal para aplicaciones escalables que requieren un alto rendimiento y una rápida respuesta.	


	Soporte multiplataforma: 

		Node.js es compatible con varias plataformas, lo que facilita su implementación en diversos entornos, como Windows, macOS y varias distribuciones de Linux.




|| Instalar y ejecutar 

	Desde su sitio oficial o Utilizando el gestor de paquetes.


	En el emulador de terminal Debian/Ubuntu: 

		```
		sudo apt-get install nodejs
		sudo apt-get install npm.
		
		```


    Verificación: 

    	Después de la instalación, verifica la versión de Node.js y npm escribiendo 

    	```
    	node -v 

    	npm -v 

    	```


    Crear y ejecutar apps: 

    	```
    	node nombre_del_archivo.js

    	```



|| Conceptos básicos de Node.js


	    Motor V8: Node.js se basa en el motor V8 de Google, que es el motor de ejecución de JavaScript de código abierto utilizado en Google Chrome y en varios otros proyectos. Este motor permite que Node.js ejecute JavaScript de manera eficiente y rápida.

    E/S sin bloqueo y basada en eventos:

    	Node.js utiliza un modelo de E/S sin bloqueo y basado en eventos, lo que significa que las operaciones de entrada y salida no bloquean el flujo de ejecución. 

    	En lugar de esperar a que se complete una operación de E/S, Node.js continuará ejecutando el código, lo que resulta en un rendimiento mejorado y una mayor capacidad de gestión de múltiples conexiones.


    npm (Node Package Manager): 

    	npm es el administrador de paquetes predeterminado para Node.js. 

    	Permite a los desarrolladores acceder a un vasto repositorio de paquetes de código abierto que pueden ser utilizados en sus propios proyectos. 

    	Los desarrolladores pueden usar npm para instalar paquetes y dependencias, así como para compartir sus propios paquetes con la comunidad.


    Módulos: 

    	Node.js utiliza un sistema de módulos para organizar y reutilizar el código. 

    	Los módulos permiten a los desarrolladores dividir su código en partes más pequeñas y manejables, lo que facilita el mantenimiento y la reutilización del código en diferentes partes de una aplicación.


    Servidor web: 

    	Node.js se usa comúnmente para crear servidores web altamente escalables y de alto rendimiento. 

    	Gracias a su capacidad para manejar múltiples conexiones simultáneas de manera eficiente, Node.js es una opción popular para aplicaciones en tiempo real y de alto tráfico.


    Eventos y emisores de eventos: 

    	La API de eventos de Node.js permite a los desarrolladores vincular funciones a eventos específicos y luego activar esos eventos cuando sea necesario.

    	Los emisores de eventos en Node.js son objetos que emiten eventos nombrados que los oyentes pueden suscribir y manejar.



|| Express.js

	Express.js es un popular marco de aplicación web para Node.js que se lanzó en 2010. 

	Fue creado por TJ Holowaychuk y originalmente se inspiró en el marco web Sinatra de Ruby. 

	Express.js se desarrolló para simplificar el proceso de desarrollo de aplicaciones web en Node.js al proporcionar un conjunto robusto de características y funcionalidades.


	Propósito:

	El propósito principal de Express.js es proporcionar a los desarrolladores de Node.js un marco minimalista y flexible que les permita crear aplicaciones web y API de manera rápida y sencilla.

	Express.js simplifica tareas comunes de desarrollo web, como el enrutamiento, la gestión de solicitudes y respuestas, y la integración de middleware, lo que permite a los desarrolladores enfocarse en la lógica comercial de sus aplicaciones en lugar de tener que preocuparse por la infraestructura subyacente.



|| Versiones

	
	Express.js 1.0.0 (2010): 

		Se lanzó la primera versión de Express.js, proporcionando a los desarrolladores un marco ligero y minimalista para la creación de aplicaciones web en Node.js.


	Express.js 2.0.0 (2011): 

		Esta versión introdujo mejoras significativas en la API y la funcionalidad de Express.js, lo que ayudó a consolidar su posición como uno de los marcos web más populares para Node.js.


	Express.js 3.0.0 (2012): 

		Se introdujeron cambios importantes en la arquitectura y la API de Express.js, lo que mejoró la modularidad y la flexibilidad del marco.


	Express.js 4.0.0 (2014): 

		La versión 4.0.0 de Express.js trajo consigo una serie de mejoras importantes en la API, la funcionalidad y el rendimiento. 

		También se hicieron actualizaciones para mejorar la seguridad y la estabilidad del marco.


	Express.js 5.0.0 (2020): 

		Esta versión, que tardó varios años en desarrollarse, trajo consigo cambios significativos en la arquitectura subyacente de Express.js. 

		Se mejoró la compatibilidad con ES6 y se adoptaron características más modernas de JavaScript	



|| Características

	Enrutamiento: 

		Express.js facilita la definición de rutas para diferentes puntos finales de la aplicación web, lo que permite a los desarrolladores responder a solicitudes HTTP específicas de manera clara y organizada.


	Manejo de solicitudes y respuestas:

		Express.js simplifica el manejo de solicitudes y respuestas HTTP, lo que permite a los desarrolladores crear lógica de negocio personalizada y devolver respuestas de manera coherente y predecible.


	Middlewares: 

		Express.js permite el uso de middlewares, que son funciones que tienen acceso a los objetos de solicitud (request) y respuesta (response) y pueden realizar modificaciones en ellos. 

		Esto facilita tareas comunes como el registro, la autenticación, la compresión y el manejo de errores.


	Integración sencilla de complementos: 

		Express.js permite la integración sencilla de una variedad de complementos y módulos de terceros, lo que amplía sus capacidades y funcionalidades y facilita el desarrollo de aplicaciones web más complejas.


	Templates: 

		Aunque Express.js en sí mismo no incluye un sistema de plantillas, es compatible con una amplia variedad de motores de plantillas, lo que permite a los desarrolladores elegir la solución que mejor se adapte a sus necesidades y preferencias.


	Manejo de errores: 

		Express.js facilita el manejo de errores mediante la implementación de middleware de manejo de errores que puede capturar y manejar errores de manera uniforme en toda la aplicación.


	Flexibilidad: 

		Express.js es conocido por su flexibilidad, lo que permite a los desarrolladores personalizar y adaptar el marco según las necesidades específicas de sus proyectos, en lugar de imponer una estructura rígida.



|| Instalación y ejecución

	En la terminal: 

	```	
	npm install express

	```	


	Instalar versión especifica: 

	```	
	npm install express@<version>

	```


|| Conceptos básicos de Express.js

	Middleware: 

		Express.js utiliza el concepto de middleware, que son funciones que tienen acceso a los objetos de solicitud (request) y respuesta (response) y pueden realizar tareas específicas en el proceso de solicitud y respuesta. 

		El middleware en Express.js puede realizar tareas como el registro, la autenticación, la compresión, el manejo de errores, etc.


	Enrutamiento: 

		Express.js proporciona un enrutador que permite a los desarrolladores definir rutas para diferentes puntos finales de la aplicación. 

		Esto permite a la aplicación responder a diferentes solicitudes HTTP de manera específica y estructurada.


	Manejadores de rutas: 

		Los manejadores de rutas en Express.js son funciones que se ejecutan cuando se alcanza una ruta específica. 

		Estas funciones pueden realizar acciones específicas, como devolver datos al cliente, realizar operaciones en la base de datos y renderizar plantillas, entre otras cosas.


	Solicitud y respuesta: 

		En el contexto de Express.js, la solicitud (request) representa la solicitud HTTP realizada por el cliente, y la respuesta (response) representa la respuesta que se enviará al cliente como resultado de la solicitud. 

		Los desarrolladores pueden manipular estos objetos para manejar las solicitudes y las respuestas de manera adecuada.


	Plantillas: 

		Aunque Express.js en sí mismo no incluye un sistema de plantillas, es compatible con varios motores de plantillas como Pug, EJS, Handlebars, entre otros. 

		Estos motores de plantillas permiten a los desarrolladores generar vistas dinámicas en función de los datos y enviar estas vistas como respuestas a las solicitudes de los clientes.


	API de aplicación: 

		Express.js proporciona una API simple pero potente que permite la creación y configuración de aplicaciones web. 

		Esta API incluye métodos y funciones para configurar middleware, definir rutas, manejar errores y administrar la aplicación en general.



|| Módulos principales de Node.js


	HTTP: 

		Proporciona un conjunto de clases y métodos que permiten la creación y gestión de servidores web.


	FS (File System): 

		Permite trabajar con el sistema de archivos del sistema operativo, lo que incluye la lectura, escritura, actualización y eliminación de archivos y directorios.


	Path: 

		Proporciona utilidades para trabajar con rutas de archivos y directorios.


	Events: 

		Proporciona un mecanismo para la emisión y escucha de eventos en Node.js, lo que permite la comunicación entre objetos de manera asíncrona.


	OS (Operating System): 

		Proporciona métodos para interactuar con el sistema operativo, lo que incluye la obtención de información sobre la CPU, la memoria y la red del sistema.


	Util: 

		Proporciona una serie de funciones de utilidad útiles que pueden ser utilizadas en diversas tareas de programación.


	Stream: 

		Proporciona la capacidad de trabajar con flujos de datos, lo que permite la lectura y escritura de datos de manera eficiente, especialmente para operaciones que involucran grandes conjuntos de datos.


	Crypto: 

		Proporciona funcionalidades de criptografía, como el cifrado y el descifrado de datos, la generación de resúmenes y la firma de datos.


	Además de estos módulos principales, Node.js cuenta con una gran cantidad de módulos de terceros disponibles a través de npm (Node Package Manager), que amplían aún más las capacidades y funcionalidades de la plataforma.



|| Funciones incorporadas

    console: 

    	Ofrece métodos para imprimir en la consola, como 'console.log()', 'console.error()' y 'console.warn()', que son útiles para la depuración y el registro de información durante el desarrollo.


    setTimeout y setInterval: 

    	Permiten a los desarrolladores programar la ejecución de una función después de un cierto tiempo ('setTimeout') o a intervalos regulares ('setInterval').


    require: 

    	Permite a los desarrolladores cargar módulos y archivos en una aplicación de Node.js. 

    	Es fundamental para la estructura de módulos de Node.js y para reutilizar código en diferentes partes de una aplicación.


    process: 

    	Proporciona información y control sobre el proceso de Node.js en ejecución, como argumentos de línea de comandos, variables de entorno y eventos 
    	del proceso.


    Buffer: 

    	Proporciona una clase para trabajar con datos binarios en Node.js, lo que incluye la manipulación de secuencias de bytes, la conversión de datos en diferentes formatos y la interacción con flujos de datos.


    Global Objects: 

    	Incluye objetos globales como 'global' (que representa el contexto global en Node.js), 'module' (que representa el módulo actual) y 'exports' (que se utiliza para exportar contenido de un módulo en Node.js).



|| Sintaxis básica para Node.js

		
	Servidor: 

	```js

	const http = require('http');
	const server = http.createServer((request, response) => {
	    response.statusCode = 200;
	    response.setHeader('Content-Type', 'text/plain');
	    response.end('Hola, mundo!');
	});
	server.listen(3000, '127.0.0.1', () => {
	    console.log('Servidor en funcionamiento en http://127.0.0.1:3000/');
	});


	```

	Importar y usar módulos: 

	```
	const modulo = require('nombre-del-modulo');
	modulo.metodo();

	```
	


|| Proyecto básico en Node.js

	Utiliza un servidor HTTP simple para responder a las solicitudes con un mensaje de "Hola, mundo".


	Crear capeta y movernos al directorio:

	```
	mkdir proyecto-nodejs
	cd proyecto-nodejs

	```


	Iniciar proyecto e instalar módulo HTTP:

	```
	npm init -y
	npm install http
	
	```


	Index.js:

	```js
	
	const http = require('http');

	const hostname = '127.0.0.1';
	const port = 3000;

	const server = http.createServer((req, res) => {
	    res.statusCode = 200;
	    res.setHeader('Content-Type', 'text/plain');
	    res.end('Hola, mundo!\n');
	});

	server.listen(port, hostname, () => {
	    console.log(`Servidor corriendo en http://${hostname}:${port}/`);
	});

	
	```


	Ejecutar js:

	```
	node index.js

	```

	Accede a la aplicación en tu navegador web visitando la dirección http://127.0.0.1:3000/. 

	Mostrará el mensaje "Hola, mundo!" en la página.



|| Buenas prácticas para Node.js


    Manejo de errores y excepciones:

    	Implementa un manejo adecuado de errores y excepciones en tu código para mejorar la robustez y la confiabilidad de tu aplicación.


    Evita devoluciones de llamada anidadas (Callback hell): 

    	Utiliza técnicas como las promesas o async/await para evitar la anidación excesiva de devoluciones de llamada, lo que puede dificultar la legibilidad y el mantenimiento del código.


    Divide tu código en módulos reutilizables: 

    	Separa tu código en módulos más pequeños y reutilizables para mejorar la legibilidad y facilitar el mantenimiento y la escalabilidad de tu aplicación.


    Utiliza herramientas de prueba unitaria: 

		Implementa pruebas unitarias para verificar el funcionamiento correcto de tu código y asegurarte de que los cambios posteriores no introduzcan regresiones.


    Gestión de dependencias: 

    	Utiliza npm o yarn para gestionar las dependencias de tu proyecto de forma efectiva y garantizar que todas las dependencias estén actualizadas y sean seguras.


    Usa middleware de forma eficiente en Express.js: 

    	Utiliza middleware de manera eficiente para la manipulación de solicitudes y respuestas en Express.js y asegúrate de mantener un flujo lógico en tu aplicación.


    Optimización y rendimiento: 

    	Presta atención al rendimiento de tu código y utiliza técnicas de optimización, como el almacenamiento en caché y la programación asíncrona, para mejorar la velocidad y la eficiencia de tu aplicación.


    Seguridad: 

    	Ten en cuenta las prácticas de seguridad recomendadas para proteger tu aplicación contra vulnerabilidades y ataques, como la validación de datos de entrada y el manejo seguro de contraseñas y credenciales



|| Módulos incorporados de Express.js


    express: 

    	El módulo principal de Express.js que se utiliza para crear una instancia de una aplicación de Express.


    express.Router: 

    	Un módulo que se utiliza para crear instancias de enrutadores independientes para manejar rutas específicas de manera modular.


    middlewares:

    	Express.js permite el uso de una variedad de middlewares de terceros y personalizados para realizar tareas como el registro, la autenticación, la compresión y el manejo de errores.


    express.static: 

    	Un módulo que se utiliza para servir archivos estáticos, como archivos HTML, imágenes, archivos CSS y archivos JavaScript, directamente desde un directorio específico.


    Express-session: 

    	Un módulo que permite la gestión de sesiones de usuario en aplicaciones web Express.js.


    Body-parser: 

    	Un módulo que analiza el cuerpo de las solicitudes entrantes en formato JSON, urlencoded y multipart.


    Helmet: 

    	Un módulo de seguridad que ayuda a proteger las aplicaciones Express.js configurando varios encabezados HTTP relacionados con la seguridad.


    Morgan: 

    	Un módulo de registro de solicitudes HTTP para Express.js que registra automáticamente las solicitudes entrantes en la consola del servidor.



|| Funciones incorporadas de Express.js

	express(): 

		Una función de fábrica que se utiliza para crear una nueva instancia de la aplicación Express.


    app.METHOD(): 

    	Métodos de enrutamiento, como app.get(), app.post(), app.put(), app.delete(), que se utilizan para manejar solicitudes HTTP específicas en rutas específicas.


    app.use(): 

    	Se utiliza para montar middleware en la aplicación y se ejecuta en cada solicitud entrante.


    app.set(): 

    	Se utiliza para configurar variables de aplicación que afectan el comportamiento de la aplicación.


    app.listen(): 

    	Se utiliza para iniciar un servidor Express en un puerto específico y una dirección IP específica.


    app.engine(): 

    	Se utiliza para registrar un motor de plantillas en Express.js para renderizar vistas con un motor de plantillas específico.


    app.all(): S

    	e utiliza para manejar todas las solicitudes de un método HTTP específico en una ruta específica.



|| Sintaxis básica para Express.js


	1. Importar módulo Express.js:

	```
	const express = require('express');

	```


	2. Crear una instación de la aplicación Express: 

	```
	const app = express();

	```


	3. Definir una ruta básica: 

	```js

	app.get('/', (req, res) => {
    	res.send('¡Hola, mundo!');
	});

	```


	4. Iniciar el servidor Express: 

	```js

	const PORT = 3000;
	app.listen(PORT, () => {
	    console.log(`Servidor en funcionamiento en el puerto ${PORT}`);
	});

	```


	5. Rutas y parámetros: 

	```js

	app.get('/usuarios/:id', (req, res) => {
    	const userId = req.params.id;
    	// Lógica para obtener y devolver información del usuario
    	res.send(`Solicitando información del usuario con ID: ${userId}`);
	});

	```


	6. Uso de middlewre: 

	```js

	app.use(express.json()); // Middleware para análisis de JSON
	app.use(express.urlencoded({ extended: true })); // Middleware para análisis de URL codificada

	```


	7. Manejo de errores: 	

	```
	app.use((err, req, res, next) => {
	    console.error(err.stack);
	    res.status(500).send('Algo salió mal!');
	});

	```


|| Proyecto básico en Express.js


	1. Carpeta del proyecto: 

	```
	mkdir proyecto-express
	cd proyecto-express

	```


	2. Inicializar un proyecto de Node.js e instalar Express.js:

	```
	npm init -y
	npm install express

	```


	3. Modificar archivo 'index.js':

	```js

	const express = require('express');
	const app = express();
	const port = 3000;

	app.get('/', (req, res) => {
	    res.send('¡Hola, bienvenido a mi aplicación Express!');
	});

	app.listen(port, () => {
	    console.log(`La aplicación está corriendo en http://localhost:${port}`);
	});

	```


	4. Ejecutar server: 

	```
	node index.js

	```

	Accede a la aplicación en tu navegador web visitando la dirección http://localhost:3000/. 

	Verás el mensaje "¡Hola, bienvenido a mi aplicación Express!" en la página.



|| Buenas prácticas en Express.js


	Estructurar tu aplicación: 

		Organiza tu código en una estructura de carpetas y archivos clara y coherente para facilitar el mantenimiento y la escalabilidad de la aplicación.


	Usar middleware de manera eficiente: 

		Utiliza middleware de forma selectiva y ordenada para manejar la lógica común, como la autenticación, el registro, la compresión y la gestión de errores.


	Validar y sanitizar los datos de entrada: 

		Asegúrate de validar y sanitizar todos los datos de entrada, como parámetros de URL, cuerpos de solicitudes y datos de formularios, para evitar vulnerabilidades de seguridad y errores en la aplicación.


	Manejar errores de manera efectiva:

		Implementa un manejo robusto de errores utilizando middleware de manejo de errores y asegurándote de que todas las rutas críticas estén protegidas contra errores inesperados.


	Utilizar controladores y enrutadores: 

		Separa la lógica de manejo de solicitudes en controladores y utiliza enrutadores para definir rutas y organizar el código de manejo de rutas de manera clara y estructurada.


	Optimizar el rendimiento: 

		Implementa técnicas de optimización, como el almacenamiento en caché, la compresión de respuestas y el uso eficiente de consultas de bases de datos, para mejorar el rendimiento y la eficiencia de tu aplicación.


	Implementar pruebas unitarias y de integración: 

		Escribe pruebas unitarias y de integración para verificar el comportamiento y la funcionalidad de tu aplicación y garantizar que funcione como se espera en diferentes escenarios.


	Mantener la seguridad: 

		Implementa medidas de seguridad, como la protección contra ataques de inyección y la protección de datos sensibles, y asegúrate de mantener todos los paquetes y dependencias actualizados para evitar vulnerabilidades conocidas.



|| REPL

	
	Read-Eval-Print Loop (REPL) es un entorno de programación interactivo que te permite ingresar comandos de JavaScript y ver los resultados de inmediato. 

	Es una herramienta útil para probar rápidamente código, experimentar con funciones y probar ideas en tiempo real. 


	Funciones: 

		Read (Leer): 

			Lee la entrada del usuario, ya sea una expresión, declaración o función de JavaScript.


		Eval (Evaluar): 

			Evalúa la entrada del usuario y ejecuta el código de JavaScript proporcionado.


		Print (Imprimir): Imprime el resultado de la evaluación en la consola.


		Loop (Bucle): 

			Repite el proceso, permitiendo al usuario ingresar más comandos y recibir resultados en tiempo real.


	Ejecutar REPL: 



|| CLI Node.js

	node : 

		Para ejecutar archivos de script de Node.js.

    npm : 

    	Para instalar paquetes y administrar dependencias en proyectos de Node.js.

    npx : 

    	Para ejecutar paquetes de Node.js directamente desde el registro npm.

    node -v : 

    	Para verificar la versión actual de Node.js instalada en tu sistema.

    npm init : 

    	Para inicializar un nuevo proyecto de Node.js y crear un archivo package.json.

    npm install <nombre_del_paquete> : 	

    	Para instalar un paquete específico de npm en tu proyecto.

    npm run <nombre_del_script> : 

    	Para ejecutar scripts personalizados definidos en el archivo package.json.



|| Globals

	Objetos o funciones que están disponibles globalmente en todos los módulos de Node.js. 

	A diferencia del navegador, donde el objeto global es window, en Node.js, el objeto global se conoce como global. 

	Los objetos y funciones globales en Node.js proporcionan funcionalidades útiles que pueden ser utilizadas en cualquier parte de una aplicación Node.js sin necesidad de importar o requerir módulos adicionales


	global: 

		El objeto global en Node.js que contiene todas las variables y funciones globales.

	__dirname: 

		Una cadena que representa el directorio en el que se encuentra el script actual.

	__filename: 

		Una cadena que representa la ruta completa del archivo actual.

	setTimeout y clearTimeout: 

		Funciones para ejecutar un bloque de código después de un cierto período de tiempo o para detener la ejecución de un temporizador.

	setInterval y clearInterval:

		Funciones para ejecutar un bloque de código de forma repetida a intervalos específicos o para detener la ejecución de un intervalo.

	console: 

		Un objeto que proporciona métodos para imprimir mensajes en la consola, como console.log, console.error y console.warn


	EJemplo: 

	```
	// Ejemplo de uso de objetos y funciones globales en Node.js

	// Imprimir el directorio actual
	console.log("__dirname:", __dirname);

	// Imprimir la ruta del archivo actual
	console.log("__filename:", __filename);

	// Ejecutar una función después de un cierto tiempo
	setTimeout(() => {
	    console.log("¡Esto se ejecuta después de 2 segundos!");
	}, 2000);

	// Ejecutar una función repetidamente a intervalos regulares
	let contador = 0;
	const intervalo = setInterval(() => {
	    contador++;
	    console.log("Contador:", contador);
	    if (contador === 5) {
	        clearInterval(intervalo);
	        console.log("Intervalo detenido.");
	    }
	}, 1000);

	```	

	Ejecutar este script de Node.js desde la terminal con el comando node nombre_del_archivo.js. 

	Verás cómo el script imprime el directorio actual, la ruta del archivo actual y luego ejecuta una función después de un cierto tiempo y repite otra función a intervalos regulares.



|| Módulos

	Unidades independientes de funcionalidad que se pueden reutilizar en una aplicación. 

	Los módulos en Node.js ayudan a organizar y estructurar el código, lo que facilita el mantenimiento y la reutilización.

	Cada archivo en Node.js se considera un módulo y puede exportar ciertas partes de su código para que otros módulos lo utilicen.	


	require: 
	
	    Una función global en Node.js que se utiliza para importar módulos y archivos en otros archivos de Node.js.


    module.exports: 

    	Un objeto especial que se utiliza para exportar funciones, variables y objetos desde un módulo de Node.js para que estén disponibles para otros módulos.


    exports: 

    	Una abreviatura de module.exports que se puede utilizar para exportar elementos desde un módulo de Node.js.


    Módulos integrados:

    	Módulos predefinidos en Node.js que se pueden utilizar directamente en cualquier aplicación Node.js sin necesidad de instalar nada adicional.


    Módulos de terceros: 

    	Módulos que no forman parte de Node.js en sí, pero que se pueden instalar utilizando npm y que proporcionan funcionalidades adicionales para las aplicaciones Node.js.


    Módulos personalizados: 

    	Módulos creados por los propios desarrolladores para encapsular lógica de negocio específica y funcionalidades reutilizables en sus aplicaciones.



    Ejemplo: 

    	1. Módulo a exportar: 

    	```
    	// saludos.js
		const saludar = nombre => {
		    console.log(`¡Hola, ${nombre}!`);
		};

		module.exports = saludar;

    	```


    	2. Módulo a importar:

    	```
    	// app.js
		const saludar = require('./saludos');

		saludar('Juan');
		saludar('María');
	
    	```

    	3. Ejecutar app: 

    	```
    	node app.js

    	```



|| Alternative Sintax

	Enfoque alternativo que los desarrolladores pueden adoptar para escribir código de manera más concisa y expresiva.


	Funciones de flecha (Arrow Functions): 

		Una forma más concisa de escribir funciones anónimas en JavaScript que evita la necesidad de la palabra clave function y utiliza una sintaxis de flecha (=>) para definir funciones.


	Template Literals: 

		Una sintaxis que permite la interpolación de variables y expresiones en cadenas de texto utilizando la sintaxis ${}.

		Esto facilita la concatenación de cadenas de texto largas y la mejora de la legibilidad del código.


	Destructuring Assignment: 

		Una sintaxis que permite extraer valores de objetos y matrices y asignarlos a variables individuales de forma más concisa. 

		Esto facilita la manipulación de datos y la asignación de valores en el código.


	Promesas (Promises) y Async/Await:

		Una forma de manejar la asincronía en Node.js de una manera más legible y manejable en comparación con las devoluciones de llamada anidadas. 

		Las promesas y el uso de la palabra clave async con await permiten un código más limpio y una mejor gestión de errores en operaciones asíncronas


	Ejemplo: 

	```js

	// Ejemplo de uso de Alternative Syntax en Node.js

	// Funciones de flecha (Arrow Functions)
	const sumar = (a, b) => a + b;
	console.log("La suma de 4 y 6 es:", sumar(4, 6));

	// Template Literals
	const nombre = "Ana";
	const edad = 30;
	console.log(`Mi nombre es ${nombre} y tengo ${edad} años.`);

	// Destructuring Assignment
	const persona = { nombre: 'Juan', edad: 25, ciudad: 'Madrid' };
	const { nombre: nombrePersona, edad: edadPersona } = persona;
	console.log(`La persona se llama ${nombrePersona} y tiene ${edadPersona} años.`);

	// Promesas (Promises) y Async/Await
	const esperar = (ms) => {
	  return new Promise(resolve => {
	    setTimeout(resolve, ms);
	  });
	};

	const hacerAlgo = async () => {
	  console.log('Haciendo algo...');
	  await esperar(2000);
	  console.log('Terminado.');
	};

	hacerAlgo();

	```


|| Built-in Modules

	Vienen incorporados de forma predeterminada con la instalación de Node.js. 

	Estos módulos proporcionan una variedad de funcionalidades listas para usar que abarcan desde operaciones básicas de entrada/salida hasta capacidades avanzadas de red y criptografía.


	http: 

		Un módulo que proporciona funcionalidades para crear aplicaciones del lado del servidor y cliente HTTP.


	fs (File System): 

		Un módulo que proporciona funcionalidades para trabajar con el sistema de archivos, permitiendo la lectura y escritura de archivos.


	path: 

		Un módulo que proporciona utilidades para trabajar con rutas de archivos y directorios.


	util: 

		Un módulo que proporciona funciones de utilidad para ayudar con la depuración y la visualización de datos.


	crypto: 

		Un módulo que proporciona funcionalidades criptográficas, como la generación de hashes y la encriptación de datos



|| OS Module

	Proporciona una serie de métodos y propiedades para interactuar con el sistema operativo en el que se está ejecutando Node.js. 

	Este módulo proporciona información útil sobre el sistema operativo subyacente, como la arquitectura de la CPU, la memoria, la información de red y más


	os.arch(): 

		Devuelve la arquitectura de la CPU del sistema.

	os.platform(): 

		Devuelve el sistema operativo de la plataforma.

	os.cpus(): 

		Devuelve un array de objetos que describen cada núcleo lógico de la CPU.

	os.totalmem(): 

		Devuelve la cantidad total de memoria del sistema en bytes.

	os.freemem(): 

		Devuelve la cantidad de memoria libre del sistema en bytes.

	os.hostname(): 

		Devuelve el nombre de host de la máquina.

	os.networkInterfaces(): 

		Devuelve un objeto que contiene información de red, como direcciones IP y interfaces de red

	Ejemplo:

	```js

	const os = require('os');

	// Mostrar la arquitectura de la CPU del sistema
	console.log('Arquitectura de la CPU:', os.arch());

	// Mostrar el sistema operativo de la plataforma
	console.log('Plataforma del Sistema Operativo:', os.platform());

	// Mostrar información de la CPU
	console.log('Información de la CPU:', os.cpus());

	// Mostrar la cantidad total de memoria del sistema
	console.log('Memoria total del sistema:', os.totalmem(), 'bytes');

	// Mostrar la cantidad de memoria libre del sistema
	console.log('Memoria libre del sistema:', os.freemem(), 'bytes');

	// Mostrar el nombre del host de la máquina
	console.log('Nombre del host de la máquina:', os.hostname());

	// Mostrar información de red
	console.log('Información de red:', os.networkInterfaces());

	```

	Al ejecutar este script de Node.js, verás la información relacionada con el sistema operativo, como la arquitectura de la CPU, la cantidad total y libre de memoria del sistema, el nombre del host de la máquina y la información de red.



|| Path Module
	
	Este módulo es útil para manipular y construir rutas de archivos de manera segura y coherente en diferentes entornos y sistemas operativos.


	path.join(): 

		Une segmentos de ruta en una sola ruta.
    
    path.resolve(): 

    	Resuelve una secuencia de segmentos de ruta en una ruta absoluta.
    
    path.basename(): 

    	Devuelve el último componente de una ruta.
    
    path.dirname(): 

    	Devuelve el directorio de una ruta.
    
    path.extname(): 

    	Devuelve la extensión de archivo de una ruta.
    
    path.parse(): 

    	Devuelve un objeto que representa la ruta proporcionada.
    
    path.normalize(): 

    	Normaliza una ruta, resolviendo ".." y "." segmentos.


    Ejemplo: 

    ```js

    const path = require('path');

	// Unir segmentos de ruta en una sola ruta
	const rutaUnida = path.join('/directorio', 'subdirectorio', 'archivo.txt');
	console.log('Ruta unida:', rutaUnida);

	// Resolver una secuencia de segmentos de ruta en una ruta absoluta
	const rutaResuelta = path.resolve('archivo.txt');
	console.log('Ruta resuelta:', rutaResuelta);

	// Obtener el último componente de una ruta
	const nombreArchivo = path.basename('/directorio/subdirectorio/archivo.txt');
	console.log('Nombre del archivo:', nombreArchivo);

	// Obtener el directorio de una ruta
	const directorio = path.dirname('/directorio/subdirectorio/archivo.txt');
	console.log('Directorio:', directorio);

	// Obtener la extensión de archivo de una ruta
	const extensionArchivo = path.extname('/directorio/subdirectorio/archivo.txt');
	console.log('Extensión del archivo:', extensionArchivo);

	// Parsear una ruta en sus componentes
	const infoRuta = path.parse('/directorio/subdirectorio/archivo.txt');
	console.log('Información de la ruta:', infoRuta);

	// Normalizar una ruta
	const rutaNormalizada = path.normalize('/directorio//subdirectorio/otro/../archivo.txt');
	console.log('Ruta normalizada:', rutaNormalizada);

    ```



|| Fs Module (Sync)


	El módulo fs (Sistema de Archivos) proporciona un conjunto de funciones para trabajar con archivos de manera síncrona y asíncrona. 

	El módulo fs síncrono, a diferencia de su contraparte asíncrona, bloquea la ejecución del programa hasta que la operación de archivo se complete, lo que significa que el código se ejecuta secuencialmente.


	fs.readFileSync(): 

		Lee un archivo de forma síncrona y devuelve su contenido.

    fs.writeFileSync(): 

    	Escribe datos en un archivo de forma síncrona.

    fs.existsSync(): 

    	Verifica si un archivo o directorio existe de forma síncrona.

    fs.readdirSync(): 

    	Lee los contenidos de un directorio de forma síncrona.

    fs.statSync(): 

    	Obtiene información del estado de un archivo de forma síncrona.

	
    Las operaciones síncronas pueden ser útiles en ciertos contextos, es importante tener en cuenta que pueden bloquear la ejecución del programa, lo que puede resultar en una mala experiencia de usuario en aplicaciones que requieren un alto rendimiento y capacidad de respuesta. 

    En general, se prefiere el uso de operaciones de archivos asíncronas en Node.js para mantener la capacidad de respuesta de la aplicación


    Ejemplo: 

    ```
    const fs = require('fs');

	// Leer un archivo de forma síncrona
	try {
	    const data = fs.readFileSync('archivo.txt', 'utf8');
	    console.log('Contenido del archivo:', data);
	} catch (err) {
	    console.error('Error al leer el archivo:', err);
	}

	// Escribir en un archivo de forma síncrona
	try {
	    fs.writeFileSync('nuevoArchivo.txt', 'Contenido de prueba');
	    console.log('Archivo escrito de forma síncrona.');
	} catch (err) {
	    console.error('Error al escribir en el archivo:', err);
	}

	// Verificar si un archivo o directorio existe de forma síncrona
	const existeArchivo = fs.existsSync('archivo.txt');
	console.log('¿El archivo existe?', existeArchivo);

	// Leer los contenidos de un directorio de forma síncrona
	try {
	    const archivos = fs.readdirSync('./');
	    console.log('Archivos en el directorio:', archivos);
	} catch (err) {
	    console.error('Error al leer el directorio:', err);
	}

	// Obtener información del estado de un archivo de forma síncrona
	try {
	    const estado = fs.statSync('archivo.txt');
	    console.log('Información del estado del archivo:', estado);
	} catch (err) {
	    console.error('Error al obtener información del estado del archivo:', err);
	}

    ```



|| Fs Module (Async)

	El módulo fs (Sistema de Archivos) también proporciona un conjunto de funciones para trabajar con archivos de manera asíncrona. 

	A diferencia de las funciones síncronas, las operaciones asíncronas no bloquean la ejecución del programa, lo que permite que otras operaciones continúen mientras se realiza una operación de E/S de archivo.


	fs.readFile(): 

		Lee un archivo de forma asíncrona y devuelve su contenido.
    
    fs.writeFile(): 

    	Escribe datos en un archivo de forma asíncrona.
    
    fs.exists() (obsoleto): 

    	Verifica si un archivo o directorio existe de forma asíncrona.
    
    fs.readdir(): 

    	Lee los contenidos de un directorio de forma asíncrona.
    
    fs.stat(): 

    	Obtiene información del estado de un archivo de forma asíncrona.


   	Ejemplo: 

   	```js

   	const fs = require('fs');

	// Leer un archivo de forma asíncrona
	fs.readFile('archivo.txt', 'utf8', (err, data) => {
	    if (err) {
	        console.error('Error al leer el archivo:', err);
	    } else {
	        console.log('Contenido del archivo:', data);
	    }
	});

	// Escribir en un archivo de forma asíncrona
	fs.writeFile('nuevoArchivo.txt', 'Contenido de prueba', (err) => {
	    if (err) {
	        console.error('Error al escribir en el archivo:', err);
	    } else {
	        console.log('Archivo escrito de forma asíncrona.');
	    }
	});

	// Verificar si un archivo o directorio existe de forma asíncrona
	fs.access('archivo.txt', (err) => {
	    if (err) {
	        console.error('El archivo no existe.');
	    } else {
	        console.log('El archivo existe.');
	    }
	});

	// Leer los contenidos de un directorio de forma asíncrona
	fs.readdir('./', (err, files) => {
	    if (err) {
	        console.error('Error al leer el directorio:', err);
	    } else {
	        console.log('Archivos en el directorio:', files);
	    }
	});

	// Obtener información del estado de un archivo de forma asíncrona
	fs.stat('archivo.txt', (err, stats) => {
	    if (err) {
	        console.error('Error al obtener información del estado del archivo:', err);
	    } else {
	        console.log('Información del estado del archivo:', stats);
	    }
	});

   	```
   
   	En general, se recomienda utilizar operaciones asíncronas en Node.js, especialmente para tareas que implican operaciones de E/S, como la lectura y escritura de archivos, el acceso a bases de datos y las solicitudes de red. 

   	El uso de operaciones asíncronas ayuda a garantizar que la aplicación sea más receptiva y eficiente, lo que mejora la experiencia del usuario y la escalabilidad del sistema.

   	Se recomienda utilizar operaciones asíncronas siempre que sea posible para garantizar un rendimiento óptimo y una mejor capacidad de respuesta del sistema.



|| Operaciones asíncronas

	las operaciones asíncronas son fundamentales en Node.js debido a la naturaleza de un entorno de E/S no bloqueante y orientado a eventos.


	Operaciones de E/S de archivos y redes: 

		Las operaciones de lectura y escritura de archivos, así como las operaciones de red, son comunes en Node.js. 

		Al utilizar operaciones asíncronas, la aplicación puede continuar respondiendo a eventos y realizar otras tareas mientras se realizan estas operaciones.


	Acceso a bases de datos: 

		Las operaciones de acceso a bases de datos suelen ser operaciones lentas y costosas en términos de tiempo. 

		Al utilizar operaciones asíncronas, la aplicación puede mantener la capacidad de respuesta y permitir que otras operaciones continúen mientras se lleva a cabo la consulta a la base de datos.


	Solicitudes HTTP y API: 

		Las solicitudes a servidores externos a través de HTTP y el consumo de APIs también pueden ser procesos que consumen tiempo. 

		Al realizar estas operaciones de forma asíncrona, la aplicación puede continuar ejecutando otras tareas y manejar múltiples solicitudes simultáneamente.


	Operaciones de sistema: 

		Tareas como la gestión de eventos, la manipulación de archivos y la ejecución de comandos del sistema pueden beneficiarse de operaciones asíncronas para mantener una alta capacidad de respuesta y un rendimiento óptimo del sistema.



|| HTTP

	Módulo incorporado que proporciona funcionalidades para crear servidores HTTP y realizar solicitudes HTTP. 

	Con este módulo, puedes crear un servidor web o realizar solicitudes a otros servidores web


	1. Creación de servidores HTTP utilizando 

		http.createServer().

    2. Escucha de eventos de solicitud y respuesta en el servidor.

    3. Envío de respuestas HTTP utilizando 

    	response.writeHead() y response.end().

    4. Realización de solicitudes HTTP a otros servidores utilizando 

    	http.request().


    Permite interactuar con el protocolo HTTP para manejar solicitudes y respuestas de manera eficiente.


    Servidor básico:

    ```js

    const http = require('http');

	const server = http.createServer((req, res) => {
	  res.writeHead(200, {'Content-Type': 'text/plain'});
	  res.end('¡Hola, mundo!\n');
	});

	const PORT = 3000;
	server.listen(PORT, () => {
	  console.log(`Servidor en funcionamiento en http://localhost:${PORT}/`);
	});

    ```

    Crea un servidor HTTP que escucha en el puerto 3000. 

    Cada vez que se recibe una solicitud, el servidor responde con un mensaje de texto plano "¡Hola, mundo!" y devuelve un código de estado HTTP 200 (OK).

    Este es un ejemplo básico de cómo puedes usar el módulo http en Node.js para crear un servidor web sencillo.


    Solicitud a otros servidores: 

    ```js

    const http = require('http');

	const options = {
	  hostname: 'api.example.com',
	  port: 80,
	  path: '/data',
	  method: 'GET'
	};

	const req = http.request(options, (res) => {
	  console.log(`Código de estado: ${res.statusCode}`);

	  res.on('data', (chunk) => {
	    console.log(`Datos recibidos: ${chunk}`);
	  });

	  res.on('end', () => {
	    console.log('Respuesta completa');
	  });
	});

	req.on('error', (e) => {
	  console.error(`Error con la solicitud: ${e.message}`);
	});

	req.end();

    ```

    Realiza una solicitud GET al servidor en api.example.com y muestra el código de estado y los datos recibidos en la consola



|| npm

	Es el sistema de gestión de paquetes por defecto para Node.js.

	Permite a los desarrolladores instalar, compartir y gestionar paquetes de código reutilizables (llamados módulos) para sus proyectos.


	npm info:

		Muestra detalles sobre el paquete, incluida su última versión, descripción, autor, dependencias y otros metadatos relacionado.

	```	
	npm info nombre-del-paquete

	```		

	Comandos: 

		npm install: 

			Instala los paquetes especificados en el proyecto.

		npm uninstall: 

			Elimina los paquetes especificados del proyecto.

		npm init: 

			Inicia un nuevo proyecto de Node.js e inicializa un archivo "package.json".

		npm publish: 

			Publica un paquete en el registro público de "NPM" para que otros lo puedan utilizar.

		npm search: 

			Busca paquetes en el registro público de "NPM" según los términos de búsqueda especificados.

		npm run: 

			Ejecuta scripts definidos en el archivo "package.json".

		npm update: 

			Actualiza los paquetes instalados a las versiones más recientes, de acuerdo con las restricciones especificadas en el archivo "package.json".

		npm version: 

			Actualiza la versión de un paquete de acuerdo con las reglas de versionado semántico
	


|| Nodemon

	Herramienta de desarrollo que ayuda a automatizar el proceso de reinicio del servidor cada vez que se detectan cambios en los archivos del proyecto.

	Elimina la necesidad de reiniciar manualmente el servidor cada vez que se realizan cambios en el código. 

	Nodemon supervisa los archivos en el directorio del proyecto y reinicia automáticamente la aplicación cuando se detectan cambios.


	Instalar y ejecutar: 

		Instalarlo globalmente o localmente en tu proyecto, y luego ejecutar tu archivo de entrada (como app.js o index.js) con Nodemon en lugar de Node. 

		```
		nodemon app.js

		```

		Supervisará los archivos en el directorio y reiniciará automáticamente la aplicación cada vez que se realicen cambios, lo que te permite ver los resultados actualizados en tiempo real durante el desarrollo de tu aplicación Node.js.



|| Global install
	
	Instalación de paquetes de Node.js de forma global en tu sistema, lo que permite acceder a estos paquetes desde cualquier lugar en la línea de comandos

	```
	npm install -g nombre-del-paquete

	```

	Paquetes que a menudo se instalan globalmente en Node.js incluyen herramientas de desarrollo como Nodemon, Gulp, Grunt y otras utilidades que se utilizan a nivel del sistema. 

	La instalación global es útil cuando necesitas utilizar una herramienta específica en múltiples proyectos o cuando la herramienta en sí misma proporciona utilidades de línea de comandos que deseas utilizar de forma global en tu sistema.



|| package-lock.json

	Archivo que se crea automáticamente en los proyectos de Node.js cuando se instalan las dependencias del proyecto. 

	Sirve como un registro detallado de las versiones exactas de cada módulo de dependencia que se instala, asegurando así que las instalaciones posteriores de las dependencias se realicen de manera consistente en diferentes entornos.

	Evita problemas de versiones conflictivas y garantiza que se instalen las mismas versiones de las dependencias en diferentes máquinas.

	No se debe modificar manualmente, ya que se actualiza automáticamente cada vez que se realiza una instalación o desinstalación de dependencias en el proyecto. 

	Al trabajar en equipo o al distribuir un proyecto a otros desarrolladores, el package-lock.json asegura que todos estén utilizando las mismas versiones de las dependencias, lo que ayuda a mantener la consistencia y la estabilidad del proyecto.


	Dependencias: 

		Producción: 

			Necesarias para que la aplicación se ejecute en un entorno de producción.


		Desarrollo:  

			Necesarias para el desarrollo y la depuración de la aplicación, como herramientas de pruebas unitarias, herramientas de construcción y otras utilidades que ayudan en el proceso de desarrollo, pero no son necesarias para que la aplicación se ejecute en producción.



|| Event Loop

	El bucle de eventos se encarga de manejar las operaciones asíncronas y de eventos en Node.js. 

	Permite que Node.js realice operaciones no bloqueantes al delegar tareas costosas en tiempo a otros subprocesos y procesar rápidamente las operaciones livianas.


	Por supuesto, el "Event Loop" (bucle de eventos) es un concepto fundamental en Node.js y otros entornos de ejecución basados en JavaScript. Es esencialmente un bucle que se encarga de manejar las operaciones asíncronas y de eventos en Node.js. Permite que Node.js realice operaciones no bloqueantes al delegar tareas costosas en tiempo a otros subprocesos y procesar rápidamente las operaciones livianas.


    Call Stack (Pila de Llamadas): 

    	Es donde se rastrean las llamadas de funciones en ejecución. 

    	Cuando se invoca una función, se agrega a la pila. Cuando la función se completa, se elimina de la pila.


    Callback Queue (Cola de Devoluciones de Llamada): 

    	Aquí se encolan las devoluciones de llamada y otros eventos. 

    	Cuando el Call Stack está vacío, el Event Loop toma devoluciones de llamada de la cola y las coloca en el Call Stack para su ejecución.


    Event Table (Tabla de Eventos): 

    	Mantiene una lista de eventos asincrónicos y sus devoluciones de llamada asociadas.


    Heap (Montón): 

    	Es donde se almacenan objetos y variables.



|| Async Patterns

	Enfoques comunes y estructuras de diseño utilizadas para gestionar tareas asíncronas y eventos en aplicaciones.

	Diseñados para manejar operaciones no bloqueantes de manera eficiente y para garantizar que el código se ejecute de manera ordenada y predecible, incluso cuando hay múltiples operaciones asíncronas en curso.


	Callbacks (Devoluciones de Llamada): 

		Utilizados para manejar tareas asíncronas al pasar una función como argumento a otra función, que se llama una vez que se completa la operación.


	Promises (Promesas): 

		Proporcionan una forma más estructurada y legible de manejar operaciones asíncronas al representar un valor que puede estar disponible ahora, en el futuro, o nunca.


	Async/Await: 

		Una forma más moderna y legible de escribir código asincrónico que utiliza las palabras clave "async" y "await" para manejar las promesas de manera más secuencial y sincrónica.


	Event Emitters (Emisores de Eventos): 

		Permiten la comunicación entre objetos en Node.js mediante la emisión y escucha de eventos, lo que es útil para gestionar eventos y notificaciones en aplicaciones de servidor y en tiempo real.


	Primero debes comprender cómo funcionan los callback, luego estudiar Promises (como una herramienta para hacer callbacks más fácil) y luego async/await (como una sintaxis para hacer que las Promises sean bonitas). 

	Pero tenga en cuenta que el sistema subyacente es el mismo: funciones que llaman a funciones que se manejan (funciones que eventualmente se llamarán en el futuro). 




|| Promises

	Representa un valor que puede estar disponible ahora, en el futuro, o nunca, y se utiliza para manejar operaciones asíncronas y controlar su flujo.

	
	Estados posibles: 

	1. Pending (Pendiente): 

		El estado inicial de una promesa antes de que se resuelva o se rechace.
	

	2. Fulfilled (Cumplida): 

		Cuando la promesa se resuelve satisfactoriamente y se obtiene un valor.
	

	3. Rejected (Rechazada): 

		Cuando la promesa no se puede cumplir y se produce un error.


	```js

	const myPromise = new Promise((resolve, reject) => {
	  // Simulación de una operación asincrónica que se resuelve después de 2 segundos
	  setTimeout(() => {
	    const success = true;
	    if (success) {
	      resolve('¡La operación se completó con éxito!');
	    } else {
	      reject(new Error('La operación ha fallado.'));
	    }
	  }, 2000);
	});

	myPromise.then((message) => {
	  console.log(message);
	}).catch((error) => {
	  console.error(error);
	});

	```

	Una promesa es una "cosa" que representa los resultados "eventuales" de una operación, por así decirlo. 

	El punto a tener en cuenta aquí es que abstrae los detalles de cuándo sucede algo y le permite concentrarse en lo que debería suceder después de que algo suceda. Esto dará como resultado un código limpio y fácil de mantener donde, en lugar de tener una devolución de llamada dentro de una devolución de llamada dentro de una devolución de llamada. 



|| Callback

	Son funciones que se pasan como argumentos a otras funciones y que se llaman una vez que se completa una operación asíncrona o de E/S.

	Un patrón común de devolución de llamada en Node.js implica proporcionar una función de devolución de llamada como argumento a una función asíncrona.


	```js

	// Ejemplo de función asincrónica con un callback
	function realizarOperacionAsincrona(x, y, callback) {
	  setTimeout(() => {
	    const resultado = x + y;
	    callback(resultado);
	  }, 2000);
	}

	// Uso de la función asincrónica con un callback
	realizarOperacionAsincrona(3, 5, (resultado) => {
	  console.log(`El resultado de la operación es: ${resultado}`);
	});

	```

	Simula una operación asíncrona que se resuelve después de 2 segundos.

	Toma dos argumentos numéricos y una función de devolución de llamada.
	
	Después de 2 segundos, la función de devolución de llamada se llama con el resultado de la operación.



|| async/await

	Las funciones asíncronas son una herramienta útil cuando tienes múltiples acciones asíncronas (implementadas como promesas) que dependen unas de otras.

	Puedes usar convenientemente la palabra clave await para recibir primero los datos en la promesa 1, y luego pasar estos datos como argumento a la promesa 2.

	Por ejemplo, cuando tu segunda promesa necesita datos que tu primera promesa proporcionará.

	la función async puede, mediante la palabra clave await, hacer que la programación asíncrona se comporte como la síncrona. 

	Como consecuencia sus aplicaciones son más fáciles de entender.

	Esta es una gran alternativa a las clásicas callbacks de JavaScript.


	Uso de async/await: 

	1. Puedes usar await con cualquier función que devuelva una promesa.

	La función que esperas no tiene que ser necesariamente asíncrona.
	
	2. Debes usar funciones asíncronas cuando quieras usar la palabra clave await dentro de esa función.

	Si no vas a usar la palabra clave await dentro de una función entonces no necesitas hacer esa función async.
	
	3. Las funciones async por defecto devuelven una promesa. 

	Esa es la razón por la que puedes esperar funciones asíncronas.


	Ejemplo: 

	La palabra clave 'async' convierte una declaración de función JS normal en una declaración de función asíncrona:

	```js

	function syncFunc {// dostuff}
	async function asyncFunc {// dostuff} // la palabra clave async se coloca antes de la palabra clave function

	```

	Una función asíncrona devuelve una Promise:

		1. Cuando la función async devuelve un valor, la Promise se resolverá con el valor devuelto.

		2. Cuando la función async lanza una excepción o algún valor, la Promise será rechazada con el valor lanzado.

		Dentro de una función asíncrona puedes usar la palabra clave await. 

		await colocada antes de una promesa hace que la función asíncrona haga una pausa hasta que la promesa se resuelva (ya sea rechazada o cumplida).

		3. Cuando la promesa se cumple El valor de la expresión await es el valor de la promesa cumplida.
		
		4. Cuando la promesa es rechazada la expresión await lanza el valor rechazado.
	

	```
	function makePromise(x) { 
	    return new Promise(resolve => {
	      setTimeout(() => {
	        resolve(x);
	      }, 1000);
	    });
	  }
	  
	  async function asyncFunc() {
	    var x = await makePromise(1); // la función se detiene aquí hasta que se cumpla la promesa
	    console.log(x); // logs 1
	    return x;
	  }
	  
	  const returnedProm = asyncFunc(); // la función asíncrona devuelve una promesa

	  returnedProm.then((x) => console.log(x));
	  // Esta promesa se cumple con el valor de retorno de la función asíncrona, por lo que se registra 1

	```


	Ejemplo: 

	```	
	// Ejemplo de una función asincrónica utilizando async/await
	function esperar(ms) {
	  return new Promise(resolve => setTimeout(resolve, ms));
	}

	async function ejecutarOperacionAsincrona() {
	  console.log('Iniciando operación asincrónica...');
	  await esperar(2000);
	  console.log('La operación asincrónica ha finalizado.');
	}

	// Llamada a la función asincrónica
	ejecutarOperacionAsincrona();

	```

	La función 'esperar' devuelve una promesa que se resuelve después de un cierto tiempo (en milisegundos).

	La función 'ejecutarOperacionAsincrona' utiliza la palabra clave 'async' para indicar que es una función asincrónica y la palabra clave 'await' para esperar a que la promesa se resuelva antes de continuar con la ejecución.




|| Events

	Es una parte integral del sistema que permite la implementación de un patrón de diseño conocido como "Observer" (Observador). 

	Este patrón permite la comunicación entre objetos mediante la emisión y escucha de eventos. 

	El módulo "Events" proporciona una clase EventEmitter que se puede utilizar para crear objetos que emiten eventos y registrar manipuladores para esos eventos.


	1. Emitter (Emisor): 

		Es un objeto que emite eventos y permite que otros objetos se suscriban a esos eventos.


	2. Event (Evento): 

		Es una señal de que algo ha sucedido, como un clic de ratón, una solicitud HTTP o la finalización de una tarea asincrónica


	3. Listener (Oyente): 

		Es una función que se asocia con un evento y que se activa cuando se emite ese evento.


	```
	const EventEmitter = require('events');

	// Crear un emisor de eventos
	const miEmitter = new EventEmitter();

	// Registrar un oyente para el evento 'saludo'
	miEmitter.on('saludo', () => {
	  console.log('Hola, ¿cómo estás?');
	});

	// Emitir el evento 'saludo'
	miEmitter.emit('saludo');

	```
	
	Creamos un emisor de eventos con EventEmitter y registramos un oyente para el evento 'saludo'. 

	Luego, emitimos el evento 'saludo', lo que activa la función del oyente y produce la salida 'Hola, ¿cómo estás?'.


	El principal beneficio es el desacoplamiento de su código, puede registrar callbacks en un emisor de eventos sin que este sepa qué hacen exactamente esas callbacks.


	En nodejs, el bucle de eventos es de un solo subproceso y selecciona un evento a la vez y los trata de forma independiente.





|| HTTP Module









