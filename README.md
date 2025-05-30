# AnaliseML_Atraso_Entregas
Analise de uma base de dados para descobrir porque as entregas estão atrasando e criando um modelo que consegue prever atrasos

**Etapas do Projeto:**

1- Coleta dos dados
  - importei o dataset
  - conheci os dados
  - traduzi o dataframe para portugues para o mehlor entendimento

2- 'Tratamento' dos outliers
  - Encontrei outliers na tabela mas não achei necessario excluir eles

3- Analise Exploratoria
  - Separei os dados por Prazos Negativos e Positivos em dataframes diferentes
  - Usei estatistica para extrair alguns insights e descobri o que causava os atrasos

4 - Visualização de Graficos
  - A partir do que eu descobri sobre o que causava os atrasos com os insights criei dois graficos comparando o prazo de entrega antes e depois de ter descoberto o que fazia os pedidos atrasarem

5 - Treino do Modelo Preditivo
  - Treinei dois modelos para que pudessem futuramente realizar previsões de Atrasos de entrega
  - Visualizei a acuracia dos dois e decidi qual seria melhor
  - Salvei o modelo usando a biblioteca Joblib
