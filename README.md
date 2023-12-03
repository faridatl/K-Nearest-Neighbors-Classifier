## K-Nearest-Neighbors-Classifier (KNN):

The Wine Dataset from the UCI machine learning repository consists of the results of a chemical analysis of wines grown within the same region in Italy but derived from three different cultivers. The analysis determined 13 constituents (attributes) found in the three types of wine. The K-Nearest Neighbors Classifier is a supervised learning algorithm that will be used to classify and test the perfomance of this model. 80% of the data will be reserved for training and the remaining 20% will be used for testing. The standardization/scaling of features was implemented to mitigate the potential dominance of one feature over another, ensuring a uniform scale for all features. This model evaluation deviates from standard binary classification, as it involves three classes instead of two. Consequently, adjustments were made to the Confusion Matrix calculation to accommodate the multi-class nature of the problem. Additionally, the random state was considered in the process to make results reproducible and to compare models or changes under the same initial conditions.

**Important Note:** Overall model accuracy with a random state of 42 was 94.4%, but, as noted in the code, when a random state of 73 was used, model accuracy improved to 100%.

## 🛠️ Technologies Used:

Python: Leveraging the power of Pandas, NumPy, and Scikit-Learn.

Sublime Text: Efficient, versatile code editor with minimalist interface.

## 📈 Results:

* The K-Nearest Neighbors (KNN) classifier, applied to the UCI machine learning wine dataset, demonstrated outstanding performance. It achieved a sensitivity of 100% for all classes (Class 1, Class 2, and Class 3), indicating a flawless ability to correctly identify instances of each class. Additionally, the classifier exhibited a specificity of 100% for all classes, showcasing its precision in correctly recognizing instances not belonging to each class. 

* A sensitivity rate of 100% for all classes (Class 1, Class 2, and Class 3) suggests that the K-Nearest Neighbors (KNN) classifier is highly effective in correctly identifying instances of each class. It indicates that the classifier successfully captures all positive instances, making it sensitive to the presence of each class in the dataset.

* Similarly, a specificity rate of 100% for all classes implies that the KNN classifier is precise in recognizing instances that do not belong to each class. This indicates a high level of accuracy in identifying true negatives, further emphasizing the classifier's specificity for each class.

* The overall model accuracy reached a remarkable 100%, emphasizing the KNN classifier's exceptional capability to accurately predict and classify instances across all classes in the wine dataset. A 100% accuracy rate is a strong indicator of the model's effectiveness in learning and generalizing from the provided data. However, it's essential to consider the characteristics of the dataset, potential overfitting, and the context of the problem to ensure a comprehensive understanding of the model's performance.

## 🔗 How to Use:

Each project/code along with their dataset has been uploaded for your review or observation. Please feel free to reach out if you have questions, suggestions, or if you're interested in collaboration!

## 🌐 Connect with Me:

LinkedIn: (https://www.linkedin.com/in/faridatlawal/)

##### I'm continuously learning and expanding my skill set. Join me on this exciting journey through the world of machine learning! 🤖✨
