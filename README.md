# SC1015-mini-project-G6
Data Analysis of Flight Departure Delay

## Dataset
https://www.kaggle.com/datasets/patrickzel/flight-delay-and-cancellation-dataset-2019-2023?select=flights_sample_3m.csv


Source data related to flight delays and cancellations for January 2019 – August 2023 retrieved from DOT On-Time : Reporting Carrier On-Time Performance (1987-present)

Variables include flight routes (origin, destination), time ranges for events (minutes, local time), delay and cancellation reasons/attributions (limited).


## Project Details

### Problem Definition
- How do various factors affect the status of a flight (On-time, delay, Cancelled)

### Contributors
 - Sai Harsha Venugopal - Presentation and Slides
 - Mustafa Poonawala - Data Cleaning & Analysis
 - Sun Yifei - Analysis with Models & Conclusion

### Overview
The project starts with data cleaning, which includes categorizing columns, removing unnecessary data and checking the completeness of the dataset. The exploratory data analysis section investigates airlines, types of delays, and flights categorized by time and location.

The project also includes building a predictive model using machine learning, with the aim of improving accuracy by adding more features to the model. The machine learning section covers training, baseline models, and polynomial features.

The endeavor begins with data preparation, entailing the classification of columns, elimination of extraneous information, and verification of the dataset. The exploratory data analysis phase delves into airlines, delay categories, and flight categorization based on time and location

Furthermore, the project encompasses the construction of a predictive model leveraging machine learning techniques, with the objective of enhancing accuracy through the incorporation of additional features. The machine learning segment encompasses training processes, baseline models, and the utilization of polynomial features.



### Conclusions
- The incorporation of additional features yielded more precise test results, underscoring the importance of comprehensive data in enhancing model accuracy.

- Despite the modifications implemented, the final accuracy remained relatively low, indicating room for further improvements.

- The introduction of polynomial features did not contribute to a significant enhancement in test accuracy, suggesting the need for alternative feature engineering approaches.

- To attain higher accuracy levels, the exploration and implementation of other machine learning models could have been beneficial.

- Augmenting the dataset with complementary features from external sources, such as flight duration and the number of on-board passengers, presents an opportunity for model refinement.

- Furthermore, the development of a dedicated model to predict flight delay durations could have enriched the project's scope and utility.


The journey has imparted valuable insights and skills, including:

- Exploration of diverse visualization techniques, such as plotly, to effectively communicate exploratory data analysis (EDA) findings.

- Proficiency in training and evaluating machine learning models using the powerful scikit-learn library, encompassing techniques like:
    - DecisionTreeClassifier
    - ExtraTreeClassifier
    - BernoulliNB
    - BaggingClassifier
    - RandomForestClassifier
    - GradientBoosterClassifier

- Mastery of polynomial features, a crucial concept in enhancing model performance.

- Comprehensive understanding of evaluation metrics, including Precision, Recall, and F1 Score, enabling effective model assessment.

- Practical application of Git for version control and collaborative coding, facilitating seamless teamwork on a shared codebase.
