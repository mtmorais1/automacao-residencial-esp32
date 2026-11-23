
 Periféricos Dedicados do ESP32

1. ADC - Conversor Analógico-Digital
Utilizado para realizar a leitura do sensor LDR, responsável por medir a luminosidade do ambiente.

- Pino utilizado: GPIO 34.
- Função: identificar se o ambiente está claro ou escuro.
- Limite configurado: 1000.

 2. Temporizador
Utilizado para controlar o tempo de permanência da iluminação após a última detecção de movimento.

- Tempo configurado: 10 segundos.
- Recurso utilizado: funções de temporização do MicroPython.

 3. Resultado esperado
A iluminação permanece ligada por 10 segundos após a última detecção de movimento, desde que o ambiente esteja escuro.

 Status
Implementado e testado na simulação Wokwi.
