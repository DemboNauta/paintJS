![image](https://github.com/user-attachments/assets/1b206a36-bc7c-4a49-8b7c-135e823f782d)

# Paint.js
## Descripción General
  Paint.js es una aplicación web sencilla que emula algunas de las funcionalidades básicas de un software de pintura tradicional. La aplicación permite a los usuarios dibujar, borrar, y crear formas como rectángulos y elipses. También incluye un selector de color para elegir colores de dibujo y una herramienta cuentagotas para capturar colores directamente desde el lienzo.

## Características
  Herramienta de Dibujo: Permite dibujar a mano alzada sobre el lienzo.
  Herramienta de Borrado: Borra partes del dibujo actual.
  Herramienta de Rectángulo: Dibuja rectángulos en el lienzo.
  Herramienta de Elipse: Dibuja elipses en el lienzo.
  Selector de Color: Permite elegir el color con el que se dibuja.
  Cuentagotas: Captura y utiliza cualquier color presente en el lienzo.
  Limpiar Lienzo: Limpia todo el contenido del lienzo para empezar desde cero.
  
## Tecnologías Utilizadas

  HTML5: Se utiliza para estructurar la interfaz de usuario, incluyendo el lienzo donde se realizan los dibujos.
  
  CSS3: Se encarga del estilo visual de la aplicación, utilizando técnicas como el modelo de cajas, el sistema de grid, y la pseudoclase :hover para interacciones con los botones.
  
  JavaScript (ES6+): Controla la lógica del lienzo y las interacciones del usuario con las herramientas de dibujo. Se emplea el contexto 2D del elemento <canvas> para las operaciones de dibujo.
  
  Canvas API: Proporciona las herramientas necesarias para dibujar, borrar, y manipular gráficos en el lienzo.
  
  EyeDropper API: Una API nativa de JavaScript utilizada para implementar la funcionalidad de cuentagotas que permite capturar colores desde el lienzo.
  
## Estructura del Proyecto
  index.html: El archivo HTML principal que contiene la estructura de la aplicación.
  styles.css: Define los estilos y diseño visual de la aplicación.
  script.js: Contiene la lógica de la aplicación, gestionando eventos de usuario y manipulaciones del lienzo.
  /icons/: Carpeta que almacena los íconos utilizados en los botones de la aplicación.
  /cursors/: Carpeta que almacena las imágenes de los cursores personalizados.
