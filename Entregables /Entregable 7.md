# Entregable 7: Reporte de Pruebas, retos y limitaciones
## Módulos
#Include <WiFi.h>: Esta línea incluye la biblioteca WiFi, que permite al ESP32 conectarse a una red Wi-Fi. #Include <PubSubClient.h>: Esta línea incluye la biblioteca PubSubClient, que se utiliza para implementar la comunicación MQTT en el ESP32. Funciones auxiliares :
- callback(char* topic, byte* payload, unsigned int length): Esta función se llama cuando el ESP32 recibe mensajes del servidor MQTT. Toma el tema (topic) y los datos (payload) del mensaje recibido. reconnect(): Esta función se encarga de establecer y gestionar la conexión MQTT con el servidor de Ubidots.
- Función de configuración ( setup()): La función setup()se ejecuta una vez al inicio del programa y de otras funciones como configurar la comunicación serial para la depuración, iniciar la conexión a la red Wi-Fi ,configurar el pin SENSOR como entrada para leer el valor del sensor,establecer la conexión al servidor MQTT de Ubidots y asociar la función callback al cliente MQTT.
- Función de Ciclo Principal ( loop()) : La función loop()se ejecuta de forma repetida. Comprueba si el cliente MQTT está conectado. Si no lo está, llama a la función reconnect()para volver a conectarse. Lee el valor del sensor conectado al pin SENSOR. Convierte el valor del sensor en una cadena y lo agrega al mensaje MQTT (payload). Publica el mensaje en el tema (topic) especificado. Llama a client.loop()para mantener la comunicación MQTT. Espere 500 milisegundos antes de repetir el ciclo.
## Implementación en un solo código
... documento...
## Lista de retos y limitacionnes
### Integración Hardware: Electrónica
- Limitaciones: Los componentes interiores no pueden exceder los límites preestablecidos (prácticamente no hay margen de error). Los componentes electrónicos son complicados de conseguir, son específicos en muchos aspectos y esto limita su búsqueda. Algunos componentes tienen un precio elevado (módulo egc).
- Retos: Lograr que todos los componentes electrónicos funcionen a la par correctamente y que su tamaño no exceda para nada las medidas preestablecidas junto con el modelado 3D.
- Posible solución: Buscar otros componentes que sean compatibles con el circuito electrónico y así tener más opciones. Buscar componentes electrónicos más baratos y accesibles , que cumplan roles parecidos a los del circuito original. Revisar las cotas del modelado 3D para que el tamaño no sea tan restringido.
### Integración Hardware: Programación
- Limitaciones: Por ahora, la lectura EKG funciones solo si el prorotipo está conectado a la computadora mediante un cable USB.
- Retos: Lograr que la lectura pueda realizarse incluso sin estar conectado, para que el dispositivo sea portable.
- Posible solución: Modificar el código actual con otra librería que nos permita esto.
### Manufactura digital: Modelado 3D
- Limitaciones: Hacer un buen boceto y calcular bien la dimensiones de la carcasa superior, inferior y las laterales para que los componentes puedan encajar y ser unidas con tornillos. Las dimensiones de algunos componentes para el ensamblado no se obtuvieron de manera específica en plataformas como grabcad.
- Retos: El modelado de los soportes de los componentes fueron diseñados de acuerdo a las medidas generales, todo ello tomando en cuenta la funcionalidad y posición dentro del case.
- Posibles soluciones Diseñar y modificar las dimensiones de la carcasa general para que todos los componentes y piezas encajen e interfieran con la parte de la electrónica. Diseñar soportes tomando en cuenta las medidas para que estas sirvan de anclaje de los componentes. Hacer algunos cambios en el diseño dependiendo del cambio de componentes (Batería de 9v- pilas de litio: diseño del case para la batería).
### Manufactura digital: Impresión 3D
- Limitación: Prototipo debe ser resistente/robusto para proteger los componentes que resguarda en el interior.
- Reto: Diseñar un protector que permita que el prototipo tenga caídas sin daños decisivos para su funcionamiento.
- Posible solución:
  - Preparar un fluido no newtoniano que disminuya la fuerza del impacto a los componentes internos.
  - Reforzar las esquinas del prototipo.
- Limitación: La integración de los componentes, con la manufactura 3D, con la forma de unión de las piezas (pernos) no es precisa o predecible.
- Reto: Hacer que los pernos encajen con los orificios destinados a ello.
- Posible Solución: Realizar pequeñas pruebas con el módulo para modificar algunas medidas y hacer mejoras en el modelado 3D.
## Imágenes y videos de prueba
### Implementación del case y los componentes
![integracionhardware_1](https://github.com/Kusi12/Proyecto-Equipo-8/assets/143301247/6f57e01c-95ed-42cd-b3a9-a84c1c1995a6)
![integracionhardware_2](https://github.com/Kusi12/Proyecto-Equipo-8/assets/143301247/2dce937e-0724-4344-ae1f-f2d63c522c23)
![integracionhardware_3](https://github.com/Kusi12/Proyecto-Equipo-8/assets/143301247/87e41199-2e69-4f55-9dc2-f30c9bbb3f4e)

### Pruebas de los sensores
![testeo_1](https://github.com/Kusi12/Proyecto-Equipo-8/assets/143301247/4a7059fd-4b48-44d7-94f5-6e2bae10d0d3)
[https://drive.google.com/file/d/1PL_Z3bpm8nl_WgxrfWn5lu9DBpf63P_T/view](https://github.com/Kusi12/Proyecto-Equipo-8/assets/143301247/71eea471-9128-4a16-a74c-7094bf1f0978
)https://github.com/Kusi12/Proyecto-Equipo-8/assets/143301247/71eea471-9128-4a16-a74c-7094bf1f0978


