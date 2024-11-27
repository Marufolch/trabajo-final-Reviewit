# trabajo-final-Reviewit
##################### README ######################################

Propósito de la Aplicación Reviewit ofrece una solución intuitiva para descubrir y evaluar locales gastronómicos. Los usuarios pueden
visualizar una lista de los locales más populares, ver sus reseñas, y guardar sus favoritos para futuras referencias. La aplicación se 
centra en brindar una interfaz amigable y funcional, similar esteticamente al sistema de gestión de pedidos propuesto por el docente.

################### Instalacion y ejecucion de la aplicacion:

1 - Abre tu navegador web y ve a la página principal de GitHub.
2 - Descarga el archivo zip del repositorio.

    2.1    Haz clic en el botón "Code" (Código) que se encuentra en la parte superior derecha de la página del repositorio (frame verde).
    2.2    En el menú desplegable, selecciona "Download ZIP" (Descargar ZIP).
    2.3    Guarda el archivo ZIP en tu computadora en la ubicación que prefieras.

3 - Descomprime el archivo ZIP haciendo clic derecho sobre él y seleccionando "Extraer aquí" o "Descomprimir aquí".
4 - Acceder al Directorio de la carpeta de descarga, ingresar a la carpeta "dist"(ubicacion de descarga\final\dist)
5 - Iniciar la Aplicación mediante la ejecucion del archivo "reviewit_app.exe"

#################### Uso de la Aplicación:

 ** Autenticación: Ingresa tu nombre de usuario(".") y contraseña(".") para acceder a la aplicación.

 ** Visualización de Locales: La ventana principal mostrará una lista de los restaurantes más populares con botones y casillas de 
verificación.

 ** Ver Reseñas: Haz clic en los botones para ver las reseñas de cada restaurante.

 ** Guardar Favoritos: Marca la casilla de verificación junto a los restaurantes que quieras guardar como favoritos y usa la opción 
de guardar para descargar la reseña en tu PC.

 ** Salida: Puedes cerrar la aplicación en cualquier momento cerrando la ventana principal.

################### descripcion de las funcionalidades Especiales:

### 1. **Listado de Locales Populares** 
- La ventana principal muestra un listado de los locales gastronómicos más populares, cada uno con su respectivo checkbox. 
- Los botones permiten seleccionar cada restaurante y visualizar la reseña correspondiente. 

### 2. **Guardado de Favoritos** 
- Cada botón incluye una casilla de verificación para permitir a los usuarios guardar en favoritos la información mostrada como 
un archivo de texto en la misma carpeta donde se encuentra el programa. 

### 3. **Librerías Utilizadas** 
- **os**: Manejo de archivos y directorios, acceso a las reseñas almacenadas en archivos de texto. 
- **tkinter**: Creación de interfaces gráficas de usuario (GUI) con ventanas, botones, etiquetas, cuadros de entrada, menús, etc. 

### 4. **Autenticación de Usuarios** 
- El usuario debe autenticarse con nombre y clave. 
- Validación de los datos ingresados contra la información de registro, con notificaciones en caso de errores o ingreso exitoso. 

### 5. **Visualización de Reseñas** 
- Las reseñas se almacenan en un diccionario con el nombre del local como clave. 
- Creación dinámica de botones para cada restaurante, que muestran la reseña al ser seleccionados. 

### 6. **Actualización Dinámica** 
- Actualización de la información del restaurante seleccionado en la interfaz. 
- Uso de ciclos y verificaciones para manejar la interactividad de los widgets y actualizar la descripción y calificación de los 
restaurantes. 

### 7. **Guardado de Reseñas en Favoritos** 
- Función para guardar las reseñas seleccionadas como favoritas en archivos de texto. 
- Posibilidad de agregar comentarios y puntuaciones antes de guardar. 

### 8. **Interfaz de Usuario** 
- Personalización de colores, logotipo y disposición visual. 
- Uso de frames y empacadores(grid y pack) para organizar los elementos de la interfaz.
