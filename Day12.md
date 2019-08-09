## Statement
```
Write a program to calculate the distance between two points.
To find the distance between two points (x1,y1) and (x2,y2), all that you need to do is use the coordinates of these ordered pairs and apply some common sense. 
Begin with the most simplest formula and then incrementally arrive at the correct formula as you solve the test cases.
```
## Sample input
```
123
```
## Code
```
# Read an integer:
# a = int(input())
# Print a value:
# print(a)
a = int(input())
digit1=a%10
a=int(a/10)
digit2=a%10
a=int(a/10)
digit3=a
print(digit1+digit2+digit3)
```
## Sample output
```
6
```
