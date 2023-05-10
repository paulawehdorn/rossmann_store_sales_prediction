# Previsão de vendas das lojas Rossmann

## 1. Sobre o Projeto
**Desafio:**
- A Rossmann opera mais de 3.000 drogarias em 7 países europeus. Atualmente, o CFO solicitou aos gerentes de cada loja a tarefa de prever suas vendas diárias com até seis semanas de antecedência. As vendas da loja são influenciadas por muitos fatores, incluindo promoções, concorrência, feriados escolares e estaduais, sazonalidade e localidade. Com milhares de gerentes individuais prevendo vendas com base em suas circunstâncias únicas, a precisão dos resultados pode variar bastante.
- Com o intuito de reformar as lojas Rossmann, o CFO precisa da previsão de vendas diárias das próximas seis semanas para investir parte do lucro no orçamento destinado às reformas. 

**Utilizaremos:**
- Dados públicos, disponíveis no [Kaggle](https://www.kaggle.com/c/rossmann-store-sales).
- Método CRISP-DM, seguindo os passos descritos na [seção 5](#planejamento-da-solução).

**Observação:** 
* Este é um projeto fictício, com o objetivo de desenvolver e demonstrar conhecimento nos estudos de Machine Learning, especificamente na criação de modelo de previsão de vendas.

## 2. Contato
- paulawehdorn@gmail.com
- [Portfólio](https://paulawehdorn.github.io/portfolio_projetos/)
- [LinkedIn](https://www.linkedin.com/in/paulawehdorn/)

## 3. Tecnologias Utilizadas
- Python, Pandas, Numpy, Matplotlib, Seaborn, Scikit-Learn;
- Jupyter Notebook;
- XGBoost Classifier;
- Pickle, BorutaPy, Scipy;
- CRISP-DM;
- Git e Github.

## 4. Atributos
ATRIBUTO | DESCRIÇÃO 
-- | -- 
store | um ID único para cada loja
store_type | 4 modelos de lojas diferentes
assortment | descreve um nível de sortimento / variedade
competition_distance | distância em metros até a loja concorrente mais próxima
competition_open_since_month | o mês aproximado da hora em que o concorrente mais próximo foi aberto
competition_open_since_year | o ano aproximado da hora em que o concorrente mais próximo foi aberto
promo2 | uma promoção contínua e consecutiva para algumas lojas
promo2_since_week | descreve a semana do calendário em que a loja começou a participar do Promo2
promo2_since_year | descreve o ano em que a loja começou a participar do Promo2
promo_interval | descreve os intervalos consecutivos em que o Promo2 é iniciado, nomeando os meses em que a promoção é iniciada novamente.
day_of_week | dia da semana
date | data de venda
sales | o volume de negócios para um determinado dia
customers | o número de clientes em um determinado dia
open | um indicador para saber se a loja estava aberta
promo | indica se uma loja está realizando uma promoção naquele dia
state_holiday | indica um feriado estadual.
school_holiday | indica se a loja foi afetada pelo fechamento das escolas públicas

## 5. Planejamento da Solução <a id="planejamento-da-solução"></a>

Utilizaremos o método CRISP-DM, pois ele ajuda a organizar as etapas do projeto desde a definição do problema até a implementação da solução.

#### As 6 fases principais do CRISP-DM são: 

1. Entendimento do problema;
2. Entendimento dos dados;
3. Preparação dos dados;
4. Modelagem;
5. Avaliação do modelo;
6. Deploy.

#### Dentro do projeto, vamos quebrá-las em 9 passos:

1. Passo 01: Descrição dos dados;
2. Passo 02: Feature engineering;
3. Passo 03: Filtragem de variáveis;
4. Passo 04: Análise exploratória de dados (EDA);
5. Passo 05: Preparação dos dados;
6. Passo 06: Seleção de variáveis;
7. Passo 07: Modelagem de Machine Learning;
8. Passo 08: Hyperparameter fine tuning;
9. Passo 09: Error translation and interpretation.

## 6. Performance do Modelo

## 7. Deploy do Modelo

## 8. Impacto Financeiro

## 9. Conclusão

## 10. Possíveis Melhorias
