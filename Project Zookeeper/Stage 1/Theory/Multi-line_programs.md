# Theory: Multi-line programs

Table of contents:

[↑ Multi-line programs](#Theory:-Multi-line-programs)

So far, we have already learned how to write simple Python programs consisting of a single line that just prints a text. However, real programs contain a significant number of lines: from tens and hundreds for small scripts to thousands and even more for large projects. So, in this lesson, we will write a program that prints multiple lines.

Let's consider an example, the following code prints exactly three strings, each on a new line:

```
print("I")
print("know")
print("Python")
```
The output is:
```
I
know
Python
```

You can run this example [here](https://repl.it/languages/python3) or locally if you have already installed Python on your computer.

There are other ways to print the same text using just one function call. We will consider them in the next topics.

The `print` function also allos you to print an empty line with no string specified:

```
print("I")
print()
print("know")
print()
print("Python")
```

Here's the output:
```
I

know

Python
```

However, skipping the line will have no effect:
```
print("And")

print("you?")
```

The output is:
```
And
you?
```