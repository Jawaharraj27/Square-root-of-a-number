# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
Program to find the square root for the given number(newton's method) using function.
Developed by: JAWAHAR RAJ N.
RegisterNumber: 23000787.
def sq():
    val1=int(input())
    val2=2
    for i in range(1,val1):
        val2=0.5*(val2+val1/val2)
    print("Square root of the number:",val2)
sq()


```

## Output:
![Screenshot 2023-11-24 052244](https://github.com/Jawaharraj27/Square-root-of-a-number/assets/139842416/cc000a5f-debb-4e33-a3b9-8a987e2694be)
![Screenshot 2023-11-24 052252](https://github.com/Jawaharraj27/Square-root-of-a-number/assets/139842416/10130774-ebe6-4803-b3a2-f7319969b123)


![gcd of two number](gcd.png)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
