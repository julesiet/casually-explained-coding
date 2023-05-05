## CONCATENATION AND OPERATORS
As a quick refresher, **concatenation**, or more specifically string concatenation, is the process of combining two strings together and ~~mutilate their organs and disembowel their bodies and take them apart atom by atom to~~ create an entirely new string! 

Concatenation is pretty common across languages; in python, we accomplish this by:
``` python
firstHalf = 'hel'
secondHalf = 'lo!'
greeting = firstHalf + secondHalf
# expected input: 'hello!'

# alternatively, we wouldn't even need a second variable...
firstHalf = 'good'
greeting = firstHalf + 'bye!'
# ...or even a first variable to concatenate!
greeting = 'good' + 'bye!'
# expected input: 'goodbye!'
```
If you attempt to concatenate a string with an integer, the value stored is now a new string! Integers do not have the ability to "add" themselves to strings as integers, so they must be converted into a string in the process.
``` python
myNum = 8
myWord = 'ball'
newWord = myNum + myWord
# expected input: '8ball'
```
Concatenation can be useful in many scenarios, like in the case where you need to repeat the addition of a string to an end of a word. Here's an example of a program that transforms a word, phrase or sentence with the use of... *__concatenation!!__*
``` python
# don't worry if you don't know what a loop is! it's touched on later in the tutorials :)
sentence = input('Give me a sentence! (in all caps): ')
splitSen = sentence.split()
index = 0 
pigLatin = ''

for i in splitSen:
   message = splitSen[index]
   reverse = message[1:] + message[0]
   pigLatin += reverse + 'AY' + ' ' # !!!
   index += 1

print(pigLatin)
```
> WOOOOOOOOO ANOTHER LESSON DOWN BABY LETS GOOOOOOO YOU'RE DOING SO WELL!! 😊
