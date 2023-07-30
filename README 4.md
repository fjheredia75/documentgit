# documentgit


<h1>Day 4</h1>

<h1>✔️ NEST.JS</h1>
<h5>Nest.js es un potente y versátil marco de desarrollo de aplicaciones Nest.js es un framework de desarrollo de aplicaciones Node.js poderoso y versátil que se basa en un enfoque modular y en la arquitectura de controladores.js que se basa en el enfoque modular y la arquitectura de controladores. Su arquitectura escalable y su capacidad para construir APIs RESTful eficientes hacen que sea una opción popular entre los desarrolladores para la creación de servicios web robustos.</h5>
<img src=https://miro.medium.com/v2/resize:fit:1400/0*1VyCqSN0pdtXitey.jpg  alt="Descripción de la imagen">


<h1>✔️ API:CRUD</h1>

<h5>Es un conjunto de operaciones básicas que permiten la manipulación de datos en una fuente de información, como una base de datos, a través de una interfaz de programación de aplicaciones (API). Estas operaciones fundamentales son ampliamente utilizadas en el desarrollo de aplicaciones para realizar tareas esenciales, como crear nuevos registros, leer datos existentes, actualizar información y eliminar registros de manera sencilla y eficiente.</h5>

<img src=https://qph.cf2.quoracdn.net/main-qimg-90d63940167637853117e850cfd26124  alt="Descripción de la imagen">

<h1>✔️ POSTMAN</h1>
<h5>Postman es una herramienta que permite a los desarrolladores probar y realizar solicitudes HTTP a diferentes servicios web de manera eficiente. Proporciona una interfaz gráfica de usuario que permite crear, enviar y recibir solicitudes HTTP, lo que facilita la prueba de APIs y servicios web.</h5>
<img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcStEPuNp2MeCOShopz-Zpm4FGdX0AklMN20DA&usqp=CAU  
	 alt="Descripción de la imagen">
<h5>En esta introducción, nos centraremos en la implementación de un controlador para una API de CATS (gatos) utilizando Nest.js. Nuestra API permitirá realizar operaciones de consulta (GET), creación (POST), actualización (PUT) y eliminación (DELETE) de registros de gatos. Para probar y consumir nuestra API, utilizaremos Postman, una herramienta ampliamente conocida para realizar solicitudes HTTP y probar APIs.</h5>

<h5>comandos para iniciar el proyecto</h5>
 ```javascript
$  nest g controller cats
```

 ```javascript
//configuracion 
$  npm i -g @nestjs/cli 

$  nest new project-name
```

 ```javascript
//iniciar el proyecto
$  npm run start:dev
```

<h5>Luego de iniciar el proyecto en el controller y escribimos el   get, post, put y delete  </h5>

<img src="C:\Users\Francisco\Pictures\cat1.jpeg"  alt="Descripción de la imagen">

<h5>Despues iniciar el proyecto probamos en el postman cada uno de ellos con localhost:3000/cats   </h5>
<h8>GET  </h8>

<img src="C:\Users\Francisco\Pictures\cat2.jpeg" alt="Descripción de la imagen">				

<h8>POST  </h8>
<img src="C:\Users\Francisco\Pictures\cat3.jpeg" alt="Descripción de la imagen">

<h8>PUT  </h8>
<img src="C:\Users\Francisco\Pictures\cat4.jpeg" alt="Descripción de la imagen">

<h8>DELETE  </h8>
<img src="C:\Users\Francisco\Pictures\cat5.jpeg" alt="Descripción de la imagen">

<h5>Finalmente se probo y puedo observar el funcionamiento de cada uno de ellos. </h5>


creature


<h5>Ahora probaremos otro ejemplo, nos centraremos en la implementación de un controlador para una API de CREATURES (criaturas) utilizando Nest.js. Nuestra API permitirá realizar operaciones de consulta (GET), creación (POST), actualización parcial (PATCH) y eliminación (DELETE) de registros de criaturas. Para probar y consumir nuestra API, utilizaremos Postman, una herramienta ampliamente conocida para realizar solicitudes HTTP y probar APIs. </h5>

<h5>Comandos para iniciar este proyecto. </h5>
 ```javascript
$  nest generate controller creatures
```

 ```javascript
//configuracion 
$  npm i -g @nestjs/cli 

$  nest new project-name
```

 ```javascript
//iniciar el proyecto
$  npm run start:dev
```

<h5>En este proyecto ya viene con  get, post, patch y delete  </h5>

<img src="C:\Users\Francisco\Pictures\creature1.jpeg" alt="Descripción de la imagen">


<h5>Despues iniciar el proyecto probamos en el postman cada uno de ellos con localhost:3000/creatures   </h5>
<h8>GET  </h8>
<img src="C:\Users\Francisco\Pictures\creature2.jpeg" alt="Descripción de la imagen">

<h8>POST  </h8>
<img src="C:\Users\Francisco\Pictures\creature3.jpeg" alt="Descripción de la imagen">

<h8>PATCH  </h8>
<img src="C:\Users\Francisco\Pictures\creature4.jpeg" alt="Descripción de la imagen">


<h8>DELETE  </h8>
<img src="C:\Users\Francisco\Pictures\creature5.jpeg" alt="Descripción de la imagen">

<h5>Finalmente se pudo ver el funcionamiento de cada uno de ellos en el postman </h5>

<h1>✔️ IA dev -GPT</h1>



<h5>Primero ingresamos a la pagina de OpenAI.com </h5>

<img src="C:\Users\Francisco\Pictures\IA 1.jpeg" alt="Descripción de la imagen">

<h5>Luego de entrar al menu y a la API generamos una clave en API Keys y la copiamos ya que solo se puede guardar una sola vez  </h5>
<img src= "C:\Users\Francisco\Pictures\IA 2.jpeg"alt="Descripción de la imagen">

<h5>Luego descargamos repositorio un proyecto personalizado de IA y pegamos la contraseña generada anteriormente  </h5>

<img src= "C:\Users\Francisco\Pictures\IA 3.jpeg" alt="Descripción de la imagen">

<h5>Después  en la parte inferior derecha abrimos y aparecerá la IA para realizar preguntas con un cierto limite ya hay limite para usar el mismo   </h5>
<img src= "C:\Users\Francisco\Pictures\IA 4.jpeg" alt="Descripción de la imagen">


<h1>✔️ NODE HTTP framework</h1>
<h5>Node.js no es un "framework HTTP" específico, sino una plataforma que permite crear servidores web y aplicaciones web utilizando su módulo HTTP nativo o combinándolo con otros frameworks y bibliotecas. Dentro existen dos que son las mas usadas:  </h5>
<img src=https://www.mindinventory.com/blog/wp-content/uploads/2022/10/14-nodejs-frameworks.png alt="Descripción de la imagen">


<h1>✔️ EXPRESS</h1>
<ul>
<li> Framework web de Node.js ampliamente utilizado y establecido.</li>
<li>Enfoque en la simplicidad y facilidad de uso.</li>
<li>Ideal para proyectos pequeños o medianos y desarrolladores principiantes.</li>
<li>Tiene una gran comunidad y muchos complementos disponibles.</li>
</ul>
<img src=https://res.cloudinary.com/practicaldev/image/fetch/s--rQS9VcWG--/c_imagga_scale,f_auto,fl_progressive,h_720,q_auto,w_1280/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/zojuy79lo3fn3qdt7g6p.png alt="Descripción de la imagen">

<h1>✔️ FASTIFY</h1>
<ul>
<li> Framework web de Node.js enfocado en el rendimiento y la eficiencia.</li>
<li> Es extremadamente rápido y adecuado para aplicaciones de alta concurrencia</li>
<li> Utiliza una arquitectura basada en la asincronía y Node.js Streams.</li>
<li> Ideal para aplicaciones de alto rendimiento y APIs con muchas solicitudes simultáneas.</li>
</ul>


<img src=https://miro.medium.com/v2/resize:fit:1400/1*1zQxQ0H8iAVAVZyhMJ0egA.png alt="Descripción de la imagen">






























































































