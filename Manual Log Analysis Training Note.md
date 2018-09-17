### Day 01 Log Analysis 

#### Credential
    - username: attacker
    - logSpreader192 

***

#### Python Programming language 

- ```python3 -c 'print("Hello World")'```


##### help function 

- to get the help interactive mode 
- help and follow by help()
- q 

*** 

#### To get the interpreter location 
- which python 

##### Comment 

### Data Types in Python 

    Numbers
        - int 
        - float  (eg 3.14.j)
        - complex
    String
    List
    Tuple
    Dictionary

### To get to know about the data type 
- type.(value)


### Identifiers 
- A python Identifier is a name used to identify a variable, function, class, module or other object. An identifier starts with a letter A to Z or a a to z or an underscore followed by zero or more letters, underscores and digits (0-9) [source](https://www.tutorialspoint.com/python/python_basic_syntax.htm)


### Variables 
- dir(variable)  
    - This will show all the attributes related with variable. 
    - methods 

- dir() will show all the objects in the memory.

- everything in python accept Keyword is Object. 

### Playing with the output 
- 

- print("Hello", "World", 2)   //comma separated value
- print(var1, var2,var3,sep="\n") // format method of the string objective
- //string Concatenation
- print("{}{}{}".format(var1,var2,var3))
    - "{}{}{}".format(var1,var2,var3)
    - "{0}{1}{0}".format(var1,var2,var3)
    - "{v1}{v2}{v3}".format(v1=var1,v2=var2,v3=var3)

- print("var1: {},var2: {}, var3: {}".format(var1,var2,var3)) 
- print("var1:{}")


### Function Names


#### Class name 


### Excercise
"Hello. My name is <your name>. I am <age> years old. My job is <job title>, which is pretty good for a <age> old person."


## gitbook 

- To generate book from Markdown 

## Escaping Characters 

- Python3 treats all as unicode 
- r"\n Hello \n World"  \\raw string 
- b"everything inside is considered as ascii"
-

## Logical Lines and Physical Lines 
- Logical Lines:
- ```python3
    a = 1
    b = 2
    print(a+b)```

- physical line 3 
- logical line 3 


## Code blocks 

if condition:
    statement
else
    statement 

## Control Block





# Expressions, operators, and operands 

a = 1 + 3 

### Integer division 

-9//4 
***
a=3
a == 3
a is 3 

total+=mark1

a+1 for a++ 

total = int(input("Please Enter the Mark")

# If block 

if condition:
    statement
elif condition:
    statement2
else:   
    statement3 

# while block

## Practice Questions 
- WAP to print a factorial of number
- fibonacci series upto nth series 

# For Loop 

for i in range(1,10,2):

for i in range(0,10,1)

# Data Structure 

Note:
- Li if you use -1, it will reverse and print 
- All the string can be indexed eg A[0]

li.sort will modified the content 
sorted(li2) will not affect the base list

## tuple 
- you can have all the list of information you don't want to change. 

## Set 
- Set is not an order list 

## dictionary 
- dict1 = {"name": "Sam", "job": "PenTester"}

## Function
1. function definition
2. function call 

def function_name(parameter1, parameter2)
    //code

    return

If you ahve a return value from a function, It can be used as a operatnt in an expression 


Parameter(place holder) and Argument(actualy value)
def sum(a,b):
    return(a,b)


Function recurssion 


WAP 
Ask user to choose which program to run 

Menu 
    option1 function 
    option2 function 

# Learn Python the Hardway 


# File Handling 

f = fopen("path/test.txt",)

- r ready only 
- w write only 
- a append 


with open("list.py") as f:
    text = f.read()
text  //has all the contenst of the file 

text= f.readlines()    \\ print the list 



with open(text.py, w) as f:
text="asdfajdslfjasldjfalskdjflksadjflajsdlfajsdlfasdfasdfadsfa"
f.wite(text)
//f.writeline(text)



def readfile(name):
    with open(name) as f:
            return f.read()



while True:

## An idea to write a tool to perform the following tasks
extract all IP 
UserAgent 
Whois Domain 




# Resource Link
[python1](https://developers.google.com/edu/python/)
[python2](https://courses.edx.org/courses/course-v1:MITx+6.00.1x+2T2018/courseware/47d859de1f9e45c5a7587d0009057aa9/01028329c5cb402bbc5931c681c9dc6d/)
[regex](https://learncodethehardway.org/regex/)
[Python Exercise](https://learnpythonthehardway.org/)
[Python3](https://pypi.org/)
[regex2](https://securityonline.info/regexp-security-cheatsheet/)
[regex3](https://bluescreenofjeff.com/2016-10-14-black-magic-parsing-with-regular-expressions-parsing-for-pentesters/)
[regex for pentester](http://blog.isecurion.com/2018/05/09/regexp-for-pentesters/)
[Malware Repository](https://github.com/ytisf/theZoo)
[Python Challenge](http://www.pythonchallenge.com/)