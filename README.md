# Handling Missing Data in Air Quality Dataset

This project demonstrates diagnosing and analyzing missing values in an air quality dataset using R and Pandas. It applies visualizations, statistical tests (t-test, chi-square), and exploratory analysis to assess whether missing values occur randomly or systematically across numerical and categorical attributes.

# Key Outcomes

Numerical Attributes: Missing values in NO2_Location_A are not influenced by Temperature, as confirmed by boxplots, histograms, and a two-sample t-test.

Categorical Attributes: No significant association was found between missing values and weekday, based on chi-square tests.

Overall Insight: Missing values appear to be randomly distributed, indicating no systematic pattern or external factor causing them.

Implication: Data can be safely preprocessed or imputed without introducing bias from these missing values.

# Skills highlighted:
Data cleaning, statistical analysis, R, Pandas, visualization, reproducible workflow.

#

<img width="975" height="532" alt="image" src="https://github.com/user-attachments/assets/3100c95a-56b7-4329-8618-32ec0eddcd46" />
*Shows Temperature distributions for rows with and without missing NO2_Location_A. Missing values appear randomly.*

<img width="975" height="373" alt="image" src="https://github.com/user-attachments/assets/d63334fd-8773-4c95-b8a9-0afa1cccb1a2" />


<img width="975" height="373" alt="image" src="https://github.com/user-attachments/assets/c80afc74-5e25-40d8-884c-b520959c8f5b" />

