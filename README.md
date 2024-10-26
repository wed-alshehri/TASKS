# All Tasks

**Naive Bayes Classifier:**

**Introduction**

This project analyzes diabetes data using the Naive Bayes algorithm, focusing on characteristics like glucose levels, blood pressure, and BMI to predict diabetes risk. It serves as a tool for individuals to assess their risk and helps healthcare providers identify those needing further testing.

**Dataset Description**

The dataset contains 768 entries, each representing an individual with the following health metrics:
- Pregnancies: Number of pregnancies.
- Glucose: Plasma glucose concentration (mg/dL).
- BloodPressure: Diastolic blood pressure (mm Hg).
- SkinThickness: Triceps skinfold thickness (mm).
- Insulin: Serum insulin concentration (μU/mL).
- BMI: Body Mass Index (kg/m²).
- DiabetesPedigreeFunction: Likelihood of diabetes based on family history.
- Age: Age in years.
- Outcome: Diabetes status (1 for diabetes, 0 for non-diabetes).

**Data Source**

The "Diabetes Dataset" used in this project is available from [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database).

**Data Processing**

1. Data Download: Downloaded the diabetes dataset for analysis.
2. Naive Bayes Model Application: Applied Naive Bayes algorithm for diabetes risk prediction.
3. Results Evaluation: Compared Naive Bayes performance with logistic regression.
4. Logistic Regression Implementation: Implemented logistic regression on the same dataset.
5. Results Comparison: Found that both models achieved an accuracy of 74.46%, indicating similar predictive performance.

**Results**

Both the Naive Bayes and logistic regression models achieved an accuracy of 74.46%, indicating good performance. The comparable accuracy suggests that the dataset is robust for predictions.

**Future Recommendations**

Further exploration of additional algorithms, such as ensemble methods, and investigation into feature engineering and data augmentation could enhance model performance.

------------------------------------------------------------------------------------------------------------------------

**Market Basket:**

**Introduction**

In this project, a Market Basket Analysis algorithm was applied to study customer behavior and analyze data to improve services. The dataset consists of nine files, with five key files selected for analysis: category_name, products, orders, payments, and items. This analysis aims to enhance marketing strategies and improve services that meet customer needs.

**Dataset Description**

The dataset is relatively large and includes the following key files:
- category_name: Names of product categories in English and Brazilian Portuguese.
- products: Details of available products.
- orders: Records of customer orders.
- payments :Information about payment methods.
- items: Details of items purchased within orders.

**Data Source**

The "Brazilian E-Commerce Dataset" used in this project is available from [Kaggle](https://www.kaggle.com/olistbr/brazilianecommerce).

**Data Processing**
  
The process began with loading the selected files and cleaning the data to remove missing values and duplicates. Various analyses were then conducted, including identifying:
- The months with the highest sales.
- The year with the highest sales.
- The top-selling products regardless of the year.

These analyses provide insights into customer behavior and sales trends.

**Results**

The visualizations provided clear and accurate results. Overall, the findings were understandable, although some results were slightly unclear. Nevertheless, the general outcome remains positive.

**Future Recommendations**

1. Utilize Advanced Analytics: Implement machine learning techniques to predict future sales trends, enhancing inventory management and marketing strategies.
2. Regularly Update Data: Establish a routine for updating the dataset to capture current sales trends and customer preferences, ensuring the analysis remains relevant.

------------------------------------------------------------------------------------------------------------------------

**Text Analysis:**

**Introduction**

This project focuses on analyzing Amazon food review data to uncover customer sentiment using various text analysis techniques. The dataset, sourced from Kaggle, offers insights into customer opinions by transforming textual data into structured, numerical features suitable for classification.

**Dataset Description**

The Amazon Fine Food Reviews dataset includes 568,454 entries, capturing details such as review ID, product ID, user ID, username, helpfulness count, rating (1 to 5 scale), timestamp, review summary, and full review text.

**Data Source**

The "Amazon Fine Food Reviews Dataset" used in this project is available from [Kaggle](https://www.kaggle.com/snap/amazon-fine-food-reviews).

**Data Processing**

1. Libraries Used: This analysis utilizes libraries including NumPy, Pandas, Matplotlib, NLTK, and WordCloud.
2. Data Cleaning: Missing values and duplicates were removed, and text data was cleaned using the Natural Language Toolkit (NLTK).
3. Text Encoding and Classification: A Bag of Words model was applied to represent text data numerically, and labels were encoded using LabelEncoder for analysis.

**Results**

The findings highlighted a significant prevalence of positive reviews over neutral and negative ones, indicating high customer satisfaction.

**Future Recommendations**

1. Enhance Positive Engagement: Focus on reinforcing the features that users appreciate the most.
2. Address Negative Feedback: Develop strategies to address areas where users expressed dissatisfaction.
3. Encourage Neutral Feedback: Gather more balanced feedback for a comprehensive view of user sentiment.
4. Monitor Feedback Over Time: Track feedback trends to assess the impact of improvements and changes.
