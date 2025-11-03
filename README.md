# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

### NAME : Naveenkumar M

### REG.NO:212224230183

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

```

<img width="1053" height="744" alt="image" src="https://github.com/user-attachments/assets/3f6d443e-2c67-4238-ad01-87da480bb7f1" />

```

student=['A','B','C','D']
attendence=[90,85,73,88]
plt.plot(attendence,student)
plt.xlabel('Attendence')
plt.ylabel('Student name')
plt.show()

```

<img width="1095" height="720" alt="image" src="https://github.com/user-attachments/assets/28117fb4-cc94-42cc-9f58-95a918425062" />

```

x=[10,20,30,40,50]
y=[100,200,300,400,500]
plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
plt.show()

```

<img width="1041" height="639" alt="image" src="https://github.com/user-attachments/assets/6c37af42-6c7b-496d-a4d6-e3dacd1eae9b" />

```

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
<img width="1297" height="785" alt="image" src="https://github.com/user-attachments/assets/2da36759-9bd5-4183-b46c-6119a7565307" />


```
act=['eat','sleep','work','play']
slices=[3,7,8,6]
color=['r','y','g','b']
plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()

```

<img width="1393" height="701" alt="image" src="https://github.com/user-attachments/assets/8865149d-52df-4839-b249-002db16e7c33" />

```

feedback=['Good','excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['y','r','b','g']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()

```

<img width="1473" height="682" alt="image" src="https://github.com/user-attachments/assets/bdb70646-dd81-472d-9f25-8b6664598a54" />

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

<img width="1253" height="773" alt="image" src="https://github.com/user-attachments/assets/269e019c-3d1d-495c-b391-0c4e4f75c18a" />

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

<img width="963" height="605" alt="image" src="https://github.com/user-attachments/assets/41bb5a77-9b28-47e2-8d80-de36768017ba" />

```

x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='blue', alpha=0.5)
plt.show()

```

<img width="869" height="631" alt="image" src="https://github.com/user-attachments/assets/089ee989-1b4c-44b0-b143-94e4229e1d95" />

```

np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=100)
data

```
<img width="917" height="547" alt="image" src="https://github.com/user-attachments/assets/1a42c6e6-9036-4494-9447-195a4eb34b09" />


```

fig, ax= plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')

```

<img width="1069" height="743" alt="image" src="https://github.com/user-attachments/assets/9cfe479d-85d2-428f-803a-712888dd3b0b" />


# Result:

 Thus, all the data visualization techniques of matplotlib has been implemented.
