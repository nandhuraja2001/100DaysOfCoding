## Statement
```
Write a program that receives a number on the input.
If the number is a multiple of 3, it prints "Jugs". 
If the number is a multiple of 5, it prints "Mugs".
If the number is a multiple of both 3 and 5, it prints "JugsMugs".
Otherwise, it prints the number.
```
## Sample input 1
```
3
```
## Sample input 2
```
15
```
## Code
```
a=int(input())
if(a%3 == 0 and a%5==0):
  print("JugsMugs")
elif(a%3==0):
  print("Jugs")
elif(a%5==0):
  print("Mugs")
else:
  print(a)
  ```
  ## Sample output 1
  ```
  Jugs
  ```
  ## Sample output 2
  ```
  Mugs
  ```
  
