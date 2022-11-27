# Redux

## Redux Toolkit (RTK)

- What concerns are addressed by Redux Toolkit?
  - "Configuring a Redux store is too complicated"
  - "I have to add a lot of packages to get Redux to do anything useful"
  - "Redux requires too much boilerplate code"

- What does configureStore() do?
  - wraps createStore to provide simplified configuration options and good defaults

- How would I use createSlice()?
  - generates a slice reducer with corresponding action creators and action types.

## What is Mobx?

- How does MobX make it “impossible” to produce an inconsistent state?
  - The strategy to achieve that is simple: Make sure that everything that can be derived from the application state, will be derived. Automatically

- How would we build a reactive user interface?
  - The observer HoC wrapper from the mobx-react-lite package fixes that by basically wrapping the React component in autorun. This keeps the component in sync with the state. This is conceptually not different from what we did with the report before.

## Tutorial

- What take-away(s) did this tutorial provide?
  - Good tutorial for redux