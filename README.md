============================================================
                SOLARIS PERUVIAN STYLE
============================================================

1. DESCRIPCIÓN DEL PROYECTO
---------------------------
Solaris Peruvian es una aplicación web profesional de arquitectura
cliente-servidor. El proyecto presenta una interfaz moderna y 
dinámica para la marca, integrando recursos multimedia de alta 
calidad y un servidor basado en Node.js.

2. ESTRUCTURA DE ARCHIVOS
-------------------------
La carpeta principal "Web Soleil Style" se organiza de la siguiente manera:

/public             -> Carpeta raíz del servidor estático.
   /assets          -> Recursos visuales y lógicos.
      /css          -> Estilos globales (estilos.css).
      /fonts        -> Tipografías (Poppins, Yeseva, Questrial, etc.).
      /img          -> Imágenes de productos, portadas y equipo.
      /js           -> Interactividad del cliente (script.js).
      /video        -> Contenido multimedia (VIDEOPORTADA.mp4).
   /index.html      -> Página de inicio.
   /nosotros.html   -> Historia y equipo de la marca.
   /productos.html  -> Catálogo de productos.
   /contactos.html  -> Formulario de contacto.
   /libro-reclamaciones.html -> Cumplimiento legal y atención al cliente.

server.js           -> Servidor backend (Node.js + Express).
package.json        -> Configuración de dependencias y scripts.
.gitignore          -> Archivos excluidos del repositorio (node_modules).

3. REQUISITOS PREVIOS
---------------------
- Node.js instalado (versión 14 o superior).
- Un gestor de paquetes como NPM (incluido con Node.js).

4. INSTRUCCIONES DE INSTALACIÓN Y EJECUCIÓN
-------------------------------------------
Para ejecutar este proyecto en su entorno local, siga estos pasos:

Paso 1: Abra una terminal en la carpeta raíz del proyecto.
Paso 2: Ejecute el comando para instalar las dependencias:
        > npm install

Paso 3: Inicie el servidor de Node.js:
        > node server.js

Paso 4: Abra su navegador y acceda a la siguiente dirección:
        http://localhost:3000

5. TECNOLOGÍAS UTILIZADAS
-------------------------
- Backend: Node.js, Express Framework.
- Frontend: HTML5, CSS3 (Custom Fonts), JavaScript.
- Control de Versiones: Git & GitHub.

6. CRÉDITOS
-----------
Desarrollado por: 
Fecha: Mayo 2026
============================================================
