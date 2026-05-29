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


# Resultados y analísis :

## Simulación de Bradicardia : 

<img width="637" height="472" alt="image" src="https://github.com/user-attachments/assets/1f07fff2-b0ea-4750-a0f4-7d8760c3eeb0" />

En la imagen se observa el monitor de signos vitales configurado para una simulación de bradicardia, donde la frecuencia cardíaca registrada es de 40 lpm, valor que se encuentra por debajo del rango normal para un adulto (60–100 lpm). Debido a esta condición, el sistema activa la alarma de bradicardia extrema, ya que el límite inferior configurado para la frecuencia cardíaca es de 35 lpm, indicando que el paciente se encuentra cerca de un umbral crítico. Además, se evidencia que las alarmas de frecuencia cardíaca y taquicardia están habilitadas, permitiendo la detección automática de alteraciones del ritmo cardíaco.

Por otro lado, la saturación periférica de oxígeno (SpO₂) se mantiene en 96 %, un valor considerado normal, lo que indica que, aunque existe una disminución importante de la frecuencia cardíaca, la oxigenación simulada del paciente sigue siendo adecuada. Esto demuestra que el monitor es capaz de identificar de manera independiente las variaciones de cada parámetro fisiológico y generar alertas específicas según la condición simulada. En general, la prueba confirma el correcto funcionamiento del sistema de alarmas y la capacidad del monitor para detectar eventos de bradicardia y advertir oportunamente al personal clínico.

## Simulación de Baja perfusión : 

<img width="636" height="466" alt="image" src="https://github.com/user-attachments/assets/49989838-b64f-41b6-9c2d-2bd4d16b54ae" />

En la imagen se observa una simulación de baja perfusión, condición en la que el flujo sanguíneo hacia los tejidos periféricos disminuye significativamente. El monitor registra una frecuencia cardíaca de 80 lpm, valor que se encuentra dentro del rango fisiológico normal, mientras que la SpO₂ muestra un valor de 100 %. A pesar de que la saturación es adecuada, el monitor genera una alarma de SpO₂ alta (>97 %) debido a la configuración de los límites de alarma establecida durante la práctica.

La señal fotopletismográfica (Pleth) continúa siendo visible, aunque en una condición real de baja perfusión esta señal suele presentar menor amplitud y puede verse más susceptible al ruido y a las interferencias. Esto ocurre porque la pulsioximetría depende de los cambios de volumen sanguíneo en los tejidos para calcular la saturación de oxígeno; cuando el flujo sanguíneo disminuye, la calidad de la señal puede deteriorarse y afectar la precisión de la medición.

Esta prueba permite evidenciar una de las limitaciones de los sistemas de pulsioximetría, ya que en situaciones de perfusión deficiente el monitor puede presentar lecturas inestables o incluso generar falsas alarmas debido a la baja calidad de la señal recibida. Sin embargo, el hecho de que el equipo continúe detectando la frecuencia cardíaca y la saturación demuestra que el sistema mantiene la capacidad de monitoreo bajo condiciones de señal reducida.

En conclusión, la simulación de baja perfusión permitió evaluar el comportamiento del monitor ante una condición clínica que puede afectar la calidad de la señal fotopletismográfica. Los resultados muestran la importancia de interpretar las lecturas de SpO₂ junto con el contexto clínico del paciente y la calidad de la señal mostrada por el equipo para evitar diagnósticos erróneos o falsas alarmas.

## Simulación de Hipoxia : 

<img width="655" height="490" alt="image" src="https://github.com/user-attachments/assets/9c8dc9d8-2477-4a0b-b15b-6f5c2155c641" />

En la imagen se observa una simulación de hipoxia, condición en la cual existe una disminución de la cantidad de oxígeno disponible en la sangre. El monitor registra una frecuencia cardíaca de 80 lpm, valor que se encuentra dentro del rango normal para un adulto, mientras que la saturación periférica de oxígeno (SpO₂) es de 85 %, un valor considerablemente inferior al rango normal (95–100 %). Debido a esta disminución, el monitor activa la alarma de SpO₂ baja, ya que el límite inferior de alarma fue configurado en 90 %, indicando una posible situación de riesgo para el paciente.

Además, se puede observar una señal fotopletismográfica (Pleth) estable y bien definida, lo que indica que el sensor está detectando correctamente la señal pulsátil simulada. La presencia de esta señal confirma que la alarma generada está asociada a una disminución real del valor de saturación configurado en el simulador y no a una pérdida de señal o mala conexión del sensor. En un entorno clínico, una SpO₂ del 85 % podría indicar problemas respiratorios o una oxigenación insuficiente de los tejidos, por lo que requeriría una intervención inmediata.

En general, esta prueba demuestra que el monitor uMEC 100 responde adecuadamente ante condiciones de hipoxia simulada, detectando la disminución de la saturación de oxígeno y activando las alarmas visuales y sonoras correspondientes. Esto evidencia la importancia de los sistemas de monitoreo continuo para la detección temprana de eventos que puedan comprometer la seguridad del paciente.

## Simulación de Taquicardia : 

<img width="885" height="652" alt="image" src="https://github.com/user-attachments/assets/3c8a0b32-ce44-43af-badf-601cd873eb08" />

En la imagen se observa una simulación de taquicardia, donde el monitor registra una frecuencia cardíaca de 140 lpm, valor que supera el rango normal para un adulto en reposo (60–100 lpm). Debido a esta condición, el sistema activa la alarma de frecuencia cardíaca alta (FC > 120 lpm), indicando que el valor medido excede el límite superior configurado en el monitor. Esta respuesta demuestra que el equipo es capaz de detectar oportunamente alteraciones en el ritmo cardíaco y alertar al personal clínico ante una posible situación de riesgo.

Por otra parte, la saturación periférica de oxígeno (SpO₂) presenta un valor de 98 %, el cual se encuentra dentro del rango fisiológico normal. Esto indica que, aunque la frecuencia cardíaca está aumentada, la oxigenación simulada del paciente continúa siendo adecuada. Asimismo, la señal fotopletismográfica muestra una mayor frecuencia de pulsos, evidenciando el incremento en la velocidad de los latidos cardíacos generado por el simulador.

Desde el punto de vista clínico, la taquicardia puede estar asociada a diferentes condiciones como ejercicio físico, estrés, fiebre, hipovolemia, alteraciones cardíacas o respuestas compensatorias del organismo. Por esta razón, la detección temprana de este evento es importante para prevenir complicaciones y permitir una intervención oportuna.

En conclusión, la prueba permitió verificar que el monitor uMEC 100 identifica correctamente una condición de taquicardia simulada, mostrando el aumento de la frecuencia cardíaca y activando las alarmas correspondientes. Esto confirma la utilidad de los sistemas de monitoreo continuo para la vigilancia de pacientes y la detección rápida de alteraciones cardiovasculares.

## Analísis General :

Durante la práctica se evaluó el desempeño del monitor de signos vitales uMEC 100 mediante la simulación de diferentes condiciones fisiológicas y patológicas utilizando el simulador Pronk OxSim OX-1. Las pruebas realizadas incluyeron escenarios de bradicardia, hipoxia, baja perfusión y taquicardia, permitiendo verificar la capacidad del monitor para medir correctamente la frecuencia cardíaca y la saturación periférica de oxígeno, así como la efectividad de sus sistemas de alarma.

En la simulación de bradicardia, el monitor detectó una frecuencia cardíaca de 40 lpm y generó las alertas correspondientes, demostrando una adecuada capacidad para identificar frecuencias cardíacas anormalmente bajas. De igual manera, en la condición de taquicardia, el equipo registró una frecuencia de 140 lpm y activó la alarma de frecuencia cardíaca elevada, evidenciando una respuesta rápida ante alteraciones significativas del ritmo cardíaco.

Por otra parte, durante la simulación de hipoxia, la saturación de oxígeno disminuyó hasta un valor de 85 %, provocando la activación de la alarma de SpO₂ baja. Este comportamiento confirmó que el monitor es capaz de detectar niveles críticos de oxigenación y advertir oportunamente sobre posibles situaciones de riesgo para el paciente. Asimismo, en la prueba de baja perfusión se observó cómo la calidad de la señal fotopletismográfica puede verse afectada cuando disminuye el flujo sanguíneo periférico, lo que demuestra la importancia de interpretar las mediciones considerando tanto los valores mostrados como la calidad de la señal adquirida.

En general, los resultados obtenidos muestran que el monitor uMEC 100 presentó un funcionamiento adecuado durante todas las pruebas realizadas, registrando correctamente los valores simulados y activando las alarmas configuradas cuando las variables excedieron los límites establecidos. Esto permitió comprobar la confiabilidad del equipo para el monitoreo continuo de pacientes y resaltar la importancia de las verificaciones periódicas mediante simuladores biomédicos para garantizar la seguridad y precisión de los sistemas de monitoreo clínico.

# Conclusiones : 

Durante el desarrollo de la práctica se logró evaluar el funcionamiento del monitor de signos vitales uMEC 100 mediante la simulación de diferentes condiciones cardiovasculares y hemodinámicas utilizando el simulador Pronk OxSim OX-1. Los resultados obtenidos demostraron que el equipo es capaz de medir adecuadamente la frecuencia cardíaca y la saturación periférica de oxígeno, además de activar correctamente las alarmas cuando los parámetros simulados superan los límites establecidos. Esto permitió comprender la importancia de los sistemas de monitoreo continuo en la detección temprana de alteraciones fisiológicas que puedan comprometer la seguridad del paciente.

Asimismo, la práctica permitió evidenciar algunas limitaciones asociadas a la medición de parámetros fisiológicos, especialmente en condiciones de baja perfusión, donde la calidad de la señal puede afectar la precisión de las lecturas y generar posibles falsas alarmas. En general, se concluye que el uso de simuladores biomédicos constituye una herramienta fundamental para verificar el desempeño de los monitores de signos vitales, ya que permite realizar pruebas funcionales de manera segura y controlada, contribuyendo al aseguramiento de la calidad y confiabilidad de los equipos utilizados en el entorno clínico.

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
