# POLYMORPHISM AND ITS FUNCTION
# AIM:
To write a python program to create class function using polymorphism concept.
# ALGORITHM:

1)Start

2)Define a class named Turtle:

   Inside the class, define a method type() that prints "turtle".

3)Define another class named Frog:

   Inside this class, define a method type() that prints "frog".

4)Create an object obj1 of class Turtle.

5)Create another object obj2 of class Frog.

6)Call the type() method on obj1:

   This will print "turtle".

   Call the type() method on obj2:

  This will print "frog".

7)End
# PROGRAM:
```
class Turtle:
    def type(self):
        print("turtle")

class Frog:
    def type(self):
        print('frog')
obj1=Turtle()
obj2=Frog()

obj1.type()
obj2.type()
```
# OUTPUT:
![image](https://github.com/user-attachments/assets/b225737c-6741-4d9b-ae13-c9a19f505149)
# RESULT:
Thus expected output is acheived.
