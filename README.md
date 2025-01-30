# Trabalho-Final---ML

Universidade Federal do Rio Grande do Norte

Programa de Pós-Graduação em Engenharia Elétrica e de Computação

Disciplina: Aprendizado de Máquina

Este repositório contém a solução para a atividade final da disciplina de Aprendizado de Máquina. O objetivo principal é aplicar e avaliar as técnicas de Transfer Learning (Aprendizado por Transferência) comparando o desempenho de dois métodos:

Técnicas Utilizadas

Feature Extractor (Extração de Características)

Nesta abordagem, usamos o modelo AlexNet pré-treinado para extrair características das imagens, a última camada do modelo foi removida, mantendo apenas as camadas convolucionais.
As imagens foram processadas, e suas características foram extraídas e usadas para treinar um modelo de Regressão Logística. O modelo foi avaliado em termos de Acurácia e F1-Score.

Fine-Tuning

Utilizamos o modelo AlexNet pré-treinado, congelando as camadas convolucionais e ajustando apenas a camada final, adaptando-o para a atividade de aprendizado de máquina. O modelo foi treinado por 10 épocas no primeiro stage e 5 épocas no segundo stage,avaliado com Acurácia, Precisão, Recall e F1-Score.
 
 
 Vídeo Explicativo
 
 Um vídeo explicativo sobre as técnicas de Transfer Learning, e a 
 aplicação que foi realizada, e as comparações entre as abordagens de 
 Feature Extractor e Fine-Tuning, destacando os passos de implementação 
 adaptaçoes, e os resultados obtidos 
 Link :https://drive.google.com/file/d/1Zr9T1z7ZLDPJaMtzcdHPiQ7XJyHpp__E/view?usp=sharing

Base de Dados

O conjunto de dados utilizado foi o Cats vs Dogs, disponível no Kaggle. Este conjunto contém 25.000 imagens divididas entre as classes "Cachorro" e "Gato".

Link dataset  Kaggle: https://www.kaggle.com/datasets/shaunthesheep/microsoft-catsvsdogs-dataset


