**Name:-** Oshank Agrawal

**Company: -** CODETECH IT SOLUTION

**ID: -** CT04DS5719

**Domain:-** DATA SCIENCE

**Duration: -** 1 MONTH FROM 1st AUGUST to 1st SEPTEMBER

**Mentor: -** NEELA SANTOSH KUMAR

# Overview of the Project

**Project: - PREDICTIVE MODELING WITH CLASSIFICATION**

In Machine Learning, imbalanced data refers to a situation in classification problems where the number of observations in each class significantly differs. In such datasets, one class (the majority class) vastly outnumbers the other class (the minority class). This imbalance can lead to biased models that favour the majority class, resulting in poor predictive performance on the minority class, which is often the class of greater interest.

**Objective**

Handling imbalanced data in classification tasks is a challenge that requires careful consideration of data preprocessing, resampling strategies, model choice, and evaluation metrics. Below is the process you can follow while performing classification on imbalanced datasets:

1. Begin by analyzing the distribution of classes within your dataset to understand the extent of the imbalance.
2. Determine the importance of each class in the context of your specific problem.
3. Increase the number of instances in the minority class by replicating them to balance the class distribution.
4. Some algorithms, like tree-based methods, are less sensitive to class imbalance. Consider using these or ensemble methods like Random Forest or Gradient Boosted Trees.
5. Besides accuracy, use metrics that are informative for imbalanced datasets, such as Precision, Recall, F1 Score, or the Area Under the Receiver Operating Characteristic (AUROC) curve.

**Key Activities**

* **Gathering Data: -** Gathering the from the internet.
* **Checking Errors: -** Before analysing the dataset check the data set contain any missing or false values or not? 
* **Data Cleaning: -** Ensuring the dataset is free from inconsistencies and missing values.
* **Data Analysis: -** Creating visulizations to understand age distribution across the diseases and their relationship.
* **Correlation Analysis: -** Identifying correlations between age and disease.

**Technologies Used**

* **Python: -** The primary programming languages for data analysis.
* **Pandas: -** Used for data manipulation and analysis.
* **Matplotlib: -** Employed for creating static, animated, and interactive visualizations.
* **Seaborn: -** Utilized for making statistical graphics that are informatiove and attractive.
* **sklearn.ensemble**
* **RandomForestClassifier**
* **sklearn.preprocessing**
* **LabelEncoder**
* **sklearn.model_selection**
* **train_test_split**
* **sklearn.metrics**
* **classification_report**
* **accuracy_score**

**Key Insights**

The dataset contains 58,592 entries and 41 columns, including the target variable claim_status. It is based on the problem of insurance claim frequency prediction. Here’s a brief overview of some of the features:
* policy_id: Unique identifier for the insurance policy
* subscription_length, vehicle_age, customer_age: Numeric attributes related to the policy, vehicle, and customer
* region_code, segment, model, fuel_type: Categorical attributes representing the region, vehicle segment, model, and fuel type
* max_torque, max_power, engine_type: Specifications of the vehicle’s engine
* airbags, is_esc, is_adjustable_steering: Features related to the vehicle’s safety and convenience
* claim_status: Target variable indicating whether a claim was made (1) or not (0)
The distribution of the claim_status shows a significant imbalance between the classes, with much fewer claims (1) compared to no claims (0). This imbalance will be a challenge to address during the model training phase to ensure our model does not become biased toward predicting the majority class.
The distributions of the numerical features subscription_length, vehicle_age, and customer_age show the following characteristics:

* subscription_length: Most values are clustered around lower numbers, indicating that many policies have shorter subscription lengths.
* vehicle_age: This distribution is somewhat uniform but with spikes at specific ages, possibly representing common vehicle age intervals in the dataset.
* customer_age: This shows a fairly normal distribution, with the majority of customers falling within a middle-age range.

The classification report above provides various metrics to evaluate the performance of the predictive model on the test data. Here’s an interpretation of the results:
1. For class 0 (no claim), precision is 1.00, meaning that when the model predicts no claim, it is correct 100% of the time. For class 1 (claim), precision is 0.98, indicating that when the model predicts a claim, it is correct 98% of the time.
2. For class 0, recall is 0.98, signifying that the model correctly identifies 98% of all actual no-claim instances. For class 1, recall is 1.00, showing that the model correctly identifies 100% of all actual claim instances.
3. The F1-score for both classes is 0.99, indicating a high balance between precision and recall. It means the model is both accurate and reliable in its predictions across both classes.
4. The overall accuracy of the model is 99%, which means that it correctly predicts the claim status for 99% of the cases in the test dataset.
5. The macro average for precision, recall and F1-score is 0.99, reflecting the average performance of the model across both classes without considering the imbalance in class distribution. This high value suggests that the model performs well across both classes. The weighted average for precision, recall, and F1-score is also 0.99, taking into account the imbalance in class distribution. It indicates that, on average, the model performs consistently well across the different classes when considering their distribution in the dataset.

These results indicate a highly effective model for predicting insurance claims, with strong performance metrics across both classes of outcomes. The high recall for claims (class 1) is particularly notable as it implies that the model is very effective at identifying the instances where claims occur, which is often the primary concern in imbalanced datasets.

**Observation**

This is how to handle class imbalance and perform classification on imbalanced data. Imbalanced data refers to a situation in classification problems where the number of observations in each class significantly differs. In such datasets, one class (the majority class) vastly outnumbers the other class (the minority class). This imbalance can lead to biased models that favour the majority class, resulting in poor predictive performance on the minority class, which is often the class of greater interest.

