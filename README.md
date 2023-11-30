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
```python

Program to find the square root for the given number(newton's method) using function.
#Developed by : AKASH KUMAR M.
#Register number : 23011321

def newton_method(number,number_items=1000):
    a=float(number)
    for i in range(number_items):
        number=0.5*(number+a/number)
    return number
a=int(input())
print("Square root of the number:",newton_method(a))

  

```

## Output:
![output](https://github.com/akash7812/Square-root-of-a-number/assets/146819826/c321b713-2019-4450-bc4e-23202a406139)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
