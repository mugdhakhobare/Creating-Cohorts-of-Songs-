# Creating Cohorts of Songs using Clustering (Spotify Data)

📌 Project Overview :

Personalized recommendations are a key factor in enhancing user experience on music streaming platforms like Spotify. This project focuses on creating cohorts (clusters) of songs based on their audio features to better understand song similarities and enable improved recommendation strategies.

The dataset used contains audio feature information for Rolling Stones songs available on Spotify. Using Exploratory Data Analysis (EDA) and K-Means clustering, similar songs are grouped into meaningful cohorts.



🎯 Objective :

Perform Exploratory Data Analysis (EDA) on Spotify song data

Identify patterns influencing song popularity

Create song cohorts using unsupervised machine learning

Interpret clusters to support personalized music recommendations




📂 Dataset Description :

The dataset is sourced from Spotify’s API and contains the following key attributes:

name – Song name

album – Album name

release_date – Album release date

popularity – Song popularity score (0–100)

acousticness, danceability, energy

instrumentalness, liveness, speechiness

loudness, tempo, valence

duration_ms – Duration of the song

Each song is uniquely identified using a Spotify ID.




🛠️ Technologies & Libraries Used :

Python

Pandas & NumPy – Data manipulation

Matplotlib & Seaborn – Data visualization

Scikit-learn –

StandardScaler

K-Means Clustering

PCA (Principal Component Analysis)




🔍 Project Workflow :

Data Loading & Inspection

Data Cleaning & Preprocessing

Exploratory Data Analysis (EDA)

Album Recommendation Analysis

Feature Scaling

Finding Optimal Clusters (Elbow Method & Silhouette Score)

K-Means Clustering

Cluster Profiling & Interpretation

Dimensionality Reduction using PCA

Business Insights & Conclusion




📊 Key Insights :

Songs were successfully grouped into distinct cohorts based on audio features.

Clusters represent different song types such as:

High-energy rock songs

Acoustic and instrumental tracks

Balanced and danceable songs

Emotional and low-valence songs

PCA helped in visualizing clusters effectively by reducing dimensionality.




📈 Business Relevance :

Helps in personalized song recommendations

Supports mood-based playlist creation

Enhances user engagement and retention

Useful for music analytics and recommendation systems




🚀 Conclusion :

This project demonstrates how unsupervised learning techniques like clustering can be used to extract meaningful insights from music data. The results can be leveraged to improve recommendation systems and deliver a better listening experience to users.
