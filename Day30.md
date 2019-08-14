## Statement
```
There was a set of cards with numbers from 1 to N. One of the card is now lost. 
Determine the number on that lost card given the numbers for the remaining cards.
Given a number N, followed by N − 1 integers representing the numbers on the remaining cards (distinct integers in the range from 1 to N). 
Find and print the number on the lost card.
```
## Sample input
```
5
3
5
2
1
```
## Code
```
a=int(input())
b=[]
for i in range(a-1):
  c=int(input())
  b.append(c)
for j in range(1,a+1):
  if b.count(j)==0:
    print(j)
```
## sample output
```
4
```
