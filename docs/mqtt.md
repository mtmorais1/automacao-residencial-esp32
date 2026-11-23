
 Comunicação MQTT

 Objetivo
Implementar a comunicação MQTT entre o ESP32 e o Node-RED para permitir o monitoramento e controle da automação residencial.

Funcionamento previsto
O ESP32 será responsável por:
- Enviar a temperatura do ambiente.
- Enviar a umidade do ambiente.
- Enviar o nível de luminosidade.
- Informar a detecção de presença.
- Receber comandos para ligar e desligar a iluminação.

 Protocolo
MQTT (Message Queuing Telemetry Transport).

Integração
- ESP32: dispositivo responsável pela coleta de dados e controle.
- Broker MQTT: responsável por distribuir as mensagens.
- Node-RED: responsável pelo dashboard e gerenciamento das informações.

 Status
Planejado. A implementação e os testes serão realizados nas próximas etapas.
