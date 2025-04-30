## EJEMPLOS

#### 1. MOTOR DIRECCIÓN BÁSICA

El propósito principal es hacer que el motor cambié de dirección cada 5 segundos, sin fijarse para ajustar su velocidad. Se usa el módulo L298N, que permite manejar hacia dónde gira el motor simplemente controlando dos pines digitales, IN1 e IN2. El motor utilizado, un GA12-N20 con reductor, es pequeño y eficiente, lo que lo hace ideal para proyectos que necesitan movimientos precisos y con cierta fuerza, como prótesis, mecanismos de posicionamiento o dispositivos portátiles.

![Gráfico de resultados](../multimedia/motor_direccion_basica.jpg)



#### 2. MOTOR DIRECCION VELOCIDAD

Nos demuestra cómo controlar tanto la dirección como la velocidad de un motorreductor DC GA12-N20 utilizando un módulo controlador L298N y una placa Arduino UNO. Este tipo de configuración es común en aplicaciones biomédicas que requieren control preciso de movimiento, como sistemas de bombeo, movilidad o rehabilitación mecánica.

#### 3. MOTOR VELOCIDAD POTENCIOMETRO

#### 4. SERVO DS3235 ADC PWM

#### 5. SERVO DS3235 CONTROL BÁSICO

<img src="../multimedia/servo_basico.jpg" alt="Gráfico de resultados" width="300">

#### 6. VIBRATION MOTOR BASICO


En esta actividad se desarrolló un circuito básico para activar un micromotor de vibración tipo coin cell utilizando una placa Arduino UNO y un transistor NPN (como el 2N2222) como interruptor. El objetivo fue demostrar un principio de retroalimentación háptica mediante la generación de vibraciones controladas por una señal digital. El montaje incluyó una resistencia de 1kΩ entre el pin digital 3 del Arduino y la base del transistor, además de un diodo de protección (1N4007) para evitar daños por picos de voltaje inducido. El código cargado en el Arduino activa el motor durante 2 segundos y lo apaga por 1 segundo en un ciclo continuo. Esta práctica introduce el uso de actuadores en sistemas biomédicos para señales táctiles, alarmas silenciosas o estimulación sensorial en contextos de rehabilitación.

<img src="../multimedia/servo_potenciometro.jpg" alt="Gráfico de resultados" width="300">

#### 7. VIBRATION MOTOR POTENCIOMETRO

En esta práctica se implementó un sistema de control de intensidad de vibración utilizando un micromotor tipo coin cell, un potenciómetro y una placa Arduino UNO. El potenciómetro actúa como interfaz de usuario, generando una señal analógica que el Arduino convierte en una señal PWM (modulación por ancho de pulso), la cual regula la base de un transistor NPN (como el 2N2222) encargado de activar el motor. La intensidad de la vibración varía proporcionalmente al giro del potenciómetro, permitiendo una retroalimentación háptica ajustable en tiempo real. El montaje incluyó un diodo flyback (1N4007) en paralelo con el motor para proteger el transistor de picos de corriente, y una resistencia de 1kΩ entre la base del transistor y el pin PWM (D3) del Arduino. Además, el programa imprime en el monitor serial tanto el valor analógico del potenciómetro como el nivel PWM aplicado, facilitando el análisis de su comportamiento. Esta técnica tiene aplicaciones en el desarrollo de dispositivos biomédicos con estimulación sensorial controlada, interfaces táctiles o prótesis con retroalimentación háptica.

## PROYECTOS

#### 1. FSR FEEDBAKC VIBRADOR

<img src="../multimedia/fsr_vibrador.jpg" alt="Gráfico de resultados" width="300">

#### 2. GUANTE FLEX DS3235




