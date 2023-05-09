# Previsão de vendas das lojas Rossmann

## 1. Sobre o Projeto
Este é um projeto fictício, com o objetivo de desenvolver e demonstrar conhecimento nos estudos de Machine Learning, especificamente na criação de modelo de previsão de vendas.
Utilizaremos:
- Dados disponíveis no [Kaggle](https://www.kaggle.com/c/rossmann-store-sales).
- Método CRISP-DM, seguindo os 11 passos descritos na [seção 6](#planejamento-da-solução).

## 2. Tecnologias Utilizadas
Python, Pandas, NumPy, Heroku, XGBoost, Seaborn, Boruta, Matplotlib, Flask, Telegram, Scikit-Learn, Jupyter Notebook

## 3. Contato
- paulawehdorn@gmail.com
- [LinkedIn](https://www.linkedin.com/in/paulawehdorn/)
- [Portfólio](https://paulawehdorn.github.io/portfolio_projetos/)

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

## 5. Problema de Negócio
Com o intuito de reformar as lojas da Rossmann, o CFO solicitou uma previsão de vendas para as próximas seis semanas, a fim de investir parte do lucro no orçamento destinado às reformas.

## 6. Planejamento da Solução <a id="planejamento-da-solução"></a>

O método CRISP-DM (Cross Industry Standard Process for Data Mining) é uma metodologia amplamente utilizada em projetos de Data Science e Mineração de Dados. Ele ajuda a organizar as etapas do projeto desde a definição do problema até a implementação da solução. Ele é útil porque fornece uma estrutura clara para o trabalho e ajuda a garantir que nenhuma etapa importante seja ignorada ou negligenciada. Além disso, o CRISP-DM ajuda a manter o foco no problema real que se pretende resolver, permitindo que o projeto seja mais eficiente e eficaz.

O CRISP-DM é composto por 6 fases principais: 

1. Entendimento do problema;
2. Entendimento dos dados;
3. Preparação dos dados;
4. Modelagem;
5. Avaliação do modelo;
6. Deploy.

## 7. Performance do Modelo

## 8. Deploy do Modelo

## 9. Conclusão
