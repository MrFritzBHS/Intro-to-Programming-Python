# Quiz Game

Create a simple multiple-choice quiz game using Python. The program should ask the user a series of questions and check their answers. After all the questions have been answered, the program should display the final score.

## Sample

Try out a sample version of the Quiz Game [here](https://codehs.com/sandbox/stefanfritz/quiz-game-example/run)

## Requirements

|Grade|Requirements|
|:-:|:-|
|C|<ol><li>A welcome message is printed to the user</li><li>The user is presented a quiz with 3 multiple-choice questions one at a time</li><li>The program compares the user's answer with the correct answer using conditional branching (`if` statements) and prints either `"Correct!"` or `"Incorrect"`</li></ol>|
|B|<ol><li>A welcome message is printed to the user</li><li>Allows the user to choose between *two* topics, each with their own set of three questions</li><li>The program compares the user's answer with the correct answer using conditional branching (`if` statements) and prints either `"Correct!"` or `"Incorrect"`.</li><li>When the user guesses incorrectly, print out the correct answer</li><li>After the quiz is complete, tell the user how many times they were correct</li></ol>|
|A|<ol><li>A welcome message is printed to the user</li><li>Allows the user to choose between *three* topics, each with their own set of three questions</li><li>The program compares the user's answer with the correct answer using conditional branching (`if` statements) and prints either `"Correct!"` or `"Incorrect"`.</li><li>The user's guess is case *IN*sensitive meaning if the correct answer is `"a"` the user can type either `"a"` or `"A"`</li><li>When the user guesses incorrectly, print out the correct answer</li><li>After the quiz is complete, tell the user how many times they were correct</li><li>After the quiz is over, print out a different statement depending on the number correct. (Ex: `"You got them all!"`, `"Keep practicing, almost there"`, `"Looks like you need to study"`, etc)</li><li>Includes comments that indicate each section of the quiz (Ex: `# Geography Questions Below`)</li></ol>|

## Example Output

```
Welcome to the Multiple-Choice Quiz Game!

Choose a category:
  Sports, World, Entertainment

> World

~~~ World Trivia ~~~

1. What is the capital of France?
(a) Paris
(b) London
(c) Rome

> a
Correct!

2. Where is Victoria Falls?
(a) Zambia
(b) India
(c) United States

> b
Incorrect. The correct answer is (a) Zambia

3. What county has the largest population?
(a) United States
(b) India
(c) China

> c
Incorrect. The correct answer is (c) China

Quiz complete!
You answered 1 out of 3 questions correctly.
```

**Note:** You should customize the questions, choices, and correct answers for your quiz. Add more questions if you'd like to!

## Tips

You can keep track of the score by adding to a counter variable like so:

```python
num_correct = 0

if answer is correct:
    print("Correct!")
    num_correct = num_correct + 1
else:
    print("Incorrect. The correction answer was...")
```
