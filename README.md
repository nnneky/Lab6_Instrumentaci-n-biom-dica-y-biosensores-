# Laboratorio 6 | Instrumentación biomédica y biosensores 

 - Daniel Espinosa 5600778
 - Samuel Velandia 5600777

## Introducción :


El monitoreo de variables cardiovasculares y hemodinámicas es una herramienta fundamental dentro de los entornos clínicos, ya que permite conocer en tiempo real el estado fisiológico de un paciente y detectar oportunamente posibles alteraciones que puedan comprometer su salud. Variables como la frecuencia cardíaca y la saturación periférica de oxígeno (SpO₂) son ampliamente utilizadas para evaluar el funcionamiento de los sistemas cardiovascular y respiratorio. Para garantizar que los monitores de signos vitales proporcionen mediciones confiables, es necesario realizar pruebas funcionales utilizando simuladores biomédicos capaces de reproducir diferentes condiciones fisiológicas y patológicas.

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

Los monitores de signos vitales son dispositivos biomédicos diseñados para medir, visualizar y registrar continuamente estos parámetros. Además de mostrar los valores medidos, cuentan con sistemas de alarmas visuales y sonoras que se activan cuando las variables fisiológicas superan los límites establecidos, permitiendo al personal médico actuar de manera rápida ante posibles situaciones de riesgo.

Para verificar el correcto funcionamiento de estos equipos se emplean simuladores biomédicos como el Pronk OxSim OX-1. Este dispositivo es capaz de generar señales equivalentes a las que produciría un paciente real, simulando diferentes frecuencias cardíacas, niveles de saturación de oxígeno y condiciones clínicas específicas. Gracias a estas características, los simuladores permiten realizar pruebas funcionales, evaluar la exactitud de las mediciones y comprobar la respuesta de los sistemas de alarma sin poner en riesgo la seguridad de un paciente.

# Procedimiento : 

Inicialmente se realizó una revisión bibliográfica sobre el monitor de signos vitales uMEC 100 y el simulador Pronk OxSim OX-1, consultando información técnica y manuales de operación para conocer sus características, funciones y procedimientos de configuración. Posteriormente, se encendió el monitor y se configuró en modo monitor para habilitar la visualización de los parámetros fisiológicos.

Después de la configuración inicial, se conectó el sensor de pulsioximetría del monitor al simulador OxSim OX-1. Se programó una condición de bradicardia con una frecuencia cardíaca de 40 bpm y una saturación de oxígeno del 95 %, registrando los valores mostrados por el monitor y calculando los errores absolutos y porcentuales entre los valores simulados y los medidos.

Posteriormente se configuraron los límites de alarma para la saturación de oxígeno y se realizaron simulaciones de hipoxia modificando los valores de SpO₂. Durante estas pruebas se observó la activación de las alarmas visuales y sonoras, registrando los tiempos de respuesta y verificando el comportamiento de la señal fotopletismográfica mostrada en la pantalla del monitor.

Finalmente, se simularon condiciones de baja perfusión y taquicardia para evaluar nuevamente la capacidad de respuesta del sistema de monitoreo. Todos los resultados obtenidos fueron analizados y comparados con los valores de referencia suministrados por el simulador, permitiendo determinar la precisión y confiabilidad del monitor de signos vitales.
