# Twinkl React Dev Roadmap (and beyond)

> The overriding design goal for Markdown’s formatting syntax is to make it as readable as possible.
> The idea is that a Markdown-formatted document should be publishable as-is, as plain text,
> without looking like it’s been marked up with tags or formatting instructions.

[— Daring Fireball](https://daringfireball.net/projects/markdown/).

In here, you can find the following markdown elements:

1. Javascript - Understanding of the parnet.
   - Dom manipulation
   - Callbacks
   - Promises
   - Async/Await
  
2. Version control.
  - GitLab
  - GitHub

3. React - Basic and more advanced areas of ReactJS.
  - Virtual DOM
  - Basics of React Components
  - Conditional Rendering
  - Rendering lists
  - Pure components
  - Component Splitting
  - Reusability
    ...
  - Responding to events - Event handlers
  - Basic states (useState, useEffect)
  - How rendering works
  - Updating complex states immutably

  - Declarative vs Imperative UI
  - Thinking UI Declaratively
  - Finding & Structuring React States
  - Connecting Event Handlers to React
  - Sharing State between components
  - Lifting State up
  - Extracting State Logic into Reducers
  - useReducer Hook
  - How to use Immer with React for concised immutable State Update
  - Passing Data Deeply inside React Components
    
  - Referencing values with Refs - useRef hook
  - Manipulating the DOM with Refs
  - Synchronizing with Effects - useEffect hook
  - Separating events from Effects
  - Removing Effect Dependencies
  - Performance optimization with useCallback and useMemo hook
  - Reusing logic with Custom Hooks
  - Calling APIs from Back-end with React
    
4. Build tools
Package managers:
  - npm
  - yarn
  - bun
Module Builders:
  - Webpack
  - Vite
Task runners:
  - npm scripts
  - Gulp
    
5. Styling
CSS/SASS
UI Frameworks
- styled components
- emotion
- material ui
  
6. Global state Managment Libraries
   Redux
   Zustand
   Context API
7. Routing - React Router.
  
8. Typescript.
9. API
Rest
  - RTK
  - Axios
GraphQL

12. Testing (Unit: Vitest + rtl. Integration testing: Karma? E2E: Selenium/Cypress).
Unit testing
  - Jest
  - Vitest
Integration testing
  - Karma
End to End testing
  - Selenium
  - Cypress

14. Internationalization (React Intl, React i18next)
15. Eslint + Airbnb + prettier.
16. Performance in React (profiler, caching, memo).
17. Form building (react hook form)

Beyond React:

1. SSR / CSR.
2. NextJS.
3. DynamoDB.
4. Backend - NodeJS.
5. Devops (CI/CD githubACTIONS).
6. Infrastructure (docker)
7. AWS (Dynamo + lambda)

## What can you do here?

This is a great location for you to test how editing markdown feels. If you have an existing markdown source, you can switch to source mode using the toggle group in the top right, paste it in there, and go back to rich text mode.

If you need a few ideas, here's what you can try:

1. Add your own code sample
2. Change the type of the headings
3. Insert a table, add a few rows and columns
4. Switch back to source markdown to see what you're going to get as an output
5. Test the diff feature to see how the markdown has changed
6. Add a frontmatter block through the toolbar button

## A code sample

MDXEditor embeds CodeMirror for code editing.

```tsx
export default function App() {
  return (<div>Hello world</div>)
}
```

## A live code example

The block below is a live React component. You can configure multiple live code presets that specify the available npm packages and the default imports. You can also specify a default component that will be rendered in the live code block.

```jsx live
export default function App() {
  return (<div>
  <p>This is a live React component, that's being previewed in codesandbox. </p>
  <p>Editing it will update the fenced codeblock in the markdown.</p>
  </div>)
}
```

## A table

Play with the table below - add rows, columns, change column alignment. When editing,
you can navigate the cells with `enter`, `shift+enter`, `tab` and `shift+tab`.

| Item              | In Stock | Price |
| :---------------- | :------: | ----: |
| Python Hat        |   True   | 23.99 |
| SQL Hat           |   True   | 23.99 |
| Codecademy Tee    |   False  | 19.99 |
| Codecademy Hoodie |   False  | 42.99 |
