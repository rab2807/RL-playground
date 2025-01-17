# RL-playground

Deep Q-learning to solve different games and puzzles

Framework used:
* <code>pytorch</code>
* <code>gymnasium</code>

---

## Maze Solver
A deep Q-learning (DQN) agent implemented to solve a maze represented as a grid. This project demonstrates reinforcement learning applied to maze navigation problems.

**State space**: Agent position ($[x,y]$)

**Action space**: $\uparrow, \downarrow, \leftarrow, \rightarrow$

**Rewards structure**:
* (-0.2) for each step
* (-1.5) for hitting walls
* (+1.0) for reaching the goal



