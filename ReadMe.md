The following is the description of the various csv files and Jupyter Notebooks included in this folder.

csv files
1. Crime_Data - Original Charlottesville Crime Dataset
2. weather_cho - The weather data of charlottesville city obtained from NOAA NCEI
3. The Final Dataset that contains the joined data from the above two csv files and also contains Holidays data. This dataset is obtained by running the jupyter notebook "Creating_Dataset"

Jupyter Notebooks
1. Creating_Dataset - Creates the final dataset and writes it into a csv file, by adding additional features related to weather and holidays to the original crime dataset
2. CharlottesvilleCrimeAnalysis - Contains the initial analysis on the original dataset and the final analysis on the additinal features added
3. PredictionUsingDrop - Contains code related to data pre-processing and running the 6 machine learning classification algorithms. This code handles missing data by dropping the records having missing values
4. PredictionUsingFill - Similar to the baove notebook, this notebook contains code related to data pre-processing and running the 6 machine learning classification algorithms. But, this code handles missing data by replacing it with the mean of the column.

The Jupyter Notebooks have further comments on what each function or part of the code does.