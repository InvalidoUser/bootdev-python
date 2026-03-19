## Optional Input and Two Results

```python
def build_message(name, greeting="Hello"):
    message = f"{greeting}, {name}!"
    status = "ready"
    return message, status
```

Question) Explain how the function uses default values and multiple return values.

My Answer)
How the function on the left uses default values:
The 2nd input parameter greeting has an equal sign next to it 
with a string "Hello". This means that it is its default value 
that it resorts to when there is no argument fed into the function 
for that variable.
How the function uses multiple return values:
It returns both message and status variables separated by a comma.

Boots' Response)
Excellent work! You correctly identified that the greeting parameter 
has a default value of "Hello", which the function falls back on when 
the caller does not provide an argument for it. You also pointed out 
that the function returns two values — message and status — separated 
by a comma, which means the caller can receive and store them in two 
separate variables. Well done — a thorough and precise explanation.
