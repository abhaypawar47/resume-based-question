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
______________________________________________________________________________________
# 🛠️ Tools & Platforms Interview Questions                                           |
                                                                                      |
**Technologies Covered:** `Git`, `GitHub`, `Jupyter Notebook`, `Visual Studio Code`   |
______________________________________________________________________________________|
### 🔀 Git (8 Questions)

1.  **What is Git?** Git is a distributed version control system used to track code changes, enable collaboration, and manage project history.

2.  **Difference between Git and GitHub?** * **Git:** A version control system (local tool) that tracks changes in source code.
    * **GitHub:** A web-based platform that provides hosting for Git repositories, facilitating collaboration and project management.

3.  **What does `git clone` do?** Copies a remote repository to your local system, including all version history.  
    ```bash
    git clone [https://github.com/user/repo.git](https://github.com/user/repo.git)
    ```

4.  **What is `git commit` vs `git push`?**
    * **`git commit`:** Saves your staged changes to your local repository's history.
    * **`git push`:** Sends your committed changes from your local repository to a remote repository (e.g., GitHub).

5.  **How to undo a commit?**
    * **`git revert <commit-hash>`:** Creates a new commit that undoes the changes of a previous commit (safe for shared history).
    * **`git reset --hard <commit-hash>`:** Moves the branch pointer to a previous commit and discards all subsequent changes (destructive, use with caution on shared branches).

6.  **What is a Git branch?**
    A branch is a lightweight, movable pointer to a commit. It represents a separate line of development, allowing you to work on new features or bug fixes independently without affecting the main codebase.
    ```bash
    git checkout -b feature/login # Creates and switches to a new branch
    ```

7.  **What is the purpose of `.gitignore`?**
    A `.gitignore` file specifies intentionally untracked files and directories that Git should ignore. This is crucial for preventing unnecessary files (e.g., build artifacts, `node_modules/`, `.env` files, IDE configurations) from being committed to the repository.

8.  **How do you resolve merge conflicts?**
    Merge conflicts occur when Git cannot automatically reconcile differences between two branches being merged. To resolve:
    1.  Git will mark the conflicting sections in the files.
    2.  Manually edit the conflicting files to choose which changes to keep.
    3.  Stage the resolved files: `git add .`
    4.  Commit the resolution: `git commit -m "Resolved merge conflict"`

---

### 🌐 GitHub (6 Questions)

1.  **What is GitHub used for?**
    GitHub is primarily used for:
    * Hosting Git repositories.
    * Collaborative code development via pull requests and code reviews.
    * Issue tracking and project management.
    * Continuous Integration/Continuous Deployment (CI/CD) with GitHub Actions.
    * Project documentation (Wikis, READMEs).
    * Community building for open-source projects.

2.  **What is a pull request (PR)?**
    A Pull Request (PR) is a feature on GitHub (and similar platforms) that allows developers to notify team members about changes they've pushed to a branch in a repository. It's a formal request to merge your changes from one branch (e.g., a feature branch) into another (e.g., `main`), enabling code review, discussions, and automated checks before merging.

3.  **How do GitHub forks work?**
    Forking creates a personal copy of a repository under your GitHub account. This allows you to freely experiment with changes without affecting the original (upstream) repository. You can then make changes in your forked repository and later propose these changes back to the original repository via a pull request.

4.  **What is GitHub Actions?**
    GitHub Actions is a CI/CD (Continuous Integration/Continuous Delivery) platform directly integrated into GitHub. It allows you to automate workflows to build, test, and deploy your code directly from your repository. You define workflows in YAML files (`.github/workflows/`), which can be triggered by various events like pushes, pull requests, or scheduled times.

5.  **How to secure a GitHub repository?**
    * **Branch Protection Rules:** Prevent direct pushes to sensitive branches (e.g., `main`), require pull request reviews, status checks, and linear history.
    * **Two-Factor Authentication (2FA):** Enable 2FA for all collaborators to add an extra layer of security.
    * **`.gitignore` and Secret Scanning:** Use `.gitignore` to prevent sensitive files from being committed. Enable GitHub's secret scanning to detect exposed secrets.
    * **Manage Collaborators and Permissions:** Regularly review and restrict access to the minimum necessary permissions for each user or team.
    * **Audit Logs:** Monitor audit logs for unusual activity.

6.  **How to contribute to open source?**
    1.  **Fork the Repository:** Create a copy of the project under your GitHub account.
    2.  **Clone Your Fork:** Clone your forked repository to your local machine.
    3.  **Create a New Branch:** Make a new branch for your specific feature or bug fix (`git checkout -b your-feature-branch`).
    4.  **Make Changes:** Implement your code changes.
    5.  **Commit and Push:** Commit your changes to your branch and push them to your forked repository on GitHub.
    6.  **Open a Pull Request:** Go to the original (upstream) repository on GitHub and open a pull request from your branch to their `main` or `development` branch, explaining your changes.

---

### 📓 Jupyter Notebook (8 Questions)

1.  **What is Jupyter Notebook?**
    Jupyter Notebook is an open-source web application that allows you to create and share documents containing live code, equations, visualizations, and narrative text. It's widely used in data science, machine learning, and scientific computing for interactive development and reproducible research.

2.  **Which languages does Jupyter support?**
    Jupyter Notebook is language-agnostic. While it's most commonly used with **Python** (via the IPython kernel), it supports over 40 programming languages, including R, Julia, Scala, and many others, through the concept of "kernels."

3.  **What are the components of a Jupyter Notebook?**
    A Jupyter Notebook document (`.ipynb` file) consists of:
    * **Cells:** The basic units of a notebook.
        * **Code Cells:** Contain executable code (e.g., Python, R).
        * **Markdown Cells:** Contain text formatted using Markdown, often for explanations, titles, or comments.
        * **Raw Cells:** Contain text that is not rendered by the notebook.
    * **Kernel:** The computational engine that runs the code in the cells.
    * **Output:** The results generated by executing code cells (e.g., text, tables, plots, error messages).

4.  **How to install and run Jupyter Notebook?**
    You can install Jupyter Notebook using pip (Python's package installer):
    ```bash
    pip install notebook
    ```
    To run it, open your terminal or command prompt in your desired project directory and type:
    ```bash
    jupyter notebook
    ```
    This will open a new tab in your web browser with the Jupyter Notebook interface.

5.  **What is a kernel in Jupyter?**
    A kernel in Jupyter is a separate process that runs and interprets the code executed within a Jupyter Notebook. When you run a code cell, the request is sent to the kernel, which executes the code and sends the results back to the notebook interface. For Python, the default kernel is IPython.

6.  **How to export a notebook?**
    Jupyter Notebooks can be exported to various formats via the `File > Download as` menu option. Common export formats include:
    * `.ipynb` (the native notebook format)
    * `.py` (Python script)
    * `.html` (HTML web page)
    * `.pdf` (PDF document, often requiring LaTeX installation)
    * `.md` (Markdown)

7.  **How to display plots in Jupyter?**
    To display plots inline within a Jupyter Notebook, you typically use plotting libraries like Matplotlib or Seaborn. You'll often include a "magic command" at the beginning of your notebook:
    ```python
    import matplotlib.pyplot as plt
    # Or for Seaborn: import seaborn as sns

    %matplotlib inline 
    # This magic command ensures that plots are displayed directly in the notebook output.

    # Your plotting code here
    plt.plot([1, 2, 3], [4, 5, 6])
    plt.show()
    ```

8.  **What are Jupyter magic commands?**
    Jupyter magic commands are special commands (not part of Python syntax) that extend the capabilities of the IPython kernel. They start with `%` (line magics, affecting a single line) or `%%` (cell magics, affecting the entire cell). They are used for tasks like timing code, running external scripts, interacting with the system shell, and configuring the notebook environment.
    * **Examples:**
        * `%timeit`: Measures the execution time of a single line of code.
        * `%%time`: Measures the execution time of the entire cell.
        * `%ls`: Lists files in the current directory (like `ls` in bash).
        * `%run script.py`: Executes a Python script.
        * `%%writefile my_script.py`: Writes the content of the cell to a file.

---

🧑‍💻 Visual Studio Code (VS Code) (8 Questions)

1.  **What is Visual Studio Code?**
    Visual Studio Code (VS Code) is a free, open-source, and highly extensible code editor developed by Microsoft. It's lightweight yet powerful, offering robust support for various programming languages, debugging, integrated Git control, and a rich marketplace for extensions.

2.  **Key features of VS Code?**
    * **IntelliSense:** Smart code completion, parameter info, quick info, and member lists for various languages.
    * **Built-in Terminal:** Integrated command-line interface for running commands without leaving the editor.
    * **Git Integration:** Seamless integration for version control operations (staging, committing, pushing, pulling, branching, resolving conflicts).
    * **Extensions Marketplace:** A vast ecosystem of extensions to add language support, debuggers, themes, and tools.
    * **Debugging Tools:** Comprehensive debugging capabilities with breakpoints, call stacks, variable inspection.
    * **Multi-root Workspaces:** Ability to work with multiple project folders in one VS Code instance.

3.  **How to install extensions in VS Code?**
    You can install extensions easily:
    1.  Open the Extensions view by clicking the Extensions icon on the Activity Bar on the side of the window (or press `Ctrl+Shift+X`).
    2.  Search for the desired extension in the search bar.
    3.  Click the "Install" button next to the extension.
    VS Code will typically prompt you to reload the window to activate the extension.

4.  **What is a workspace in VS Code?**
    A VS Code workspace is essentially a configuration that defines how VS Code interacts with one or more root folders (your project directories) and their associated settings. It's particularly useful for larger projects or when you're working on multiple related projects simultaneously. Workspaces are saved as `.code-workspace` files.

5.  **How to run code in VS Code?**
    * **Code Runner Extension:** The simplest way for many languages. Install the "Code Runner" extension, then right-click in the editor and select "Run Code" (or use the shortcut).
    * **Integrated Terminal:** Open the integrated terminal (`Ctrl+` `` ` ``) and execute your code using the appropriate command (e.g., `python your_script.py`, `node your_app.js`).
    * **Debugging Tools:** For languages with debugger support, you can configure a `launch.json` file and use the Run and Debug view (`Ctrl+Shift+D`) to run your code with debugging enabled.

6.  **How to use Git inside VS Code?**
    VS Code has excellent built-in Git integration:
    1.  **Initialize Repository:** Open a folder that is not yet a Git repository, and VS Code will prompt you to initialize one.
    2.  **Source Control View:** Click the Source Control icon (`Ctrl+Shift+G`) in the Activity Bar to see all tracked, modified, and untracked files.
    3.  **Stage/Commit:** Hover over files to stage them (`+` icon), then enter a commit message and click the checkmark to commit.
    4.  **Push/Pull/Branch:** Use the "..." menu in the Source Control view or the status bar at the bottom to push, pull, create/switch branches, and perform other Git operations.

7.  **How to use the debugger in VS Code?**
    1.  **Set Breakpoints:** Click in the gutter next to a line number in your code to set a breakpoint (a red circle appears).
    2.  **Run and Debug View:** Go to the Run and Debug view (`Ctrl+Shift+D`).
    3.  **Configure Launch:** If no `launch.json` exists, VS Code will prompt you to create one, often detecting your language.
    4.  **Start Debugging:** Press `F5` (or click the green play button) to start the debugger.
    5.  **Inspect:** Use the "Variables," "Watch," "Call Stack," and "Breakpoints" panels to inspect the program's state. Use the debug controls (step over, step into, continue) to navigate your code.

8.  **What are VS Code settings?**
    VS Code settings allow you to customize almost every aspect of the editor's behavior and appearance. They are primarily managed through JSON files:
    * **User Settings:** Applied globally to all VS Code instances (`settings.json` located in your user profile).
    * **Workspace Settings:** Applied only to the current workspace/folder (`.vscode/settings.json` within your project folder). These override user settings.
    You can access them via `File > Preferences > Settings` (or `Ctrl+,`).
    ```json
    {
      "editor.tabSize": 2,
      "editor.formatOnSave": true,
      "editor.fontSize": 14,
      "files.autoSave": "afterDelay"
    }
    ```

---

### 💡 Tips for Tool-Based Interview Questions

* **Know the Basics Cold:** Be able to confidently execute and explain fundamental Git commands (`add`, `commit`, `push`, `pull`, `merge`, `rebase`, `branch`, `checkout`).
* **Real-World Workflow:** Be prepared to describe a typical Git/GitHub workflow you've followed in a project, emphasizing collaboration aspects (e.g., feature branching, pull request reviews).
* **Jupyter for Data Analysis:** For Jupyter, highlight your understanding of its interactive nature for data exploration, visualization, and rapid prototyping. Mention how it helps in creating reproducible reports.
* **VS Code Productivity:** For VS Code, showcase how you leverage its features to enhance your productivity (e.g., specific extensions you use, custom settings, debugging techniques, keyboard shortcuts).
* **Problem-Solving:** If asked about a problem, like a merge conflict, explain the steps you would take to diagnose and resolve it.
* **"Why this tool?"**: Be ready to briefly articulate why you choose these tools over alternatives (e.g., Why Git vs. SVN? Why VS Code vs. Atom/Sublime?).
````

