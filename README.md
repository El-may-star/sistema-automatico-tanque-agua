# Sistema Automático de Control de Nivel de Agua

## 1. Descripción del proyecto

Desarrollo de un sistema embebido basado en ESP32 para monitorear y controlar automáticamente el nivel de agua de un tanque, mediante sensores, actuadores y programación en Arduino IDE.

## 2. Planteamiento del problema

En algunos sistemas de almacenamiento de agua, el llenado del tanque depende de la supervisión manual de una persona. Esto puede ocasionar desbordamientos, desperdicio de agua, funcionamiento innecesario de la bomba y dificultades para conocer el nivel disponible.

Por esta razón, se propone desarrollar un sistema que mida el nivel de agua y controle automáticamente el funcionamiento de una bomba, buscando mejorar la seguridad y eficiencia del proceso.

## 3. Objetivo general

Desarrollar un sistema embebido con ESP32 que permita medir el nivel de agua de un tanque y controlar automáticamente el llenado mediante una bomba.

## 4. Objetivos específicos

- Medir el nivel de agua mediante un sensor ultrasónico HC-SR04.
- Procesar las mediciones utilizando un ESP32.
- Activar la bomba cuando el nivel de agua sea igual o inferior al 30%.
- Desactivar la bomba cuando el nivel alcance o supere el 90%.
- Implementar validaciones para evitar el funcionamiento inseguro ante lecturas incorrectas.
- Realizar pruebas con un prototipo físico.

## 5. Alcance de la primera iteración

Para esta primera etapa se desarrollarán tres funcionalidades principales:

1. **Medición del nivel de agua:** lectura del sensor ultrasónico y conversión de la distancia en porcentaje de llenado.
2. **Control automático de la bomba:** activación al 30% o menos y desactivación al 90% o más.
3. **Protección del sistema:** validación de lecturas y filtrado de variaciones anormales para evitar acciones incorrectas.

La aplicación móvil, la conectividad WiFi y el historial de funcionamiento se consideran funcionalidades para futuras iteraciones.

## 6. Tecnologías y componentes

- ESP32.
- Sensor ultrasónico HC-SR04.
- Módulo de relé.
- Bomba de agua.
- Arduino IDE.
- Lenguaje de programación C/C++.
- Prototipo físico y conexiones electrónicas.

## 7. Equipo de desarrollo

| Integrante | Responsabilidad inicial |
|---|---|
| Juan Diego Arango | Medición del nivel de agua |
| Maykol Andrés Pejendino | Control automático de la bomba |
| Miguel Ángel Cáceres | Protección y validación del sistema |

## 8. Organización del trabajo

El desarrollo se gestionará mediante GitHub, utilizando:

- **Issues:** registro de historias de usuario y tareas.
- **Projects:** seguimiento del estado de las actividades.
- **Branches:** desarrollo independiente de funcionalidades.
- **Commits:** registro de los cambios realizados.
- **Pull Requests:** revisión e integración del código.

Cada integrante tendrá actividades asignadas y deberá registrar los avances y evidencias de su trabajo.

## 9. Objetivo de la primera iteración

Completar un prototipo funcional que permita medir el nivel de agua, controlar el llenado del tanque y responder de manera segura ante lecturas incorrectas.
