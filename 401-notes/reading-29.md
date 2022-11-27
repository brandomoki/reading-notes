# Advanced State with Reducers

## [useReducer hook](https://reactjs.org/docs/hooks-reference.html#usereducer)

- Name an alternative to the useState Hook.
  - useReducer()
  
- Why might the useReducer Hook be preferable to the useState Hook?
  - Handles complex state better

- What are two ways to set the initial state?
  - Pass initial state as a second argument
  - You can also create the initial state lazily. To do this, you can pass an init function as the third argument.

## [Ultimate Guide to useReducer](https://blog.logrocket.com/react-usereducer-hook-ultimate-guide/)

- In terms of state, what does useReducer expect to receive as a parameter?
  - It accepts a reducer function as its first parameter

- What does useReducer return?
  - useReducer returns an array that holds the current state value and a dispatch function
- Explain dispatch to a non-technical recruiter.
  - Dispatch allows us to send an action to the reducer.
  