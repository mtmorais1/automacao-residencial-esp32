
 Banco de Dados SQLite

 Objetivo
Armazenar os dados coletados pela automação residencial inteligente.

Dados que serão registrados
- Temperatura;
- Umidade;
- Luminosidade;
- Detecção de presença;
- Estado da iluminação;
- Data e horário da leitura.

 Tecnologia
SQLite.

Integração prevista
O Node-RED receberá os dados enviados pelo ESP32 via MQTT e fará o registro no banco de dados SQLite.

 Status
Planejado. A criação do banco e os testes serão realizados nas próximas etapas.
