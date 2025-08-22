# Exp. No: 2a  
## ITERATIVE STATEMENTS –  print 1 to n Even numbers
###  Aim
To write a Python program to print all even numbers from 1 to n

###  Algorithm

Start the program.

Input the value of n from the user.

Use a for loop to iterate from 1 to n.

Inside the loop, check if the number is even using the condition:
- if i % 2 == 0

If the condition is true, print the number.

Stop the program.


###  Program
```
n=int(input())
for i in range(1,n+1):
    if(i%2==0):
        print(i)

```
### OUTPUT
```
<img width="396" height="510" alt="image" src="https://github.com/user-attachments/assets/d547efbd-fc15-493d-aea4-ec6db7d4ea3e" />

```
### RESULT

Thus, the Python program to print even numbers from 1 to n was successfully executed and verified.





# Exp. No: 2b  
## Functions– find the absolute value of the given number using the concept of function

###  Aim
To write a Python program to find the absolute value of a given number using the concept of functions.


###  Algorithm

Start the program.

Define a function absolute_value(num) that:

Takes a number as an argument.

If the number is less than 0, return -num.

Otherwise, return num.

Input a number from the user.

Call the function with the given number.

Display the absolute value returned by the function.

Stop the program.


### 🧾 Program
```
def absolute_value(num):
    if num >= 0:
        return num
    else:
        return -num
        


```

### OUTPUT
```
<img width="577" height="352" alt="image" src="https://github.com/user-attachments/assets/2e624737-d516-4fa5-980e-b0dd672d650d" />

```
### RESULT
```
Thus, the Python program to find the absolute value of a given number using a function was successfully executed and verified.

```





# Exp. No: 2c 
## Built-In Funtions & Lambda Function – lambda function which takes z as a parameter and returns z*2 using python

###  Aim

To write a Python program to create a lambda function that takes z as a parameter and returns z * 2.


###  Algorithm

Start the program.

Input an integer value from the user and store it in variable i.

Define a lambda function f that takes z as a parameter and returns z * 2.

Call the lambda function by passing the input value i.

Display the result.

Stop the program.


### 🧾 Program

```
i=int(input())

f=lambda z: z*2

print(f(i))
```

### OUTPUT

```
<img width="317" height="189" alt="image" src="https://github.com/user-attachments/assets/363a91b8-571c-4660-871c-7ab57c0bc7c1" />

````
### RESULT
```
Thus, the Python program to create a lambda function that takes z as a parameter and returns z * 2 was successfully executed and verified.

```





# Exp. No: 2d 
## Looping (Patterns) – print alternate number pattern

###  Aim
To write a Python program to print alternate numbers from 1 to n.

---

###  Algorithm

Start the program.

Input the value of n from the user.

Use a for loop starting from 1 to n with a step of 2.

In each iteration, print the number.

Stop the program.

### 🧾 Program
```
n=int(input())
i=1
while i<=n:
    j=1
    while j<=i:
        print((i*2-1),end=' ')
        j=j+1
    i=i+1
    print('')
           
```                


### OUTPUT
```
<img width="542" height="492" alt="image" src="https://github.com/user-attachments/assets/ad178856-7cf7-4806-a184-8ede212cad31" />

```
### RESULT
```
Thus, the Python program to print alternate numbers from 1 to n was successfully executed and verified.
```





# Exp. No: 2e  
## SEB – compute whether the given number is a palindrome
###  Aim
To write a Python program to check whether the given number is a palindrome or not.

---

###  Algorithm
Start the program.

Input a number from the user.

Store the original number in a variable.

Reverse the number using:

Initialize a variable rev = 0.

Use a while loop until the number becomes 0.

Extract the last digit using rem = num % 10.

Update the reverse using rev = rev * 10 + rem.

Remove the last digit using num = num // 10.

Compare the original number with the reversed number.

If both are equal → It is a palindrome.

Otherwise → It is not a palindrome.

Display the result.

Stop the program.

### 🧾 Program
```
num=int(input())
temp=num
rev=0
while temp>0:
    rem=temp%10
    rev=(rev*10)+rem
    temp=temp//10
if(num==rev):
    print("The given number {} is a Palindrome".format(num))
else:
    print("The given number {} is not a palindrome".format(num))
```
### OUTPUT
```
<img width="986" height="213" alt="image" src="https://github.com/user-attachments/assets/851412fb-0854-47d0-94cb-0e7ac08182bc" />


```
### RESULT
```
Thus, the Python program to check whether the given number is a palindrome was successfully executed and verified.
```

