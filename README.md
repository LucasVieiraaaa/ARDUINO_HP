# 🎵 Harry Potter Intro Melody - Arduino

Este projeto utiliza um **Arduino** e um **buzzer** para tocar o início da melodia da introdução de Harry Potter. Ele é ideal para quem deseja aprender a programar sons com tons e ritmos no Arduino.

## 📋 Descrição

- O código define as frequências das notas musicais (de B0 a DS8) para serem reproduzidas pelo buzzer.
- A melodia é definida em um array chamado `melody`, que alterna entre notas e suas durações.
- O tempo da música é configurado em `tempo`, permitindo ajustes de velocidade.
- As durações das notas (como semínima, mínima e colcheia) são calculadas dinamicamente com base no tempo.

## 🛠️ Requisitos

- **Hardware:**
  - Placa Arduino (ex.: Arduino Uno)
  - Buzzer passivo
  - Cabos jumper
  - Protoboard (opcional)
  
- **Conexão:**
  - Conecte o pino positivo do buzzer ao pino digital **11**.
  - Conecte o pino negativo do buzzer ao GND do Arduino.
  
## 🧙‍♂️ Observação

- Este código reproduz apenas uma parte inicial da melodia de Harry Potter.
- O tempo entre as notas foi ajustado para manter a fluidez da música.