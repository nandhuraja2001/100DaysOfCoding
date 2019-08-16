## Statement
```
Given a string in which the letter h occurs at least twice, 
reverse the sequence of characters enclosed between the first and last occurrences of it.
```
## Sample input
```
In the hole in the ground there lived a hobbit
```
## Code
```
s=input()
a=s[s.find('h'):s.rfind('h')]
b=(s[:s.find('h')+1] + a[::-1] + s[s.rfind('h')+1:])
print(b)
```
## Sample output
```
In th a devil ereht dnuorg eht ni eloh ehobbit
```
