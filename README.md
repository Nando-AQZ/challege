# Encriptador de texto.

### Archivo html.
- Iniciando creacion del encriptador
- Primero se creo el diseño de el encriptador
- con dos secciones, (izquierda y derecha)
- seccion izquierda estaran los datos de entrada para ser en criptados.
- boton encriptar, encripta el texto ingresado.
- boton desencriptar, desencripta el texto ingresado.
- boton limpiar. limpia todo lo que esta dentro del textarea de ingreso.
- seccion derecha estaran las salidas, el texto encriptado y el boton copiar.

### Archivo Styles.
- Tiene todo lo relacionado a el estilo de el encriptador
- las imagenes usadas estan en el archivo assets.
- la responsividad esta realizada deacuerdo a los requrimientos.

### Archivo app.js
- se crearon funciones para los botones de encriptar, desencriptar, limpiar, copiar.
- en primera se verifica si el texto ingresado es o no caracter o es Mayuscula, si son entonces se enviara un mensaje de error.
- Si el texto es permitido, entonces realizara un remplazo de las letras pedidas para este challenge y los cambiara, realizando asi la encriptacion.
- al mismo tiempo habilita y deshabilita los espacios de la seccion derecha.
- el boton desencriptar realiza el mismo procedimiento pero a la inversa.
- el boton limpiar realiza una limpieza de los espacios donded estaran los textos ingresados y de salida.
- el boton copiar realizara una copia de el texto salida.
