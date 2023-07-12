# Detecção de Fraudes em Cartões de Crédito

Este é um projeto de detecção de fraudes em cartões de crédito. O objetivo é construir modelos de aprendizado de máquina para prever transações fraudulentas com base em um conjunto de dados de transações de cartão de crédito.

## Conjunto de Dados

O conjunto de dados utilizado neste projeto é chamado [Detecção de Fraudes em Cartões de Crédito](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) e contém transações feitas por titulares de cartões de crédito europeus. O conjunto de dados consiste em 284.807 transações, das quais 492 são fraudulentas. As variáveis de entrada são resultado de transformações de Análise de Componentes Principais (PCA) para preservar a confidencialidade dos dados. As principais variáveis incluem 'Time', 'Amount' e 'V1' a 'V28', e a variável alvo é 'Class', que indica se a transação é fraudulenta (1) ou não (0).

## Funcionalidades do Projeto

O projeto consiste nas seguintes etapas:

1. Análise Exploratória de Dados (EDA): Nesta etapa, são realizadas análises e visualizações para entender melhor os dados, como a distribuição de tempo, valor das transações e a relação entre as variáveis.

2. Pré-processamento de Dados: Nesta etapa, os dados são processados e preparados para o treinamento dos modelos. Isso pode envolver a normalização das variáveis, tratamento de valores ausentes ou inconsistentes, e balanceamento das classes.

3. Modelagem: Vários modelos de classificação são treinados e avaliados utilizando técnicas como Regressão Logística, Naive Bayes, Random Forest, entre outros. O desempenho dos modelos é avaliado com base em métricas como precisão, recall, F1-score e acurácia.

4. Avaliação e Seleção do Melhor Modelo: Os modelos são comparados e o melhor modelo é selecionado com base em sua capacidade de detectar transações fraudulentas de forma precisa.

## Dependências do Projeto

Para executar este projeto, você precisará das seguintes dependências:

- Python (versão 3.6 ou superior)
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn

## Instruções de Uso

1. Faça o download do conjunto de dados [Detecção de Fraudes em Cartões de Crédito](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) e coloque-o na pasta do projeto.

2. Abra o arquivo do projeto em um ambiente Jupyter Notebook.

3. Execute as células do notebook em sequência para realizar as etapas de análise, pré-processamento, modelagem e avaliação.

## Contribuição

Contribuições são bem-vindas! Se você tiver alguma sugestão, correção ou melhoria para o projeto, fique à vontade para abrir uma "issue" ou enviar uma solicitação de "pull request".

## Licença

Este projeto é licenciado sob a licença MIT. Para mais detalhes, consulte o arquivo [LICENSE](LICENSE).

