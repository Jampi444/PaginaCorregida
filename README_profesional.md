# GuardianAI

## Resumen ejecutivo

GuardianAI es un proyecto de ingeniería de software orientado al desarrollo de un collar inteligente para mascotas con capacidades de monitoreo, seguridad y salud. La solución integra sensores, geolocalización, análisis de comportamiento, inteligencia artificial y servicios en la nube para brindar una experiencia de protección proactiva para propietarios, cuidadores y veterinarias.

## Descripción del problema

La pérdida de mascotas, la falta de seguimiento continuo y la incapacidad de detectar riesgos de salud o fuga representan problemas reales tanto para la seguridad animal como para la tranquilidad del propietario. Los sistemas tradicionales suelen ofrecer únicamente localización básica, sin análisis predictivo ni alertas inteligentes.

GuardianAI busca cerrar esa brecha mediante una solución integral que combine hardware, software, servicios conectados y análisis predictivo en una sola plataforma.

## Objetivo general

Desarrollar un sistema inteligente para el monitoreo y protección de mascotas, que permita:

- localizar a la mascota en tiempo real,
- detectar anomalías y comportamientos peligrosos,
- evaluar indicadores de salud,
- generar alertas automáticas,
- mejorar la gestión de cuidados veterinarios y la seguridad del animal.

## Objetivos específicos

- Implementar un collar con sensores de movimiento, GPS y conectividad inalámbrica.
- Integrar mecanismos de comunicación con aplicaciones móviles y paneles web.
- Desarrollar alertas por geocercas, batería baja y pérdida de señal.
- Aplicar modelos de inteligencia artificial para la detección de patrones y riesgos.
- Gestionar información de salud, historial médico y registro de mascotas.
- Diseñar una arquitectura escalable con almacenamiento seguro en la nube.

## Alcance del proyecto

El alcance del sistema contempla los siguientes componentes:

### Hardware
- ESP32 como unidad principal de control
- GPS para geolocalización
- Sensores de movimiento y entorno
- Batería recargable
- Comunicaciones Wi-Fi, Bluetooth y MQTT

### Backend
- API REST con Java Spring Boot
- Gestión de autenticación y roles
- Comunicación con la base de datos y servicios de notificación

### Base de datos
- Firebase Firestore
- Almacenamiento seguro de usuarios, mascotas, historial y alertas

### Frontend móvil
- Aplicación desarrollada con Flutter
- Monitoreo en tiempo real
- Notificaciones y administración de mascotas

### Frontend web
- Panel administrativo desarrollado con Angular
- Dashboard con métricas, reportes y gestión de usuarios

### Inteligencia artificial
- Modelos para análisis de patrones de actividad y comportamiento
- Predicción de riesgo, cambio de comportamiento y posibles anomalías

## Funcionalidades principales

- GPS en tiempo real
- Inteligencia artificial para detección de anomalías
- Geocercas inteligentes
- Monitoreo de salud y signos vitales
- Historial de recorridos
- Detección de actividad
- Monitoreo de batería
- Alertas inteligentes
- Botón de emergencia
- Modo antirrobo
- Modo perdido
- Resistencia al agua
- Dashboard en tiempo real
- Perfil médico de la mascota
- Recordatorios veterinarios
- Seguridad de datos con JWT
- Actualización OTA del firmware

## Arquitectura propuesta

La solución se estructura en una arquitectura distribuida compuesta por:

1. Dispositivo wearable
   - Sensorización física del collar
   - Captura de GPS, movimiento, entorno y señales de conectividad

2. Gateway de comunicación
   - Conexión con Wi-Fi, Bluetooth y protocolos MQTT/HTTP

3. Backend de servicios
   - Procesamiento de datos, validación de eventos y lógica de negocio

4. Persistencia de datos
   - Firestore para almacenamiento de usuarios, mascotas, alertas y reportes

5. Frontend web y móvil
   - Visualización de ubicación, gestión de usuarios y alertas

6. Inteligencia artificial
   - Procesamiento de datos para análisis predictivo y generación de alertas

## Stack tecnológico

- ESP32
- GPS
- Google Maps API
- Firebase
- Firestore
- FCM
- Flutter
- Angular
- Java Spring Boot
- Python
- TensorFlow
- Scikit-learn
- Pandas
- MQTT
- JWT
- Firebase Cloud Messaging

## Casos de uso

### Caso de uso 1: pérdida de mascota
Cuando una mascota sale de una geocerca establecida, el sistema activa una alerta para el propietario y registra la última ubicación conocida.

### Caso de uso 2: monitoreo de salud
Si el collar detecta cambios inusuales en la actividad o signos vitales, el sistema genera una alerta preventiva para el propietario o el centro veterinario.

### Caso de uso 3: ausencia prolongada
Si la mascota permanece inactiva por mucho tiempo, el sistema notifica posibles riesgos o estados de emergencia.

### Caso de uso 4: robo o retiro del collar
Si el collar es retirado sin autorización, el sistema envía una alerta con la ubicación más reciente.

## Impacto esperado

El proyecto busca generar un impacto positivo en varios ámbitos:

- mejor seguridad para mascotas,
- reducción de pérdidas y robos,
- mejor atención veterinaria,
- más tranquilidad para propietarios,
- uso de tecnología aplicada a bienestar animal.

## Estado del proyecto

El proyecto se encuentra en fase de diseño y presentación de prototipo, con enfoque académico y tecnológico. La página web servirá como presentación visual del sistema y sus capacidades.

## Repositorio y ejecución

La página principal se encuentra en el archivo `index.html` y fue diseñada como una landing page para presentar la solución de manera clara, moderna y profesional.

Para ejecutarla:

1. Abrir la carpeta del proyecto.
2. Cargar `index.html` en el navegador.
3. O usar Live Server desde VS Code.

## Autor

Hoobert Jean Paul Barrios Pineda

## Institución

Universitaria de Colombia

## Nota

Este proyecto se desarrolla con fines académicos y de presentación de una propuesta de ingeniería de software aplicada a la solución de problemas reales en bienestar animal.
