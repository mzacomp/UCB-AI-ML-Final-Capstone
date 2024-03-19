# UCB-AI-ML-Final-Capstone

### Capstone Project: Heart Disease Diagnosis Prediction

**by Mahsan Zare Asadabadi**

#### I. Executive summary
Cardiovascular diseases (CVDs) or heart diseases are the leading international cause of human death. According to a report conducted in 2019 by the World Health Organization (WHO), approximately 18 million people died that year due to CVDs, representing 32% of total deaths. Among them, 85% was caused by heart failure and stroke (1). It is difficult for physicians to diagnose these diseases early and correctly. A total of 25% of people die suddenly without any prior symptoms of heart disease. The use of machine learning methods can help experts in obtaining valuable insight about heart patients and promote early detection. The objective of this capstone project is the early detection of heart diseases by using classification models and  deep-learning models.


#### Rationale
Precision AI in medicine is a rapidly growing field of AI and machine learning. It is focused on   early detection of diseases and to quantify disease risk through the use of machine learning and artificial intelligence. This project can be a tool to provide experts with the knowledge of the most effective model to use for early detection for such a prominent disease like heart disease. 



#### Research Question
How do classification models compare with deep learning models to best predict heart disease diagnosis? 

### Objective: 
Objective: To use and test different classification and deep learning models to determine the highest evaluation metrics for heart disease diagnosis. 



#### Data Sources
I will be using the UCI Heart Disease Dataset from the UCI Machine Learning Repository(link: https://archive.ics.uci.edu/dataset/45/heart+disease). 

#### Methodology
The following data analysis incorporates the following classification and deep learning models: ogistic Regression, Random Forest,  Support Vector Machine, K-Nearest Neighbors, Gradient Boost, XGBoost, AdaBoost, Decision Tree, Naive Bayes, and MLP Neural Network.

#### II. Results

Data: 

<img width="490" alt="Screen Shot 2024-02-20 at 4 55 09 PM" src="https://github.com/mzacomp/UCB-AI-ML-Capstone-I/assets/146776815/2a9e9078-2d37-4d1c-97d0-e2610db60e89">

Data Correlation: 
<img width="997" alt="Screen Shot 2024-03-18 at 7 02 00 PM" src="https://github.com/mzacomp/UCB-AI-ML-Final-Capstone/assets/146776815/488c1085-ee47-482b-8e1b-e4cdb816f944">

The correlation matrix demonstrates a high correlation between the target heart disease variable between exercise induced agina,systolic depression,and major vessels.

Numerical variable data visualizations: 
![download](https://github.com/mzacomp/UCB-AI-ML-Capstone-I/assets/146776815/bd99411e-6b04-4812-82b5-bcaad79a7dd6)

![download-2](https://github.com/mzacomp/UCB-AI-ML-Capstone-I/assets/146776815/3877d509-9379-44f6-b92c-347e20d38be0)

![download-2](https://github.com/mzacomp/UCB-AI-ML-Capstone-I/assets/146776815/ff998356-dcdc-445f-9347-403fd5e51230)
![download-3](https://github.com/mzacomp/UCB-AI-ML-Capstone-I/assets/146776815/e828febe-12e5-4691-ad8c-63033a15bfe5)

![download-4](https://github.com/mzacomp/UCB-AI-ML-Capstone-I/assets/146776815/2b9d5ab3-7838-4f70-bf9c-816f5b668d8e)

![download-5](https://github.com/mzacomp/UCB-AI-ML-Capstone-I/assets/146776815/4d0788b8-19a3-4f5f-9e9e-4667a1f9ee31)

![download-6](https://github.com/mzacomp/UCB-AI-ML-Capstone-I/assets/146776815/1cfd4fa3-7303-4ac7-8e9f-3e30baa4f46b)

![download-7](https://github.com/mzacomp/UCB-AI-ML-Capstone-I/assets/146776815/9011e417-d68b-4869-a11d-bf5399b0ba05)

Categorical variable data visualizations: 

![download](https://github.com/mzacomp/UCB-AI-ML-Capstone-I/assets/146776815/d93dd181-7601-4d38-849d-f1f3304c97e1)

![download-1](https://github.com/mzacomp/UCB-AI-ML-Capstone-I/assets/146776815/ea03175d-fa88-43f8-94cb-f1109b225c21)
![download-2](https://github.com/mzacomp/UCB-AI-ML-Capstone-I/assets/146776815/d7acc9b8-add9-40e1-893e-bee0ff902acf)

![download-3](https://github.com/mzacomp/UCB-AI-ML-Capstone-I/assets/146776815/70b30fc5-9441-4453-8b2c-44e24c18c063)
![download-4](https://github.com/mzacomp/UCB-AI-ML-Capstone-I/assets/146776815/71a8fd85-042c-44fb-9843-a254fb4f2eaf)

![download-5](https://github.com/mzacomp/UCB-AI-ML-Capstone-I/assets/146776815/945d915e-c88b-4961-b50f-f4571fe79170)

![download-8](https://github.com/mzacomp/UCB-AI-ML-Capstone-I/assets/146776815/d368a962-9319-457b-8518-c2cce9b9c9fc)

![download-8](https://github.com/mzacomp/UCB-AI-ML-Capstone-I/assets/146776815/c5df18ee-09b1-4ca6-841a-759fe7650481)

Target variable visualization: 

![download](https://github.com/mzacomp/UCB-AI-ML-Capstone-I/assets/146776815/246afc68-c8bf-42a6-8489-6dfc5f772bcb)



### Model Results: 


Baseline Model: A baseline model of Logistic Regression, with no hyperparameters or GridSearchCV utilization, was used for comparison. 

<img width="922" alt="Screen Shot 2024-03-19 at 12 19 23 PM" src="https://github.com/mzacomp/UCB-AI-ML-Final-Capstone/assets/146776815/daae2f62-7405-4f66-bf53-70f01af0c82b">

Classification Models: 

<img width="980" alt="Screen Shot 2024-03-19 at 12 21 37 PM" src="https://github.com/mzacomp/UCB-AI-ML-Final-Capstone/assets/146776815/a8976bfb-6d5d-48a2-ba3b-1eb038b6a21a">

Best performing classification models: 
 1. Support Vector Machine. It scored the highest values in test accuracy, precision, recall, and F1-score against the baseline model. 
 2. The second best model the Decision Tree model. It scored higher than the baseline model in test accuracy, test recall, and test F1 score, but not precision.
3. The third best model was the Logistic Regression, which was the baseline model.
4.The fourth best model was the Naive Bayes. This model scored the same test accuracy as Logistic Regression and scored better in test precision, but not in test recall or test F1 score.

Confusion Matrices: 

![cms](https://github.com/mzacomp/UCB-AI-ML-Final-Capstone/assets/146776815/d3bacfb4-7a85-4ca0-842b-52bb50a766b5)

Confusion Matrices demonstrate Logistic Regression, Support Vector Machine, Decision Tree, and Naive Bayes had higher amount of true predictions,including true positives and true negatives. They also have lower amounts of false negatives and positives.


ROC/AUC Curves: 

![roc](https://github.com/mzacomp/UCB-AI-ML-Final-Capstone/assets/146776815/600d1919-fcab-4c89-a416-a54daaeb5f0e)

The better performing ROC curves are  Support Vector Machine and Decision Tree. 


Multi-Layer Perceptron(MLP) Neural Network: 

A multi-layer perceptron netural network was constructed with one input layer, one hidden layer, and one output layer with Keras TensorFlow. 

<img width="938" alt="Screen Shot 2024-03-19 at 12 34 11 PM" src="https://github.com/mzacomp/UCB-AI-ML-Final-Capstone/assets/146776815/af5e703d-4711-4005-b0be-3621d18fa44d">

MLP Construction: 

<img width="971" alt="Screen Shot 2024-03-19 at 12 46 15 PM" src="https://github.com/mzacomp/UCB-AI-ML-Final-Capstone/assets/146776815/c69b75c7-8f77-4814-b28d-ded719e1ddd5">


Test Accuracy: 
<img width="792" alt="Screen Shot 2024-03-19 at 12 35 53 PM" src="https://github.com/mzacomp/UCB-AI-ML-Final-Capstone/assets/146776815/6eb53415-1b6d-4e63-bfa1-436df3c6d84e">

Validation Loss: 

![nn](https://github.com/mzacomp/UCB-AI-ML-Final-Capstone/assets/146776815/5b65d7f0-9d7d-46b9-bfad-b5c057cb7d77)

The test accuracy of the MLP Neural Network is the same as the baseline model. This mean it is on par with Logistic Regression and Naive Bayes. However, it does not perform better than Support Vector Machine or Decision Tree. 

#### III. Conclusion and Next steps

The top 5 performing models for heart disease prediction are:
1. Support Vector Machine
2. Decision Tree
3. Naive Bayes
4. Linear Regression (Baseline Model)
5. MLP Neural Network


The prediction of heart disease at an early stage can prevent grave health events and diseases. The use of an efficient and appropriate algorithm can help physicians in detecting the possible presence of heart disease before it fully manifests. It is clear that both classification models and deep learning models like neural networks can be both very useful and efficient for predicting heart disease. However, the classification models did perform better than the deep learning model, MLP Neural Network, in this exercise.

Next steps include:
1. Testing these models in specific patient settings and to select most useful parameters based on significant research
2. Perform futher research on what specific evaluation metric matters more or a combination of both or many (accuracy,precision, recall, f1 score)
3. Investigate how the volume and scale of a certain population with heart disease would present the need for a certain models or models


Citations and Sources:
1. Arooj, S.; Rehman, S.u.; Imran, A.; Almuhaimeed, A.; Alzahrani, A.K.; Alzahrani, A. A Deep-Learning-Based Approach for the Early Detection of Heart Disease. Biomedicines2022,10,2796. https:// doi.org/10.3390/biomedicines10112796
2. Hossain MI, Maruf MH, Khan MAR, Prity FS, Fatema S, Ejaz MS, Khan MAS. Heart disease prediction using distinct artificial intelligence techniques: performance analysis and comparison. Iran J Comput Sci. 2023 Jun 12:1–21. doi: 10.1007/s42044-023-00148-7. Epub ahead of print. PMCID: PMC10258084
