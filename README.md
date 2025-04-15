1. What is the MERN Stack?
Answer: MERN Stack is a full-stack JavaScript framework using MongoDB (database), Express.js (backend framework), React (frontend library), and Node.js (server runtime). It’s popular for building fast, scalable web apps with one language—JavaScript.
2. What is MongoDB, and why use it in MERN?
Answer: MongoDB is a NoSQL database that stores data in flexible, JSON-like documents. It’s used in MERN because it’s scalable, easy to integrate with JavaScript, and great for handling unstructured data.
3. How does Express.js work in the MERN Stack?
Answer: Express.js is a lightweight framework for Node.js that handles server-side logic, like routing and APIs. In MERN, it connects React to MongoDB by managing HTTP requests.
4. What is React, and what makes it special?
Answer: React is a JavaScript library for building user interfaces. It’s special because it uses a virtual DOM for fast updates and reusable components for easier coding.
5. What is Node.js, and why is it important in MERN?
Answer: Node.js is a runtime that lets you run JavaScript on the server. In MERN, it powers the backend, making the stack fully JavaScript-based.
6. What’s the difference between SQL and NoSQL databases?
Answer: SQL uses fixed tables (e.g., MySQL), while NoSQL (like MongoDB) uses flexible documents or key-value pairs, ideal for dynamic data in MERN apps.
7. How do you install the MERN Stack?
Answer: Install Node.js (includes npm), then use npm to add Express (npm install express), React (npx create-react-app), and MongoDB (via its site or npm package mongoose).
8. What are React components?
Answer: Components are reusable building blocks in React, like functions or classes, that return UI elements. Example: a button or a navbar.
9. What’s the virtual DOM in React?
Answer: It’s a lightweight copy of the real DOM. React updates it first, compares changes, and only updates the real DOM where needed—makes it fast!
10. What are hooks in React?
Answer: Hooks are functions (like useState, useEffect) that let you use state and lifecycle features in functional components, introduced in React 16.8.
11. How do you manage state in React?
Answer: Use useState for simple state, Context API for app-wide data, or Redux for complex state management across components.
12. What’s Redux, and when do you use it?
Answer: Redux is a library for managing app state in one central store. Use it for big apps where state changes need to be tracked globally, like e-commerce carts.
13. What’s the event loop in Node.js?
Answer: It’s a process that handles async tasks in Node.js’s single-threaded model. It keeps the app running smoothly by queuing tasks like API calls.
14. How do you create an API in Express.js?
Answer: Set up Express, define routes (e.g., app.get('/users', (req, res) => res.json(data))), and start the server with app.listen(port).
15. What’s middleware in Express.js?
Answer: Middleware are functions that run between a request and response, like logging (console.log) or authentication checks.
16. How do you connect MongoDB to Node.js?
Answer: Use the mongoose package (npm install mongoose), connect with mongoose.connect('mongodb://url'), then define schemas and models.
17. What’s a schema in MongoDB?
Answer: A schema defines the structure of data in MongoDB, like fields (name, age) in a collection. With Mongoose, it’s a JavaScript object.
18. How do you perform CRUD operations in MongoDB?
Answer: Use Mongoose methods: create() (POST), find() (GET), updateOne() (PUT), deleteOne() (DELETE).
19. What’s JWT, and how do you use it in MERN?
Answer: JWT (JSON Web Token) is for secure user authentication. Generate a token on login, verify it in Express middleware, and protect routes.
20. How do you handle errors in Express.js?
Answer: Use error-handling middleware: app.use((err, req, res, next) => res.status(500).json({ error: err.message })).
21. What’s the difference between props and state in React?
Answer: Props are data passed to components (read-only), while state is internal data managed within a component (mutable).
22. How do you fetch data in React?
Answer: Use useEffect with fetch or axios: useEffect(() => { fetch('/api').then(res => setData(res.data)) }, []).
23. What’s a RESTful API?
Answer: It’s an API design using HTTP methods (GET, POST, PUT, DELETE) to manage resources, like /users for user data.
24. How do you secure a MERN app?
Answer: Use HTTPS, JWT for auth, helmet for headers, sanitize inputs, and store passwords with bcrypt.
25. What’s the difference between let, const, and var?
Answer: var is function-scoped and hoisted, let is block-scoped, const is block-scoped and can’t be reassigned (but objects can mutate).
26. How do you optimize React performance?
Answer: Use lazy loading (React.lazy), memoization (useMemo, React.memo), and avoid unnecessary re-renders.
27. What’s CORS, and how do you handle it in Express?
Answer: CORS (Cross-Origin Resource Sharing) controls access between domains. Add cors package: app.use(cors()).
28. What’s the purpose of package.json in Node.js?
Answer: It’s a file that lists project details, dependencies (like Express), and scripts (like npm start).
29. How do you handle async operations in Node.js?
Answer: Use callbacks, promises, or async/await. Example: await fetchData() instead of nested callbacks.
30. What’s indexing in MongoDB?
Answer: Indexing speeds up queries by creating a lookup for fields (e.g., db.collection.createIndex({ name: 1 })).
31. How do you deploy a MERN app?
Answer: Build React (npm run build), serve it with Express, deploy to Vercel/AWS, and connect MongoDB Atlas.
32. What’s server-side rendering (SSR) in React?
Answer: SSR renders React components on the server, sending HTML to the client for faster load and better SEO.
33. How do you implement WebSockets in MERN?
Answer: Use Socket.IO: set up a server (io.on('connection', socket => ...)) and connect from React.
34. What’s the difference between map() and forEach() in JavaScript?
Answer: map() returns a new array with transformed values, forEach() just loops without returning anything.
35. How do you test a React component?
Answer: Use Jest and React Testing Library: write tests like render(<Button />) and check output with screen.getByText().
36. What’s Mongoose in MERN?
Answer: Mongoose is an ODM (Object Data Modeling) library for MongoDB, making it easier to define schemas and query data.
37. What’s prop drilling in React?
Answer: It’s passing props through multiple component layers. Avoid it with Context API or Redux.
38. How do you handle file uploads in MERN?
Answer: Use multer in Express (app.post('/upload', multer().single('file'), ...)), save to server or cloud.
39. What’s the difference between useEffect and useLayoutEffect?
Answer: useEffect runs after render, useLayoutEffect runs before, for DOM updates like measurements.
40. How do you scale a MERN app?
Answer: Use load balancers, caching (Redis), horizontal scaling (more servers), and optimize database queries.
41. What’s GraphQL, and can it replace REST in MERN?
Answer: GraphQL is a query language for APIs, letting clients request exact data. It can replace REST for flexibility.
42. How do you debug a MERN app?
Answer: Use console.log, Chrome DevTools for React, Node’s --inspect flag, and Postman for APIs.
43. What’s a higher-order component (HOC) in React?
Answer: An HOC is a function that takes a component and returns a new one with added features, like authentication.
44. How do you handle variables in MERN?
Answer: Use a .env file with dotenv package (require('dotenv').config()), access with process.env.KEY.
45. What’s lazy loading in React?
Answer: It’s loading components only when needed (const LazyComp = React.lazy(() => import('./Comp'))) to boost performance.
46. How do you write unit tests for Node.js?
Answer: Use Jest or Mocha: test('adds 1 + 2', () => expect(1 + 2).toBe(3)).
47. What’s the aggregation framework in MongoDB?
Answer: It’s a pipeline for processing data (e.g., $group, $match)—like SQL’s GROUP BY but more flexible.
48. How do you prevent SQL injection in MongoDB?
Answer: MongoDB uses BSON, not SQL, but sanitize inputs with libraries like express-validator to avoid injection.
49. What’s the difference between SSR and CSR?
Answer: SSR (Server-Side Rendering) renders on the server for speed/SEO, CSR (Client-Side Rendering) renders in the browser for interactivity.
50. How do you stay updated with MERN trends?
Answer: Follow blogs (Medium, Dev.to), join communities (Reddit, Discord), and build projects with new tools like Next.js.
