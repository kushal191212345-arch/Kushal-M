
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
