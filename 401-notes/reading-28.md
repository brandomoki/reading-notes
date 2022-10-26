# Component Lifecycle / useEffect Hook

## effects hook

- What purpose does useEffect serve in a function component compared to its counterpart(s) in class components?

  - The Effect Hook lets you perform side effects in function components

- When using the useEffect Hook:

  - What does useEffect do?
    - it tells react that your component needs to do something after the render
  - Why is useEffect called inside a component?
    - Placing useEffect inside the component lets us access the count state variable (or any props)


- Explain the importance of properly implementing effects with Cleanup

  - it is important to clean up so that we don’t introduce a memory leak
  