# Task 3: Exploratory Data Analysis (EDA) Using Netflix Dataset

## 1. Problem Statement

The objective of this task is to perform Exploratory Data Analysis (EDA) on the Netflix dataset to identify trends, patterns, and relationships in the data.

The analysis includes calculating summary statistics, examining missing values, performing correlation analysis, and creating visualizations to understand Netflix's content distribution across content types, release years, and countries.

## 2. Dataset Details

- **Dataset Name:** Netflix Movies and TV Shows
- **Source:** Kaggle
- **File Name:** `netflix_titles.csv`
- **Dataset Link:** https://www.kaggle.com/datasets/shivamb/netflix-shows

The dataset contains information about movies and TV shows available on Netflix.

### Important Columns

| Column Name | Description |
|---|---|
| show_id | Unique ID of each title |
| type | Movie or TV Show |
| title | Name of the movie or TV show |
| director | Director's name |
| cast | Actors and actresses |
| country | Country associated with the title |
| date_added | Date the title was added to Netflix |
| release_year | Year the title was released |
| rating | Content rating |
| duration | Movie duration or number of seasons |
| listed_in | Genre or category |
| description | Brief description of the title |

## 3. Tools and Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 4. Approach

The following steps were performed during the analysis:

### Step 1: Data Loading
Imported the Netflix dataset using Pandas and displayed the first few records to understand its structure.

### Step 2: Data Inspection
Examined the dataset dimensions, column information, data types, and missing values.

### Step 3: Summary Statistics
Generated descriptive statistics to understand the dataset's characteristics.

### Step 4: Content Type Analysis
Created a count plot to compare the number of movies and TV shows available on Netflix.

### Step 5: Release Year Analysis
Created a line chart to examine the distribution of Netflix titles across release years.

### Step 6: Country Analysis
Created a bar chart showing the top 10 countries contributing Netflix content.

### Step 7: Correlation Analysis
Calculated correlations between numerical columns and displayed them using a heatmap where applicable.

### Step 8: Trend Analysis
Compared the number of movies and TV shows across release years to identify patterns in content distribution.

## 5. Visualizations

The following visualizations were created:

1. **Content Type Distribution:** Compares movies and TV shows.
2. **Release Year Trend:** Displays the number of titles by release year.
3. **Top 10 Countries:** Shows the countries with the highest numbers of titles.
4. **Correlation Heatmap:** Displays correlations between numerical variables.
5. **Movies vs. TV Shows Trend:** Compares the release-year distributions of movies and TV shows.

## 6. Results and Observations

- Movies represent a larger share of titles than TV shows in the analyzed Netflix dataset.
- The release-year analysis helps identify periods with higher numbers of titles.
- The country analysis highlights the countries contributing the most content.
- Comparing movies and TV shows reveals differences in their release-year distributions.
- Missing-value analysis identifies columns that may require further cleaning.
- Correlation analysis helps examine relationships between available numerical variables.

*Note: Actual counts and trends depend on the dataset version. The findings should be verified against the generated charts.*

## 7. Conclusion

This task demonstrates how Exploratory Data Analysis can be used to understand a real-world dataset. Summary statistics, missing-value analysis, correlation analysis, and visualizations were used to explore Netflix content and identify meaningful patterns.

The analysis provides a foundation for further data cleaning, visualization, and data-driven decision-making.

## 8. Project Structure

```text
Task-3-Netflix-EDA/
├── netflix_titles.csv
├── Netflix_EDA.ipynb
└── README.md
```

*Note: Update the filenames to match the files uploaded to your GitHub repository.*
