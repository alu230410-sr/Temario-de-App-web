# Temario-de-App-web
Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web.  
1.-Introducción al desarrollo web  
Historia y evolución del desarrollo web  
Tipos de aplicaciones web (estáticas, dinámicas, SPA, PWA)  
2.Arquitectura de aplicaciones web  
Cliente-Servidor  
Arquitectura de tres capas (presentación, lógica, datos)  
REST y API-first design  
3. -Lenguajes y tecnologías fundamentales  
HTML, CSS, JavaScript, PHP, MySQL  
4.-Control de versiones  
Git y GitHub  
Flujo de trabajo con ramas (branching, merge, pull requests)  

Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web   
1.-Diseño e implementación del frontend  
Maquetación/Wireframe/Mockup  
API  
**Maquetación:**  
  Es el proceso de estructurar visualmente la información y los elementos de la interfaz en una página web. Se suele hacer usando HTML y CSS, y define la disposición de menús, botones, formularios, imágenes, etc.  
  - Herramientas comunes: HTML, CSS (Flexbox, Grid), Bootstrap, Tailwind.  

- **Wireframe:**  
  Esquema básico (boceto) que representa la estructura de las páginas antes del diseño final. Se centra en la funcionalidad y organización, no en los colores ni estilos.  
  - Herramientas: Figma, Balsamiq, Adobe XD, papel y lápiz.  
  - Utilidad: Facilita la comunicación entre desarrolladores y diseñadores, permite definir y validar la experiencia de usuario (UX).  

- **Mockup:**   
  Representación visual más detallada del producto final. Incluye estilos, colores, tipografía y elementos gráficos, mostrando cómo se verá antes de codificarlo.  
  - Herramientas: Figma, Adobe XD, Sketch, Photoshop.  
  - Utilidad: Permite validar el aspecto visual y realizar ajustes antes de la implementación.  

---

### API  

- **Definición:**  
  Una API (Interfaz de Programación de Aplicaciones) conecta el frontend con el backend, permitiendo que la web obtenga y envíe datos dinámicamente.  
  - Tipos comunes: RESTful APIs (JSON), GraphQL.  
  - Métodos HTTP: GET (consultar datos), POST (crear), PUT/PATCH (actualizar), DELETE (eliminar).  
  - Buenas prácticas: Validar datos, gestionar errores, proteger con autenticación (tokens).  
  - 
2.-Diseño e implementación del backend  
Servidor  
Manejo de peticiones y respuestas HTTP  
Conexión a bases de datos (MySQL, PostgreSQL, MongoDB)
**Servidor:**    
  El servidor es el componente encargado de recibir las peticiones del cliente (navegador o app) y devolver respuestas, como páginas web, archivos o datos. Puede estar desarrollado en distintos lenguajes (Node.js, PHP, Python, Java, etc.). Se encarga de la lógica del negocio y gestiona la comunicación con la base de datos y otros servicios.  

- **Manejo de peticiones y respuestas HTTP:**  
  El backend recibe solicitudes (requests) a través del protocolo HTTP y responde con datos, páginas o mensajes. Cada petición tiene un método (GET, POST, PUT, DELETE) y puede incluir parámetros, cabeceras y cuerpo. El servidor procesa la petición, realiza las acciones necesarias (consultar datos, guardar información, etc.) y envía una respuesta (response) con el código de estado (200 OK, 404 Not Found, 500 Error), datos o mensajes.  

- **Conexión a bases de datos (MySQL, PostgreSQL, MongoDB):**    
  El backend se conecta a bases de datos para almacenar y recuperar información.  
  - **MySQL** y **PostgreSQL** son bases de datos relacionales: almacenan datos en tablas con relaciones entre ellas. Se usan consultas SQL para interactuar con los datos.  
  - **MongoDB** es una base de datos NoSQL: almacena datos en documentos tipo JSON, permitiendo mayor flexibilidad y escalabilidad.    
  El backend utiliza librerías o frameworks para establecer la conexión, realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) y asegurar la consistencia y seguridad de los datos.   
3.-Bases de datos  
 Modelado de datos y relaciones  
ORM (Object Relational Mapping)  
CRUD desde el backend  
4.-Seguridad básica en aplicaciones web  
Validación de formularios  
Autenticación y autorización   

Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional  
1. -Integración de frontend y backend  
Interfaz de usuario Frontend  
Manejo de API  
Proceso de Solicitud y Respuesta de Backend  

2.- Almacenamiento en Servidor  
Tipos de servidores   
Servidores y servicios de hosting   
Proveedores de Servicios de Almacenamiento  

3.-Optimización y rendimiento  
Optimización de recursos (imágenes, scripts)  
Despliegue de aplicaciones web  
CI/CD básico  
Documentación del proyecto  
