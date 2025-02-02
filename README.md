# React Native: Accessing State Before Initialization

This repository demonstrates a common error in React Native: accessing a state variable before it has been initialized.  The `Bug.js` file shows the problematic code, while `BugSolution.js` provides the corrected version.

## Problem
Accessing state before the component has mounted often results in undefined or null values, leading to unexpected errors or crashes. This issue is exemplified in `Bug.js`.

## Solution
The solution involves using a conditional rendering or a default value to gracefully handle cases where the state is not yet initialized.  `BugSolution.js` presents the corrected approach.

This simple example highlights a critical aspect of React Native development – state management and asynchronous operations. Always ensure that your state is properly initialized before attempting access.