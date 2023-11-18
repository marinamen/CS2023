**QUIZ 022** 

✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 

 
22.  Create a program shows the graph of the parabola for 100 values of x in the interval -10 < x < 10   
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

*code*
```.py
from matplotlib import pyplot as plt
def produce():
    x_out=[]
    y_out=[]
    for n in range(-10,11):
        x_out.append(n)
        yres=2*((n+5)**2)
        y_out.append(yres)
    return x_out,y_out
plt.style.use("ggplot")
x,y= produce()
plt.plot(x,y,color="lightpink")
plt.show()

```
#part b　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

*Circuit for:*

**not(bit0 bit1 + not (bit0 + bit1))**


<img src="https://github.com/marinamen/CS2023/blob/main/unit%202/quizzes/pictures/22.jpeg" width=50% height=50%>



#test　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

![](https://github.com/marinamen/CS2023/blob/main/unit%202/quizzes/pictures/Screenshot%202023-11-18%20at%2013.12.34.png)

#flowchart　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦
![](https://github.com/marinamen/CS2023/blob/main/unit%202/quizzes/pictures/quiz017.jpg)
