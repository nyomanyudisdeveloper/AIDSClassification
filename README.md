# Project Name

The project name is AIDS Classification. This is project to fulfill my assignment project at Hactiv8 and part of my personal portofolio in Data Science. My other personal project can be found at the [Nyoman Yudis Developer](https://github.com/nyomanyudisdeveloper)

#### -- Project Status: On-Hold

## Project Intro/Objective

The purpose of this project is to make predict who patient will have chance to get affected by AIDS based on their personal information, behaviour, and treatment. This will make benefit to save people life as many as possible because there are no cure for AIDS and it will sure leading to death. For that i use SVM as part of supervised learning and got recall score 0.73.

### Methods Used

- Exploratory Data Analysis (EDA)
- Feature Engineer
- Data Balancing
- Cross Validation
- Supervised Learning
- HyperParameter Tuning

### Technologies

- Python
- Pandas
- Matplotlib
- Sklearn
- Imblearn
- Streamlit

## Project Description

The dataset i use to create this model is from [here](https://www.kaggle.com/datasets/aadarshvelu/aids-virus-infection-prediction) where contain file csv 5000 total data and 50000 total data. These two file contain column that have information about patient HIV personal information, behaviour, and treatment.
After do exploratory data analysis (EDA) i found that:

- This dataset has inbalance label which is give bad impact on process model training
- The most effective treatment before AIDS is ZDV + ddl
- People who has HIV is around 25 - 45 years old. Dominant who has experience homosexual activity or white race. Has benchmark cd40 for get AIDS around 180 - 300 and cd80 around 800 - 1200.

And to solve the problem i make model to clasify patient who have chance get affected by AIDS by using method supervised learning. To determine which model algorithm classify supervised learning i use, i used cross validation with these 4 model algorithm "KNNeigbordClassifier", "RandomForestClassifier", "Decision Tree", and "SVM" with metrics recall score. The result is SVM is the best model algorithm for this case. And after do hyperparameter tuning with SVM i got final recall score with 0.73.

The blocker i found when do this project is because limited time i can't do more variant of hyperparameter tuning. And then i can try to less my correlation for process feature selection to increase feature that i can use to make model classification. And because i use file csv with total 50.000 instead 5.000 it take more time to do model training.

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept in file AIDS_Classification_50000.csv
3. For process Feature Engineer, Exploratory Data Analysis (EDA), Data Balancing, Cross Validation, Model Training, Model Evaluation, Model Improvement, and Model Inference are being kept in file P1M2_yudis_aditya.ipynb.
4. Streamlit for deployment to hunggigface script are being kept in folder deployment

## Featured Notebooks/Analysis/Deliverables

- [Hungging Face for model usage demonstration](https://huggingface.co/spaces/nyomanyudisdeveloper/AIDS_Classification_EDA)
- [Link Dataset](https://www.kaggle.com/datasets/aadarshvelu/aids-virus-infection-prediction)

## Contact

- If you have any question or want to contribute with this project, feel free to ask me in [linkedin](https://www.linkedin.com/in/yudit-a-9941ab318/) or my partners.
