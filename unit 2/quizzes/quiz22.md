**QUIZ 022** 

✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 

 
22. Create a function that changes the vowels in a string to numbers such as a=4,e=3,i=1,o=0 and space by _

　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

*code*

    def get_l3tt3r(input):

    vowelrep = {'a': '4', 'e': '3', 'i': '1', 'o': '0', 'u': '5'}
    result = ""

    for char in input:
        if char.lower() in vowelrep:
            result+=vowelrep[char.lower()]
        elif char ==' ':
            result+='_'
        else:
            result+=char

    return result

    input="Hello World"
    output=get_l3tt3r(input)
    print(output)

#test　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

![](https://github.com/marinamen/CS2023/blob/main/unit%202/quizzes/pictures/Screenshot%202023-10-29%20at%2019.54.00.png)

#flowchart　　✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦
![](https://github.com/marinamen/CS2023/blob/main/unit%202/quizzes/pictures/quiz017.jpg)
