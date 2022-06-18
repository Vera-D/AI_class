# AI_class
Repo for notes and resources for AI course and related topics

The course is based on the book: Artificial Intelligence: A Modern Approach, by Stuart J. Russell and Peter Norvig.

# Topics
## Searching 
TERMS
**agent** is anything that can be viewed as percieving its environment through sensors and acting on that environment through actuators

**rational agent** is one that does the right thing

**reflex agents** base their actions on a direct mapping from states to actions.

**simple reflex agents** respond directly to percepts

**model-based reflex agents** maintain internal state to track aspects of the world

**goal-based agents** act to achieve their goals, consider future actions and desirability of their outcomes. (see planning agents)

**utility-based agents** maximize their own expected hapiness

**problem solving agents** use atomic representations (state of the world)

**PEAS** Performance, Environment, Actuators, Sensors

**percept** refers to an agent's perceptual inputs at any given instant

start state
actions
goal state
cost
successors

**search** process of looking for a sequence of actions that reaches a goal.

**search algorithm** takes a problem as input and returns a solution in the form of an action sequence.



exhastive search (brute force)
state space
informed search
heuristic
    - manhattan distance
    - euclidean distance 
evaluation function
node
search tree
minimize the value of function
depth first search 

greedy best-first search: get to a solution quickly, it ognores the cost of the path that has already been traveresed, solution is not necessarily optimal, resemles depth first search. Time complexity O(b^m)

uniform cost

**A* search** is a type of best-first search

memory-bounded heuristic search: drawback is space consumption


