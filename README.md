# SM2_EXAMEN_PRACTICO

1. Descripción del Proyecto, breve con las funcionalidades implementadas (2 historias). 

# Descripcion del Proyecto
El propósito de este proyecto es desarrollar una aplicación móvil que facilite a los turistas en Tacna la búsqueda y selección de los mejores restaurantes locales. Utilizando Flutter y Firebase para la gestión de datos en tiempo real, la aplicación ofrecerá un mapa interactivo con opciones filtradas por tipo de cocina y recomendaciones personalizadas basadas en el presupuesto del usuario. La integración de inteligencia artificial permitirá personalizar las sugerencias gastronómicas y optimizar la experiencia culinaria del usuario. 

#Descripcion de Funcionalidades Implementadas (2 Historias):

1. **Registro y Gestión de Productos de un Negocio:**
- Como administrador, ahora es posible registrar, editar y eliminar Productos dentro de la aplicación.
- El proceso incluye la captura de datos como nombre del producto, descripcion Breve,Precio, Stock,categoria,Estado y subir una imagen.
- Además, se implementó una validación de los datos ingresados para asegurar que la información sea correcta y esté completa antes de ser registrada en la base de datos.
  
   - **Características**:
     - El administrador puede agregar Productos, ingresando información relevante.
     - Se permite la edición y eliminación de registros existentes.
     - Validación de datos para garantizar que todos los campos sean correctos antes de guardar la información.
     - Interfaz de usuario sencilla y clara para facilitar la gestión de Productos.
     - Mensajes de error informativos en caso de que los datos ingresados no sean correctos.

2. **Gestion y Registro de las Cartas asignada a un Negocio:**
   
Para esta historia ,como administrador podremos actualizar las cartas de un negocio dentro de nuestro aplicativo.
Este proceso incluye la captura de datos como agregar Productos a una carta,Subir y seleccionar una Imagen de Fondo y color de Texto.Además de Previsualizar la carta:

Se implementó una validación de los datos ingresados para asegurar que la información sea correcta y esté completa antes de ser registrada en la base de datos.

Características:
El administrador puede agregar nuevas cartas, ingresando información relevante sobre la carta del restaurante.
Se permite la edición y eliminación de cartas existentes asignadas a los restaurantes.
Validación de los datos para garantizar que todos los campos sean correctos antes de guardar la información.
Interfaz de usuario sencilla y clara para facilitar la gestión de las cartas y su asignación a los negocios.
Mensajes de error informativos en caso de que los datos ingresados no sean correctos o estén incompletos.
Asignación fácil de cada carta a un restaurante específico dentro del sistema.

2.Capturas de imágenes del APP de las 2 funcionaliades

# **Registro y Gestión de Productos de un Negocio:**

![image](https://github.com/user-attachments/assets/1358a36c-5280-4436-ae1a-a1e98c39e3bb)

![image](https://github.com/user-attachments/assets/ab097014-c40d-4f39-b61b-ff83581abbe8)

![image](https://github.com/user-attachments/assets/8db2cf95-0ad9-4fba-ba8f-671a79e10d20)

# **Gestion y Registro de las Cartas asignada a un Negocio:**

![image](https://github.com/user-attachments/assets/dc0da006-97d8-4d83-a044-a88372d7bf67)


3.Enlaces y Referencias: Si has utilizado recursos externos (librerías, APIs, etc.), menciona los enlaces o referencias.

Flutter:
La aplicación está construida con Flutter, un framework de desarrollo de aplicaciones móviles de Google. Permite crear aplicaciones nativas para iOS y Android desde una única base de código.
Enlace: https://flutter.dev/

Firebase:
Firebase se utiliza para la gestión de bases de datos en tiempo real, autenticación de usuarios y almacenamiento de imágenes.
Enlace: https://firebase.google.com/

Cloud Firestore:
Se utilizo Cloud Firestore de Firebase para almacenar los datos de restaurantes, cartas, productos y usuarios en tiempo real, permitiendo actualizaciones dinámicas y rápidas en la aplicación.
Enlace: https://firebase.google.com/docs/firestore

Flutter Provider:
Se utiliza el paquete Provider para la gestión de estado de la aplicación, facilitando el manejo de datos globales y la actualización eficiente de la UI.
Enlace: https://pub.dev/packages/provider

Flutter Image Picker:
La librería image_picker se utiliza para permitir a los administradores subir imágenes de los productos o cartas desde la galería del dispositivo o mediante la cámara.
Enlace: https://pub.dev/packages/image_picker

Flutter Validation:
Para validar los datos de entrada de los formularios, se utiliza un conjunto de validaciones personalizadas basadas en el paquete form_field_validator.
Enlace: https://pub.dev/packages/form_field_validator

FontAwesome Flutter:
Se usa la librería FontAwesome para incluir iconos de alta calidad en la interfaz de usuario de la aplicación.
Enlace: https://pub.dev/packages/font_awesome_flutter

Dart:
Dart es el lenguaje de programación utilizado para escribir la lógica de la aplicación junto con Flutter.
Enlace: https://dart.dev/
 

