**Description:**
Create a simple multiple-choice quiz game using Python. The program should ask the user a series of questions and check their answers. After all the questions have been answered, the program should display the final score.

**Requirements:**

1. The user will choose between three topics, and then be given three questions in that topic.
2. The quiz should consist of at least 9 questions. (3 per topic)
2. Each question should have multiple choices, and the user should input their answer.
3. The program should compare the user's answer with the correct answer using conditional branching (`if` statements).
4. Keep track of the user's score and display it at the end of the quiz.
5. You can assume the user will enter only lowercase letters (but for a challenge, have the program function correctly with uppercase letters as well!)
6. Use meaningful prompts for questions and provide feedback on whether the answer is correct or incorrect.

**Example Output:**

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
