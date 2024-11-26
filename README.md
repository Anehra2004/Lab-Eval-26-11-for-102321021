# Lab-Eval-26-11-for-102321021
Lab evaluation 
#Q2 part a 
import pandas as pd

data={ 'House':['Avalon','Cross Winds','The White House','The Rectory',
'Larchwood','Orchard House'],
'Sale Price(100$)':[2050,2080,2150,2150,1999,1900],
'Size(sqft0':[2650,2600,2554,2921,2580,2580],
'Age(yeras)':[13,'*',6,3,4,4]}

df=pd.DataFrame(data)
print(df)

#Q2 part b 
print("The Answer to the part is\n",df.iloc[2:3])

#Q1 PART A
import pandas as pd
df=pd.read_csv('concrete.csv')
print(df)
data=df.drop(6)
print(data.head())
