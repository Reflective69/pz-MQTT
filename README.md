# STT-PZ-3: MQTT Broker

## Мета роботи

Розгорнути MQTT-брокер у Docker, налаштувати базову конфігурацію сервісу та перевірити роботу MQTT-протоколу через Publish/Subscribe.

## Використані технології

- Ubuntu Linux
- Docker
- Docker Compose
- Eclipse Mosquitto
- Mosquitto Clients
- Git / GitHub

## Структура проєкту

```text
stt-pz-3/
├── broker/
│   ├── docker-compose.yml
│   ├── mosquitto.conf
│   ├── data/
│   └── logs/
├── screenshots/
│   ├── 01_docker_status.txt
│   ├── 02_broker_logs.txt
│   └── 03_mqtt_tests.txt
├── .editorconfig
├── .gitignore
└── README.md
