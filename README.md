# Trabalho-Final---ML

Universidade Federal do Rio Grande do Norte

Programa de Pós-Graduação em Engenharia Elétrica e de Computação

Disciplina: Aprendizado de Máquina

Este repositório contém a solução para a atividade final da disciplina de Aprendizado de Máquina. O objetivo principal é aplicar e avaliar as técnicas de Transfer Learning (Aprendizado por Transferência) comparando o desempenho delas em um problema de classificação.

Técnicas Utilizadas

Feature Extractor (Extração de Características)

Nesta abordagem, usamos o modelo AlexNet pré-treinado para extrair características das imagens, a última camada do modelo foi removida, mantendo apenas as camadas convolucionais.
As imagens foram processadas, e suas características foram extraídas e usadas para treinar um modelo de Regressão Logística. O desempenho do modelo foi avaliado com métricas de Acurácia e F1-Score.

Fine-Tuning

Na abordagem de Fine- Tuning o modelo AlexNet pré-treinado foi utilizado com  as camadas convolucionais congeladas, ajustando apenas a camada final,  para adaptar o modelo  à tarefa específica. O modelo foi treinado em duas fases 10 épocas no  primeiro estágio, e 5 épocas no segundo estágio, o desempenho foi avaliado utilizando as métricas, Acurácia, Precisão, Recall e F1-Score.
 
 
 Vídeo Explicativo
 
 Um vídeo explicativo sobre as técnicas de Transfer Learning, e a 
 aplicação que foi realizada, e as comparações entre as abordagens de 
 Feature Extractor e Fine-Tuning, destacando os passos de implementação 
 adaptaçoes, e os resultados obtidos. 
 
 Assita ao vídeo aqui 
 Link :https://drive.google.com/file/d/1Zr9T1z7ZLDPJaMtzcdHPiQ7XJyHpp__E/view?usp=sharing

 Artigo Medium
 Além do vídeo, foi elaborado um artigo no Medium detalhando a atividade realizada, com uma explicação sobre as técnicas 
 utilizadas, os resultados obtidos e as conclusões tiradas a partir da análise dos experimentos.
 
 Leia o artigo no Medium aqui
 
 Link :https://medium.com/@sayonaraufrn/universidade-federal-do-rio-grande-do-norte-bce54cbf8c10

Base de Dados

O conjunto de dados utilizado foi o Cats vs Dogs, disponível no Kaggle. Este conjunto contém 25.000 imagens divididas entre as classes "Cachorro" e "Gato".

Link dataset  Kaggle: https://www.kaggle.com/datasets/shaunthesheep/microsoft-catsvsdogs-dataset


