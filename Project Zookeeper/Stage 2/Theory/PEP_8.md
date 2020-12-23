# Theory: PEP 8

Table of contents:

[↑ PEP 8](#Theory:-PEP-8)

1. [PEPs](##PEPs)
2. [The length of a line](##The-length-of-a-line)
3. [Avoid extra spaces](##Avoid-extra-spaces)
4. [Quotes](##Quotes)
5. [What's next?](##What's-next?)

How to write code that is clean and easy to read? That is the question that you bump into when moving from simple single-line programs to more complicated ones. In the beginning, it may seem unimportant, but in real life, programming is a process that involves a lot of people that work together, so you spend more time reading code than writing it.

Although Python is often more readable than other programming languages because of its minimalistic syntax, just syntax itself is not enough. It is the way you write code that affects general readability. That is why you need to follow common conventions about programming style, so other programmers could read your code easily.

You may ask, where do these conventions come from? There is a document that is called [PEP 8](https://www.python.org/dev/peps/pep-0008/). The key idea of it is to use the same code style for all python projects as if they were written by the same programmer. This document guarantees that even a beginner will easily understand the code, written by any other developer.

## PEPs

Before going further, let’s talk about PEP for a moment. PEP stands for **Python Enhancement Proposal**. There are different types of PEP and the most useful one for beginners is the informational PEP. PEPs of this kind typically describe commonly accepted guidelines or conventions about the language, so they can be very helpful. Besides PEP 8, which is an official style guide, another great PEP to look at is [the Zen of Python](https://www.python.org/dev/peps/pep-0020/).

Since we know what PEP 8 is, let’s read a bit from it.

## The length of a line

Do not use more than 79 characters in a line of code. Shorter lines look better in code editors. During this course, we will learn several ways to achieve it.

## Avoid extra spaces
Sometimes you may add some spaces even if you don't really need it. This will reduce the readability of your code.

- **Avoid extra spaces within parentheses**

Good:
```
print('Hello!')
```

Bad:
```
print( 'Hello!' )
```

- **Avoid an extra space before an open parenthesis.**

Good:
```
print('some text')
```
Bad:
```
print ('some text')
```

## Quotes
As it was already mentioned, you can use either single or double quotes to define strings. Please, choose one that you like the most and consistently use it in your code. The only recommendation in PEP 8 is that if a string contains single or double quotes, you should use the other one to avoid backslashes.

Good:
```
print("It's a good string!")
```
Bad and harder to read:
```
print('It\'s a bad string!')
```
As you can see, the first example is easier to read.

## What's next?
Later on, you will learn a lot of things about Python and become a more skillful programmer, but following the code style will always remain important. Do not worry, though: you do not need to learn all the conventions at once; just open them from time to time after learning something new. We will also give parts of these conventions in this course.