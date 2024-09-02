Frontend: React 
React is a JavaScript library for building user interfaces, particularly single-page applications with a 
focus on performance and responsiveness. It helps developers create reusable UI components and 
manage application state efficiently. 
Core Concepts 
Components 
Definition: Components are the building blocks of React applications. They represent UI elements 
that can be reused throughout the application. 
Types: 
Functional Components: Use functions to define components. They are simpler and are becoming 
the preferred choice with the introduction of hooks. 
Class Components: Use ES6 classes to define components. They are more complex and are used when 
lifecycle methods are needed. 
JSX (JavaScript XML) 
Definition: JSX is a syntax extension that allows you to write HTML-like code within JavaScript. It makes 
the structure of the UI more readable and concise. 
Purpose: JSX is transpired into plain JavaScript by tools like Babel, which then creates React elements. 
State and Props 
State: 
Definition: State represents data that changes over time and affects the rendering of components. It 
is local to the component. 
Usage: Components with state can dynamically render content based on user interactions or other 
events. 
Props: 
Definition: Props (short for properties) are read-only attributes passed from parent components to 
child components. 
Usage: They allow components to be reusable with different data inputs. 
Lifecycle Methods (Class Components) 
Definition: Lifecycle methods are hooks into specific points in a component’s lifecycle, such as 
mounting, updating, and unmounting. 
Purpose: They are used to execute code at certain times, such as fetching data when a component 
mounts. 
React Hooks 
Definition: Hooks are functions that let you use state and other React features in functional 
components. 
Common Hooks: 
useState: Manages state in functional components. 
useEffect: Performs side effects in functional components, such as fetching data or subscribing to 
events. 
Advanced Guides 
Context API 
Definition: Context API provides a way to pass data through the component tree without having to 
pass props down manually at every level. 
Usage: It’s useful for managing global state, such as theme settings or user authentication status. 
React Router 
Definition: React Router is a library for handling routing in single-page applications. It allows you to 
navigate between different views or pages. 
Purpose: It enables dynamic route matching and rendering of components based on the current URL. 
State Management Libraries 
Definition: Libraries like Redux or MobX provide more robust state management solutions for larger 
applications. 
Purpose: They help manage global state across multiple components and facilitate predictable state 
changes. 
Backend: SQL 
SQL (Structured Query Language) is used to interact with relational databases. It provides a 
standardized way to manage and manipulate data, define database structures, and perform complex 
queries. 
Core SQL Concepts 
Tables 
Definition: Tables are the fundamental structures in a relational database where data is stored in rows 
and columns. 
Structure: Each table consists of columns (attributes) and rows (records), where columns define the 
data type and rows contain actual data. 
Queries 
Definition: Queries are commands used to interact with the database. They can retrieve, insert, 
update, or delete data. 
Types: 
SELECT: Retrieves data from the database. 
INSERT: Adds new records to a table. 
UPDATE: Modifies existing records. 
DELETE: Removes records from a table. 
Joins 
Definition: Joins are used to combine rows from two or more tables based on a related column. 
Types: 
INNER JOIN: Retrieves matching rows from both tables. 
LEFT JOIN (OUTER JOIN): Retrieves all rows from the left table and matched rows from the right table. 
RIGHT JOIN (OUTER JOIN): Retrieves all rows from the right table and matched rows from the left table. 
FULL JOIN (OUTER JOIN): Retrieves all rows when there is a match in either table. 
Indexes 
Definition: Indexes are special data structures that improve the speed of data retrieval operations. 
Purpose: They help quickly locate and access data without scanning the entire table. 
Transactions 
Definition: Transactions are sequences of SQL operations that are executed as a single unit of work. 
Purpose: They ensure that a series of operations either complete successfully or have no effect if any 
part fails (ACID properties: Atomicity, Consistency, Isolation, Durability). 
Advanced SQL Features 
Stored Procedures 
Definition: Stored procedures are precompiled collections of SQL statements that can be executed as 
a single command. 
Purpose: They encapsulate complex logic and can improve performance by reducing the need to send 
multiple queries from the application. 
Views 
Definition: Views are virtual tables created by a query that selects data from one or more tables. 
Purpose: They provide a way to present data in a specific format or subset without altering the 
underlying tables. 
Triggers 
Definition: Triggers are automatic actions executed in response to certain events on a table, such as 
inserts, updates, or deletes. 
Purpose: They help enforce business rules and maintain data integrity. 
Normalization 
Definition: Normalization is the process of organizing data to reduce redundancy and improve data 
integrity. 
Purpose: It involves dividing large tables into smaller, related tables and defining relationships 
between them. 
