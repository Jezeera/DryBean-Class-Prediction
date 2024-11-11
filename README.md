# DryBean-Class-Prediction

# Motivation to solve the Problem:

Dry Beans are one of the most consumed edible legumes in the world. Seed quality affects the crop production and revenue.

It is hence essential to classify dry bean seeds for optimal production and max revenue as well as for sustainable farming.

# Goals of the Project:

This clearly is a multi class classification problem where we need to classify a Dry bean seed into one of the seven classes from Seker, Barbunya, Bombay, Cali, Dermosan, Horoz and Sira.


# File Structure:

Dry-Bean-Predictor.ipynb -> Jupyter Notebook with ML Model

Dry_Bean_Dataset.xlsx -> Dataset

# RESULTS
# 1) 
The analysis drawn from the data (preprocessing and visualisation) are:

There are no null values in the dataset and 68 duplicate values.

We can see that the DERMASON is the most abundant class while BOMBAY is the least abundant class.

BOMBAY class has the highest area and perimeter while the DERMASON class the lowest.

There are many outliers in the area and perimeter in the dataset.

BOMBAY Class has high Major and Minor Axis length and Minor Axis Length.

ConvexArea and Area have a direct correlation. i.e., As ConvexArea increases the Area increases.

# 2)
Best model for finding the class of drybean have identified which is RANDOM FOREST.
And it is saved with pipeline setting for future predicting purpose.

# Future works:

We can apply more ML model buiding techniques to find more accurate ML model for the prediction.
We can learn more about uses from the paper and update our models accordingly.



