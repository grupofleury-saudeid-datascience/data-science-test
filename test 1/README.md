# Data Science

## Introdução

Com o objetivo de avaliar algumas das competências importantes para essa posição, pedimos que realize um estudo de Ciências de Dados na linguagem Python (versão 3 em diante) proposto no problema abaixo.

### Entregáveis

A solução para o problema proposto abaixo deve ser entregue com as seguintes caracteristicas:

- Todos os arquivos necessários para reproduzir a solução (e.g notebooks, arquivos e etc.);

- Arquivo de texto explicando como re-executar o estudo feito;

- Sua solução deve poder ser re-executada em uma máquina local;

- Melhores práticas de tecnologias, escrita de código, nomemclatura de variáveis e aquivos...etc;

- Áudio/Video (de 8min no máximo) ou Texto (também jupyter notebook/.py) com explicação da sua solução.

### Instruções para envio

 - Crie um repositório para a solução no seu ```https://github.com/``` e faça upload dos entregáveis;

 - Autorize o acesso ao seu projeto para o usuário ```grupofleury-datascience``` e siga as instruções enviadas também em seu e-mail;

 - Em caso de dúvida entre em contato por e-mail.

## O problema

Os dados estão nos arquivos seguinte:

- advertising.csv
- Ecommerce_Purchases.csv

### Sua solução deve conter as etapas abaixo com base nos dados fornecidos

#### Utilizando a biblioteca pandas

1. Importe a biblioteca ```Pandas``` as leia o arquivo ```Ecommerce Purchases.csv```.

1. Quantas linhas e colunas o dataframe tem? Quais os datatypes?

1. Quais foram os 5 ```Purchase Price``` mais altos e mais baixos?

1. Quantas pessoas tem no ```Job``` o título aparece ```Scientist```?

1. Quantas pessoas tem ```American Express``` como ```CC Provider``` e fizeram compras acima de $95?

1. Quais foram os 5 dominios mais populares (```gmail.com, yahoo.com```)?

#### Análise de dados

1. Usando o dataset ```advertising.csv``` faça uma analise exploratória dos dados, coloque seus comentários e o que achou interessante em sua análise.

1. Crie um gráfico de dsitribuição com KDE do  ```Daily Time spent on site``` vs. ```Age```. Quais suas conclusões?

1. Crie um pairplot com HUE definido como ```Clicked on Ad```. Quais suas conclusões?

#### Predição da variável resposta 'Clicked on Ad'

1. Separe os dados para treino e teste.

1. Escolha o modelo de predição. Por que foram escolhidos esses modelos ? Explique resumidamente o que fazem.

1. Quais métricas utilizou para treinar e validar a performance do modelo?

1. Calcule os erros dos modelos. Quais erros foram calculados, explique resumidamente o que eles representam. Plote a ```Curva ROC``` e Calcule o ```AUC```.

1. Escolha o melhor modelo. Aplique o ```Cross Validation com kfold = 10``` e explique o que é.

1. Qual foi a média do erro obtido com o ```Cross Validation```?

1. Grave um áudio/video (de 8 min no máximo) ou se preferir no texto (também Jupyter notebook ou .py) para nos enviar seus resutados e conclusões.

## Avaliação

Após o envio da solução, avaliaremos sua solução e apresentação da mesma também pelo texto ou áudio/video, portanto comente tudo que achar importante ou grave o áudio/video (de 8 min no máximo) para complementar a apresentação da sua solução.