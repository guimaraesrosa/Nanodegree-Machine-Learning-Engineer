Projeto usa base de dados TSUM_B.CSV

Projeto desenvolvido em Jupyter Notebook, separado em três partes:
1. Exploração dos Dados
	- Ao final gera uma nova base de dados: exploration_data_trombose.csv
2. Pré-Processamento
	- Ao final gera uma nova base de dados para treinamento: 		    		pre_processing_trombose.csv
3. Modelos de Treinamento e Refinamento

Bibliotecas:

- pandas
- numpy
- matplotlib.pyplot
- seaborn


- sklearn.model_selection
	--train_test_split

- sklearn.metrics
	--confusion_matrix
	--precision_recall_curve
	--recall_score
	--classification_report
-sklearn.metrics 
	--accuracy_score
	--precision_score
	--f1_score


-itertools

#AdaBoost
-sklearn.tree 
	--DecisionTreeClassifier
-sklearn.ensemble
	--AdaBoostClassifier

-collections 
	--Counter
-imblearn.datasets
	--fetch_datasets
-sklearn.pipeline
	--make_pipeline
-imblearn.over_sampling
	--SMOTE, ADASYN
-imblearn.under_sampling
	--NearMiss
-imblearn.metrics
	--classification_report_imbalanced
-sklearn.ensemble 
	--RandomForestClassifier
-sklearn.svm
	--LinearSVC


