## Statement
```
Write a program that receives a number on the input.
- If the number is a multiple of 3, or it contains digit 3, it prints "Jugs". 
- If the number is a multiple of 5, or it contains digit 5, it prints "Mugs".
- If the number is a multiple of 7, or it contains digit 7, it prints "Pugs".
Otherwise, it prints the number.
```
## Sample input 1
```
73 
```
## Sample input 2
```
51  
```
## Sample input 3
```
105
```
## Code
```
n=int(input())
if(n%3==0 or '3' in str(n)):
  print("Jugs")
if(n%5==0 or '5' in str(n)):
  print("Mugs")
if(n%7==0 or '7' in str(n)):
  print("Pugs")de
```
## Sample output 1
```
JugsPugs
```
## Sample output 2
```
JugsMugs
```
## Sample output 3
```
JugsMugsPugs
```
