# Biodiseño Equipo 8
Bienvenidos al repositorio  del Grupo 8 del curso Fundamentos de Biodiseño

### Descripción de roles
 
* Diego Alexander Nolasco Murillo (Coordinador general)
  - Encargado de supervisar la estructura del equipo con el fin de garantizar una coordinación eficiente entre sus miembros y lograr la ejecución exitosa del proyecto.
* Gian Manuel Rojas Vergaray (Coordinador de Electrónica)
  -  Su rol consistirá en controlar, administrar, supervisar e instalar toda la parte electrónica del equipo, así como informar del uso de cada parte requerida e informar sobre cualquier falla. Trabajará directamente con el encargado de programación.
* Ana Paula Cornejo Salazar (Coordinadora de Impresión 3D)
  - Se encargará de la impresión 3D del prototipo cuando su modelado final esté terminado. Asimismo, trabaja con la coordinadora de Diseño y Modelado 3D para llegar a un acuerdo en cuanto a las especificaciones que debe tener el prototipo para que su impresión 3D proceda sin problemas.
* Daniel Alain Estela Rodríguez (Coordinador de Pogramación)
   - Se encarga de diseñar los códigos de algoritmo necesarios para el funcionamiento óptimo del prototipo.
* Kusi Qoyllur Uñapillco Franco (Coordinadora de Diseño)
   - Encargada de dirigir el diseño y modelado digital en 3D del prototipo. Para posteriormente proceder con la impresión 3D de la mejor opción de prototipado.

![casadas](https://github.com/DiegoNM31/Proyecto-Equipo-8/assets/143019323/9a62c2cf-400e-4a22-8d4b-dda583e8a55e)

  
## Contexto social
El holter electrocardiográfico externo (ECG) es un dispositivo no invasivo que permite el registro continuo de la actividad eléctrica del corazón durante periodos largos de tiempo; no interfiere con las actividades diarias del paciente [1]. Asimismo, los ECG portables (holters) son dispositivos que han demostrado su utilidad para detectar arritmias de manera bastante eficaz en comparación con el método estándar de atención actual. Estos comprobaron su capacidad para mejorar la atención al paciente y reducir los costos de atención médica, mientras que dispositivos diferentes son destinados a utilizarse como una pantalla de lectura de señales a más grande escala [2]. 
La educación técnica y superior en el Perú siempre se ha destacado por su enfoque teórico y la abundancia de conocimientos, pero suele carecer de actividades prácticas. En el ámbito de la educación médica, ya sea a nivel universitario o técnico, a menudo los estudiantes se ven afectados por la falta de inversión en equipos médicos de entrenamiento que podrían utilizar para aplicar sus conocimientos y familiarizarse con las tecnologías médicas [3]. 
De esta manera, se evidencia la importancia de la utilización de Holters a corto y largo plazo debido a los beneficios que este trae, como la reducción del costo de atención médica, más precisión a la hora de presentar resultados del monitoreo ya que es constante, y su practicidad. Además, se evidenció la falta de actividades prácticas en el ámbito de la educación médica superior universitaria y técnica. Por lo tanto, la necesidad de contar con profesionales de salud con experiencia en el uso de estos dispositivos es urgente.

## Problemática
La educación técnica y superior en el Perú siempre se ha destacado por su enfoque teórico y la abundancia de conocimientos, pero suele carecer de actividades prácticas. En el ámbito de la educación médica, ya sea a nivel universitario o técnico, a menudo los estudiantes se ven afectados por la falta de inversión en equipos médicos de entrenamiento que podrían utilizar para aplicar sus conocimientos y familiarizarse con las tecnologías médicas [3]. Dado que la práctica en el campo médico es crucial, hemos decidido abordar esta problemática mediante la creación de un dispositivo Holter diseñado específicamente para fines académicos, es decir, con fines educativos.

### Hospital Nacional Dos de Mayo de Perú
Se realizó un estudio observacional descriptivo en un hospital peruano de tercer nivel (Hospital Nacional Dos de Mayo, Lima, Perú). Se reportó que a partir de 446 pacientes que ingresaron en el servicio. Las cardiopatías más frecuentes fueron la insuficiencia cardiaca (51,57%), las cardiopatías congénitas (23,99%), la fibrilación auricular (17,49%) y el infarto agudo de miocardio (14,57%)[4].

![adsad](https://github.com/DiegoNM31/Proyecto-Equipo-8/assets/143019323/26954453-9c88-438e-93a0-656e11893f0c)
Tabla 1. Perú: Morbilidad registrada en consulta externa en MINSA y Gobiernos Regionales según grandes grupos de causas, 2019-2021 [5]

Una gran parte de emergencias cardiovasculares que llevan a la muerte, tales como Fibrilación ventricular, Taquicardia Ventricular, entre otros pueden detectarse con ayuda de herramientas como la electrocardiografía, la cual debe ser una de las herramientas esenciales en los servicios de urgencias hospitalarias.


###  Formulación de problemática
¿Cómo podríamos diseñar un Open Hardware de bajo costo,  que cumpla funciones básicas para el monitoreo de señales cardiácas en base al funcionamiento de los ECGs portátiles?

## Estado del Arte científico


| Dispositivo  | Ventajas | Desventajas | Imagen |
| ------------- | ------------- |------------- | ------------- |
|Electrocardiografo en reposo. (cardio express SL12A)| - Con batería recargable incorporada para permitir la portabilidad. - Cumple con los requisitos de ANSI/AAMI EC11. - Pantalla táctil de alta resolución para facilitar el uso y la interpretación. - Detección automática de arritmias. - Facilitar el análisis y la generación de informes  | - Costo elevado (dólares). - Adquisición mediante importación de países extranjeros.| ![70868-11596106](https://github.com/DiegoNM31/Proyecto-Equipo-8/assets/143019323/952446e7-f305-4367-ab6c-c97f463c1ebe)|
|App ECG (Apple Watch y relojes de este estilo en general)| - Monitoreo instantáneo (30 segundos) - Se puede exportar un PDF para tu médico. - Resultados interpretables solo incluyen la fibrilación auricular.|- La app ECG no puede detectar un infarto de miocardio. Si alguna vez experimentas dolor, presión o sensación de opresión en el pecho, o lo que crees que podría ser un infarto de miocardio, debes llamar de inmediato a los servicios de emergencia. - La app ECG no puede detectar trombos (coágulos de sangre) o accidentes cerebrovasculares. - La app ECG no puede detectar otros problemas relacionados con el corazón. Por ejemplo, hipertensión, insuficiencia cardiaca congestiva, un elevado nivel de colesterol u otros tipos de arritmia. - Las lecturas de la App ECG deben ser interpretadas por un personal de salud - Monitoreo instantáneo (30 segundos)|![Apple-Watch-Series7-Health-hero_inline jpg slideshow-xlarge_2x](https://github.com/DiegoNM31/Proyecto-Equipo-8/assets/143019323/05dc3c23-e404-4d30-bcfc-af1b60b6a7d3)|
|Heal Force Monitor ECG PC-80B|- Monitoriza el ECG y la frecuencia cardíaca en cualquier momento. - El software estándar de análisis de datos puede cargar datos en la computadora para el análisis estadístico. - Almacena una gran cantidad de datos.|- Tiene un elevado costo alrededor de los €520.00. - Su interfaz está diseñada para cardiólogos, lo que dificulta su uso para cualquier persona.|![69536-16760822](https://github.com/DiegoNM31/Proyecto-Equipo-8/assets/143019323/3d8f3bd1-5010-45bf-b2d3-1a77134ac0cb)|


# Contexto Comercial
## Productos de mercado
| Equipos | Descripción | Especificaciones | Imagen |
| ------------- | ------------- |------------- | ------------- |
|Holter Medilog® AR (Schiller)|Gracias al sistema de doble batería, los pacientes pueden ser monitorizados durante más de 14 días sin que necesiten volver a la consulta para cambiar las baterías. La detección de fibrilación/aleteo auricular en cero segundos mediante el análisis de las ondas P reales es uno de los aspectos de ingeniería más destacados de esta solución de Holter.|·   	Peso: 125 g aprox. sin batería AAA ·   	Costo: $ 3.406,71 ·   	Dimensiones: 83 x 60 x 18 mm ·   	Marca: Schiller ·   	Sistema de análisis rápido y preciso ·   	Exactitud de muestreo: 12 bits ·   	Resolución: 15,5 bit ·   	Velocidad de registro: 250 Hz ·   	Capacidad de la batería: >14 días ·   	Software: medilog®DARWIN2 [4]|![images](https://github.com/DiegoNM31/Proyecto-Equipo-8/assets/143019323/7f980363-275b-455f-abe7-c710115356fd) Figura 1. Holter Medilog® AR [4]|
|Sistema EC-3H/ABP|Sistema combinado ECG Holter y ABPM de tres canales y divulgación completa sin PC ni impresora. El sistema Holter combinado EC-3H/ABP combina un Holter de ECG de 3 canales y un monitor de presión arterial ambulatorio.[5]|·   	Peso: ~ 250 g (incluidas las pilas) ·   	Costo: $ 22 521 ·   	Dimensiones: 125mm x 70mm x 33mm ·   	Marca: LABTECH ·   	Voltaje interno (máx.): 3,3 voltios ·   	Registro de lectura: mediante cable USB ·   	Fuente de alimentación: 2 pilas recargables AA de 1,2 V ·   	Periodo de grabación (horas): 8h – 336h [5]|![EC-3HABP_profil-500_2](https://github.com/DiegoNM31/Proyecto-Equipo-8/assets/143019323/fb33a4c5-a8cc-4722-a314-490e2befc246) Figura 2. Sistema EC-3H/ABP [5]|
|Sistema HOLTER ECG 24 horas Modelo CT-H5000|Se compone de grabadora de ECG para registro continuo durante 24 horas de 12 derivaciones y software. La grabadora tiene un sistema de almacenamiento flash que aumenta su capacidad de memoria. La frecuencia de muestreo de 1000 muestras / seg ha mejorado la calidad de la forma de onda. El software del sistema se verifica por la AHA, y los datos MIT, garantizan su exactitud.[6]|·   	Peso: 105 gr. (sin batería) ·   	Costo: 1.580,00€ ·   	Dimensiones: 111mm x 60mm x 25mm ·   	Marca: Tecnomed 2000 ·   	Sistema de análisis rápido y preciso ·   	Exactitud de muestreo: 12 bits ·   	Pequeña grabadora ECG con pantalla a color OLED, que puede mostrar la forma de onda ECG en tiempo real. ·   	Interfaz USB ·   	Selección de la frecuencia de muestra, 200, 500, 1000 muestras / seg [6]|![CT-H50002](https://github.com/DiegoNM31/Proyecto-Equipo-8/assets/143019323/062609b0-aecf-4477-9f7e-dbe98dd2afb0) Figura 3. Sistema HOLTER ECG 24 horas Modelo CT-H5000 [6]|

## Patentes de utilidad

| Nombre de la patente (Código) | Descripción | Imagen |
| ------------- | ------------- |------------- |
|LIVE HOLTER (WO2014206382)|Holter en vivo que permite el monitoreo local o distante de señales cardíacas detectadas, procesadas y mostradas, curvas de ECG, frecuencia cardíaca, arritmia y sus límites por parte de la persona monitoreada o del especialista o personal de enfermería.[7]|![km9gcWxR0k4PyrPfS3hef1gwIV0PCjljg8QmvtFvnRAiA-Eo5iTFW3ni0AnaVlHc](https://github.com/DiegoNM31/Proyecto-Equipo-8/assets/143019323/54ffcad5-e647-466f-92e6-dea2e60a5527) Figura 4. WO2014206382 - LIVE HOLTER [7]|
|HOLTER-TYPE MONITOR SYSTEM COMPRISING AN ANALYTE SENSOR (EP1148808 )|Holter que consta de un dispositivo receptor de datos remoto, un sensor de análisis que genera una señal relacionada con una característica del usuario y un dispositivo de registro tipo Holter. El conector de sensor recibe las señales del sensor de analito, y el procesador las almacena para enviarlas al dispositivo receptor de datos remoto. Además, el dispositivo de registro puede transferir las señales almacenadas al dispositivo receptor de datos, que puede ser utilizado para diversas aplicaciones, como monitoreo médico, transmisión de datos a otros dispositivos o administración de medicamentos.[8]|![mj1ks3V5ZPfUGoYleQpAtnqyUc5HYUoGL_hPD8ZNYAR0QBty_aN1avBPeG_LTcct](https://github.com/DiegoNM31/Proyecto-Equipo-8/assets/143019323/8facbc53-4a92-47c3-8a54-a9b939644a43) Figura 5. WO2014206382 - LIVE HOLTER [8]|
|AUTOMATIC HIGH SPEED HOLTER SCANNING SYSTEM (WO1981000806)|Un Holter automático de alta velocidad.El sistema de escaneo (10) opera en un modo no automático o en un modo automático para recibir señales de electrocardiograma que han sido pregrabadas en formatos diferentes que tienen diferentes parámetros conocidos, y para procesarlas de acuerdo con una entrada del operador. El procesador automático de arritmias de la presente invención detecta información cardíaca ectópica, almacena la información detectada en secuencia temporal y lee y muestra selectivamente la información ectópica almacenada en respuesta a la orden del operador. Además, el procesador automático de arritmias compara los complejos QRS en las señales de ECG recibidas con un complejo QRS normal deseado y actualiza continuamente el intervalo RR y el área del complejo QRS normal después de cada comparación del complejo QRS normal con los complejos QRS posteriores.[9]|![HRz64Ju4MRjQLw8hC9hksXJlufZ4vE4eONXW7bc8pxEYK5tWq5dWmblB8nK5LCXE](https://github.com/DiegoNM31/Proyecto-Equipo-8/assets/143019323/33987ac5-1e2a-428a-a4dc-0d4d5d61592d) Figura 6. WO1981000806 - AUTOMATIC HIGH SPEED HOLTER SCANNING SYSTEM [9]|

## EEG Portátiles Open Hardware

|Nombres|Características|
|------|--------|
|Prototipo de electrocardiógrafo portátil |Prototipo de electrocardiógrafo portátil, con el diseño y fabricación de la PCB de adaptación y filtrado de la señal eléctrica proveniente del cuerpo humano hasta la preparación y programación de la placa de desarrollo Beaglebone Black Rev C. Falta hacer mejoras en la representación gráfica en tiempo real de la señal ECG en una pantalla LCD o mediante la instalación de un servidor web en la placa y su debida representación en un navegador [10].|
|Grove - Ear-clip Heart Rate Sensor (open Hardware)|Prototipo de bajo consumo de energía. Tiene un amplio rango de alimentación: DC 3~5V - Ventajas: cómodo de usar, tiene alta sensibilidad Cumple la directiva RoHS. Desventajas: Necesita de una graduación extra para su respectivo análisis.Además la portabilidad deficiente por los cables y el cuidado del kit [10].|
|Diseño y Construcción de un Electrocardiógrafo Portátil Recargable|Es necesario hacer diferentes etapas de amplificación y de filtrado para obtener la señal del ECG de manera más óptima teniendo en cuenta la interferencia eléctrica [10]|

# Propuesta de solución
Para solucionar la problemática planteada previamente, se propone diseñar un dispositivo Open Hardware holter el cual cumpla con requerimientos básicos, sirva para la enseñanza práctica, y sea accesible para futuros profesionales en el ámbito de la salud.

# Lista de requerimientos
### Requerimientos funcionales
Desarrollar un Open Hardware de código abierto diseñado específicamente como una herramienta educativa, con requisitos funcionales clave que aseguren su efectividad en el proceso de enseñanza y aprendizaje. Por ellos en los conceptos clave se precisara de los componentes básicos de un holter  los cuale son: una grabadora, un sistema de electrodos y un electro analizador.

Se diseñará un Holter externo no apto para un monitoreo constante sino para un fin educativo, por ende; no se necesita una batería de extensa duración, además de la oportunidad de usar una unidad de memoria más simple, ya que no se requiere la necesidad de registrar en tiempo real una gran cantidad de datos, sin embargo si se puede agregar una unidad de memoria que después de la medición de las señales, bote los resultados

### Requerimientos no funcionales
El producto será lo más parecido estéticamente a la mayoría de los holters y tendrá su estructura básica. Adicionalmente, el material será de bajo costo para hacerlo más accesible económicamente.

## Canalización de requirimientos
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
- Arduino: Nos ayuda mucho su principal propiedad “open source “, lo que nos permite personalizarlo a prácticamente cualquier uso 
- Electrodos para ECG: Electrodos genericos y descartable, suficientes para suplir la necesidades  
- Alimentación: presenta puestos USB que serán usados para recargar el dispositivo cuando este lo requiera  (alimentador AD a DC o una batería ) 
- Carcasa : Cobertura diseñada a escala y con gran detalle con el uso de varias herramientas que facilitarán el proceso.
- Raspberry Pi: Ordenador de placa reducida de bajo costo 
- Electrodos: colocados en las zonas de interés donde el Holter hará las mediciones
  
  ## Bibliografía
[1] Fernández, M. F. (2017). Manual de Enfermería. Enfermería en cardiología, 7, 123–136.
https://enfermeriaencardiologia.com/wp-content/uploads/electro_07.pdf

[2] Kamga, P., Mostafa, R., & Zafar, S. (2022). The use of wearable ECG devices in the clinical setting: A review. Current Emergency and Hospital Medicine Reports, 10(3), 67–72. https://doi.org/10.1007/s40138-022-00248-x

[3] Defensoría del Pueblo: Falta de personal médico y equipos, así como déficit de infraestructura en hospitales de Trujillo ponen en riesgo calidad de atención de pacientes. (s. f.). Defensoria del Pueblo - Perú. https://www.defensoria.gob.pe/defensoria-del-pueblo-falta-de-personal-medico-y-equipos-asi-como-deficit-de-infraestructura-en-hospitales-de-trujillo-ponen-en-riesgo-calidad-de-atencion-de-pacientes/

[4] Holter Medilog® AR [Internet] Disponible en: https://www.hemocare.pe/productos/holter

[5] Sistema EC-3H/ABP [Internet] Disponible en: https://www.labtech.hu/en/product/holter-ecg-and-abp-systems/ec-3h-abp/

[6] Sistema HOLTER ECG 24 horas Modelo CT-H5000 [Internet] Disponible en: https://tecnomed2000.com/producto/holter-ecg-basico-software-grabadora/ 

[7] WO2014206382 - LIVE HOLTER [Internet] Disponible en: https://patentscope.wipo.int/search/en/detail.jsf?docId=WO2014206382&_cid=P12-LMGL1H-63447-1 

[8] EP1148808 - HOLTER-TYPE MONITOR SYSTEM COMPRISING AN ANALYTE SENSOR [Internet] Disponible en: https://patentscope.wipo.int/search/en/detail.jsf?docId=EP13630973&_cid=P12-LMGL1H-63447-1 

[9] WO1981000806 - AUTOMATIC HIGH SPEED HOLTER SCANNING SYSTEM Disponible en https://patentscope.wipo.int/search/en/detail.jsf?docId=WO1981000806&_cid=P10-LMH8GE-61674-2

[10] Peralta, A. (2016). Prototipo de electrocardiógrafo portátil. 
https://biblus.us.es/bibing/proyectos/abreproy/12343/fichero/Prototipo+de+electrocardi%C3%B3grafo+port%C3%A1til+-+copia.pdf 





