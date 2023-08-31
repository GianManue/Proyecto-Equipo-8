# Biodiseño Equipo 8
Bienvenidos al repositorio  del Grupo 8 del curso Fundamentos de Biodiseño
### Intregrantes
* Gian Manuel Rojas Vergaray
* Diego Alexander Nolasco Murillo
* Ana Paula Cornejo Salazar
* Daniel Alain Estela Rodríguez
* Kusi Qoyllur Uñapillco Franco
## Análisis del caso
Las enfermedades cardiovasculares son la principal causa de mortalidad en el
mundo, siendo la causa de aproximadamente 31% de muertes durante el año 2017. [1]

En el Perú, es una de las causas importante de muerte, se estima que, de
todas las causas de muertes prematuras, el 15% son causadas por Enfermedades
cardiovasculares con una tasa de mortalidad de 143 muertes por 100000 habitantes. [2]

Es posible que no se diagnostiquen enfermedades de las arterias coronarias hasta que empiecen los ataques cardiácos, angina de pecho, un accidente cerebrovascular o insuficiencia cardíaca. Es importante estar atento a los síntomas cardíacos y comunicar las preocupaciones al proveedor de atención médica. A veces, las enfermedades cardíacas (cardiovasculares) pueden detectarse a tiempo con exámenes médicos regulares y el monitoreo constante. [3]

Una gran parte de emergencias cardiovasculares que llevan a la muerte, tales
como Fibrilación ventricular, Taquicardia Ventricular, entre otros pueden
detectarse con ayuda de herramientas como la electrocardiografía, la cual debe ser una de las herramientas esenciales en los servicios de urgencias hospitalarias.
###  Formulación de problemática
¿Cómo podríamos diseñar e implementar un dispositivo de bajo costo, en centros de salud donde estos son escasos, que cumpla con funciones básicas para el análisis y detección de algunas enfermedades cardiovasculares?
## Estado del Arte científico
| Dispositivo  | Ventajas | Desventajas | Imagen |
| ------------- | ------------- |------------- | ------------- |
|Electrocardiografo en reposo. (cardio express SL12A)| - Con batería recargable incorporada para permitir la portabilidad. - Cumple con los requisitos de ANSI/AAMI EC11. - Pantalla táctil de alta resolución para facilitar el uso y la interpretación. - Detección automática de arritmias. - Facilitar el análisis y la generación de informes  | - Costo elevado (dólares). - Adquisición mediante importación de países extranjeros.| ![70868-11596106](https://github.com/DiegoNM31/Proyecto-Equipo-8/assets/143019323/952446e7-f305-4367-ab6c-c97f463c1ebe)|
|App ECG (Apple Watch y relojes de este estilo en general)| - Monitoreo instantáneo (30 segundos) - Se puede exportar un PDF para tu médico. - Resultados interpretables solo incluyen la fibrilación auricular.|- La app ECG no puede detectar un infarto de miocardio. Si alguna vez experimentas dolor, presión o sensación de opresión en el pecho, o lo que crees que podría ser un infarto de miocardio, debes llamar de inmediato a los servicios de emergencia. - La app ECG no puede detectar trombos (coágulos de sangre) o accidentes cerebrovasculares. - La app ECG no puede detectar otros problemas relacionados con el corazón. Por ejemplo, hipertensión, insuficiencia cardiaca congestiva, un elevado nivel de colesterol u otros tipos de arritmia. - Las lecturas de la App ECG deben ser interpretadas por un personal de salud - Monitoreo instantáneo (30 segundos)|![Apple-Watch-Series7-Health-hero_inline jpg slideshow-xlarge_2x](https://github.com/DiegoNM31/Proyecto-Equipo-8/assets/143019323/05dc3c23-e404-4d30-bcfc-af1b60b6a7d3)|
|Pulsoxímetro|- Recargables, algunos a pilas 2 AA y otros con una batería recargable. - Con una precisión considerable al ser un equipo portátil. - Además de la frecuencia cardiaca, mide otros parámetros como la saturación de oxígeno en la sangre. -No se requiere de personal médico calificado para operar este equipo. - Su costo es accesible por lo que es relativamente fácil adquirir uno. - Se puede conectar a tu smartphone para monitorear tus parámetro.|- Su medición depende de múltiples factores, por lo que en la mayoría de casos si el paciente usa esmalte de uñas o no está en reposo la medición de los resultados es bastante imprecisa. - Su modelo no está diseñado para usarse de manera continua, por lo que es imposible el monitoreo constante.|![51NWbCXm1wL _AC_UF1000,1000_QL80_](https://github.com/DiegoNM31/Proyecto-Equipo-8/assets/143019323/cfb6ac61-b066-4343-acf9-15b6113eab89)|
|Heal Force Monitor ECG PC-80B|- Monitoriza el ECG y la frecuencia cardíaca en cualquier momento. - El software estándar de análisis de datos puede cargar datos en la computadora para el análisis estadístico. - Almacena una gran cantidad de datos.|- Tiene un elevado costo alrededor de los €520.00. - Su interfaz está diseñada para cardiólogos, lo que dificulta su uso para cualquier persona.|![69536-16760822](https://github.com/DiegoNM31/Proyecto-Equipo-8/assets/143019323/3d8f3bd1-5010-45bf-b2d3-1a77134ac0cb)|
  ## Caso clínico
  ### Datos personales del paciente
  * Nombre: Alexis Matías Rodríguez Martínez 
  * Edad: 45 años
  * Género: Masculino
  * Residencia: Pachacamac, Lima
  * Estado civil: Casado, 2 hijos 
  * Ocupaciòn: Obrero

  ### Antecedentes: 
  Familiares cercanos presentan problemas cardiovasculares con relativa facilidad desde que entran a la etapa adulta.

  ### Diagnóstico:
  El paciente se presenta al “Hospital de la Solidaridad” (centro de salud en Pachacamac) por motivos médicos, puesto que presenta un dolor “punzante” en el pecho 
  constantemente. Después de una evaluación previa, es derivado a la unidad de emergencias (por la ausencia de una unidad de cardiología en este hospital). En 
  emergencias detectan un comportamiento anormal, esto genera preocupación en los profesionales médicos presentes, los cuales lamentablemente no son especialistas 
  en esa área. Se le solicita al paciente que programe múltiples citas para evaluarlo puesto que se proyecta una posible cardiopatía ; lamentablemente; el sistema 
  de citas está bastante saturado por el resto de pacientes (esto debido a que hay poco personal médico capacitado y mucha demanda de pacientes), también el señor 
  Rodriguez vive a una larga distancia de este hospital, complicando aún más su situación.

  ### Contexto social:
  Alexis Matìas Rodrìguez Martìnez no cuenta con estudios superiores, por lo cual su trabajo de obrero es su opción más beneficiosa. Sin embargo, este trabajo le 
  permite proveer sólo para mantener a su familia mes a mes; los ahorros que llegó a guardar junto con su pareja se fueron en la cuota del hospital en el que fue 
  atendido de emergencia, por lo que ahora tiene una deuda y le es imposible pagar controles y transporte frecuentes para detectar la patología exacta que padece 
  lo antes posible para poder tratarla.

  ### Tratamiento:
  Los médicos le advirtieron a Alexis que deben detectar su patología cardíaca con urgencia, más no hay nada que puedan hacer si Alexis no asiste a los controles 
  con regularidad. Hay factores socioeconómicos que no le permiten a Alexis mejorar su calidad de vida. Por lo tanto, nuestro desafío como grupo será analizar la 
  situación de nuestro usuario desde su contexto social y económico, para que el paciente tenga la posibilidad de tener una calidad de vida más digna detectando su 
  enfermedad cardíaca lo más pronto posible y así evitar una muerte prematura por ataque cardíaco, angina de pecho, un accidente cerebrovascular o insuficiencia 
  cardíaca.

  ## Documentos importantes
  * https://rpmesp.ins.gob.pe/index.php/rpmesp/article/view/4425/3329
  * https://link.springer.com/article/10.1007/s40138-022-00248-x
  * http://memoriascnib.mx/index.php/memorias/article/view/25
  * https://www.dge.gob.pe/portalnuevo/publicaciones/analisis-de-situacion-de-salud-asis/#tab-content-5
  * https://www.mayoclinic.org/es/diseases-conditions/heart-disease/symptoms-causes/syc-20353118
  * https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.3001931 
  
  ## Bibliografía
  [1] Soria Analía Graciela, Guber Rosa Silvina, Tefaha Liliana Mónica, Aragón Félix Fernando, Romero Claudio de Jesús, del Valle Toledo Roxana et al . Prevalencia de hipertensión arterial y factores de riesgo cardiovascular en una población rural expuesta al arsénico en Argentina. Rev. perú. med. exp. salud publica  [Internet]. 2021  Oct [citado  2023  Ago  30] ;  38( 4 ): 530-536. Disponible en: http://www.scielo.org.pe/scielo.php?script=sci_arttext&pid=S1726-46342021000400530&lng=es.  Epub 22-Dic-2021.  http://dx.doi.org/10.17843/rpmesp.2021.384.9402.
  
  [2] Global Health Metrics. Global, Regional, and National Age-Sex-Specific Mortality for 282 Causes of Death in 195 Countries and Territories, 1980-2017: A Systematic Analysis for the Global Burden of Disease Study 2017 GBD 2017 Causes of Death Collaborators*. 20 June 2019. 
  
  [3] MAYO CLINIC. “Enfermedad Cardíaca - Síntomas Y Causas - Mayo Clinic.” Www.mayoclinic.org, 25 Aug. 2022, www.mayoclinic.org/es/diseases-conditions/heart-disease/symptoms-causes/syc-20353118. Revisado el 30 Aug. 2023.

