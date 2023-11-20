# Entregable 7: Reporte de Pruebas, retos y limitaciones
## Módulos
#Include <WiFi.h>: Esta línea incluye la biblioteca WiFi, que permite al ESP32 conectarse a una red Wi-Fi. #Include <PubSubClient.h>: Esta línea incluye la biblioteca PubSubClient, que se utiliza para implementar la comunicación MQTT en el ESP32. Funciones auxiliares :

- callback(char* topic, byte* payload, unsigned int length): Esta función se llama cuando el ESP32 recibe mensajes del servidor MQTT. Toma el tema (topic) y los datos (payload) del mensaje recibido. reconnect(): Esta función se encarga de establecer y gestionar la conexión MQTT con el servidor de Ubidots.
- Función de configuración ( setup()): La función setup()se ejecuta una vez al inicio del programa y de otras funciones como configurar la comunicación serial para la depuración, iniciar la conexión a la red Wi-Fi ,configurar el pin SENSOR como entrada para leer el valor del sensor,establecer la conexión al servidor MQTT de Ubidots y asociar la función callback al cliente MQTT.
- Función de Ciclo Principal ( loop()) : La función loop()se ejecuta de forma repetida. Comprueba si el cliente MQTT está conectado. Si no lo está, llama a la función reconnect()para volver a conectarse. Lee el valor del sensor conectado al pin SENSOR. Convierte el valor del sensor en una cadena y lo agrega al mensaje MQTT (payload). Publica el mensaje en el tema (topic) especificado. Llama a client.loop()para mantener la comunicación MQTT. Espere 500 milisegundos antes de repetir el ciclo.
## Implementación en un solo código
... documento...
## Lista de retos y limitacionnes
### Integración Hardware
- Limitaciones: Los componentes interiores no pueden exceder los límites preestablecidos (prácticamente no hay margen de error). Los componentes electrónicos son complicados de conseguir, son específicos en muchos aspectos y esto limita su búsqueda. Algunos componentes tienen un precio elevado (módulo egc).
- Retos: Lograr que todos los componentes electrónicos funcionen a la par correctamente y que su tamaño no exceda para nada las medidas preestablecidas junto con el modelado 3D.
- Posible solución: Buscar otros componentes que sean compatibles con el circuito electrónico y así tener más opciones. Buscar componentes electrónicos más baratos y accesibles , que cumplan roles parecidos a los del circuito original. Revisar las cotas del modelado 3D para que el tamaño no sea tan restringido.
