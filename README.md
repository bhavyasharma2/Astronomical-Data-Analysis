# Astronomical Data Analysis using SDSS Tabular Data 

**Overview**

This project involves the analysis and classification of astronomical objects using data from the Sloan Digital Sky Survey (SDSS). The key steps of the project include:

- Data Retrieval and Exploration:

> Download the SDSS tabular dataset from Google Drive and load it into a Pandas DataFrame.
> Explore and analyze the structure of the dataset, identifying unique classes and checking for constant columns.

- Data Visualization:

> Utilize Matplotlib to visualize the distribution of classes in the data, providing insights into the balance of the dataset.
> Create 3D scatter plots to visualize the distribution of stars, galaxies, and quasars based on Right Ascension, Declination, and Redshift.

- Data Preprocessing:

> Prepare the data for machine learning by removing irrelevant columns and splitting it into features (X) and labels (y).
> Apply one-hot encoding to convert the categorical labels into a numerical format.

- Data Scaling:

> Use Min-Max Scaling to standardize the feature values, ensuring consistent ranges for input data to the machine learning model.

- Model Building and Training:

> Build a neural network model using Keras with multiple layers and softmax activation for classification.
> Train the model on the prepared dataset, validating its performance with a 10% validation split.

- Model Evaluation:

> Visualize the training process, including accuracy and loss over epochs, to assess the model's learning performance.
> Use the trained model to predict classes on a test set and evaluate its performance using a confusion matrix.


**Usage**

Download the SDSS Tabular Data and add it to your Google Drive at a known location.

Open and run the provided code in a Jupyter environment.


**Two Key Achievements**

- Conducted in-depth analysis and visualization of the SDSS tabular data, gaining insights into the distribution and characteristics of astronomical objects.
- Developed and trained a neural network model for object classification, achieving accurate predictions and providing valuable astronomical insights.
