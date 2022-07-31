# EstimationOfPhotometricRedshiftUsingDL
The objective of the project is to find the Photometric Redshift from the data extracted from SDSS server. Data is extracted from server through SQL. The extracted data is sampled with many machine learning and deep learning-based algorithms to calculate the best accurate photometric redshift values.

# Requirements
- Python3
- Jupyter Notebook
- Python packages required are numpy, panda, tensorflow, livelossplot, matplotlib...etc (Others mentioned in the respective Jupyter notebooks)

# Procedure
- Download the train set by using the SQL wih z-value from SQL redshift text file
- Transform the redshift dataset using "Adjacent_mean_calculation [train].ipynb"
- Low dataset can be run in decisionTree, kNN, ann_lowz Jupyter notebook files
- Download the high-range redshift datasets from different Data releases from SDSS and use "Combining datasets.ipynb" to combine all the datasets into one
- For downloading the test dataset run the SQL without z-value from SQL redshift text file
- High redshifts train datasets can be run in "ann_highz.ipynb" and high redshift train and test datasets can be used in "ann2_Z_prediction_modified.ipynb".
- All the datasets are named in such a way for easy understanding and the same are used in the python files