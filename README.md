# Projeto IoT - Monitoramento Remoto via MQTT

Este projeto simula um sistema de monitoramento remoto utilizando o protocolo MQTT para comunicação entre dispositivos. Um microcontrolador (Arduino) envia dados via broker MQTT para um cliente Python.

## Tecnologias utilizadas
- Arduino UNO
- Ethernet Shield / ESP8266 (simulado)
- Protocolo MQTT
- Python + Paho MQTT
- Plataforma de simulação: Tinkercad e IDEs locais

## Fluxo de Funcionamento
1. Arduino lê dados simulados (ex: temperatura, status)
2. Envia via MQTT para um broker (Mosquitto)
3. Cliente Python recebe e exibe/processa as mensagens

## Estrutura de arquivos
- `/arduino/mqtt_arduino.ino`: código do Arduino com lógica de envio
- `/python/mqtt_client.py`: script Python com assinaturas e callbacks MQTT
- 
---

Desenvolvido por Felipe Molonhoni – Estudante de Ciência da Computação na FIAP
