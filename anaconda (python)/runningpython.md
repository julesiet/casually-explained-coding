# RUNNING PYTHON IN THE TERMINAL (+ YOUR FIRST PROGRAM)
I think python is actually an extremely easy language to compile and run, in comparison to languages like `javascript` or *ANY* form of `C` code. But if you haven't figured it out yet ... :O 

Python is available in the terminal in virtually every single computer ~~that you can run League of Legends on~~, **BUT** if you don't have python or just want to check if you do, type:
```bash
# THIS WORKS UNIVERSALLY!! (i just use macOS because it's my most common machine :))
python3 --version
# ... to check for the most recent version of python, but you can still use: 
python --version
# if you're looking for any remnants of python on your computer :)
```
I would tell you how to install python / python3 because they are very easy to download, but I think literally everyone I'm showing this to has python installed somewhere, somehow on their computer, so I'll just leave a link to the [official website](https://www.python.org/downloads/) that teaches how to download python on macOS / Windows / Linux (if you're a nerd).  

Create a file that ends in `.py` which runs python script by either using the `touch` keyword on macOS:
``` bash
~ % touch hello.py
```
**OR** `type nul > hello.txt` replacing the `hello.txt` filename with one that ends in `.py`:
``` c++
C:\Users\username>type nul > hello.py
```
Use `nano` command in command line to inspect/write code to a file:
``` bash
# THIS WORKS UNIVERSALLY!! (i just use macOS because it's my most common machine :))
~ % nano hello.py
```
... which will hopefully open something like:
![nano_in_terminal](https://github.com/julesiet/casually-explained-coding/blob/40d01d941081d5d7559bf3c128a73823b88e551f/anaconda%20(python)/nano.png)
**OR** use an IDE (integrated development environment) to edit code easier and more fluidly!
|   POPULAR IDE(s)   |                                                                                                                FUNCTIONS                                                                                                                |
|:------------------:|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| VISUAL STUDIO CODE |      Lots of extensions and one of the most world renowned code editor(s) with the ability to run code within VS code via its own terminal, __*but*__ not really beginner friendly and can be overwhelming to observe all the features.     |
|        ATOM        | Customizable interface, beginner friendly and has the ability to pair alongside Github, __*but*__ takes an oddly long time to open, is shutting down in further development soon, and must be run in seperate terminal (need to fact check) |
|    SUBLIME TEXT    |                                                  Customizable interface, "minimalistic" (subjective), __*but*__ must be run in seperate terminal and storing files in folders is weird ...                                                  | 

Write your first python program using the `console.log` keyword, which can print any message put in single/double quotations:
``` python
# FIRST PYTHON PROGRAM WOOOOO !!!
print('Hello World!')
# also comments are left with the '#' keyword :)
```
Run python in the command line by using `python3` followed by the filename (`python2` / `python` if you want to use a deprecated version of python): 
``` bash
# THIS WORKS UNIVERSALLY!! (i just use macOS because it's my most common machine :))
~ % python3 hello.py # runs python3 (SEVERELY RECOMMENDED)
~ % python2 hello.py # runs python2
~ % python hello.py # ALSO runs python2 :)
```
And you should get...
``` bash
# THIS WORKS UNIVERSALLY!! (i just use macOS because it's my most common machine :))
~ % python3 hello.py
Hello World!
~ %
```
WOOOOOOO WE SAID HELLO TO THE WORLD!! 
> and you wrote and executed your first python program!! good job kings and queens <3
