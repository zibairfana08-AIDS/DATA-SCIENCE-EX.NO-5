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
import matplotlib.pyplot as plt
x = [0,1,2,3,4,5]
y = [0,1,4,9,16,25]
plt.plot(x,y)
plt.show()
```
<img width="554" height="422" alt="image" src="https://github.com/user-attachments/assets/66a3c901-c3ba-4a59-9307-324a3f179dab" />

```
import matplotlib.pyplot as plt
x = [1,2,3]
y = [2,4,1]
plt.plot(x,y)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My first graph!')
plt.show()
```

<img width="583" height="451" alt="Screenshot 2026-03-29 000724" src="https://github.com/user-attachments/assets/8084e5af-441a-4c01-9f56-c15ced278a30" />

```
import matplotlib.pyplot as plt
x1 = [1,2,3]
y1= [2,4,1]
plt.plot(x1,y1,label="line 1")
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label="line 2")
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()
```

<img width="609" height="458" alt="image" src="https://github.com/user-attachments/assets/b783e813-8957-47ee-8d06-b7fb04ed175f" />

```
import matplotlib.pyplot as plt
x = [1,2,3,4,5,6]
y = [2,4,1,5,2,6]
plt.plot(x,y,color='green', linestyle='dashed', linewidth= 3,
        marker='o', markerfacecolor='blue', markersize=12)
plt.ylim(1,8)
plt.xlim(1,8)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('some cool customizations!')
plt.show()
```

<img width="569" height="449" alt="image" src="https://github.com/user-attachments/assets/c1843411-8c20-47e0-8185-0c403ea6d856" />

```
yield_apples = [0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```

<img width="567" height="448" alt="image" src="https://github.com/user-attachments/assets/6334eaf6-af32-4b1e-8692-3ce8f43b205d" />

```
years = [2010,2011,2012,2013,2014,2015]
yield_apples = [0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)
```

<img width="581" height="449" alt="image" src="https://github.com/user-attachments/assets/3aa6be41-4447-4724-9747-32bbb47cdf54" />

```
years = range(2000,2012)
apples = [0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges = [0.926,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896]
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('year')
plt.ylabel('Yeild (tons per hectare)')
plt.title('Crop Yields in  Kanto')
plt.legend(['Apples','Oranges']);
```

<img width="616" height="305" alt="image" src="https://github.com/user-attachments/assets/5bd3d1ba-3e9a-4b2a-9ed0-980392dc92f4" />

```
plt.plot(years,apples)
plt.xlabel('Year')
plt.ylabel('Yeild (tons per hectare)');
```

<img width="640" height="435" alt="image" src="https://github.com/user-attachments/assets/b6fd01eb-6111-4b9b-bd2c-4cc22529443b" />

```
plt.figure(figsize=(12,6))
plt.plot(years,oranges,marker='o')
plt.title("Yield of oranges(tons per hectare)");
```

<img width="816" height="297" alt="image" src="https://github.com/user-attachments/assets/6d0fcc1d-d709-44ad-ae98-0e22230dc9d3" />

```
import matplotlib.pyplot as plt
x = [0,1,2,3,4,5]
y = [0,1,4,9,16,25]
plt.scatter(x,y,s=30,color='blue')
plt.show()
```

<img width="580" height="406" alt="image" src="https://github.com/user-attachments/assets/858d5b48-2416-492e-b7b3-ee7b6b9f7b3e" />

```
import matplotlib.pyplot as plt
x = [1,2,3,4,5,6,7,8,9,10]
y = [2,4,5,7,6,8,9,11,12,12]
plt.scatter(x,y,label="stars",color="green",marker="*",s=30)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My scatter graph!')
plt.legend()
plt.show()
```

<img width="648" height="439" alt="image" src="https://github.com/user-attachments/assets/206a2090-e216-4ce4-98ae-2f8b1a1d2d61" />


```
import matplotlib.pyplot as plt
import pandas as pd
import numpy as np
x=np.arange(0,10)
y=np.arange(11,21)
x
```

<img width="337" height="35" alt="image" src="https://github.com/user-attachments/assets/9063f235-196c-4308-8221-5cad511430bd" />

```
y
```

<img width="368" height="43" alt="image" src="https://github.com/user-attachments/assets/5d56ef86-79cb-476b-af17-de09e1b47d6d" />

```
plt.scatter(x,y,c='r')
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```

<img width="578" height="439" alt="image" src="https://github.com/user-attachments/assets/808165d7-e397-4d03-bf88-a41ce896206e" />

```
y=x*x
y
```

<img width="355" height="30" alt="image" src="https://github.com/user-attachments/assets/7271aa58-f2b2-4d55-b4a0-9507fea48614" />

```
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('2D Diagram')
```

<img width="609" height="479" alt="image" src="https://github.com/user-attachments/assets/d646077a-0bf3-4c5b-851c-9c0b4d65f78a" />

```
plt.subplot(2,2,1)
plt.plot(x,y,'r--')
plt.subplot(2,2,2)
plt.plot(x,y,'g*--')
plt.subplot(2,2,3)
plt.plot(x,y,'bo')
plt.subplot(2,2,4)
plt.plot(x,y,'go')
```

<img width="574" height="443" alt="image" src="https://github.com/user-attachments/assets/e2ea0f3f-2d60-41a7-9ff2-792c3110ca11" />

```
np.pi
```

<img width="151" height="32" alt="image" src="https://github.com/user-attachments/assets/474d675a-e33f-4561-b05d-98efd85a0963" />

```
x = np.arange(0,4* np.pi,0.1)
y = np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```

<img width="606" height="441" alt="image" src="https://github.com/user-attachments/assets/2999697d-c96c-4d6e-a47a-b888e2ad16d3" />

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

<img width="562" height="411" alt="image" src="https://github.com/user-attachments/assets/18dbf746-93ae-48f6-b9ce-102e6464d83d" />

```
plt.stackplot(x,y1,y2,y3,labels=['Line1','Line2','Line3'])
plt.legend(loc='upper left')
plt.title('Stacked Line Chart')
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.show()
```

<img width="624" height="445" alt="image" src="https://github.com/user-attachments/assets/a0885fb9-4391-4279-8609-661d978ef16b" />

```
import matplotlib.pyplot as plt
values=[5,6,3,7,2]
names=["A","B","C","D","E"]
plt.bar(names,values,color="green")
plt.show()
```

<img width="560" height="414" alt="Screenshot 2026-03-29 002212" src="https://github.com/user-attachments/assets/1bb61059-2efb-4142-8654-c2a534a9cda4" />

```
import matplotlib.pyplot as plt
values=[5,6,3,7,2]
names=["A","B","C","D","E"]
plt.barh(names,values,color="yellowgreen")
plt.show()
```

<img width="552" height="416" alt="image" src="https://github.com/user-attachments/assets/49384d93-35c2-45c3-9934-fbfe72ca6628" />

```
import matplotlib.pyplot as plt
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My bar chart!')
plt.show()
```

<img width="599" height="452" alt="image" src="https://github.com/user-attachments/assets/5edfe97c-e4d5-4bad-a6ca-25f0ae94f3c1" />

```
x = [2,8,10]
y = [11,16,9]
x2 = [3,9,11]
y2 = [6,15,7]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.show()
```

<img width="617" height="434" alt="image" src="https://github.com/user-attachments/assets/57891505-b002-4494-b096-cf63bd3b6230" />

```
import matplotlib.pyplot as plt
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range = (0,100)
bins = 10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No. of people')
plt.title('My histogram')
plt.show()
```

<img width="607" height="444" alt="image" src="https://github.com/user-attachments/assets/b61877c3-138f-4976-b508-dfcd762f9cdc" />

```
import matplotlib.pyplot as plt
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x,bins = 10,color = 'blue',alpha=0.5)
plt.show()
```

<img width="538" height="405" alt="image" src="https://github.com/user-attachments/assets/fde78f9e-9218-431e-a732-d4c83ebd052a" />

```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(10)
data = np.random.normal(loc=0,scale=1,size=100)
data
```

<img width="536" height="350" alt="image" src="https://github.com/user-attachments/assets/9c4fe98e-17c6-40b8-b482-8ce19653bea4" />












# Result:
 Include your result here
