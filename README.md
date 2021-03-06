# 30 Days of Python
Start learning python and hopefully will use it for Machine Learning and Deep Learning in the future.

- [x] Day 1: Basics [time=Mon, Apr 17, 2017]
- [x] Days 2&3: Lists, Dictionaries, Tuples and Loops [time=Wed, Apr 19, 2017]
- [x] Day 4: Conditionals [time=Tue, Apr 25, 2017]
- [ ] Day 5: Functions
- [ ] Day 6: Advanced Strings
- [ ] Days 7-9: Classes
- [ ] Days 10 - 20: Python CSV, and Email | Do something Real
- [ ] Days 21 - 24: Web Scraping with Python 3 Python Requests & BeautifulSoup
- [ ] Day 25: Web Scraping on Javascript Driven HTML
- [ ] Day 26: Get Data with an API
- [ ] Days 27 - 28: Text Messaging (SMS/MMS) with Python & Twilio
- [ ] Day 29: Twitter API & Python
- [ ] Day 30: Read Email Inbox using Python & Gmail;

# HackMD Note
https://hackmd.io/AwTgHAJlHAtMAWAjAI1ghBmEsCGIA2AdlhVwCYRNh8BjJBXIA===?view

# Python Day 1: Basics
```Ruby
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Install Python3
```Ruby
brew install python3
```

### Variables
Declare directly with variable name
```Python
abc = 'some string'
```

# Python Day 2: Lists, Dictionaries, Tuples
### Lists
It is also called array in some languages.
String and numbers (Any Type) are allowed to store within the list.
```Python
list_var = ['some thing', 123, 'another thing']
list_var.append('new item') //append new item
list_var.pop() //pop the last item
list_var.pop(0) //index of the item
len(list_var) //get length of array
```

### Dictionaries
It is similar to Objective-C Dictionary, with key-value opinion.
However its key can be integer value while it is not allowed in some other languages.
*It can store a pointer within the value too*
```Python
Car = {'seats': ['driver', 'passanger'], 'mirror': 'front', 1234: 'others'}
Car[1234] //others
Car['mirror'] //front
Car['door'] = 4 //add new or edit key
```

### Tuples
It is a data structure (such as choices), not really everyone will like this.
```Python
Tup = (123, 234)
Tup = (('another', 'another'), ('some', 'some'))
```
Special thing to note
```Python
tup = (('tic', 'tic'), ('tac', 'tac'))
tup += ('toe', 'toe')
```
> (('tic', 'tic'), ('tac', 'tac'), 'toe', 'toe')

To append ```('toe', 'toe')``` in tail
```Python
tup = (('tic', 'tic'), ('tac', 'tac'))
tup += (('toe', 'toe'),)
```
> (('tic', 'tic'), ('tac', 'tac'), **('toe', 'toe')**)

# Python Day 3: For and While Loops
Use : to start the loop, and indention will be loop scope
Leave a empty line to state the end of loop (Other kind of indention will do)

### For Loops
```Python
bag = [10, 11, 12, 13]
for item in bag:
    print(item)
```

### While Loops
```Python
i = 1
while i < 11:
    print(i)
    i = i + 1
```

# Python Day 4: Conditionals
Boolean value
```Python
obj_a = True
obj_b = False

obj_a == obj_b //False
obj_a is obj_b //False
not obj_a is obj_b //True
```

### Using Conditional Expressions
```Python
list_d = ['Justin', 123, 'Apple', 'Food']
for item in list_d:
    if isinstance(item, str):
        print(item)

```

## Python Day 5: Functions
using sort or sorted function
```Python
str_items = ['aaa', 'Abc', 'AD', 'ED', 'JM']
str_items.sort()
str_items.sort(key=str.lower)
str_items.sort(key=str.lower, reverse=True)
new_items = sorted(sort_items)
new_itmes = sorted(str_items, key=str.lower, reverse=True)
```

### Others
note: There is different between Python2 and Python3
```Python
int_items = [1313, 21938.3, 12.23, 1314]
sum(int_items)
len(int_items)
total = sum(int_items)
average = sum(int_items)/len(int_items)

average = 1114124/len(int_items)
#Python2 = 278531 <-> Python3 = 278531.0

# References
Course [(30 days of python) Udemy](https://www.udemy.com/30-days-of-python)
Python3 [Python Installation](https://gist.github.com/uranusjr/6fa2770a8c8651192e93)

###### tags: `python` `30DaysPython`
