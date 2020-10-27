<img src="https://github.com/yoviny/Deep-learning-Competitions/blob/master/OSIC%20Pulmonary%20Fibrosis%20Progression/thumbnail.png" width="128">

# OSIC Pulmonary Fibrosis Progression (07/07/2020 - 07/10/2020)
**Predict lung function decline**

https://www.kaggle.com/c/osic-pulmonary-fibrosis-progression

Current methods make fibrotic lung diseases difficult to treat, even with access to a chest CT scan. In addition, the wide range of varied prognoses create issues organizing clinical trials. Finally, patients suffer extreme anxiety—in addition to fibrosis-related symptoms—from the disease’s opaque path of progression.

Open Source Imaging Consortium (OSIC) is a not-for-profit, co-operative effort between academia, industry and philanthropy. The group enables rapid advances in the fight against Idiopathic Pulmonary Fibrosis (IPF), fibrosing interstitial lung diseases (ILDs), and other respiratory diseases, including emphysematous conditions. Its mission is to bring together radiologists, clinicians and computational scientists from around the world to improve imaging-based treatments.

In this competition, you’ll predict a patient’s severity of decline in lung function based on a CT scan of their lungs. You’ll determine lung function based on output from a spirometer, which measures the volume of air inhaled and exhaled. The challenge is to use machine learning techniques to make a prediction with the image, metadata, and baseline FVC as input.
[source:https://www.kaggle.com/c/osic-pulmonary-fibrosis-progression/overview/description)

# Evaluation metric
This competition is evaluated on a modified version of the Laplace Log Likelihood. In medical applications, it is useful to evaluate a model's confidence in its decisions. Accordingly, the metric is designed to reflect both the accuracy and certainty of each prediction.

For each true FVC measurement, both an FVC and a confidence measure (standard deviation σ) is predicted

[source:https://www.kaggle.com/c/osic-pulmonary-fibrosis-progression/overview/evaluation]
