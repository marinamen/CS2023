**QUIZ 024** 

✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 

 
24. Create a program that ① show the graph and ②create a linear (H_model = m*t+b) for the data below:

***h = [57.0, 56.0, 57.0, 56.0, 55.0, 55.0, 54.0, 54.0, 54.0, 53.0, 53.0, 54.0, 53.0, 53.0, 52.0, 52.0, 51.0, 51.0, 51.0, 50.0, 50.0, 49.0, 50.0, 49.0, 49.0, 48.0, 49.0, 49.0, 48.0, 48.0, 48.0, 49.0]*** 




　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

*code*

```.py
import numpy as np
from matplotlib import pyplot as plt
x_model=[]
h = [57.0, 56.0, 57.0, 56.0, 55.0, 55.0, 54.0, 54.0, 54.0, 53.0, 53.0, 54.0, 53.0, 53.0, 52.0, 52.0, 51.0, 51.0, 51.0, 50.0, 50.0, 49.0, 50.0, 49.0, 49.0, 48.0, 49.0, 49.0, 48.0, 48.0, 48.0, 49.0]
for i in range(len(h)):
    x_model.append(i)
plt.scatter(x_model,h,color="plum")
plt.ylabel("variable y stinkbugs in r1-10")
plt.xlabel("variable x temperature in degreees celsius")
m,b=np.polyfit(x_model,h,1)
print(f"Linear equation is y={m:.2f}x+({b:.2f})")
y_model=[]
plt.ylabel("relative humidity %")
plt.xlabel("samples")
for i in x_model:
    y_model.append(m*i+b)
plt.plot(x_model,y_model,color="lightpink")
plt.show()
```

#part b　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

*Convert the following color in hex to rgb*

**#e6e627**
<img src="https://github.com/marinamen/CS2023/blob/main/unit%202/quizzes/pictures/Screenshot%202023-11-18%20at%2014.37.42.png" width=20% height=20%>


<img src="https://github.com/marinamen/CS2023/blob/main/unit%202/quizzes/pictures/24.jpeg" width=30% height=30%>


#test　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

![](https://github.com/marinamen/CS2023/blob/main/unit%202/quizzes/pictures/Screenshot%202023-11-18%20at%2013.31.22.png)
#flowchart　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦
![](https://github.com/marinamen/CS2023/blob/main/unit%202/quizzes/pictures/quiz017.jpg)
