# AnaliseML_Atraso_Entregas
Analise de uma base de dados para descobrir porque as entregas estão atrasando e criando um modelo que consegue prever atrasos

**Etapas do Projeto:**

1- Coleta dos dados
  - Usei a biblioteca Pandas
  - Importei o dataset
  - Conheci os dados
  - Traduzi o dataframe para portugues para o mehlor entendimento

2- 'Tratamento' dos outliers
  - Usei as bibliotecas Matplotlib e Seaborn para criar os graficos de BoxPlot 
  - Encontrei outliers na tabela mas não achei necessario excluir eles

3- Analise Exploratoria
  - Separei os dados por Prazos Negativos e Positivos em dataframes diferentes
  - Usei estatistica para extrair alguns insights e descobri o que causava os atrasos

4 - Visualização de Graficos
  - Usei as bibliotecas Matplotlib e Seaborn para criar os graficos de barras
  - A partir do que eu descobri sobre o que causava os atrasos com os insights criei dois graficos comparando o prazo de entrega antes e depois de ter descoberto o que fazia os pedidos atrasarem

5 - Treino do Modelo Preditivo
  - Usei as bibliotecas do SkitLearn
  - Treinei dois modelos para que pudessem futuramente realizar previsões de Atrasos de entrega
  - Visualizei a acuracia dos dois e decidi qual seria melhor
  - Salvei o modelo usando a biblioteca Joblib

### Insights:

**Porque os Pedidos Atrasam:**
  - Os pedidos mais mal avaliados tem em media 1 estrela de avaliação
  - Os que mais atrasam são enviados por navios
  - Pedidos atrasados tem media de 4 chamadas de suporte
  - São mais pesados, tem em media 4173 libras
  - São mais caros e tem valor em media de 214 dolares

**Pedidos com Prazo Positivo tem o maior numero de entregas por navio e media de 4 chamadas de suporte tambem mas:**
  - São mais leves pesando em média 3292 libras
  - São mais baratos custando em média 208 dolares
  - E média de avaliação de 5 estrelas

### Como resolver os atrasos:
  **Com pedidos mais leves e preços menores nós conseguimos diminuir os Prazos de entrega negativos**
