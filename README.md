# Reconocimiento de partes y funcionamiento de una máquina de anestesia

# 1. INTRODUCCIÓN
La anestesia es un procedimeinto médico que se realiza tanto en cirugías como entros procedimientos diagnósticos, esto por la supresión temporal de la sensibilidad, el dolor y de consciencia del paciente. Para su administracion se requieren equipos medicos espcializados, los cuales suministran gases medicinales, tambien controlan la concentracion de agentes anestésicos y proporcionan soporte ventilatorio de ser necesario. Para cumplir con sus funciones este equipo integra diferentes subsistemas electricos y mecanicos los cuales trabajan conjuntamente. 

Sus componentes principales, esta el suministro de gases, los reguladores de presión, los flujómetros, los vaporizadores, el circuito de respiración, el sistema de absorción de dióxido de carbono, el ventilador mecanico y los sistemas de monitorización y alarmas. Para la ingenieria biomedica comprender el funcionamiento de estos equipos es crucial para identificar sus componentes, reconocer fallas, verificar su funcionamiento optimo.

En esta práctica se utilizó la máquina de anestesia Mindray WATO EX-20, identificando sus principales subsistemas y analizando los principios físicos y fisiológicos que permiten su funcionamiento.

# 2. MARCO TEÓRICO

La anestesia es un estado donde el paciente es inducido farmacológicamente,  este permite realizar procedimientos médicos y quirúrgicos evitando la percepción del dolor. Dependiendo del tipo de anestesia, esta puede producir pérdida de sensibilidad en una región específica del cuerpo o afectar el estado de consciencia. Los agentes anestésicos actúan sobre diferentes estructuras y mecanismos del sistema nervioso central y sistema periférico, modificando asi la transmisión de señales nerviosas relacionadas con la sensibilidad, el dolor, la memoria y el estado de consciencia. La selección del procedimiento anestésico depende de factores como el tipo de cirugía, procedimeinto, las condiciones clínicas del paciente, y los posibles riesgos. [1]


## 2.1. Tipos de anestesia

### 2.1.1. Anestesia general

Es un estado farmacológicamente inducido donde se genera una pérdida reversible de la consciencia, una ausencia de respuesta a estímulos dolorosos y la disminución o pérdida de determinados reflejos protectores. Es utilizada principalmente en procedimientos quirúrgicos complejos que requieren que el paciente permanezca inconsciente durante toda la intervención. Puede ser administrada mediante via intravenosa o inhalatoria, durante la anestesía genral es necesario vigilar la frecuencia cardiaca, la presion arterial, la saturación de oxigeno, la ventilación y la concentración de dióxido de carbono. Con la maquina de anestesia se controla el suministro de gases, la administración de agentes anestésicos inhalados y proporcionar ventilación mecánica. [2][3]

### 2.1.2. Anestesia regional

Esta anestesia bloquea temporalmente la transmisión de señales nerviosas en una región determinada del cuerpo, para asi evitar que el paciente perciba dolor en esa zona especifica. No necesariamente produce perdida de conciencia, por lo que el paciente permanece despierto durante el procedimeinto. Se utiliza en procedimientos de las extremidades, cirugías abdominales inferiores y procedimientos obstétricos, entre otros.[1]

### 2.1.3. Anestesia local

Consiste en bloquear la sensibilidad de una zona pequeña y específica del cuerpo mediante la administración de anestésicos locales. Estos medicamentos actúan principalmente bloqueando los canales de sodio dependientes de voltaje de las membranas neuronales, impidiendo la propagación del potencial de acción y asi impidiendo la transmisión de señales dolorosas. Se utiliza principalmente en procedimientos odontológicos, suturas, pequeñas intervenciones dermatológicas.

### 2.1.4. Sedación monitorizada

Esta es una técnica farmacológica que produce diferentes grados de disminución del estado de alerta, relajación y respuesta a estímulos.

Se clasifica habitualmente en:

- **Sedación mínima:** el paciente permanece despierto y responde normalmente a estímulos verbales.
- **Sedación moderada:** el paciente responde intencionalmente a estímulos verbales o táctiles.
- **Sedación profunda:** el paciente presenta una disminución importante del estado de consciencia y puede requerir asistencia para mantener la vía aérea.

Se utiliza en procedimientos endoscópicos, intervenciones odontológicas y procedimientos diagnósticos que requieren disminuir la ansiedad y las molestias del paciente.


## 2.4. Máquina de anestesia Mindray WATO EX-20

La Mindray WATO EX-20 es una estación de anestesia diseñada para pacientes adultos y pediatricos para un procedimientos de anestesia general. Integra sistemas de suministro de gases, vaporización de agentes anestésicos, ventilación y monitorización.
Este quipo cuenta con:
- Pantalla LCD para visualizar parámetros y formas de onda.
- Ventilador electrónico de accionamiento neumático.
- Modos de ventilación manual y mecánica.
- Control de volumen y control de presión.
- Circuito de respiración con sistema de absorción de CO₂.
- Posibilidad de utilizar hasta dos vaporizadores, según configuración.
- Sistemas de alarmas para identificar condiciones anormales.

El fabricante describe los modos de ventilación manual, VCV, control por presión y VISO dentro de las características de esta serie.[5]

## 2.5. Sistema de suministro de gases medicinales
Los gases utilizados habitualmente son:
- Oxígeno (O₂)
- Óxido nitroso (N₂O)
- Aire medicinal
- Agentes anestésicos inhalatorios

## 2.6. Sistemas de presión de la máquina de anestesia

El funcionamiento neumático de una máquina de anestesia se organiza en tres sistemas de presión:

### Sistema de alta presión

Su función consiste en recibir el gas almacenado a alta presión y permitir su reducción mediante reguladores.

### Sistema de presión intermedia

Recibe los gases provenientes de los cilindros después de su regulación y de las redes centrales de suministro hospitalario. Donde permite mantener unas condiciones de presión adecuadas para el funcionamiento de los diferentes componentes.

### Sistema de baja presión

Se encuentra después de los sistemas de control de flujo y comprende los componentes encargados de preparar y conducir la mezcla de gases hacia el paciente. Su importancia se debe a que permite controlar la composición de la mezcla que llega al circuito respiratorio.

## 2.7. Vaporizador anestésico

El vaporizador se encarga de convertir un agente anestésico líquido en vapor y añadirlo de manera controlada a la mezcla de gases que será administrada al paciente.

## 2.8. Sistema de respiración

El sistema de respiración es el conjunto de componentes que permite conducir los gases desde la máquina de anestesia hasta el paciente y tambien facilitar el retorno de los gases espirados. Permite controlar el intercambio de gases y reducir el consumo de gases medicinales y agentes anestésicos.

## 2.9. Absorción de dióxido de carbono (CO₂)

Durante la respiración celular, el organismo produce dióxido de carbono, que es transportado por la sangre hacia los pulmones para ser eliminado en la espiración. Es necesario eliminar el CO₂ antes de que el gas vuelva a ser inspirado.
Para cumplir esta función se utiliza un recipiente absorbente que contiene sustancias químicas, generalmente cal sodada esta reacciona con el dióxido de carbono mediante un proceso químico que permitiendo su retención y evitando su reinhalación.

## 2.10. Ventilación mecánica

La ventilación mecánica proporciona movimiento de gases hacia los pulmones con ayuda de un dispositivo externo cuando se requiere asistencia o sustitución de la ventilación espontánea.

Entre los modos de ventilación utilizados en la WATO EX-20 estan:

**Ventilación controlada por volumen (VCV):** el ventilador administra un volumen corriente previamente establecido durante cada ciclo respiratorio.

**Ventilación controlada por presión (PCV):** el ventilador administra gas hasta alcanzar una presión inspiratoria determinada, manteniendo dicha presión durante el tiempo inspiratorio establecido.

**Ventilación manual:** permite que el operador proporcione ventilación mediante la bolsa reservorio y controle la presión máxima del circuito utilizando la válvula APL.

**VISO:** corresponde a un modo de ventilación espontánea identificado por el fabricante para esta serie. Su funcionamiento específico debe verificarse en el manual de usuario de la versión instalada.

## 2.11. Válvula APL

La válvula APL (Adjustable Pressure Limiting) es un componente del sistema respiratorio que permite controlar la presión máxima del circuito durante la ventilación manual.
Liberar el exceso de gas cuando la presión del circuito alcanza el valor establecido. De esta manera ayuda a evitar un aumento en la presión del sistema respiratorio. Su regulación se realiza de acuerdo con las condiciones clínicas del paciente y las indicaciones del profesional responsable.

## 2.12. Sistema de reserva

El sistema de reserva es un componente mecánico que forma parte del sistema de ventilación de la máquina de anestesia. Este permite almacenar temporalmente los gases y facilitar su administración durante los ciclos de ventilación mecánica.

## 2.13. Monitorización y sistemas de seguridad

La monitorización permite evaluar continuamente el estado del paciente y el comportamiento adecuado del equipo durante algun procedimiento.

Entre las variables que pueden monitorizarse se encuentran:

| Parámetro | Descripción |
|---|---|
| FiO₂ | Fracción inspirada de oxígeno. |
| SpO₂ | Saturación periférica de oxígeno. |
| EtCO₂ | Concentración de dióxido de carbono al final de la espiración. |
| Ppico | Presión máxima de la vía aérea. |
| Pmedia | Presión media de la vía aérea. |
| TV | Volumen corriente. |
| MV | Volumen minuto. |
| Frecuencia respiratoria | Número de ciclos respiratorios por minuto. |

Los sistemas de alarma permiten advertir sobre condiciones como presión excesiva, volumen minuto bajo, apnea, desconexión del circuito y fallas en el suministro de gases.
La correcta interpretación de estas variables permite identificar alteraciones en el funcionamiento del equipo y responder oportunamente ante situaciones de riesgo.


# 3. PARTE A. DESARROLLO DE LAS PREGUNTAS

## 3.1. Pregunta A: ¿Cuántos y cuáles son los tipos de anestesia que comúnmente se aplican durante una cirugía? Explique cada uno.

**1. Anestesia general:**

Produce pérdida reversible de la consciencia y ausencia de respuesta a estímulos dolorosos. Se utiliza en procedimientos quirúrgicos mayores y puede administrarse por vía intravenosa o inhalatoria. Durante su aplicación puede requerirse ventilación mecánica y monitorización continua de las funciones cardiovasculares y respiratorias.

**2. Anestesia regional:**

Bloquea la transmisión nerviosa en una región determinada del cuerpo. El paciente puede permanecer consciente, ya que la pérdida de sensibilidad se limita al área intervenida. Sus principales técnicas son la anestesia epidural, espinal y los bloqueos nerviosos periféricos.

**3. Anestesia local:**

Produce pérdida temporal de sensibilidad en una zona pequeña y específica. Actúa principalmente mediante el bloqueo de los canales de sodio de las neuronas, impidiendo la propagación de impulsos nerviosos relacionados con el dolor. Se utiliza en procedimientos odontológicos, suturas y pequeñas intervenciones quirúrgicas.

**4. Sedación monitorizada:**

Consiste en administrar medicamentos que disminuyen el estado de alerta, producen relajación y reducen la ansiedad del paciente. Puede variar desde sedación mínima hasta profunda, dependiendo de la dosis y del medicamento utilizado. Se emplea en procedimientos diagnósticos y terapéuticos que no necesariamente requieren anestesia general.

En conclusión, la selección del tipo de anestesia depende de las características del procedimiento, las condiciones del paciente y la valoración del anestesiólogo.

## 3.2. Pregunta B: ¿Con cuáles gases trabaja una máquina de anestesia y qué función cumple cada uno? ¿Cuáles de ellos se incorporan a la máquina mediante sistema de alta presión?

La máquina de anestesia utiliza principalmente oxígeno, óxido nitroso y aire medicinal. Adicionalmente, puede administrar agentes anestésicos inhalatorios mediante vaporizadores.

| Gas o agente | Función |
|---|---|
| Oxígeno (O₂) | Permite mantener la oxigenación del paciente y es fundamental para el metabolismo celular. |
| Óxido nitroso (N₂O) | Tiene propiedades anestésicas y analgésicas. Se utiliza como complemento de otros agentes anestésicos. |
| Aire medicinal | Permite complementar la mezcla respiratoria y controlar la concentración de oxígeno administrada. |
| Sevoflurano | Agente anestésico volátil utilizado para inducir y mantener la anestesia general. |
| Isoflurano | Agente anestésico inhalatorio utilizado para el mantenimiento de la anestesia. |
| Desflurano | Agente anestésico volátil utilizado en determinados procedimientos anestésicos. |

**Sistema de alta presión:**

Los gases que ingresan mediante los cilindros de reserva pasan inicialmente por el sistema de alta presión. En las configuraciones correspondientes, estos pueden ser:

- Oxígeno.
- Óxido nitroso.
- Aire medicinal, cuando el equipo dispone de conexión de cilindro para este gas.

En este sistema, los gases se encuentran almacenados a presiones elevadas y posteriormente pasan por reguladores que reducen su presión a niveles adecuados para el funcionamiento del equipo.

Es importante diferenciar el suministro mediante cilindros del suministro mediante la red central hospitalaria. La red central ingresa al equipo mediante conexiones de suministro de presión intermedia, mientras que los cilindros constituyen una fuente de reserva.

Los agentes anestésicos volátiles no ingresan como gases comprimidos por el sistema de alta presión. Se almacenan como líquidos y se incorporan a la mezcla respiratoria mediante los vaporizadores correspondientes.

## 3.3. Pregunta C: ¿Qué es el sistema de respiración en la máquina de anestesia y cuál es su función? ¿Qué partes de este sistema podrían esterilizarse por medio de autoclave?

El sistema de respiración es el conjunto de elementos que permite transportar la mezcla de gases anestésicos desde la máquina hasta el paciente y conducir los gases espirados nuevamente hacia el circuito.

Su función principal consiste en garantizar el suministro de gases durante la inspiración, permitir la eliminación del dióxido de carbono y facilitar el control de la ventilación del paciente.

En la máquina de anestesia se utiliza un circuito circular que permite la reutilización parcial de los gases espirados después de eliminar el CO₂ mediante el recipiente absorbente.

**Componentes principales:**

1. **Rama inspiratoria:** conduce la mezcla de gases desde la máquina hacia el paciente.
2. **Rama espiratoria:** transporta los gases exhalados desde el paciente hacia el sistema.
3. **Válvulas unidireccionales:** permiten mantener el sentido adecuado del flujo de gases.
4. **Recipiente absorbente de CO₂:** contiene el material encargado de eliminar el dióxido de carbono.
5. **Bolsa reservorio:** permite almacenar temporalmente los gases y facilitar la ventilación manual.
6. **Válvula APL:** regula la presión máxima del circuito durante la ventilación manual.
7. **Conector en Y:** une las ramas inspiratoria y espiratoria con la conexión del paciente.

**Esterilización mediante autoclave:**

El autoclave utiliza vapor de agua saturado a presión y temperatura controladas para destruir microorganismos, incluidas las esporas bacterianas.

En los sistemas de anestesia, algunos componentes desmontables y reutilizables del circuito respiratorio pueden ser compatibles con esterilización mediante autoclave, dependiendo de sus materiales y de las instrucciones del fabricante.

Entre los elementos que podrían ser esterilizables, siempre que el fabricante lo autorice, se encuentran:

- Determinados tubos respiratorios reutilizables.
- Conectores y piezas desmontables del circuito.
- Conectores en Y reutilizables.
- Algunos componentes de la bolsa manual.

**Importante:** no todos los elementos del sistema de respiración pueden someterse a autoclave. Los sensores electrónicos, sensores de flujo, componentes internos, válvulas y piezas fabricadas con materiales sensibles al calor pueden deteriorarse.

Por tanto, para la máquina WATO EX-20 se debe consultar el manual de usuario y las instrucciones de reprocesamiento de cada accesorio antes de aplicar cualquier método de esterilización. No debe asumirse que un componente es autoclavable únicamente porque pueda desmontarse.

## 3.4. Pregunta D: ¿Cuántos y cuáles son los submenús del ventilador? ¿En qué consiste cada uno? ¿En cuál de ellos se puede activar la pausa inspiratoria?

En la máquina de anestesia Mindray WATO EX-20, la configuración del ventilador permite seleccionar diferentes modos de ventilación y establecer los parámetros respiratorios correspondientes.

De acuerdo con las características del fabricante, se identifican los siguientes modos principales:

**1. Ventilación manual:**

Permite proporcionar ventilación al paciente mediante la bolsa reservorio. El operador controla manualmente la ventilación y regula la presión máxima del circuito utilizando la válvula APL.

**2. Ventilación controlada por volumen (VCV):**

El ventilador administra un volumen corriente previamente establecido en cada ciclo respiratorio. La presión alcanzada depende de las características mecánicas del sistema respiratorio, especialmente de la distensibilidad pulmonar y la resistencia de las vías aéreas.

**3. Ventilación controlada por presión (PCV):**

El ventilador administra gas hasta alcanzar una presión inspiratoria determinada. Durante la inspiración mantiene la presión establecida y el volumen suministrado depende de las características del sistema respiratorio.

**4. VISO:**

Es un modo de ventilación espontánea identificado por Mindray para esta serie. Su funcionamiento y parámetros específicos deben consultarse en el manual de operación correspondiente a la versión del equipo.

**Pausa inspiratoria:**

La pausa inspiratoria es un intervalo que se introduce al final de la inspiración durante el cual se interrumpe temporalmente el flujo de gas antes de iniciar la espiración.

Durante este periodo, la presión de la vía aérea tiende a equilibrarse con la presión alveolar, lo que permite evaluar la presión de meseta cuando se cumplen las condiciones necesarias.

En el modo VCV de la WATO EX-20, el parámetro relacionado con esta función aparece como **TIP:TI (tiempo de pausa inspiratoria respecto al tiempo inspiratorio)**.

Por lo tanto, la pausa inspiratoria se configura en el modo de ventilación controlada por volumen (VCV), mediante el ajuste del parámetro TIP:TI.

---

## Parte B
### 1. Identifique y ubique las siguientes partes de la máquina de anestesia WATOEX-20, explicando su función.
a. Vaporizador
<img width="1056" height="340" alt="image" src="https://github.com/user-attachments/assets/36b1874f-a889-4b94-b018-2dbc220f2285" />  

<p align="center">
<b>Figura 1.</b> Vaporizador.
</p>
Se encuentra en la parte superior de la máquina, sobre el sistema de administración de gases frescos, en el soporte destinado a los vaporizadores.Transforma el anestésico líquido volátil en vapor y lo incorpora, en una concentración controlada, a la mezcla de gases frescos que recibe el paciente. Permite administrar agentes anestésicos inhalatorios, como sevoflurano o isoflurano, según el vaporizador instalado. [11]  

b. Válvula APL
<img width="1056" height="340" alt="image" src="https://github.com/user-attachments/assets/36b1874f-a889-4b94-b018-2dbc220f2285" />  

<p align="center">
<b>Figura 2.</b> Válvula APL
</p>
Se encuentra en el sistema respiratorio, en la zona frontal del circuito de ventilación manual, cerca de la bolsa reservorio. Regula y limita la presión dentro del circuito durante la ventilación manual. Permite liberar el exceso de gases hacia el sistema de evacuación de gases anestésicos (AGSS), evitando que se produzcan presiones excesivas en el circuito respiratorio del paciente. [11]  

c. Recipiente absorbente de CO2
<img width="1056" height="340" alt="image" src="https://github.com/user-attachments/assets/36b1874f-a889-4b94-b018-2dbc220f2285" />  

<p align="center">
<b>Figura 3.</b> Recipiente absorbente de CO2.
</p>
Se encuentra en la parte inferior del sistema respiratorio, conectado al circuito circular de ventilación.Contiene un material absorbente, generalmente cal sodada, que elimina el dióxido de carbono (CO₂) del aire espirado por el paciente. Esto permite reutilizar los gases restantes del circuito, evitando la reinhalación de concentraciones perjudiciales de CO₂. [11]  

d. Fuelle
<img width="1056" height="340" alt="image" src="https://github.com/user-attachments/assets/36b1874f-a889-4b94-b018-2dbc220f2285" />  

<p align="center">
<b>Figura 4.</b> Fuelle.
</p>
Se encuentra en el compartimento del sistema respiratorio, dentro de una carcasa transparente ubicada en la parte superior del circuito respiratorio.Es un componente fundamental para la ventilación mecánica. Se expande y comprime mediante la acción del gas impulsor, permitiendo movilizar un volumen determinado de gas hacia los pulmones del paciente durante la inspiración. También permite observar visualmente el movimiento respiratorio y detectar posibles alteraciones en la ventilación. [11] 

### 2. Si el ventilador muestra el mensaje “batería en uso” y el paciente se encuentra conectado a la máquina ¿Qué acción debería ejecutarse?
Se debe verificar inmediatamente la conexión eléctrica de la máquina a la red de corriente alterna (AC), comprobando que el cable de alimentación esté correctamente conectado y que el tomacorriente tenga suministro eléctrico. Mientras se verifica la alimentación, se debe mantener la vigilancia continua de la ventilación del paciente y comprobar que el ventilador continúe funcionando correctamente.  

Si la máquina está funcionando con batería, significa que ha perdido la alimentación eléctrica externa y está utilizando su batería interna como respaldo. Por tanto, se debe restablecer la conexión a la red eléctrica lo antes posible, sin desconectar al paciente ni interrumpir la ventilación, si la alimentación eléctrica está correctamente conectada y el mensaje persiste, se debe solicitar la revisión del sistema eléctrico por parte del personal de ingeniería biomédica. [11]  

### 3. ¿Con qué frecuencia debería reemplazarse el recipiente absorbente de CO2?
El recipiente absorbente de CO₂ debe reemplazarse cuando el material absorbente (cal sodada) haya perdido su capacidad para eliminar adecuadamente el dióxido de carbono, no existe un intervalo de tiempo único que garantice su reemplazo, ya que su duración depende de factores como:  
- La cantidad de pacientes atendidos.   
- El flujo de gases frescos utilizado.  
- La duración de los procedimientos anestésicos.  
- La cantidad de CO₂ producido por el paciente.  
- El grado de agotamiento del material absorbente.
   
Se debe vigilar el cambio de color del indicador de la cal sodada, cuando el producto lo incorpora, y especialmente la concentración de CO₂ inspirado mediante la monitorización capnográfica. Si se detecta reinhalación de CO₂ o agotamiento del absorbente, debe reemplazarse.  
### 4. ¿Cuál es el procedimiento para verificar si hay fuga en el cilindro de alta presión?
De acuerdo con el manual de servicio de la Mindray WATO EX-20, la prueba de fugas del cilindro de alta presión se realiza de la siguiente manera:
1. Colocar el interruptor del sistema en posición de apagado.
2. Cerrar el flujómetro de oxígeno auxiliar, si la máquina cuenta con este accesorio.
3. Girar todos los controles de flujo completamente en sentido horario, hasta alcanzar el flujo mínimo.
4. Abrir lentamente la válvula del cilindro que se desea verificar.
5. Registrar la presión inicial indicada en el manómetro del cilindro.
6. Cerrar la válvula del cilindro.
7. Esperar un minuto y registrar nuevamente la presión indicada en el manómetro.
8. Comparar ambas mediciones para identificar posibles pérdidas de presión.
   
Criterios para identificar una fuga:   
- Para el gas impulsor (Drive Gas), se considera que existe una fuga si la presión disminuye más de 5000 kPa (725 psi).
- Para los gases que no son impulsores, se considera que existe una fuga si la presión disminuye más de 690 kPa (100 psi).

Si se identifica una fuga, se debe instalar una junta nueva en el cilindro y repetir la prueba. Si la fuga continúa, no se debe utilizar el sistema de suministro del cilindro y se debe solicitar la revisión técnica correspondiente. [11]

### 5. ¿Influye el contar o no con el sensor de O2 al hacer la prueba sobre el sistema de control de flujo? ¿De qué forma?  
Sí, influye directamente, porque la presencia del sensor de oxígeno modifica la forma de comprobar el funcionamiento del sistema de control de flujo y la seguridad de la mezcla de gases.
El manual de servicio de Mindray establece dos procedimientos:  

Cuando la máquina NO cuenta con sensor de O₂: 

1. Se verifica que los flotadores de los flujómetros se desplacen suavemente.
2. Se comprueba el funcionamiento del sistema de enlace entre oxígeno (O₂) y óxido nitroso (N₂O).
3. Se verifica que, al aumentar el flujo de N₂O, el flujo de O₂ aumente proporcionalmente.
4. También se comprueba que, al disminuir el flujo de O₂, el sistema reduzca el flujo de N₂O para mantener las proporciones de seguridad establecidas. En este caso, la comprobación se realiza principalmente mediante las lecturas de los flujómetros y las relaciones de flujo establecidas por el fabricante. [11]

Cuando la máquina SÍ cuenta con sensor de O₂:  
1. Primero se debe comprobar que el sensor esté correctamente calibrado.
2. Se verifica el funcionamiento del sistema de enlace O₂-N₂O.
3. Al aumentar el flujo de N₂O, el flujo de O₂ debe aumentar proporcionalmente.
4. Al disminuir el flujo de O₂, el flujo de N₂O debe disminuir. Además, el sensor permite comprobar directamente la concentración de oxígeno de la mezcla, la cual debe mantenerse igual o superior al 25 % durante las pruebas indicadas por el fabricante. [11]
   
La principal diferencia es que, cuando existe un sensor de O₂, se puede verificar directamente la concentración de oxígeno de la mezcla de gases. Cuando no existe, la comprobación se realiza mediante los flujos indicados por los flujómetros y el funcionamiento del sistema de enlace. el sensor proporciona una verificación adicional, pero su ausencia no elimina la necesidad de realizar las pruebas de seguridad del sistema.  

### 6. ¿Para qué se requiere el sistema de presión negativa?
El sistema de presión negativa de la máquina de anestesia WATO EX-20 se utiliza para realizar la aspiración de secreciones y fluidos corporales del paciente, especialmente los presentes en la región faríngea, su funcionamiento se basa en el principio de Venturi: utiliza un flujo de aire u oxígeno como gas impulsor para generar presión negativa (vacío), permitiendo succionar secreciones, líquidos y vómito a través de una sonda de aspiración. Los principales componentes de este sistema son:  

- Generador de vacío Venturi: produce la presión negativa necesaria para la aspiración.  
- Regulador de presión negativa: permite ajustar el nivel de succión.  
- Manómetro: indica el nivel de presión negativa.  
- Frasco recolector: almacena temporalmente los líquidos aspirados.  
- Válvula de protección contra sobrellenado: evita que los líquidos lleguen al generador de vacío y ocasionen daños.  
- Filtro: ayuda a evitar la contaminación bacteriana del sistema. [11]  

## Parte C

  ### 1. DESARROLLO DEL PROCEDIMIENTO
Durante la práctica de reconocimiento de partes y funcionamiento de la máquina de anestesia Mindray WATO EX-20, se realizó una inspección general del equipo con el propósito de identificar sus principales componentes, comprender la función de cada subsistema y reconocer los principios de funcionamiento relacionados con la administración de gases y la ventilación mecánica.

El procedimiento desarrollado fue el siguiente:
### Paso 1. Reconocimiento general del equipo.

Se realizó una inspección visual de la máquina de anestesia Mindray WATO EX-20, identificando su estructura externa, pantalla de visualización, panel de control, conexiones para gases medicinales, soporte de vaporizadores y sistema respiratorio.

### Paso 2. Identificación del sistema de suministro de gases.

Se reconocieron las conexiones correspondientes al oxígeno, óxido nitroso y aire medicinal. Se explicó cómo estos gases ingresan al equipo desde las redes centrales o los cilindros de reserva y cómo sus presiones son reguladas antes de pasar al sistema de control de flujo.

### Paso 3. Reconocimiento de los vaporizadores.

Se identificó la ubicación de los vaporizadores y se explicó su función en la transformación del anestésico líquido en vapor. También se reconoció su importancia en el control de la concentración del agente anestésico que se incorpora a la mezcla de gases frescos.

### Paso 4. Identificación del sistema respiratorio.

Se inspeccionaron los componentes del circuito respiratorio, reconociendo las ramas inspiratoria y espiratoria, las válvulas unidireccionales, la bolsa reservorio, el recipiente absorbente de CO₂ y la válvula APL. Se explicó cómo estos elementos permiten conducir los gases hacia el paciente y facilitar el retorno de los gases espirados.

### Paso 5. Reconocimiento del sistema de ventilación mecánica.

Se identificó el fuelle ubicado en el compartimento respiratorio y se explicó su función durante la ventilación mecánica. Además, se revisaron conceptualmente los modos de ventilación disponibles, como ventilación controlada por volumen (VCV), ventilación controlada por presión (PCV), ventilación manual y VISO.

### Paso 6. Identificación de los sistemas de monitorización y alarma.

Se reconocieron los parámetros que pueden visualizarse en la pantalla, como la frecuencia respiratoria, el volumen corriente, la presión de la vía aérea, la concentración de oxígeno y el CO₂ al final de la espiración. Se explicó la importancia de las alarmas para advertir sobre condiciones anormales durante el funcionamiento.

### Paso 7. Reconocimiento de los sistemas de seguridad.

Se estudiaron las funciones de la batería interna, los sistemas de regulación de presión, las alarmas y los mecanismos de protección del circuito respiratorio. Se explicó la importancia de verificar las condiciones de alimentación eléctrica y suministro de gases antes de utilizar el equipo.

### Paso 8. Análisis del funcionamiento general.

Finalmente, se relacionaron los diferentes subsistemas para comprender cómo trabajan conjuntamente durante un procedimiento anestésico. Se identificó que el suministro de gases, la vaporización, la ventilación y la absorción de CO₂ son procesos fundamentales para garantizar el funcionamiento adecuado de la máquina.

La práctica se desarrolló mediante reconocimiento visual y explicación de los componentes, sin realizar intervenciones sobre un paciente.
## 13. ANÁLISIS DE RESULTADOS
### 13.1. Análisis 1. Fallas que pueden presentarse en los subsistemas de la máquina de anestesia y sus posibles causas.
La máquina de anestesia Mindray WATO EX-20 está compuesta por diferentes subsistemas que trabajan de manera coordinada para garantizar el suministro de gases medicinales, la administración de agentes anestésicos y la ventilación del paciente. Sin embargo, durante su funcionamiento pueden presentarse fallas mecánicas, neumáticas, eléctricas y electrónicas que afectan su desempeño y seguridad.

De acuerdo con el manual de servicio del fabricante, las principales fallas que pueden presentarse son las siguientes [11]:
### 1. Sistema de suministro de gases
- Fugas de gases: pueden producirse por daños en las mangueras, conexiones flojas o empaques deteriorados.
- Presión insuficiente de oxígeno: puede deberse a una baja presión en la red central, cilindros con poca reserva o fallas en los reguladores.
- Falla en el suministro del gas impulsor: puede estar relacionada con problemas en las conexiones, reguladores o sensores de presión.
Estas fallas pueden ocasionar un suministro inadecuado de gases y afectar el funcionamiento del ventilador.

### 2. Sistema de control y administración de gases
- Fugas en los flujómetros: pueden presentarse por deterioro de los sellos o daños en las conexiones internas.
- Falla en el botón de oxígeno rápido (O₂ Flush): puede producirse por desgaste o deterioro de sus elementos de sellado.
- Falla en la válvula de corte O₂-N₂O: puede impedir la regulación adecuada de la mezcla de gases.
- Fugas en el sistema de baja presión: pueden originarse por empaques deteriorados, conexiones defectuosas o daños en las tuberías.
Estas condiciones pueden alterar la concentración y el flujo de gases que se administran al paciente.

### 3. Sistema de vaporización
- Fugas en el conjunto del vaporizador: pueden producirse por empaques dañados, sellos deteriorados o una instalación incorrecta.
- Problemas en el acoplamiento: pueden impedir una conexión adecuada entre el vaporizador y su soporte.
- Dosificación inadecuada del agente anestésico: puede relacionarse con fallas de calibración o problemas internos del vaporizador.
Estas fallas pueden ocasionar una administración incorrecta del anestésico inhalatorio.

### 4. Sistema de ventilación mecánica
- Falla de los sensores de flujo: puede producir mediciones incorrectas del volumen corriente.
- Falla de los sensores de presión: puede generar errores en la medición de la presión de la vía aérea.
- Problemas en las válvulas inspiratoria, espiratoria o PEEP: pueden alterar el control del flujo y de las presiones respiratorias.
- Presión insuficiente durante la inspiración: puede presentarse por fugas, suministro insuficiente de gas impulsor o fallas en los componentes de control.
- Falla de comunicación del ventilador: puede relacionarse con problemas en los cables o tarjetas electrónicas.
Estas alteraciones pueden comprometer la ventilación adecuada del paciente.

### 5. Sistema respiratorio y absorción de CO₂
- Fugas en el circuito respiratorio: pueden producirse por tubos deteriorados, conexiones incorrectas o sellos defectuosos.
- Problemas en el fuelle: pueden deberse a una instalación incorrecta o al deterioro de su sistema de sellado.
- Fallas en la válvula APL: pueden impedir la regulación adecuada de la presión durante la ventilación manual.
- Instalación incorrecta del recipiente absorbente: puede ocasionar fugas en el circuito.
- Agotamiento del absorbente de CO₂: puede permitir la reinhalación de dióxido de carbono por parte del paciente.
Estas fallas pueden afectar la circulación de los gases y la eliminación del CO₂.

### 6. Sistema de monitorización y componentes electrónicos
- Falla del sensor de oxígeno: puede producir mediciones incorrectas de la concentración de O₂ debido a una calibración inadecuada, humedad o deterioro del sensor.
- Falla de los sensores de flujo y presión: puede generar valores incorrectos en los parámetros de monitorización.
- Fallas de comunicación entre tarjetas electrónicas: pueden ocasionar errores en la visualización y control de las funciones del equipo.
- Falla de la batería: puede impedir la autonomía del equipo durante una interrupción del suministro eléctrico.
- Falla de la pantalla o del panel de control: puede dificultar la configuración y visualización de los parámetros.
En general, las fallas identificadas pueden relacionarse con el desgaste de los componentes, el uso continuo del equipo, la falta de mantenimiento preventivo, las conexiones incorrectas, la contaminación por humedad y la ausencia de pruebas de funcionamiento antes de su utilización. [11], [12].
### 13.2. Análisis 2. Clasificación de los subsistemas según el número de fallas asociadas
A partir de la revisión del capítulo de solución de problemas del manual de servicio de la Mindray WATO EX-20, se realizó una clasificación de los subsistemas considerando la cantidad y variedad de fallas descritas para sus componentes.

Es importante aclarar que el fabricante no presenta una estadística de frecuencia real de fallas por subsistema. Por esta razón, el siguiente orden corresponde a una clasificación cualitativa de las fallas documentadas, agrupadas según el subsistema al que pertenecen, y no a una tasa estadística de ocurrencia.

<img width="748" height="377" alt="image" src="https://github.com/user-attachments/assets/66e0d88c-92b2-480e-a37f-fc8d605f5bce" />

De acuerdo con esta clasificación, el sistema de ventilación mecánica y el sistema respiratorio agrupan una mayor variedad de fallas, debido a que están conformados por diferentes componentes neumáticos, sensores, válvulas y elementos de medición que deben funcionar coordinadamente.

Por otra parte, las fugas en el suministro y la administración de gases representan condiciones importantes porque pueden alterar la composición y el flujo de la mezcla respiratoria. Asimismo, las fallas en los sistemas electrónicos y de monitorización pueden dificultar la identificación de parámetros incorrectos durante la operación.

Finalmente, aunque el sistema de vaporización presenta una menor variedad de fallas dentro de esta agrupación, su correcto funcionamiento es indispensable para garantizar una administración controlada de los agentes anestésicos. [11].

## 15. PREGUNTAS PARA LA DISCUSIÓN
## Pregunta 1. ¿Qué tipos de anestésicos son los más usados en cirugía?

Los anestésicos más utilizados durante los procedimientos quirúrgicos se clasifican principalmente en anestésicos inhalatorios e intravenosos. La selección depende del procedimiento, las condiciones clínicas del paciente y el tipo de anestesia que se requiere.

### 1. Anestésicos inhalatorios

Son administrados mediante la vía respiratoria y se utilizan principalmente para mantener la anestesia general.

Entre los más utilizados se encuentran:
- Sevoflurano: es un anestésico volátil utilizado para la inducción y el mantenimiento de la anestesia general. Se caracteriza por su rápida acción y recuperación.
- Isoflurano: se utiliza principalmente para el mantenimiento de la anestesia general durante procedimientos quirúrgicos.
- Desflurano: es un anestésico volátil que permite controlar rápidamente la profundidad anestésica.
- Óxido nitroso: posee propiedades analgésicas y se utiliza como complemento de otros agentes anestésicos.
### 2. Anestésicos intravenosos

Se administran directamente en el torrente sanguíneo y se utilizan principalmente para inducir la anestesia general o proporcionar sedación.

Entre ellos se encuentran:
- Propofol: es uno de los anestésicos intravenosos más utilizados para inducir y mantener la anestesia general.
- Ketamina: produce anestesia disociativa y tiene propiedades analgésicas.
- Etomidato: se utiliza principalmente para la inducción anestésica, especialmente cuando se busca mantener una mayor estabilidad cardiovascular.
- Tiopental: es un anestésico intravenoso utilizado para la inducción de la anestesia general.

También se utilizan medicamentos complementarios, como los opioides (fentanilo y remifentanilo), que ayudan a controlar el dolor, y los relajantes neuromusculares, como el rocuronio, que facilitan determinadas intervenciones quirúrgicas.

## Pregunta 2. ¿Qué diferencias plantea el modelo EX-35 con respecto al EX-20?
La Mindray WATO EX-35 es una estación de anestesia que incorpora características adicionales respecto al modelo WATO EX-20, principalmente en la interfaz de usuario, los modos de ventilación, la monitorización y las funciones de seguridad.

Las principales diferencias son:

<img width="758" height="537" alt="image" src="https://github.com/user-attachments/assets/8ada67f2-9272-4494-a4f6-7b58cd2a8934" />

El modelo EX-35 también incorpora funciones como la identificación automática de agentes anestésicos mediante módulos compatibles y el cambio automático del gas impulsor, lo que mejora la continuidad del soporte ventilatorio.

Por otra parte, ambos equipos permiten administrar gases medicinales, utilizar vaporizadores y proporcionar ventilación mecánica durante procedimientos de anestesia general.
### 14. CONCLUSION

La práctica de reconocimiento de partes y funcionamiento de la máquina de anestesia Mindray WATO EX-20 permitió identificar sus principales subsistemas y comprender su importancia en la administración de anestesia y ventilación mecánica. Se evidenció que el funcionamiento adecuado del equipo depende de la integración de los sistemas de suministro de gases, control de flujo, vaporización, ventilación, absorción de CO₂ y monitorización, ya que cualquier alteración puede comprometer la seguridad del paciente. Asimismo, se identificó que las fallas más comunes pueden estar relacionadas con el desgaste de empaques y conexiones, fugas en los circuitos, obstrucciones, problemas de calibración de sensores, fallas eléctricas y mantenimiento inadecuado. Por esta razón, es fundamental realizar inspecciones periódicas, pruebas de fugas, verificaciones de los sistemas de alarma y mantenimiento preventivo. Finalmente, la práctica permitió reconocer la importancia del ingeniero biomédico en la inspección, mantenimiento y verificación de estos equipos, contribuyendo a garantizar su confiabilidad y seguridad dentro del entorno hospitalario.

### 4. BIBLIOGRAFÍA

[1] National Institute of General Medical Sciences (NIGMS). (2026). *Anesthesia*. National Institutes of Health.  
https://www.nigms.nih.gov/education/Pages/Anesthesia

[2] MedlinePlus. (2025). *Anestesia*. Biblioteca Nacional de Medicina de los Estados Unidos.  
https://medlineplus.gov/spanish/anesthesia.html

[3] Mindray. (s. f.). *WATO EX-20: Máquina de anestesia*.  
https://www.mindray.com/content/xpace/es_co/products/anesthesia/wato-ex-20.html

[4] Mindray. (s. f.). *WATO EX-20/30/35 Anesthesia Machine: Service Manual*. Manual técnico del fabricante.  
https://www.manualslib.com/manual/3984431/Mindray-Wato-Ex-20.html

[5] Dosch, M. P. (2005). The Anesthesia Machine. En M. Karlet (Ed.), *Nurse Anesthesia Secrets* (1.ª ed.). Elsevier Health Sciences.

[6] Sherwin, M. A., & Eisenkraft, J. B. (2020). Anesthesia hazards: What is the role of the anesthesia machine? *International Anesthesiology Clinics, 58*(1), 27–31.  
https://doi.org/10.1097/AIA.0000000000000264

[7] Dondelinger, R. M. (2004). Anesthesia machines. *Biomedical Instrumentation & Technology, 38*(6), 445–449.

[8] Fischler, I. S., Kaschub, C. E., Lizdas, D. E., & Lampotang, S. (2008). Understanding of anesthesia machine function is enhanced with a transparent reality simulation. *Simulation in Healthcare, 3*(1), 26–32.  
https://doi.org/10.1097/SIH.0b013e31816366d3

[9] Anesthesia Machine. (2022). *StatPearls*. National Center for Biotechnology Information.  
https://www.ncbi.nlm.nih.gov/books/NBK572060/

[10] Occupational Safety and Health Administration (OSHA). *Anesthetic Gases: Guidelines for Workplace Exposures*.  

[11] Mindray. (2012). WATO EX-20/30/35 Anesthesia Machine: Service Manual (Rev. 6.0). Shenzhen Mindray Bio-Medical Electronics Co., Ltd. https://manuals.plus/m/5fff859b068b970cdde442e407db428eaf22c7e9b750706ee02fd0114e99e237.pdf 

[12] Mindray. (s. f.). WATO EX-20 Anesthesia Machine: Operator's Manual. Shenzhen Mindray Bio-Medical Electronics Co., Ltd. https://cleanmedical.com.br/wp-content/uploads/2023/06/Manual-Usuario_Aparelho-Anestesia_Mindray-WATO-EX-20.pdf 

[13] OpenAnesthesia. (s. f.). Carbon Dioxide Absorbers. International Anesthesia Research Society. https://www.openanesthesia.org/keywords/carbon-dioxide-absorbers/ 

[14] Anesthesia Patient Safety Foundation (APSF). (2005). Carbon Dioxide Absorbent Desiccation Safety Conference Convened by APSF. https://www.apsf.org/article/carbon-dioxide-absorbent-desiccation-safety-conference-convened-by-apsf/https://www.osha.gov/waste-anesthetic-gases/workplace-exposures-guidelines

---

**Nota académica:** La información correspondiente a los modos de ventilación y a las características de la WATO EX-20 debe contrastarse con el manual de operación de la versión instalada en el laboratorio. El manual de servicio y la información comercial del fabricante no sustituyen las instrucciones específicas de operación y reprocesamiento.
