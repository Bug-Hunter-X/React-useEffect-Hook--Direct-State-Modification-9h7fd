# React useEffect Hook: Direct State Modification

This repository demonstrates a common error in React when using the `useEffect` hook: directly modifying state variables instead of using the setter function provided by `useState`.

The `bug.js` file shows the incorrect approach which leads to no change in the UI because React does not detect the direct mutation of the `count` variable.  The `bugSolution.js` file provides the correct implementation using the `setCount` function.

This example highlights the importance of using functional updates for state changes within `useEffect` and other lifecycle methods to ensure that React's state management mechanism works correctly.