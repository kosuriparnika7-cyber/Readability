# Readability
A C program that determines the approximate reading grade level of a text using the Coleman-Liau index, completed as part of Harvard's CS50 Week 2.
# Readability 📖

A C program that determines the approximate reading grade level of a piece of text.

The program counts the number of letters, words, and sentences in the text and uses the Coleman-Liau index to calculate the reading grade level.

This was completed as part of **Harvard's CS50x — Week 2: Arrays**.

## How It Works

The program asks the user to enter a piece of text.

It then counts:

- Letters
- Words
- Sentences

These values are used in the Coleman-Liau formula:

```text
index = 0.0588 × L - 0.296 × S - 15.8
```
Where:

L is the average number of letters per 100 words
S is the average number of sentences per 100 words

The result is rounded to the nearest whole number and displayed as the approximate reading grade level.

If the result is below Grade 1, the program prints:

Before Grade 1

If the result is Grade 16 or higher, it prints:

Grade 16+
What I Used
C
CS50 Library
Strings
Functions
strlen()
isalpha()
for loops
if / else if / else
Floating-point calculations
round()
What I Learned

This problem helped me break a larger problem into smaller functions.

I practiced counting different character types in a string and using those values in a mathematical formula.

I also got more comfortable with functions, loops, strings, character checking, and floating-point calculations.

# How to Run

Compile:

make readability

Run:

./readability

Example:

Text: Congratulations! Today is a great day.
Grade 5
