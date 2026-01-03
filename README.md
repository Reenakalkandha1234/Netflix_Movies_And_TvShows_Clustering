🎬 Netflix Movies and TV Shows Clustering
📌 Project Overview

This project focuses on clustering Netflix movies and TV shows using unsupervised machine learning techniques.
The goal is to group similar content based on features like description, genre, duration, rating, and country, which can help improve recommendation systems and content analysis.

This project is part of Module 6 – Unsupervised Learning under the AlmaBetter Data Science & Machine Learning Program.

🧠 Problem Statement

Netflix has a huge library of movies and TV shows.
Due to the large volume of content, it becomes difficult to:

Understand content patterns

Group similar content

Improve personalized recommendations

🎯 Objective

To apply clustering algorithms to group Netflix content into meaningful clusters based on similarity.

📂 Dataset Description

The dataset contains information about Netflix movies and TV shows, including:

Show ID

Type (Movie / TV Show)

Title

Director

Cast

Country

Date Added

Release Year

Rating

Duration

Listed Genres

Description

The dataset contains missing values and text data, which require preprocessing before modeling.

🧹 Data Cleaning & Preprocessing

The following preprocessing steps were performed:

Handled missing values by replacing them with "Unknown"

Converted date_added to datetime format

Extracted year and month from date

Cleaned the duration column

Removed duplicates

Processed text data by:

Lowercasing

Removing punctuation and stopwords

Tokenization

📊 Exploratory Data Analysis (EDA)

EDA was performed to understand Netflix content trends:

Distribution of Movies vs TV Shows

Content growth over years

Country-wise content production

Most common genres on Netflix

📌 Key Insight:
Netflix content increased rapidly after 2015, with movies dominating the platform.

🔤 Text Vectorization

Used TF-IDF Vectorizer to convert text descriptions into numerical features

TF-IDF helps identify important words while reducing the impact of common words

⚙️ Feature Engineering & Scaling

Combined text features with numerical features

Applied StandardScaler to normalize data

Scaling is important because clustering algorithms are distance-based

🤖 Clustering Model
Algorithm Used:

K-Means Clustering

Choosing Optimal Clusters:

Used the Elbow Method

Optimal number of clusters selected: 5

📈 Cluster Analysis & Visualization

The dataset was grouped into 5 meaningful clusters

Used PCA (Principal Component Analysis) for dimensionality reduction

Visualized clusters in 2D space to verify separation

📌 Each cluster represents a different category of Netflix content such as:

Long-running TV shows

Short movies

Drama-focused content

Comedy and family content

International shows and movies

✅ Conclusion

Successfully clustered Netflix movies and TV shows

Demonstrated the use of unsupervised learning in real-world scenarios

Highlighted the importance of text preprocessing in machine learning

💡 Business Use Case

Improves recommendation systems

Helps Netflix understand content strategy

Enables better user segmentation

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-Learn

NLP (TF-IDF)

Jupyter Notebook# Netflix_Movies_And_TvShows_Clustering
