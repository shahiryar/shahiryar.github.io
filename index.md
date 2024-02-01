# Portfolio

---

## Applications

## [Image Reconstruction form AutoEncoder](https://colab.research.google.com/drive/12NJUTSnH3ESkRPyOOH6JMGbsa5D8pK4M?usp=sharing)
<br/>
An application of autoencoders includes image denoising. I have used the persons dataset which is a subset of the COCO dataset. I have used the images present in the dataset and generated labels by adding salt and pepper noise to the image. The input to the model will be the noisy image created through using functions from opencv library and the output is the original image. In the process, the model learns to denoise the images. Thus, through a synthetic dataset, I have created an image denoiser.
<br/><br/>
<span style="background-color: #ba9ff5; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">AutoEncoder</span>
<span style="background-color: #eb8a8a; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Image Processing</span>
<span style="background-color: #f59faf; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Computer Vision</span>
<span style="background-color: #bb8aeb; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Keras</span>
<span style="background-color: #8abceb; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Deep Learning</span>
<br/><br/>
<div style="display: flex;">
    <img src="images/denoising.png" alt="The scene of a 2019 political violence in Nigeria, a crowd protesting in the backdrop of fire and smoke" style="margin-right: 10px; width: 45%;"/>
</div>

## [Spam SMS Text Classification](https://colab.research.google.com/github/shahiryar/spam-classification/blob/main/Spam_SMS_Classification.ipynb)
<br/>
Uses deep learning to detect spam messages. A Bi-Directional Encoder Representation from Transformers (BERT) as a feature extraction backbone is used to predict if the text of a given SMS is likely to be a Spam message.
<br/><br/>
<span style="background-color: #ba9ff5; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">BERT</span>
<span style="background-color: #eb8a8a; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Data Cleaning</span>
<span style="background-color: #f59faf; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Text Classification</span>
<span style="background-color: #bb8aeb; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Keras</span>
<span style="background-color: #8abceb; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Deep Learning</span>
<br/><br/>
<div style="display: flex;">
    <img src="images/Spam detection evals.png" alt="The scene of a 2019 political violence in Nigeria, a crowd protesting in the backdrop of fire and smoke" style="margin-right: 10px; width: 45%;"/>
</div>

## [Modeling Political Conflicts](/project_conflict_modeling.md)
<br/>
The objective of this project is to develop a predictive model to determine the likelihood of conflicts, civil unrest, or political violence in a country. By analyzing historical data and various socio-economic, political, and demographic factors, the model aims to provide early warning indicators and insights that can help policymakers and organizations proactively address potential conflicts.
<br/><br/>
<span style="background-color: #f59faf; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Support Vector Machine (SVM)</span>
<span style="background-color: #8abceb; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Deep Learning</span>
<span style="background-color: #f59faf; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Random Forest Classifier</span>
<span style="background-color: #eb8a8a; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Data Cleaning</span>
<span style="background-color: #8aebe1; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Feature Engineering</span>
<span style="background-color: #ba9ff5; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Scikit Learn</span>
<span style="background-color: #eb8ad0; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Tensorflow</span>
<span style="background-color: #bb8aeb; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Keras</span>
<br/><br/>
<div style="display: flex;">
    <img src="images/cover_conflcit_modeling_POLITICAL-VIOLENCE.jpeg" alt="The scene of a 2019 political violence in Nigeria, a crowd protesting in the backdrop of fire and smoke" style="margin-right: 10px; width: 45%;"/>
    <img src="images/Confusion_matrix_random_forest_clasif_conflict_modeling.png" style="margin-right: 10px; width: 45%;"/>
</div>

---
### [Semantic Search and Keyword Knowledge Graph](/knowledge-graph)
<br/>
Shows underlying correlation patterns between various research fields and researchers in major Universities of Japan in the form a graph networks. The projects deal with multi lingual data including English and Japanese. It was built on top of pretrained BERT model from HuggingFace and Facebook’s FIASS indexing.
<br/><br/>
<span style="background-color: #9ff5e5; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">BERT</span>
<span style="background-color: #cfeb8a; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">NLP</span>
<span style="background-color: #ba9ff5; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Graph Network</span>
<span style="background-color: #daf59f; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Indexing</span>
<span style="background-color: #f59faf; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Indexing Big Data</span>
<span style="background-color: #8abceb; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">FIASS Indexing</span>
<span style="background-color: #8aebe1; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Correlation</span>
<br/><br/>
<img src="images/knowledge-graph.png"/>

---
### [Geo-Spatial Analysis of Earthquakes in Turkey](https://www.kaggle.com/code/shahiryarsaleem/turkey-earthquakes-analysis)
<br/>
Looks at the historic earthquake data, uses geospatial analysis to theorise the origin of earthquakes,  and recommends most vulnerable  districts in Turkey.
<br/><br/>
<span style="background-color: #eb8a8a; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Data Analysis</span>
<span style="background-color: #ebac8a; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Geo-spatial Analysis</span>
<span style="background-color: #bb8aeb; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Visualisation</span>
<br/><br/>
<img src="images/turkey-earthquake-geospatial.png"/>

---

## Algorithm Implementations

### [Upper Confidence Bound Implementation Fom Scratch](https://colab.research.google.com/drive/1xlZhZ6AvMTTfXFCe2WrHD2jdo6kSHbWY#scrollTo=u-u1-vwMXQWa)
<br/>
Based on the assumption that given a set of possible options each option has an underlying normal distribution, Upper Confidence Bound Strategy is coded from scratch to choose the optimal option without knowing those distribution, with minimal exploration, and maximum exploitation. This algorithm is useful in a wide variety of problems such as marketing, drug efficacy, and recommender systems.
<br/><br/>
<span style="background-color: #eb8ad0; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Reinforcement Learning</span>
<span style="background-color: #ebe78a; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Upper Bound Confidence</span>
<span style="background-color: #8abceb; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Recommender System</span>
<span style="background-color: #f59faf; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Machine Learning Algorithm</span>
<br/><br/>
<img src="images/upper-bound-confidence.png"/>

---
### [Naive Bayes Implementation From Scratch](https://github.com/shahiryar/Naive-Bayes/blob/master/README.rst)
<br/>
From scratch implementation of Naive Bayes Classification Algorithm. Classifies a given set of datapoints into a certain number of classes.
<br/><br/>
<span style="background-color: #9ff5e5; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Classification</span>
<span style="background-color: #f59faf; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Machine Learning Algorithm</span>
<br/><br/>
<img src="images/naive-bayes-classification.png">

---
### [Logistic Regression From Scratch](https://github.com/shahiryar/Logistic-Regression/blob/main/README.md)
<br/>
From scratch implementation of Logistic Regression Classification Algorithm. Also, includes built it visualisation and validation functions.
<br/><br/>
<span style="background-color: #9ff5e5; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Classification</span>
<span style="background-color: #f59faf; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Machine Learning Algorithm</span>
<span style="background-color: #ba9ff5; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Linear Model</span>
<span style="background-color: #eb8a8a; color: #ffffff; padding: 0.5px 7px; border-radius: 5px;">Regression</span>
<br/><br/>
<img src="images/logistic-regression-classification.png"/>

---
