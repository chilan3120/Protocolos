# ToCupboard Website - DevSecOps

Este repositorio contiene todos los archivos y documentación relacionados con el desarrollo del sitio web de ToCupboard, utilizando WordPress y aplicando el modelo DevSecOps.

## Contenido del Repositorio

- **wordpress.zip**: Este archivo comprimido contiene todos los archivos del sitio web, incluyendo el tema personalizado, plugins, y configuraciones de seguridad.
  - **Contenido del archivo ZIP**:
    - Archivos de WordPress: Incluye el tema Astra personalizado para ToCupboard.
    - Plugins de seguridad: Wordfence y otros plugins de seguridad configurados.
    - Certificado SSL: Configuración HTTPS para una conexión segura. "Hecho a medias, tuve algunos errores y no pude culminarlo"
    - Simulación de pasarela de pagos: Proceso de pago simulado utilizando métodos seguros.

## Instrucciones para Revisar y Ejecutar el Sitio Web

### 1. Configuración Local

1. **Descargar el archivo ZIP**:
   - Descarga el archivo `wordpress.zip` desde el repositorio.

2. **Descomprimir el archivo**:
   - Extrae el contenido del archivo ZIP en tu servidor local (por ejemplo, en la carpeta `htdocs` de XAMPP).

3. **Configurar la base de datos**:
   - Crea una base de datos en tu entorno local (MySQL).
   - Importa la base de datos incluida en el archivo ZIP, si está presente, o configura una nueva instalación de WordPress utilizando los archivos.

4. **Configurar `wp-config.php`**:
   - Asegúrate de que el archivo `wp-config.php` contiene la información correcta de la base de datos y otros detalles de configuración.

5. **Acceder al sitio**:
   - Inicia el servidor local y accede al sitio a través de `http://localhost/tu-directorio`.

### 2. Integración de API

- Por falta de tiempo no pude hacer la integración de API

### 3. Simulación de Pasarela de Pagos

- Se ha configurado una simulación de pasarela de pagos, utilizando un entorno seguro de prueba (como el modo de prueba de PayPal). Sigue los pasos dentro del sitio para probar el flujo de compra.

## Prácticas de Seguridad Implementadas

- **Actualizaciones Automáticas**: WordPress y los plugins están configurados para recibir actualizaciones automáticas.
- **Seguridad del Sitio**: Wordfence y otros plugins de seguridad están instalados y configurados para proteger el sitio contra amenazas.
- **HTTPS**: El sitio está configurado para utilizar HTTPS, asegurando una conexión segura para los usuarios. "No lo utiliza como tal porque me da muhcos errores"


![Captura de pantalla 2024-09-06 025925](https://github.com/user-attachments/assets/232064ef-7fa6-4571-af59-187bd2187c32)
