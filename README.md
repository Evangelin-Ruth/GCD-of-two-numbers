# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
/*
Program to find the gcd of two number using function.
Developed by: Evangelin.S
RegisterNumber: 21500561 
*/
def gcd():
    n1,n2=int(input()),int(input())
    if n1>n2:
        small=n2
    else:
        small=n1
    for i in range(1,small+1):
        if(n1%i==0 and n2%i==0):
            hcf=i
    print("GCD of two numbers is:",hcf)
    
        
```

## Output:
![GCD](https://user-images.githubusercontent.com/94219798/149742274-04b4a60f-85ad-488b-8cbf-0d6a012fd1c5.JPG)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
