num=int(input("enter the number between 1-7:"))
if num==1: print("sunday")
elif num==2: print("monday")
elif num==3: print("tuesday")
elif num==4: print("wednesday")    
elif num==5: print("thursday")
elif num==6: print("friday")
elif num==7: print("saturday")
else:
    print("wrong input")

'''write a program to find the entered character is a vowel or a consonant,while user input could be either 
upper or lower case uisng if-elif-else'''
ch=input("enter the character")
if ch=='a' or ch=='e' or ch=='o' or ch=='u':
    print("it is vowel")
elif ch=='A' or ch=='E' or ch=='I' or ch=='U':
    print("it is vowel")
else:
    print("it is upper case or lower case")

ch=input("enter the character")
vowels='aeiouAEIOU'
for char in vowels:
    if char in ch:
        print("it is vowel")
    
'''write a program to create a simple calc by using if-elif-else to perform arithmetic operations 
+-*/ by choice of users input'''
a=float(input())
b=float(input())
op=input()
if op=='+':
    print("result",a+b)
elif op=='-':
    print("result",a-b)
elif op=='*':
    print("result",a*b)
elif op=='/':
    if b!=0:
        print("result",a/b)
    else:
        print("invalid number")
else:
    print("operations completed")
