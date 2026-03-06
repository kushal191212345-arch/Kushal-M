
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
