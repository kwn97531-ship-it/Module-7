# 🔁 Types of Recursion: Head Recursion in Python

## 🎯 AIM:
To write a Python program to demonstrate **Head Recursion** by finding and printing the sequence based on the sum of all digits (even or odd adjusted input).

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `fun(n)`
3. In the function:
   - Create a recursive call at the **beginning** (Head Recursion)
   - Print the result after the recursive call
4. Take input from the user
5. If input is odd, convert it to the next even number
6. Call the recursive function
7. **Stop**

## 💻 PROGRAM:

def fun(n,d):
    if (n > 0):
        fun(n - d,d)
        print(n, end=" ")
 
d= int(input())
x = int(input())
fun(x,d)


## OUTPUT
<img width="1254" height="256" alt="image" src="https://github.com/user-attachments/assets/88836584-1dab-4496-a239-023104a695da" />


## RESULT
Thus the required head recursion ouput is Verified.

