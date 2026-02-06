[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/4oW3WLnZ)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=22553750)
# Week 1: Conditionals

This week you'll complete 5 problems that all use **conditional statements** (if, if/else, if/elif/else blocks).

## Learning Resources

Don't know about conditionals yet? CS50 has you covered with multiple ways to learn:

### Full Lecture (1 hour)
**Watch the complete Week 1 lecture:**  
https://www.youtube.com/watch?v=_b6NgY_pMdw

### Read the Notes
**Skim the prepared notes if you prefer reading:**  
https://cs50.harvard.edu/python/notes/1/

### Short Videos (5-10 minutes each)
**Watch specific topics:**
- **Conditionals:** https://cs50.harvard.edu/python/shorts/conditionals/
- **Boolean Expressions:** https://cs50.harvard.edu/python/shorts/boolean_expressions/

### Jump Right In
**Or just figure stuff out as you go!** The problem descriptions will guide you.

---

## Assignment Overview

Complete **ALL** of the following problems from CS50P Week 1:

1. **Deep Thought** - The answer to life, the universe, and everything
2. **Home Federal Savings Bank** - Greetings and money
3. **File Extensions** - Determine media types
4. **Math Interpreter** - A calculator program
5. **Meal Time** - Is it time to eat?

---

## Problem 1: Deep Thought
📁 `deep/deep.py`  
🔗 https://cs50.harvard.edu/python/psets/1/deep/

Implement a program that prompts the user for the answer to the Great Question of Life, the Universe and Everything. Output `Yes` if the user inputs `42` or (case-insensitively) `forty-two` or `forty two`. Otherwise output `No`.

---

## Problem 2: Home Federal Savings Bank
📁 `bank/bank.py`  
🔗 https://cs50.harvard.edu/python/psets/1/bank/

Implement a program that prompts the user for a greeting:
- If the greeting starts with `"hello"`, output `$0`
- If the greeting starts with `"h"` (but not `"hello"`), output `$20`
- Otherwise, output `$100`

Ignore any leading whitespace in the user's greeting, and treat it case-insensitively.

---

## Problem 3: File Extensions
📁 `extensions/extensions.py`  
🔗 https://cs50.harvard.edu/python/psets/1/extensions/

Implement a program that prompts the user for a file name and outputs that file's media type if the file's name ends (case-insensitively) in any of these suffixes:

- `.gif`
- `.jpg`
- `.jpeg`
- `.png`
- `.pdf`
- `.txt`
- `.zip`

If the file's name ends with some other suffix or has no suffix at all, output `application/octet-stream`.

---

## Problem 4: Math Interpreter
📁 `interpreter/interpreter.py`  
🔗 https://cs50.harvard.edu/python/psets/1/interpreter/

Implement a program that prompts the user for an arithmetic expression and then calculates and outputs the result as a floating-point value formatted to one decimal place.

**Assumptions:**
- User's input will be formatted as `x y z` (with spaces)
- `x` is an integer
- `y` is `+`, `-`, `*`, or `/`
- `z` is an integer
- If `y` is `/`, then `z` will not be 0

**Example:** If the user inputs `1 + 1`, your program should output `2.0`.

---

## Problem 5: Meal Time
📁 `meal/meal.py`  
🔗 https://cs50.harvard.edu/python/psets/1/meal/

Implement a program that prompts the user for a time and outputs whether it's breakfast time, lunch time, or dinner time. If it's not time for a meal, don't output anything at all.

**Assumptions:**
- User's input will be formatted in 24-hour time as `#:##` or `##:##`
- Each meal's time range is inclusive

**Required structure:**
```python
def main():
    ...

def convert(time):
    ...

if __name__ == "__main__":
    main()
```

The `convert` function should convert time (a string in 24-hour format) to the corresponding number of hours as a float. For instance, `"7:30"` should return `7.5`.

**Challenge (Optional):**  
Add support for 12-hour times:
- `#:## a.m.` and `##:## a.m.`
- `#:## p.m.` and `##:## p.m.`

---

## Testing Your Code

Before submitting, test each problem with `check50`:
```bash
check50 cs50/problems/2024/python/deep
check50 cs50/problems/2024/python/bank
check50 cs50/problems/2024/python/extensions
check50 cs50/problems/2024/python/interpreter
check50 cs50/problems/2024/python/meal
```

*(Note: Remove `--local` flag - it's not needed)*

---

## Saving Your Work

After completing each problem:

1. Click the **Source Control** icon (left sidebar)
2. Stage your changes (click the **+** button)
3. Type a commit message (e.g., "Complete deep thought")
4. Click **Commit**
5. Click **Sync Changes**

**Do this after each problem so your work is saved!**

---

## Submission

When you've completed all five problems:
- Make sure all files are committed and synced
- Your work will be automatically recorded

---

## Getting Help

- Review the problem specifications at the CS50 links above
- Watch the lecture or shorts if you're stuck on concepts
- Test your code with different inputs
- Ask for help if needed!
