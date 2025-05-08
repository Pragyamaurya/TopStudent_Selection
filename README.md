# Student Performance Clustering
This project applies clustering techniques on a dataset of students' academic performance to classify them into Top, Medium, and Low performance categories based on their scores in Math, Reading, and Writing.

📊 Dataset Overview
The dataset consists of students' demographic and academic details including:

Gender

Race/Ethnicity

Parental Level of Education

Lunch Type

Test Preparation Course

Math Score

Reading Score

Writing Score

Sample Features
Feature	Description
math score	Marks obtained in Math (0–100)
reading score	Marks obtained in Reading (0–100)
writing score	Marks obtained in Writing (0–100)

🔍 Objective
The main goal is to cluster students based on academic scores to identify groups such as:

Top Performers

Medium Performers

Low Performers

These groupings help in understanding performance trends and potentially guiding targeted interventions.

🧠 Methodology
Data Preprocessing

Selected relevant numerical features: math score, reading score, writing score

Normalized the scores (if necessary)

Clustering Algorithm

Applied K-Means Clustering

Chose k=3 (for top, medium, low groups)

Evaluated cluster quality using inertia and silhouette score

Cluster Labeling

After clustering, average scores of each cluster were analyzed

Labels were assigned as:

Top Performer

Medium Performer

Low Performer

📈 Results
Each student was assigned to a cluster based on their overall academic performance. These clusters help in:

Identifying high-achieving students

Spotting students who may need academic support

Understanding overall group-level trends

📁 Files
student_scores.csv: The dataset used

student_clustering.ipynb: Notebook for preprocessing, clustering, and analysis

README.md: This file

🛠 Tools Used
Python

Pandas, NumPy

Matplotlib, Seaborn (for visualization)

Scikit-learn (for clustering)

📝 Future Work
Incorporate demographic features for deeper segmentation

Use advanced clustering (e.g., DBSCAN, Agglomerative Clustering)

Apply classification models post-clustering








