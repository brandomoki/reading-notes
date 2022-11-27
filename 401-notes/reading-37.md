# Combined Reducers

## [Multiple Reducers Example](https://www.youtube.com/watch?v=gBER4Or86hE)

- Why create multiple reducers?
  - Better organize your code
- How would you combine multiple reducers?
  - use the `combineRducers()`
- How will you manage state as an immutable object? why?
  - return a newState object

## [Redux Docs: Using Combined Reducers](https://redux.js.org/usage/structuring-reducers/using-combinereducers/)
  
- combineReducers is a utility function to simplify the most common use case when writing ___ _____ .
  - redux reducers
- Explain how combineReducers assembles the new state tree.
  - combineReducers will call each slice reducer with its current slice of state and the current action
- How would you define initial state in an app using combineReducers?
  - Return new state

## [Redux Docs: Combined Reducer Syntax](https://redux.js.org/api/combinereducers/)

- Why will you want to split your reducing functions as your app becomes more complex?
  - So they can manage their own state
- The _____ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to ____.
  - createStore and combineReducers
- What is a popular convention when naming reducers?
  - Naming them to the slice they manage
  