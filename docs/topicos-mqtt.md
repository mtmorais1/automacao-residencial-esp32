
 Tópicos MQTT - Automação Residencial

 Identificação do projeto
Projeto: Automação Residencial Inteligente com ESP32.

 Tópicos de envio (ESP32 para Node-RED)

| Tópico | Informação |
|---|---|
| casa/temperatura | Temperatura do ambiente |
| casa/umidade | Umidade do ambiente |
| casa/luminosidade | Luminosidade do ambiente |
| casa/presenca | Detecção de presença |
| casa/iluminacao/estado | Estado atual da iluminação |

 Tópicos de recebimento (Node-RED para ESP32)

| Tópico | Comando |
|---|---|
| casa/iluminacao/comando | Ligar ou desligar a iluminação |

 Valores das mensagens

- Temperatura: valor numérico em °C.
- Umidade: valor numérico em %.
- Luminosidade: leitura do ADC.
- Presença: 1 para detectada e 0 para não detectada.
- Iluminação: 1 para ligada e 0 para desligada.

Funcionamento previsto

O ESP32 enviará as informações dos sensores ao broker MQTT.

O Node-RED receberá esses dados e exibirá as informações no dashboard.

O dashboard poderá enviar comandos para controlar a iluminação remotamente.

Status

Planejado. Os tópicos serão utilizados na implementação e nos testes da comunicação MQTT.
