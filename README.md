Power BI Visualization Project: Amazon Customer Reviews Analysis
Overview
This project involves analyzing and visualizing a dataset of customer reviews using Power BI. The dataset has been cleaned and prepared to uncover insights into customer feedback, helpfulness, and sentiment distribution. The visualizations tell a compelling story about customer behavior, review trends, and product performance.

Features
Data Cleaning:

Handled missing values and duplicates.
Ensured data integrity by correcting issues such as invalid helpfulness ratios.
Normalized and standardized textual data for analysis.
Converted timestamps to human-readable formats.
Added derived metrics like HelpfulnessRatio for deeper insights.
Key Visualizations:

Review sentiment distribution.
Trends in review volume over time.
Analysis of helpfulness and total votes.
Product performance comparison.
Word cloud for most common terms in reviews.
Heatmaps, scatterplots, and decomposition trees for advanced insights.
Storytelling:

Focused on providing actionable insights for decision-makers.
Highlighted top-performing products and areas for improvement.
Dataset
The dataset used in this project contains the following key fields:

ProductId: Unique identifier for the product.
UserId: Unique identifier for the reviewer.
ProfileName: Name of the reviewer.
HelpfulnessNumerator: Number of helpful votes a review received.
HelpfulnessDenominator: Total votes a review received.
Score: Review score (1 to 5).
Time: Timestamp of the review.
Summary: Short description of the review.
Text: Full review text.
The cleaned version of the dataset, Cleaned_Reviews.csv, is included for reproducibility.

Tools and Technologies
Data Cleaning: Python (pandas, numpy) in Google Colab.
Visualization: Power BI.
Instructions
Step 1: Data Cleaning
Open the provided clean_data.py script in Google Colab to clean the raw dataset.
Ensure the cleaned dataset is saved as Cleaned_Reviews.csv.
Step 2: Load Data into Power BI
Open Power BI and import the cleaned dataset (Cleaned_Reviews.csv).
Ensure data types are correctly set (e.g., Time as datetime).
Step 3: Build Visualizations
Use the following charts and visuals in Power BI:

Bar Chart: Distribution of reviews by Score.
Line Chart: Trends in review counts over time.
Scatter Plot: Correlation between HelpfulVotes and TotalVotes.
Word Cloud: Common words in Summary or Text.
Heatmap: Review distribution by Score and ProductId.
Decomposition Tree: Breakdown of total reviews by Score and other factors.
Step 4: Publish and Share
Save the Power BI report as a .pbix file.
Share the file or publish it to the Power BI Service for broader access.
Example Visualizations
Sentiment distribution across products.
Trends in helpfulness ratios over time.
Word cloud of commonly used terms in reviews.
Future Enhancements
Automate data cleaning using an ETL pipeline.
Add predictive analysis for customer sentiment.
Integrate the Power BI dashboard with a live database for real-time insights.
Author
[Your Name]
[Your Contact Information]
