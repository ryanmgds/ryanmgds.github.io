## Welcome to Ryan's Github Pages
## Calculator Highlights page

In coding languages, Reverse Polish Notation is used to calculate math expressions by using Stacks and the Shunting-yard algorithm to parse through the inputed data

Ex: 6 * 15 becomes 6 15 *

Operators are stored in a hash map based off of order of operations - which ones come first and thus take precedence

private final Map OPERATORS = new HashMap<>(); { // Map<"token", precedence> OPERATORS.put("*", 3); OPERATORS.put("/", 3); OPERATORS.put("%", 3); OPERATORS.put("+", 4); OPERATORS.put("-", 4); }


## Replit containing all deployed code

Week 0: https://replit.com/@ryanmgds/challenegs-week-0#Main.java

Week 1:

Week 2: https://replit.com/@ryanmgds/challlenege-week-2#Main.java

Week 3:



# Tech talk notes

## Week 0
-Notes Data Structures are a method of organizing data - variables, sequences, and databases are all data structures. Data structures and algorithms work well together to create otpimized and efficient code.

-using the HashMap to with a Runnable action so that the main file of each challenge can be run. This was probably the most important, key part to figuring out this challenge. This also helps keep all the challenges organized so that the menu can iterate through the HashMap.
Impaerative paradigms use statements to change a program's state. Object Oriented Paradigms use objects and classes.

-try and catch implementation: the try & catch helps account for user error

-implementing getters and setters so that in the swapToLowHighOrder function, we can actually use the getters and setters to swap the values

## Week 1

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
Linked Lists are a type of data structure in which each piece of data contains a reference link to the next piece of data, meaning that the next node can be referenced through the cucrent node

-linked lists are lists that are linked in one direction though variables within each object within the list. head is the first node of the linked list tail is the last node of the linked list the head of the linked list will link to the next node and so on. The last node (tail) will link to null since there isn’t anything else after it.

## Week 2
-after the expression is in RPN format, I iterate through the String Arraylist reverse_polish which is the reverse polish notation. Then, if the token is not an operator (essentially, it is a number) I push it to the stack. Otherwise, if the token is an operator than I pop the top two values off the stack and perform an operation on these values. I had to create individual (if) statements to check the operator. If it is a %, ^, +, -, *, /, etc. Then, I store the value obtained from the operation in “result” and push result back into the Stack This is essentially how we calculate from RPN notation.

## Week 3
-simplest sorting algorithm
-Takes the most time to run
-repeatedly swaps adjacent elements if in wrong order
-Time complexity of O(n^2) because two for loops go through entire array
