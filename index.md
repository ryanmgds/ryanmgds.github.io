## Welcome to Ryan's Github Pages

You can use the [editor on GitHub](https://github.com/ryanmgds/self-repository-tri-3/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Calculator Highlights page

In coding languages, Reverse Polish Notation is used to calculate math expressions by using Stacks and the Shunting-yard algorithm to parse through the inputed data

Ex: 6 * 15 becomes 6 15 *

Operators are stored in a hash map based off of order of operations - which ones come first and thus take precedence

private final Map OPERATORS = new HashMap<>(); { // Map<"token", precedence> OPERATORS.put("*", 3); OPERATORS.put("/", 3); OPERATORS.put("%", 3); OPERATORS.put("+", 4); OPERATORS.put("-", 4); }

### replit

https://replit.com/@ryanmgds/challenge#Main.java

### Tech talk notes

Unit 1 Key Learnings, Tech Talk 1 Notes Queues are a type of data structure in which elements are inserted at the end of a queue and removed from the beginning - first in first out

Stacks are a type of data structure in which elements are inserted at the beginning of a queue and removed from the beginning - first in last out

Queue.add(1)

Queue.add(2)

Queue.delete()

Result: {2}

Stack.add(1)

Stack.add(2)

Stack.delete()

Result: {1}

Tech Talk 0 Notes Data Structures are a method of organizing data - variables, sequences, and databases are all data structures. Data structures and algorithms work well together to create otpimized and efficient code.

Impaerative paradigms use statements to change a program's state. Object Oriented Paradigms use objects and classes.

Linked Lists are a type of data structure in which each piece of data contains a reference link to the next piece of data, meaning that the next node can be referenced through the cucrent node
