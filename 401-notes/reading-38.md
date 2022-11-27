# Redux - Asynchronous Actions

## async actions

- Why use Redux middleware?
  - Redux middleware were designed to enable writing logic that has side effects.

- Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.

- How are we accommodating async in our Redux app?
  - we will use thunk

## thunk middleware

- Why would you need redux-thunk middleware?
  - used to delay the dispatch of an action, or to dispatch only if a certain condition is met

- Redux Thunk middleware allows you to write action creators that return a ____ instead of an action.
  - function

- Describe how any return value from the inner thunk function will be made available.
  - available as return value
  