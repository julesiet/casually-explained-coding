# LOOPS
Loops, or iteration statements, are meant to repeat lines of code in order to reduce the amount of repeated code or to automate certain processes x number of times. 

To do this, use the `for` keyword to determine when a loop should end; in this example, we want to print the phrase "hey there, user!" 5 times:
``` python
# instead of doing..
print('hey there, user!')
# ..5 times, we can replace all those lines of code with:
for i in range(0, 5):
   print('hey there, user!')
# as both a way to reduce code AND to make it easier to read :)
```
`i` in this case represents the counting variable and the `in` keyword, in conjuction with the `range` command, defines the amount of times `i` will repeat until the loop exits. 

We are not limited to the *for* keyword either! We can also use *while* in a similar fashion to repeat lines of code until the condition returns true:
``` python
i = 0

while i < 5:
   print('hey there, user!')
   i += 1 
# ^^ note: we must increment i by 1 to make sure this loop doesn't run infinitely :)
```
NOTE: `i` still represents the counting variable, but we initialize `i` prior to the loop because in contrast to the `for` loop, it is not initialized within the loop itself.
> ~~loop deez nuts into yo mouf~~
