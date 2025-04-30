## EJEMPLOS

#### 1. MOTOR DIRECCIÓN BÁSICA

El propósito principal es hacer que el motor cambié de dirección cada 5 segundos, sin fijarse para ajustar su velocidad. Se usa el módulo L298N, que permite manejar hacia dónde gira el motor simplemente controlando dos pines digitales, IN1 e IN2. El motor utilizado, un GA12-N20 con reductor, es pequeño y eficiente, lo que lo hace ideal para proyectos que necesitan movimientos precisos y con cierta fuerza, como prótesis, mecanismos de posicionamiento o dispositivos portátiles.

<img src="/multimedia/motor_direccion_basica.jpg" alt="Gráfico de resultados" width="300">


#### 2. MOTOR DIRECCION VELOCIDAD

Nos demuestra cómo controlar tanto la dirección como la velocidad de un motorreductor DC GA12-N20 utilizando un módulo controlador L298N y una placa Arduino UNO. Este tipo de configuración es común en aplicaciones biomédicas que requieren control preciso de movimiento, como sistemas de bombeo, movilidad o rehabilitación mecánica.

#### 3. MOTOR VELOCIDAD POTENCIOMETRO

Muestra controlar la velocidad de un motorreductor DC GA12-N20 mediante un potenciómetro , utilizando una placa arduino y módulo controlador L298N. Este tipo de configuración es útil en aplicaciones biomédicas que requieren ajustes precisos de velocidad, como prótesis motorizadas o sistemas de asistencia robótica.


#### 4. SERVO DS3235 ADC PWM

En esta actividad se controló la posición de un servomotor DS3235 con un potenciómetro conectado a un Arduino UNO. El valor analógico leído se transformó directamente en una señal PWM (500–2400 µs) usando la función map, y se envió al servomotor mediante writeMicroseconds. Aunque el ángulo no se usó en el control, se estimó linealmente (0°–265°) y se mostró por el monitor serial como retroalimentación. El sistema fue alimentado con una fuente externa de 6V–2A con GND común. Esta práctica es útil para interfaces hombre-máquina en ortesis, terapias motoras y simulación articular.

Los sistemas de control proporcional aplicados en ortesis permiten desarrollar simuladores de movimiento articular, dispositivos de terapia motora con entrada manual e interfaces hápticas con respuesta ajustable, optimizando el entrenamiento y la rehabilitación clínica.


#### 5. SERVO DS3235 CONTROL BÁSICO

En esta actividad se implementó el control básico de un servomotor digital de alto torque DS3235 utilizando una placa Arduino UNO. El objetivo fue posicionar el servo en distintos ángulos mediante pulsos PWM personalizados enviados con la función (writeMicroseconds) de la librería Servo. Se programaron cuatro posiciones representativas (0°, 90°, 180° y 270°) usando anchos de pulso que van desde 500 µs hasta 2400 µs, valores adecuados para este tipo de servos que superan el rango de los modelos estándar. El servomotor fue alimentado por una fuente externa de 6V, y se mantuvo una conexión común a tierra con el Arduino para garantizar el correcto funcionamiento. El programa realiza pausas de 5 segundos entre cada movimiento, permitiendo observar con claridad los cambios de posición. Este tipo de control es especialmente útil en aplicaciones biomédicas como ortesis robóticas, dispositivos de asistencia respiratoria o mecanismos de manipulación en prótesis, donde se requiere precisión y fuerza en el posicionamiento.

La integración de control de articulaciones robóticas en ortesis activas, sistemas de posicionamiento de válvulas en dispositivos de asistencia respiratoria, mecanismos de manipulación en brazos protésicos y dispositivos de entrenamiento motor asistido impulsa el desarrollo de soluciones biomédicas avanzadas para la rehabilitación y asistencia funcional.


#### 6. VIBRATION MOTOR BASICO


En esta actividad se activó un micromotor de vibración tipo coin cell usando un Arduino UNO y un transistor NPN (2N2222) como interruptor, controlado por una señal digital. Se usó una resistencia de 1kΩ en la base y un diodo 1N4007 como protección. El motor se programó para vibrar 2 segundos y apagarse 1 segundo en bucle. Esta práctica demuestra retroalimentación háptica aplicada a señales táctiles y estimulación sensorial en rehabilitación biomédica.

Las señales hápticas en sistemas de biofeedback, como los utilizados para corregir la postura o monitorear la frecuencia cardíaca, ofrecen una vía efectiva y no invasiva para mejorar la percepción corporal y el autocontrol fisiológico. Estas tecnologías también pueden aplicarse como alarmas discretas para pacientes con pérdida auditiva, permitiendo una comunicación silenciosa pero efectiva. Además, las interfaces sensoriales desempeñan un papel clave en la rehabilitación y la estimulación multisensorial, facilitando la recuperación funcional a través de experiencias táctiles que complementan otros canales sensoriales.

<img src="/multimedia/servo_basico.jpg" alt="Gráfico de resultados" width="300">

#### 7. VIBRATION MOTOR POTENCIOMETRO

En esta práctica se implementó un sistema de control de intensidad de vibración utilizando un micromotor tipo coin cell, un potenciómetro y una placa Arduino UNO. El potenciómetro actúa como interfaz de usuario, generando una señal analógica que el Arduino convierte en una señal PWM (modulación por ancho de pulso), la cual regula la base de un transistor NPN (como el 2N2222) encargado de activar el motor. La intensidad de la vibración varía proporcionalmente al giro del potenciómetro, permitiendo una retroalimentación háptica ajustable en tiempo real. El montaje incluyó un diodo flyback (1N4007) en paralelo con el motor para proteger el transistor de picos de corriente, y una resistencia de 1kΩ entre la base del transistor y el pin PWM (D3) del Arduino. Además, el programa imprime en el monitor serial tanto el valor analógico del potenciómetro como el nivel PWM aplicado, facilitando el análisis de su comportamiento. Esta técnica tiene aplicaciones en el desarrollo de dispositivos biomédicos con estimulación sensorial controlada, interfaces táctiles o prótesis con retroalimentación háptica.

Los sistemas de retroalimentación táctil en órtesis y prótesis permiten mejorar la percepción del entorno y el control del dispositivo por parte del usuario, brindando una experiencia más natural e intuitiva. La estimulación sensorial controlada, aplicada en terapia ocupacional, favorece la integración sensorial y el desarrollo de habilidades motoras finas. Por su parte, los dispositivos de entrenamiento con respuesta háptica ofrecen una herramienta eficaz para la rehabilitación motora, al proporcionar una guía activa durante el movimiento. Finalmente, las interfaces usuario-dispositivo sin estímulo visual resultan especialmente útiles en contextos donde se requiere atención plena a otras señales sensoriales, promoviendo una interacción más eficiente y accesible.

<img src="/multimedia/servo_potenciometro.jpg" alt="Gráfico de resultados" width="300">

## PROYECTOS

#### 1. FSR FEEDBAKC VIBRADOR

Permite generar una señal de vibración proporcional a la presión aplicada sobre un sensor FSR. A medida que se aplica más fuerza, el motor vibrador aumenta su intensidad mediante una señal PWM. Es una forma efectiva y económica de implementar retroalimentación táctil proporcional en interfaces biomédicas o educativas.

<img src="/multimedia/fsr_vibrador.jpg" alt="Gráfico de resultados" width="300">

#### 2. GUANTE FLEX DS3235

En este proyecto se implementó un control proporcional de un servomotor DS3235 usando un sensor flex como entrada analógica, simulando el movimiento articular sin estructura mecánica ni guante. El sensor, conectado como divisor de voltaje, fue leído por el Arduino UNO, y su valor se transformó en un pulso PWM (500–2400 µs) enviado al servo mediante writeMicroseconds. Se estimó el ángulo (0°–265°) para mostrarlo en el monitor serial. Esta práctica integró conceptos de ADC, PWM y control de actuadores con aplicaciones en prótesis, interfaces hápticas y rehabilitación.

La simulación de control mioeléctrico en prótesis de mano, los sistemas de asistencia robótica proporcional como los exoesqueletos, y las interfaces cuerpo-máquina para rehabilitación motora representan avances clave en la ingeniería biomédica orientada a la recuperación funcional. Estos enfoques permiten interpretar señales musculares para controlar dispositivos protésicos o de asistencia, facilitando movimientos más naturales y personalizados. Además, el entrenamiento clínico con dispositivos portables mejora la rehabilitación al brindar retroalimentación en tiempo real y permitir sesiones fuera del entorno hospitalario, promoviendo la autonomía del paciente y acelerando su recuperación.

<img src="/multimedia/flex_proyecto.jpg" alt="Gráfico de resultados" width="300">

