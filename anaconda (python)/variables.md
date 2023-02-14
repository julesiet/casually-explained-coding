## VARIABLES
Unlike many aspects in programming languages, variable types are virtually the same across the board.
> The names are just different sometimes D:<

### STRINGS
String values are typically words, phrases or sentences, but can store anything as long as it's within single or double quotations: 
``` python
myString = 'word'
myString = 'two words'
myString = 'a whole sentence!! :)'
# i can also store numbers look!
myStringNum = '6'
# but is it really a number ... hmmm? U+1F928
```
There can be some interferences if you're storing with apostrophes.. 
``` python
myString = 'i'm a string!'
# this would throw an error :( BUT we can resolve this with either ...
myString = "i'm a string!" # using double quotations
myString = 'i\'m a string!' # using a backslash

# I DON'T KNOW WHY THE DOUBLE QUOTATIONS DON'T WORK BUT IT DOES I PROMISE :')
```
### INTEGERS
Integer values are any **whole** number, which is an important distinction to make as there tends to be type differences with *float* values:
``` python
myInt = 6 # single digit number!
myInt = 69 # double digit number!
myInt = 6969696969696969696969 # BIG INTEGER :)
myFloat = 4.20 # not an integer, dirty FLOATING POINT >:(
```
#### FLOATING POINT
Floating point values are numbers but with decimals (that's it.)
``` python
myFloat = 4.20 # look i did it twice :)
```

### OBJECTS
Objects store multiple values within one variable, there are two main types:

#### LISTS / ARRAYS
List values are the most common type of objects used, as they not only just store a type of variables, BUT multiple types of variables in one!!
``` python 
myStrList = ['this', 'is', 'a', 'way', 'of', 'storing', 'strings']
myNumList = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10] # integers in one list :)
myListList = [['this is'], ['a list'], ['within a list']] # lists within lists!!
allTypes = ['string', 69, ['list type']] # look at these types!!
```
Reference **list** elements / indexes with numbers starting from 0!
``` python
juniorRoboticks = ['Samantha', 'Jude', 'Jon', 'Kyra', 'Jose', 'Sila', 'Brian']
print(juniorRobotics[0])
# expected output: 'Samantha'
print(juniorRobotics[4])
# expected output: 'Jose'
print(juniorRobotics[5-3]) # you can even apply math to indexes!
# expected output: 'Jon'
print(juniorRobotics[7])
# expected output: ERROR // index is out of list length >:(
```
BONUS: You can also find length of lists by using the `len` function.. shhhhh.. no one's supposed to know ;)
``` python 
print(len(juniorRoboticks))
# expected output: 7

# tell me what you can do with len(juniorRoboticks) - 1 >:)
```
#### DICTIONARIES
> i don't think there's another name for dictionary in python O__O 

Dictionaries have the ability to store types of variables in a variable, BUT they can also be stored with an object!!
``` python
# format of dictionary listing is "key: object"
myDictionary = {
  'string': 'hello world!', 
  'integer': 69, 
  'list': ['this', 'is', 'a', 'list']
  }
```
Reference **dictionary** objects with the key they're stored with!
``` python
print(myDictionary['string']) 
# expected output: 'hello world!'
print(myDictionary['list'])
# expected output: ['this', 'is', 'a', 'list']
```
(You can also print the keys the objects are stored with the `.keys()` keyword :D) 
``` python
print(myDictionary.keys())
# expected output: dict_keys(['string', 'integer', 'list'])
```
The main takeaway from this lesson is that:
- absolutely NO one cares about boolean values <3 (although understanding what `null` is would be good for jason's hideout)
- AND THAT YOU FIGURED OUT VARIABLE TYPES AGAIN!! WOOOOOOO :)
# PYTHON BABYYYYYY >:D

