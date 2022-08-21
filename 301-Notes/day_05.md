# React Putting it all together

1. What is the single responsibility principle and how does it apply to components?
    * A component should be responsible for one

1. What does it mean to build a ‘static’ version of your application?
    * build a version of your app that renders your data model UI, but doesnt use state and has no interactivity.

1. Once you have a static application, what do you need to add?
    * You need to identify what needs state and implement it.

1. What are the three questions you can ask to determine if something is state?
     1. Is it passed in from a parent via props? If so, it probably isn’t state.

     1. Does it remain unchanged over time? If so, it probably isn’t state.

     1. Can you compute it based on any other state or props in your component? If so, it isn’t state.

1. How can you identify where state needs to live?
    * a single component above all the components that need state

## Higher-Order Functions

1. What is a “higher-order function”?
    * Functions that operate other Functions are Higher order functions.

1. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
    * line 2 is returning a function that checks if m is > n

1. Explain how either map or reduce operates, with regards to higher-order functions.
    * map is the higher order function and returns the newly mapped array to be used in the lower function

