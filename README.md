a=int(input("Enter the first number : "))
b=int(input("Enter the second number : "))
s=a+b
d=a-b
p=a*b
q=a/b
f=a//b
m=a%b
print("Performing all arithematic operations ")
print("addition = ",s)
print("subtraction = ",d)
print("multiplication = ",p)
print("division = ",q)
print("floor division = ",f)
print("modulus = ",m)

a=int(input("Enter the first number : "))
b=int(input("Enter the second number : "))
c=int(input("Enter the third number : "))
max_val=max(a,b,c)
print("The Largest of three numbers is ",max_val)

numlist=[int(input("Enter the numbers : ")) for i in range(5)]
max_val=max(numlist)
min_val=min(numlist)
print("The maximum value of the five numbers is : ",max_val)
print("The minimum value of the five numbers is : ",min_val)

perc=int(input("Enter the student percentage : "))
if perc > 90:
  print("Grade = A")
elif perc >= 80 and perc < 90:
  print("Grade = B")
elif perc >= 70 and perc < 80:
  print("Grade = C")
elif perc >= 60 and perc < 70:
  print("Grade = D")
else:
  print("Grade = E")

number = int(input("enter the number to print the multiplication table : "))
print("The multiplication table of : ",number)
for count in range(1,11):
  print(number,"x",count,"=",number*count)

num = int(input("Enter number:"))
sum=0
while(num!=0):
  r=num%10
  sum=sum+r
  num=num//10
print(sum)

def prefix(name,gender):
  if gender == "M" or gender == "m" :
    print("Hello,Mr.",name)
  elif gender == "F" or gender == "f":
    print("Hello,Ms.",name)
  else:
    print('Please enter only M or F in gender')
name = input('Enter your name : ')
gender = input("Enter your gender: M for Male and F for Female:")
prefix(name,gender)

def swapN(a,b):
  t=a
  a=b
  b=t
  return a,b
n1=int(input("Enter Number 1:"))
n2=int(input("Enter Number 2:"))
print("Returned value from function:")
n1,n2=swapN(n1,n2)
print("Number 1 : ",n1,"Number 2 : ",n2)

def titlecase(string):
  print(string.title())
str = input("Write a sentence : ")
titlecase(str)

def hyphen(string):
  print(str.replace(" ","-"))
str=input("Write a sentence:")
hyphen(str)

list1=[10,20,30,40,50,60,20,50,10,30,50,30,24,45]
print("The list is :",list1)
inp=int(input("Which element occurrence would you like to count? : "))
count=list1.count(inp)
print("The count of element",inp,"in the list is:",count)

def largestNum(list1):
  i=max(list1)
  return i
list1=[1,2,3,14,5,6,7,8,9]
max_num=largestNum(list1)
print("\n The largest number of the list : ",max_num)

n=int(input("Enter the number of elements:"))
I=[]
for i in range(n):
  ele=input("Enter the elements:")
  I.append(ele)
print("my list",I)
non_duplicate_value=set(I)
print("List after removing duplicate elements is")
print(non_duplicate_value)
