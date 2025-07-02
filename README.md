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


