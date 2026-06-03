# esp32-environmental-monitoring-system
Sistema IoT de monitoreo agrícola desarrollado con ESP32, BMP280 y SIM800L para registrar y transmitir datos de temperatura, presión atmosférica y altitud mediante mensajes SMS en tiempo real.

---Agricultural IoT Datalogger---

---Descripción---

Desarrollé un sistema de monitoreo ambiental orientado al sector agrícola utilizando tecnologías IoT y sistemas embebidos. El proyecto fue diseñado para recopilar información crítica del entorno, como temperatura, presión atmosférica y altitud, permitiendo a los agricultores acceder a datos en tiempo real y generar registros históricos para apoyar la toma de decisiones.

La solución integra un microcontrolador ESP32, un sensor BMP280 y un módulo de comunicación GSM SIM800L para capturar, procesar y transmitir información ambiental mediante mensajes SMS. El sistema fue concebido como una alternativa de bajo costo para el monitoreo remoto de zonas agrícolas donde el acceso a infraestructura de red puede ser limitado.

---Problemática Abordada---

Durante el análisis del proyecto se identificó la falta de herramientas accesibles para registrar y consultar datos ambientales históricos en áreas agrícolas. Esta ausencia de información dificultaba la detección de patrones climáticos y la toma de decisiones relacionadas con el manejo de cultivos, prevención de enfermedades y optimización de recursos.

---Funcionalidades---

* Monitoreo de temperatura ambiental.
* Medición de presión atmosférica.
* Cálculo de altitud.
* Captura automática de datos mediante sensores.
* Procesamiento local de información en ESP32.
* Comunicación GSM mediante SIM800L.
* Envío automático de datos por SMS.
* Monitoreo remoto en tiempo real.
* Generación de registros históricos.
* Operación en zonas con conectividad limitada.

---Arquitectura del Sistema---

---Hardware---

* ESP32 (Microcontrolador principal)
* BMP280 (Sensor de temperatura y presión atmosférica)
* SIM800L (Módulo GSM/GPRS)
* Batería recargable
* Protoboard
* Cableado Dupont

---Comunicación---

* I2C para la comunicación entre ESP32 y BMP280.
* UART para la comunicación entre ESP32 y SIM800L.
* Red GSM para la transmisión remota de información mediante SMS.

---Tecnologías Utilizadas---

---Software---

* C++
* Arduino IDE
* Librerías Adafruit BMP280
* HardwareSerial
* Wire
* SPI

---Hardware---

* ESP32
* BMP280
* SIM800L

---Habilidades Demostradas---

---Programación---

* Desarrollo de sistemas embebidos.
* Programación en C++ para microcontroladores.
* Integración de sensores.
* Comunicación serial UART.
* Comunicación I2C.
* Implementación de protocolos GSM.
* Uso de comandos AT.
* Procesamiento de datos en tiempo real.

---Electrónica---

* Diseño e integración de circuitos electrónicos.
* Diagnóstico y solución de fallas.
* Gestión de alimentación eléctrica.
* Integración de módulos IoT.
* Configuración de sensores ambientales.

---Ingeniería de Proyectos---

* Análisis de requerimientos.
* Diseño de soluciones IoT.
* Planeación e implementación de prototipos.
* Pruebas y validación de sistemas.
* Documentación técnica.

---Resultados Obtenidos---

El sistema logró recopilar y transmitir exitosamente datos ambientales en tiempo real mediante mensajes SMS. La implementación permitió mejorar la capacidad de monitoreo de las condiciones climáticas en zonas agrícolas y facilitar la toma de decisiones basada en información obtenida directamente del entorno.

Además, el proyecto fortaleció mis conocimientos en electrónica, programación de sistemas embebidos, protocolos de comunicación y desarrollo de soluciones IoT aplicadas a problemas reales.

---Objetivo del Proyecto---

Diseñar e implementar un sistema IoT de bajo costo capaz de monitorear variables ambientales críticas para el sector agrícola, permitiendo el acceso remoto a información relevante y contribuyendo a una gestión más eficiente de los cultivos mediante el uso de tecnologías embebidas y comunicación móvil.
