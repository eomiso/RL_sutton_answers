# Exercise 1.4 : Learning from exploration

## Question
What is the probability that agent learns from exploratory moves?

## Answer
1. The probablity to choose that certain exploratory action(according to the consequence, it might reduce or increase).
2. The probablity to choose a greedy action.


## Featured Answer
1. With the step size parameter appropriately reduced, and assuming the exploration rate is fixed, the probability set with no learning from exploration is the value of each state given the optimal action from them on is taken, whereas with learning from exploration it is the __expected__ value of each state including the activ exploration policy.\
    Using the former is better to learn, as it reduces __variance__ from sub-optimal future states (e.g. if you can win a game of chess in one move, but if you perform another move your opponent wins) The former would result in more wins all other htings being equal.

