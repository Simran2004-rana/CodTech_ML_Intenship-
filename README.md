DECISION TREE IMPLEMENTATION

COMPANY: CODTECH IT SOLUTIONS

NAME: SIMRAN

INTERN ID: CT04DF1484

DOMAIN: MACHINE LEARNING

DURATION: 4 WEEKS

MENTOR: NEELA SANTHOSH


DESCRIPTION : In this task, we implemented a Decision Tree Classifier using Python's scikit-learn library, which is one of the most widely used machine learning libraries for building supervised learning models. The main objective of this task was to understand the process of building, training, testing, and visualizing a decision tree on a classic dataset.We used the Iris dataset, a popular benchmark dataset for classification tasks that includes three species of the Iris flower: Setosa, Versicolor, and Virginica. The dataset contains four numerical features: sepal length, sepal width, petal length, and petal width. These features are used as input variables to predict the species of the flower (target variable).We started by importing essential libraries including pandas, numpy, matplotlib, and modules from sklearn such as DecisionTreeClassifier, train_test_split, and plot_tree. The Iris dataset was loaded directly using load_iris() from sklearn.datasets.After loading the dataset, we separated the features (X) and the labels (y). We then split the data into training and testing sets using an 80-20 ratio. The training data was used to fit the decision tree model, and the testing data was used to evaluate its performance. We used DecisionTreeClassifier with default parameters and set a fixed random_state for reproducibility.Once the model was trained, predictions were made on the test set. We evaluated the model's performance using accuracy score and classification report. These metrics helped us understand how well the decision tree was able to classify unseen data based on the training it received.Additionally, the decision tree was visualized using plot_tree(). This graphical representation of the tree helps in interpreting how decisions are made by the model at each node based on feature thresholds. Each node in the tree shows the feature used for the split, the threshold, class distributions, and Gini impurity, which measures the purity of the node.One of the key advantages of decision trees is that they are highly interpretable and can handle both numerical and categorical data. However, they are prone to overfitting, especially if not properly pruned. In our case, we used the default settings, which worked well on the Iris dataset because of its small size and clean structure.Through this task, we gained practical experience in:Loading and preparing datasets,Implementing a machine learning model using scikit-learn,Evaluating classification performance,
And visualizing a decision tree for better interpretability,This task laid the foundation for understanding supervised machine learning, classification models, and decision-making processes in ML. It also helped build confidence in using scikit-learn tools for real-world problems. The simplicity and clarity of the Iris dataset made it ideal for learning and demonstration purposes.

OUTPUT:![Image](https://github.com/user-attachments/assets/33e9cfce-ef6d-48ec-aa66-d2011545c400)
 
