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

Pagina Principal
![Captura de pantalla 2024-09-06 025452](https://github.com/user-attachments/assets/b1c11052-82d2-4e79-b932-4b5c2af00777)
![Captura de pantalla 2024-09-06 025500](https://github.com/user-attachments/assets/6bd4b910-cc1f-40ea-ad33-32e1804f9508)
![Captura de pantalla 2024-09-06 025507](https://github.com/user-attachments/assets/ab17ae08-c4f7-4f8e-bdb2-dfe8925d3460)
![Captura de pantalla 2024-09-06 025512](https://github.com/user-attachments/assets/04a11914-4e9d-440c-9255-37da8d369627)
![Captura de pantalla 2024-09-06 025517](https://github.com/user-attachments/assets/69f8b622-9dc6-448d-906a-f36caa76a08a)
![Captura de pantalla 2024-09-06 025527](https://github.com/user-attachments/assets/eaf4a676-6f6d-4599-813b-dee59289edb3)
![Captura de pantalla 2024-09-06 025532](https://github.com/user-attachments/assets/5be40332-7d99-4ebb-9bca-a5917ead32cc)

Tienda
![Captura de pantalla 2024-09-06 025556](https://github.com/user-attachments/assets/ae6a648f-ed7c-42cd-a47b-d686634ffa03)
![Captura de pantalla 2024-09-06 025606](https://github.com/user-attachments/assets/e961ef89-3154-4ef4-bf0b-044860fbf7f2)

Comprando
![Captura de pantalla 2024-09-06 025621](https://github.com/user-attachments/assets/06e1ec38-b719-4a20-beb7-af6342d3e165)
![Captura de pantalla 2024-09-06 025633](https://github.com/user-attachments/assets/5e122393-bef8-4f91-ac05-2040dc982770)

Carrito
![Captura de pantalla 2024-09-06 025642](https://github.com/user-attachments/assets/7174a1a8-c80f-4909-8bc6-6e4831ac3ed1)
![Captura de pantalla 2024-09-06 025647](https://github.com/user-attachments/assets/82434510-2aad-4076-a3fd-ec43869d1853)

Checkout - Paypal
![Captura de pantalla 2024-09-06 025659](https://github.com/user-attachments/assets/ebd0ec8f-611f-400b-99d9-72ceacd38ec6)
![Captura de pantalla 2024-09-06 025704](https://github.com/user-attachments/assets/137f863a-63cc-4f2e-93e3-9503e4549ae3)
![Captura de pantalla 2024-09-05 200133](https://github.com/user-attachments/assets/ab9bf2ec-e2dc-4427-b442-edaf2b431ac3)
![Captura de pantalla 2024-09-06 025738](https://github.com/user-attachments/assets/579e17b1-6ba3-4567-aca8-612f7c656f21)

Checkout - Tranferencia bancaraia directa 
![Captura de pantalla 2024-09-06 025817](https://github.com/user-attachments/assets/b20851fa-0420-4aab-82bc-5693fb0be751)
![Captura de pantalla 2024-09-06 025827](https://github.com/user-attachments/assets/bfbd918c-232d-4d70-adc3-f540cba445b7)

Contactanos
![Captura de pantalla 2024-09-06 025857](https://github.com/user-attachments/assets/d93209fd-b7bd-4241-b273-24a5cee56d10)
![Captura de pantalla 2024-09-06 025902](https://github.com/user-attachments/assets/a30db0ce-b6d2-436d-adae-b0109a67f0e2)
![Captura de pantalla 2024-09-06 025909](https://github.com/user-attachments/assets/e444ce18-ca42-4d11-aede-832e2b0fb442)

Sobre Nosotros
![Captura de pantalla 2024-09-06 025925](https://github.com/user-attachments/assets/056498bc-f37a-45cd-8247-f078117f065f)



