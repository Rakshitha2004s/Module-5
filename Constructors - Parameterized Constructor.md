# Exp.No:21 Constructors - Parameterized Constructor
# AIM
To write a Python code to create a class for a person with a parameterized constructor, which will take the name and userid of the person as parameters and print the userid of the person.

# ALGORITHM
Begin the program. Define a person class. The person class should have a parameterized init method that accepts two parameters: name and userid. Inside the init method, assign the name to self.name and the userid to self.userid. Print the self.userid. Prompt the user to enter their name (string) and userid. Create an instance s1 of the person class by passing the entered name and userid to the constructor. Terminate the program.

# PROGRAM
~~~
Reg-212222060245 Name-Singamala Rakshitha
class person:
def init(self,a,b):
self.a=a
self.b=b
def show(self):
print(self.b)
a=str(input())
b=str(input())
x=person(a,b)
x.show()
~~~
# OUTPUT
<img width="1091" height="285" alt="image" src="https://github.com/user-attachments/assets/91264270-697c-49b0-b1a8-2b217d77b2e8" />

# RESULT
Thus the python program was initiated and executed successfully.
