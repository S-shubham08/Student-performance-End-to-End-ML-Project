## Students' Performance in Exams End to End Machine Learning Project

### Application Demo page:
![image](https://github.com/S-shubham08/Student-performance-End-to-End-ML-Project/assets/127888794/c034ecf6-fb9d-440e-badd-01930cd6b467)


#### Life cycle of Machine Learning Project

- Understanding the Problem Statement
- Data Collection
- Data Checks to perform
- Exploratory data analysis
- Data Pre-Processing
- Model Training
- Choose best model

### Project Description
This project aims to predict student's performance (test scores) is affected by other variables such as Gender, Ethnicity, Parental level of education, Lunch and Test preparation course. It provides an end-to-end solution that includes data preprocessing, model training, and a Flask web application for making predictions.

### Data Collection
- Dataset Source - https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977
- The data consists of 8 column and 1000 rows.

### Dataset Information
- gender : sex of students  -> (Male/female)
- race/ethnicity : ethnicity of students -> (Group A, B,C, D,E)
- parental level of education : parents' final education ->(bachelor's degree,some college,master's degree,associate's degree,high school)
- lunch : having lunch before test (standard or free/reduced) 
- test preparation course : complete or not complete before test
- math score
- reading score
- writing score

### Project Structure
- /artifacts: Contains the dataset and data preprocessing and trained machine learning model.
- /src/components: Include all the components like data_ingestion, data_transformation and modal_trainer.
- /src/pipeline: Predice pipeline steps added
- app.py: Includes the Flask web application and API.
- utils.py: Include all the common function used in project.
- requirements.txt: List of dependencies required to run the project.

### Install the required packages:
  - pip install -r requirements.txt

### Usage
1. Run the Flask application:
  - python app.py  
2. Open your web browser and go to (http://127.0.0.1:5000/predictdata) to access the web application.
3. Enter the necessary student information, and the application will display the predicted performance.

  
