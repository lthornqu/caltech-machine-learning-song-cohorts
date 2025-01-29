# caltech-machine-learning-song-cohorts
Machine Learning project through Caltech. Performed exploratory data analysis, feature engineering, and cluster analysis on The Rolling Stones’ discography to create a cohort of songs and recommendations for users to discover similar music to their favorite songs and albums.

---

## 🎵 Creating Cohorts of Songs

### 📌 Project Overview
This project aims to enhance music recommendation systems by clustering songs into distinct cohorts based on their attributes. Using data from Spotify, we apply **exploratory data analysis (EDA)** and **clustering techniques** to identify patterns in song characteristics. The insights from this project can help improve personalized music recommendations.

### 🏆 Objective
As a data scientist / machine learning engineer, the goal is to analyze song features, understand the relationships between different attributes, and categorize songs into meaningful clusters. This will help in:
- Identifying key factors that influence song popularity.
- Grouping similar songs to create meaningful cohorts.
- Enhancing music recommendation algorithms.

### 📝 Dataset Description
The dataset includes all **Rolling Stones** albums available on Spotify, with the following key attributes:

| Variable       | Description |
|---------------|------------|
| `name` | Song title |
| `album` | Album name |
| `release_date` | Release date (YYYY-MM-DD) |
| `track_number` | Position of the song in the album |
| `id` | Unique Spotify song ID |
| `uri` | Spotify URI for the song |
| `acousticness` | Confidence level (0.0 - 1.0) for whether a track is acoustic |
| `danceability` | Suitability for dancing (0.0 - 1.0) |
| `energy` | Perceptual measure of intensity and activity (0.0 - 1.0) |
| `instrumentalness` | Likelihood of no vocals (0.0 - 1.0) |
| `liveness` | Probability of a live performance (0.0 - 1.0) |
| `loudness` | Overall loudness in decibels (dB) |
| `speechiness` | Measure of spoken words in a track (0.0 - 1.0) |
| `tempo` | Beats per minute (BPM) |
| `valence` | Musical positiveness (0.0 - 1.0) |
| `popularity` | Popularity score (0 - 100) |
| `duration_ms` | Track duration in milliseconds |

---

## 📊 Steps to Perform

### 🔍 1. Data Preprocessing
- Inspect for missing values, duplicates, and outliers.
- Clean and refine data for further processing.

### 📈 2. Exploratory Data Analysis (EDA)
- Generate visualizations to understand song characteristics.
- Identify the most popular albums based on the number of hit songs.
- Analyze the relationship between song popularity and key features.
- Discuss the importance of **dimensionality reduction** for clustering.

### 🎯 3. Clustering Analysis
- Determine the optimal number of clusters.
- Apply suitable **clustering algorithms** (e.g., K-Means, DBSCAN).
- Define each cluster based on the extracted features.

---

## 🛠️ Technologies Used
- **Python**
- **Pandas**, **NumPy** – Data manipulation
- **Matplotlib**, **Seaborn** – Data visualization
- **Scikit-learn** – Machine learning (clustering, dimensionality reduction)
- **Spotify API** – Data collection (if needed)

---

## 📌 Key Insights
- Identified patterns in song popularity and attributes.
- Clustered songs into meaningful groups for better recommendations.
- Highlighted the significance of different song features in user engagement.

---

## 🚀 How to Use This Project
1. Clone the repository:
   ```bash
   git clone https://github.com//song-cohort-clustering.git](https://github.com/lthornqu/caltech-machine-learning-song-cohorts.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the **Jupyter Notebook** to explore data and perform clustering.

---

## 📌 Future Improvements
- Expand the dataset beyond Rolling Stones albums.
- Implement **deep learning** techniques for music classification.
- Integrate the model into a real-time recommendation system.

---

## 👨‍💻 Contributors
- **Lee Thornquist** - Data Analysis & Machine Learning
