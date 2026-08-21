# What is a Range?

A range is a type of Python object which is iterable and generates integers that follow a specific pattern. It does not store all values in memory, but generates them on demand.

Ranges are commonly looped over in for loops to generate sequences of numbers that can be processed or otherwise used in the body of the for loop. The behaviour based on the arguments passed to the `range()`{.python} function is similar to that of slicing.

# Basic Syntax

To create a range, you can use the built-in `range()`{.python} function. It can take one, two, or three arguments.

## One Argument

When only one argument is passed, it is interpreted as the `stop` value. The range starts at 0 and goes up to (but does not include) the stop value in steps of 1.

```py-cell
for i in range(5):
    print(i)
```

## Two Arguments

When two arguments are passed, they are interpreted as `start`{.python} and `stop`{.python}. The range starts at the start value and goes up to (but does not include) the stop value in steps of 1.

```py-cell
for i in range(2, 7):
    print(i)
```

## Three Arguments

When three arguments are passed, they are interpreted as `start`{.python}, `stop`{.python}, and `step`{.python}. The range starts at the start value, goes up to (but does not include) the stop value, and increments by the step value.

```py-cell
for i in range(1, 11, 2):
    print(i)
```
