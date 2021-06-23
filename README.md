# Fizz Buzz!

## Timings

30 minutes

## Summary

#### Super simple game that will substitute multiples of 3 and 5 for fizz an buzz respectily, or fizzbuzz for multiples of the two
## Tasks
## Core:
- Write a program that prints the numbers from 1 to 100.
```
for i in range(1, 101):
    print(i)
 ```
- For multiples of three print "Fizz" instead of the number
````
for i in range(1, 101):
    if i % 3 == 0:
        print("Fizz")
    else:
        print(i)
````
- For the multiples of five print "Buzz" instead of the number
````
for i in range(1, 101):
    if i % 5 == 0:
        print("Buzz")
    else:
        print(i)
````
- For numbers which are multiples of both three and five print "FizzBuzz".
````
for i in range(1, 101):
    if i % 3 == 0 and i % 5 == 0:
        print("FizzBuzz")
    elif i % 3 == 0:
        print("Fizz")
    elif i % 5 == 0:
        print("Buzz")
    else:
        print(i)
````
## Extra:
#### make a new fizzbuzz file and make it functional
#### make it so we we can decide which numbers to substitute for fizz and buzz using functions
```
number = int(input("Please enter a number: "))
def fizz_buzz(number):
    is_fizz = number % 3 == 0
    is_buzz = number % 5 == 0
    if is_fizz and is_buzz:
        print(f"{number} is FizzBuzz")
    elif is_fizz:
        print(f"{number} is Fizz")
    elif is_buzz:
        print(f"{number} is Buzz")
    else:
        print(f"{number} is not Fizz or Buzz")
fizz_buzz(number)
```
#Hint: loop, range, control flow

## Acceptance Criteria

# All core task are done
# Code works with no error
