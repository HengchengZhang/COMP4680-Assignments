# COMP4680-Assignments

### Assigments and feedbacks for COMP4680 2022, S2

## Assignment1
94/100

Q1: 

Q2: 9/10. 2(d) Missing steps.

Q3: Full mark.

Q4: good

Q5: -2: You should prove that the lower bound is still reachable by giving a specific non-negative example.

Q6: 

Q7: d) incorrect result

Q8: Good approach.

Q9: Good. The logic of your proof is somewhat backwards; make it clear what you are deriving and from what. Also, your second last line is false.

Q10: 10/10

## Assignment2
82.5/100

Q1: Full mark.

Q2: 8/10. First row condition is incorrect (should be 38).

Q3: -4: In the first 3 questions, you should show convexity by correctly explicitly showing those sets to be intersection of halfspaces. -1: In (d), what if x_0=y? Should not be intersection of halfspaces. -0.5: Proof not rigorous in (e). -2: Wrong derivation in (f).

Q4: Q4: 11.5/15

Feedback:
a) 3/3 
b) 2.5/3 
Poor notation, either explain what you mean or use standard notation where it is a sum over I instead of a_i
c) 3/3 
d) 3/3 
e) 0/3 
m is dependent on p and thus the two half spaces are not well defined

Q5: Good work 

Q6: Good

Q7: (a) Other cases for y should be sumYes > 1, not >= 1. (b) Need to assume x is sorted. (c) Equality holds on a different condition actually (yi * xi is the same for all i).

Q8: Good. I think you have misunderstood the extra constraint; it ask that x is at least the ones vector.

## Assignment3
85/100

Q1: (a) no objective function required here in this question. Otherwise well done!

Q2: (b) it is good to be looking for non-equality in the constrainsts, but you have the wrong answer. We have -1 < x_2 < 1.

Q3: 23/30. (a) Specify the case of no solution as -inf; (b) What if any l_i > u_i?

Q4: -2: You should mention the Slater's conditions. -1: > is different from not<=.

Q5: Good

Q6: You did not mention that the domain feasibility constraint only holds for feasible x. (-1)
Missing a nabla in the last two lines.
14/15

## Assignment4
63/100

Q1: (b) The  last row is unclear. You need a bit more justification because page 281 only talks about the weak max-min ineq. (d) You need to prove for all arbitrary norms, not for all arbitrary p-norm.



Q2 a,b: (a,b) Please show steps or alternatively, cite your source (e.g., the textbook).



Q2(c,d): -3: c lack process. -5: d.



Q3: Proved the hint correctly. 3a: need to explain why it unbounded below otherwise (-2). 3b: |x|>1 is unbounded only for |v_i|>2, you need to show this and also that it is less than 1/4 v_i^2 when |v_i|<=2, |x|>1 (-3). 3c: should explain the last step more, -2. 23/30



Q4: you also need to show that the problem is convex; incorrect answer to a star and b star

## Assignment5
91.5/100

Q1: a: Need derivation -8. b: Great. c: hessian seems to give wrong answer numerially: not sure where the bug is, implementation is of merit (-0.5). rest: good

Q2: 

Q3: 20/20

## Assignment6
84/100

Q1: (1.2.1) Why can SGD escape from local minima?
(1.2.2) A bit more conceptual difference of adagrad is needed. For example, how does adagrad adapt the learning rates to the parameters?
(1.2.3) Storage is also another problem for second-order methods.
(1.3) The effect of batch size and of initial point is unclear in your answer.

Q2: Wrong number of parameters, should be 32832+128+4160+128+195 = 37443 (-3). (d) no improvement (-3). 54/60
