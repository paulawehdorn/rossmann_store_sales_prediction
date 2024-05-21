# Sales Forecasting Project - Rossmann Store Sales
![rossmann_cover](https://github.com/paulawehdorn/rossmann_store_sales_prediction/assets/37786319/3c57a302-39a1-47bc-bc94-a19d7d5f646f)

## 1. Descrição
Este é um projeto end-to-end com o objetivo de prever vendas para as próximas seis semanas de todas as lojas da rede de farmácias Rossmann, utilizando técnicas de análise de dados e machine learning.

## 2. Entendimento do negócio
### 2.1. Contexto
A Rossmann é uma rede de drogarias com origem alemã. Com mais de 3.000 lojas em sete países europeus, ela é uma das maiores redes de drogarias na Europa. A empresa vende uma variedade de produtos, incluindo itens de cuidados pessoais, produtos de beleza, produtos para o lar, alimentos e bebidas, entre outros. A Rossmann é conhecida por oferecer uma ampla gama de produtos a preços acessíveis e por sua presença em muitas comunidades locais na Europa.

### 2.2. Por que é importante para o negócio?
#### **Desafio**
Atualmente, os gerentes das lojas da Rossmann têm a tarefa de prever suas vendas diárias com até seis semanas de antecedência. As vendas das lojas são influenciadas por muitos fatores, incluindo promoções, concorrência, feriados escolares e estaduais, sazonalidade e localização. Com milhares de gerentes individuais prevendo vendas com base em suas circunstâncias únicas, a precisão dos resultados pode variar bastante.

#### **Objetivo**
Com o intuito de reformar as lojas Rossmann, o CFO precisa da previsão de vendas diárias das próximas seis semanas para investir parte do lucro no orçamento destinado às reformas.

### 2.3. Como vamos trabalhar?
O objetivo deste projeto é gerar o maior valor possível no menor espaço de tempo, seguindo o Princípio de Pareto. Para isso, faremos entregas em ciclos, sempre priorizando o que gera maior percepção de valor para o cliente, utilizando a Metodologia Agile. Seguiremos o método CRISP-DM para organizar as etapas do projeto, pois ele nos ajuda a desde a definição do problema até a implementação da solução.

**Fonte de dados:**

Utilizaremos dados públicos, disponíveis [aqui](https://www.kaggle.com/c/rossmann-store-sales).

### 2.4. O que vamos entregar?
A principal demanda do CFO é obter o valor total de vendas para as próximas seis semanas. Portanto, neste ciclo entregaremos os valores totais e, no próximo ciclo, forneceremos as previsões de vendas por loja.

## 3. Conclusões
O modelo com melhor performance foi o XGBoost Classifier, que entregou o seguinte resultado:

![image](https://github.com/paulawehdorn/rossmann_store_sales_prediction/assets/37786319/3906321e-3403-4d32-8df2-4080e5e048f8)

Ou seja, para as próximas 6 semanas, as 1.115 lojas da Rossmann irão faturar aproximadamente R$285 milhões, com um erro de 13,5%. Sendo que a arrecadação total prevista para o pior cenário é de R$ 283.453.104,21 e para o melhor cenário é de R$ 284.978.623,45.

## 4. Próximos passos
- Criar um modelo em produção que forneça a previsão de vendas das próximas seis semanas de apenas uma loja específica, conforme seja solicitado pelo usuário.

## 5. Tecnologias Utilizadas
- Python, Pandas, Numpy, Matplotlib, Seaborn, Scikit-Learn;
- Jupyter Notebook;
- XGBoost Classifier;
- Pickle, BorutaPy, Scipy;
- CRISP-DM;
- Git e Github.
