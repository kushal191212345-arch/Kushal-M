
# Begining
print("Python is the coding language")

k="kushal"
print(k)

l="100"
print(type(int(l)))


l="100"
print(type(float(l)))

l="100"
print(type(str(l)))

#Arthamatic Operators
a=10
b=20
print(a+b)
print(a-b) 
print(abs(a-b))  # here abs means absolute value it give the positive value of the number
print(a*b)
print(a/b)  
print(a//b) #it means it give the quotient without the decimal part
print(a%b) #it means it give the remainder


#concatenation
a="kushal"
b="kumar"   
print(a+b) # it will give the output as kushalkumar

#input
name=input("enter your name: ")
age=input("enter your age: ")
print("your name is "+ name +" and your age is "+age)# and it is a normal method to print the name and age
print(f"your name is {name} and your age is {age}") # and it is a f string method to print the name and age and it is easy

#repetition
a="kushal"
print(a*3) # it give the valve of a three times

#opeerators 

#assignment operators
a=10
a+=5 # it is same as a=a+5
print(a)
a-=5 # it is same as a=a-5
print(a)
a*=5 # it is same as a=a*5
print(a)
a/=5 # it is same as a=a/5
print(a)

#comparison operators
a=10
b=20    
print(a==b) # it will give the output as false because a is not equal to b
print(a!=b) # it will give the output as true because a is not equal to b
print(a> b) # it will give the output as false because a is not greater than b
print(a< b) # it will give the output as true because a is less than b  
print(a>=b) # it will give the output as false because a is not greater than or equal to b
print(a<=b) # it will give the output as true because a is less than or equal to b

#logical operators
a=10
b=20    
print(a>5 and b>15) # it will give the output as true because both conditions are true
print(a>5 or b>15) # it will give the output as true because at least one condition is true
print(not(a>5 and b>15)) # it will give the output as false because both conditions are true and not operator will give the opposite value

#membership operators
a="kushal"  
print('k' in a) # it will give the output as true because k is present in a
print('z' in a) # it will give the output as false because z is not present in a
print('k' not in a) # it will give the output as false because k is present in a
print('z' not in a) # it will give the output as true because z is not present in a 
#list operations

#adding an element to the list

hema.append(6) # it will add the value 6 at the end of the list
print(hema) # it will give the output as [1,2,3,4,5,6]

hema.insert(0,0) # it will add the value 0 at the index 0 of the list
print(hema) # it will give the output as [0,1,2,3,4,5,6]

#removing an element from the list
hema.remove(0) # it will remove the value 0 from the list
print(hema) # it will give the output as [1,2,3,4,5,6]

hema.pop() # it will remove the last element from the list
print(hema) # it will give the output as [1,2,3,4,5] 

#replacing an element in the list
hema[0]=10 # it will replace the value at index 0 with 10        
print(hema) # it will give the output as [10,2,3,4,5]

#tuples
t=(1,2,3,4,5)   
print(t) # it will give the output as (1,2,3,4,5)

"""
 its has the same operations as list
 but it is immutable means we cannot change the value of the tuple once it is created
 and it is faster than list because it is immutable
 and it is used to store the data that cannot be changed like the days of the week, months of the year etc.
"""

#sets
s={1,2,3,4,5}
print(s) # it will give the output as {1,2,3,4,5}   

"""
it is unordered collection of unique elements
it is mutable means we can change the value of the set  
it is used to store the data that cannot be duplicated like the unique values of a list etc.
"""
#dictionaries
d={"name":"kushal",
   "age":20,"city":"delhi"
}
print(d) # it will give the output as {'name':'kushal','age':20,'city':'delhi'}

#dictionary operations
#adding an element to the dictionary
d["country"]="india" # it will add the key country with the value india to the dictionary
print(d) # it will give the output as {'name':'kushal','age':20,'city':'delhi','country':'india'}       
 
#removing an element from the dictionary
del d["city"] # it will remove the key city from the dictionary
print(d) # it will give the output as {'name':'kushal','age':20,'country':'india'}  
 
#replacing an element in the dictionary
d["age"]=21 # it will replace the value of the key age with 21      
print(d) # it will give the output as {'name':'kushal','age':21,'country':'india'}
 
#accessing an element from the dictionary
print(d["name"]) # it will give the output as kushal because it will access the value of the key name from the dictionary   
 
#returning keys in the dictionary
print(d.keys()) # it will give the output as ['name', 'age', 'country'] because these are the keys in the dictionary
 
#returning values in the dictionary
print(d.values()) # it will give the output as ['kushal', 21, 'india'] because these are the values in the dictionary   
 
#returning items in the dictionary
print(d.items()) # it will give the output as [('name', 'kushal'), ('age', 21), ('country', 'india')] because these are the items in the dictionary
#conditional statements *(if, elif, else)*
a=int(input("enter a number: "))
if a>0:  
      print("a is positive") # it will give the output as a is positive because a is greater than 0
elif a<0:
      print("a is negative") # it will give the output as a is negative because a is less than 0   
else:
      print("a is zero") # it will give the output as a is zero because a is equal to 0
 
#simple operations on conditional statements
print("Engineering fee structure")
a=input("enter a name of the students: ")
b=input("enter a catse name: ")
c=int(input("enter a age: "))
if b=="general" :
      print("you have to pay full fee") # it will give the output as you have to pay full fee because the caste is general
      if b==" OBC":
            print("you have to pay 75% of the fee") # it will give the output as you have to pay 75% of the fee because the caste is OBC
      elif b=="SC":
            print("you have to pay 50% of the fee") # it will give the output as you have to pay 50% of the fee because the caste is SC/ST
      elif b=="ST":
            print("you have to pay 35% of the fee") # it will give the output as you have to pay 25% of the fee because the caste is SC/ST
else:
      print("you have to pay full fee")
#loops

#while loop

e=input("enter a gender: ")
b=int(input("enter a age: "))
while True:
      if e=="female":
            print("ticket is free for womens")
            break
      if e=="male" and b>60:
            print("ticket is free for senior citizens")
            if b<10:
                  print("ticket is free for childrens")
      else:
            print("u have to pay full price")
 
#for loop
i=int(input("enter a first number: "))
j=int(input("enter a second number: "))
for k in range(i,j):
      for l in range(i,j):
            print(f"{k}X{l}={k*l}") 
      
print(" ")
#some operation on loops with user interaction
while True:
    i=int(input("enter a first number: "))
    j=int(input("enter a second number: "))
    for k in range(1,i+1):
        for l in range(1,j+1):
            print(f"{k}X{l}={k*l}") 
        print(" ")    
    continue
    
#list comprehension
k=[1,2,3,4,5,6,7,8,9,10]
dk=[i for i in k if i%2==0]
print(dk) 

l=[num**3 for num in range(30) if num%3!=0]
print(l)

m=[num for num in m ].split()
print(m)

#dictionary comprehension

k=input("enter a name: ")
l=int(input("enter a age: "))
n={k:l for k,l in zip(k,l)}
print(n)

#Functions
def add(a,b):
      print(a+b)

add(10,20) # it will give the output as 30 because it will add the two numbers
add(100,200) # it will give the output as 300 because it will add the two numbers
#it is a function that takes two arguments a and b and prints the sum of a and b
#it is a simple function that performs addition of two numbers and prints the result
#it is a reusable block of code that can be called multiple times with different arguments to perform the same operation


#some operations on functions
def factorial(n):
      if n==0:
            return 1
      else:
            return n*factorial(n-1)
print(factorial(5)) 

def calc_area(**shapes):
      if "circle" in shapes:
            radius = shapes["circle"]
            pi = 3.14
            area = pi * radius ** 2
      elif "triangle" in shapes:
            base = shapes["triangle"]["base"]
            height = shapes["triangle"]["height"]
            area = 0.5 * base * height
      elif "rectangle" in shapes:
            length = shapes["rectangle"]["length"]
            width = shapes["rectangle"]["width"]
            area = length * width
      return area

#we can call the function with different shapes and their dimensions to calculate the area
def greet(name):
      print(f"hello {name} welcome to python programming")  
greet("kushal") # it will give the output as hello kushal welcome to python programming because it will greet the name that is passed as an argument to the function
greet("hema") # it will give the output as hello hema welcome to python programming because it will greet the name that is passed as an argument to the function





# I has started to solve the roblems in hackerrank 
#Task Given an integer, , perform the following conditional actions:

If  is odd, print Weird
If  is even and in the inclusive range of  to , print Not Weird
If  is even and in the inclusive range of  to , print Weird
If  is even and greater than , print Not Weird
#!/bin/python3

import math
import os
import random
import re
import sys



if __name__ == '__main__':
    n = int(input().strip())
    if n%2!=0:
        print("Weird")
    elif n%2==0 and range(2,6):
        print("Not Weird")
    elif n%2==0 and range(6,21):
        print("Weird")
    elif n%2==0:
        if n>20:
            print("Not Weird")

#Task
#The provided code stub reads two integers from STDIN,  and . Add code to print three lines where:

#The first line contains the sum of the two numbers.
#The second line contains the difference of the two numbers (first - second).
#The third line contains the product of the two numbers

if __name__ == '__main__':
    a = int(input())
    b = int(input())
    print(a+b)
    print(a-b)
    print(a*b)
# The provided code stub reads an integer, , from STDIN. For all non-negative integers , print .
if __name__ == '__main__':
    n = int(input())
    for i in range(0,n):
        if i<n:
           print(i**2)
"""           
Let's learn about list comprehensions! You are given three integers  and  representing the dimensions of a cuboid along with an integer . Print a list of all possible coordinates given by  on a 3D grid where the sum of  is not equal to . Here, . Please use list comprehensions rather than multiple loops, as a learning exercise
"""
if __name__ == '__main__':
    x = int(input())
    y = int(input())
    z = int(input())
    n = int(input())
    result = [[i, j, k] for i in range(x + 1) for j in range(y + 1) for k in range(z+ 1) if (i + j + k) != n]
    print(result)
"""
Given the participants' score sheet for your University Sports Day, you are required to find the runner-up score. You are given  scores. Store them in a list and find the score of the runner-up
"""
if __name__ == '__main__':
    n = int(input())
    arr = map(int, input().split())
k=set(arr)
m=sorted(list(k))
l=m[-2]
print(l)
"""
Given the names and grades for each student in a class of  students, store them in a nested list and print the name(s) of any student(s) having the second lowest grade
"""
if __name__ == '__main__':
    students = []
    for _ in range(int(input())):
        name = input()
        score = float(input())
        students.append([name, score])
    unique_grades = sorted(set(student[1] for student in students))
    second_lowest_grade = unique_grades[1]
    names_with_second_lowest = []
    for student in students:
        if student[1] == second_lowest_grade:
            names_with_second_lowest.append(student[0])
    names_with_second_lowest.sort()
    for name in names_with_second_lowest:
        print(name)

"""
The provided code stub will read in a dictionary containing key/value pairs of name:[marks] for a list of students. Print the average of the marks array for the student name provided, showing 2 places after the decimal.
"""
if __name__ == '__main__':
    n = int(input())
    student_marks = {}
    for _ in range(n):
        name, *line = input().split()
        scores = list(map(float, line))
        student_marks[name] = scores
    query_name = input()
    k=student_marks[query_name]
    l=sum(k)/len(k)
    print("{:.2f}".format(l))

"""
Given an integer,n ,n and  space-separated integers as input, create a tuple, , of those  integers. Then compute and print the result of hash()
"""
if __name__ == '__main__':
    # Read the number of elements (n)
    n = int(input())
    integer_list = map(int, input().split())
    t = tuple(integer_list)
    print(abs(hash(t)))
"""
The included code stub will read an integer, , from STDIN.
Without using any string methods, try to print the following: 123......n
Note that "" represents the consecutive values in between .
"""
if __name__ == '__main__':
    n = int(input())
    for i in range(1,n+1):
        print(i,end="")
"""
Let's dive into the interesting topic of regular expressions! You are given some input, and you are required to check whether they are valid mobile numbers.

A valid mobile number is a ten digit number starting with a 7,8  or 9
"""
import re
n = int(input())
for x in range(0, n):
    if(re.match(r'^[7-9]{1}[0-9]{9}n?r?$',input())):
        print ("YES")
    else:
        print ("NO")
 """
 In this challenge, the user enters a string and a substring. You have to print the number of times that the substring occurs in the given string. String traversal will take place from left to right, not from right to left.
 """
 def count_substring(string, sub_string):
    return

if __name__ == '__main__':
    string = input().strip()
    sub_string = input().strip()
    count = count_substring(string, sub_string)
    print(count)
"""
We have seen that lists are mutable (they can be changed), and tuples are immutable (they cannot be changed).

Let's try to understand this with an example.

You are given an immutable string, and you want to make changes to it.
"""
def mutate_string(string, position, character):
    return

if __name__ == '__main__':
    s = input()
    i, c = input().split()
    s_new = mutate_string(s, int(i), c)
    print(s_new)
        
