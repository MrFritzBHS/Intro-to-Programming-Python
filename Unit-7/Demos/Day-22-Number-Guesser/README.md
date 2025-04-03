# Extensions

## Random numbers

Implement a computer-generated secret number by doing the following:

1. Import the random library
2. generate the random value within a specified range

Here's what it looks like (type this at the top of your code):

```python
import random

# wherever you're storing the secret number:
secret_num = random.randint(1,100)
```

This would store a random number from 1 to 100 (inclusive).

## Close guess

If the user is within 5 of the correct answer, tell them "Close!"

For example if the secret number is 25, and the guess is 20, print `"Close!"`. This should also work for the guess 30.
