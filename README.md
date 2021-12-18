# Previsão de tarifa de táxi de Nova Iorque

A base de dados foi extraída desta competição do Kaggle: https://www.kaggle.com/c/new-york-city-taxi-fare-prediction/overview. Abaixo a descrição:

> Nesta competição [...] você tem a tarefa de prever o valor da tarifa (inclusive pedágios) para uma corrida de táxi em Nova Iorque, dado os locais de partida e destino. **Embora você possa obter uma estimativa básica baseada apenas na distância entre os dois pontos, isso resultará em um RMSE de 5 a 8**, dependendo do modelo utilizado [...]. Seu desafio é ter resultados melhores do que esses usando técnicas de aprendizagem de máquina!

São disponibilizados duas bases de dados:

>`train.csv` - Características de entrada e valor da taxa, que corresponde a base de dados de treinamento (aproximadamente 55M de linhas).<br>
>`test.csv` - Características de entrada para a base de dados de teste (aproximadamente 10K linhas). O seu objetivo é prever a taxa para cada linha.

Para reduzir o tempo de processamento devido a grande quantidade de dados, foi optado trabalhar com 250k amostras da base de dados de treino disponibilizada para a competição.

### Caso o nootbook não seja caregado pelo GitHub acesse o [link](https://nbviewer.org/github/ernestojr-7/kaggle_tarifa_taxi/blob/main/Previsao_Tarifa_de_Taxi_de_Nova_Iorque.ipynb)
