## Decision

In programming, making decision is important. It is a mechanism in which the program runs based on certain conditions. It is just like our real life situation when we have to do something is a condition is met. For example, when it is rain, we stay at home. 

### ``if`` Statement

The first and the simplest conditional statement is ``if`` as follow:

```python
if true_or_not:
	do_this_if_true
```

Now the question is, **how this statement works?**

* First, if the ``true_or_not`` expression represents the truth (i.e., its value is not equal to zero), the indented statement(s) will be executed.
* But, if ``true_or_not`` expression does not represents the truth (i.e., its value is equal to zero), the indented statement(s) will be omitted, and the next executed instruction will be the one after the original indentation level.

In real life, we often express a desire:

```
if the weather is good, we'll go for walk

then, we'll have lunch
```
As we can see above that having lunch is not a conditional activity and doesn't depend on the weather. By knowing what condition affects our behavior, the condition above can be translated as follows:
```python
if weather_is_good:
	go_for_a_walk()
have_lunch()
```

``if`` statement is the most basic decision-making in programming.

### ``if-else`` Statement

The `else` statement allows you to specify an alternative block of code to execute if the `if` condition is false.
```python
age = 16
if age >= 18:
    print("You are an adult.")
else:
    print("You are not an adult.")
```
### A Series of ``if`` Statement
```python
x = 10

if x > 5: # condition one
    print("x is greater than 5")  # Executed if condition one is True.

if x < 10: # condition two
    print("x is less than 10")  # Executed if condition two is True.

if x == 10: # condition three
    print("x is equal to 10")  # Executed if condition three is True.
```

### ``if-elif-else`` Statement

The `elif` (short for else if) statement allows us to check multiple conditions.
```python
age = 16
if age >= 18:
    print("You are an adult.")
elif age >= 13:
    print("You are a teenager.")
else:
    print("You are a child.")
```

### Nested ``if`` Statement
```python
x = 10

if x > 5:  # True
    if x == 6:  # False
        print("nested: x == 6")
    elif x == 10:  # True
        print("nested: x == 10")
    else:
        print("nested: else")
else:
    print("else")
```



### Analysing Code Examples
