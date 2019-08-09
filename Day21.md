## Statement
```
Write a program that receives a number on the input.
  - If the number is a multiple of 3, it prints "Jugs". 
  - If the number is a multiple of 5, it prints "Mugs".
  - If the number is a multiple of 7, it prints "Pugs".
  - If the number is a multiple of both 3 and 5, it prints "JugsMugs".
  - If the number is a multiple of both 3 and 7, it prints "JugsPugs".
  - If the number is a multiple of both 5 and 7, it prints "MugsPugs".
  - If the number is a multiple of both 3, 5 and 7, it prints "JugsMugsPugs".
Otherwise, it prints the number.
```
## Sample input 1
```
15
```
## Sample input 2
```
21
```
## Sample input 3
```
105
```
## Code
```
n=int(input())
if(n%3==0):
  print("Jugs")
if(n%5==0):
  print("Mugs")
if(n%7==0):
  print("Pugs")
if(n%3!=0 and n%5!=0 and n%7!=0):
  print(n)
  ```
## Sample output 1
```
JugsMugs
```
## Sample output 2
```
JugsPugs
```
## Sample output 3
```
JugsMugsPugs
```
