# Entregable 3
## Lista de requerimientos
### Requerimientos funcionales
- Desarrollar un Open Hardware de código abierto diseñado específicamente como una herramienta educativa, con requisitos funcionales clave que aseguren su efectividad en el proceso de enseñanza y aprendizaje.
- Evaluar: El prototipo evaluará las actividades eléctricas cardiacas durante un período prolongado de tiempo. Procesar la información: A partir del sensado con los electrodos se espera, guardar la información el el almacenamiento de Arduino UNO. Para luego ser representada, ya sea numéricamente o por gráficas.
- Graficar: Una vez terminado el monitoreo, se mostrará una gráfica del ECG.
### Requerimientos no funcionales
- Parecido a los holters de uso médico
- Diseño ergonómico
- Diseño amigable con el público objetivo
- Material de costo reducido
## Canalización de requerimientos
### Estrategias
- Aumentar la producción de holters para uso educativo.
- Simplificar la estructura del dispositivo sin quitarle su función principal y propósito.
- Reducir el costo de la práctica de campo para los estudiantes de ciencias de la salud.
- Entrenar a los estudiantes de ciencias de la salud en el uso de los holters para la vida profesional.
### Conceptos
- Manteniendo la estructura básica de la mayoría de holters pero reduciendo sus capacidades de manera que sirva para maniobrarlo correctamente.
- La lectura de datos se realizará después de la lectura y no durante.
### Módulos
- Módulo de almacenamiento
- Módulo de lector cardiaco
- Módulo de traducción de información
### Componentes
| Componentes | Descripción | Imagen |
| ------------- | ------------- |---------|
|Esp32|Su capacidad de concectarse por wifi y bluetoh convierte a este procesador en uno mas portatil y versatil|![descarga](https://github.com/Kusi12/Proyecto-Equipo-8/assets/143300872/572d79c3-82e7-4b2a-9000-a20605de663e)(|
|Electrodos para ECG|Electrodos genericos y descartable, suficientes para suplir la necesidades|![IMG_0314-1000x1000](https://github.com/DiegoNM31/Proyecto-Equipo-8/assets/143019323/ba69c999-892a-4b00-91a9-031ec36e91b7)|
|Alimentación|Presenta puestos USB que serán usados para recargar el dispositivo cuando este lo requiera  (alimentador AD a DC o una batería ) |![plug-conector-de-bateria-9v-para-jack-arduino](https://github.com/Kusi12/Proyecto-Equipo-8/assets/143300872/38a11bef-2a8d-46b6-a517-a2f3d5eef6d8)|
|Carcasa|Cobertura diseñada a escala y con gran detalle con el uso de varias herramientas que facilitarán el proceso.|![68095-6663521](https://github.com/DiegoNM31/Proyecto-Equipo-8/assets/143019323/18998faf-a882-4684-9a86-b5d4c3bf07e9)|
|Módulo ECG: para sensar|AD8232 funciona mediante el uso de un amplificador de instrumentación para amplificar la señal eléctrica débil del corazón, un filtro de señal para eliminar el ruido y las interferencias de la señal y una interfaz de conexión para electrodos. |![descarga (1)](https://github.com/Kusi12/Proyecto-Equipo-8/assets/143300872/282c2f4f-6d6e-423c-b878-45e39ecf7e94)|
|Reguladro de Bateria|regulador de voltaje es un dispositivo electrónico diseñado para mantener un nivel de tensión constante|![1-250x250](https://github.com/Kusi12/Proyecto-Equipo-8/assets/143300872/cc57d48d-d801-498b-b93e-82a26f9d8a5c)|
## Caja negra
![caja_negra](https://github.com/Kusi12/Proyecto-Equipo-8/assets/143301247/1053d639-c503-4da5-bc29-06c64aacf007)
## Esquema de funciones
...imagen
## Matriz morfológica
...imagen
## Tabla de valoración
...imagen
## Conclusiones
En conclusión, después de haber hecho una correcta valoración de los conceptos de solución, la propuesta 3 resulto ganadora puesto que presentó un mayor valoración.
