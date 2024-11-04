# Jogador Automático de Forca

Este projeto tem como objetivo desenvolver um jogador automático de forca que utiliza conceitos de entropia e teoria da informação para maximizar suas chances de vitória em um jogo com apenas 5 vidas. O vocabulário permitido é obtido de uma lista disponível em uma URL, e o jogador é capaz de acessar esse vocabulário para realizar suas jogadas.

## Objetivo

O principal objetivo deste projeto é criar um algoritmo que jogue o jogo da forca de forma eficiente, tentando adivinhar a palavra secreta escolhida pelo juiz. O jogador utiliza o conceito de entropia para calcular a probabilidade de cada letra aparecer na palavra, aumentando assim suas chances de acertar as letras antes de perder todas as vidas.

## Estrutura do Projeto

1. **Coleta de Dados**: O vocabulário de palavras é coletado de uma lista disponível na internet, garantindo um conjunto diversificado de palavras em português.

2. **Implementação do Jogo**: A classe `JogoDeForca` gerencia as regras do jogo, incluindo o controle das vidas e a escolha de palavras aleatórias do vocabulário.

3. **Jogador Automático**: A classe `JogadorAutomatico` implementa a lógica de escolha de letras e palavras. Utiliza contagem de frequências e cálculo de entropia para selecionar a próxima letra a ser adivinhada.

4. **Execução do Jogo**: O jogador automático tenta adivinhar as letras até descobrir a palavra ou perder todas as vidas. O desempenho do jogador é avaliado em múltiplas partidas.

5. **Avaliação de Desempenho**: O algoritmo é testado em pelo menos 100 jogos, com o objetivo de reportar a taxa de vitória do jogador automático.

## Requisitos

Para rodar o projeto, é necessário ter instalados os seguintes pacotes Python:

- `requests`
- `collections`
- `math`

## Requisitos

O projeto inclui um notebook demo.ipynb comentado, que executa testes e gera resultados sobre a taxa de vitória do jogador automático, permitindo uma análise detalhada do desempenho e eficiência do algoritmo.

A taxa de vitória é um reflexo de como as técnicas de entropia e probabilidade podem ser aplicadas para melhorar a performance em jogos de adivinhação, destacando a importância da teoria da informação no desenvolvimento de estratégias eficazes.

## Conclusão

Este projeto demonstra a aplicação prática de conceitos de álgebra linear e teoria da informação em um jogo simples, mostrando como a matemática pode ser utilizada para criar algoritmos que aprendem e se adaptam a situações de incerteza.

Você pode instalar todos os pacotes executando o comando:

```bash
pip install -r requirements.txt