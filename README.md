# Wine Classification Using Decision Trees in Python
The project aims to develop a decision tree model for predicting wine classification **(Class 0, Class 1, or Class 2)** based on thirteen distinct chemical measurements obtained from various wine samples. The input features utilized in the model include: Alcohol, Malic Acid, Ash, Alcalinity of Ash, Magnesium, Total Phenols, Flavanoids, Nonflavanoid Phenols, Proanthocyanins, Color Intensity, Hue, OD280/OD315 of diluted wines, and Proline.

This classification problem is critical for the wine industry, as it enables businesses to accurately and consistently categorize wines based on their chemical composition. By implementing a reliable decision tree model, wine producers can enhance their quality control processes, ensuring that their products meet both industry standards and consumer expectations.

## Methodology
* The Wine dataset is loaded using the load_wine() function from the scikit-learn library.
* The data is converted into a Pandas DataFrame.
* The dataset is shuffled to ensure a random distribution of samples.
* The dataset is divided into training and testing sets using an 80-20 ratio.
* A Decision Tree classifier is instantiated using the entropy criterion to determine optimal splits.
* The classifier is trained on the training data.
* A plot of the decision tree is generated to provide insights into the importance of different features in classifying wine types.
* The model's performance is assessed by calculating its accuracy, precision, and recall on its test set.

## Performance metrics
* The decision tree achieved an **accuracy of 0.88**, indicating that 88% of the wine classifications were correctly predicted.
* The model attained a **recall of 0.89**, demonstrating its effectiveness in identifying true positive classifications among the wine samples.
* The model also achieved a **precision of 0.89**, reflecting the proportion of positive identifications that were actually correct, showcasing the model's reliability in classifying wine types.

## Insightful discussion
The decision tree analysis reveals that **color intensity** is the most informative feature for predicting wine class. This insight suggests that wine producers should prioritize measuring color intensity when assessing wine quality. For instance, wines with higher color intensity may be associated with richer and more complex flavor profiles. Understanding the importance of color intensity enables producers to make informed decisions throughout the winemaking process, such as selecting grape varieties or adjusting fermentation techniques to achieve the desired hue.

Additionally, the decision tree indicates that **proline** and **flavonoids** are also significant factors in distinguishing between wine classes. Recognizing the roles of these features can guide producers in optimizing their production methods, enhancing the overall quality and marketability of their wines. By focusing on these key attributes, wineries can better align their offerings with consumer preferences and industry standards, ultimately leading to improved product consistency and satisfaction.
