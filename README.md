Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web.

1.- Introducción al desarrollo web  
Historia y evolución del desarrollo web  
**Respuesta:**  
El desarrollo web inició en los años 90 con la creación de la World Wide Web por Tim Berners-Lee. Inicialmente, las páginas eran estáticas y solo contenían texto y enlaces. Con el tiempo, surgieron tecnologías como JavaScript y CSS que permitieron páginas más interactivas. El desarrollo web ha evolucionado hacia aplicaciones dinámicas, SPA (Single Page Applications) y PWA (Progressive Web Apps), buscando mejorar la experiencia de usuario y el rendimiento.

Tipos de aplicaciones web (estáticas, dinámicas, SPA, PWA)  
**Respuesta:**  
- **Estáticas:** Solo muestran contenido fijo, no interactúan con bases de datos (ejemplo: portafolio personal).  
- **Dinámicas:** El contenido cambia según la interacción o datos del usuario, requieren backend (ejemplo: foros, blogs).  
- **SPA:** Toda la interacción ocurre en una sola página, cargando datos dinámicamente sin recargar (ejemplo: Gmail).  
- **PWA:** Aplicaciones web que ofrecen experiencia similar a apps nativas, pueden funcionar offline y enviando notificaciones (ejemplo: Twitter Lite).

2.- Arquitectura de aplicaciones web  
Cliente-Servidor  
**Respuesta:**  
El modelo cliente-servidor divide la aplicación en dos partes: el cliente, que solicita servicios o recursos, y el servidor, que responde a esas solicitudes. El navegador web es el cliente y el servidor aloja la aplicación, procesa datos y responde.

Arquitectura de tres capas (presentación, lógica, datos)  
**Respuesta:**  
- **Presentación:** Interfaz de usuario, lo que ve el usuario (HTML, CSS, JS).  
- **Lógica:** Procesa datos y reglas de negocio (backend).  
- **Datos:** Maneja el almacenamiento y recuperación de información (base de datos).

REST y API-first design  
**Respuesta:**  
REST es un estilo de arquitectura para diseñar servicios web que usan HTTP y recursos como URLs. API-first significa diseñar primero la interfaz de programación antes de desarrollar la aplicación, asegurando que otros servicios puedan interactuar fácilmente.

3.- Lenguajes y tecnologías fundamentales  
HTML, CSS, JavaScript, PHP, MySQL  
**Respuesta:**  
- **HTML:** Estructura de la página web.  
- **CSS:** Diseño y estilos visuales.  
- **JavaScript:** Interactividad y lógica en el navegador.  
- **PHP:** Lenguaje de backend para procesar datos y generar contenido dinámico.  
- **MySQL:** Sistema de gestión de bases de datos relacional, almacena información.

4.- Control de versiones  
Git y GitHub  
**Respuesta:**  
Git es una herramienta para controlar versiones de código, permitiendo guardar cambios y colaborar. GitHub es una plataforma online donde se alojan repositorios Git para compartir y trabajar en proyectos.

Flujo de trabajo con ramas (branching, merge, pull requests)  
**Respuesta:**  
- **Branching:** Crear una rama para desarrollar nuevas funcionalidades sin afectar el código principal.  
- **Merge:** Unir los cambios de una rama al código principal.  
- **Pull requests:** Solicitud para que otros revisen y aprueben las modificaciones antes de integrarlas.

---

Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web

1.- Diseño e implementación del frontend  
Maquetación/Wireframe/Mockup  
**Respuesta:**  
La maquetación consiste en organizar los elementos de la página. Wireframes son bosquejos básicos y mockups incluyen detalles visuales. Estas herramientas ayudan a planificar el diseño antes de programar.

API  
**Respuesta:**  
El frontend se comunica con el backend a través de APIs, enviando solicitudes y recibiendo datos para mostrar en la interfaz.

2.- Diseño e implementación del backend  
Servidor  
**Respuesta:**  
El servidor ejecuta el código backend, responde a solicitudes, procesa datos y comunica con la base de datos.

Manejo de peticiones y respuestas HTTP  
**Respuesta:**  
El backend recibe peticiones (GET, POST, PUT, DELETE), procesa la información y envía respuestas al cliente.

Conexión a bases de datos (MySQL, PostgreSQL, MongoDB)  
**Respuesta:**  
El backend usa drivers o ORM para conectar y realizar consultas a bases de datos como MySQL (relacional), PostgreSQL (relacional avanzada) y MongoDB (NoSQL).

3.- Bases de datos  
Modelado de datos y relaciones  
**Respuesta:**  
El modelado organiza los datos en tablas y define relaciones entre ellas (uno a uno, uno a muchos, muchos a muchos).

ORM (Object Relational Mapping)  
**Respuesta:**  
ORM permite interactuar con bases de datos usando objetos en el lenguaje de programación, facilitando consultas y manipulación de datos (ejemplo: Sequelize, SQLAlchemy).

CRUD desde el backend  
**Respuesta:**  
CRUD significa Crear, Leer, Actualizar y Borrar datos usando el backend. Se implementa mediante rutas y controladores en el servidor.

4.- Seguridad básica en aplicaciones web  
Validación de formularios  
**Respuesta:**  
Verifica que los datos ingresados por el usuario sean correctos antes de enviarlos al backend, evitando errores y ataques.

Autenticación y autorización  
**Respuesta:**  
Autenticación confirma la identidad del usuario (login), autorización verifica qué acciones puede realizar (permisos).

---

Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional

1.- Integración de frontend y backend  
Interfaz de usuario Frontend  
**Respuesta:**  
El usuario interactúa con la interfaz gráfica, que muestra datos recibidos del backend y envía solicitudes mediante formularios o botones.

Manejo de API  
**Respuesta:**  
El frontend envía solicitudes a la API y recibe respuestas para mostrar información dinámica.

Proceso de Solicitud y Respuesta de Backend  
**Respuesta:**  
El backend recibe la solicitud, procesa la lógica, accede a la base de datos si es necesario y responde con los datos solicitados.

2.- Almacenamiento en Servidor  
Tipos de servidores  
**Respuesta:**  
- **Servidor compartido:** Varios sitios en un mismo servidor.  
- **Servidor dedicado:** Exclusivo para una aplicación.  
- **Servidor en la nube:** Recursos escalables y flexibles (ejemplo: AWS, Azure).

Servidores y servicios de hosting  
**Respuesta:**  
Hosting es el servicio que permite publicar la aplicación en internet, puede ser compartido, dedicado o en la nube.

Proveedores de Servicios de Almacenamiento  
**Respuesta:**  
Ejemplos: Amazon Web Services (AWS), Google Cloud Platform, Microsoft Azure, Digital Ocean.

3.- Optimización y rendimiento  
Optimización de recursos (imágenes, scripts)  
**Respuesta:**  
Reducir el tamaño de imágenes, minificar scripts y estilos, usar caché para mejorar velocidad de carga.

Despliegue de aplicaciones web  
**Respuesta:**  
Publicar la aplicación en un servidor o plataforma online, asegurando que esté accesible para los usuarios.

CI/CD básico  
**Respuesta:**  
CI/CD automatiza pruebas y despliegues, permitiendo integrar cambios de código y publicar nuevas versiones fácilmente.

Documentación del proyecto  
**Respuesta:**  
Describir en archivos como README.md el objetivo, instalación, uso y detalles técnicos para facilitar la colaboración y mantenimiento.
