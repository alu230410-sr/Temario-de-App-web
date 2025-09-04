Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web.

1.- Introducción al desarrollo web  
Historia y evolución del desarrollo web  
 
El desarrollo web inició en los años 90 con la creación de la World Wide Web por Tim Berners-Lee. Inicialmente, las páginas eran estáticas y solo contenían texto y enlaces. Con el tiempo, surgieron tecnologías como JavaScript y CSS que permitieron páginas más interactivas. El desarrollo web ha evolucionado hacia aplicaciones dinámicas, SPA (Single Page Applications) y PWA (Progressive Web Apps), buscando mejorar la experiencia de usuario y el rendimiento.

Tipos de aplicaciones web (estáticas, dinámicas, SPA, PWA)  
  
- **Estáticas:** Solo muestran contenido fijo, no interactúan con bases de datos (ejemplo: portafolio personal).  
- **Dinámicas:** El contenido cambia según la interacción o datos del usuario, requieren backend (ejemplo: foros, blogs).  
- **SPA:** Toda la interacción ocurre en una sola página, cargando datos dinámicamente sin recargar (ejemplo: Gmail).  
- **PWA:** Aplicaciones web que ofrecen experiencia similar a apps nativas, pueden funcionar offline y enviando notificaciones (ejemplo: Twitter Lite).
- <img width="305" height="178" alt="image" src="https://github.com/user-attachments/assets/a26b03a9-2f2f-4017-b2bf-00e0e0b70b43" />


2.- Arquitectura de aplicaciones web  
Cliente-Servidor  
  
El modelo cliente-servidor divide la aplicación en dos partes: el cliente, que solicita servicios o recursos, y el servidor, que responde a esas solicitudes. El navegador web es el cliente y el servidor aloja la aplicación, procesa datos y responde.

Arquitectura de tres capas (presentación, lógica, datos)  
**Respuesta:**  
- **Presentación:** Interfaz de usuario, lo que ve el usuario (HTML, CSS, JS).  
- **Lógica:** Procesa datos y reglas de negocio (backend).  
- **Datos:** Maneja el almacenamiento y recuperación de información (base de datos).

REST y API-first design  
  
REST es un estilo de arquitectura para diseñar servicios web que usan HTTP y recursos como URLs. API-first significa diseñar primero la interfaz de programación antes de desarrollar la aplicación, asegurando que otros servicios puedan interactuar fácilmente.
<img width="270" height="172" alt="image" src="https://github.com/user-attachments/assets/8ecedf1f-52fb-417d-bc71-2a429a43bfe6" />


3.- Lenguajes y tecnologías fundamentales  
HTML, CSS, JavaScript, PHP, MySQL  
  
- **HTML:** Estructura de la página web.  
- **CSS:** Diseño y estilos visuales.  
- **JavaScript:** Interactividad y lógica en el navegador.  
- **PHP:** Lenguaje de backend para procesar datos y generar contenido dinámico.  
- **MySQL:** Sistema de gestión de bases de datos relacional, almacena información.

4.- Control de versiones  
Git y GitHub  
  
Git es una herramienta para controlar versiones de código, permitiendo guardar cambios y colaborar. GitHub es una plataforma online donde se alojan repositorios Git para compartir y trabajar en proyectos.

Flujo de trabajo con ramas (branching, merge, pull requests)  
  
- **Branching:** Crear una rama para desarrollar nuevas funcionalidades sin afectar el código principal.  
- **Merge:** Unir los cambios de una rama al código principal.  
- **Pull requests:** Solicitud para que otros revisen y aprueben las modificaciones antes de integrarlas.
- <img width="270" height="175" alt="image" src="https://github.com/user-attachments/assets/5a5c91b5-967a-4b13-bb0c-0d3b15071004" />


---

Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web

1.- Diseño e implementación del frontend  
Maquetación/Wireframe/Mockup  
 
La maquetación consiste en organizar los elementos de la página. Wireframes son bosquejos básicos y mockups incluyen detalles visuales. Estas herramientas ayudan a planificar el diseño antes de programar.

API  
  
El frontend se comunica con el backend a través de APIs, enviando solicitudes y recibiendo datos para mostrar en la interfaz.
<img width="254" height="175" alt="image" src="https://github.com/user-attachments/assets/f223ccab-cee7-489a-ba04-62391a6740b0" />


2.- Diseño e implementación del backend  
Servidor  
 
El servidor ejecuta el código backend, responde a solicitudes, procesa datos y comunica con la base de datos.

Manejo de peticiones y respuestas HTTP  
  
El backend recibe peticiones (GET, POST, PUT, DELETE), procesa la información y envía respuestas al cliente.

Conexión a bases de datos (MySQL, PostgreSQL, MongoDB)  
  
El backend usa drivers o ORM para conectar y realizar consultas a bases de datos como MySQL (relacional), PostgreSQL (relacional avanzada) y MongoDB (NoSQL).
<img width="257" height="173" alt="image" src="https://github.com/user-attachments/assets/c66fb247-e384-40f4-bf59-c9b879da910a" />


3.- Bases de datos  
Modelado de datos y relaciones  
 
El modelado organiza los datos en tablas y define relaciones entre ellas (uno a uno, uno a muchos, muchos a muchos).

ORM (Object Relational Mapping)  
  
ORM permite interactuar con bases de datos usando objetos en el lenguaje de programación, facilitando consultas y manipulación de datos (ejemplo: Sequelize, SQLAlchemy).

CRUD desde el backend  
  
CRUD significa Crear, Leer, Actualizar y Borrar datos usando el backend. Se implementa mediante rutas y controladores en el servidor.
<img width="284" height="162" alt="image" src="https://github.com/user-attachments/assets/9cf6ea03-0ea2-435d-8394-443af6c94323" />


4.- Seguridad básica en aplicaciones web  
Validación de formularios  
  
Verifica que los datos ingresados por el usuario sean correctos antes de enviarlos al backend, evitando errores y ataques.

Autenticación y autorización  
  
Autenticación confirma la identidad del usuario (login), autorización verifica qué acciones puede realizar (permisos).
<img width="304" height="193" alt="image" src="https://github.com/user-attachments/assets/fd88f1be-c28e-4774-b670-357bc5295aba" />


---

Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional

1.- Integración de frontend y backend  
Interfaz de usuario Frontend  

El usuario interactúa con la interfaz gráfica, que muestra datos recibidos del backend y envía solicitudes mediante formularios o botones.

Manejo de API  
 
El frontend envía solicitudes a la API y recibe respuestas para mostrar información dinámica.

Proceso de Solicitud y Respuesta de Backend  
  
El backend recibe la solicitud, procesa la lógica, accede a la base de datos si es necesario y responde con los datos solicitados.
<img width="301" height="187" alt="image" src="https://github.com/user-attachments/assets/487ca987-2467-4c47-b91b-2879738b5010" />


2.- Almacenamiento en Servidor  
Tipos de servidores  
  
- **Servidor compartido:** Varios sitios en un mismo servidor.  
- **Servidor dedicado:** Exclusivo para una aplicación.  
- **Servidor en la nube:** Recursos escalables y flexibles (ejemplo: AWS, Azure).

Servidores y servicios de hosting  
  
Hosting es el servicio que permite publicar la aplicación en internet, puede ser compartido, dedicado o en la nube.

Proveedores de Servicios de Almacenamiento  
 
Ejemplos: Amazon Web Services (AWS), Google Cloud Platform, Microsoft Azure, Digital Ocean.
<img width="294" height="180" alt="image" src="https://github.com/user-attachments/assets/fadf3103-82e4-4c05-bbf2-4043d3216c0f" />


3.- Optimización y rendimiento  
Optimización de recursos (imágenes, scripts)  
  
Reducir el tamaño de imágenes, minificar scripts y estilos, usar caché para mejorar velocidad de carga.

Despliegue de aplicaciones web  
  
Publicar la aplicación en un servidor o plataforma online, asegurando que esté accesible para los usuarios.

CI/CD básico  
  
CI/CD automatiza pruebas y despliegues, permitiendo integrar cambios de código y publicar nuevas versiones fácilmente.

Documentación del proyecto  
 
Describir en archivos como README.md el objetivo, instalación, uso y detalles técnicos para facilitar la colaboración y mantenimiento.
<img width="326" height="189" alt="image" src="https://github.com/user-attachments/assets/c263eded-619e-4701-9af9-345191d7eb22" />

