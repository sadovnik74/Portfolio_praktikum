# Классификация токсичных комментариев
## Описание проекта

Необходимо обучить модель классификации комментариев на позитивные и негативные. В нашем распоряжении набор данных с разметкой о токсичности правок.

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **nltk**
- **matplotlib**
- **seaborn**
- scipy.sparse.**vstack**
- nltk.corpus.**stopwords**
- nltk.stem.**WordNetLemmatizer**
- sklearn.feature_extraction.text.**TfidfVectorizer**
- sklearn.metrics.**f1_score**
- sklearn.linear_model.**LogisticRegression**
- sklearn.tree.**DecisionTreeClassifier**
- sklearn.ensemble.**RandomForestClassifier**
- sklearn.model_selection.**GridSearchCV**
- sklearn.model_selection.**RandomizedSearchCV**
- sklearn.model_selection.**PredefinedSplit**
- sklearn.model_selection.**train_test_split**
- sklearn.svm.**SVC**
- **re**

## Краткий вывод
В проекте был применен подход к преобразованию текстовых данных векторизация TF-IDF. Были обучены и оценены модели логистическая регрессия, решающее дерево и случайный лес.

По качеству и скорости обучения лучше всех показала Логистическая регрессия с коэфициентом С=10 и F1=0.767.
