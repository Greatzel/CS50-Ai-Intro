Search Problems:

- Agent - Entity that perceives its environment and acts upon that environment

- State - A configuration of the agent in it's environment

- Initian State - A state where an agent begins

- Action - Choices that can be made in a state

- Action  of (s) or Action(s) - Returns the set of actions that can be executed in state s

  - *s* - input
  - *a* - action
 
- Transition Model - A description of what state results from eprforming any applicable action in any state
  - Result(s, a) = returns the state resulting from performing action a in state s
 
- State Space
  - The set of all states reachable from the initial state by any sequence of actions

The State Space can be represented as a graph with nodes and arrows. Nodes can represent the state and arrows can represent the action.

- Goal Test - A way to determine whether a given state is a goal state
- Path Cost - a numerical cost associated with a given path
