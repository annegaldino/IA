PEste primeiro projeto tem como intuito predizer a marca de um carro que será vendida com base em dados do consumidor:

- Download do DataSet: https://www.kaggle.com/datasets/missionjee/car-sales-report
- Criar no Portal Azure um Recurso de Azure Machine Learning
- Ir para o Azure Machine Learning Studio e criar uma atividade automatizada de Machine Learning
- O tipo de tarefa será classificação
- Realizar upload do arquivo local 
- selecionar as colunas como features que mais faz sentido, eliminando coluna de data e ID, nome de vendedores
- Na configuração da tarefa o target será Company, que é a marca do automóvel, a métrica primária será Accuracy
- Entre os modelos permitidos, selecionar LogisticRegression, Decision Tree e Random Forest
- O nível de nós será até 50, e o percentual de testes de 20%, timeout será de 15 min, tentaivas serão 3
- Treinar o modelo
- Implantar Serviço Web do melhor modelo