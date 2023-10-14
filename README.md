# Portfolio_Akshay_Kamoji
Porfolio that showcases my technical abilities in Data Science and analytics

# Project 1: Predicting Customer Churn with XGBoost and SMOTE

In this project, I leveraged the power of XGBoost, a robust gradient boosting algorithm, to develop a machine learning model for predicting customer churn. The objective was to proactively identify customers who might churn, enabling targeted retention strategies.



- **Machine Learning Model:**
  - Implemented and fine-tuned an XGBoost model, known for its effectiveness in handling complex relationships within data.

- **Addressing Class Imbalance:**
  - Recognizing the challenge posed by imbalanced data, I employed the Synthetic Minority Over-sampling Technique (SMOTE). SMOTE helped balance the class distribution, preventing the model from being biased toward the majority class.
    ![Class Imbalance](./imbal.PNG "example1")

- **Feature Engineering:**
  - Explored and engineered relevant features to enhance the predictive capabilities of the model. Considered factors such as customer behavior, transaction history, and engagement metrics.

- **Model Evaluation and Interpretation:**
  - Rigorously evaluated the model using industry-standard metrics and techniques. Additionally, delved into model interpretation to understand the factors contributing to predictions.
    
  - Confusion matrices for train and test data
  
    ![Train accuracy before applying SMOTE](./train_conf_xg.PNG)
    
    ![Test accuracy before applying SMOTE](./test_cong_xg.PNG)
 
    <br><br> <!-- Adding line breaks for spacing -->
 
    ![Train accuracy after applying SMOTE](./train_conf_xg_smote.PNG)
    
    ![Test accuracy after applying SMOTE](./test_conf_xg_smote.PNG)

- **Scalability and Deployment Considerations:**
  - Discussed considerations for scalability and potential deployment strategies, ensuring the model's practicality in real-world scenarios.

This project not only showcases my proficiency in machine learning and predictive modeling but also underscores my commitment to addressing real-world challenges, such as class imbalance, to deliver robust and actionable solutions.

# Project 2: Spam Classifier using Dense Neural Networks and Word Embeddings (Word2Vec)

For this project, I developed a sophisticated spam classifier using deep learning techniques, specifically Dense Neural Networks, and harnessed the power of word embeddings generated with Word2Vec.

## Key Features:

- **Dataset and Cleaning:**
  - Utilized the spam classifier dataset from Kaggle as the foundation for the project.
  - Employed Spacy for data cleaning, removing stop words and punctuation to enhance the quality of the text data.

- **Word Embeddings with Word2Vec:**
  - Leveraged Gensim to convert text into embedding vectors. The vectors were obtained through training on the cleaned dataset. The following hyperparametrs where used to get the vectors - vector size =20, window size =7, sg=1(skipgram)
  
  - Implemented the skip-gram model to capture better contextual understanding and representation of words.

- **Dense Neural Network Model:**
  - Constructed a deep learning model based on Dense Neural Networks, utilizing the word embeddings as input features.
  - Explored different architectures, layer configurations, and activation functions to optimize the model's performance.

  **Training and Evaluation:**
  - Trained the model on the spam classifier dataset, carefully validating its performance to ensure robustness.
  - Employed metrics such as precision, recall, and F1 score for a comprehensive evaluation of the model's effectiveness.
    
  - ROC plots obtained:

    ![Train accuracy before applying SMOTE](./ROC_train_title.PNG)
 
    <br><br> <!-- Adding line breaks for spacing -->
    
    ![Train accuracy before applying SMOTE](./ROC_test_title.PNG)

    <br><br> <!-- Adding line breaks for spacing -->
    
  - Confusion matrices for train and test data:

    ![Train accuracy before applying SMOTE](./conf_embed_traon.PNG)

    ![Train accuracy before applying SMOTE](./conf_embed_test.PNG)

- **Application to Real-world Problem:**
  - Addressed the practical challenge of spam detection, contributing to the ongoing efforts to enhance email security and user experience.

- **Model Interpretation:**
  - Delved into the interpretability of the model, analyzing important features and gaining insights into its decision-making process.

This project not only showcases my proficiency in implementing deep learning models for natural language processing tasks but also demonstrates my commitment to addressing real-world challenges such as spam detection through advanced techniques like Word2Vec and Dense Neural Networks.


# Project 3: Visualizing COVID-19 Vaccination Patterns in the US using Tableau

In this project, I utilized Tableau to create insightful visualizations of COVID-19 vaccination patterns in the United States. Leveraging data from the CDC website, I aimed to provide a comprehensive understanding of vaccination trends based on diverse criteria, including state-wise distribution and vaccination progress over time.

## Key Achievements:

- **Data Collection and Preprocessing:**
  - Collected COVID-19 vaccination data from the CDC website, ensuring data accuracy and completeness.
  - Preprocessed the data in R, utilizing time series imputation methods to handle missing values. This step was crucial for maintaining the integrity of the visualizations.

- **Tableau Visualizations:**
  - Developed a series of interactive dashboards using Tableau to showcase vaccination patterns. These dashboards enable users to explore the data dynamically, gaining insights into state-level variations and temporal trends.
 

- **Exploratory Data Analysis:**
  - Conducted exploratory data analysis within Tableau, uncovering key patterns and correlations. This involved analyzing vaccination rates, identifying hotspots, and assessing the impact of vaccination campaigns.
 
    - Understanding the corrleation between vaccine hesitancy and political influence

      ![Train accuracy before applying SMOTE](./DoH_top_10.PNG)

      <br><br> <!-- Adding line breaks for spacing -->

    - Vaccination status by different status as of December 2021

      ![Train accuracy before applying SMOTE](./tableau1.PNG)
      

- **Effect Exploration:**
  - Explored the effects of various factors, including political influences, weather conditions, time, and state-specific dynamics, on vaccination patterns.

- **Storytelling through Data Visualization:**
  - Crafted a compelling narrative by arranging visualizations into a cohesive story. This approach enhances the communicative power of the project, making complex vaccination data more accessible to a broad audience.

- **User Interaction Features:**
  - Implemented features for user interaction within Tableau, allowing viewers to filter and drill down into specific aspects of the data. This enhances the overall user experience and facilitates deeper exploration.

This project not only demonstrates my proficiency in data visualization but also showcases my ability to extract meaningful insights from complex datasets, contributing to a better understanding of COVID-19 vaccination trends in the US.


# Project 4: Understanding the Impact of Shall Carry Laws on Crime Rates using Time Series Fixed Effects Model

In this project, I conducted a comprehensive investigation into the relationship between Shall Carry Laws in the United States and crime rates. Leveraging data from [Princeton University's Stock-Watson Empirical Exercises datasets](https://www.princeton.edu/~mwatson/Stock-Watson_3u/Students/Stock-Watson-EmpiricalExercises-DataSets.htm), I applied a time series fixed effects model to unravel patterns and discern the impact of various factors on crime rates.

## Key Components:

- **Exploratory Data Analysis (EDA) in Stata:**
  - Initiated the project with a meticulous EDA in Stata to gain insights into trends and patterns in the data.
  - Explored statistical summaries, visualizations, and correlations to inform subsequent steps.

    ![Train accuracy before applying SMOTE](./stata1_re.PNG)

    <br><br> <!-- Adding line breaks for spacing -->

    ![Train accuracy before applying SMOTE](./stata2_re.PNG)

- **Data Preprocessing:**
  - Addressed issues related to data distribution and multicollinearity through preprocessing techniques.
  - Ensured the quality and reliability of the data before proceeding with model development.

- **Fixed Effects Model Construction:**
  - Developed a robust time series fixed effects model to investigate the relationship between Shall Carry Laws, crime rates, and a range of influential factors.
  - Considered variables such as city population, average salary, incarceration rate, population density, among others, to capture the complexity of the relationships.

- **Model Evaluation and Interpretation:**
  - Rigorously evaluated the model using appropriate statistical metrics, ensuring its accuracy and reliability.
  - Interpreted the results to draw meaningful conclusions about the impact of Shall Carry Laws on crime rates and the nuanced interplay with other contributing factors.

- **Policy Implications and Real-world Context:**
  - Considered the broader policy implications of the findings, contributing valuable insights to the discourse on public safety and firearm regulations.

This project not only demonstrates my proficiency in empirical analysis using Stata and constructing sophisticated time series fixed effects models but also showcases my ability to tackle complex socio-economic questions through data-driven approaches.


