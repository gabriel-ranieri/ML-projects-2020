# Coletânea de Atividades Machine Learning 2020

## Processing the Adult database
Competição no Kaggle: https://www.kaggle.com/competitions/adult-pmr3508

A primeira seção é dedicada à dos dados, na qual são observadas como são distribuídas as variáveis do dataset, quais valores elas assumem etc; a outra seção é dedicada 
à avaliação do impacto da seleção de variáveis e feature engineering e seleção do parâmetro K, do algoritmo K-Nearest Neighbors(KNN), sobre a acurácia do seu classificador.

### Dados
* train_data.csv - contém a base de treino e a sua label ( a coluna "income");

* test.csv - contém a base de teste, porém sem a coluna de labels ( a avaliação é feita por meio da submissão de resultados na competição;

* sampleSubmission.csv Contém um exemplo de submissão para scoring da base de teste - todas suas submissões de resultados para esta competição devem seguir este formato;

* Extra file from UCI - contém detalhes adicionais sobre a base adult que estavam contidos originalmente no repositório.

## California Housing
Competição no Kaggle: https://www.kaggle.com/competitions/atividade-regressao-PMR3508

Construção de um modelo regressivo de machine learning que prevê o preço mediano de uma casa em uma região da Califórnia.

### Dados

* train.csv - O dataset de treino, contendo Ids, features e target , median_house_value;

* train.csv - O dataset de treino, contendo Ids, features e target , median_house_value;

* test.csv - As features de teste e suas Ids;

* sample_sub_1.csv - Submissão exemplo.

## Análise de Sentimentos com Redes Neurais
Competição no Kaggle: https://www.kaggle.com/competitions/sentiment-analysis-pmr3508/overview

Utilização de Redes Neurais para a classificação de textos de acordo com o sentimento que eles transmitem (Positivo ou Negativo). Pontos importantes:

* São utilizadas avaliações de filmes (IMDb);
* É utilizado um modelo pré-treinado de Deep Learning chamado Doc2Vec para a realização da transformações dos textos em embeddings (vetores);
* Redes neurais MLP são treinadas para a classificação dos textos.

### Dados
* data_train.csv: conjunto de textos e marcações para treinamento dos modelos de classificação;

* data_test1.csv: conjunto de textos e marcações para teste antes da submissão dos resultados finais;

* data_test2_X.csv: conjunto de textos utilizados para a submissão dos resultados finais;

* doc2vec: modelo Doc2Vec pré-treinado utilizado para representação vetorial dos textos.
