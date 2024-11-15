<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<div class="header">
  <h1>Child Mind Institute — Problematic Internet Use Prediction</h1>
  <p>Predicting Severity Impairment Index (SII) from Physical Activity and Internet Usage Data</p>
</div>

<div class="section">
  <h2>Competition Overview</h2>
  <p>This project is based on the <a href="https://www.childmind.org/">Child Mind Institute</a> competition focusing on predicting the Severity Impairment Index (SII) related to Problematic Internet Use. The dataset, part of the Healthy Brain Network (HBN) study, combines physical activity data with internet usage behavior, aiming to identify biological markers for improving diagnosis and treatment of mental health and learning disorders.</p>
</div>

<div class="section">
  <h2>Dataset Highlights</h2>
  <ul>
    <li><strong>Participants:</strong> Approximately 5,000 individuals aged 5-22.</li>
    <li><strong>Data Sources:**
      <ul>
        <li>Physical activity (wrist-worn accelerometer data, fitness assessments, questionnaires)</li>
        <li>Internet usage behavior data</li>
      </ul>
    </li>
    <li><strong>Target Variable:** Severity Impairment Index (SII) for Problematic Internet Use</li>
    <li><strong>Instrument Measurements:** Detailed in <code>data_dictionary.csv</code>, including demographics, internet use, physical measures, and more.</li>
  </ul>
</div>

<div class="section">
  <h2>Models and Techniques Employed</h2>
  <ul>
    <li>LightGBM (LGBMRegressor)</li>
    <li>Keras Neural Network Model</li>
    <li>PyTorch TabNetRegressor</li>
    <li>GridSearchCV for Hyperparameter Tuning</li>
    <li>SimpleImputer and KNNImputer for Missing Value Handling</li>
    <li>StandardScaler for Feature Scaling</li>
  </ul>
</div>

<div class="section">
  <h2>Getting Started</h2>
  <ol>
    <li>Clone the repository: <code>git clone https://github.com/shrish01/CMI-ProblematicInternetUse.git</code></li>
    <li>Install required libraries: Check <code>requirements.txt</code> for details.</li>
    <li>Explore the dataset and models in the respective folders.</li>
    <li>Contribute by submitting a pull request with your improvements or new models.</li>
  </ol>
</div>

<div class="section">
  <h2>Contribution Guidelines</h2>
  <p>To contribute, please ensure you:</p>
  <ul>
    <li>Fork the repository.</li>
    <li>Create a new branch for your changes.</li>
    <li>Submit a pull request with a detailed description of changes.</li>
  </ul>
</div>


  
