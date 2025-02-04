# Heart Disease Exploratory Data Analysis

This repository contains a Python-based Exploratory Data Analysis (EDA) project focused on a heart disease dataset. The project utilizes popular data visualization libraries like Pandas, Seaborn, and Matplotlib to gain insights into the data and identify potential risk factors associated with heart disease.

## Prerequisites

Before running the code in this repository, ensure you have the following Python libraries installed:

- Pandas: For data manipulation and analysis.
- Seaborn: For statistical data visualization.
- Matplotlib: For creating static, interactive, and animated visualizations in Python.

You can install these libraries using pip:

```bash
pip install pandas seaborn matplotlib


Project Overview
This EDA project is divided into six key sections, each focusing on a specific aspect of the heart disease dataset:

Heart Disease EDA - Age (DistPlot): Visualizes the distribution of age using a distplot, combining a histogram, kernel density estimate (KDE), and rug plot.  This allows us to understand the age range of the individuals in the dataset and identify any age-related patterns.  We observe the minimum and maximum ages and the distribution of ages within the dataset.

Heart Disease EDA - Categorical Columns (Pie Charts): Explores the distribution of categorical variables, such as gender, using pie charts. This helps to understand the proportion of different categories within the dataset. In this specific example, we analyze the gender distribution among individuals with heart disease.

Heart Disease EDA - ViolinPlot: Combines a box plot and a kernel density plot to visualize the distribution of a continuous variable (e.g., age) for different categories (e.g., gender). This allows us to compare the distributions and identify potential differences.  We compare the distribution of age for males and females to see if there are any differences in age ranges.

Heart Disease EDA - Correlation (HeatMap): Creates a heatmap to visualize the correlation matrix of numerical variables. This helps to identify strong positive or negative correlations between variables.

Heart Disease EDA - Correlation (PairPlot): Generates a pairplot, which is a matrix of scatter plots showing the pairwise relationships between numerical variables. The diagonal of the matrix displays the distribution of each individual variable. This provides a comprehensive view of the relationships between all numerical features.

Heart Disease EDA - Correlation - (JointPlot): Visualizes the joint distribution of two variables along with their individual distributions using a scatter plot with marginal histograms or KDE plots.  This allows us to see how two variables relate to each other. In this case, we explore the relationship between cholesterol levels and maximum heart rate (MaxHR).
