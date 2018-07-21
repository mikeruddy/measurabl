# Measurabl Take Home Test

This demonstration makes the assumption that the user is running a modern ES6 capable browser. Features such as the spread operator, `Set` data type, Object functions and native promises are used.

### Getting Started

To run this project simply run `npm install` followed by `npm start`.

### Prerequisites

You'll need nodeJS installed to be able to run the http-proxy server. Once you run `npm start` the application will be available at `http://localhost:8080/`.

### Unit Testing Strategy

If I were to unit test this, the main functions would be split into a module that could be imported. The functions are pure functions so that dependency on external state is not required, specifically `safeMerge()` and `renderTable()`.