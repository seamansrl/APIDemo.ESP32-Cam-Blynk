# PROYECTO HORUS: Demo en Arduino C para ESP32-CAM con monitoreo vía Blynk

Código demo en C de ARDUINO para el consumo de la API de reconocimiento (Proyecto Horus) junto a los servicios de https://blynk.io/.

Blynk son librerías para el entorno Arduino que nos permiten controlar o monitorear nuestros dispositivos IoT via APP Movil.
Para poder usar esta demo una vez cargado el código a la ESP32-Cam deberemos instalar en nuestro dispositivo IOS o Android la APP de Blynk, crear un proyecto y en el agregar un display matrix con los pines de lectura V5 y V6.

Para copiar el codigo a la ESP32-Cam se requiere de un adaptador USB-TTL el cual ira conectado de la siguiente manera:

![Conexion entre TTL y ESP32-Cam](Conexionado.jpg)


El Proyecto Horus consiste en una API REST que permite de forma simple identificar imágenes vía redes neuronales.

Dentro de las funciones de la API podemos encontrar:

- FACE ID
- OBJECT DETECTION
- QR DECODER
- ID DECODER
- APLR (AUTOMATIC PLATE LICENSE RECOGNITION)

al 01-02-2020 el proyecto estas en modo beta por lo cual para poder acceder y configurar la API se deberá descargar la APP que permite a la administracion desde https://www.proyectohorus.com.ar/Admin.zip

La URL a usar en el código de ejemplo es: http://server1.proyectohorus.com.ar

El usuario, Password y Perfil se obtienen en esta primera etapa desde el software descargable desde https://www.proyectohorus.com.ar

Ejemplo de cómo usar el administrador aca:

https://www.youtube.com/watch?v=R8AcntEprjE
