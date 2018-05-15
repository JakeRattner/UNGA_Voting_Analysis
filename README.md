# UNGA_Voting_Analysis
How and Why U.N. Member Nations form Voting Blocks Each Year

# United Nations Voting Records: Cluster Analysis

Status: Completed, new features being added.

United Nations Voting Record Slider: Yearly Cluster Analysis:
A cluster analysis of UN voting records in the General Assembly.  

A HDBSCAN cluster analysis of UN member state voting records from 1946 - 2017. Each year's data is passed through a function which generates output of: Which countries reside in each cluster, PCA visualization, identification of which resolutions were most significant in forming clusters. 

# Installation:

- git clone https://github.com/JakeRattner/United_Nations_Voting_Records-Cluster_Analysis.git
- Ensure all libraries added/supported
- Open in Jupyter Notebook

# Usage:

- Run code from jupyer notebook until you see the following widget near the bottom of the notebook:
- Use slider at end of notebook to view yearly output:
<img width="1016" alt="slider" src="https://user-images.githubusercontent.com/34926054/39941030-de852f58-5520-11e8-8870-83949ffb83b4.png">

PCA-based Visualization (Note: Purple pts = Outliers)
<img width="672" alt="pca visualized" src="https://user-images.githubusercontent.com/34926054/39941186-5dc1d01e-5521-11e8-8ce6-aae252c46be2.png">

HDBSCAN-based Output (Silhouette Coefficient, # of clusters, countries in each cluster)
<img width="998" alt="hdbscan output" src="https://user-images.githubusercontent.com/34926054/39941627-c7d96100-5522-11e8-889a-9b7600017549.png">

PCA Variance Analysis (Tells us which resolutions voted on in a given year were most important/responsible for variance)
<img width="613" alt="pca scoring" src="https://user-images.githubusercontent.com/34926054/39941686-f7f587ce-5522-11e8-92d5-97f06e35a6e0.png">

# Contributing:
As I continue to build this project out I am looking for any help / opportunities for collaboration.  Please contact me through Github or rattnerjake at gmail.com.  I will be adding more detailed notes on opportunities for collab in the future.

# Credits/Sources:
- Voeten, Erik; Strezhnev, Anton; Bailey, Michael, 2009, "United Nations General Assembly Voting Data", https://hdl.handle.net/1902.1/12379, Harvard Dataverse, V18, UNF:6:xkt0YWtoBCThQeTJWAuLfg==
- I would also like to credit; Heather Robbins, Mathew Brems, Justin Pounders and Riley Dallas for the suggestions and guidance offered over the course of this project. Thanks guys!

