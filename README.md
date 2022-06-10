# DSE 200 Final Project
# Horse Racing Odds: Merging Dataframes to Predict Odds on the Racetrack
## Leslie's final project with horse racing data from Kaggle

#### About this project
The purpose of this project for our first quarter Python class was to merge dataframes and use features of both datasets to predict a target, and more importantly to show our approaches and convey our findings in well documented code.

The data I chose was "Triple Crown Races (2005 - 2019)" by Joseph (jmolitoris) on [Kaggle](https://www.kaggle.com/jmolitoris/triple-crown-of-horse-races-2005-2019?select=TripleCrownRaces_2005-2019.csv), and "Horse Racing Data from 1990" by Nikolay Kashavkin (hwaitt) on [Kaggle](https://www.kaggle.com/hwaitt/horse-racing?select=horses_2019.csv), merging along either the names of horse trainers or jockeys. Both resulting dataframes were run through the three machine learning models we learned to use: linear regression, elastic net, and decision tree regressor. The mean square errors (MSE) and coefficients of determinations (r$^2$) were returned as results, which were the determining factors we'd used in class thus far.

While other classes have since taught us other machine learning models, methods of determining model robustness, and following standard organization methods, this project was a good opportunity to show my understanding of Jupyter notebooks and Python code with an emphasis on the pandas, numpy, matplotlib, and seaborn libraries.

The notebook was submitted for school on December 3rd, 2021.

(Note: In the "Final Project_Fall2021.ipynb" notebook, grey font indicates text written by the instructor.)


## Notebook outline

- Finding datasets to use
	- "Triple Crown Races (2005 - 2019)" and "Horse Racing Data from 1990"
		- by Joseph (jmolitoris) and by Nikolay Kashavkin (hwaitt) on Kaggle
		- Listed column descriptions
- Reading in the datasets
	- Read in both datasets twice
	- Once for the trainer name merging and once for the jockey name merging
- Cleaning and understanding the data 
	- Examining the columns
		- Removed unnecessary (duplicate, object, etc) columns for my analysis
		- Converted object types to ints and floats types
		- Removed outliers
		- Graphed distributions and relationships between columns
	- Took note of potential correlations between columns
- Can the odds be predicted with this data?
	- Merging dataframes along trainer or jockey names
		- Performed three times each with differing columns (features) included
	- Setting up the machine learning models
		- Linear regression
		- Elastic net
		- Decision tree regressor
	- Executing the ML models
		- Modeling based on trainer names
		- Modeling based on jockey names
- Observing the results
	- Visual (plotted) observations of the predicted vs actual output
	- Mean squared errors and coefficients of determination
- Conclusions


## How to run:
1. Download this repository
2. Start jupyter lab
3. Run the jupyter notebook "Final Project_Fall2021.ipynb"