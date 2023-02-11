# Python-Basic

##Intro:Python is a popular programming language. It was created by Guido van Rossum, and released in 1991.
##lets go a print 
print('My first code using python! welcome hello world')
My first code using python! welcome hello world
##python comment
#1st way
"""
This is a comment
written in
more than just one line
"""
# #2nd way
#This is a comment
##Python Variables
x = 5 #number
y = "John" #string
print(x)
print(y)
5
John
x = str(3)    # x will be '3'
y = int(3)    # y will be 3
z = float(3)  # z will be 3.0
print(x)
print(y)
print(z)
3
3
3.0
#if you don't believe 🤣 me so using type
print(type(x))
print(type(y))
<class 'str'>
<class 'int'>
##legal way to write
myvar = "John"
my_var = "John"
_my_var = "John"
myVar = "John"
MYVAR = "John"
myvar2 = "John"
##write multi value
x, y, z = "Orange", "Banana", "Cherry"
print(x)
print(y)
print(z)
Orange
Banana
Cherry
x = "Python"
y = "is"
z = "awesome"
print(x, y, z)
Python is awesome
x = "Python "
y = "is "
z = "awesome"
print(x + y + z)
Python is awesome
x = 5
y = 10
print(x + y)
15
##Global Variable
x = "awesome"

def myfunc():
  print("Python is " + x)

myfunc()
Python is awesome
x = "awesome"

def myfunc():
  x = "fantastic"
  print("Python is " + x)

myfunc()

print("Python is " + x)
Python is fantastic
Python is awesome
#Python Data Types
# Text Type:	str
# Numeric Types:	int, float, complex
# Sequence Types:	list, tuple, range
# Mapping Type:	dict
# Set Types:	set, frozenset
# Boolean Type:	bool
# Binary Types:	bytes, bytearray, memoryview
# None Type:	NoneType
#String
x = "Hello World"
x
'Hello World'
#number
x = 20
x
20
# float
x = 20.5
x
20.5
#complex
x = 1j
x
1j
print(type(x))
<class 'complex'>
#list
x = ["apple", "banana", "cherry"]
x
['apple', 'banana', 'cherry']
#tuple
x = ("apple", "banana", "cherry")
x
('apple', 'banana', 'cherry')
#range
x = range(6)
x
range(0, 6)
#dictionary
x = {"name" : "John", "age" : 36}
x
{'name': 'John', 'age': 36}
#set
x = {"apple", "banana", "cherry"}
x
{'apple', 'banana', 'cherry'}
#frozenset
x = frozenset({"apple", "banana", "cherry"})
x
frozenset({'apple', 'banana', 'cherry'})
#boolean
x = True
x
True
#bytes
x = b"Hello"
x
b'Hello'
#bytearray
x = bytearray(5)
x
bytearray(b'\x00\x00\x00\x00\x00')
#memoryViews
x = memoryview(bytes(5))
x
<memory at 0x0000029137C54C40>
#nonetype
x = None
x
#python numbers
x = 1    # int
y = 2.8  # float
z = 1j   # complex
print(type(x),type(y),type(z))
<class 'int'> <class 'float'> <class 'complex'>
x = 35e3
y = 12E4
z = -87.7e100

print(type(x))
print(type(y))
print(type(z))
<class 'float'>
<class 'float'>
<class 'float'>
#Python Casting
x = int(1)   # x will be 1
y = int(2.8) # y will be 2
z = int("3") # z will be 3
#Python Strings
a = """Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua."""
print(a)
Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua.
#Slicing Strings
b = "Hello, World!"
print(b[2:5])
llo
b = "Hello, World!"
print(b[:5])#0=H,1=e,2=l,3=l,4=o :5 means before 5
Hello
b = "Hello, World!"
print(b[2:])
llo, World!
b = "Hello, World!"
print(b[-5:-2])
# This code is using string slicing to extract a substring from the string "Hello, World!" and then print it to the console.

# The slice [-5:-2] specifies a range of indices to include in the output. The first index, -5, corresponds to the fifth character from the end of the string (i.e., the letter "o" in "World"). The second index, -2, corresponds to the second-to-last character in the string (i.e., the letter "r" in "World").

# When these indices are used to slice the string, the resulting substring is "orl". This substring is then printed to the console using the print() function.
orl
#Upper Case
a = "Hello, World!"
print(a.upper())
HELLO, WORLD!
#Lower case
a = "Hello, World!"
print(a.lower())
hello, world!
#remove whitespace
a = " Hello, World! "
print(a.strip()) # returns "Hello, World!"
Hello, World!
#replcae
a = "Hello, World!"
print(a.replace("H", "J"))
Jello, World!
#split
a = "Hello, World!"
print(a.split(",")) # returns ['Hello', ' World!']
['Hello', ' World!']
#String Concatenation
a = "Hello"
b = "World"
c = a + b
print(c)
HelloWorld
a = "Hello"
b = "World"
c = a + " " + b
print(c)
Hello World
#text formating
age = 36
txt = "My name is John, and I am {}"
print(txt.format(age))
My name is John, and I am 36
quantity = 3
itemno = 567
price = 49.95
myorder = "I want {} pieces of item {} for {} dollars."
print(myorder.format(quantity, itemno, price))
I want 3 pieces of item 567 for 49.95 dollars.
quantity = 3
itemno = 567
price = 49.95
myorder = "I want to pay {2} dollars for {0} pieces of item {1}."
print(myorder.format(quantity, itemno, price))
I want to pay 49.95 dollars for 3 pieces of item 567.
#short cut for fromating
a=2
b=3
f'Five plus ten is {a + b} and not {2 * (a + b)}.'
'Five plus ten is 5 and not 10.'
 #Escape Characters
# \'	Single Quote	
# \\	Backslash	
# \n	New Line	
# \r	Carriage Return	
# \t	Tab	
# \b	Backspace	
# \f	Form Feed	
# \ooo	Octal value	
# \xhh	Hex value
#Python Booleans
a = 200
b = 33

if b > a:
  print("b is greater than a")
else:
  print("b is not greater than a")
b is not greater than a
print(bool("Hello"))
print(bool(15))
True
True
#Python Arithmetic Operators
# +	Addition	x + y	
# -	Subtraction	x - y	
# *	Multiplication	x * y	
# /	Division	x / y	
# %	Modulus	x % y	
# **	Exponentiation	x ** y	
# //	Floor division	x // y
# =	x = 5	x = 5	
# +=	x += 3	x = x + 3	
# -=	x -= 3	x = x - 3	
# *=	x *= 3	x = x * 3	
# /=	x /= 3	x = x / 3	
# %=	x %= 3	x = x % 3	
# //=	x //= 3	x = x // 3	
# **=	x **= 3	x = x ** 3	
# &=	x &= 3	x = x & 3	
# |=	x |= 3	x = x | 3	
# ^=	x ^= 3	x = x ^ 3	
# >>=	x >>= 3	x = x >> 3	
# <<=	x <<= 3	x = x << 3
# and 	Returns True if both statements are true	x < 5 and  x < 10	
# or	Returns True if one of the statements is true	x < 5 or x < 4	
# not	Reverse the result, returns False if the result is true	not(x < 5 and x < 10)	
#Python Lists
thislist = ["apple", "banana", "cherry"]
print(thislist)
['apple', 'banana', 'cherry']
#Access List Items
thislist = ["apple", "banana", "cherry"]
print(thislist[1])
banana
thislist = ["apple", "banana", "cherry"]
print(thislist[-1])
cherry
thislist = ["apple", "banana", "cherry", "orange", "kiwi", "melon", "mango"]
print(thislist[2:5])
['cherry', 'orange', 'kiwi']
thislist = ["apple", "banana", "cherry", "orange", "kiwi", "melon", "mango"]
print(thislist[:4])
['apple', 'banana', 'cherry', 'orange']
thislist = ["apple", "banana", "cherry", "orange", "kiwi", "melon", "mango"]
print(thislist[2:])
['cherry', 'orange', 'kiwi', 'melon', 'mango']
thislist = ["apple", "banana", "cherry"]
thislist[1] = "blackcurrant"
print(thislist)
['apple', 'blackcurrant', 'cherry']
thislist = ["apple", "banana", "cherry", "orange", "kiwi", "mango"]
thislist[1:3] = ["blackcurrant", "watermelon"]
print(thislist)
['apple', 'blackcurrant', 'watermelon', 'orange', 'kiwi', 'mango']
#insert
thislist = ["apple", "banana", "cherry"]
thislist.insert(2, "watermelon")
print(thislist)
['apple', 'banana', 'watermelon', 'cherry']
#Add list item
thislist = ["apple", "banana", "cherry"]
thislist.append("orange")
print(thislist)
['apple', 'banana', 'cherry', 'orange']
thislist = ["apple", "banana", "cherry"]
thislist.insert(1, "orange")
print(thislist)
['apple', 'orange', 'banana', 'cherry']
thislist = ["apple", "banana", "cherry"]
tropical = ["mango", "pineapple", "papaya"]
thislist.extend(tropical)
print(thislist)
['apple', 'banana', 'cherry', 'mango', 'pineapple', 'papaya']
#remove item
thislist = ["apple", "banana", "cherry"]
thislist.remove("banana")
print(thislist)
['apple', 'cherry']
thislist = ["apple", "banana", "cherry"]
thislist.pop(1)
print(thislist)
['apple', 'cherry']
thislist = ["apple", "banana", "cherry"]
thislist.pop()
print(thislist)
['apple', 'banana']
thislist = ["apple", "banana", "cherry"]
del thislist#full delete
 
thislist = ["apple", "banana", "cherry"]
thislist.clear()
print(thislist)
[]
#Loop in list
thislist = ["apple", "banana", "cherry"]
for x in thislist:
  print(x)
apple
banana
cherry
thislist = ["apple", "banana", "cherry"]
for i in range(len(thislist)):
  print(thislist[i])
apple
banana
cherry
fruits = ["apple", "banana", "cherry", "kiwi", "mango"]
newlist = []

for x in fruits:
  if "a" in x:
    newlist.append(x)

print(newlist)
['apple', 'banana', 'mango']
fruits = ["apple", "banana", "cherry", "kiwi", "mango"]

newlist = [x for x in fruits if "a" in x]

print(newlist)
['apple', 'banana', 'mango']
#sort
thislist = ["orange", "mango", "kiwi", "pineapple", "banana"]
thislist.sort()
print(thislist)
['banana', 'kiwi', 'mango', 'orange', 'pineapple']
thislist = ["orange", "mango", "kiwi", "pineapple", "banana"]
thislist.sort(reverse = True)
print(thislist)
['pineapple', 'orange', 'mango', 'kiwi', 'banana']
thislist = [100, 50, 65, 82, 23]
thislist.sort(reverse = True)
print(thislist)
[100, 82, 65, 50, 23]
#copy
thislist = ["apple", "banana", "cherry"]
mylist = thislist.copy()
print(mylist)
['apple', 'banana', 'cherry']
#join list
list1 = ["a", "b" , "c"]
list2 = [1, 2, 3]

for x in list2:
  list1.append(x)

print(list1)
['a', 'b', 'c', 1, 2, 3]
list1 = ["a", "b" , "c"]
list2 = [1, 2, 3]

list1.extend(list2)
print(list1)
['a', 'b', 'c', 1, 2, 3]
