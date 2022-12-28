# Explainable AI for customer segmentation
## Original dataset
https://archive.ics.uci.edu/ml/datasets/adult
## Introduction
Both feature-based and data-based XAI are implemented in this program. Specifically, LIME is selected as the feature-based explainer, and Monte-Carlo methoed is developed as the data-based explainer.
## Experiment result
<div align=center>
<img width="1248" alt="local_explanation" src="https://user-images.githubusercontent.com/103876273/209775234-81a0bf75-f9b0-4b30-b175-614dae10b6b2.png"> 
</div>
<p align="center"> Figure 1 Local explanation for a data instance </p>
<div align=center>
<img width="511" alt="feature importance-scale down" src="https://user-images.githubusercontent.com/103876273/209777522-08b5ed9e-22c9-409e-b5e4-2b4c41e54f73.png">
</div>
<p align="center"> Figure 2 Feature importance  </p>
<div align=center>
<img width="519" alt="mode performance-scale down" src="https://user-images.githubusercontent.com/103876273/209777537-a0d45f56-e3cd-4c73-aca1-b55182420e3f.png">
</div>
<p align="center"> Figure 3 Model performance with high-value data VS low-value data  </p>  
