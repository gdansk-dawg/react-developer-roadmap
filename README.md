# Twinkl React Dev Roadmap (and beyond)

# Table of Contents
1. [Javascript - Fundamentals](#javascript-1)
   - [Dom manipulation](#javascript-11)
   - [Callbacks](#javascript-12)
   - [Promises](#javascript-13)
   - [Async/Await](#javascript-14)
  
2. [Version Control](#version-control-2)
   - [GitLab](#section-21)
   - [GitHub](#section-22)

3. [React](#react-3)
   - [Virtual DOM](#react-31)
   - [Basics of React Components - useState/useEffect](#react-32)
   - [Conditional rendering](#react-33)
   - [Rendering lists](#react-34)
   - [Pure components](#react-35)
   - [Component Splitting](#react-36)
   - [Reusability](#react-37)
   - [Event handlers](#react-38)
   - [Updating complex states immutably](#react-39)
   - [Declarative vs Imperative UI](#react-311)
   - [FInding & Structuring React States](#react-312)
   - [Sharing state between components](#react-313)
   - [Lifting state up](#react-314)
   - [Concised immutable state update](#react-315)
   - [Passing data deeply inside React components](#react-316)
   - [Advanced React Hooks](#react-317)
   - [Performance hooks](#react-318)
   - [Custom Hooks](#react-319)
    
4. [Build Tools](#build-tools-4)
 4.1 [Package Managers](#build-tools-4-1)
  - [Npm](#build-tools-4-1-1)
  - [Yarn](#build-tools-4-1-2)
  - [BunJS](#build-tools-4-1-3)
 4.2 [Module Builders](#build-tools-4-2)
  - [Webpack](#build-tools-4-2-1)
  - [Vite](#build-tools-4-2-2)
 4.3 [Task runners](#build-tools-4-3)
  - [Npm Scripts](#build-tools-4-3-1)
  - [Gulp](#build-tools-4-3-2)
    
1. [Styling](#styling-5)
5.1 [CSS/SASS](#styling-5-1)
5.2 [Styling Libraries](#styling-5-2)
  - [Material UI](#styling-5-2-1)
  - [Emotion](#styling-5-2-2)
  - [Styled Components](#styling-5-2-3)

1. [State Managment Libraries](#sml-6)
   - [Redux Toolkit](#sml-6-1)
   - [Zustand](#sml-6-2)
   - [Context API](#sml-6-3)

2. [Routing - React Router](#routing-7)
  
3. [Typescript](#typescript-8)
   - eslint + airbnb + prettier
4. [API](#api-9)
   - 9.1 [Rest](#api-9-1)
    - [RTK](#api-9-1-1) 
    - [Axios](#api-9-1-2)
   9.2 [GraphQL](#api-9-2)

5.  [Testing](#testing-10)
   9.1 [Unit Testing](#testing-10-1)
    - [Jest](#testing-10-1-1) 
    - [Vitest](#testing-10-1-2)
   9.2 [Integration Testing](#testing-10-2)
    - [Karma](#testing-10-2-1) 
   9.3 [End to End testing](#testing-10-3)
    - [Selenium](#testing-10-3-1)
    - [Cypress](#testing-10-3-1)

6.  [Internationalization](#internationalization-11)
   - [React i18next](#internationalization-11-1)
   - [React Intl](#internationalization-11-2)

7.  [Performance in React](#performance-12)
    - [Profiler](#performance-12-1)
    - [Caching](#performance-12-2)

8.  [Form building](#form-building-13)


Beyond React:

1. SSR / CSR.
2. NextJS.
3. DynamoDB.
4. Backend - NodeJS.
5. Devops (CI/CD githubACTIONS).
6. Infrastructure (docker)
7. AWS (Dynamo + lambda)


<div id='javascript-1'/>

# 1. Javascript Fundamentals

This is where it all starts, you need to have basic react knowledge to 

<div id='javascript-11'/>

## Dom Manipulation
DOM manipulation in JavaScript enables dynamic changes to the content, structure, and style of web pages. It involves using JavaScript to select, add, modify, and remove HTML elements and attributes. Developers can also listen for and respond to user events, allowing for interactive web experiences. This process leverages the Document Object Model (DOM), which represents the page as a structured hierarchy

### Documentation
https://www.freecodecamp.org/news/dom-manipulation-in-javascript/

### Video explanation
https://www.youtube.com/watch?v=NO5kUNxGIu0&ab_channel=BroCode

<div id='javascript-12'/>

## Callbacks

<div id='javascript-13'/>

## Promises
TODO add image (promise img)
Promises in JavaScript are used to handle asynchronous operations, offering a more manageable approach to dealing with actions that might take time to complete, like fetching data from an API. A promise is an object that may produce a single value in the future: either a resolved value or a reason why it's not resolved (e.g., a network error). It can be in one of three states: pending, fulfilled, or rejected. The .then() method is used to handle the fulfilled state, .catch() for rejection, and .finally() for executing code after the promise is settled, regardless of its outcome. This mechanism simplifies asynchronous programming by allowing more straightforward code flow and error handling. Promises are a foundational concept in modern JavaScript development, essential for working with asynchronous data.

### Documentation
https://javascript.info/promise-basics

### Video explanation
https://www.youtube.com/watch?v=li7FzDHYZpc&ab_channel=RobertsDevTalk

<div id='javascript-14'/>

## Async/Await
Async/await in JavaScript simplifies handling asynchronous operations by allowing developers to write code that looks synchronous but operates asynchronously. The async keyword declares a function as asynchronous, and await pauses its execution until a promise is resolved, without blocking the main thread. This makes code involving promises more readable and easier to debug.

<div id='version-control-2'/>

# 2. Version Control
Version control is a system that records changes to a file or set of files over time, enabling you to recall specific versions later. It is essential for managing code in software development, allowing multiple developers to work on the same project without conflicting changes.

<div id='version-control-22'/>

## GitHub

<div id='version-control-23'/>

## GitLab
Web-based DevOps lifecycle tool that provides a Git repository manager supporting version control and collaboration features. It facilitates continuous integration/continuous deployment (CI/CD), issue tracking, and more, within a comprehensive platform. GitLab enables teams to cover the entire software development process from planning to monitoring, emphasizing automation and collaboration.

<div id='react-3'/>

# 3. React
TODO instead of description add what you'll learn

<div id='react-31'/>

## Virtual DOM
The Virtual DOM in React is an in-memory representation of the real DOM elements, allowing React to optimize rendering by minimizing direct manipulations of the DOM. It works by comparing the current state of the Virtual DOM with the previous state and calculating the most efficient way to update the real DOM. This process, known as reconciliation, enhances application performance and responsiveness by only rendering nodes that have changed.

<div id='react-32'/>

## Basics of React Components

<div id='react-33'/>

## Conditional Rendering
Conditional rendering in React allows components to render different UI elements based on certain conditions. This technique utilizes JavaScript logical operators or ternary expressions to include or exclude components in the output. It makes the UI more interactive and responsive to user inputs or other state changes.

<div id='react-34'/>

## Rendering lists
Rendering lists in React involves mapping over an array of data and returning a list of elements for each item. This is typically done using the .map() function, which transforms each item in the array into a React element, often wrapped in a container like <ul> or <div>. Key props are used to provide a unique identifier for each element, improving performance and consistency during updates.

<div id='react-35'/>

## Pure components
Pure components in React are a simpler way to write components that only render when there is a change in their props or state. They perform a shallow comparison on both props and state to determine if the component should update, optimizing performance. Pure components reduce the need for manual shouldComponentUpdate methods by handling the comparison automatically.

<div id='react-36'/>

## Component Splitting
Component splitting in React is the practice of breaking down a large, complex component into smaller, reusable components. This approach enhances code readability, maintainability, and facilitates easier testing by isolating functionalities. It also improves performance by allowing React to render only the components that need updating, rather than the entire UI.

<div id='react-37'/>

## Reusability
Reusability in React refers to the practice of creating components that can be used in multiple places within an application, reducing code duplication and increasing efficiency. By designing generic, modular components, developers can build scalable and maintainable applications. This approach streamlines development, makes code easier to understand, and simplifies future updates or changes.

<div id='react-38'/>

## Event handlers
Event handlers in React are functions that are triggered by specific events, such as user clicks, form submissions, or key presses, allowing React components to respond to user interactions. They are attached to elements via props like onClick or onSubmit, following the camelCase naming convention. Utilizing event handlers makes React applications interactive and responsive to user input.

<div id='react-39'/>

## Complex state updates
Complex state updates in React involve managing changes to state objects or arrays that require careful handling to ensure the component's state remains immutable. Developers often use functional updates or utility libraries like Immer to handle these updates, as they provide a cleaner and less error-prone way of updating state without directly modifying it. This approach ensures the predictability and efficiency of React's state management, especially in components with intricate state logic.

<div id='react-311'/>

## Declarative vs Imperative UI
Declarative UI, as used in React, describes "what" the UI should look like for any given state, abstracting away the "how" of state transitions, leading to more readable and maintainable code. Conversely, Imperative UI requires explicitly defining the steps to reach a desired UI state, offering detailed control but at the expense of complexity.

<div id='react-312'/>

## Finding & Structuring React States

<div id='react-313'/>

## Sharing state between components
To share state between React components, use props for direct parent-child relationships, the Context API for wider application state access without prop drilling, or external libraries like Redux for complex state management across many components. These approaches facilitate efficient and coherent state sharing in React applications.

<div id='react-314'/>

## Lifting state up
Lifting state up in React moves state to a common parent component, enabling shared state management among sibling components through props. This pattern simplifies state synchronization and promotes reusability within the application.

<div id='react-315'/>

## Concised immutable state update
Immutable state updates in React involve modifying state without directly altering the original state object. Use spread operators or functions like setState with a callback that returns a new state object, ensuring the original state remains unchanged. This practice maintains purity and helps prevent bugs related to state mutability.

<div id='react-316'/>

## Passing data deeply inside React components
A scenario often referred to as "prop drilling", involves passing props through multiple layers of components to reach deeply nested ones. While effective for simple structures, it becomes cumbersome for deeper component trees.

<div id='react-317'/>

## Advanced React hooks
https://github.com/kentcdodds/advanced-react-hooks?tab=readme-ov-file

<div id='react-318'/>

## Performance hooks (useMemo, memo, useCallback)
Performance optimization in React focuses on improving the efficiency and speed of your application.
Memoization: Using React.memo for functional components to memoize and only re-render components when their props change.
PureComponent: Extending React.PureComponent in class components for a shallow comparison of props and state, minimizing unnecessary updates.
shouldComponentUpdate: Implementing this lifecycle method in class components to manually control the rendering logic based on specific conditions.
useMemo and useCallback Hooks: useMemo saves the result of expensive function calls, and useCallback memorizes callback functions, both avoiding unnecessary recalculations and re-renders.
Virtualization: Implementing windowing or list virtualization with libraries like react-window or react-virtualized to render only visible items in long lists, improving rendering performance.
Lazy Loading: Utilizing React.lazy and Suspense for splitting and lazily loading components, reducing the initial load time.
Code Splitting: Using dynamic import() syntax to split the codebase into smaller chunks, loading them on demand.

<div id='react-319'/>

## Custom hooks
Custom hooks in React are functions that let you "hook into" React state and lifecycle features from function components. They allow you to create reusable logic across different components, making your code cleaner and more modular
