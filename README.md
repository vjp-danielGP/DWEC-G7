Marca.com

FRONTEND
- Interfaz visual: Botones, menús, barras de navegación, etc.
- Contenido multimedia: Imágenes, videos, GIFs, etc.
- Tecnologías principales: HTML, CSS, JS (Scripts).

BACKEND
- Base de datos: Información de resultados deportivos, plantillas, clasificaciones, etc.
- Gestor de contenido: Plataforma en la cual redactores y editores suben su contenido.
- APIs de resultados en directo: Proporciona información en tiempo real acerca de goles, tiempos, marcadores, etc.
- Tecnologías principales: MySQL, Node,js, JAVA o PHP.

MODELO CLIENTE SERVIDOR
- Petición (Request): Cuando entras a la web o pulsas sobre alguna noticia, el navegador (cliente) envia una petición al servidor utlizando el protocolo HTTPS a los servidores de Marca.
- Procesado: El servidor recibe la petición y consulta sus bases de datos para elaborar la respuesta que corresponda.
- Respuesta (Response): El servidor envía de vuelta al cliente una serie de datos, en los que se incluyen archivos HTML, CSS, JS, JSON, etc.
- Renderizado (Render): Se encarga de "dibujar" la interfaz que vemos en pantalla para que se pueda interactuar y leer en ella.

PETICIONES (DevTools)

Captura 1
- Método: GET
- Código de estado: 200 (Éxito)
- Content-Type: text/html
- Explicación: El navegador pide mediante GET la página principal o portada de marca.com,
el servidor responde con 200, pues se ha procesado correctamente. Devuelve el html de la 
página, es relevante porque a partir de esta petición se solicitan el CSS, JS, imágenes, etc.

Captura 2
- Método: GET
- Código de estado: 200 (Éxito)
- Content-Type: image/x-icon
- Explicación: El navegador solicita el archivo del favicon de la página, al funcionar correctamente, devuelve el archivo del icono y lo muestra en la barra de pestañas.