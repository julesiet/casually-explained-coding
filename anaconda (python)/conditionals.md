## CONDITIONALS
The purpose of a conditional, or alternatively **if-statements**, is to check for a *condition* and to execute code if that condition returns *true.*
``` python
x = 10
y = 5

if y < x:
  print('y is less than x!')
# expected output: y is less than x!
```
If-statements typically return nothing as true, which can be useful! However, programmers have the option to use **if... else** statements to run code when a condition is *true and false.*
``` python
x = 5
y = 10

if y < x:
   print('y is less than x!')
else:
   print('x is less than y!')
# expected output: x is less than y!
```
Multiple if-statements can be chained to check for multiple conditions, but in most situations, programmers can use the shorthand **elif** to continue an initial if-statement to check for another condition.
> You can also attach an else statement at the end of a series of if-statements, no matter how long it might be!
``` python
x = 5
y = 5

if y < x:
   print('y is less than x!')
elif x == 5:
   print('y is equal to x!')
# expected output: y is equal to x!

# we can also do...
if y < x:
   print('y is less than x!')
elif y > x:
   print('y is greater than x!')
else:
   print('y is equal to x!')
# ...to check for this condition, which will return the same expected output!
```
