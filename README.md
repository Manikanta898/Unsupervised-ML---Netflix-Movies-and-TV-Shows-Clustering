# Netflix Movies and TV Shows Clustering - ML Project

This project focuses on applying unsupervised machine learning to cluster Netflix movies and TV shows, uncovering trends and patterns to inform content categorization and business decisions.

## Table of Contents
- [Getting Started](#getting-started)
- [Data Sources](#data-sources)
- [File Descriptions](#file-descriptions)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Clustering](#clustering)
- [Technologies Used](#technologies-used)
- [Usage](#usage)

## Getting Started
To run the analysis locally, clone this repository and install the dependencies.

## Data Sources
The Netflix data used in this project was sourced from Almabetter.

## File Descriptions
- Netflix_Movies_and_TV_Shows_Clustering.ipynb : Colab notebook containing the exploratory data analysis.
- NETFLIX MOVIES AND TV SHOWS CLUSTERING.csv : Folder containing the raw and processed datasets.

## Exploratory Data Analysis
In the Netflix_Movies_and_TV_Shows_Clustering.ipynb  notebook, the following aspects of the Netflix data were explored:
- Data Visualization, Storytelling & Experimenting with Charts.
- Distribution of Content ratings and durations of different Movies and TV Shows.
- Correlation between relevant numerical variables.

## Clustering
In the Netflix_Movies_and_TV_Shows_Clustering.ipynb notebook, the following aspects of clustering were explored:
- Applied KMeans clustering with 6 clusters, based on silhouette score.
- Used Agglomerative Clustering with 4 clusters and visualized the results with a dendrogram.
- Applied DBSCAN, but it struggled with noise, resulting in one large and a few small clusters.
- Chose KMeans as the final model for its ability to handle noise and generate meaningful clusters.


## Technologies Used
- Python 3
- Colab Notebook
- Pandas, Matplotlib, Numpy, Seaborn, nltk(Natural Language Toolkit), scikit-learn, scipy, yellowbrick

## Usage
To reproduce the analysis, open  Netflix_Movies_and_TV_Shows_Clustering.ipynb  in Colab Notebook and execute the cells sequentially.
