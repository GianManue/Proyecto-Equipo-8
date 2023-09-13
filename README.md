# Biodiseño Equipo 8
Bienvenidos al repositorio  del Grupo 8 del curso Fundamentos de Biodiseño
### Intregrantes
* Gian Manuel Rojas Vergaray
* Diego Alexander Nolasco Murillo
* Ana Paula Cornejo Salazar
* Daniel Alain Estela Rodríguez
* Kusi Qoyllur Uñapillco Franco

### Descripción de roles
 
* 
## Contexto
La educación técnica y superior en el Peru siempre ha destacado por ser muy teórica , rica en conocimientos; pero muy pobre en actividades prácticas. En el caso de la educación médica ( tanto universitaria como técnica ) muchas veces los estudiantes se ven afectados por la falta de inversión en equipos médicos de entrenamiento  que ellos podrían usar para poner en práctica todos sus conocimientos e ir familiarizándose con las tecnologías médicas . Considerando que la práctica en el campo médico es muy importante , hemos decidido tratar de solventar esta problemática con la creación  de un dispositivo Holter cuyo uso sea académico, es decir , de enseñanza.[a]

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
|Pulsoxímetro|- Recargables, algunos a pilas 2 AA y otros con una batería recargable. - Con una precisión considerable al ser un equipo portátil. - Además de la frecuencia cardiaca, mide otros parámetros como la saturación de oxígeno en la sangre. -No se requiere de personal médico calificado para operar este equipo. - Su costo es accesible por lo que es relativamente fácil adquirir uno. - Se puede conectar a tu smartphone para monitorear tus parámetro.|- Su medición depende de múltiples factores, por lo que en la mayoría de casos si el paciente usa esmalte de uñas o no está en reposo la medición de los resultados es bastante imprecisa. - Su modelo no está diseñado para usarse de manera continua, por lo que es imposible el monitoreo constante.|![51NWbCXm1wL _AC_UF1000,1000_QL80_](https://github.com/DiegoNM31/Proyecto-Equipo-8/assets/143019323/cfb6ac61-b066-4343-acf9-15b6113eab89)|
|Heal Force Monitor ECG PC-80B|- Monitoriza el ECG y la frecuencia cardíaca en cualquier momento. - El software estándar de análisis de datos puede cargar datos en la computadora para el análisis estadístico. - Almacena una gran cantidad de datos.|- Tiene un elevado costo alrededor de los €520.00. - Su interfaz está diseñada para cardiólogos, lo que dificulta su uso para cualquier persona.|![69536-16760822](https://github.com/DiegoNM31/Proyecto-Equipo-8/assets/143019323/3d8f3bd1-5010-45bf-b2d3-1a77134ac0cb)|
|Grove - Ear-clip Heart Rate Sensor (open Hardware)| - Bajo consumo de energía. - Amplio rango de alimentación: DC 3~5V - Cómodo de usar. - Alta sensibilidad. - Cumple la directiva RoHS| - Necesita de una graduación extra para su respectivo análisis. - Una portabilidad deficiente por los cables y el cuidado del kit. |![Gheartsensor-600x600](https://github.com/DiegoNM31/Proyecto-Equipo-8/assets/143019323/d9ff8f2a-f6df-4f0d-8390-7fbde255284f)|
|Open-source-hardware-heart-monitor| - Monitor Holter estándar de 4 electrodos. - Cómodo y ligero, incluso con las pilas incluidas. - Largo tiempo de ejecución.|- Se disminuyó el uso de 12 electrodos a 4. - Falta terminar y concretar las ideas del open Hardware. - Falta sensibilidad||

# Contexto Comercial
## Productos de mercado
| Equipos | Descripción | Especificaciones | Imagen |
| ------------- | ------------- |------------- | ------------- |
|Holter Medilog® AR (Schiller)|Gracias al sistema de doble batería, los pacientes pueden ser monitorizados durante más de 14 días sin que necesiten volver a la consulta para cambiar las baterías. La detección de fibrilación/aleteo auricular en cero segundos mediante el análisis de las ondas P reales es uno de los aspectos de ingeniería más destacados de esta solución de Holter.|·   	Peso: 125 g aprox. sin batería AAA ·   	Costo: $ 3.406,71 ·   	Dimensiones: 83 x 60 x 18 mm ·   	Marca: Schiller ·   	Sistema de análisis rápido y preciso ·   	Exactitud de muestreo: 12 bits ·   	Resolución: 15,5 bit ·   	Velocidad de registro: 250 Hz ·   	Capacidad de la batería: >14 días ·   	Software: medilog®DARWIN2|![images](https://github.com/DiegoNM31/Proyecto-Equipo-8/assets/143019323/7f980363-275b-455f-abe7-c710115356fd)|
|Sistema EC-3H/ABP|Sistema combinado ECG Holter y ABPM de tres canales y divulgación completa sin PC ni impresora. El sistema Holter combinado EC-3H/ABP combina un Holter de ECG de 3 canales y un monitor de presión arterial ambulatorio.|·   	Peso: ~ 250 g (incluidas las pilas) ·   	Costo: $ 22 521 ·   	Dimensiones: 125mm x 70mm x 33mm ·   	Marca: LABTECH ·   	Voltaje interno (máx.): 3,3 voltios ·   	Registro de lectura: mediante cable USB ·   	Fuente de alimentación: 2 pilas recargables AA de 1,2 V ·   	Periodo de grabación (horas): 8h – 336h|![EC-3HABP_profil-500_2](https://github.com/DiegoNM31/Proyecto-Equipo-8/assets/143019323/fb33a4c5-a8cc-4722-a314-490e2befc246)|
|Sistema HOLTER ECG 24 horas Modelo CT-H5000|Se compone de grabadora de ECG para registro continuo durante 24 horas de 12 derivaciones y software. La grabadora tiene un sistema de almacenamiento flash que aumenta su capacidad de memoria. La frecuencia de muestreo de 1000 muestras / seg ha mejorado la calidad de la forma de onda. El software del sistema se verifica por la AHA, y los datos MIT, garantizan su exactitud.|·   	Peso: 105 gr. (sin batería) ·   	Costo: 1.580,00€ ·   	Dimensiones: 111mm x 60mm x 25mm ·   	Marca: Tecnomed 2000 ·   	Sistema de análisis rápido y preciso ·   	Exactitud de muestreo: 12 bits ·   	Pequeña grabadora ECG con pantalla a color OLED, que puede mostrar la forma de onda ECG en tiempo real. ·   	Interfaz USB ·   	Selección de la frecuencia de muestra, 200, 500, 1000 muestras / seg|![CT-H50002](https://github.com/DiegoNM31/Proyecto-Equipo-8/assets/143019323/062609b0-aecf-4477-9f7e-dbe98dd2afb0)|

 
  ## Documentos importantes
  * https://rpmesp.ins.gob.pe/index.php/rpmesp/article/view/4425/3329
  * https://link.springer.com/article/10.1007/s40138-022-00248-x
  * http://memoriascnib.mx/index.php/memorias/article/view/25
  * https://www.dge.gob.pe/portalnuevo/publicaciones/analisis-de-situacion-de-salud-asis/#tab-content-5
  * https://www.mayoclinic.org/es/diseases-conditions/heart-disease/symptoms-causes/syc-20353118
  * https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.3001931 
  
  ## Bibliografía
  [a] https://ems.sld.cu/index.php/ems/article/view/1413/768
  https://www.defensoria.gob.pe/defensoria-del-pueblo-falta-de-personal-medico-y-equipos-asi-como-deficit-de-infraestructura-en-hospitales-de-trujillo-ponen-en-riesgo-calidad-de-atencion-de-pacientes/
  
  
 
  [2] Global Health Metrics. Global, Regional, and National Age-Sex-Specific Mortality for 282 Causes of Death in 195 Countries and Territories, 1980-2017: A Systematic Analysis for the Global Burden of Disease Study 2017 GBD 2017 Causes of Death Collaborators*. 20 June 2019. 
  
  [3] MAYO CLINIC. “Enfermedad Cardíaca - Síntomas Y Causas - Mayo Clinic.” Www.mayoclinic.org, 25 Aug. 2022, www.mayoclinic.org/es/diseases-conditions/heart-disease/symptoms-causes/syc-20353118. Revisado el 30 Aug. 2023.

[4] Chambergo-Michilot Diego, Velit-Rios Bruno, Cueva-Parra Angel. Prevalencia de enfermedades cardiovasculares en el Hospital Nacional Dos de Mayo de Perú. Rev. mex. angiol.  [revista en la Internet]. 2020  Sep [citado  2023  Sep  01] ;  48( 3 ): 84-89. Disponible en: http://www.scielo.org.mx/scielo.php?script=sci_arttext&pid=S2696-130X2020000300084&lng=es.  Epub 23-Ago-2021.  https://doi.org/10.24875/rma.20000012.

[5] ANÁLISIS DE SITUACIÓN DE SALUD DEL PERÚ 2021. Centro Nacional de Epidemiología, Prevención y Control de Enfermedades - Lima: Ministerio de Salud; 2023.: Biblioteca del Ministerio de Salud; 2023. [citado 2023 Sep 01]. Disponible en: https://www.dge.gob.pe/portalnuevo/publicaciones/analisis-de-situacion-de-salud-asis/#tab-content-5


