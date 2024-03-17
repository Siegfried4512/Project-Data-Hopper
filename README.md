![Data_Hopper](doc/Data_Hopper.png)

## Sobre:
Data Hopper é um dispositivo baseado na plataforma Arduino UNO R3 capaz de medir e apresentar ao usuário os valores médios de luminosidade, temperatura e umidade de um ambiente industrial a qual estiver inserido em um display, além de armazenar e apresentar os instantes em que os valores estiverem fora dos intervalos especificados.

## Objetivo:
O objetivo do dispositivo é realizar padronizadamente leituras de luminosidade, temperatura e umidade, apresentando os resultados no visor LCD e realizando o armazenamento dos valores em um EEPROM Data Logger, a fim de realizar um cálculo da média ponderada, estabelecendo níveis de referência a se limitar a mudança desses valores. Caso os níveis de referência sejam ultrapassados ou não sejam atingidos pelo sensor DHT-11, será soado um alarme (buzzer) para alertar a discrepância e um ou mais LEDs serão acesos para indicar a leitura discrepante.

## Especificações técnicas:
### Materiais utilizados:
\* 1 MCU (Atmega 328P) - Arduino Uno R3

\* 1 LDR + Resistor 10KOhm

\* 1 DHT-11 (Sensor de temperatura e umidade)

\* 1 LCD 16x2 - I2C

\* 1 Bateria de 9V + suporte para bateria

\* 1 RTC (Real Time Clock)

\* 1 Protoboard

\* 35 Jumpers

\* 3 LEDs

\* 5 Resistores 330 Ohms 

\* 2 Resistores 10k Ohms 

### Funcionalidade:
>TODO

### Manual de operação do Data Hopper:
![Manual](doc/Manual.png)

A navegação do dispositivo dispõe-se do uso de dois botões acionáveis e um display LCD para exibir as informações processadas ao usuário. A temperatura pode ser apresentada dentre as três escalas disponíveis (Kelvin, Celsius ou Fahreinheit), podendo ser alternada com o acionamento do primeiro botão. Abaixo da temperatura, é apresentada o valor da porcentagem da umidade e, após curtos instantes, é mostrado o valor da luminosidade. O segundo botão alterna entre os valores atuais e os de discrepância registrados, revelando os valores médios e o horário e data do registro.

## Montagem do projeto e seu diagrama elétrico:
### Montagem:
![Montagem](doc/Montagem.png)

### Diagrama:
![Diagrama](doc/Diagrama.jpg)



