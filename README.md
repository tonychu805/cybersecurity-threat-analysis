# cybersecurity-threat-analysis

## Summary:

- Introduction: The notebook focuses on analyzing cybersecurity threat data, aiming to merge multiple CSV files, perform exploratory data analysis (EDA), and apply statistical and machine learning techniques to extract insights.
- Data Loading and Merging: Code cells demonstrate how to load and merge multiple CSV files from a directory into a single DataFrame.
- Exploratory Data Analysis (EDA):
  - Data Structure and Cleaning: Overview of the dataset structure, removal of unnecessary columns, and conversion of date columns to datetime format.
  - Descriptive Statistics and Visualization: Generating summary statistics and visualizations such as bar plots, histograms, and heatmaps to understand data distributions and relationships.
  - Correlation Analysis: Calculating and visualizing correlations between numerical variables using heatmaps.
- Statistical Analysis:
  - T-Test and Chi-Squared Test: Functions and code for performing t-tests and chi-squared tests to compare means and examine relationships between variables.
- Clustering and Pattern Recognition:
  - Hierarchical Clustering: Code for hierarchical clustering and dendrogram visualization.
  - Patch Time Analysis: Calculation and visualization of the time taken to patch vulnerabilities, including histogram plots and binning strategies.
- Insights and Findings:
  - Identified patterns and trends in the cybersecurity threat data, such as product and CWE rankings, and patch time distributions.
  - Highlighted the importance of specific features and their relationships to vulnerability patching.

Git Repository Content:

- The notebook does not explicitly mention the Git repository content, but it implies that the repository contains scripts for data loading, merging, EDA, and statistical analysis.

Dependencies and Libraries:

- Pandas: For data manipulation and analysis.
- NumPy: For numerical operations.
- Matplotlib and Seaborn: For data visualization.
- SciPy: For statistical tests and hierarchical clustering.
- scikit-learn: For machine learning algorithms and imputation.
- glob and os: For file handling and directory operations.



In this project, I delved into the patterns and characteristics of vulnerabilities, their severity, the speed of patching, and temporal trends.

The analysis of vulnerabilities across different products showed that Windows had the highest incidence, with 311 reported vulnerabilities, making it the most affected. It was followed by the Flash Player at 116, Internet Explorer at 96, Office at 81, and Win32k at 80 vulnerabilities. This underscores the necessity for enhanced security protocols for these widely utilized products.

Regarding the severity of these vulnerabilities, 55.6% was deemed high severity, highlighting the urgent nature of these security threats. Furthermore, over 34% of these vulnerabilities were considered critical, posing a severe risk of damage. About 15% were of medium severity, and the rest were categorized as low severity.

Looking at the timeliness of vulnerability patching, it was observed that an exceptional 100% of the vulnerabilities were patched by their due dates. This reflects a commendable level of commitment and efficiency in the management and resolution of vulnerabilities, bolstering security defenses.

In terms of vulnerabilities by vector, the majority, amounting to 73.4%, were network-related, with 25% classified under local vectors, and only 1.5% associated with adjacent network vectors. This emphasizes the critical need to fortify both network and local systems against threats.

When examining vulnerabilities based on complexity, it was found that there were more vulnerabilities of low complexity (91%) than those of high complexity (9%). This suggests that many vulnerabilities could be exploited with relative ease, necessitating preemptive security measures.

The analysis also highlighted the vendors most affected by vulnerabilities, with Microsoft leading at 925, followed by Adobe at 236, Cisco at 233, Apple at 154, and Google at 147. This information is crucial for focusing security initiatives and collaborating with these vendors to mitigate vulnerabilities.

In evaluating the speed of patching, the fastest patching time was noted as 44 days, indicating instances of pre-patching, while the slowest was 7212 days. The median patching time stood at 1064 days, with an average of 1396.8 days. This points to the critical importance of prompt and efficient patching to reduce the risk and impact of vulnerabilities.
