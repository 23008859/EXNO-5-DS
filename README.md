
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
## Name:Roshini.S
## Reg.No:21223230174
```
import matplotlib.pyplot as plt
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label='line1')
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label='line2')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()
```

![image](https://github.com/23008859/EXNO-5-DS/assets/139117979/bc50a1b1-f105-44e8-9e45-cb114258821f)
```
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations!')
plt.show()
```

![image](https://github.com/23008859/EXNO-5-DS/assets/139117979/df657ddf-2496-4e9e-8b69-c9ef964a2190)
```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```

![image](https://github.com/23008859/EXNO-5-DS/assets/139117979/70ede198-dcea-4139-8d0e-7ec735aa16c3)
```
years=[2010,2011,2012,2013,2014,2015]
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)
```

![image](https://github.com/23008859/EXNO-5-DS/assets/139117979/22b77a4f-a6a1-48c1-8658-14865445c93a)
```
years=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.926,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896, ]
plt.plot(years, apples)
plt.plot(years, oranges)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title('Crop Yields in Kanto')
plt.legend(['Apples','Oranges']);
```

![image](https://github.com/23008859/EXNO-5-DS/assets/139117979/bdeb3927-e84e-42f6-b7ca-4894e295cb77)
```
plt.figure(figsize=(12,6))
plt.plot(years,oranges,marker='o')
plt.title("Yield of Oranges (tons per hectare)");
```

![image](https://github.com/23008859/EXNO-5-DS/assets/139117979/16a3e4c7-2684-4169-8742-86ce21df3ab0)
```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x
```

![image](https://github.com/23008859/EXNO-5-DS/assets/139117979/860970ce-2396-4e59-a8bd-b71f5784aa76)
```
y
```

![image](https://github.com/23008859/EXNO-5-DS/assets/139117979/823406b3-e98c-4104-9664-f236ba73e376)
```
plt.scatter(x,y,c='r')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```

![image](https://github.com/23008859/EXNO-5-DS/assets/139117979/b1b09bdb-0453-4da7-9153-671b907461a9)
```
y=x*x
y
```

![image](https://github.com/23008859/EXNO-5-DS/assets/139117979/2e077082-f8f2-4531-8bf2-a55149ae889c)
```
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
```

![image](https://github.com/23008859/EXNO-5-DS/assets/139117979/6d4d38cb-5c13-42a9-835c-d974482316cc)
```
np.pi
```

![image](https://github.com/23008859/EXNO-5-DS/assets/139117979/0667d595-cb9e-4394-857a-5a8510f5bda7)
```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```

![image](https://github.com/23008859/EXNO-5-DS/assets/139117979/97735247-4dd3-4a15-95c8-4ee54cba95b5)
```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')
```

![image](https://github.com/23008859/EXNO-5-DS/assets/139117979/f0e076f3-c781-48d7-bcc4-33077f6ca268)
```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')

plt.plot(x,y1,color='red')
plt.plot(x,y2,color='black')
plt.legend(['y1','y2'])
plt.show()
```

![image](https://github.com/23008859/EXNO-5-DS/assets/139117979/07e336bc-0ba6-4f83-b967-8e7cc50a079e)
```
import matplotlib.pyplot as plt
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My bar chart!')
plt.show()
```
 ![image](https://github.com/23008859/EXNO-5-DS/assets/139117979/d69abaa1-7a2e-4bd0-be42-dd0b78ee2d4e)
 ```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('X axis')
plt.show()
```
![image](https://github.com/23008859/EXNO-5-DS/assets/139117979/c7bb4c39-2782-419e-a8fb-b77a65dac9f9)
```
import matplotlib.pyplot as plt
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No. of people')
plt.title('My histogram')
plt.show()
```
![image](https://github.com/23008859/EXNO-5-DS/assets/139117979/9b30c724-526b-4cd5-882c-232c46efa06a)
```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
![image](https://github.com/23008859/EXNO-5-DS/assets/139117979/c4252b4f-500d-43c2-a455-9edd613ac146)
```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```
![image](https://github.com/23008859/EXNO-5-DS/assets/139117979/08795dea-f950-46eb-80d2-38b0a0eb93bc)
```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```
![image](https://github.com/23008859/EXNO-5-DS/assets/139117979/c17f9466-a806-4f7c-8f49-176766a4c5c7)
```
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
```
![image](https://github.com/23008859/EXNO-5-DS/assets/139117979/342d115e-20ba-4c7a-bceb-14f24934501d)

# Result:
Thus, The implementation of data visualization using matplotlib has been successfully verified.


