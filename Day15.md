## Statement
```
Given a month - an integer from 1 to 12, print the number of days in it in the year 2017.
```
## Sample input 1
```
1
```
## Sample input 2
```
2
```
## Code
```
# Read an integer:
# a = int(input())
# Print a value:
# print(a)
a = int(input())
if(a==1 or a==3 or a==5 or a==7 or a==8 or a==10 or a==12):
    print("31")
elif(a==2):
    print("28")
else:
   print("30")
```
## Sample output 1
```
31
```
## Sample output 2
```
28
```
