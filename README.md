--------------------------------------------------------------
**💌Frontend: React.js, HTML5, CSS3, JavaScript, Bootstrap** |
--------------------------------------------------------------

## ✅ React.js (15 Questions)

1.  **What are React components?**
    Components are reusable UI pieces. Function components use hooks; class components have state and lifecycle methods.

2.  **What’s JSX?**
    A syntax extension mixing HTML-like tags with JavaScript, compiled by Babel into `React.createElement` calls.

3.  **Function vs class components?**
    Function components are simpler, use hooks; class components are stateful and include lifecycle methods.

4.  **What are hooks?**
    Functions like `useState`, `useEffect`, `useContext` that enable state and lifecycle-like features in functional components.

5.  **Explain `useState`.**
    Hook to add state in functions. Returns current state and setter:
    ```js
    const [count, setCount] = useState(0);
    ```

6.  **Explain `useEffect`.**
    Performs side effects (fetching, subscriptions). Can mimic mount/update/unmount with dependency array.

7.  **What’s virtual DOM?**
    A lightweight in-memory tree React uses to diff and efficiently update the real DOM.

8.  **Keys in lists—why?**
    Helps React track items. Unique keys prevent unnecessary re-renders and maintain identity.

9.  **Prop drilling & alternatives.**
    Passing props deeply. Alternatives: Context API, Redux, or component composition.

10. **What are React fragments?**
    `<React.Fragment>` or `<>...</>` groups multiple children without adding extra DOM nodes.

11. **Controlled vs uncontrolled components?**
    Controlled: React state drives inputs. Uncontrolled: DOM ref holds value; React reads via ref.

12. **Error boundaries?**
    Class components with `componentDidCatch` catch runtime errors in child components to prevent whole app crash.

13. **HOC vs render props?**
    HOC is a function wrapping a component. Render prop is a component accepting a function that returns JSX.

14. **React Context use-case?**
    Avoids prop drilling; useful for themes, locales, auth, global stores.

15. **What’s Suspense?**
    For code splitting and async rendering; works with `React.lazy` to load components lazily.

---

## 🧱 HTML5 (7 Questions)

1.  **New HTML5 semantic tags?**
    `<header>`, `<nav>`, `<main>`, `<footer>`, `<section>`, `<article>`, `<aside>`, `<figure>` improve structure and SEO.

2.  **Difference between `<article>` and `<section>`?**
    `<article>` is a self-contained content unit; `<section>` groups related content thematically.

3.  **What’s the purpose of `<canvas>`?**
    A drawable area controlled via JavaScript—for graphics, charts, games.

4.  **Explain `<picture>` and `srcset`.**
    Enables responsive images with different sources based on device DPI or width.

5.  **What are Web Storage APIs?**
    `localStorage` (persistent) and `sessionStorage` (per-tab) allow client-side key-value storage.

6.  **`<input type="date">—browser support?**
    Supported in modern browsers; older ones fallback to plain text input.

7.  **What’s the `draggable` attribute?**
    Enables native drag-and-drop behaviors on elements.

---

## 🎨 CSS3 (10 Questions)

1.  **CSS Flexbox vs Grid?**
    Flexbox is 1D layout (row/column). Grid is 2D (rows and columns) ideal for complex layouts.

2.  **Explain `box-sizing: border-box`.**
    Makes width include padding/border—easier sizing.

3.  **What’s a CSS variable?**
    Custom properties:
    ```css
    :root { --main-color: #06c; }
    color: var(--main-color);
    ```

4.  **Difference between `.class1 .class2` and `.class1.class2`?**
    `.class1 .class2`: descendant. `.class1.class2`: same element must have both classes.

5.  **What’s BEM methodology?**
    Naming convention: `block__element--modifier` for scalable, maintainable CSS.

6.  **Explain `:nth-child`.**
    Selects elements based on position, e.g. `li:nth-child(odd)`.

7.  **How does `position: sticky` work?**
    Acts like relative until a threshold; then sticks as if fixed within its parent.

8.  **What’s CSS Grid `fr` unit?**
    Fractional unit dividing available space.

9.  **Explain CSS transitions vs animations.**
    Transitions animate between states on change. Animations are fully scripted keyframe-based movements.

10. **What’s a media query?**
    CSS rules applying at certain viewport sizes:
    ```css
    @media (max-width: 600px) { /* ... */ }
    ```

---

## 💻 JavaScript (13 Questions)

1.  **`let` vs `const` vs `var`.**
    `var` is function-scoped, can be hoisted. `let`/`const` are block-scoped; `const` cannot be reassigned.

2.  **Explain closures.**
    Function retains access to outer scope variables even after outer has returned.

3.  **What’s event delegation?**
    One event handler on a parent handles multiple child events via event bubbling.

4.  **Difference between `==` and `===`.**
    `==` converts types, `===` checks both type and value equality.

5.  **What are Promises?**
    Objects for async results: `promise.then`, `promise.catch`, and `async`/`await`.

6.  **Explain `this` keyword.**
    Context depends on invocation: method, function, arrow, or `bind`, `call`, `apply`.

7.  **How does `async`/`await` work?**
    Syntax sugar over promises; `await` pauses until a promise resolves.

8.  **What’s event loop?**
    JS runtime mechanism handling asynchronous callbacks from the task queue after the call stack clears.

9.  **Explain array methods: `map`, `filter`, `reduce`.**
    * `map`: transforms elements.
    * `filter`: selects elements.
    * `reduce`: accumulates into a single value.

10. **Spread vs rest syntax?**
    * Spread (`...`): decompresses arrays/objects into individual elements/properties.
    * Rest (`...`): collects remaining elements into an array or object.

11. **What’s a module in JS?**
    `import`/`export` allows encapsulation and reuse of code across files.

12. **How to deep-clone an object?**
    Use `structuredClone()`, `JSON.parse(JSON.stringify(...))`, or libraries like Lodash's `cloneDeep`.

13. **Explain debouncing vs throttling.**
    * **Debounce:** wait after the *last* event in a series before executing (e.g., search input).
    * **Throttle:** fire at most every `N` milliseconds, even if events are continuous (e.g., scroll, resize).

---

## 🔲 Bootstrap (5 Questions)

1.  **What is Bootstrap?**
    Popular CSS+JS UI toolkit; responsive grid, components, utility classes.

2.  **Explain Bootstrap grid system.**
    12-column system with classes like `.col-md-6`, responding via breakpoints (sm, md, lg, etc).

3.  **How to customize Bootstrap styles?**
    Override variables via Sass before importing Bootstrap, or use utility-first classes and custom CSS.

4.  **How to use Bootstrap modals?**
    Use `data-bs-toggle="modal"` and `data-bs-target="#myModal"`, or via JavaScript API.

5.  **What are utility classes?**
    Prebuilt helper classes (e.g., `.mt-3`, `.text-center`, `.d-flex`) to minimize custom CSS.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

____________________________________________________________________________
## 🗄️ Backend & Databases Interview Questions (MySQL, MongoDB, PostgreSQL) |
____________________________________________________________________________

### 🐬 MySQL (10 Questions)

1. **What is MySQL?**  
   MySQL is an open-source relational database management system based on SQL (Structured Query Language).

2. **What are the different types of JOINs in MySQL?**  
   - INNER JOIN  
   - LEFT JOIN (or LEFT OUTER JOIN)  
   - RIGHT JOIN (or RIGHT OUTER JOIN)  
   - FULL JOIN (not supported directly, use UNION of LEFT and RIGHT JOIN)

3. **What is the difference between `WHERE` and `HAVING` clause?**  
   - `WHERE` filters rows before aggregation.  
   - `HAVING` filters groups after aggregation.

4. **How does indexing work in MySQL?**  
   Indexes speed up data retrieval. Common types include B-tree, Full-text, and Hash indexes.

5. **What is normalization?**  
   The process of organizing data to reduce redundancy and improve data integrity. Includes forms like 1NF, 2NF, 3NF.

6. **What is a primary key vs foreign key?**  
   - Primary key: uniquely identifies a row.  
   - Foreign key: a reference to a primary key in another table.

7. **What is ACID in databases?**  
   - Atomicity, Consistency, Isolation, Durability — properties ensuring reliable transactions.

8. **Difference between `TRUNCATE`, `DELETE`, and `DROP`?**  
   - `DELETE`: removes specific rows.  
   - `TRUNCATE`: removes all rows, faster.  
   - `DROP`: deletes the table structure entirely.

9. **How do you prevent SQL injection?**  
   Use prepared statements, parameterized queries, and ORM libraries.

10. **What is a stored procedure?**  
    A saved SQL block that can be reused. Can contain logic and parameters.

---

### 🍃 MongoDB (10 Questions)

11. **What is MongoDB?**  
    MongoDB is a NoSQL document database that stores data in flexible, JSON-like documents (BSON).

12. **What is a document in MongoDB?**  
    A document is a key-value pair structure similar to JSON. Example:  
    ```json
    { "name": "John", "age": 30 }
    ```

13. **Difference between MongoDB and MySQL?**  
    - MongoDB: schema-less, document-based.  
    - MySQL: schema-based, relational.

14. **What is a collection in MongoDB?**  
    Equivalent to a table in SQL. It holds a group of related documents.

15. **What is indexing in MongoDB?**  
    Improves query performance. Common indexes: single field, compound, text, geospatial.

16. **What are MongoDB aggregation pipelines?**  
    A series of stages (`$match`, `$group`, `$sort`, etc.) to process documents and compute results.

17. **What is the difference between `find()` and `aggregate()`?**  
    - `find()` is for basic queries.  
    - `aggregate()` is for advanced data processing and transformations.

18. **What are replicas in MongoDB?**  
    Replica sets provide redundancy and high availability. Includes primary and secondary nodes.

19. **How do you ensure data consistency in MongoDB?**  
    By using replica sets, write concerns, and transactions (since v4.0).

20. **What is sharding in MongoDB?**  
    Distributes data across multiple machines for horizontal scaling.

---

### 🐘 PostgreSQL (10 Questions)

21. **What is PostgreSQL?**  
    PostgreSQL is an advanced, open-source object-relational database known for standards compliance and extensibility.

22. **How is PostgreSQL different from MySQL?**  
    PostgreSQL supports advanced features like full-text search, custom data types, and better compliance with SQL standards.

23. **What is a CTE in PostgreSQL?**  
    Common Table Expression: a temporary result set used within `WITH` clauses for readability and modular queries.

24. **What are some data types unique to PostgreSQL?**  
    - `JSON`, `JSONB`  
    - `ARRAY`, `HSTORE`, `UUID`, `ENUM`, `CIDR`

25. **Explain `SERIAL` and `BIGSERIAL`.**  
    Auto-incrementing integer types, similar to `AUTO_INCREMENT` in MySQL.

26. **How does indexing differ in PostgreSQL?**  
    Supports B-tree, Hash, GIN, GiST, BRIN indexes for various use cases.

27. **What is a window function in PostgreSQL?**  
    Performs a calculation across a set of rows related to the current row.  
    Example: `ROW_NUMBER()`, `RANK()`, `LEAD()`, `LAG()`

28. **What is `VACUUM` in PostgreSQL?**  
    Reclaims storage by removing obsolete row versions created by updates/deletes.

29. **What is a trigger in PostgreSQL?**  
    A function that automatically executes in response to certain table events (INSERT, UPDATE, DELETE).

30. **How do you manage JSON data in PostgreSQL?**  
    PostgreSQL supports `JSON` and `JSONB` types with powerful query and indexing capabilities.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------


