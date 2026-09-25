PROYECTO: Creación de una página web responsiva con CSS y Bootstrap
CURSO: NCBTO - 2026-5CC - WADE 1000L - 3663ONL (Front-End Technologies and
       User Interface (UI) and Laboratory)
UNIVERSIDAD: Northbridge University
ESTUDIANTE: Gerardo J. Medina (GJ)
NUMERO DE ESTUDIANTE: 2507056253

DESCRIPCIÓN
-----------
Este proyecto es un sitio web de portafolio personal, compuesto por varias
páginas interconectadas, construido con HTML5, CSS propio y el framework
Bootstrap. El tema del sitio es un portafolio de desarrollador web con
proyectos ficticios de práctica. La página fue construida en Visual Studio
Code y gestionada con control de versiones (Git/GitHub). Demuestra el uso de:

1. Página de inicio (index.html):
   - Barra de navegación (navbar) de Bootstrap con tres enlaces: Inicio,
     Portafolio y Contacto.
   - Encabezado con imagen de fondo (background-image) y título.
   - Sección "Acerca de mí" con información del propietario del sitio.
   - Botón de llamado a la acción que dirige a la página de contacto.

2. Página de portafolio (portafolio.html):
   - Tarjetas (cards) de Bootstrap que resumen tres proyectos ficticios.
   - Botón "Leer más" en cada tarjeta que lleva a una página de detalle
     independiente (proyecto1.html, proyecto2.html, proyecto3.html).

3. Página de contacto (contacto.html):
   - Formulario de contacto ficticio con campos de nombre, correo
     electrónico y mensaje.
   - Validación de formularios de Bootstrap (clase "needs-validation",
     atributo "novalidate" y script de validación).
   - Información de contacto adicional (correo y teléfono ficticios).

4. Selectores CSS propios (además de los de Bootstrap):
   - De elemento (ej. body, footer).
   - De ID (ej. #menu-principal, #encabezado-hero).
   - De clase (ej. .tarjeta-perfil, .tarjeta-proyecto, .tarjeta-contacto).

5. Modelo de caja (box model): las clases propias "tarjeta-perfil",
   "tarjeta-proyecto" y "tarjeta-contacto" sobrescriben el padding, borde,
   bordes redondeados y sombra de una tarjeta normal de Bootstrap.

6. Diseño responsivo: el grid de 12 columnas de Bootstrap (row/col-md-*)
   adapta el contenido a distintos tamaños de pantalla, y se complementa
   con una media query propia (@media max-width: 576px) para el encabezado
   en celulares.

7. Personalización de estilos: tipografía propia (Google Fonts "Poppins"),
   tema oscuro (data-bs-theme="dark"), color de acento verde esmeralda, y
   efecto de elevación (hover) en las tarjetas de proyectos.

ARCHIVOS INCLUIDOS
-------------------
- index.html        -> Página de inicio.
- portafolio.html    -> Página de portafolio con las tarjetas de proyectos.
- proyecto1.html     -> Página de detalle: Tienda online de cartas Topps.
- proyecto2.html     -> Página de detalle: Estadísticas de fútbol (LaLiga y Champions).
- proyecto3.html     -> Página de detalle: Blog de tecnología (artículos de front-end).
- contacto.html      -> Página de contacto con formulario y validación.
- style.css          -> Hoja de estilos propia (selectores, modelo de caja
                         y ajustes responsivos), cargada después de Bootstrap.
- imagenes/           -> Carpeta con las imágenes del sitio (fondo del
                         encabezado y capturas de los proyectos).
- README.txt          -> Este archivo.

ENLACE DEL REPOSITORIO DE GITHUB
---------------------------------
https://github.com/medinalab3/portafolio-web-bootstrap

CÓMO VISUALIZAR EL PROYECTO
-----------------------------
1. Abrir la carpeta del proyecto en Visual Studio Code.
2. Abrir el archivo "index.html" con la extensión Live Server (Bootstrap
   se carga desde internet vía CDN, así que se necesita conexión a
   internet para ver los estilos) o directamente con el navegador de
   preferencia.
3. Navegar entre las páginas usando la barra de navegación superior.
4. Para probar el diseño responsivo, abrir las herramientas de
   desarrollador (F12), activar la vista de dispositivo móvil, o reducir
   el ancho de la ventana y observar cómo el menú se colapsa en un botón
   de hamburguesa y las tarjetas se apilan.
