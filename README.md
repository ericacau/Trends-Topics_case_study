# Trends \& Topics case study

This repository refers to the paper [Trends and Topics: Characterizing Echo Chambers' Topological Stability and In-group Attitudes](https://arxiv.org/abs/2307.15610) and contains the code of the case study. 
<br/>
The aim of the paper is to define a platform-independent framework to detect and analyze the temporal development of echo chambers through Dynamic Community Detection while considering the topics discussed by users via topic modeling and valence analysis. The analysis is conducted on Reddit's discussion about *politics*, *minorities discrimination* and *gun control* the first two year and a half of Donald Trump's presidency (2017/2019).

## Content
+ **EC detection and analysis** folder contains the code to create the user interaction network and analyze the diachronic stability of echo chambers and non polarized communities
+ **Topic Modeling** contains the code to perform the preprocessing of texts and the topic extraction via BERTopic
+ **Valence extraction and analysis** folder contains the code to calculate valence scores for texts and visualization
+ **plot**: the folder contains all the figures of the analysis

## Dataset
+ The **data** folder contains a sample of the data used in the case study, organized by topic and semester.
