# Trabalho-Final---ML

Universidade Federal do Rio Grande do Norte

Programa de Pós-Graduação em Engenharia Elétrica e de Computação

Disciplina: Aprendizado de Máquina

Este repositório contém a solução para a atividade final da disciplina de Aprendizado de Máquina. O objetivo principal é aplicar e avaliar as técnicas de Transfer Learning (Aprendizado por Transferência) em um problema de classificação de imagens, comparando o desempenho de dois métodos:


Técnicas Utilizadas
1. Feature Extraction (Extração de Características)
Nesta abordagem, utilizamos a parte convolucional do modelo AlexNet (pré-treinado) para extrair características das imagens. Essas características extraídas foram então usadas como entrada para um classificador simples, treinado para distinguir entre as classes "Cachorro" e "Gato". Não houve ajuste nas camadas convolucionais do AlexNet, apenas a adaptação do classificador final.

2. Fine-Tuning
Neste método, realizamos o fine-tuning do modelo AlexNet. Usamos as camadas convolucionais do modelo pré-treinado, mas comparamos o desempenho ajustando as camadas finais (totalmente conectadas) para melhor adaptar o modelo ao nosso conjunto de dados específico. Esse processo envolve o ajuste de parâmetros do modelo durante o treinamento, buscando melhorar a performance de classificação.
 
 Os modelos foram avaliados com base nas seguintes métricas:
 
 Acurácia: Percentual de classificações corretas.
 Precisão: Capacidade de evitar falsos positivos.
 Recall: Capacidade de identificar todas as instâncias positivas.
 F1-Score: Média harmônica entre precisão e recall.
 
Ambos os métodos (Feature Extraction e Fine-Tuning) foram comparados para avaliar qual técnica proporciona melhores resultados 
para a classificação do dataset "Cats vs Dogs".
 
 Vídeo Explicativo
Um vídeo explicativo sobre as técnicas de Transfer Learning, e a aplicação que foi realizada, e as comparações entre as abordagens de Feature Extraction e Fine-Tuning, destacando os passos de implementação adaptaçoes, e os resultados obtidos 
Link []

Base de Dados
O conjunto de dados utilizado foi o Cats vs Dogs, disponível no Kaggle. Este conjunto contém 25.000 imagens divididas entre as classes "Cachorro" e "Gato". As imagens foram usadas para treinar os modelos nas técnicas de Feature Extraction e Fine-Tuning.
Link dataset  Kaggle: https://www.kaggle.com/datasets/shaunthesheep/microsoft-catsvsdogs-dataset


