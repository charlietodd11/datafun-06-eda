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
## add lines .venv/, .vscode/, and .ipynb_checkpoints/ to .gitignore file

## Git add and commit

'''zsh
git add .
git commit -m "add .gitignore, cmds to readme"
git push origin main
'''

## Data to Explore
I chose the mpg data set from seaborn. I created a folder in my root project folder called data. I downloaded the csv file for mpg there. MPG data has 9 columns: miles per gallon, cylinders, displacement, horsepower, weight, acceleration, model year, origin, and name. There are 399 entries. 

## Specification
'''
This project was built to the following specification:

- [datafun-06-spec](https://github.com/denisecase/datafun-06-spec)
'''
