# useState() Hook

## [Introducing Hooks](https://reactjs.org/docs/hooks-intro.html#motivation)

1. What was the motivation for introducing Hooks?

   - Lets you use react features without using a class

2. What changes are important regarding implementing Hooks versus Component Classes?

   - With Hooks, you can extract stateful logic from a component so it can be tested independently and reused.

3. Hooks allow you to reuse stateful logic without changing
   - component hierarchy

## [hooks api](https://reactjs.org/docs/hooks-overview.html)

1. Name two rules imposed by React Hook usage.
   - Only call hooks at the top level
   - Only call hooks from React components
2. How would you identify a custom Hook and why might you create one?

   - You would start the name with "use" then the hook.

## [the state hook](https://reactjs.org/docs/hooks-state.html)

1. What is a Hook?

   - A Hook is a special function that lets you “hook into” React features.

1. When would I use the useState Hook?

   - When you want to use state from another component

1. If you were to add React state to a function component by declaring a state variable:
   - What does calling useState do?
     - useState is a hook to directly hook into the component. Calls a "state variable"
   - What do we pass to useState as an argument?
      - initial state
   - What does useState return?
       - Returns a pair of values
