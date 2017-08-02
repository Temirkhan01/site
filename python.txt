Python 3.6.1 (v3.6.1:69c0db5, Mar 21 2017, 18:41:36) [MSC v.1900 64 bit (AMD64)] on win32
Type "copyright", "credits" or "license()" for more information.
>>> print 'Hello world'
SyntaxError: Missing parentheses in call to 'print'
>>> print "Hello"
SyntaxError: Missing parentheses in call to 'print'
>>> print ("Hello")
Hello
>>> name = 'Temirkhan'
>>> print name
SyntaxError: Missing parentheses in call to 'print'
>>> print ('name')SyntaxError: Missing parentheses in call to 'print'
SyntaxError: invalid syntax
>>> print ('name')
name
>>> name = 'Temirkhan'
>>> print (name)
Temirkhan
>>> n = raw_input('What is your name?')
Traceback (most recent call last):
  File "<pyshell#9>", line 1, in <module>
    n = raw_input('What is your name?')
NameError: name 'raw_input' is not defined
>>> raw_input
Traceback (most recent call last):
  File "<pyshell#10>", line 1, in <module>
    raw_input
NameError: name 'raw_input' is not defined
>>> 
