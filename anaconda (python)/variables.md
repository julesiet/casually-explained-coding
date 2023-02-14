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
#### DICTIONARIES
> i don't think there's another name for dictionary in python O__O 

Dictionaries have the ability to store types of variables in a variable, BUT they can also be stored with a key!!
``` python
# format of dictionary listing is "key: object"
myDictionary = {
  'string': 'hello world!', 
  'integer': 69, 
  'list': ['this', 'is', 'a', 'list']
  }
```
