# Exp.No:23 Multiple Inheritance
# AIM
To write a Python program using multiple inheritance to get a student’s name, attendance, and ID (grade), and determine if the student is eligible for placement based on their grade.

# ALGORITHM
Start the program. Define class A: In the constructor init(), accept input for: n: Student's name a: Student's attendance i: Student's ID (grade) Define class B inheriting from A: Define disp1() to print the name and attendance. Define class C inheriting from A: Define disp2() to check if grade (i) is greater than 90: If yes, print “Eligible for Placement”. Else, print “Not Eligible for Placement”. Define class D that inherits from both B and C (multiple inheritance). Create an object o of class D. Call disp1() to display name and attendance. Call disp2() to check placement eligibility. End the program.

# PROGRAM
class student: def init(self,name,id,attendance): self.name=name self.id=id self.attendance=attendance def view(self): print(self.name) print(self.id) name=input() id=int(input()) attendance=int(input()) obj=student(name,id,attendance) obj.view () if attendance>=75: print("Eligible for Exam") else: print("Not Eligible for Exam")

# OUTPUT
<img width="1177" height="343" alt="image" src="https://github.com/user-attachments/assets/73df1c07-7d00-4eb6-b9e5-1f2c7149503e" />

# RESULT
Thus the python program was initiated and executed successfully.
