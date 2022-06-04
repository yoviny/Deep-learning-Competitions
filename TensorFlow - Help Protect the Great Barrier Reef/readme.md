<img src="https://github.com/yoviny/Deep-learning-Competitions/blob/master/Prostate%20cANcer%20graDe%20Assessment%20Challenge/thumbnail.png" width="128">

# TensorFlow - Help Protect the Great Barrier Reef (22/11/2021 - 14/02/2022)
**Detect crown-of-thorns starfish in underwater image data**

**Leaderboard ranking - 279/2025 (top 14%)**

https://www.kaggle.com/competitions/tensorflow-great-barrier-reef

The goal of this competition is to accurately identify starfish in real-time by building an object detection model trained on underwater videos of coral reefs.

Your work will help researchers identify species that are threatening Australia's Great Barrier Reef and take well-informed action to protect the reef for future generations.

![image](https://github.com/yoviny/Deep-learning-Competitions/blob/master/Prostate%20cANcer%20graDe%20Assessment%20Challenge/panda-image.png)

[source:https://www.kaggle.com/competitions/tensorflow-great-barrier-reef/overview/description)

# Evaluation metric
Submissions are scored based on the the F2 Score at different intersection over union (IoU) thresholds. The F2 metric weights recall more heavily than precision, as in this case it makes sense to tolerate some false positives in order to ensure very few starfish are missed.

The metric sweeps over IoU thresholds in the range of 0.3 to 0.8 with a step size of 0.05, calculating an F2 score at each threshold. For example, at a threshold of 0.5, a predicted object is considered a "hit" if its IoU with a ground truth object is at least 0.5.
[source:https://www.kaggle.com/competitions/tensorflow-great-barrier-reef/overview/evaluation]
