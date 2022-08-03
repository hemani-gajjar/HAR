## Project Details

#### This Project is done as part of the Course: CSL7460 Mobile and Pervasive Computing
#### Instructor: [Dr. Suchetana Chakraborty](https://sites.google.com/site/suchetana0116)
#### Project Title: Research-Oriented Study of Mobile Sensing and Human Activity Recognition 

## Team Members 

* [Hemani Gajjar (B19CSE031)](https://github.com/hemani-gajjar)
* [Gautam Jain (B19CSE033)](https://github.com/gautamjain9615)

## About

Due to the widespread availability of low-cost wearable devices and portable computing devices, massive amounts of data, such as motion, location, physiological signals, and environmental data, are being captured. **Human activity recognition (HAR)** is a research topic that aims to understand how human behavior develops through the interpretation of attributes derived from data.

## Objectives (As part of the Course Project)

1. Study research publications and articles on applications that employ sensor data to identify a person's specific movements or habits 
2. Study methodologies used to recognize Human Activity from obtained data from sensors like : **Accelerometer** and
**Gyroscope** and classify activities into one of the five activities:
**Sitting, Standing, Walking, Walking Upstairs, Walking Downstairs**
3. Compare and contrast the various strategies mentioned in various papers and find the most reliable method of activity recognition
4. Distinguish between hard-to-distinguish activities like **Sitting** and **Standing** 

## Relevant Documents

* [Human Activity Recognition Part 1.ipynb](https://github.com/Mobile-and-Pervasive-Computing-Projects/course-projects-hemani-gajjar/blob/master/Human_Activity_Recognition_Part_1.ipynb)

* [Human Activity Recognition Part 2.ipynb](https://github.com/Mobile-and-Pervasive-Computing-Projects/course-projects-hemani-gajjar/blob/master/Human_Activity_Recognition_Part_2.ipynb)

* [Project Presentation](https://github.com/Mobile-and-Pervasive-Computing-Projects/course-projects-hemani-gajjar/blob/master/Mobile%20Sensing%20and%20HAR%20-%20Final%20Presentation%2C%205th%20May%202022.pdf)

* [Project Report](https://github.com/Mobile-and-Pervasive-Computing-Projects/course-projects-hemani-gajjar/blob/master/Mobile%20Sensing%20and%20HAR%20-%20Report.pdf)

* [Project Files Repository](https://github.com/Mobile-and-Pervasive-Computing-Projects/course-projects-hemani-gajjar)



## Implementation Steps

#### For: [Human Activity Recognition Part 1.ipynb](https://github.com/Mobile-and-Pervasive-Computing-Projects/course-projects-hemani-gajjar/blob/master/Human_Activity_Recognition_Part_1.ipynb)  

- This colab file includes the implementation of three models namely: **Decision Tree, Random Forest and Logistic Regression classifiers**. In addition, it contains the analysis of the results in terms of **Accuracy** and **Run Time** along with comparing the **Feature Selection Technique** on this dataset - [Dataset Link](https://www.kaggle.com/datasets/uciml/human-activity-recognition-with-smartphones)

1. Data Visualization
2. Pre-processing
3. Feature Extraction
4. Classifier Training & Validation Strategy

#### For: [Human Activity Recognition Part 2.ipynb](https://github.com/Mobile-and-Pervasive-Computing-Projects/course-projects-hemani-gajjar/blob/master/Human_Activity_Recognition_Part_2.ipynb)

- This colab file includes the implementaion of the 2D CNN model with the focus on distinguishing between **Sitting** and **Standing** activites on this dataset - [Dataset Link](https://www.cis.fordham.edu/wisdm/dataset.php)

1. Standardize data
2. Frame Preparation
3. 2D CNN Model

## References

1. [Activity recognition using smartphone sensors](https://ieeexplore.ieee.org/document/6488584)
2. [HAR using smartphone sensors with two-stage continuous hidden Markov models](https://ieeexplore.ieee.org/abstract/document/6975918)
3. [Dataset: Human Activity Recognition with Smartphones](https://www.kaggle.com/datasets/uciml/human-activity-recognition-with-smartphones)
4. [WISDM: WIreless Sensor Data Mining](https://www.cis.fordham.edu/wisdm/dataset.php)


## Technologies Used

* [Scikit-learn](https://scikit-learn.org/)
* [Matplotlib](https://matplotlib.org/)
* [TensorFlow](https://www.tensorflow.org/)
* [Keras](https://keras.io/)