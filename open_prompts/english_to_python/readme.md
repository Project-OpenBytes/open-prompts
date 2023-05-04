# English to Python

### Categories

### Description

You can use the same prompt settings as the Playground's English to French option;
just change the French settings to Python in the form, and enable line breaks in the output.

### Examples

#### Example

Prompt

```
English: print "hi there"
Python: print('hi there')

English: loop 3 times, print 'x' each time
Python: for i in range(0,3):
   print('x')

English: A function that returns an argument to the power of 2
Python: def func(x):
   return x*x

English: A function that loops 10 times from 1 to 10 and adds the value to a total sum
Python: def func():
    sum = 0
    for i in range(1,11):
        sum += i
    return sum

English: Code that prints "hi" three times.
Python: print("hi"); print("hi"); print("hi")

English: Code that prints today's date.
Python: import datetime
print(datetime.datetime.now())

English: Code that asks the user for their name as a command line input.
Python: name = input("What is your name?")

English: Read a file into memory.
```

Response

```

```

### Source

<https://github.com/wgryc/gpt3-prompts/blob/master/english-to-python.md>
