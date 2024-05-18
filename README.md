# Monitor de Batimentos Cardíacos com ESP8266 e MQTT

Este projeto utiliza um sensor de batimentos cardíacos AD8232, um microcontrolador ESP8266 e o protocolo MQTT para monitorar e transmitir dados de batimentos cardíacos em tempo real para a plataforma Ubidots.

## Componentes

- NodeMCU (ESP8266)
- Sensor de batimentos cardíacos AD8232
- Resistor de 220 ohms
- LED
- Protoboard e jumpers

## Conexões

### Sensor AD8232
- **OUTPUT** -> A0 (pino analógico do ESP8266)
- **3.3V** -> 3.3V (do ESP8266)
- **GND** -> GND (do ESP8266)

### LED
- **Anodo (perna longa)** -> GPIO 2 (ou outro pino disponível no ESP8266)
- **Catodo (perna curta)** -> Resistor de 220 ohms -> GND

Este README fornece uma visão geral do projeto, incluindo componentes, conexões, código, configuração da plataforma Ubidots e resultados obtidos. Você pode personalizá-lo conforme necessário para se adequar melhor ao seu projeto específico.