
Testes do Projeto
 Automação Residencial Inteligente com ESP32

 1. Teste do sensor LDR
- Objetivo: identificar a luminosidade do ambiente.
- Resultado: valores diferentes foram observados para ambientes claros e escuros.
- Status: aprovado na simulação.

 2. Teste do sensor PIR
- Objetivo: detectar a presença de pessoas.
- Resultado: o sensor identificou movimento e ausência de movimento.
- Status: aprovado na simulação.

 3. Teste do botão
- Objetivo: controlar manualmente a iluminação.
- Resultado: um acionamento liga a luz e outro desliga.
- Status: aprovado na simulação.

4. Teste do LED
- Objetivo: verificar o acionamento da iluminação.
- Resultado: o LED acende conforme as condições programadas.
- Status: aprovado na simulação.

5. Teste do temporizador
- Objetivo: manter a iluminação ligada após a última detecção de movimento.
- Resultado: a luz permanece acesa por aproximadamente 10 segundos.
- Status: aprovado na simulação.

6. Teste do sensor DHT22
- Objetivo: medir temperatura e umidade.
- Resultado: as leituras são exibidas no monitor serial.
- Status: testado na simulação.

 Conclusão

Os testes realizados no Wokwi demonstraram o funcionamento dos sensores e do controle de iluminação do projeto.

Os testes de comunicação MQTT, banco de dados, dashboard e protótipo físico ainda serão realizados.
