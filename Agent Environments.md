* An environment is everything in the world which
surrounds the agent.
* It is where agents live, operate, and provide the agent with someting to sense or act upon.

## Fully vs Partially observable
* Whether or not agent can sense or access the complete state of the environment everytime.
* A fully observal environment is easy as maintaining an internal state of the world is unneeded.
## Static vs Dynamic
  * If an environment changes while an agent is thinking, then it is dynamic
  * Static environments are easier as the agent does not need to check the environment every action.
  * Examples:
    * Static - Puzzle
    * Dynamic - Driving
##  Discrete vs Continuous
  * If there is a finite number of percepts and performable actions within an environment, it discerete, else  continuous.
  * Examples:
    * Discrete - Chess
    * Dynamic - Driving
## Deterministic vs Stochastic
  * If an agent's current state and selected action can completely determine the next state of the environment, then the environment is called a deterministic environment.
  * A stochastic environment is random in nature and cannot be
determined completely by an agent.
  * In a deterministic, [fully observable environment](#fully-vs-partially-observable), there is NO uncertainty.
## Single-agent vs Multi-agent
  * Whether one or more agents are operating in an environment.
  * Agent design works differently for the multi-agent case.
## Episodic vs sequential
  Episodic - only current percent is needed for an action.
  Sequential - requires memory of past actions to determine next best action.
## Known vs Unknown 
  * Not an environment feature, instead it is an agent's state of knowledge for an action
  * Known - agent knows results of all actions.
  * Unknown - Agent needs to learn how the environment works to perform an action.
  * Possible for known to be partially observable, and unknown to be fully observable.
## Accessible vs Inaccessible 
  * Whether an agent can obtain complete and accurate info about an environment's state
  * Examples:
    * Aaccessible - Empty room whose state is captured by a temperature reading.
    * Inaccessible - An event on Earth.
