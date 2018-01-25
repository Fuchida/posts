title: Python Decorator by Example
date: 2018

###Basic Setup for a decorator
```
# py:3
def logger(func):
    
    def wrap(*args, **kwards):
        if "House" in args:
            print "House Logging"
        else:
            print "logging"
        return func(*args, **kwards)
    return wrap

@logger
def say_hello(word):
    print word
```

```
say_hello("House")
>> House Logging
>> House
```
