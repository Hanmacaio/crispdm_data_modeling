Esse exercício é uma atividade de reposição de dados utilizando um dicionário pronto da bibliotéca SKLearn, seguindo apenas a etapa de de Modeling do CrispDM.
O intúito desse projeto é justamente praticar essa etapa do crisp enquanto posso fixar minhas habilidades e ferramentas em python.

O dicionário utilizado foi fetch_california_housing disponível no link abaixo
https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html

O objetivo é realizar a predição do target com a menor taxa de erro possível, para isso, seguido a ideia de materiais disponíveis na internet decidi utilizar os seguintes métodos de modelagem:
-  Linear Regression do SKLearn (LR)
-  Support Vector Regression do SKLearn (SVR)
-  Decision Tree Rregression do XGBoost (DTR)
Assumindo apenas Variáveis numéricas.

Para as métricas de avaliação do modelo, escolhi utilizar:
- Mean Square Error do SKLearn (MSE)
- Root Mean Square Error do SKLearn + Nunpy (RMSE)
Levando em consideração que estou buscando penalizar o modelo sempre que ele decidir realizar erros 'muito' fora da curva.

Para realizar a divisão de treino e teste, foi utilizada uma proporção padrão de 80% e 20% respectivamente.
