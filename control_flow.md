## Decision

In programming, making decision is important. It is a mechanism in which the program runs based on certain conditions. It is just like our real life situation when we have to do something is a condition is met. For example, when it is rain, we stay at home. 

### ``if`` Statement

The first and the simplest conditional statement is ``if`` as follow:

```
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

```
if weather_is_good:
	go_for_a_walk()
have_lunch()
```

``if`` statement is the most basic decision-making in programming.

### ``if-else`` Statement

The `else` statement allows you to specify an alternative block of code to execute if the `if` condition is false.

```
age = 16
if age >= 18:
    print("You are an adult.")
else:
    print("You are not an adult.")
```

```

```

### ``if-elif-else`` Statement

The `elif` (short for else if) statement allows us to check multiple conditions.

```
age = 16
if age >= 18:
    print("You are an adult.")
elif age >= 13:
    print("You are a teenager.")
else:
    print("You are a child.")

```

<pre><div class="dark bg-gray-950 rounded-md border-[0.5px] border-token-border-medium"><div class="flex items-center relative text-token-text-secondary bg-token-main-surface-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md"><span></span></div></div></pre>

### Nested ``if`` Statement
