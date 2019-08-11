## Statement
```
Write a program that receives a number on the input.
It also should receive another boolean value 'rev' on the input. 
- If the number is a multiple of 3, or it contains digit 3, it prints "Jugs". 
- If the number is a multiple of 5, or it contains digit 5, it prints "Mugs".
- If the number is a multiple of 7, or it contains digit 7, it prints "Pugs".
- If the number is a multiple of both 3 and 5, it prints "JugsMugs".
- also if number contains 3 and 5, it prints "JugsMugs"
- If the number is a multiple of both 3 and 7, it prints "JugsPugs".
- also if number contains 3 and 7, it prints "JugsPugs"
- If the number is a multiple of 3, 5 and 7, it prints "JugsMugPugs".
- also if number contains 3, 5 and 7, it prints "JugsMugsPugs"
Otherwise, it prints the number.
REVERSE REQUIREMENT:
If the boolean 'rev' is True, then reverse the order of printing. 
   - "PugsJugsMugs" for multiples of 3, 5 and 7
   - "PugsMugs" for multiple of 3 and 7
   - "MugsJugs" for multiple of 3 and 5 
   - "PugsJugs" for multiple of 5 and 7
```
## Sample input 1
```
73 
False  # contains 3 and 7
```
## Sample input 2
```
73 
True  # contains 7 and 3, print reverse order
```
## Code
```
n=int(input())
rev=int(input())
if rev==1:
  if (n%3==0 and n%5==0 and n%7==0)or(('3'and'7'and'5') in str(n)):
    print("PugsMugsJugs")
  elif (n%3==0 and n%5==0)or(('3'and'5') in str(n)):
    print("MugsJugs")
  elif (n%3==0 and n%7==0)or(('3'and'7') in str(n)):
    print("PugsJugs")
  elif (n%5==0 and n%7==0)or(('5'and'7') in str(n)):
    print("PugsJugs")
  elif (n%3==0)or('3' in str(n)):
    print("Jugs")
  elif (n%5==0)or('5' in str(n)):
    print("Mugs")
  elif (n%7==0)or('7' in str(n)):
    print("Pugs")
  else:
    print(n)
else:
  if (n%3==0 and n%5==0 and n%7==0)or(('3'and'5'and'7') in str(n)):
   print("JugsMugsPugs")
  elif (n%3==0 and n%5==0)or('3'and'5' in str(n)):
    print("JugsMugs")
  elif (n%3==0 and n%7==0)or('3'and'7' in str(n)):
    print("JugsPugs")
  elif (n%5==0 and n%7==0)or('5'and'7' in str(n)):
    print("MugsPugs")
  elif (n%3==0)or('3' in str(n)):
    print("Jugs")
  elif (n%5==0)or('5' in str(n)):
    print("Mugs")
  elif (n%7==0)or('7' in str(n)):
    print("Pugs")
  else:
    print(n)
 ```
 ## Sample output 1
 ```
 JugsPugs
 ```
 ## Sample output 2
 ```
 PugsJugs
 ```
