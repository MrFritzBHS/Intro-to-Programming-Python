Mad Libs are a silly word game where random parts of speech are added to sentences to make a funny story.

Create a Mad Libs game where users can input different types of words to complete a story. The program should prompt the user for various types of words (e.g., noun, adjective, verb) and then construct a story using the provided words.

**Requirements:**

1. Use one of these [Mad Libs templates](https://drive.google.com/file/d/1she4AlYATjaajQBzEVGyYp_4DnVkpuv2/view?usp=sharing) and identify all of the parts of speech you are collecting (nouns, verbs, adjectives, etc)
2. Prompt the user to enter words of the specified types (noun, adjective, etc.) and store them in variables for every blank space in your Mad Lib.
3. Use the collected words to replace the placeholders in the story template.
4. Display the final story to the user, with the inserted words. Use multiple `print` commands to break up the length of each line in the story.

---

**Simple Example:**

```
Welcome to Mad Libs!
Enter an adjective: fluffy
Enter a noun: cat
Enter a verb: dance

Here's your Mad Libs story:

Once upon a time, there was a fluffy cat who loved to dance every day.

```

**Extension** 

Add color! Give the user a visual cue to show which text comes from their user input. For example:

> The dog went to the $${\color{red}orchard}$$ and $${\color{red}zapped}$$ some $${\color{red}beans}$$.

### Adding color

You can use ANSI **escape codes** to change the color of the text output. For example:

```python
print("This is " + "\033[31mred" + "\033[0m!")
```
prints:

![image here](https://github.com/MrFritzBHS/Intro-to-Programming-Python/blob/main/Unit-4/Project-Mad-Libs/redText.png?raw=true)

The key is to use the proper esacpe codes. They must be place immediately before any text you'd like to change. To break this down:

- start with `\033[` which says to python "here comes some text style instructions"
- type the number of the color you want (in the example, red is `31`
- type `m` to end the instructions.

Be sure to set your text *back* to black.

#### Using it with a variable:

```python
print("I like to eat " + "\033[32m" + word + "\033[0m every day!")
```

![image here](https://github.com/MrFritzBHS/Intro-to-Programming-Python/blob/main/Unit-4/Project-Mad-Libs/greenText.png?raw=true)

