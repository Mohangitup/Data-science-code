# Data-science-code
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
df=pd.read_csv("D:inten.csv")
df.head()
df.tail()
df.shape
df.info
df.isnull() .sum()
df.isnull() .sum()/df.shape[0]*100
df.duplicated().sum()
df5 = df['Fresh'].value_counts().head(5)
print("\nTop 5 Fresh\n", df5)
df6 = list(df['Fresh'].value_counts().keys())
print("\nList of Fresh\n", df6)
df7 = df['Milk'].value_counts()
print("\nThe frequency of the Milk\n", df7)
df8 = df['Grocery'].value_counts()
print("\nThe number of Grocery for Series reference\n", df8)
plt.figure(figsize=(7, 7))
plt.hist(df['Grocery'])
plt.show()
df9 = df['Frozen'].value_counts()
print("\nThe number of Frozen values\n", df9)
plt.figure(figsize=(7, 7))
plt.bar(list(df['Frozen'].value_counts().head(3).keys()), list(df['Frozen'].value_counts().head(3)), color=['blue', 'orange', 'green'])
plt.show()
plt.figure(figsize=(7, 7))
plt.pie(list(df['Frozen'].value_counts()), labels=list(df['Frozen'].value_counts().keys()), autopct='%0.0f%%')
plt.show()
