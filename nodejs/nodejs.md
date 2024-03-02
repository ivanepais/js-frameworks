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

	Módulo incorporado que permite crear aplicaciones del lado del servidor y realizar operaciones de red utilizando el protocolo HTTP.

	Proporciona funcionalidades para crear servidores HTTP, realizar solicitudes HTTP, y manejar eventos relacionados con el protocolo HTTP, como solicitudes y respuestas.

	```
	const http = require('http');

	// Crear un servidor HTTP simple
	const server = http.createServer((req, res) => {
	  res.writeHead(200, { 'Content-Type': 'text/plain' });
	  res.end('¡Hola desde el servidor HTTP de Node.js!\n');
	});

	// Escuchar en el puerto 8080
	server.listen(8080, '127.0.0.1', () => {
	  console.log('Servidor en funcionamiento en http://127.0.0.1:8080/');
	});


	```

	Utilizamos el módulo HTTP para crear un servidor HTTP simple que responde con un mensaje de saludo cuando se recibe una solicitud. 

	El servidor utiliza eventos para manejar las solicitudes entrantes y enviar respuestas al cliente



|| Streams
	
	Permite leer y escribir datos de manera eficiente en pedazos (o fragmentos) en lugar de manejar todo el conjunto de datos a la vez. 

	Los streams se utilizan para trabajar con datos que se pueden procesar de manera incremental y en tiempo real, lo que resulta especialmente útil para manipular archivos grandes o datos de red.


	Existen 4 tipos de streams: 

	1. Readable Streams (Flujos de Lectura): 

		Permiten la lectura de datos de una fuente, como un archivo, una solicitud HTTP o la salida de otro proceso.
	

	2. Writable Streams (Flujos de 
	Escritura): 

		Permiten escribir datos en un destino, como un archivo o una solicitud HTTP.
	

	3. Duplex Streams (Flujos Dúplex): 	

		Son flujos que pueden ser tanto de lectura como de escritura.
	

	4. Transform Streams (Flujos de Transformación): 

		Son un tipo especial de dúplex streams que permiten la manipulación de datos mientras se están transfiriendo de una fuente a un destino.


	```
	const fs = require('fs');

	// Crear un stream de lectura desde el archivo de origen
	const readableStream = fs.createReadStream('archivo-origen.txt');

	// Crear un stream de escritura hacia el archivo de destino
	const writableStream = fs.createWriteStream('archivo-destino.txt');

	// Piping (conducción) de los datos del stream de lectura al stream de escritura
	readableStream.pipe(writableStream);

	console.log('Copia de datos completada.');

	```

	Utilizamos streams para copiar datos de un archivo de origen a un archivo de destino de manera eficiente y sin bloqueos. 

	El método pipe() se utiliza para conectar el stream de lectura con el stream de escritura y transferir los datos de manera incremental.



|| Read File - Streams

	Implica la lectura de datos desde un archivo. 

	Una forma común de leer un archivo es utilizando streams, lo que permite leer y procesar el contenido del archivo en fragmentos en lugar de cargar todo el contenido en la memoria al mismo tiempo, lo que puede ser especialmente útil para archivos grandes

	El módulo 'fs' (sistema de archivos) integrado, que proporciona funcionalidades para interactuar con el sistema de archivos. P

	Puedes crear un stream de lectura utilizando el método 'createReadStream()' y luego manejar los eventos y los datos emitidos por el stream de lectura. 


	```
	const fs = require('fs');

	// Crear un stream de lectura desde el archivo
	const readableStream = fs.createReadStream('archivo.txt', 'utf8');

	// Manejar eventos y datos emitidos por el stream de lectura
	readableStream.on('data', (chunk) => {
	  console.log(`Recibidos ${chunk.length} bytes de datos.`);
	  console.log(chunk);
	});

	readableStream.on('end', () => {
	  console.log('Lectura del archivo completada.');
	});

	readableStream.on('error', (error) => {
	  console.error(`Se ha producido un error en la lectura del archivo: ${error}`);
	});

	```

	Creamos un stream de lectura desde un archivo de texto y manejamos los eventos 'data', 'end' y 'error' emitidos por el stream de lectura.

	Cada vez que se leen fragmentos de datos del archivo, se dispara el evento 'data', y al final de la lectura, se dispara el evento 'end'. 

	Si ocurre algún error durante la lectura, se dispara el evento 'error' y se maneja el error correspondiente.



|| HTTP Request/Response Cycle
	
	Proceso fundamental que subyace a la comunicación entre un cliente y un servidor en el contexto del protocolo HTTP. 

	Este ciclo describe la interacción entre un cliente, que envía una solicitud a un servidor, y el servidor, que procesa la solicitud y envía una respuesta de vuelta al cliente. 


	El ciclo típico de solicitud y respuesta HTTP sigue los siguientes pasos:

	1. Cliente envía una solicitud HTTP al servidor: 

		El cliente, generalmente un navegador web o una aplicación que realiza solicitudes HTTP, envía una solicitud al servidor para solicitar recursos como páginas web, archivos, o datos.


    2. Servidor recibe y procesa la solicitud: 

    	El servidor recibe la solicitud del cliente y la procesa, determinando cómo manejarla y qué respuesta enviar de vuelta al cliente.


    3. Servidor genera y envía una respuesta al cliente: 

    	El servidor genera una respuesta basada en la solicitud recibida y envía la respuesta de vuelta al cliente a través de Internet.

    
    4. Cliente recibe y procesa la respuesta: 

    	El cliente recibe la respuesta del servidor y la procesa, lo que puede implicar mostrar contenido en el navegador, realizar acciones específicas en función de la respuesta, o procesar datos recibidos.
	


|| HTTP Menssages

	Se utilizan para la comunicación entre el cliente y el servidor a través del protocolo HTTP. 

	Estos mensajes consisten en solicitudes y respuestas que contienen encabezados y, en el caso de las respuestas, un cuerpo opcional que puede contener datos o contenido.

	Los mensajes HTTP se utilizan para representar solicitudes entrantes y respuestas salientes en el servidor.

	transmiten información entre el cliente y el servidor, lo que permite que los datos y el contenido se envíen y reciban de manera eficiente y estructurada.


	```
	const http = require('http');

	// Crear un servidor HTTP simple
	const server = http.createServer((req, res) => {
	  // Manejar la solicitud entrante
	  // ... (código para manejar la solicitud)

	  // Escribir una respuesta con un mensaje de saludo
	  res.writeHead(200, { 'Content-Type': 'text/plain' });
	  res.write('¡Hola desde el servidor HTTP de Node.js!');
	  res.end();
	});

	// Escuchar en un puerto específico
	server.listen(8080, '127.0.0.1', () => {
	  console.log('Servidor en funcionamiento en http://127.0.0.1:8080/');
	});

	```

	El módulo "http" para crear un servidor HTTP simple que responde con un mensaje de saludo. 

	Manejamos la solicitud entrante y luego escribimos una respuesta utilizando el método 'writeHead()' para establecer los encabezados de la respuesta y 'write()' para enviar el contenido de la respuesta. 

	Finalmente, utilizamos el método 'end()' para finalizar la respuesta y enviarla al cliente.



|| Conceptos HTTP

	
	Protocolo de Transferencia de Hipertexto (HTTP): 

		HTTP es un protocolo de aplicación utilizado para la transferencia de información en la World Wide Web. 

		Se utiliza para la comunicación entre un cliente, como un navegador web, y un servidor que aloja recursos, como páginas web, imágenes y archivos.


    Cliente y Servidor: 

    	En el contexto de HTTP, el cliente es generalmente un navegador web o una aplicación que realiza solicitudes de recursos, y el servidor es una máquina remota que aloja y sirve esos recursos en respuesta a las solicitudes del cliente.


    Métodos HTTP: 

    	Los métodos HTTP son acciones que se utilizan para indicar la acción deseada a realizar en un recurso determinado. 

    	Algunos de los métodos HTTP más comunes son GET (para obtener recursos), POST (para enviar datos al servidor), PUT (para actualizar recursos) y DELETE (para eliminar recursos).


    Códigos de Estado HTTP: 

    	Los códigos de estado son códigos numéricos que indican el estado de una solicitud HTTP realizada por el cliente.

    	Algunos de los códigos de estado HTTP más comunes incluyen 200 (OK), 404 (No Encontrado), y 500 (Error del Servidor Interno).


    Encabezados HTTP: 

    	Los encabezados son componentes de los mensajes HTTP que transmiten información adicional sobre la solicitud o respuesta. 

    	Los encabezados pueden incluir información sobre el tipo de contenido, la longitud del contenido, la fecha y hora de la solicitud o respuesta, entre otros detalles.


    URL (Localizador Uniforme de Recursos): 

    	Una URL es una cadena de caracteres que proporciona la dirección de un recurso en la web. 

    	Las URL se utilizan para identificar y localizar recursos, como páginas web, imágenes y archivos, a través de Internet.



|| HTTP Headers

	Componentes clave de los mensajes HTTP que se utilizan para transmitir información adicional sobre una solicitud o una respuesta. 

	Los encabezados HTTP se utilizan para proporcionar metadatos importantes que ayudan a especificar cómo se debe procesar una solicitud o una respuesta, qué tipo de contenido se está enviando o recibiendo, y otra información relevante para la comunicación entre el cliente y el servidor.

	Se utiliza el módulo HTTP incorporado para manejar los encabezados HTTP en solicitudes entrantes y respuestas salientes.

	Al manipular los encabezados HTTP, puedes establecer metadatos como el tipo de contenido, la longitud del contenido, la codificación, la fecha y hora, y otros detalles importantes relacionados con la comunicación HTTP.

	Utilizamos el método 'writeHead()' para establecer el encabezado de contenido en la respuesta con el código de estado 200 y el tipo de contenido 'text/plain'. 

	Esto indica que el servidor está respondiendo con un texto plano. Además, utilizamos el método 'write()' para escribir datos en la respuesta y el método 'end()' para finalizar la respuesta y enviarla al cliente.




|| HTTP Request Object

	El objeto de solicitud HTTP se refiere al objeto que representa una solicitud entrante a un servidor HTTP. 

	Este objeto contiene información sobre la solicitud realizada por el cliente, incluidos detalles como la URL solicitada, los encabezados de la solicitud, los parámetros de la consulta, el método HTTP utilizado y otros metadatos relacionados con la solicitud.

	Al utilizar el módulo HTTP incorporado en Node.js, puedes acceder al objeto de solicitud HTTP y utilizar sus propiedades y métodos para leer y procesar los detalles de la solicitud entrante.

	Puedes acceder a propiedades como 'url', 'method', 'headers' y 'httpVersion' para obtener información sobre la solicitud y tomar decisiones sobre cómo manejarla.

	```
	const http = require('http');

	// Crear un servidor HTTP simple
	const server = http.createServer((req, res) => {
	  // Acceder a propiedades del objeto de solicitud
	  const { url, method, headers } = req;
	  console.log('URL solicitada:', url);
	  console.log('Método de solicitud:', method);
	  console.log('Encabezados de la solicitud:', headers);

	  // Escribir una respuesta con un mensaje de saludo
	  res.writeHead(200, { 'Content-Type': 'text/plain' });
	  res.write('¡Hola desde el servidor HTTP de Node.js!');
	  res.end();
	});

	// Escuchar en un puerto específico
	server.listen(8080, '127.0.0.1', () => {
	  console.log('Servidor en funcionamiento en http://127.0.0.1:8080/');
	});

	```
	Accedemos a las propiedades 'url', 'method' y 'headers' del objeto de solicitud 'req' y las imprimimos en la consola para mostrar detalles sobre la solicitud entrante.



|| HTTP - HTML File

	Utilizar módulos como http y fs para servir archivos HTML estáticos desde un servidor. 

	Los archivos HTML son archivos de texto plano que contienen código HTML y se utilizan para representar contenido y estructura en una página web.

	Primero leer el contenido del archivo HTML utilizando el módulo 'fs' y luego enviar el contenido como respuesta a una solicitud HTTP entrante utilizando el módulo 'http'.	
	

	Ejemplo: 

		Servir un archivo HTML estático

	```
	const http = require('http');
	const fs = require('fs');

	http.createServer((req, res) => {
	  // Leer el contenido del archivo HTML
	  fs.readFile('archivo.html', (err, data) => {
	    if (err) {
	      res.writeHead(404, { 'Content-Type': 'text/plain' });
	      res.write('Archivo no encontrado');
	      res.end();
	    } else {
	      // Escribir la respuesta con el contenido del archivo HTML
	      res.writeHead(200, { 'Content-Type': 'text/html' });
	      res.write(data);
	      res.end();
	    }
	  });
	}).listen(8080);

	console.log('Servidor en funcionamiento en http://127.0.0.1:8080/');

	```

	Lee el contenido de un archivo HTML llamado archivo.html y luego envía ese contenido como respuesta a cualquier solicitud HTTP entrante.

	Dependiendo de si se encuentra el archivo o no, el servidor envía una respuesta con un código de estado 404 (No Encontrado) o 200 (OK).



|| Express.js - All Static

	Técnica de servir archivos estáticos, como archivos HTML, CSS, JavaScript, imágenes y otros recursos estáticos, directamente desde el servidor sin procesamiento adicional. 

	En Express.js, puedes utilizar el middleware express.static para servir archivos estáticos de un directorio específico.

	Al utilizar la función express.static en Express.js, puedes especificar un directorio que contiene recursos estáticos, y Express configurará automáticamente las rutas para servir estos archivos estáticos en el servidor.


	```
	const express = require('express');
	const path = require('path');

	const app = express();

	// Servir archivos estáticos desde el directorio 'public'
	app.use(express.static(path.join(__dirname, 'public')));

	// Iniciar el servidor en un puerto específico
	const PORT = 3000;
	app.listen(PORT, () => {
	  console.log(`Servidor Express en funcionamiento en el puerto ${PORT}`);
	});

	```

	'express.static' se utiliza para servir archivos estáticos desde el directorio "public". 

	Todos los archivos presentes en el directorio "public" (como archivos HTML, CSS, imágenes, etc.) serán accesibles desde el servidor Express. 

	Puedes acceder a los archivos en el navegador utilizando rutas relativas a la raíz del directorio "public".



|| CSR, SPA, SSR y API 

	CSR: 

		Client-Side Rendering enfoque utilizado en el desarrollo web donde la mayor parte del procesamiento y renderización de la interfaz de usuario se realiza en el navegador del cliente en lugar de en el servidor. 

		En este modelo, el servidor envía datos en bruto al cliente, generalmente en formato JSON u otro formato de datos, y luego el cliente utiliza estos datos para generar y renderizar la interfaz de usuario de manera dinámica en el navegador.

		El navegador es responsable de tomar los datos proporcionados por el servidor y convertirlos en una representación visual que el usuario puede interactuar. 

		Esto se hace típicamente utilizando JavaScript y bibliotecas de front-end como React, Vue.js, Angular u otras.

		Interactividad rápida: 

			La renderización en el lado del cliente permite una experiencia de usuario más fluida y receptiva, ya que las interacciones del usuario se pueden manejar de forma instantánea en el navegador sin necesidad de comunicarse constantemente con el servidor.

    	Menor carga en el servidor: 

    		Al transferir la mayor parte del trabajo de renderización al cliente, el servidor puede concentrarse en servir datos en bruto y otras tareas relacionadas con la lógica del negocio, lo que puede ayudar a reducir la carga del servidor y mejorar el rendimiento general del sitio web.

    	Separación de preocupaciones:

    		El Client-Side Rendering facilita la separación de la lógica del negocio en el servidor y la presentación en el cliente, lo que puede hacer que el código sea más modular y mantenible.


   	SPA: 

   		Single Page Application es un tipo de aplicación web que carga una sola página HTML y luego actualiza dinámicamente esa página mientras el usuario interactúa con la aplicación, en lugar de cargar páginas completamente nuevas desde el servidor.

		En una SPA, la mayor parte del procesamiento ocurre en el navegador del cliente utilizando JavaScript y bibliotecas de front-end como React, Angular, Vue.js, o similares. 

		La navegación entre diferentes secciones o vistas de la aplicación se realiza cambiando dinámicamente el contenido de la página, a menudo utilizando enlaces internos o el historial del navegador para mantener el estado de la aplicación.


	SSR: 

		Server-Side Rendering es una técnica utilizada en el desarrollo web para renderizar y enviar páginas web completas al cliente desde el servidor, en lugar de renderizarlas en el navegador del cliente. 

		Esto implica que el servidor genera el HTML final basado en el estado de la aplicación y lo envía al cliente como una página completa, lista para mostrarse en el navegador

		Al enviar una versión pre-renderizada de la página al cliente, se puede mejorar la velocidad de carga inicial y la legibilidad de la página para los motores de búsqueda.

		Puede ser más costoso en términos de uso de recursos del servidor en comparación con el Renderizado del Lado del Cliente (Client-Side Rendering), ya que el servidor debe generar y enviar el HTML completo en cada solicitud.

		Además, en comparación con las aplicaciones de una sola página (Single Page Applications) que utilizan CSR, las aplicaciones que utilizan SSR pueden requerir una comunicación más frecuente entre el cliente y el servidor, lo que puede afectar la experiencia del usuario en términos de interactividad y dinamismo.

		Es útil para mejorar el rendimiento inicial y la SEO (optimización para motores de búsqueda) de una aplicación web, aunque puede requerir más recursos del servidor y potencialmente limitar la interactividad y dinamismo en comparación con las aplicaciones de una sola página que utilizan CSR.


	API: 

	Application Programming Interface es un conjunto de reglas y protocolos que permiten que distintos programas se comuniquen entre sí. 

	Proporciona un conjunto de comandos, protocolos y herramientas para construir software y aplicaciones. 

	Las API permiten que distintos componentes de software interactúen entre sí de manera estandarizada.

	Pueden tomar varias formas, incluidas las API web, que permiten la comunicación entre aplicaciones a través de Internet. 
	
	Estas son particularmente comunes en el contexto de servicios web y aplicaciones en la nube. 

	Las API también pueden ser utilizadas por sistemas operativos, bibliotecas de software, y diversas aplicaciones de software para definir cómo deben interactuar diferentes componentes de software.

	Por ejemplo, las API web son utilizadas para permitir la integración de distintos servicios y aplicaciones. 

	Esto puede incluir la integración de servicios de terceros, como redes sociales o servicios de pago, en una aplicación web o móvil. 

	Las API también permiten a los desarrolladores acceder a funcionalidades y datos específicos de servicios externos, como datos de clima, geolocalización, o información de productos en una tienda en línea.



|| JSON

	Es un formato ligero de intercambio de datos. 

	Es fácil de leer y escribir para los humanos, y fácil de generar y analizar para las máquinas. 

	Está basado en un subconjunto del lenguaje de programación JavaScript, pero es independiente de cualquier lenguaje de programación.


	Sintaxis: 

		JSON utiliza una sintaxis sencilla y fácil de entender que consiste en pares de clave-valor. 

		Los datos se representan en forma de objetos (objetos anidados o anidamiento de objetos) y matrices (listas de valores) en JSON.

		Claves son cadenas de texto y los valores pueden ser cadenas de texto, números, booleanos, arrays, objetos o null. 

		Los pares clave-valor se separan por comas y se encierran entre llaves {} para objetos y corchetes [] para arrays.

		```
		{
		  "nombre": "Juan",
		  "edad": 30,
		  "casado": false,
		  "hobbies": ["leer", "correr", "viajar"],
		  "direccion": {
		    "calle": "Calle Principal",
		    "ciudad": "Ciudad Ejemplo",
		    "codigo_postal": "12345"
		  }
		}

		```


	Tipos de datos admitidos: 

		JSON admite tipos de datos simples como cadenas de texto, números, booleanos y valores nulos, así como tipos de datos compuestos como objetos y matrices. 

		Esto lo hace adecuado para representar una amplia variedad de datos.


	Formato de intercambio de datos:

		JSON se utiliza comúnmente como un formato de intercambio de datos entre aplicaciones y servicios web. 

		Es particularmente útil en el contexto de la comunicación entre el servidor y el cliente, donde los datos se envían y reciben en formato JSON.


	Serialización y deserialización: 

		La serialización se refiere al proceso de convertir datos en un formato compatible con JSON, mientras que el análisis se refiere al proceso inverso de convertir datos JSON en un formato legible para un programa.


	Uso en la web: 

		JSON se utiliza ampliamente en el desarrollo web para el intercambio de datos entre el cliente y el servidor. 

		Se utiliza en APIs web y servicios web para transmitir datos estructurados de manera eficiente



|| Params - Express.js

	Valores variables que forman parte de la URL de una solicitud. 

	Estos parámetros son utilizados para capturar valores específicos de la URL y utilizarlos en el procesamiento de una solicitud en el servidor. 

	Los parámetros de ruta se definen en las rutas de Express y se utilizan para capturar valores dinámicos proporcionados en la URL.

	```
	app.get('/users/:userId', (req, res) => {
	  const userId = req.params.userId;
	  // Resto del código para manejar la solicitud
	});

	```

	':userId' es un parámetro de ruta que captura un valor variable en la URL. 

	Cuando se recibe una solicitud en esta ruta, Express capturará el valor proporcionado en el lugar de ':userId' y lo hará disponible a través del objeto 'req.params' en el controlador de la ruta. 

	Puedes acceder a este valor capturado utilizando 'req.params.userId'.

	Son útiles para crear rutas dinámicas que pueden manejar diferentes valores de identificación u otros parámetros en una sola ruta.



|| Query String

	Parte de una URL que se utiliza para pasar datos a través de parámetros de consulta. 

	La cadena de consulta es una serie de pares clave-valor separados por el símbolo '&' y se coloca al final de una URL después del signo de interrogación ('?'). 

	Estos parámetros de consulta permiten la transferencia de datos adicionales entre el cliente y el servidor, lo que facilita la personalización y filtrado de los datos solicitados.

	```
	http://ejemplo.com/ruta?nombre=Juan&edad=30

	```

	La cadena de consulta es ?nombre=Juan&edad=30, donde nombre y edad son claves, y Juan y 30 son los valores correspondientes. 

	En Express.js, puedes acceder a estos parámetros de consulta a través del objeto req.query en el controlador de la ruta correspondiente


	Acceder a los parámetros de consulta en Express.js:

	```
	app.get('/ruta', (req, res) => {
	  const nombre = req.query.nombre;
	  const edad = req.query.edad;
	  // Resto del código para manejar la solicitud con los parámetros de consulta
	});

	```

	Utilizando la propiedad req.query, puedes acceder a los valores proporcionados en la cadena de consulta y utilizarlos en la lógica de manejo de rutas para procesar y responder a la solicitud de manera adecuada. 

	Esto es útil para realizar búsquedas, filtrar datos y personalizar la respuesta del servidor en función de los parámetros proporcionados en la URL.	


|| Funciones, Middleware y app.use

	Se refiere a funciones que tienen acceso al objeto de solicitud (req), al objeto de respuesta (res) y a la siguiente función de middleware en el ciclo de solicitud-respuesta de la aplicación. 

	El middleware puede realizar tareas como realizar modificaciones en la solicitud y la respuesta, terminar el ciclo de solicitud-respuesta, llamar a la siguiente función de middleware en la pila o incluso finalizar la solicitud.

	Se utiliza para realizar tareas comunes, como el registro, la autenticación, el manejo de errores, el análisis del cuerpo de la solicitud, entre otras. 

	El middleware se puede montar a nivel de aplicación, a nivel de enrutador o a nivel de ruta, lo que permite un alto grado de flexibilidad en la manipulación del flujo de solicitud y respuesta.

	```js

	// Ejemplo de middleware a nivel de aplicación
	app.use((req, res, next) => {
	  console.log('Time:', Date.now());
	  next();
	});

	// Ejemplo de middleware a nivel de ruta
	app.get('/', (req, res, next) => {
	  // Middleware específico para la ruta raíz
	  next();
	});

	// Ejemplo de manejo de rutas
	app.get('/', (req, res) => {
	  res.send('Hola Mundo!'); // Responde con 'Hola Mundo!' al realizar una solicitud GET a '/'
	});

	```

	'app.use' se utiliza para montar el middleware a nivel de aplicación, lo que significa que se aplicará a todas las solicitudes que lleguen a la aplicación. 

	También puedes aplicar middleware a nivel de ruta utilizando funciones de middleware específicas en la definición de la ruta. 

	El middleware puede realizar tareas específicas y luego pasar el control a la siguiente función de middleware en la pila llamando a 'next()'.



|| Multiple Middleware Functions

	Es posible definir múltiples funciones de middleware para una ruta específica. 

	Esto permite encadenar varias funciones de middleware para manejar una solicitud en una secuencia específica. 

	Cada función de middleware tiene acceso a los objetos de solicitud (req), respuesta (res) y a la siguiente función de middleware en la pila.

	Para definir múltiples funciones de middleware para una ruta en Express.js, puedes pasar una serie de funciones de middleware como argumentos en la definición de la ruta. 

	Cada función de middleware se ejecutará en orden y, si se llama a 'next()', pasará el control a la siguiente función de middleware en la pila.

	```
	// Ejemplo de múltiples funciones de middleware para una ruta
	app.get('/ejemplo', 
	  function middleware1(req, res, next) {
	    console.log('Middleware 1');
	    next();
	  },
	  function middleware2(req, res, next) {
	    console.log('Middleware 2');
	    next();
	  },
	  function middleware3(req, res) {
	    console.log('Middleware 3');
	    res.send('Respuesta final');
	  }
	);

	```

	se definen tres funciones de middleware diferentes para la ruta '/ejemplo'. 

	Cada función de middleware realiza una tarea específica y luego llama a 'next()' para pasar el control a la siguiente función de middleware en la pila. 

	La última función de middleware responde directamente a la solicitud utilizando el método 'res.send()'. 

	Mediante el encadenamiento de múltiples funciones de middleware, puedes controlar y manipular el flujo de una solicitud de manera más detallada y secuencial.



|| Methods - Express.js

	Se refieren a los distintos verbos HTTP que se utilizan para indicar la acción que se debe realizar en un recurso específico. 

	Estos métodos o verbos son utilizados para especificar la intención de una solicitud HTTP y ayudan a determinar la operación que se debe realizar en el servidor. 

	Algunos de los métodos comunes en Express.js incluyen GET, POST, PUT, DELETE, entre otros.

	GET: 

		Se utiliza para solicitar datos de un recurso específico del servidor. 
		Por ejemplo, obtener información de un usuario específico.


    POST: 

    	Se utiliza para enviar datos al servidor para crear un nuevo recurso.
    	Por ejemplo, enviar datos de un formulario para crear una nueva entrada en una base de datos.


    PUT: 

    	Se utiliza para actualizar o reemplazar datos de un recurso específico en el servidor. 
		Por ejemplo, actualizar la información de un usuario existente.


    DELETE: 

    	Se utiliza para eliminar un recurso específico en el servidor. Por ejemplo, eliminar un usuario de una base de datos.


	Son utilizados por Express.js para manejar diferentes tipos de solicitudes HTTP y realizar operaciones específicas en función del verbo HTTP proporcionado en la solicitud. 

	Puedes definir rutas específicas en Express.js que respondan a diferentes métodos HTTP para manejar diversas operaciones de manera eficaz
	


|| GET - Express.js

	```
	const express = require('express');
	const app = express();
	const PORT = 3000;

	// Definir una ruta con el método GET
	app.get('/', function(req, res) {
	  res.send('¡Hola desde Express!');
	});

	// Iniciar el servidor en el puerto especificado
	app.listen(PORT, function() {
	  console.log(`Servidor Express en funcionamiento en el puerto ${PORT}`);
	});

	```

	Se define una ruta utilizando app.get('/', function(req, res) {...}). 

	La función de devolución de llamada toma dos argumentos, req y res, que representan el objeto de solicitud y el objeto de respuesta respectivamente. 

	Dentro de la función de devolución de llamada, se utiliza el método res.send() para enviar una respuesta al cliente cuando se realiza una solicitud GET a la ruta especificada, en este caso, la ruta raíz '/'.

	Cuando se inicia el servidor con 'app.listen()', el servidor Express estará en funcionamiento en el puerto especificado, y la ruta definida responderá a las solicitudes GET con el mensaje "¡Hola desde Express!" en el navegador o en la herramienta de prueba de API que estés utilizando.



|| POST - Express.js 

	```
	const express = require('express');
	const app = express();
	const PORT = 3000;

	// Configurar el middleware para analizar el cuerpo de la solicitud
	app.use(express.json());
	app.use(express.urlencoded({ extended: true }));

	// Definir una ruta con el método POST
	app.post('/login', function(req, res) {
	  const { username, password } = req.body;
	  // Verificar las credenciales aquí (esto es solo un ejemplo)
	  if (username === 'usuario' && password === 'contraseña') {
	    res.send('Inicio de sesión exitoso');
	  } else {
	    res.status(401).send('Credenciales incorrectas');
	  }
	});

	// Iniciar el servidor en el puerto especificado
	app.listen(PORT, function() {
	  console.log(`Servidor Express en funcionamiento en el puerto ${PORT}`);
	});

	```

	Se define una ruta utilizando app.post('/login', function(req, res) {...}). 

	La función de devolución de llamada toma dos argumentos, req y res, que representan el objeto de solicitud y el objeto de respuesta, respectivamente. 

	Dentro de la función de devolución de llamada, se accede a los datos enviados en el cuerpo de la solicitud a través de req.body.

	En este caso, se asume que se reciben las credenciales de inicio de sesión en el cuerpo de la solicitud. 

	Se verifica si las credenciales son válidas y se envía una respuesta en consecuencia. 

	Si las credenciales son válidas, se envía el mensaje "Inicio de sesión exitoso". 

	Si las credenciales no son válidas, se envía un estado 401 con el mensaje "Credenciales incorrectas".



|| Form - Express.js


	```html

	<!DOCTYPE html>
	<html>
	<body>

	<h2>Formulario de ejemplo</h2>

	<form action="http://localhost:3000/formulario" method="post">
	  <label for="nombre">Nombre:</label><br>
	  <input type="text" id="nombre" name="nombre"><br>
	  <label for="apellido">Apellido:</label><br>
	  <input type="text" id="apellido" name="apellido"><br><br>
	  <input type="submit" value="Enviar">
	</form>

	</body>
	</html>

	```

	Se envían dos campos, "nombre" y "apellido", utilizando el método POST a la ruta /formulario en el servidor Express.js. 

	Asegúrate de que el servidor Express esté en funcionamiento en el puerto 3000 y de que tenga una ruta configurada para manejar la solicitud POST en la ruta /formulario.

	```js

	const express = require('express');
	const app = express();
	const PORT = 3000;

	// Configurar el middleware para analizar el cuerpo de la solicitud
	app.use(express.urlencoded({ extended: true }));

	// Manejar la solicitud POST desde el formulario
	app.post('/formulario', function(req, res) {
	  const { nombre, apellido } = req.body;
	  res.send(`¡Hola ${nombre} ${apellido}!`);
	});

	// Iniciar el servidor en el puerto especificado
	app.listen(PORT, function() {
	  console.log(`Servidor Express en funcionamiento en el puerto ${PORT}`);
	});

	```

	Configura el middleware para analizar los datos del formulario mediante express.urlencoded(). 

	La solicitud POST a la ruta /formulario se maneja para extraer los datos del cuerpo de la solicitud y enviar un saludo personalizado en función de los datos proporcionados en el formulario.



|| PUT - Express.js

	
	```js

	const express = require('express');
	const app = express();
	const PORT = 3000;

	// Configurar el middleware para analizar el cuerpo de la solicitud
	app.use(express.json());
	app.use(express.urlencoded({ extended: true }));

	// Datos de ejemplo para simular una base de datos
	let usuarios = [
	  { id: 1, nombre: 'Ejemplo1' },
	  { id: 2, nombre: 'Ejemplo2' }
	];

	// Ruta para actualizar un usuario mediante el método PUT
	app.put('/usuarios/:id', function(req, res) {
	  const userId = req.params.id;
	  const nuevoNombre = req.body.nombre;
	  usuarios.forEach(usuario => {
	    if (usuario.id === Number(userId)) {
	      usuario.nombre = nuevoNombre;
	    }
	  });
	  res.send('Usuario actualizado correctamente');
	});

	// Iniciar el servidor en el puerto especificado
	app.listen(PORT, function() {
	  console.log(`Servidor Express en funcionamiento en el puerto ${PORT}`);
	});


	```

	Se define una ruta utilizando app.put('/usuarios/:id', function(req, res) {...}) para actualizar un usuario específico en la "base de datos" simulada. 

	El parámetro ':id' en la ruta se utiliza para identificar al usuario que se va a actualizar. 

	La función de devolución de llamada toma los datos del cuerpo de la solicitud y busca al usuario correspondiente en el array 'usuarios'. 

	Una vez encontrado, actualiza el nombre del usuario con el nuevo nombre proporcionado en el cuerpo de la solicitud.

	Al realizar una solicitud 'PUT' a la ruta '/usuarios/:id' con un nuevo nombre en el cuerpo de la solicitud, el servidor responderá con el mensaje "Usuario actualizado correctamente". 



|| DELETE - Express.js

	```js

	const express = require('express');
	const app = express();
	const PORT = 3000;

	// Datos de ejemplo para simular una base de datos
	let usuarios = [
	  { id: 1, nombre: 'Ejemplo1' },
	  { id: 2, nombre: 'Ejemplo2' }
	];

	// Ruta para eliminar un usuario mediante el método DELETE
	app.delete('/usuarios/:id', function(req, res) {
	  const userId = req.params.id;
	  usuarios = usuarios.filter(usuario => usuario.id !== Number(userId));
	  res.send('Usuario eliminado correctamente');
	});

	// Iniciar el servidor en el puerto especificado
	app.listen(PORT, function() {
	  console.log(`Servidor Express en funcionamiento en el puerto ${PORT}`);
	});


	```

	Define una ruta utilizando app.delete('/usuarios/:id', function(req, res) {...}) para eliminar un usuario específico en la "base de datos" simulada. 

	El parámetro ':id' en la ruta se utiliza para identificar al usuario que se va a eliminar. 

	La función de devolución de llamada filtra el array 'usuarios' para mantener solo aquellos usuarios cuyo ID no coincide con el ID proporcionado en la solicitud.

	Al realizar una solicitud 'DELETE' a la ruta /usuarios/:id, el servidor responderá con el mensaje "Usuario eliminado correctamente" después de eliminar el usuario correspondiente. 
	


|| Router - Express.js	

	Función constructora que se utiliza para crear manejadores de rutas montables y modulares. 

	Permite dividir tu aplicación en subaplicaciones y grupos de rutas más pequeñas y manejables. 

	Con el enrutador, puedes definir rutas, aplicar middleware y manejar solicitudes HTTP para rutas específicas de manera modular y organizada.

	Al utilizar Router en Express.js, puedes definir grupos de rutas con funcionalidades relacionadas y luego montar estos grupos de rutas en la aplicación principal. 

	Esto facilita la organización y el mantenimiento de aplicaciones más grandes al dividirlas en componentes más pequeños y fáciles de administrar. 

	```
	const express = require('express');
	const app = express();
	const router = express.Router();

	// Definir una ruta utilizando el enrutador
	router.get('/', function(req, res) {
	  res.send('¡Hola desde el enrutador!');
	});

	// Montar el enrutador en la aplicación principal
	app.use('/ruta', router);

	// Iniciar el servidor en el puerto especificado
	app.listen(3000, function() {
	  console.log('Servidor Express en funcionamiento en el puerto 3000');
	});

	```

	define un enrutador utilizando express.Router() y se le agrega una ruta utilizando router.get('/' ...). 

	Luego, el enrutador se monta en la aplicación principal utilizando app.use('/ruta', router). 

	Esto significa que todas las rutas definidas en el enrutador se precederán con '/ruta' en la aplicación principal. 

	Esto te permite mantener tus rutas organizadas y modularizar tu aplicación en función de la lógica y la funcionalidad.



|| Router Controllers - Express.js

	funciones que se utilizan como controladores para manejar la lógica de las rutas definidas en un enrutador. 

	Estos controladores se encargan de procesar las solicitudes entrantes, realizar operaciones específicas y enviar respuestas adecuadas al cliente.

	El uso de controladores en un enrutador permite separar la lógica de manejo de rutas de la definición de las rutas mismas. 

	Esto promueve una mejor organización del código y facilita la reutilización de la lógica en diferentes rutas o incluso en diferentes aplicaciones.


	```JS

	// usersController.js

	// Controlador para manejar la lógica de la ruta de usuarios
	exports.getUser = function(req, res) {
	  res.send('Obteniendo información del usuario');
	};

	exports.createUser = function(req, res) {
	  res.send('Creando un nuevo usuario');
	};

	```

	```
	// routes.js

	const express = require('express');
	const router = express.Router();
	const usersController = require('./usersController');

	// Definir las rutas y usar los controladores correspondientes
	router.get('/users', usersController.getUser);
	router.post('/users', usersController.createUser);

	module.exports = router;

	```

	En este ejemplo, usersController.js contiene funciones de controlador para manejar las operaciones relacionadas con los usuarios, como obtener información del usuario y crear un nuevo usuario. 

	Estos controladores se exportan y se utilizan en el archivo routes.js, donde se definen las rutas utilizando router.get() y router.post(). 

	De esta manera, la lógica de manejo de las rutas se mantiene separada de la definición de las rutas mismas, lo que facilita el mantenimiento y la organización del código.	



|| Postman

	Plataforma de colaboración para el desarrollo de API que permite a los desarrolladores diseñar, probar, documentar, monitorear y compartir fácilmente API. 

	Tiene su origen en 2012, cuando Abhinav Asthana creó Postman como una extensión de Chrome para simplificar la construcción y el manejo de solicitudes de API. 

	Desde entonces, se ha convertido en una herramienta fundamental para desarrolladores de API en todo el mundo

	Probar diferentes rutas y métodos, y ver las respuestas para asegurarse de que las API funcionen correctamente. 

	Postman también ofrece características avanzadas como la creación de entornos, pruebas automatizadas, generación de documentación y colaboración entre equipos, lo que hace que el proceso de desarrollo de API sea más eficiente y productivo.
