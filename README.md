# APRENDIENDO TELEMETRÍA

## 1. Telemetría
La telemetría se refiere a la recopilación, transmisión y análisis de datos sobre el rendimiento y comportamiento de las aplicaciones,
proporcionando los datos necesarios para configurar el monitoreo y alertas que informen a los operadores sobre problemas antes que afecten a los usuarios.

La telemetría incluye:

- **Métricas**: Datos cuantitativos sobre el rendimiento del sistema, como latencia, uso de CPU y memoria.
- **Logs**: Registros generados por la aplicación, como errores, advertencias e informativos.
- **Trazas**: Información sobre la propagación de las solicitudes a través de diferentes servicios.

## 2. Observabilidad
Se refiere a la capacidad de entender lo que está sucediendo dentro de un sistema basado en los datos de telemetría.

## 3. Herramientas

| Herramienta                                | Objetivo                                                                                             |
|--------------------------------------------|------------------------------------------------------------------------------------------------------|
| [Prometheus](path/01-prometheus/README.md) | Brinda métricas de rendimiento y estado de aplicaciones, como uso de CPU, RAM, tasas de error, etc.  |
| [Zipkin](path/02-zipkin/README.md)         | Brinda visibilidad sobre la propagación de una solicitud a través de múltiples servicios.            |
| [Loki](path/03-loki/README.md)             | Permite almacenar y consultar Logs.                                                                  |
| [Grafana](path/04-grafana/README.md)       | Brinda dashboards personalizados basados en las métricas de Prometheus, Loki u otra fuente de datos. |
