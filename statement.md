# Welcome!

這個例子 for one-page playground.

```python runnable
print('Hello World!')
```
---

```python runnable
# {
# autofold
# Please ignore this part
print("TECHIO> terminal -i \"python3 main.py\"")
print("\033[2J")
# }
from random import randint

number_to_guess = randint(0, 100)
n = int(input('Guess my number! '))
while n != number_to_guess:
    if n < number_to_guess:
        print('Too small!')
    else:
        print('Too big!')
    n = int(input('Try again: '))
print('Congratulation! You found it!')
```

# Advanced usage

If you want a more complex example (external libraries, viewers...), use the [Advanced Python template](https://tech.io/select-repo/429)
