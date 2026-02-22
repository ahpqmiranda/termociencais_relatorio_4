# Relatório 4: Determinação do Perfil de Velocidade em Túnel de Vento

Este repositório contém o relatório experimental, os scripts de tratamento de dados e os gráficos referentes à **Experiência 04 - Determinação de Perfil de Velocidade e Cálculo da Velocidade Média de Escoamento**, parte da disciplina de Termociências/Mecânica dos Fluidos.

## 👥 Equipe do Projeto

| Nome | Matrícula |
| :--- | :--- |
| **Alan Henrique Pereira Miranda** | 202102140072 |
| **Alexandro Aldo Lopes Osório** | 202302140096 |
| **Ana Monica Cardoso da Costa** | 202202140017 |

## 🛠 Tecnologias e Ferramentas Utilizadas

* **Instrumentação:** Arduino + Sensor de Pressão Diferencial (ADC 10 bits)
* **Tratamento de Dados e Visualização:** Python (`pandas`, `numpy`, `scipy`, `matplotlib`, `seaborn`)
* **Documentação Científica:** LaTeX

## 📋 Resumo do Experimento

O projeto consistiu em medir o perfil de velocidades de escoamento de ar em um tubo cilíndrico de PVC (diâmetro de 6 cm) em duas condições de vazão (100% e 60% da capacidade do ventilador). Para isso, foi utilizado um **Tubo de Pitot** conectado a um microcontrolador Arduino.

A inovação do experimento foi a calibração do sinal analógico bruto do Arduino (0-1023) contra um manômetro em U de coluna de água (mm). Um script em Python foi desenvolvido para:
1. Realizar a Regressão Linear e calibrar o sensor.
2. Calcular a velocidade local através da Equação de Bernoulli.
3. Gerar os gráficos finais do perfil de velocidades parabólico do fluido.

## 📂 Estrutura do Repositório

* `/scripts/`: Contém os scripts em Python desenvolvidos para o tratamento dos dados brutos, as planilhas do experimento e as imagens geradas (gráficos em `.png`).
* `/main.tex`: Arquivo LaTeX contendo a redação do relatório experimental completo (Introdução, Metodologia, Resultados e Discussão).
* `/main.bib`: Arquivo contendo as referências bibliográficas do projeto.

---
*Projeto desenvolvido para fins acadêmicos - 2026.*
