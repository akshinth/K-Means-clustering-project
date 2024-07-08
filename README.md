# K-Means-clustering-project

## Overview

This project aims to use KMeans Clustering to group universities into two clusters based on various factors, distinguishing between private and public institutions.

## Project Description

### The Data

The dataset contains 777 observations on the following 18 variables:

- **Private**: A factor with levels "No" and "Yes" indicating private or public university
- **Apps**: Number of applications received
- **Accept**: Number of applications accepted
- **Enroll**: Number of new students enrolled
- **Top10perc**: Percentage of new students from the top 10% of high school class
- **Top25perc**: Percentage of new students from the top 25% of high school class
- **F.Undergrad**: Number of full-time undergraduates
- **P.Undergrad**: Number of part-time undergraduates
- **Outstate**: Out-of-state tuition
- **Room.Board**: Room and board costs
- **Books**: Estimated book costs
- **Personal**: Estimated personal spending
- **PhD**: Percentage of faculty with Ph.D.'s
- **Terminal**: Percentage of faculty with terminal degree
- **S.F.Ratio**: Student/faculty ratio
- **perc.alumni**: Percentage of alumni who donate
- **Expend**: Instructional expenditure per student
- **Grad.Rate**: Graduation rate

## Project Structure

1. **Data Loading and Exploration**
   - Load the dataset into a pandas DataFrame.
   - Explore the data to understand its structure and content.

2. **Data Preparation**
   - Handle any missing or erroneous data.
   - Convert categorical variables like "Private" into numerical format if necessary.
   - Scale the data as needed for clustering algorithms.

3. **Modeling: K Means Clustering**
   - Implement the KMeans clustering algorithm to cluster universities into two groups (private and public).
   - Visualize the clusters and analyze their characteristics.

4. **Evaluation**
   - As this project involves labeled data (Private/No), a new column 'Cluster' was created in the DataFrame.
   - 'Cluster' is set to 1 for Private schools and 0 for public schools.
   - Utilize this labeled data to evaluate the clustering results.
   - Assess the accuracy of clustering by comparing the assigned clusters to the actual labels.

5. **Conclusion**
   - Summarize findings and insights gained from the clustering analysis.
   - Discuss potential applications or further steps based on the results.

## Usage

To run this project, ensure you have Python installed along with the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn


