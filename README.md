# Real-Estate-Tycoon

A Real Estate Investment Trust based in New York invests in houses apartments/condo
They try to predict a fair transaction price of a property before it's sold. 
This is used to calibrate the internal pricing and to keep a tab on market prices.
REIT currently uses a 3rd party appraisal service and they found out that the estimates
given by inexperienced appraisers were off the mark by $70k on average. 
Task: to build a model to predict transaction prices with an average error of under $70k.

## Specifics
- Deliverable : Trained Model File
- Machine Learning Task: Regression
- Target Variable: Transaction Price
- Win Condition: Mean Absolute Error < $70k

## Project Scoping:
- implementing the entire applied machine learning workflow from start to finish 
  and focus on how they work together.

- This is a top-down approach that will first show  exactly where each piece fits
  into the big picture.

- This is to develop a high-level intuition of the entire process needed to build 
  an effective model using machine learning. 

- to practice using the entire suite of machine learning tools at your disposal.

- 5 core components of the Machine Learning workflow. 


## Exploratory Analysis
### Exercise 1.1 - Back to Basics: basic information about the dataset. 
- exploring basic information about the housing dataset.
### Exercise 1.2 - Distribution of categorical and numerical features.
- using Histograms
- plotting distributions of numeric and categorical features.

### Exercise 1.3 - Segmentation: Observing relationship between categorical feature & numerical features.
- Segmenting dataframes
- segmentation of the housing dataset by 'property_type'.
### Exercise 1.5 - Correlation: Observing relationships between Numeric features and other Numeric feature. 
- using heatmap
- visualizing a heatmap of feature correlations.
  1. Change the background to white. This way, 0 correlation will show as white
  2. Annotate the cell with their correlations values
  3. Mask the top triangle (less visual clutter)
  4. Drop the legend (colorbar on the side)


## Data Cleaning
### Exercise 2.1 - Introduction
- check the dataset for duplicate and irrelevant observations.
### Exercise 2.2 - Repairing Walls
- fixing various structural errors, such as mislabeled classes.
### Exercise 2.3 - Music of Outliers
- making violin plots of 'beds', 'sqft', 'lot_size'
- removing an outlier after plotting violin plots.
### Exercise 2.4 - Inputting Missing values
- labelling missing data in the categorical features.

## Feature Engineering
### Exercise 3.1 - Leveraging Domain Knowledge

### Exercise 3.2 - Heuristics (Creating Interaction features)

### Exercise 3.3 - Heuristics II (grouping sparse classes)
### Exercise 3.4 - School Score heuristics

### Exercise 3.5 - Sparse Roofs Heuristics

### Exercise 3.6 - Finalizing the A.B.T

- made several indicator features from domain knowledge.
- created the interaction feature 'property_age'.
- grouped sparse classes in the 'exterior_walls' and 'roof' features.
- encoded dummy variables and saved the final analytical base table.
## Regression Algorithms
### Exercise 1.1 - Back to Basics


## Model Training
### Exercise 1.1 - Back to Basics

