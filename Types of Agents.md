## 1. Simple Reflex Agents
   *  Acts only the current percept and ignores previous ones.
   *  Acts on condition-action rule.
   *  Works only in a [fully-observable environment](./Agent%20Environments.md)
## 2. Model-Based Reflex Agents.
   * Works by finding a rule whose condition matches the current situation.
   * Can handle a [partially observable environment](./Agent%20Environments.md) 
   * Keeps track of internal state, adjusted by each percept and depends on percept history
   * Updates requires info of:
     * How the world revolves independently of the agent.
     * How agent actions affect the world.
## 3. Goal-Based Agents.
   * Does decisions based on distance from the __goal__ (description of desirable situations).
   * Allows an agent to choose among multiple possibilities, the one that reaches a goal state.
   * It's knowledge are modifiable, thereby making these flexible.
## 4. Utility-Based Agents.
   * End uses become building blocks
   * Can decide which action is best for when multiple possible alternatives exist.
   * Sometimes achieving the desired goal is not enough.
   * Agent __happiness__ is considered.
## 5. Learning Agent
   * A type of agent that learns from past experiences or has learning capabilities.
   * It starts with basic knowledge, then acts and adapts automatically by learning. 
   * Four components:
      1. __Learning__  - responsible for improvements
      2. __Critic__ - describes how well an agent is doing 
      3. __Performance__ - It is responsive for selecting external action
      4. __Problem generator__ - Responsible for suggesting new actions for informative experiences.
