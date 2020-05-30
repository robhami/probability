# Rules




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

The probability of an event ranges from 0 to 1. The sum of probabilities of all possible events equals 1. The rule of subtraction follows directly from these properties.

Rule of Subtraction. The probability that event A will occur is equal to 1 minus the probability that event A will not occur.

P(A) = 1 - P(A')

Suppose, for example, the probability that Bill will graduate from college is 0.80. What is the probability that Bill will not graduate from college? Based on the rule of subtraction, the probability that Bill will not graduate is 1.00 - 0.80 or 0.20.

### Rule of Multiplication ###
The rule of multiplication applies to the situation when we want to know the probability of the intersection of two events; that is, we want to know the probability that two events (Event A and Event B) both occur.

Rule of Multiplication The probability that Events A and B both occur is equal to the probability that Event A occurs times the probability that Event B occurs, given that A has occurred.

P(A ∩ B) = P(A) P(B|A)

Example An urn contains 6 red marbles and 4 black marbles. Two marbles are drawn without replacement from the urn. What is the probability that both of the marbles are black?

Solution: Let A = the event that the first marble is black; and let B = the event that the second marble is black. We know the following:

In the beginning, there are 10 marbles in the urn, 4 of which are black. Therefore, P(A) = 4/10. After the first selection, there are 9 marbles in the urn, 3 of which are black. Therefore, P(B|A) = 3/9. Therefore, based on the rule of multiplication:

P(A ∩ B) = P(A) P(B|A) P(A ∩ B) = (4/10) * (3/9) = 12/90 = 2/15 = 0.133

### Rule of Addition ###
The rule of addition applies to the following situation. We have two events, and we want to know the probability that either event occurs.

Rule of Addition The probability that Event A or Event B occurs is equal to the probability that Event A occurs plus the probability that Event B occurs minus the probability that both Events A and B occur.

P(A ∪ B) = P(A) + P(B) - P(A ∩ B)

Note: Invoking the fact that P(A ∩ B) = P( A )P( B | A ), the Addition Rule can also be expressed as:

P(A ∪ B) = P(A) + P(B) - P(A)P( B | A )

Example A student goes to the library. The probability that she checks out (a) a work of fiction is 0.40, (b) a work of non-fiction is 0.30, and (c) both fiction and non-fiction is 0.20. What is the probability that the student checks out a work of fiction, non-fiction, or both?

Solution: Let F = the event that the student checks out fiction; and let N = the event that the student checks out non-fiction. Then, based on the rule of addition:

P(F ∪ N) = P(F) + P(N) - P(F ∩ N) P(F ∪ N) = 0.40 + 0.30 - 0.20 = 0.50