<h1 align="center"> 
	🚧 Em construção 🚧
</h1>

# Rastreador solar com uso de algoritmo genético para otimização na captação de energia dos painéis fotovoltaicos

<!-- ---------------------------------------------------------------------- -->

## 📄 Sumário
- [📝 Descrição](#-descrição)
- [💡 Tema e Hipótese](#-tema-e-hipótese)
- [⚙ Funcionalidades](#-Funcionalidades)
- [🔧 Componentes Utilizados](#-componentes-utilizados)
- [📂 Sobre o Código](#-sobre-o-código)
- [💻 Código](#-código)
- [🦸 Autor](#-autor)
- [📜 Licença](#-licença)

<!-- ---------------------------------------------------------------------- -->

## 📄 Descrição
Este projeto busca criar uma solução para otimizar a captação de energia solar em painéis fotovoltaicos utilizando algoritmos genéticos aplicados a rastreadores solares. A proposta visa melhorar a eficiência energética ajustando automaticamente a posição dos painéis ao longo do dia, alinhando-os com a posição calculada do Sol. Dessa forma, busca-se superar as limitações dos rastreadores convencionais, como altos custos, manutenção frequente e falhas em sensores, maximizando a geração de energia com menor complexidade tecnológica e maior sustentabilidade.

<!-- ---------------------------------------------------------------------- -->

## 💡 Tema e Hipótese
### Uso do Algoritmo Genético para Otimização na Captação de Energia dos Painéis Fotovoltaicos através de Rastreador Solar

<!-- ---------------------------------------------------------------------- -->

## ⚙ Funcionalidades
A placa solar deve se inclinar em direção ao sol com o intuito de gerar a maior quantidade de energia possível.\**
posição inicial leste com inclinação de “ ”
posição final oeste com inclinação de “ ”
A angulação/movimento da placa fotovoltaica será calculado pelo algoritmo genético onde definirá qual ângulo em cada horário irá gerar maior captação de energia e fazer a movimentação de acordo com o horário.
Os dados de dia e hora serão definidos pelo módulo rtc.
A leitura de tensão da placa fotovoltaica será feita por um sensor de tensão .
A leitura da corrente da placa fotovoltaica será feita por um sensor de corrente. 
A gravação dos dados de captação de energia serão gravados pelo leitor de cartão SD salvando dados como data, hora,voltagem , corrente,potência,  e ângulo do servo.
exemplo: 06/12/2024 14:35:20 - Voltagem: 12.5 V, Corrente: 3.7 A, Potenciar: 45.3 W, Ângulo: 90 graus
Utilizarei um Display Lcd 16x2  para mostrar as informações Primeira linha (Data e Hora), Segunda linha (Voltagem, Corrente, Potência e Ângulo).
exemplo:
linha 1 = DD/MM HH:MM
linha 2= V: 5.00 I: 0.35 P: 1.75 A: 45
V = voltagem/tensão, I = corrente/Amperes ,P=Watt/Potência sendo, (P = V × I ), A = ângulo servo motor


<!-- ---------------------------------------------------------------------- -->

## 🔧 Componentes Utilizados
Arduino uno
Placa solar fotovoltaica
Servo motor
Sensor de tensão
Sensor de corrente acs712
Leitor de cartão micro SD
Módulo Rtc Ds1307
Jumper
Display Lcd 16x2 com modulo serial I2C


<!-- ---------------------------------------------------------------------- -->

## 📂 Sobre o Código
_Em construção._

<!-- ---------------------------------------------------------------------- -->

## 💻 Código
_Em construção._

<!-- ---------------------------------------------------------------------- -->

## 🦸 Autor
Jean Pereira Coelho  
[jeanpc0018@gmail.com](mailto:jeanpc0018@gmail.com)

<!-- ---------------------------------------------------------------------- -->

## 📜 Licença
Este projeto está sob a licença [MIT](./LICENSE).  
Feito por: Jean Pereira Coelho
