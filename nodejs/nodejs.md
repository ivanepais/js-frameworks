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






