1. JavaScript y Node.js
JavaScript: Es el lenguaje principal que utilizamos tanto en el frontend como en el backend. Permite la interactividad en la interfaz del usuario y la lógica en el servidor.
Node.js: Es el entorno de ejecución de JavaScript en el backend. Aquí se procesa la lógica del servidor, se manejan peticiones HTTP y se conecta con la base de datos. También permite usar módulos para estructurar mejor el código.
2. Plantillas HTML
Sirven para generar vistas dinámicas que se envían al navegador del cliente. Usando motores de plantillas como EJS o Handlebars (comúnmente usados con Node.js), se pueden mezclar HTML estático con datos dinámicos provenientes del backend.
3. Tailwind CSS
Proporciona estilos CSS prediseñados mediante clases utilitarias. Se aplica directamente en las plantillas HTML, permitiendo un diseño eficiente y responsivo.
Se integra fácilmente porque no requiere configuraciones complicadas y funciona bien con el HTML generado dinámicamente.
4. Supabase
Es la base de datos de la aplicación. Supabase se comunica con el backend en Node.js para manejar operaciones como consultas y actualizaciones de datos.
Proporciona APIs que puedes usar en el servidor para autenticar usuarios, manejar datos y ejecutar funciones relacionadas con tu lógica de negocio.
Relación entre las herramientas:
El navegador del cliente envía solicitudes al servidor (Node.js).
El servidor usa JavaScript para manejar la lógica de la aplicación, recuperar datos de Supabase y procesar la información.
Los datos dinámicos se integran en plantillas HTML, que generan vistas personalizadas.
Tailwind CSS estiliza estas vistas para proporcionar una experiencia visual atractiva.
El navegador del cliente recibe las vistas generadas, junto con la interactividad manejada por JavaScript.
