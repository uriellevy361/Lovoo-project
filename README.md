# Project README

## Lovoo Meeting App Data Analytics Project

### Project Overview:

This project analyzes a dataset from the Lovoo meeting app, focusing on female user profiles gathered during spring 2015. The project aims to explore various aspects of user behavior and preferences within the app.

### Project Team:

- **Lecturer:** Dr. Lihi Drai
- **Team Members:** Uriel Levy, Daniel Tzumi, Dan Sa'adya, Artem Goncharov

### Introduction:

The Lovoo meeting app dataset is explored using Python, particularly utilizing the Jupyter notebooks. The analysis covers several key aspects, including age distribution, correlations between various user metrics, word cloud analysis of user bios, and exploration of user interests.

### Prerequisites:

To run the provided code, ensure that you have the following Python libraries installed:

```bash
pip install wordcloud
```

### Data Details:

The dataset is loaded from the following URL:

```python
link = 'https://raw.githubusercontent.com/tema455/Project-1/main/lovoo_v3_users_api-results%20(1).csv'
df = pd.read_csv(link)
```

A summary of the dataset's information is obtained using:

```python
df.info()
```

### Analysis Highlights:

#### 1. Correlation Matrix:

The project explores correlations between various user metrics using the Spearman method. The key findings include strong positive correlations between counts_kisses & counts_profileVisits, counts_fans & counts_kisses / counts_profileVisits, counts_profileVisits & counts_pictures, and more.

#### 2. Word Cloud Analysis:

A word cloud is generated to visualize the most popular words within user bios. This analysis reveals common social network mentions (e.g., Facebook, Snapchat, Instagram) and identifies positive, attractive, and filtering-related words used by users.

#### 3. User Interests:

The project categorizes users based on their flirt interests (chat, friends, date) and explores their characteristics, such as distance vs. match counts. Insights include users open to dating having fewer matches, while those seeking chat purposes tend to have more matches.

### How to Run:

1. Ensure you have Python installed on your system.
2. Install the required libraries using the provided pip command.
3. Download the Jupyter notebook or copy the code sections into your own notebook.
4. Execute the code cells in sequence to reproduce the analysis.

### Conclusion:

The Lovoo meeting app data analytics project provides valuable insights into user behavior and preferences. The correlation matrix, word cloud analysis, and exploration of user interests contribute to a comprehensive understanding of the dataset.

Thank you for your time and attention. For more details and visualizations, refer to the complete Jupyter notebook in this repository.
