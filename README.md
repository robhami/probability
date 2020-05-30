# probability

How to Compute Probability: Equally Likely Outcomes
Sometimes, a statistical experiment can have n possible outcomes, each of which is equally likely. Suppose a subset of r outcomes are classified as "successful" outcomes.

The probability that the experiment results in a successful outcome (S) is:

P(S) = ( Number of successful outcomes ) / ( Total number of equally likely outcomes ) = r / n


### Sets ###
A set is a well-defined collection of objects.
Each object in a set is called an element of the set.
Two sets are equal if they have exactly the same elements in them.
A set that contains no elements is called a null set or an empty set.
If every element in Set A is also in Set B, then Set A is a subset of Set B.



A set is usually denoted by a capital letter, such as A, B, or C.
An element of a set is usually denoted by a small letter, such as x, y, or z.
A set may be described by listing all of its elements enclosed in braces. For example, if Set A consists of the numbers 2, 4, 6, and 8, we may say: A = {2, 4, 6, 8}.
The null set is denoted by {} or ∅.
Sets may also be described by stating a rule. We could describe Set A from the previous example by stating: Set A consists of all the even single-digit positive integers.

The list of all possible outcomes from a statistical experiment is called the sample space. And a particular outcome or collection of outcomes is called an event.

You can see that a sample space is a type of set. It is a well-defined listing of all possible outcomes from a statistical experiment. And an event in a statistical experiment is a subset of the sample space.

### Set Operations ###
Suppose we have a sample space S defined as follows: S = {1, 2, 3, 4, 5, 6}. Within that sample space, suppose we define two subsets as follows: X = {1, 2} and Y= {2, 3, 4}.

The union of two sets is the set of elements that belong to one or both of the two sets. Thus, if X is {1, 2} and Y is {2, 3, 4}, the union of sets X and Y is:
X ∪ Y = {1, 2, 3, 4}

Symbolically, the union of X and Y is denoted by X ∪ Y.

The intersection of two sets is the set of elements that are common to both sets. Thus, if X is {1, 2} and Y is {2, 3, 4}, the union of sets X and Y is:
X ∩ Y = {2}

Symbolically, the intersection of X and Y is denoted by X ∩ Y.

The complement of an event is the set of all elements in the sample space but not in the event. Thus, if the sample space is {1, 2, 3, 4, 5, 6}, and Y is {2, 3, 4}, the complement of set Y is:
Y' = {1, 5, 6}

On this website, we denote the complement of set Y as Y'. In other places, you may see the complement of set Y denoted as Yc.

### The Sample Space ###
* A sample space is a set of elements that represents all possible outcomes of a statistical experiment.
* A sample point is an element of a sample space.
* An event is a subset of a sample space - one or more sample points.

### Probability of an Event ###
With some statistical experiments, each sample point is equally likely to occur. In this situation, the probability of an event is very easy to compute. It is:

P(E) =	Number of sample points in event/Number of sample points in sample space	

Think about the toss of a single die. The sample space consists of six possible outcomes (1, 2, 3, 4, 5, and 6). And each outcome is equally likely to occur. Suppose we defined Event A to be the die landing on an odd number. There are three odd numbers (1, 3, and 5). So, the probability of Event A would be 3/6 or 0.5.

### Types of events ###
* Two events are mutually exclusive if they have no sample points in common.
* Two events are independent when the occurrence of one does not affect the probability of the occurrence of the other.

Which of the following sets represent an event when you roll a die?

A.   {1}
B.   {2, 4,}
C.   {2, 4, 6}
D.   All of the above

The correct answer is D. Remember that an event is a subset of a sample space. The sample space is any integer from 1 to 6. Each of the sets shown above is a subset of the sample space, so each represents an event.


Consider the events listed below. Which are mutually exclusive?

A.   {1}
B.   {2, 4,}
C.   {2, 4, 6}

Two events are mutually exclusive, if they have no sample points in common. Events A and B are mutually exclusive, and Events A and C are mutually exclusive; since they have no points in common. Events B and C have common sample points, so they are not mutually exclusive.

Suppose you roll a die two times. Is each roll of the die an independent event?

Yes. Two events are independent when the occurrence of one has no effect on the probability of the occurrence of the other. Neither roll of the die affects the outcome of the other roll; so each roll of the die is independent.

### Definitions and Notation ###
Before discussing the rules of probability, we state the following definitions:

* Two events are mutually exclusive or disjoint if they cannot occur at the same time.
* The probability that Event A occurs, given that Event B has occurred, is called a conditional probability. The conditional probability of Event A, given Event B, is denoted by the symbol P(A|B).
* The complement of an event is the event not occurring. The probability that Event A will not occur is denoted by P(A').
* The probability that Events A and B both occur is the probability of the intersection of A and B. The probability of the intersection of Events A and B is denoted by P(A ∩ B). If Events A and B are mutually exclusive, P(A ∩ B) = 0.
* The probability that Events A or B occur is the probability of the union of A and B. The probability of the union of Events A and B is denoted by P(A ∪ B) .
* If the occurrence of Event A changes the probability of Event B, then Events A and B are dependent. On the other hand, if the occurrence of Event A does not change the probability of Event B, then Events A and B are independent.

### Rule of Subtraction ###
In a previous lesson, we learned two important properties of probability:

The probability of an event ranges from 0 to 1.
The sum of probabilities of all possible events equals 1.
The rule of subtraction follows directly from these properties.

Rule of Subtraction. The probability that event A will occur is equal to 1 minus the probability that event A will not occur.

P(A) = 1 - P(A')

Suppose, for example, the probability that Bill will graduate from college is 0.80. What is the probability that Bill will not graduate from college? Based on the rule of subtraction, the probability that Bill will not graduate is 1.00 - 0.80 or 0.20.

### Rule of Multiplication ###
The rule of multiplication applies to the situation when we want to know the probability of the intersection of two events; that is, we want to know the probability that two events (Event A and Event B) both occur.

Rule of Multiplication The probability that Events A and B both occur is equal to the probability that Event A occurs times the probability that Event B occurs, given that A has occurred.

P(A ∩ B) = P(A) P(B|A)

Example
An urn contains 6 red marbles and 4 black marbles. Two marbles are drawn without replacement from the urn. What is the probability that both of the marbles are black?

Solution: Let A = the event that the first marble is black; and let B = the event that the second marble is black. We know the following:

In the beginning, there are 10 marbles in the urn, 4 of which are black. Therefore, P(A) = 4/10.
After the first selection, there are 9 marbles in the urn, 3 of which are black. Therefore, P(B|A) = 3/9.
Therefore, based on the rule of multiplication:

P(A ∩ B) = P(A) P(B|A)
P(A ∩ B) = (4/10) * (3/9) = 12/90 = 2/15 = 0.133

### Rule of Addition ###
The rule of addition applies to the following situation. We have two events, and we want to know the probability that either event occurs.

Rule of Addition The probability that Event A or Event B occurs is equal to the probability that Event A occurs plus the probability that Event B occurs minus the probability that both Events A and B occur.

P(A ∪ B) = P(A) + P(B) - P(A ∩ B)

Note: Invoking the fact that P(A ∩ B) = P( A )P( B | A ), the Addition Rule can also be expressed as:

P(A ∪ B) = P(A) + P(B) - P(A)P( B | A )

Example
A student goes to the library. The probability that she checks out (a) a work of fiction is 0.40, (b) a work of non-fiction is 0.30, and (c) both fiction and non-fiction is 0.20. What is the probability that the student checks out a work of fiction, non-fiction, or both?

Solution: Let F = the event that the student checks out fiction; and let N = the event that the student checks out non-fiction. Then, based on the rule of addition:

P(F ∪ N) = P(F) + P(N) - P(F ∩ N)
P(F ∪ N) = 0.40 + 0.30 - 0.20 = 0.50
