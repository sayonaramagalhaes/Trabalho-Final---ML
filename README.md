# Trabalho-Final---ML

Universidade Federal do Rio Grande do Norte

Programa de Pós-Graduação em Engenharia Elétrica e de Computação

Disciplina: Aprendizado de Máquina

Este repositório contém a solução para a atividade final da disciplina de Aprendizado de Máquina. O objetivo principal é aplicar e avaliar as técnicas de Transfer Learning (Aprendizado por Transferência) em um problema de classificação de imagens, comparando o desempenho de dois métodos :

Feature Extraction (Extração de Características)
Fine-Tuning
O modelo utilizado foi o algoritmo pré-treinado AlexNet, que foi adaptado para o problema de classificação de imagens de gatos e cachorros.

Técnicas Utilizadas
1. Feature Extraction (Extração de Características)
Nesta abordagem, utilizamos a parte convolucional do modelo AlexNet (pré-treinado) para extrair características das imagens. Essas características extraídas foram então usadas como entrada para um classificador simples, treinado para distinguir entre as classes "Cachorro" e "Gato". Não houve ajuste nas camadas convolucionais do AlexNet, apenas a adaptação do classificador final.

2. Fine-Tuning
Neste método, realizamos o fine-tuning do modelo AlexNet. Usamos as camadas convolucionais do modelo pré-treinado, mas comparamos o desempenho ajustando as camadas finais (totalmente conectadas) para melhor adaptar o modelo ao nosso conjunto de dados específico. Esse processo envolve o ajuste de parâmetros do modelo durante o treinamento, buscando melhorar a performance de classificação.

Base de Dados
O conjunto de dados utilizado foi o Cats vs Dogs, disponível no Kaggle. Este conjunto contém 25.000 imagens divididas entre as classes "Cachorro" e "Gato". As imagens foram usadas para treinar os modelos nas técnicas de Feature Extraction e Fine-Tuning.

Link para o dataset no Kaggle: Microsoft Cats vs Dogs Dataset

