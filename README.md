# Read-from-CSV

## AIM:
To write a program to read from csv

## ALGORITHM:
### Step 1:
load the csv into a data frame
### Step 2:
print the number of contents to be displayed using df.head()
### Step 3:
the number of rows returened is defined in pandas option settings
### Step 4:
check your systems maximum colum with the pd.options.display.max_colums statement
### Step 5:
increase the maximum number of rows to display the entire data frame 

## PROGRAM:
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print("number of colum ",len(df.axes[0]))
print("number of rows),len(df.axes[1]))
## OUTPUT:
![k1](https://user-images.githubusercontent.com/94166007/153749078-039e1d93-34c4-4f84-9cf8-1fe57d6804ac.PNG)

## RESULT:
thus the program runs successfully
