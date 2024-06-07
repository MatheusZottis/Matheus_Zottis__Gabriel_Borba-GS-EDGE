# Sustentablue
## Descrição do Projeto
Sustentablue é uma plataforma de monitoramento e gestão sustentável dos oceanos, que visa reduzir a poluição marinha e promover práticas de economia azul. A solução integra várias tecnologias para capturar, analisar e visualizar dados sobre a saúde dos oceanos, utilizando sensores de temperatura e umidade (DHT22) e um display LCD para exibição local dos dados. Este projeto é simulado utilizando o Wokwi, uma ferramenta de simulação para projetos de Arduino.

## Funcionalidades
Monitoramento contínuo da temperatura e umidade utilizando o sensor DHT22.
Exibição local dos dados em um display LCD.
Simulação do projeto no Wokwi para testes e desenvolvimento.

## Requisitos
Hardware:
  Arduino Uno
  Sensor DHT22
  Display LCD I2C (16x2)
  Fios de conexão
  Protoboard (opcional)

Software:
  Arduino IDE
  Bibliotecas Arduino: DHT, LiquidCrystal_I2C

## Instalação e Configuração
### 1. Instalação das Bibliotecas
Instale as seguintes bibliotecas no Arduino IDE:

DHT:

  Vá para Sketch > Include Library > Manage Libraries.
  Procure por DHT e instale a biblioteca Adafruit DHT Sensor Library.
   
LiquidCrystal_I2C:  

  Vá para Sketch > Include Library > Manage Libraries.
  Procure por LiquidCrystal_I2C e instale a biblioteca.
    
### 2. Conexões de Hardware

DHT22:
  
  VCC -> 5V no Arduino
  GND -> GND no Arduino
  Data -> Pino 2 no Arduino

LCD I2C:
  
  VCC -> 5V no Arduino
  GND -> GND no Arduino
  SDA -> A4 no Arduino
  SCL -> A5 no Arduino
   
### 3. Carregar o Código no Arduino
Carregue o código fonte (disponível no repositório) no Arduino.

### 4. Simulação no Wokwi
Para simular este projeto no Wokwi acesse:
https://wokwi.com/projects/399984618837309441

#### Uso e Operação
Inicialize o Arduino: Conecte o Arduino à alimentação.

Monitor Serial: Abra o monitor serial no Arduino IDE para verificar as leituras de temperatura e umidade.

Display LCD: Observe as leituras de temperatura e umidade no display LCD.

Wokwi: Utilize a plataforma Wokwi para simular e testar o projeto.
