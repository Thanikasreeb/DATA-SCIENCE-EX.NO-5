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
import numpy as np 
x=np.arange(10,20)
y=np.arange(21,31)
a=np.arange(45,55)
b=np.arange(55,65)
plt.scatter(x,y,c='g')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')

y=x*x
plt.plot(x,y,'r*',linestyle='solid',linewidth=3, markersize=10)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
plt.show()

plt.subplot(3,3,1)
plt.plot(x,y,'r--')
plt.subplot(3,3,2)
plt.plot(x,y,'g*--')
plt.subplot(3,3,3)
plt.plot(x,y,'bo')
plt.subplot(3,3,4)
plt.plot(a,b,'go')
plt.show()

x = np.arange(0,10) 
y = 3 * x + 5 
plt.title("Matplotlib demo") 
plt.xlabel("x axis caption") 
plt.ylabel("y axis caption") 
plt.plot(x,y) 
plt.show()

np.pi
x = np.arange(0, 4 * np.pi, 0.1) 
y = np.sin(x) 
plt.title("cosine wave form") 

# Plot the points using matplotlib 
plt.plot(x, y) 
plt.show()

x = np.arange(0, 5 * np.pi, 0.1) 
y_sin = np.sin(x) 
y_cos = np.cos(x)  
   
# Set up a subplot grid that has height 2 and width 1, 
# and set the first such subplot as active. 
plt.subplot(2, 1, 1)
   
# Make the first plot 
plt.plot(x, y_sin,'r--') 
plt.title('Sine')  
   
# Set the second subplot as active, and make the second plot. 
plt.subplot(2, 1, 2) 
plt.plot(x, y_cos,'g--') 
plt.title('Cosine')  
   
# Show the figure. 
plt.show()

x = [2,4,6] 
y = [4,8,10]  

x2 = [1,3,5] 
y2 = [2,6,8] 
plt.bar(x, y) 
plt.bar(x2, y2, color = 'g') 
plt.title('Bar graph') 
plt.ylabel('Y axis') 
plt.xlabel('X axis')  

plt.show()

a = np.array([22,87,5,43,56,73,55,54,11,20,51,5,79,31,27]) 
plt.hist(a) 
plt.title("histogram") 
plt.show()

data = [np.random.normal(0, std, 100) for std in range(1, 4)]

# rectangular box plot
plt.boxplot(data,vert=True,patch_artist=False);  
plt.show()

data = [np.random.normal(0, std, 100) for std in range(1, 6)]

# rectangular box plot
plt.boxplot(data,vert=True,patch_artist=True);
plt.show()

data

labels = 'Python', 'C++', 'Ruby', 'Java'
sizes = [200, 130, 245, 210]
colors = ['red', 'cyan', 'yellow', 'lightskyblue']
explode = (0.4, 0, 0, 0)  # explode 1st slice

# Plot
plt.pie(sizes, explode=explode, labels=labels, colors=colors,
autopct='%1.1f%%', shadow=False)

plt.axis('equal')
plt.show()
```

# Result:
<img width="763" height="592" alt="image" src="https://github.com/user-attachments/assets/011064f1-9a21-4083-b748-9918178ee704" />

<img width="757" height="582" alt="image" src="https://github.com/user-attachments/assets/054cf3c7-6549-41a1-948c-892b567a5300" />

<img width="757" height="392" alt="image" src="https://github.com/user-attachments/assets/b6dc475c-2dc3-4345-882b-a08a77a837b8" />

<img width="740" height="563" alt="image" src="https://github.com/user-attachments/assets/3e6812f2-cb34-487f-b1ef-55b3fe418178" />

<img width="728" height="535" alt="image" src="https://github.com/user-attachments/assets/5fa57804-7877-4560-9aac-fb0ce62f48f5" />

<img width="731" height="747" alt="image" src="https://github.com/user-attachments/assets/af4a3414-8721-4a11-9883-143761930afc" />

<img width="672" height="505" alt="image" src="https://github.com/user-attachments/assets/54ee4ca5-578e-47f1-ae76-2d59bb1fe3a7" />

Thus Data Visualization using matplot python library for the given datas is performed.
