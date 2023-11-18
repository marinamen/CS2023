**QUIZ 023** 

✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 

 
23. Create a program shows the graph of the function below for 100 values of x in the interval -10 < x < 10   




　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

*code*
```.py
def produce(n,m,s):
    import random
    random.seed(1234)
    x_out=[]
    y_out=[]
    z='|        x        |       y(x)        |\n'.center(10)
    for i in range(100):
        x=-10+0.2*i
        x_out.append(x)
        y=abs(x).__round__(2)
        y_out.append(y)
        z+=(f"|   {str(x).center(10)}    |    {str((y).__round__(2)).center(10)}     |\n").center(10)
    return y_out,x_out
data_y,data_x=produce(n=100,m=3,s=2)
from matplotlib import pyplot as plt
plt.plot(data_x,data_y,color="lightpink",marker="*")
plt.ylabel("$y=|x|$ absolute value")
plt.xlabel("variable X")
plt.show()
```

#part b　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

*Convert to decimal*
**FFA5**


<img src="https://github.com/marinamen/CS2023/blob/main/unit%202/quizzes/pictures/23.jpeg" width=35% height=35%>

#test　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

![](https://github.com/marinamen/CS2023/blob/main/unit%202/quizzes/pictures/Screenshot%202023-11-18%20at%2014.14.57.png)

#flowchart　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦
![](https://github.com/marinamen/CS2023/blob/main/unit%202/quizzes/pictures/quiz017.jpg)
