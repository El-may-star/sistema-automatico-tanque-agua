# Conexiones electrónicas

## Componentes principales

- ESP32.
- Sensor ultrasónico HC-SR04.
- Módulo de relé.
- Bomba de agua.
- Fuente de alimentación.

## Conexiones del sensor HC-SR04

- VCC: alimentación del sensor.
- GND: tierra común.
- TRIG: pin de salida del ESP32.
- ECHO: pin de entrada del ESP32.

## Consideraciones

La salida ECHO del HC-SR04 trabaja a 5 V. 
Se debe utilizar un divisor de tensión para proteger
la entrada del ESP32, que trabaja a 3,3 V.

Los pines definitivos se documentarán después de
realizar el montaje físico.
