# **DEVELOPING A PREDICTIVE MODEL FOR EARLY DETECTION OF MENTAL HEALTH CONDITIONS** 

**Authors:**

Elvis Wanjohi (Team Leader)

Jessica Gichimu

Jesse Ngugi

Stephen Gachingu

Latifa Riziki

## 1. Business Understanding

### 1.1 Business Overview
Given the fast-moving pace of economic and technological advancement in today’s world, most people, especially from the younger generation, tend to experience some form of mental health issues in their lifetime. There has been a significant increase in individuals experiencing suicidal ideation. While it may appear that such individuals do not explicitly communicate their distress, a closer examination of their online activity, such as social media posts, comments, and engagement patterns, often reveals underlying emotional states indicative of psychological distress. This could help researchers, students, and practitioners to develop early detection models for mental health support. The goal is to encourage data-driven approaches to mental health awareness, prevention, and support systems. Mental health awareness is primarily in the healthcare and psychology domains, focusing on the assessment, diagnosis, and treatment of mental health conditions. 

The target audience for this NLP model are health care professionals (such as therapists, psychologists, psychiatrists), and mental health organizations and clinics, where they can prioritize high-risk cases, or monitor trends in mental health conditions across populations. This model could be used to identify early symptoms of the mental health of individuals in our society. We were able to find a brief description of mental health in the Practical Natural Language Processing( A Comprehensive Guide to Building Real-World NLP Systems) book, which gave us the idea of tackling this project. The motivation for the project is try and improve the diagnosis  and treatment of mental health by identifying underlying conditions at an early stage.
### 1.2 The Problem
Mental health professionals often rely on personal expertise and manual assessment to diagnose patients—an approach that is time-intensive and difficult to scale. In many cases, warning signs are missed or detected late, especially when individuals express themselves informally online.

This project proposes an NLP-based predictive model that analyzes text statements and classifies potential mental-health conditions. By integrating automated linguistic analysis with professional oversight, the model can complement human judgment, enabling faster, broader screening. The tool is also designed for public awareness and self-assessment purposes, with a clear ethical guideline that professional consultation must accompany any automated insights.

### 1.3 Project Objectives
#### 1.3.1 Main Objective
The main objective is to develop a machine learning model that can accurately classify mental health conditions based on textual statements expressed by individuals.

#### 1.3.2 Specific Objectives
The specific objectives of the project are:
 
1. Translate all text data into Swahili to localize the dataset and improve inclusivity.

2. Identify the most common mental health condition.

3. Preprocess the data through processes such as Vectorization and tokenization, handling missing values, and creating new features such as characters, words and sentences.

4. Use exploratory tools such as word clouds to visualize commonly terms associated with specific mental health categories.

5. Analyze text length to classify a mental health condition or show correlation  with a mental health condition. 

6. Evaluate model performance using metrics such as Precision, Recall, F1score, Accuracy Score and ROC-AUC.

7. Compare different classification models to determine which performs best for this dataset.

8. Scrapping data from an online platform like twitter to show the efficiency of the model.

9. Create a translate feature to allow English–Swahili switching for interpretability and diversity in the model.


#### 1.3.3 Research Questions
1. Can the dataset be effectively translated and localized to Swahili?

2. Which is the most common health condition?

3. Which features influence mental health condition?

4. Which words are specific to each mental health category?

5. Which classifier model achieves the best Precision, Recall, F1 score, Accuracy and ROC-AUC?

6. Which classification model performs best for this dataset?

7. How efficiently can the model classify conditions when applied to Twitter data?

8. How can we ensure diversity, fairness and interpretability in the multilingual model?


### 1.4 Success Criteria
The success of this project will be assessed in the following ways:

1. The analysis should generate actionable insights into the most common mental health conditions to inform better prevention and support strategies.

2. A machine learning model should successfully classify text into relevant mental health categories with high performance metrics.

3. The final system should maintain interpretability, cultural sensitivity and ethical integrity when applied to both English and Swahili datasets.

## 2. Data Understanding
This section uses the English  mental health text dataset to build a condition classification model.The model also used The dataset contains user statements translated from English to Swahili, serving as the foundation for downstream Natural Language Processing (NLP) modeling in an African context.

The aim is to understand the dataset’s structure and content. This includes reviewing the available features, verifying data types and identifying potential quality issues such as missing values, duplicates or inconsistencies.

By exploring the data at this stage, it is possible to detect quality concerns and inform decisions for text cleaning, data preprocessing and subsequent model development.

## 3. Data Preparation

## 4. Exploratory Data Analysis

## 5. Modeling and Evaluation


## 6. Deployment


## 7. Technologies Used

- **Python**: Primary programming language

- **Pandas**: Data manipulation and analysis

- **Sklearn**: For modelling purposes

- **Matplotlib**: Data visualization

- **Jupyter Notebook**: Development environment

- **Git**: Commit and push to the remote repository

- **NLTK**: For Natural Language Processing

- **Plotly**: To create interactive visualizations

- **Joblib and Pickle**: To save the trained model.

## 8. Conclusion

## 9. Support
For questions or support, please contact:

1. jessengugi99@gmail.com

2. jessica.gichimu@gmail.com

3. stephenmunene092@gmail.com

4. leeelvis562@gmail.com

5. latifariziki5@gmail.com

