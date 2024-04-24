<!DOCTYPE html>
<html>
   <head>
   </head>
   <body>
      <header>
         <h1>Test BCI</h1>
      </header>
         <h2>introducción</h2>
         <p>Vamos a tener diferentes micros servicios que se van a comunicar entre sí para poder realizar todo lo requerido.El proceso de autenticación con Spring Clood Security utilizando OAuth2.
         Por un lado vamos a tener el servicio usuarios que se encarga solamente de gestionar a los usuario con sus roles para poder crear actualizar y eliminar, buscar por ejemplo por el user name para el proceso de logín de Autenticación.
         Vamos a tener por otra parte un servicio de Autorización encargado de generar el tóken y autenticar al usuario donde el usuario envía sus credenciales el "User Name" el "Password" y ademas el "ClientId" con el "Código Secreto".Si todo sale correcto y existe el   
         usuario con sus credenciales genera el toque y lo devuelve dentro de un Json cubriendo así un requerimiento vital para resolver este test.</p>
          <h2>Arquitectura Microservicios</h2>
        <p>(https://github.com/GaedoC/TestBCI/assets/17816969/0ff4e3b3-6a63-460d-ad46-06d0299ce550)</p>
         <h2>Modelo de datos</h2>
        <p>(https://github.com/GaedoC/TestBCI/assets/17816969/0ff4e3b3-6a63-460d-ad46-06d0299ce550)</p>
         <h2>Tecnología a utilizar</h2>
        <p></p>
      <footer>
      </footer>
   </body>
</html>
