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
   - [Thinking UI Declaratively](#react-312)
   - [FInding & Structuring React States](#react-313)
   - [Sharing state between components](#react-314)
   - [Lifting state up](#react-315)
   - [Advanced React Hooks](#react-316)
   - [Concised immutable state update](#react-317)
   - [Passing data deeply inside React components](#react-318)
   - [useRef Hook](#react-319)
  - Referencing values with Refs - useRef hook
  - Manipulating the DOM with Refs
  - [useMemo and useCallback](#react-320)
  - [Custom Hooks](#react-321)
    
4. [React](#build-tools-4)
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
    
5. [Styling](#styling-5)
5.1 [CSS/SASS](#styling-5-1)
5.2 [Styling Libraries](#styling-5-2)
  - [Material UI](#styling-5-2-1)
  - [Emotion](#styling-5-2-2)
  - [Styled Components](#styling-5-2-3)

6. [State Managment Libraries](#sml-6)
   - [Redux Toolkit](#sml-6-1)
   - [Zustand](#sml-6-2)
   - [Context API](#sml-6-3)

7. [Routing - React Router](#routing-7)
  
8. [Typescript](#typescript-8)
   - eslint + airbnb + prettier
9. [API](#api-9)
   - 9.1 [Rest](#api-9-1)
    - [RTK](#api-9-1-1) 
    - [Axios](#api-9-1-2)
   9.2 [GraphQL](#api-9-2)

10. [Testing](#testing-10)
   9.1 [Unit Testing](#testing-10-1)
    - [Jest](#testing-10-1-1) 
    - [Vitest](#testing-10-1-2)
   9.2 [Integration Testing](#testing-10-2)
    - [Karma](#testing-10-2-1) 
   9.3 [End to End testing](#testing-10-3)
    - [Selenium](#testing-10-3-1)
    - [Cypress](#testing-10-3-1)

11. [Internationalization](#internationalization-11)
   - [React i18next](#internationalization-11-1)
   - [React Intl](#internationalization-11-2)

12. [Performance in React](#performance-12)
    - [Profiler](#performance-12-1)
    - [Caching](#performance-12-2)

13. [Form building](#form-building-13)


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

<div id='version-control-2'/>

# 2. Version Control

<div id='version-control-22'/>

## GitHub

<div id='version-control-23'/>

## GitLab
