## Ex.No:5 Data Visualization using Matplot Library
### Date : 
### Name : Bala R
### Reg No : 212222220007
## Aim:
  To Perform Data Visualization using matplot python library for the given datas.

## Explanation
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

## Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

## Coding and Output:
```
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.plot(x_values,y_values)
plt.show()
```

![image](https://github.com/23005529/EXNO-5-DS/assets/139842207/8a24b518-3d79-4182-8707-bc8d6096065c)

```
import matplotlib.pyplot as plt
x=[1,2,3]
y=[2,4,1]
plt.plot(x,y)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My first graph!')
plt.show()
```

![image](https://github.com/23005529/EXNO-5-DS/assets/139842207/7a07beca-2b88-4783-bc07-020d33dc0533)

```
import matplotlib.pyplot as plt
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label="line 1")
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label="line 2")
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()
```

![image](https://github.com/23005529/EXNO-5-DS/assets/139842207/e831fb62-ad2d-461e-aae9-875e9bc28dd3)

```
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.ylim(1,8)
plt.xlim(1,8)

plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations!')

plt.show()

```
![image](https://github.com/23005529/EXNO-5-DS/assets/139842207/7cd022bd-7a45-490b-a616-a57b019f96f6)

```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```

![image](https://github.com/23005529/EXNO-5-DS/assets/139842207/177c05a5-8dd5-4bd1-aa80-07e77f6648b4)

```
years=[2010,2011,2012,2013,2014,2015]
yeild_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yeild_apples)
```
![image](https://github.com/23005529/EXNO-5-DS/assets/139842207/121d63bb-e1e1-4301-b819-0ea4b96c747a)

```
years=range(2000,2012)
apples= [0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896,]
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)');
```

![image](https://github.com/23005529/EXNO-5-DS/assets/139842207/70bbf070-142b-4fda-8750-832a8b5e7402)

```
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)')
plt.title("Crop Yeilds in Kanto")
plt.legend(['Apples','Oranges']);
```

![image](https://github.com/23005529/EXNO-5-DS/assets/139842207/7c94f797-e747-475e-a2fc-f1ff80f9d787)

```
years=[2010,2011,2012,2013,2014,2015]
yeild_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yeild_apples)
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)');
```

![image](https://github.com/23005529/EXNO-5-DS/assets/139842207/66f4e60f-5f42-4ed1-9aef-de7bf5556623)

```
years=range(2000,2012)
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896,]
plt.figure(figsize=(12,6))
plt.plot(years,oranges,marker='o')
plt.title("Yeild of Oranges (tons per hectare)");
```

![image](https://github.com/23005529/EXNO-5-DS/assets/139842207/51621de6-03f6-457d-860d-7d36d213fe32)

```
plt.plot(years,apples,marker='o')
plt.plot(years,oranges,marker='x')
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)')
plt.title("Crop Yeilds in Kanto")
plt.legend(['Apples','Oranges']);
```

![image](https://github.com/23005529/EXNO-5-DS/assets/139842207/a1ae17bb-1556-48c0-b1e9-68f4f54dfdd8)

```
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.scatter(x_values,y_values,s=30,color="blue")
plt.show()
```
![image](https://github.com/23005529/EXNO-5-DS/assets/139842207/065336f1-ab58-4c09-b6ef-5ad99bd0cca6)

```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x
```
array([0, 1, 2, 3, 4, 5, 6, 7, 8, 9])

```
y
```
array([11, 12, 13, 14, 15, 16, 17, 18, 19, 20])
```
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```
![image](https://github.com/23005529/EXNO-5-DS/assets/139842207/5cb6585d-8fad-4e30-a068-7dc61df0a6f2)
```
y=x*x
y
```
array([ 0, 1, 4, 9, 16, 25, 36, 49, 64, 81])
```
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
```
![image](https://github.com/23005529/EXNO-5-DS/assets/139842207/d1725ad8-9d89-4fe9-8d8b-d7df1e6d9501)

```
np.pi
```
3.141592653589793
```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```
![image](https://github.com/23005529/EXNO-5-DS/assets/139842207/98151d35-ad81-4589-9f43-aab91931aadd)

```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color="blue")
plt.fill_between(x,y2,color="green")
plt.plot(x,y1,color="red")
plt.plot(x,y2,color="black")
plt.legend(['y1','y2'])
plt.show()
```
![image](https://github.com/23005529/EXNO-5-DS/assets/139842207/c615d908-79c3-4885-8bd1-f116bdd278d7)

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
![image](https://github.com/23005529/EXNO-5-DS/assets/139842207/d0d94e70-0f69-4ba2-955a-7b9b351d4cab)

## PIE CHART
```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,
autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```
![image](https://github.com/23005529/EXNO-5-DS/assets/139842207/5b704e3a-08d9-4443-9692-16d26d138a11)
```
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,
        startangle=90,shadow=True,explode=(0,0,0.1,0),
        radius=1.2,autopct='%1.1f%%')
plt.legend()
```
![image](https://github.com/23005529/EXNO-5-DS/assets/139842207/a5d2c9f6-74fd-4988-b9bb-9bd20831eebd)

## Result:
Thus to Perform Data Visualization using matplot python library for the given datas is successful.
