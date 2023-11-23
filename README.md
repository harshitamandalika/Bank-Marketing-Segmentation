# Bank-Marketing-Segmentation

- A Term deposit is a deposit that a bank or a financial institution offers with a fixed rate in which your money will be returned back at a specific maturity time. The
process by which companies create value for customers and build strong customer relationships in order to capture value from customers in return is known as Market-
ing. Using the marketing trends and Machine Learning, banks can make their work easier.
- This project aims to detect if a particular customer will opt for term deposits or not. Machine Learning is used to train the algorithms on data collected
by a Portugal Bank during their marketing campaign. The name of this dataset is the 'Bank Marketing' that consists of 17 variables including the target class. Link to the dataset- https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset
- Several pre-processing steps are applied on the dataset and refined for future use. Firstly, the outliers in the dataset are removed and then a label encoder is used to
transform the data. As the dataset is imbalanced with the 2 classes having 11% and 89% of the data, SMOTE is used to balance the dataset. After balancing the dataset,
Extra tree classifier is used and 10 out of the 16 features are selected. Furthermore, machine learning algorithms are fit on this data and the best-fit model which shows the highest metrics is found.
- After fitting the machine learning models, the performance of these machine learning models are compared based on different metrics such as accuracy, precision, recall and F1 scores. The Random Forest classifier and XG Boost have obtained the highest accuracy scores of 0.928 and 0.925 respectively.
