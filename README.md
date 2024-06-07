# datafun-06-eda
This project preforms an exploratory data analysis of a dataset found in the pandas library.

## Create Project Virtual Environment and update pip and install requests

On mac, create a project virtual environment in the .venv folder. 

''' zsh
python3 -m venv .venv
cd documents/data_analytics/datafun-04-jupyter/.venv/bin
source activate
touch requirements.txt
python3 -m pip install -r requirements.txt
python3 -m pip install jupyterlab numpy pandas matpotlib seaborn scipy
python3 -m pip freeze > requirements.txt
mkdir .gitignore
'''
add lines .venv/, .vscode/, and .ipynb_checkpoints/ to .gitignore file

## Git add and commit

'''zsh
git add .
git commit -m "add .gitignore, cmds to readme"
git push origin main
'''

## Data to Explore
I chose the [mpg data set](https://github.com/charlietodd11/datafun-06-eda/blob/main/data/mpg.csv) from seaborn. I created a folder in my root project folder called data. I downloaded the csv file for mpg there. MPG data has 9 columns: miles per gallon, cylinders, displacement, horsepower, weight, acceleration, model year, origin, and name. There are 398 entries. 

## Goals of this Exploratory Analysis

First I want to determine what country has more fuel effiecent cars. Next I want to determine if there is a clear varialbe that influences that countries fuel efficency. 

### Data Acquisition, Initial Data inspection, and Inital Descriptive Statistics

Define dataframe from the seaborn library labled 'mpg' and print the first few rows. Next print the first ten rows and check the shape of the data and the different category types. Finally determine the summary statistics of the dataset. 

### Initial Data Distribution for Numerical Columns and for Categorical Columns. 

Create histograms for each numerical column and countplots for each categorical column. 

### Initial Visualization

I created pair plots to check correlation, then scatter plots specified to country, and finally line plots specified to country. 

## Specification
'''
This project was built to the following specification:

- [datafun-06-spec](https://github.com/denisecase/datafun-06-spec)
'''
