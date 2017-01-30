# ABM-1
Agent Based Model to describe feed strategies in a population where individuals can move,
eat and reproduce themselves.
Codes are developed in NetLogo and Python (some of them).

These are the main features of the present model:

ENVIRONMENT
* The environment is a thorus 
* Its dimensions are 41X41. Is divided in cells of 1X1
* In every cell grows a source (turtle) with some energy

AGENTS

* Agents permorms three actions: eat, move and reproduce themselves
* They eat every source in their cone of vision
* They move according an internal variable
* Everyone spend at least a minimum amount of energy (basal metabolism)
* When they acumulate an specific amount of energy, they reproduce themselves by division.
* When reproducing, agent divides its energy.

