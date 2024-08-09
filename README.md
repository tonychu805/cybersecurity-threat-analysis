# cybersecurity-threat-analysis

## Introduction
This analysis focuses on cybersecurity threat data, with an emphasis on merging multiple CSV files, conducting exploratory data analysis (EDA), and applying statistical and machine learning techniques to extract meaningful insights from the dataset. Let's commence!

## Objectives
- Understand the structure and distribution of the cybersecurity dataset.
- Perform data cleaning and transformation to prepare the dataset for analysis.
- Generate summary statistics and visualizations to identify key patterns and relationships.
- Implement statistical tests and clustering techniques to explore data characteristics and trends.
- Identify vulnerabilities and trends within the data, and assess the timeliness and efficiency of vulnerability patching.

## Methodologies

### Exploratory Data Analysis (EDA)
- Data Structure and Cleaning: Provided an overview of the dataset structure, removed unnecessary columns, and converted date columns to datetime format.
- Descriptive Statistics and Visualization: Generated summary statistics and visualizations, such as bar plots, histograms, and heatmaps, to understand data distributions and relationships.
- Correlation Analysis: Calculated and visualized correlations between numerical variables using heatmaps.
Statistical Analysis

### T-Test and Chi-Squared Test: 
- Conducted t-tests and chi-squared tests to compare means and examine relationships between variables within the dataset.

### Hierarchical Clustering: 
- Implemented hierarchical clustering techniques and visualized the results using dendrograms.
- Patch Time Analysis: Analyzed and visualized the time taken to patch vulnerabilities, including histogram plots and binning strategies.

## Insights and Findings
### Product Vulnerabilities:
- Windows: Identified as the most affected product with 311 reported vulnerabilities.
- Other Products: Noted vulnerabilities in Flash Player (116), Internet Explorer (96), Office (81), Win32k (80).
- Insight: Emphasizes the need for enhanced security protocols for widely used products.
### Severity of Vulnerabilities:
- High Severity: 55.6% of vulnerabilities were classified as high severity.
- Critical Severity: 34% were critical, posing severe risks.
- Medium Severity: 15% of vulnerabilities were medium severity.
- Low Severity: The remaining vulnerabilities were of low severity.
- Insight: Highlights the urgent need to address high and critical severity vulnerabilities due to their potential damage.
### Patching Timeliness:
- Efficiency: All vulnerabilities were patched by their due dates.
- Insight: Reflects a high level of commitment and efficiency in vulnerability management.
### Vulnerability Vectors:
- Network-Related: Accounted for 73.4% of vulnerabilities.
- Local Vectors: Made up 25% of vulnerabilities.
- Adjacent Network Vectors: Comprised 1.5% of vulnerabilities.
- Insight: Stresses the importance of fortifying both network and local systems.
### Complexity of Vulnerabilities:
- Low Complexity: 91% of vulnerabilities were easily exploitable.
- High Complexity: 9% of vulnerabilities were more complex.
- Insight: Necessitates preemptive security measures to address easily exploitable vulnerabilities.
### Vendor Vulnerabilities:
- Microsoft: Identified as the most affected vendor with 925 vulnerabilities.
- Other Vendors: Noted vulnerabilities in Adobe (236), Cisco (233), Apple (154), Google (147).
- Insight: Points to the critical need for focusing security initiatives and collaboration with these vendors.
### Patching Speed:
- Fastest Patching: Occurred within 44 days, indicating instances of pre-patching.
- Slowest Patching: Took as long as 7212 days.
- Median Patching Time: Was 1064 days.
- Average Patching Time: Calculated to be 1396.8 days.
## Git Repository Content:
- 5 CVE files in csv format from Kaggle
- cybersecurity threat analysis.ipynb to document the analysis

## Dependencies and Libraries:

- Pandas: For data manipulation and analysis.
- NumPy: For numerical operations.
- Matplotlib and Seaborn: For data visualization.
- SciPy: For statistical tests and hierarchical clustering.
- scikit-learn: For machine learning algorithms and imputation.
- glob and os: For file handling and directory operations.




