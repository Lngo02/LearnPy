# Theory: Quotes and multi-line strings

You are already familiar with strings that are extremely common and useful in programming. Let's take a look at some features of Python strings related to quotes and multi-line strings.

# Table of contents:

[↑ Quotes and multi-line strings](#Theory:-Quotes-and-multi-line-strings)

1. [Quotes](##Quotes)
2. [Multiline strings](##Multiline-strings)

## Quotes

As you know, a string literal is surrounded by a pair of **single** or **double quotes**. There is basically no difference between the two, but there are some common conventions concerning the use:

- use double quotes if your string contains single quotes, for example, `"You're doing great!"`
- use single quotes if your string contains double quotes, for example, `'Have you read "Hamlet"?'`
- do NOT mix two styles in one literal, for example, something like `"string!'` is NOT correct
- most importantly, be **consistent** in your use!

There is a way to include any quotes in your string, regardless of the style of the outer quotes, and that is to use the **backslash symbol (\)** before the quotes inside of the string. The backslash will basically tell Python that the quote symbol that follows it is a part of the string rather than its end or beginning. It is called **escaping**, and you'll learn about it in detail in the next topics.

So in the examples below both ways of writing the strings are correct and will produce the same result:
```
# example 1
print("You're doing great!")
print('You\'re doing great!')
# example 2
print("Have you read \"Hamlet\"?")
print('Have you read "Hamlet"?')
```

## Multiline strings

Strings can represent a long text, a single character or even zero characters (like an empty string). But so far our strings were just in one line, no matter how long they were. You can also write **multi-line** strings in Python, and to do that you need to use **triple quotes** on each side of the string literal. Again, which quotes to choose, single or double, is up to you, both work fine in Python.

- Multi-line string in double quotes:
```
print("""This
is
a
multi-line
string""")
```

- Multi-line string in single quotes:
```
print('''This
is
a
multi-line
string''')
```

Both examples print the same result:
```
This
is
a
multi-line
string
```

Well, these are just some basics, strings in Python are much more interesting, and there are so many things you can do with them!