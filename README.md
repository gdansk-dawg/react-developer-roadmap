# Twinkl React Dev Roadmap (and beyond)

> The overriding design goal for Markdown’s formatting syntax is to make it as readable as possible.
> The idea is that a Markdown-formatted document should be publishable as-is, as plain text,
> without looking like it’s been marked up with tags or formatting instructions.

[— Daring Fireball](https://daringfireball.net/projects/markdown/).

In here, you can find the following markdown elements:

1. Javascript - Understanding of the parnet.
2. Version control (Github).
3. React - Basic and more advanced areas of ReactJS.&#x20;
4. Build tools (Package Managers: yarn, npm, pnpm. Module Builders: webpack, vite. TaskRunners: npm scripts, gulp).
5. Styling (CSS Processor: Sass. CSS in JS: StyledComponents, Emotion. UI Frameworks: Mui).
6. State Managment  (Component State, Libraries: context api, redux, zustand).
7. Routing (react router).
8. Typescript.
9. API (REST: axios, rtk. GRAPHQL: Apollo).
10. Testing (Unit: Vitest + rtl. Integration testing: Karma? E2E: Selenium/Cypress).
11. Internationalization (React Intl, React i18next)
12. Eslint + Airbnb + prettier.
13. Performance in React (profiler, caching, memo).
14. Form building (react hook form)

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
