# Express REST API

## Review: ES6 Classes

- Classes are a template for creating ____.

  - objects

- Can a class declaration be hoisted?

  - no it cannot

- How would you describe a constructor and contextual “this” to a non-technical friend?

  - A constructor is a do all object and this fills in what to do

## Using Express Routing

- Within Express, what does routing refer to?

  - This is the direction pointing to an endpoint

- What is the difference between a route path and a route method?

  - Route methods come from HTTP methods and is attached to an instance
  - Route paths define endpoints they can be strings, or regular expressions

- When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?

  - With multiple callback functions, it is important to provide next as an argument to the callback function and then call next() within the body of the function to hand off control to the next callback

## Express Routing

- What is an Express Router?

  - Its a mini express app

- By what mean do we initialize express.Router() in an express server?

  - We call an instance and apply routes to it that our application uses

- What do we use route middleware for?

  - this allows us to do something or have checks prior to running the route
  