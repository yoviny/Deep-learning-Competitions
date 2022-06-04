<img src="https://github.com/yoviny/Deep-learning-Competitions/blob/master/Prostate%20cANcer%20graDe%20Assessment%20Challenge/thumbnail.png" width="128">

# TensorFlow - Help Protect the Great Barrier Reef (22/11/2021 - 14/02/2022)
**Detect crown-of-thorns starfish in underwater image data**

**Leaderboard ranking - 279/2025 (top 14%)**

https://www.kaggle.com/competitions/tensorflow-great-barrier-reef

The goal of this competition is to accurately identify starfish in real-time by building an object detection model trained on underwater videos of coral reefs.

Your work will help researchers identify species that are threatening Australia's Great Barrier Reef and take well-informed action to protect the reef for future generations.

![image](https://github.com/yoviny/Deep-learning-Competitions/blob/master/Prostate%20cANcer%20graDe%20Assessment%20Challenge/panda-image.png)

Figure 1: An illustration of the Gleason grading process for an example biopsy containing prostate cancer. The most common (blue outline, Gleason pattern 3) and second most common (red outline, Gleason pattern 4) cancer growth patterns present in the biopsy dictate the Gleason score (3+4 for this biopsy), which in turn is converted into an ISUP grade (2 for this biopsy) following guidelines of the International Society of Urological Pathology. Biopsies not containing cancer are represented by an ISUP grade of 0 in this challenge.

Radboud University Medical Center and Karolinska Institute have teamed up to organize this competition in collaboration with colleagues from Tampere University. The Computational Pathology Group (CPG) of the Radboud University Medical Center is a research group that develops computer algorithms to aid clinicians. Karolinska Institute’s Department of Medical Epidemiology and Biostatistics (MEB) includes an interdisciplinary research group to improve the diagnostics and treatment of prostate cancer. Together, they hope to further their existing research to make a significant impact on the healthcare of prostate cancer patients.

Challenge organizer team: Wouter Bulten, Geert Litjens, Hans Pinckaers, Peter Ström, Martin Eklund, Lars Egevad, Henrik Grönberg, Kimmo Kartasalo, Pekka Ruusuvuori, Tomi Häkkinen, Sohier Dane, Maggie Demkin.

[source:https://www.kaggle.com/competitions/tensorflow-great-barrier-reef/overview/description)

# Evaluation metric
Submissions are scored based on the the F2 Score at different intersection over union (IoU) thresholds. The F2 metric weights recall more heavily than precision, as in this case it makes sense to tolerate some false positives in order to ensure very few starfish are missed.

The metric sweeps over IoU thresholds in the range of 0.3 to 0.8 with a step size of 0.05, calculating an F2 score at each threshold. For example, at a threshold of 0.5, a predicted object is considered a "hit" if its IoU with a ground truth object is at least 0.5.
[source:https://www.kaggle.com/competitions/tensorflow-great-barrier-reef/overview/evaluation]
