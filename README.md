# Temario-de-Aplicaciones-Web
Temario para los fundamentos de las aplicaciones web y su creación

## Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web.  
### 1.-Introducción al desarrollo web 
 **·Historia y evolución del desarrollo web:** 
  Inicia con Tim Berners-Lee y la creacion del World Wide Web en 1989.
  Para los 90s se creo el html (lenguaje de programacion) y posteriormente le siguio JavaScript y PHP con contenido dinamico.
  La evolución continuó con la Web 2.0, enfocada en la colaboración.
  Luego con las aplicaciones web progresivas (PWAs) y diseños responsivos, adaptándose al auge de los dispositivos móviles y las plataformas de aplicaciones.  
  ![Show the image of Tim Bermers-Lee.](https://static.wikia.nocookie.net/genios-computacion-1002/images/e/e1/Fotis_2.jpg/revision/latest?cb=20171127202331&path-prefix=es)
  
**·Tipos de aplicaciones web (estáticas, dinámicas, SPA, PWA):**   
  *Estáticas:* Son sencillas, con contenido fijo en HTML y CSS, ideales para información que no cambia frecuentemente, como un portafolio personal o una página de presentación.  
  *Dinámicas:* Utilizan bases de datos para mostrar información que se actualiza constantemente.  
  *(SPA):* Cargan una única página web y la actualizan dinámicamente sin necesidad de recargarla por completo, ofreciendo una experiencia fluida como la de una aplicación nativa.  
  *(PWA):* Se pueden descargar en dispositivos y funcionar incluso sin conexión, mejorando la accesibilidad y el rendimiento.  
  
### 2.Arquitectura de aplicaciones web
  **·Cliente-Servidor:**
  modelo informático que divide las tareas entre dos tipos de componentes: clientes (que solicitan servicios o datos) y servidores (que proveen dichos servicios y datos)  
  **·Arquitectura de tres capas (presentación, lógica, datos)**
  divide una aplicación en tres niveles lógicos: la capa de presentación (interfaz de usuario), la capa de aplicación (lógica de negocio) y la capa de datos (almacenamiento de datos)  
  **·REST y API-first design**
  La arquitectura REST (Representational State Transfer) es un estilo de diseño para API que utiliza métodos HTTP (GET, POST, PUT, DELETE) para interactuar con recursos web de manera escalable y sin estado.
  El diseño API-first es una metodología de desarrollo donde las API se diseñan y construyen como el núcleo de una aplicación, antes que el código. Al priorizar las API, se aseguran de que sean un producto bien definido e intuitivo, lo que facilita la integración y el desarrollo paralelo de componentes y servicios, y a menudo se documenta mediante lenguajes como OpenAPI. 
  
### 3. -Lenguajes y tecnologías fundamentales
  *HTML*:
   lenguaje fundamental para crear páginas web. Su propósito es estructurar y dar formato al contenido de un sitio web, definiendo elementos como párrafos, imágenes, enlaces, videos y tablas, para que un navegador web pueda mostrarlos correctamente. El HTML utiliza etiquetas y atributos para organizar la información, siendo el esqueleto de cualquier página web.  
  *CSS:* 
  es un lenguaje de estilos que se utiliza para describir la presentación y el aspecto visual de documentos escritos en lenguajes de marcado como HTML. Su función principal es separar el contenido de la forma en que se muestra, permitiendo controlar aspectos como el color, la tipografía, los márgenes y la disposición general de una página web.  
  *JavaScript:*
  lenguaje de programación versátil usado principalmente para dar interactividad y contenido dinámico a las páginas web, aunque también se utiliza en el lado del servidor con Node.js. A través del navegador, JS permite manipular el contenido de una página (DOM), interactuar con el usuario mediante formularios o crear animaciones. Es fundamental para la web moderna, haciendo que las páginas sean funcionales y enriqueciendo la experiencia del usuario.  
  *PHP:*
   lenguaje de programación de código abierto para el desarrollo web del lado del servidor que permite crear sitios y aplicaciones web dinámicas e interactivas. Se ejecuta en el servidor, genera contenido dinámico, interactúa con bases de datos y puede integrarse fácilmente con HTML, CSS y JavaScript. Es gratuito, ampliamente utilizado y cuenta con una gran comunidad que proporciona soporte y documentación, lo que facilita el desarrollo y la gestión de sitios web complejos  
  *MySQL:*
   es un sistema de gestión de bases de datos relacionales (RDBMS) de código abierto que se utiliza para almacenar y gestionar grandes cantidades de datos de manera eficiente. Sirve para aplicaciones web, como sistemas de gestión de contenido (CMS) y plataformas de comercio electrónico, donde se almacena información de usuarios, productos, publicaciones y configuraciones, permitiendo a las aplicaciones acceder y manipular esta información a través de consultas en lenguaje SQL.   

### 4.-Control de versiones
  *Git:*
  sistema de control de versiones distribuido que permite rastrear y gestionar los cambios en archivos y proyectos de software, especialmente útil cuando varias personas colaboran en el mismo código. Funciona como una "máquina del tiempo" que permite a los desarrolladores crear instantáneas del proyecto (confirmaciones), revertir a versiones anteriores y trabajar en paralelo en diferentes ramas sin interferir entre sí. Su naturaleza distribuida significa que cada desarrollador tiene una copia completa del proyecto y su historial localmente, lo que facilita trabajar sin conexión y agiliza el proceso de desarrollo.  
  *GitHub:*
GitHub es una plataforma basada en la nube que aloja proyectos que usan Git, el sistema de control de versiones distribuido, permitiendo a individuos y equipos colaborar, almacenar y rastrear cambios en código y otros proyectos. Funciona como un repositorio centralizado para proyectos, facilitando el trabajo conjunto, la gestión de cambios y el lanzamiento de código de fuente abierta.  
   
  **Flujo de trabajo con ramas (branching, merge, pull requests)**  
  *Branching:*
   proceso organizado para gestionar el código fuente en un repositorio, donde cada nueva característica, corrección de errores o experimento se desarrolla en una rama aislada para mantener limpia la rama principal y facilitar la colaboración. Los desarrolladores crean ramas a partir de la rama principal, trabajan en ellas y luego las fusionan de nuevo a la rama principal a través de un proceso de revisión.  
  *Merge:*
  se refiere a la práctica de unir cambios de una rama de código a otra, especialmente la rama principal (como main o master) en sistemas de control de versiones como Git. Implica combinar el historial de commits, lo que puede requerir la resolución de conflictos si las mismas partes del código fueron modificadas en ambas ramas.  
  *Pull:*
   es un enfoque de gestión donde el trabajo se inicia únicamente en respuesta a una demanda real, como un pedido de cliente, en lugar de producir en anticipación a una demanda futura. Se basa en la filosofía Lean para reducir el desperdicio y el inventario, producir solo lo necesario y justo a tiempo, y adaptarse rápidamente a los cambios en la demanda.  
  *Request:*
  proceso que se inicia a partir de una solicitud (request), como una petición de servicio, recursos o cambio de código, y sigue una serie de pasos para ser procesada, aprobada y ejecutada. Los flujos de trabajo de solicitud pueden aplicarse en diversas áreas, desde la gestión de TI y el desarrollo de software hasta la gestión de proyectos y la automatización de tareas.  

## Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web
### 1.-Diseño e implementación del frontend
  Maquetación/Wireframe/Mockup
  API
  
### 2.-Diseño e implementación del backend
  Servidor
  Manejo de peticiones y respuestas HTTP
  Conexión a bases de datos (MySQL, PostgreSQL, MongoDB)
  
### 3.-Bases de datos
  Modelado de datos y relaciones
  ORM (Object Relational Mapping)
  CRUD desde el backend
  
### 4.-Seguridad básica en aplicaciones web
  Validación de formularios
  Autenticación y autorización 

## Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional
### 1. -Integración de frontend y backend
  *Interfaz de usuario Frontend:*
  La interfaz de usuario frontend (o el "frontend") es la parte de un sitio web o aplicación que los usuarios ven y con la que interactúan directamente. Se enfoca en la apariencia visual y la funcionalidad interactiva de la aplicación, utilizando tecnologías como HTML, CSS y JavaScript para crear la estructura, el estilo, y la interacción de los elementos visuales. Su objetivo principal es proporcionar una experiencia de usuario (UX) intuitiva, atractiva y accesible a través de cualquier dispositivo. 
  *Manejo de API:*
  implica enviar solicitudes a un servidor para obtener o enviar datos, gestionar el ciclo de vida de la API (creación, publicación, monitorización), protegerla y analizar su uso. Para interactuar con una API, se debe obtener una clave de acceso, configurar un cliente HTTP y estructurar solicitudes utilizando métodos como GET o POST, recibiendo respuestas en formatos como JSON o XML. Es fundamental gestionar los errores, documentar las API y aplicar el almacenamiento en caché para optimizar el rendimiento  
  *Proceso de Solicitud y Respuesta de Backend:*
  El proceso de solicitud y respuesta de backend es el ciclo en el que un cliente envía una solicitud al servidor de backend, que luego la procesa, interactúa con la base de datos si es necesario, y finalmente devuelve una respuesta en un formato como JSON o XML al cliente para que el usuario la vea. Este proceso implica la recepción de la solicitud, el manejo de la lógica empresarial, la validación y la recuperación o actualización de datos, culminando en la generación y envío de una respuesta al frontend para su visualización  

### 2.- Almacenamiento en Servidor
  Tipos de servidores 
  Servidores y servicios de hosting 
  Proveedores de Servicios de Almacenamiento

### 3.-Optimización y rendimiento
  Optimización de recursos (imágenes, scripts)
  Despliegue de aplicaciones web
  CI/CD básico
  Documentación del proyecto
