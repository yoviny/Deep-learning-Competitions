<img src="https://github.com/yoviny/Deep-learning-Competitions/blob/master/HuBMAP%20-%20Hacking%20the%20Kidney/thumbnail_hubmap.png" width="128">

# HuBMAP - Hacking the Kidney (17/11/2020 - 10/05/2021)
**Identify glomeruli in human kidney tissue images**

**Competition leaderboard ranking - 190/1216 (top 16%)**
**Final Dice Score - 0.9407**

Just as the Human Genome Project mapped the entirety of human DNA, the Human BioMolecular Atlas Program (HuBMAP) is a major endeavor. Sponsored by the National Institutes of Health (NIH), HuBMAP is working to catalyze the development of a framework for mapping the human body at a level of glomeruli functional tissue units for the first time in history. Hoping to become one of the world’s largest collaborative biological projects, HuBMAP aims to be an open map of the human body at the cellular level.

This competition, “Hacking the Kidney," starts by mapping the human kidney at single cell resolution.

The challenge is to detect functional tissue units (FTUs) across different tissue preparation pipelines. An FTU is defined as a “three-dimensional block of cells centered around a capillary, such that each cell in this block is within diffusion distance from any other cell in the same block” (de Bono, 2013). The goal of this competition is the implementation of a successful and robust glomeruli FTU detector.
[source:https://www.kaggle.com/c/hubmap-kidney-segmentation/overview/description]

# Evaluation metric
Submissions are evaluated on the mean Dice coefficient. The Dice coefficient can be used to compare the pixel-wise agreement between a predicted segmentation and its corresponding ground truth. The formula is given by:

<img src="https://github.com/yoviny/Deep-learning-Competitions/blob/master/HuBMAP%20-%20Hacking%20the%20Kidney/dice%20coeff%20eq.png" width="128>
