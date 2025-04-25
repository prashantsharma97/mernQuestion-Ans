# 📘 Frontend Development Interview Q&A

This document contains categorized **interview questions** on **HTML, CSS, JavaScript, React, and Redux**. It’s great for quick revision, learning, or preparing for frontend developer interviews.

---

## 🔶 HTML & CSS Questions

### 1. Difference between HTML tags and elements?  
**Answer:** Tags are like `<p>` or `<div>`, whereas an element includes the opening tag, content, and closing tag like `<p>Hello</p>`.

### 2. What are attributes in HTML?  
**Answer:** Attributes add extra information to elements, like `class`, `id`, `href`.

### 3. What are void elements in HTML?  
**Answer:** Elements that don’t need a closing tag. Examples: `<br>`, `<img>`, `<input>`.

### 4. What are HTML entities?  
**Answer:** Codes used to display reserved characters. Example: `&lt;` for `<`.

### 5. Difference between `id` and `class` in HTML?  
**Answer:** `id` is unique per element; `class` can be shared by multiple elements.

### 6. Describe HTML layout structure.  
**Answer:** Usually includes: `<header>`, `<nav>`, `<main>`, `<section>`, `<aside>`, `<footer>`.

### 7. How to optimize website assets loading?  
**Answer:** Use minification, compression, lazy loading, CDN, and defer scripts.

### 8. Is nesting of webpages possible?  
**Answer:** Yes, using the `<iframe>` tag.

### 9. Difference between cellpadding and cellspacing?  
**Answer:** `cellpadding` adds space inside a cell; `cellspacing` adds space between cells.

### 10. Ways to display HTML elements?  
**Answer:** Block, inline, inline-block, none, flex, grid, table, etc.

### 11. Difference between `display: none` and `visibility: hidden`?  
**Answer:** `display: none` removes the element from the flow, `visibility: hidden` hides it but keeps the space.

### 12. Difference between `<link>` and `<a>` tag?  
**Answer:** `<link>` is for linking external resources; `<a>` is for hyperlinks.

### 13. Advantages of HTML5?  
**Answer:** Semantic elements, audio/video support, local storage, new APIs, better forms.

### 14. Inline and block elements in HTML5?  
**Answer:** Inline: flows with text (`<a>`, `<span>`), Block: starts on a new line (`<div>`, `<p>`).

### 15. How to specify metadata in HTML5?  
**Answer:** Use the `<meta>` tag inside `<head>`.

### 16. What are semantic elements?  
**Answer:** Tags with meaningful names like `<article>`, `<section>`, `<aside>`.

### 17. Web storage in HTML5?  
**Answer:** `localStorage` and `sessionStorage` store key-value data on the browser.

### 18. What is DOCTYPE in HTML?  
**Answer:** Declares the document type. HTML5 uses `<!DOCTYPE html>`.

### 19. Types of APIs in HTML5?  
**Answer:** Geolocation, Drag-and-Drop, Web Storage, Web Workers, Canvas, etc.

---

## 🎨 CSS Questions

### 20. What is the box model in CSS?  
**Answer:** It includes content, padding, border, and margin.

### 21. How to include CSS in a webpage?  
**Answer:** Inline, internal (`<style>`), external (`<link rel="stylesheet">`).

### 22. Types of CSS selectors?  
**Answer:** Universal, tag, class, ID, attribute, pseudo-class, pseudo-element.

### 23. What are `vh` and `vw`?  
**Answer:** `vh`: viewport height, `vw`: viewport width.

### 24. Difference: inline, inline-block, block?  
**Answer:**  
- `inline`: no height/width support  
- `inline-block`: allows size control  
- `block`: full width

### 25. Pseudo-classes vs Pseudo-elements?  
**Answer:**  
- Pseudo-classes: `:hover`, `:focus`  
- Pseudo-elements: `::before`, `::after`

### 26. Adaptive vs Responsive design?  
**Answer:** Adaptive uses fixed layouts, responsive adjusts fluidly to screen sizes.

### 27. Border-box vs Content-box?  
**Answer:**  
- `border-box`: padding/border included in width  
- `content-box`: padding/border outside width

### 28. What is opacity?  
**Answer:** Transparency level from 0 (invisible) to 1 (opaque).

### 29. Flexbox properties?  
**Answer:** `display: flex`, `justify-content`, `align-items`, `flex-direction`, `flex-wrap`, etc.

### 30. CSS `position` property?  
**Answer:** Values: `static`, `relative`, `absolute`, `fixed`, `sticky`.

### 31. What is media query?  
**Answer:** CSS technique for applying styles based on screen size.

### 32. What is grid system in CSS?  
**Answer:** A 2D layout system using rows and columns.

### 33. Difference between flexbox and grid?  
**Answer:**  
- Flexbox: 1D (row/column)  
- Grid: 2D (row and column)

### 34. What is specificity in CSS?  
**Answer:** Determines which rule is applied when multiple rules match. Inline > ID > Class > Element > *

---
# 💻 JavaScript, React, and Redux Interview Questions

This repository contains a collection of commonly asked JavaScript, React, and Redux interview questions, along with concise answers to help you prepare for technical interviews.

---

## 📌 JavaScript Questions

1. **What are variables in JavaScript?**
   - **Answer:** Variables store data. Declared using `var`, `let`, or `const`.

2. **Difference between `let`, `var`, and `const`?**
   - **Answer:**
     - **`var`**: Function-scoped, hoisted.
     - **`let`**: Block-scoped, not hoisted.
     - **`const`**: Block-scoped, cannot be reassigned.

3. **What are data types in JavaScript?**
   - **Answer:**
     - **Primitive:** `String`, `Number`, `Boolean`, `null`, `undefined`, `Symbol`, `BigInt`
     - **Non-Primitive:** `Object`, `Array`, `Function`

4. **What is an array? Example methods?**
   - **Answer:** An array in JavaScript is an ordered list of elements — used to store multiple values in a single variable.
   - **Methods:** `push()`, `pop()`, `map()`, `filter()`, `reduce()`.
   ## 🍇 Common Array Methods (with Examples)

| Method    | Description                           | Example                                  | Output                            |
|-----------|---------------------------------------|------------------------------------------|-----------------------------------|
| `push()`  | Add item to end                       | `fruits.push('orange')`                  | `['apple', 'banana', 'mango', 'orange']` |
| `pop()`   | Remove item from end                  | `fruits.pop()`                           | `['apple', 'banana']`            |
| `map()`   | Transform each item                   | `fruits.map(f => f.toUpperCase())`       | `['APPLE', 'BANANA', 'MANGO']`   |
| `filter()`| Keep items matching a condition       | `fruits.filter(f => f !== 'banana')`     | `['apple', 'mango']`             |
| `reduce()`| Combine values into single result     | `[1, 2, 3].reduce((a, b) => a + b, 0)`    | `6`                              |


5. **What is an object? Important methods?**
   - **Answer:** A collection of key-value pairs. Methods: `Object.keys()`, `Object.values()`, `hasOwnProperty()`.
   - ## 🧱 Common Object Methods (with Examples)

| Method              | Description                              | Example                          | Output                                  |
|---------------------|------------------------------------------|----------------------------------|-----------------------------------------|
| `Object.keys()`     | Returns all keys as an array             | `Object.keys(user)`              | `['name', 'age', 'isDeveloper']`        |
| `Object.values()`   | Returns all values as an array           | `Object.values(user)`            | `['Prashant', 25, true]`                |
| `Object.entries()`  | Returns array of key-value pairs         | `Object.entries(user)`           | `[['name', 'Prashant'], ['age', 25], ['isDeveloper', true]]` |
| `Object.assign()`   | Copies values from one object to another | `Object.assign({}, user)`        | `{ name: 'Prashant', age: 25, isDeveloper: true }` |
| `hasOwnProperty()`  | Checks if a property exists              | `user.hasOwnProperty('age')`     | `true`                                  |


6. **What is Temporal Dead Zone (TDZ)?**
   - **Answer:** Temporal Dead Zone (TDZ) is the time between when a let or const variable is declared and when it is initialized,
     during which accessing the variable will throw a ReferenceError.,Variables declared with let or const are hoisted, but not initialized — and that's what creates the "dead zone".

7. **What is hoisting?**
   - **Answer:** Variable and function declarations are moved to the top during compile phase.

8. **What is prototype in JavaScript?**
   - **Answer:** Every object has a prototype from which it can inherit properties/methods.

9. **Primitive vs Non-Primitive types?**
   - **Answer:**
     - **Primitive:** Immutable values (e.g., `1`, `true`)
     - **Non-Primitive:** Reference types (e.g., `{}`, `[]`)

10. **Difference between `==` and `===`?**
    - **Answer:**
      - **`==`**: Compares value (loose comparison).
      - **`===`**: Compares value and type (strict comparison).

11. **Pass by value vs Pass by reference?**
    - **Answer:**
      - **Value:** Primitives
      - **Reference:** Objects, Arrays

12. **What is an IIFE?**
    - **Answer:** Immediately Invoked Function Expression. Example: `(function(){})()`.

13. **Higher-order function?**
    - **Answer:** A function that takes or returns another function.

14. **What is `this` keyword?**
    - **Answer:** Refers to the object calling the function.

15. **What is a self-invoking function?**
    - **Answer:** A function that runs immediately when defined.

16. **What are `call()`, `apply()`, and `bind()`?**
    - **Answer:**
      - **`call()`**: Invokes function with arguments.
      - **`apply()`**: Same as `call()`, but takes array of arguments.
      - **`bind()`**: Returns a new function with `this` bound.

17. **What is currying?**
    - **Answer:** Transforming a function with multiple arguments into nested single-argument functions.

18. **What is scope and scope chain?**
    - **Answer:** Scope defines variable access; the scope chain is the hierarchy from local to global.

19. **What is closure in JavaScript?**

    -  **Answer:**
      A closure is a function that remembers the variables from its outer lexical scope even after the outer function has finished executing.

**Example:**
```javascript
function outer() {
    let count = 0;
    return function inner() {
        count++;
        console.log(count);
    }
}

const counter = outer();
counter(); // 1
counter(); // 2
counter(); // 3
counter(); // 4


20. **What are object prototypes?**
    - **Answer:** Objects inherit from `Object.prototype` or custom prototypes.

21. **What are callbacks?**
    - **Answer:** Functions passed as arguments to be executed later.

22. **What is memoization?**
    - **Answer:** Caching function results to avoid recalculating.

23. **What is recursion?**
    - **Answer:** A function calling itself.

24. **What is a constructor function?**
    - **Answer:** A function used to create objects using `new`.

25. **What is the DOM?**
    - **Answer:** Document Object Model — structure of HTML as objects.

26. **What is BOM?**
    - **Answer:** Browser Object Model — window, navigator, etc.

27. **Client-side vs Server-side JS?**
    - **Answer:**
      - **Client:** Runs in the browser.
      - **Server:** Runs on the backend (e.g., Node.js).

28. **What are arrow functions?**
    - **Answer:** Short syntax, no `this` binding.

29. **What is the rest operator?**
    - **Answer:** Gathers remaining arguments: `function(...args)`.

30. **What is the spread operator?**
    - **Answer:** Expands arrays/objects: `let newArr = [...oldArr]`.

31. **What is a Promise?**
    - **Answer:** An object representing future completion of an async operation.

32. **What are classes in JavaScript?**
    - **Answer:** ES6 syntax for creating objects and handling inheritance.

33. **What is object destructuring?**
    - **Answer:** Extracting values: `const {name} = obj;`

34. **What is async/await?**
    - **Answer:** Syntax for writing promises like synchronous code.

35. **What is lexical scoping?**
    - **Answer:** Inner functions have access to outer function variables.

36. **What is the event loop?**
    - **Answer:** Handles async code via the call stack, callback queue, and microtask queue.

37. **What is debouncing?**
    - **Answer:** Delay function call until the user stops triggering the event.

38. **What is throttling?**
    - **Answer:** Limits function execution to once per interval.

39. **`map()`, `filter()`, `reduce()` differences?**
    - **Answer:**
      - **`map()`**: Transforms an array.
      - **`filter()`**: Filters an array.
      - **`reduce()`**: Returns a single value from an array.

40. **How to optimize JS app performance?**
    - **Answer:** Lazy load, reduce DOM access, debounce/throttle, minimize code.

41. **Shallow copy vs Deep copy?**
    - **Answer:**
      - **Shallow:** References nested objects.
      - **Deep:** Full copy including nested objects.

42. **Types of `fetch()` usage?**
    - **Answer:**
      - `.then()`
      - `async/await`
      - With headers, POST, etc.

43. **What is JSON in JS?**
    - **Answer:** JavaScript Object Notation — used for data exchange.

44. **`localStorage` vs `sessionStorage` vs cookies?**
    - **Answer:**
      - **`localStorage`:** Persists until manually deleted.
      - **`sessionStorage`:** Ends with the tab.
      - **Cookies:** Sent with HTTP requests.

45. **What is event bubbling?**
    - **Answer:** Events propagate from child to parent.

46. **What is event capturing?**
    - **Answer:** Events go from parent to child.

47. **What are timing events in JS?**
    - **Answer:** `setTimeout()`, `setInterval()`, `requestAnimationFrame()`.

48. **What is single-threaded in JS?**
    - **Answer:** JS runs one task at a time.

49. **What is Set and Map in JS?**
    - **Answer:**
      - **Set:** Stores unique values.
      - **Map:** Stores key-value pairs.

50. **Useful string methods in JS?**
    - **Answer:** `split()`, `slice()`, `substr()`, `toUpperCase()`, `includes()`.

51. **What is ES6 in JS?**
    - **Answer:** Major JS update: arrow functions, `let`/`const`, promises, classes, etc.

52. **Difference between `null` and `undefined`?**
    - **Answer:**
      - **`null`:** Intentional absence.
      - **`undefined`:** Declared but not assigned.

---

## ⚛️ React Questions

87. **What is React?**
    - **Answer:** A library to build user interfaces using components.

88. **What is state?**
    - **Answer:** A component’s local data.

89. **What is props?**
    - **Answer:** Data passed from parent to child components.

90. **Function vs Class components?**
    - **Answer:**
      - **Function:** Stateless (now can use hooks).
      - **Class:** Older way with lifecycle methods.

91. **Lifecycle methods in function components?**
    - **Answer:** Managed using hooks like `useEffect`.

92. **Lifecycle methods in class components?**
    - **Answer:** `componentDidMount`, `shouldComponentUpdate`, etc.

93. **What is props drilling?**
    - **Answer:** Passing props through multiple levels. Avoid using Context API.

94. **What is a pure component?**
    - **Answer:** Prevents unnecessary re-renders by shallow prop/state comparison.

95. **What are error boundaries?**
    - **Answer:** Catch JS errors in child components. Use `componentDidCatch`.

96. **What is a Hook in React?**
    - **Answer:** Functions to use state and lifecycle in functional components.

97. **`useState` hook?**
    - **Answer:** Adds local state to a function component.

98. **`useEffect` hook?**
    - **Answer:** Side effects like data fetching or subscriptions.

99. **`useReducer` hook?**
    - **Answer:** For complex state logic using reducer functions.

100. **Custom Hook?**
    - **Answer:** Reusable logic extracted into a function using other hooks.

101. **`useMemo` hook?**
    - **Answer:** Memoizes expensive calculations.

102. **`useCallback` hook?**
    - **Answer:** Memoizes functions to avoid re-creating them.

103. **`useRef` hook?**
    - **Answer:** Access DOM nodes or persist values without re-rendering.

104. **`useContext` hook?**
    - **Answer:** Access context values without drilling props.

105. **What is JSX?**
    - **Answer:** HTML-like syntax used in React.

106. **What is virtual DOM?**
    - **Answer:** A lightweight copy of real DOM to optimize rendering.

107. **What is HOC (Higher Order Component)?**
    - **Answer:** Function that returns a new component with enhanced behavior.

108. **What is Routing in React?**
    - **Answer:** Handling navigation with libraries like React Router.

---

## 🔄 Redux Questions

109. **What is Redux?**
    - **Answer:** A state container to manage global state in applications.

110. **Redux flow?**
    - **Answer:** `Component → Action → Reducer → Store → View update`

111. **What is Flux?**
    - **Answer:** Architecture that inspired Redux. Unidirectional data flow.

112. **What are action, reducer, and store?**
    - **Answer:**
      - **Action:** Event with type and payload.
      - **Reducer:** Returns new state.
      - **Store:** Holds state tree.

113. **What is Redux Thunk?**
    - **Answer:** Middleware to handle async logic. Example: API call in action.

114. **`mapStateToProps()` vs `mapDispatchToProps()`?**
    - **Answer:**
      - **`mapStateToProps()`**: Maps state to props.
      - **`mapDispatchToProps()`**: Maps actions to props.

---

## 💡 Key Concepts

- **Hoisting:** Variable and function declarations are moved to the top during the compile phase.
- **Event Loop:** Handles async code via call stack, callback queue, and microtask queue.
- **Promise:** An object representing future completion of an async operation.






