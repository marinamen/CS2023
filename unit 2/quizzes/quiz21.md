**QUIZ 021** 

✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 

 
21. Create a program that produces the graph for the function in Quiz #22 

　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

*code*
```.py
     import random
     import matplotlib.pyplot as plt
     import numpy as np
     def produce(n, m, s):
         random.seed(1234)
         x_values = []
         y_values = []
         for i in range(n):
             x = random.randint(0, 101)
             y = x ** 0.5 * ((m / s) ** 2)
             y_rounded = round(y, 2)
             x_values.append(x)
             y_values.append(y_rounded)
         return x_values, y_values
     
     x, y = produce(n=10, m=5, s=2)
     z = np.polyfit(x, y, 1)
     p = np.poly1d(z)
     plt.plot(x, p(x),color = "purple")
     plt.plot(x,y,color="lightpink",marker="*")
     plt.ylabel("$y=x^{1/2(m/s)^2}$")
     plt.xlabel("Variable X")
     plt.show()
 
```



#part b　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

*Truth table for:*

**A(A ⊕ B)**


<img src="https://github.com/marinamen/CS2023/blob/main/unit%202/quizzes/pictures/21.jpeg" width=60% height=60%>


   

#test　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

![](https://github.com/marinamen/CS2023/blob/main/unit%202/quizzes/pictures/Screenshot%202023-11-18%20at%2013.11.33.png)

#flowchart　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦
![](https://github.com/marinamen/CS2023/blob/main/unit%202/quizzes/pictures/quiz21.drawio.png)
