# Laboratorio 6 | Instrumentación biomédica y biosensores 

 - Daniel Espinosa 5600778
 - Samuel Velandia 5600777

## Introducción :


El monitoreo de variables cardiovasculares y hemodinámicas es una herramienta fundamental dentro de los entornos clínicos, ya que permite conocer en tiempo real el estado fisiológico de un paciente y detectar oportunamente posibles alteraciones que puedan comprometer su salud. Variables como la frecuencia cardíaca y la saturación periférica de oxígeno (SpO₂) son ampliamente utilizadas para evaluar el funcionamiento de los sistemas cardiovascular y respiratorio. Para garantizar que los monitores de signos vitales proporcionen mediciones confiables, es necesario realizar pruebas funcionales utilizando simuladores biomédicos capaces de reproducir diferentes condiciones fisiológicas y patológicas.

<img width="370" height="177" alt="image" src="https://github.com/user-attachments/assets/0284f908-08de-4c97-a063-fdeb05c41c74" />

En esta práctica se utilizó el monitor de signos vitales uMEC 100 junto con el simulador Pronk OxSim OX-1 para analizar el comportamiento del sistema frente a diferentes escenarios clínicos simulados. A través de esta actividad fue posible comprender el funcionamiento de las alarmas, evaluar la precisión de las mediciones y reconocer la importancia de la verificación periódica de los equipos biomédicos utilizados en la atención de pacientes.


# Objetivos : 

## Objetivo general: 

- Evaluar el funcionamiento de un monitor de signos vitales mediante la simulación de variables cardiovasculares y hemodinámicas.

## Objetivos especificos 

- Identificar los principales modos de operación del simulador Pronk OxSim OX-1.
- Verificar la respuesta del monitor uMEC 100 ante diferentes valores simulados de frecuencia cardíaca y SpO₂.
- Analizar la activación de alarmas y la precisión de las mediciones obtenidas.

# Materiales : 

- Monitor de signos vitales uMEC 100 (MINDRAY) con sensor de SpO2
- Simulador de parámetros hemodinámicos Pronk Ox-Sim OX-1
- Computador personal con conexión a Internet
- Libreta y lapiz o lapicero 

# Marco teórico :

Los signos vitales son indicadores fisiológicos que permiten evaluar el estado de salud de una persona. Entre los más importantes se encuentran la frecuencia cardíaca y la saturación periférica de oxígeno (SpO₂), parámetros que proporcionan información sobre el funcionamiento del corazón y la capacidad del organismo para transportar oxígeno a los tejidos. La frecuencia cardíaca corresponde al número de latidos del corazón por minuto, mientras que la SpO₂ representa el porcentaje de hemoglobina oxigenada presente en la sangre.

<img width="285" height="212" alt="image" src="https://github.com/user-attachments/assets/38feb0ed-0244-4121-9f7f-bedd77bb8943" />

Los monitores de signos vitales son dispositivos biomédicos diseñados para medir, visualizar y registrar continuamente estos parámetros. Además de mostrar los valores medidos, cuentan con sistemas de alarmas visuales y sonoras que se activan cuando las variables fisiológicas superan los límites establecidos, permitiendo al personal médico actuar de manera rápida ante posibles situaciones de riesgo.

Para verificar el correcto funcionamiento de estos equipos se emplean simuladores biomédicos como el Pronk OxSim OX-1. Este dispositivo es capaz de generar señales equivalentes a las que produciría un paciente real, simulando diferentes frecuencias cardíacas, niveles de saturación de oxígeno y condiciones clínicas específicas. Gracias a estas características, los simuladores permiten realizar pruebas funcionales, evaluar la exactitud de las mediciones y comprobar la respuesta de los sistemas de alarma sin poner en riesgo la seguridad de un paciente.

<img width="332" height="207" alt="image" src="https://github.com/user-attachments/assets/b5a90a27-b70c-485c-8475-79feacecaaf4" />

# Procedimiento : 

Inicialmente se realizó una revisión bibliográfica sobre el monitor de signos vitales uMEC 100 y el simulador Pronk OxSim OX-1, consultando información técnica y manuales de operación para conocer sus características, funciones y procedimientos de configuración. Posteriormente, se encendió el monitor y se configuró en modo monitor para habilitar la visualización de los parámetros fisiológicos.

Después de la configuración inicial, se conectó el sensor de pulsioximetría del monitor al simulador OxSim OX-1. Se programó una condición de bradicardia con una frecuencia cardíaca de 40 bpm y una saturación de oxígeno del 95 %, registrando los valores mostrados por el monitor y calculando los errores absolutos y porcentuales entre los valores simulados y los medidos.

Posteriormente se configuraron los límites de alarma para la saturación de oxígeno y se realizaron simulaciones de hipoxia modificando los valores de SpO₂. Durante estas pruebas se observó la activación de las alarmas visuales y sonoras, registrando los tiempos de respuesta y verificando el comportamiento de la señal fotopletismográfica mostrada en la pantalla del monitor.

Finalmente, se simularon condiciones de baja perfusión y taquicardia para evaluar nuevamente la capacidad de respuesta del sistema de monitoreo. Todos los resultados obtenidos fueron analizados y comparados con los valores de referencia suministrados por el simulador, permitiendo determinar la precisión y confiabilidad del monitor de signos vitales.

# Preguntas a desarrollar : 

- Pregunta 1. ¿Cuál es el principio de operación del Pronk OxSim OX-1 para simular una onda pulsátil?

El simulador Pronk OxSim OX-1 funciona reproduciendo las señales ópticas que normalmente serían detectadas por un sensor de pulsioximetría durante el paso de la sangre por los tejidos. El dispositivo genera variaciones controladas en la absorción de luz, simulando los cambios producidos por el pulso arterial. De esta manera, el monitor interpreta estas señales como si provinieran de un paciente real y calcula valores de frecuencia cardíaca y saturación de oxígeno. Gracias a este principio de funcionamiento, es posible verificar el desempeño de los monitores de signos vitales de forma segura y controlada.

- Pregunta 2. ¿Por qué la SpO₂ baja puede ser un falso positivo (falsa alarma) en una situación de mala perfusión?

La pulsioximetría depende de una adecuada circulación sanguínea para obtener una señal confiable. Cuando existe mala perfusión, como ocurre en casos de hipotensión, vasoconstricción o disminución del flujo sanguíneo periférico, la cantidad de sangre que llega al sitio donde se encuentra el sensor es insuficiente. Esto provoca una señal débil o distorsionada que puede ser interpretada erróneamente por el monitor como una disminución de la saturación de oxígeno. Por esta razón, el equipo puede generar una alarma de SpO₂ baja aunque el paciente realmente mantenga niveles normales de oxigenación, produciendo así un falso positivo.

# Bibliografía : 


- Dosch, M. P. (2005). The anesthesia machine. En M. Karlet (Ed.), Nurse anesthesia secrets (1.ª ed.). Elsevier Health Sciences.

- Fischler, I. S., Kaschub, C. E., Lizdas, D. E., & Lampotang, S. (2008). Understanding of anesthesia machine function is enhanced with a transparent reality simulation. Simulation in Healthcare, 3(1), 26–32. https://doi.org/10.1097/SIH.0b013e31816366d3

- Instituto Nacional de Vigilancia de Medicamentos y Alimentos (INVIMA). (s.f.). ABC de dispositivos médicos: Guía reguladora. https://www.invima.gov.co

- Instituto de Salud Pública de Chile. (2021). Guía para la clasificación de dispositivos médicos según riesgo. https://www.ispch.cl/sites/default/files/Guia_de_Clasificacion_de_Dispositivos_Medicos_Segun_riesgo_Formato_Institucional.pdf

- Medical IT. (s.f.). Ox-Sim: Simulador de pulsioximetría. https://www.medicalitech.com/producto/ox-sim/

- Sherwin, M. A., & Eisenkraft, J. B. (2020). Anesthesia hazards: What is the role of the anesthesia machine? International Anesthesiology Clinics, 58(1), 27–31. https://doi.org/10.1097/AIA.0000000000000264

- Dondelinger, R. M. (2004). Anesthesia machines. Biomedical Instrumentation & Technology, 38(6), 445–449.
