# air-quality-monitor
Moniteur de qualité d'air (CO2, humidité, température) : capteur SCD41 → ESP32 (firmware C/ESP-IDF)
→ backend Go → InfluxDB → Grafana.

## Stack
- Firmware : ESP32, ESP-IDF (C), FreeRTOS
- Backend : Go
- Stockage : InfluxDB
- Visualisation : Grafana
- Déploiement local : Docker Compose

## Statut
En cours — infra et backend en développement, capteur en commande.

## Structure
Voir `docs/architecture.md`.
