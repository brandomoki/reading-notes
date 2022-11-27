# API Integration

## [Review API Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/api-server/)

- Explain the different between a query string parameter and a path parameter.
  - The path parameter defines the resource location, while the query parameter defines sort, pagination, or filter operations. The user's input (the query) is passed as a variable in the query parameter, while each path parameter must be substituted with an actual value when the client makes an API call
- What would our API URL with a path id parameter be given the following information:
  - Domain: http://our-site.com
  - v3
  - model name: stuff
  - id: things
    - URL would look like this <http://our-site.com/v3/stuff/things>
  
- We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.
- Its like breaking it up into searchable segments

## [Review Auth Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/auth-server/)

- Describe how you would use middleware to implement basic and bearer auth.
  - I would use basic to handle sign-in routes and bearer to access user profile info
- Describe the handshake necessary to implement OAuth.
  - handshaking process create/update a local user account in our database, and return an object with a re-authentication/bearer token and the user object
- Describe how Role Based Access Control works to a non-technical friend.
  - allow access to only the users with that permission that their job entails
