# Projeto de Monitoramento da Qualidade da Água com Arduino
## Link para o projeto:
https://wokwi.com/projects/399824217708896257

## Introdução
Este projeto visa desenvolver um sistema de monitoramento da qualidade da água utilizando a plataforma Arduino. O sistema mede a temperatura e o pH da água, exibindo os dados em um display LCD. Além disso, gera alertas quando os níveis de pH estão fora da faixa ideal para a saúde dos peixes.

## Componentes Utilizados
- Arduino Uno
- Sensor de Temperatura e Umidade DHT22
- Potenciômetro (simulando sensor de pH)
- Display LCD 16x2 com interface I2C
- Jumpers e Protoboard

## Dependências
Instale as seguintes bibliotecas no Arduino IDE:

- DHT Sensor Library: Para o sensor DHT22.
- Adafruit Unified Sensor: Dependência para a biblioteca DHT.
- LiquidCrystal I2C: Para o display LCD I2C.

## Como Usar
1 - Montagem do Circuito: Siga o diagrama de conexões fornecido.

2 - Carregamento do Código: Abra o Arduino IDE, copie e cole o código fornecido, e carregue-o no Arduino Uno.

3 - Monitoramento: O display LCD exibirá a temperatura e o pH da água. Se o pH estiver fora da faixa de 6.5 a 8.0, uma mensagem de alerta será exibida.

## Projeto desenvolvido por:

Miguel Garcez de Carvalho - RM 553768

Vinicius Souza e Silva - RM 552781
