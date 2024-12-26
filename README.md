#  Program 2. WAP to accept a number 'n' to compute the following:
a. check if 'n' is prime or not

code= n = eval(input("enter value"))
if n>1:
for i in range(2,n):

if n % 1 == 0:
print(n,"not a prime number")
break
else:
print(n,"prime number")
else:
print(n,"not a prime number")
