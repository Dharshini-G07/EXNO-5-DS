# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:

```
 import pandas as pd
 import numpy as np
 import seaborn as sns
 import matplotlib.pyplot as plt
 marks=[13,45,63,78]
 student=['ABC','QOR','EFB','TOB']
 plt.plot(marks,student)
 plt.xlabel('Marks')
 plt.ylabel('Student name')
 plt.show()
 student=['A','B','C','D']
 attendence=[90,85,73,88]
 plt.plot(attendence,student)
 plt.xlabel('Attendence')
 plt.ylabel('Student name')
 plt.show()
```

<img width="865" height="543" alt="image" src="https://github.com/user-attachments/assets/21aa87a1-284d-4140-8393-76527cc9cd61" />
<img width="827" height="555" alt="image" src="https://github.com/user-attachments/assets/5c869e7d-1187-4c55-9309-65614bc3aed5" />

```
x=[10,20,30,40,50]
 y=[100,200,300,400,500]
 plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
 plt.show()
 x=np.arange(0,15)
 y=np.arange(0,15)
 x
 y
 plt.scatter(x,y,c='r')
 plt.xlabel('X axis')
 plt.ylabel('y axis')
 plt.title('Scatter plot')
 plt.show()
```
<img width="723" height="516" alt="image" src="https://github.com/user-attachments/assets/33ca88c7-653f-4a0a-bfa2-3abdacff3fb0" />
<img width="749" height="572" alt="image" src="https://github.com/user-attachments/assets/cc820aa6-705c-4a3f-80b2-b60be7225ec8" />

```
 act=['eat','sleep','work','play']
 slices=[3,7,8,6]
 color=['r','y','g','b']
 plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.legend()
 plt.show()
 feedback=['Good','excellent','Perfect','Ok']
 slices=[4,10,3,8]
 color=['y','r','b','g']
 plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.legend()
 plt.show()
```

<img width="634" height="516" alt="image" src="https://github.com/user-attachments/assets/7bd103da-7e65-4b15-bf4b-8f99c728f745" />
<img width="643" height="507" alt="image" src="https://github.com/user-attachments/assets/2d6b2ab1-bd3c-4556-8629-9458db814d1b" />


```
 x = [1, 2, 3, 4, 5]
 y1 = [10, 12, 14, 16, 18]
 y2 = [5, 7, 9, 11, 13]
 y3 = [2, 4, 6, 8, 10]
 plt.fill_between(x, y1, color='blue')
 plt.fill_between(x, y2, color='green')
 plt.plot(x, y1, color='red')
 plt.plot(x, y2, color='black')
 plt.legend(['y1','y2'])
 plt.show()
```

<img width="728" height="513" alt="image" src="https://github.com/user-attachments/assets/50b5ff1c-f060-4d72-a54c-510d89e9bb74" />

```
 height = [10, 24, 36, 40, 5]
 names = ['one', 'two', 'three', 'four', 'five']
 c1=['red', 'green'] 
 c2=['b', 'g']
 plt.bar (names, height, width=0.8, color=c1)
 plt.xlabel('x - axis')
 plt.ylabel('y - axis')
 plt.title('My bar chart!')
 plt.show()
```
<img width="782" height="558" alt="image" src="https://github.com/user-attachments/assets/c27ce1ce-c16f-4c82-99a4-3700c4e6ec76" />

```
 x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
 plt.hist(x, bins = 10, color='blue', alpha=0.5)
 plt.show()
```

<img width="697" height="530" alt="image" src="https://github.com/user-attachments/assets/f5d848b1-641c-4260-9fd7-36822c4d0377" />

```
 np.random.seed(0)
 data=np.random.normal(loc=0, scale=1, size=100)
 data
```
<img width="666" height="435" alt="image" src="https://github.com/user-attachments/assets/b36c69dd-6952-48db-96d0-5996c53d779a" />

```
 fig, ax= plt.subplots()
 ax.boxplot(data)
 ax.set_xlabel('Data')
 ax.set_ylabel('Values')
 ax.set_title('Box Plot')
```
<img width="762" height="602" alt="image" src="https://github.com/user-attachments/assets/2f3ecd3f-1bbe-422b-8084-7df768433334" />







# Result:
 Thus the program is executed successfully.
