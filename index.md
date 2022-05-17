## Welcome to Ryan's Github Pages

# WEEK 1 NOTES

Machine learning
- K-nearest neighbors algorithm (when trying to decide the likeness of something relating to past choices and history)
- MOre the data, the better the model, the higher the accuracy
- Supervised learning: uses labeled data to train the model
- Unsupervised learning: uses unlabeled data to train the model
- Reinforcement learning: learns from negative feedback to not make the same mistakes again
- Machine learning model: input to model to output, if its right we take it as final result, if not we give feedback
- Machine learning is used in healthcare, sentiment analysis (social media), fraud detection, and predicting customer choices in e commerce
- Search pricing model: predicts price of something based on availability, time spent, distance, etc, used by companies like uber

Neural network
- Neuron -> thing that holds a number between 0 and 1
- Layers make it so things can be processed
- Activation is the measure of something
- Weights tell the pattern, and bias tells how high the weighted sum needs to be
- Learning is getting the computer to find a valid setting for all these numbers to solve the problem that is presented
- 
- Think of each neuron as a function that takes in the output of all the previous neurons in the previous layer and spits it out as one

Gradient descent
- Gradient descent: underlies how neural networks work but also all machine learning networks
- Training data: data that comes from testing through the functions, it is random
- Each neuron is connected to every other neuron
- Cost function: a way of training the computer
- You need to be able to change the computer how it should change its incorrections
- Through network learning we are just minimizing the cost of a function
- Gradient descent: repeatedly nudging an input of a function by some multiple of the negative gradient, helps converge towards some local minimum of a cost function
- Relative magnitudes tell us which change matters more for our data, another way of thinking about direction
- Extra help: http://neuralnetworksanddeeplearning.com/ 


















# Study Week 2

MCQ Result: 
<img width="1374" alt="Screen Shot 2022-04-26 at 10 11 04 AM" src="https://user-images.githubusercontent.com/72889620/166304763-e148faa5-283d-48be-833a-637b2c3e4d8d.png">

Link to corrections: https://docs.google.com/document/d/1l5BaBwvggB0XlxHto2437yTFrKE1pv5S2DNOvpaOKg0/edit?usp=sharing 


FRQ Result: (didn't take because not taking AP exam)




# Study Week 1

## Unit 6 video notes
- hard coding is difficult for adapting projects
- Programs can make classes through print statements
- using random makes it hard to debug
- classes show behaviors and states of code
- 
## Unit 5 video notes
-classes used to organize data and group them, main way to keep them organized so they aren't scattered
-






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
