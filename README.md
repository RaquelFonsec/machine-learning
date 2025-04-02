Análise e Previsão de Rendimento de Estudantes em Portugal

Objetivo


O objetivo deste projeto é utilizar um conjunto de dados real sobre estudantes para realizar uma análise exploratória, pré-processamento de dados, e aplicar diferentes modelos de machine learning para prever o desempenho acadêmico dos alunos. A análise será dividida em duas abordagens:

Previsão da Nota Final (G3): Modelos de regressão.

Classificação Aprovado/Reprovado: Modelos de classificação.

Base de Dados Sugerida
A base de dados utilizada neste projeto é o Student Performance Data Set, disponível no UCI Machine Learning Repository.

Este conjunto de dados contém informações sobre alunos do ensino médio em Portugal, incluindo:

Dados Demográficos: Sexo, idade, tipo de endereço, tamanho da família, etc.

Hábitos de Estudo: Tempo dedicado ao estudo, número de faltas, etc.

Consumo de Álcool: Consumo diário e no final de semana.

Participação em Atividades Extracurriculares: Se o aluno participa ou não.

Notas ao Longo do Ano: G1, G2, G3 (onde G3 é a nota final).

Este conjunto de dados permite realizar tanto tarefas de regressão quanto de classificação.

Tarefas Propostas
1. Análise Exploratória
Objetivo: Compreender a estrutura do conjunto de dados, verificar tipos de dados e valores ausentes, e explorar a distribuição das variáveis.

Passos:

Verificar os tipos de dados e possíveis valores nulos.

Analisar a distribuição das variáveis e como elas se relacionam com as notas (G3).

Visualizar a correlação entre variáveis.

2. Pré-processamento de Dados
Objetivo: Preparar os dados para os modelos de machine learning.

Passos:

Substituir valores nulos com a média para colunas numéricas e a moda para colunas categóricas.

Transformar variáveis categóricas em numéricas utilizando o Label Encoder.

Normalizar as variáveis numéricas para garantir que os modelos de machine learning possam aprender de maneira eficiente.

3. Divisão dos Dados
Objetivo: Separar os dados em conjuntos de treino e teste.

Passos:

Dividir os dados em 70% para treino e 30% para teste.

Separar os dados para regressão (prever a nota final - G3) e classificação (classificar como aprovado ou reprovado, baseado em G3 ≥ 10).

4. Aplicação dos Modelos
Modelos de Regressão:
Regressão Linear: Prever a nota final (G3).

Árvore de Decisão Regressora: Prever a nota final (G3).

Métrica de Avaliação: R² (coeficiente de determinação), para avaliar a precisão do modelo.

Modelos de Classificação:
Regressão Logística: Classificar os alunos como Aprovados ou Reprovados (G3 ≥ 10).

Árvore de Decisão Classificadora: Classificar os alunos como Aprovados ou Reprovados (G3 ≥ 10).

Métricas de Avaliação:

Acurácia

Precisão

Recall

Matriz de Confusão

Resultados Obtidos
Após treinar os modelos, os seguintes resultados foram obtidos:

Modelos de Classificação:
🔹 Regressão Logística

Acurácia: 0.92

Precisão: 0.93

Recall: 0.95

Matriz de Confusão:

[
41
5
4
69
]
[ 
41
4
​
  
5
69
​
 ]
🔹 Árvore de Decisão (Classificação)

Acurácia: 0.84

Precisão: 0.86

Recall: 0.88

Matriz de Confusão:

[
36
10
9
64
]
[ 
36
9
​
  
10
64
​
 ]
Modelos de Regressão:
🔹 Regressão Linear - R²: 0.79
🔹 Árvore de Decisão Regressora - R²: 0.82

Conclusão: A Árvore de Decisão Regressora teve melhor desempenho para prever a nota final dos alunos (R² = 0.82).

Conclusão
Neste projeto, conseguimos:

Realizar uma análise exploratória detalhada sobre o desempenho dos estudantes.

Aplicar técnicas de pré-processamento de dados para preparar o conjunto de dados para análise.

Treinar e avaliar modelos de regressão e classificação para prever a nota final dos estudantes e classificá-los como aprovados ou reprovados.

A Árvore de Decisão Regressora se mostrou o modelo mais eficaz para a previsão da nota final (G3), enquanto a Regressão Logística teve bom desempenho na classificação Aprovado/Reprovado.

