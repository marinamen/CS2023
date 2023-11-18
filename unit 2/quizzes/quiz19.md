**QUIZ 019** 

✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 

 
19. Using the function that produces the table of Truth for 3 inputs, add a column for the boolean equation
AB+(not B)+not(CB)


　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

*code*
```.py
    def get_truth2():
        print("A | B | C | Boolean")
    
        input = [0, 1]
        for a in input:
            for b in input:
                for c in input:
                    boolean = (a and b or (not b)) or not(c and b)
                    print(f"{a} | {b} | {c} |   {int(boolean)}")
    
    get_truth2()
```

#part b　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

*b.Truth table and circuit for:*

**X = ZW ⨁ (Z ⨁ Y(not W))**


![](https://github.com/marinamen/CS2023/blob/main/unit%202/quizzes/pictures/19.jpeg)

 
#test　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

![](https://github.com/marinamen/CS2023/blob/main/unit%202/quizzes/pictures/Screenshot%202023-11-09%20at%2000.56.38.png)

#flowchart　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦
![](https://github.com/marinamen/CS2023/blob/main/unit%202/quizzes/pictures/quiz019.drawio.png)
