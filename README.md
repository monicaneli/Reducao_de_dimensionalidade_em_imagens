# Redução de dimensionalidade em imagens

Este projeto apresenta uma implementação em Python para transformação de imagens coloridas em duas representações de menor complexidade: escala de cinza (0–255) e binarizada (0 e 255, preto e branco). 

A redução de dimensionalidade é um passo essencial em visão computacional, pois simplifica a representação dos dados sem comprometer informações relevantes para análise, tornando os modelos mais robustos e eficientes.

## Por que converter as cores de uma imagem?

A conversão para tons de cinza e, posteriormente, para imagens binárias permite reduzir significativamente o número de canais de cor, diminuindo o espaço de armazenamento e o custo computacional de processamento. 

Essa abordagem é amplamente utilizada em pré-processamento de imagens para tarefas como reconhecimento de padrões, segmentação e classificação, facilitando o treinamento de algoritmos de aprendizado de máquina.

## Objetivo

O objetivo principal é implementar, de forma clara e didática, um fluxo de transformação de imagens utilizando Python e bibliotecas como NumPy, Matplotlib e OpenCV. 

O projeto inclui:

* Leitura de imagens coloridas (RGB).
* Conversão para tons de cinza a partir da fórmula ponderada dos canais R, G e B.
* Aplicação de limiar (thresholding) para obtenção de imagens binárias.
* Visualização comparativa das três versões (original, cinza e binária).

## Contribuição

O trabalho demonstra como operações simples de pré-processamento podem reduzir a dimensionalidade de imagens e servir como base para aplicações mais avançadas em visão computacional e aprendizado de máquina. 

Além disso, fornece uma implementação prática e modular que pode ser facilmente adaptada a diferentes contextos de análise de imagens.


<img src="https://github.com/monicaneli/Reducao_de_dimensionalidade_em_imagens/blob/51f66cbf2ccfa5d7a24f122e7a0ea2dd1cd94c21/resultados.png" />
