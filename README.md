# Radar-LTR20-IIoT
# Sistema IoT para Monitoreo de Condición y Alertas Predictivas del Radar LTR20

## Descripción

Este proyecto implementa una Prueba de Concepto (Proof of Concept - PoC) basada en tecnologías de Internet Industrial de las Cosas (IIoT) para el monitoreo de condición de un radar LTR20.

La solución integra Node-RED como simulador de sensores, Eclipse Mosquitto como broker MQTT y ThingsBoard Cloud como plataforma IoT para la visualización de telemetrías, gestión de alarmas y monitoreo en tiempo real.

## Arquitectura

Node-RED → Mosquitto MQTT Broker → ThingsBoard Cloud → Dashboard IoT → Alertas Predictivas

## Variables Monitoreadas

- Temperatura Espina
- Temperatura Amplificador PA
- Humedad Relativa
- Relación de Onda Estacionaria (ROE)
- Potencia de Transmisión (TX)
- Voltaje UPS
- Potencia Amplificador (PA)

## Tecnologías Utilizadas

- Node-RED v4.1.5
- Eclipse Mosquitto MQTT Broker v2.1.2
- ThingsBoard Cloud v4.3.1.2 PAAS Free
- MQTT
- JSON
## Archivos del Proyecto

### flujo_radar_ltr20.json
Contiene la lógica de simulación de sensores y transmisión MQTT implementada en Node-RED.

### dashboard_radar_ltr20.json
Contiene la configuración completa del Dashboard IoT desarrollado en ThingsBoard Cloud, incluyendo widgets, alarmas y visualizaciones.

## Autor

- Efrén Molina
- Edwin Ramirez

Maestría en Electrónica y Automatización

2026
