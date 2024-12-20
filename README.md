# React Router Dom v6 Nested Routes Issue

This repository demonstrates a common issue encountered when working with nested routes in React Router Dom v6.  The problem lies in how nested routes are defined and handled, leading to the nested routes not rendering correctly despite the parent route rendering as expected.

The `bug.js` file contains the problematic code, and `bugSolution.js` provides the corrected implementation.  This issue highlights the importance of correctly structuring nested routes within the `Routes` component to ensure proper rendering.

## How to Reproduce

1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.
4. Navigate to the application in your browser. You will observe that the nested routes do not render.  Examine `bug.js` for the incorrect setup.
5. Then check `bugSolution.js` to see the correct implementation.