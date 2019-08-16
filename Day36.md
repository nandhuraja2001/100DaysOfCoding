## Statement
```
Given a string in which the letter h occurs at least twice, 
replace every occurrence of the letter h by the letter H, except for the first and the last ones.
```
## Sample input
```
In the hole in the ground there lived a hobbit
```
## Code
```
s=input()
a=s[s.find('h')+1:s.rfind('h')]
b=(s[:s.find('h')+1] + a.replace('h','H') + s[s.rfind('h'):])
print(b)
```
## Sample output
```
In the Hole in tHe ground tHere lived a hobbit
```
