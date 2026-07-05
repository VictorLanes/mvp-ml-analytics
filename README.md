# MVP - Machine Learning & Analytics: Risco de Saúde Materna

Projeto de MVP disciplina de Machine Learning & Analytics, Foi desenvolvido com o objetivo de classificar o nível de risco de saúde materna (baixo, médio ou alto) a partir de sinais vitais coletados por um sistema de monitoramento IoT em áreas rurais de Bangladesh.

## Dataset

Maternal Health Risk Data Set, do UCI Machine Learning Repository (1.013 registros, 6 atributos preditores + variável-alvo `RiskLevel`). O CSV está disponível neste repositório e é carregado no notebook via URL raw do GitHub.

## Abordagem

Análise exploratória, preparação dos dados (codificação ordinal, padronização), divisão treino/teste estratificada, comparação entre baseline e 5 modelos de classificação (KNN, Árvore de Decisão, Random Forest, SVM, Regressão Logística), otimização de hiperparâmetros via GridSearchCV e avaliação final com métricas de classificação.

## Resultado

Random Forest otimizado foi o melhor modelo, com acurácia de teste próxima da validação cruzada, sem sinais de overfitting/underfitting.

## Como executar

Abra o notebook `MVP_Maternal_Health_Risk_.ipynb` no Google Colab. O dataset é carregado automaticamente via URL pública deste repositório, sem necessidade de configuração adicional.
