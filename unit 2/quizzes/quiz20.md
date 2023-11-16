**QUIZ 020** 

✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 

 
20. Create a function that changes the vowels in a string to numbers such as a=4,e=3,i=1,o=0 and space by _

　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

*code #1*


    import random
    
    def produce(n,m,s):
        random.seed(1234)
        final=[]
        for i in range(n):
    
            x =random.randint(0,101)
            y = ((x **0.5)*(m/s)**2)
            yround=round(y,2)
            test = f"|{str(x):<6}| {str(yround):<6}|"
            final.append(test)
        final1 = '\n'.join(final)
        return final1
    
    result=produce(n=5,m=3,s=2)
    print(result)


*code #2*

    def produce(n, m, s):
        random.seed(1234)
        return '\n'.join(f"|{x:<6}| {y:.2f}|"
                         for x, y in ((random.randint(0, 101), (random.randint(0, 101) ** (1/2* ((m / s) ** 2)))) for _ in range(n)))
    
    result = produce(n=5, m=3, s=2)
    print(result)

#test　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

![](https://github.com/marinamen/CS2023/blob/main/unit%202/quizzes/pictures/Screenshot%202023-11-16%20at%2014.51.57.png)

#flowchart　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦
![](https://github.com/marinamen/CS2023/blob/main/unit%202/quizzes/pictures/quizz20.drawio%20(1).png)
