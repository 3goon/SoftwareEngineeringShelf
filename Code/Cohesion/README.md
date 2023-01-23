# Cohesion
## Defination
Cohesion is a measure of the degree to which the elements of the module are functionally related. It is the degree to which all elements directed towards performing a single task are contained in the component. 

## Types
- **Coincidental** : The elements are not related(unrelated). The elements have no conceptual relationship other than location in source code. It is accidental and the worst form of cohesion. 

- **Logical** : The elements are logically related and not functionally. 
- **Temporal** : The elements are related by their timing involved. A module connected with temporal cohesion all the tasks must be executed in the same time span.
- **Procedural** : Elements of procedural cohesion ensure the order of execution. Actions are still weakly connected and unlikely to be reusable.
- **Communicational** : Two or more elements operate on the same input data or contribute towards the same output data. 
- **Sequential** : An element outputs some data that becomes the input for other element, i.e., data flow between the parts. It occurs naturally in functional programming languages.
- **Functional** : Every essential element for a single computation is contained in the component. A functional cohesion performs the task and functions. It is an ideal situation.

## Examples
- **Coincidental** : Print next line and reverse the characters of a string in a single component.
- **Logical** : A component reads inputs from tape, disk, and network. All the code for these functions is in the same component. Operations are related, but the functions are significantly different.
- **Temporal** : Class that have init/start/stop )ex: Timer)
- **Procedural** : Read data from database and return it to caller in a result set.
- **Communicational** : Update record in the database and send it to the printer. 
- **Sequential** : A tools class with too many un related methods in it.
- **Functional** : Read log record

## Nice to remember
- We always prefer `high cohesion`.

## Source(s)
- [Wikipedia](https://en.wikipedia.org/wiki/Cohesion_(computer_science))