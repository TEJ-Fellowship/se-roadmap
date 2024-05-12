# 🔥 Software engineering roadmap

## Overview

### 4 Cs to success

- **Community**: Get 2 or more friends to do it together
- **Curriculum**:
  - Pick one language (JS, Python)
  - Learn the language before framework
- **Commit**: E.g. 5 hrs a week, finish 1 chapter a week
- **Coach**: Find a coach. e.g. your teacher, brother etc.

### Curriculum

#### 1. Learn JavaScript basics

- course: [Bootcamp prep](https://www.fullstackacademy.com/bootcamp-prep-online)
- how to sign up: fill in your first name, last name, email, phone number, zip code
- plan: 12 weeks, 1 hour per day, 5 days a week

#### 2. Learn React basics

- course: [Complete Intro to React v8](https://react-v8.holt.courses/) by Brian Holt
- plan: follow the 'No frills react' and 'JS tools' chapters

#### 3. Learn full stack coding

- course: [Fullstack open curriculum](https://fullstackopen.com/en/)
- plan:
  - study Part 0, 1, 2, 3
  - time: 16 weeks, 1 hour per day, 5 days a week
  - support: https://study.cs.helsinki.fi/discord/join/fullstack support group to help you

#### 4. Practice algorithm problems

- course: https://www.codewars.com/
- plan: solve 1 problem per day
  - start at level 8: two weeks
  - level 7: four weeks
  - level 6 (for Nepal jobs): 16 weeks
  - level 5 (for Global jobs): 52 weeks

### Useful links

- [git basics](https://git-scm.com/book/en/v2)

# Fullstack open guide

## [PART 0: Fundamentals of web apps](https://fullstackopen.com/en/part0/fundamentals_of_web_apps)

HTTP call

<details><summary><h3 style="display:inline">Chapters</h3></summary>

<details><summary>Part 0-b</summary>

**_WE-WILL-LEARN:_**

- HTTP call

**_PRE-WORK:_**

- [PART 0: Read only the 'HTTP GET' section](https://fullstackopen.com/en/part0/fundamentals_of_web_apps)

**_TO-STUDY:_**

- [PART 0-b: HTTP request](https://fullstackopen.com/en/part0/fundamentals_of_web_apps#http-get)

**_LECTURE-VIDEO:_**

- [Exercise web sequence diagrams](https://youtu.be/ycQnptR5qj8)

**_TO-DO:_**

- [0.4-0.6](https://fullstackopen.com/en/part0/fundamentals_of_web_apps#exercises-0-1-0-6)

_Instructions for TO-DO_

1. create a new git repository called `fullstackopen` in your local computer
1. create a repository in github to push your local `fullstackopen`
1. create a folder called `part0` inside `fullstackopen`
1. create separate files to put your sequence diagrams for exercises 0.4 to 0.6

</details>

</details>

---

## [PART 1: Introduction to react](https://fullstackopen.com/en/part1)

pure react, modern react dev setup, component, state, event handler

<details><summary><h3 style="display:inline">Chapters</h3></summary>
<details><summary>Part 1-a: Introduction to React</summary>

- [Part 1-a: Introduction to React](https://fullstackopen.com/en/part1/introduction_to_react)

**_WE-WILL-LEARN:_**

- pure react
- modern react dev setup

**_PRE-WORK:_**

- [watch this video on eventloop](https://www.youtube.com/watch?v=8aGhZQkoFbQ)

**_TO-STUDY:_**

- [Complete Intro to React v8: Pure react](https://react-v8.holt.courses/lessons/no-frills-react/pure-react)
- [Complete Intro to React v8: JS tools](https://react-v8.holt.courses/lessons/js-tools/npm)
- [PART 1-a: Intro to React](https://fullstackopen.com/en/part1/introduction_to_react)

**_LECTURE-VIDEO:_**

- [Pure react](https://youtu.be/gjPQSF1GvRk)
  1. Create folder structure and files
  - create folder `pure-react`, then `src` inside it
  2. Create `index.html` inside `src`
  - add script tag for React, ReactDOM, and index.js
  3. Create `index.js` inside `src`
  - use `ReactDOM.createRoot`, `React.createElement`, and `render` to create web application using pure react
- [Tooling with npm, prettier, eslint, vite](https://youtu.be/JXvofCk2_gM)
  1. Create folder structure and files
  - create folder `tooling`, then copy `src` from `pure-react`
  2. Toolings
  - create npm project by `npm init -y`
  - install Dev prettier, eslint, vite
  - setup config for prettier, eslint, and vite
  - install react, react-dom
- [Convert pure react to dev environment running from vite](https://youtu.be/JXvofCk2_gM?t=1552)
  1. Move react and react-dom libraries to index.js
  2. Use `type="module"` in index.html
  3. Create vite scripts in package.json for `dev`, `build`, and `preview`
- [Using JSX](https://youtu.be/eG7UPaLh5WQ)
  1. Move components `App` and `Hello` to individual files
  - remember to import and export required things
  - make sure to start component name with `Capital`
  2. Convert `React.createElement` to JSX
  - rename all files with JSX to `.jsx` extension from `.js`
  - remove the imports that are not required for JSX
  3. Configure eslint to understand react and JSX
  - `npm i -D eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-react`
  - update eslint config
  4. Please read [Some notes](https://fullstackopen.com/en/part1/introduction_to_react#some-notes) section for common errors to avoid
  5. What can you [render](https://fullstackopen.com/en/part1/introduction_to_react#do-not-render-objects) in JSX?

_Instructions for the `workshops` shown in the `LECTURE-VIDEO`s_

1. Create a new repository called `fullstackopen-workshops`
   - create the repository in your local computer
   - create a repository in github to push your local `fullstackopen-workshops`
   - create a folder called `part1` inside `fullstackopen-workshops`
2. Please do the workshop at least once by yourself
   - read notes under `LECTURE-VIDEO` section
   - watch the lecture-video (if required)
   - read the material (if required)
   - then put today's workshop inside the `part1` folder
   - refer to source code from lecture in [`part1-a` branch](https://github.com/TEJ-Fellowship/tej-bootcamp/tree/part1-a/part1/pure-react) if needed
   - continue future workshops under appropriate folder structures

**_TO-DO:_**

- [1.1-1.2](https://fullstackopen.com/en/part1/introduction_to_react#exercises-1-1-1-2)

_Instructions for TO-DO_

1. In the `fullstackopen` repository, create a folder called `part1` inside `fullstackopen`
2. Create folder called `courseinfo` inside of `part1` to put your code for exercise 1.1-1.2
   - You can create `courseinfo` project either by using `vite`, as we did for the class today. You can clone this [starter kit](https://github.com/TEJ-Fellowship/react-start-kit)
   - Or you can create `courseinfo` project using `create-react-app` as described in the [`introduction to react`](https://fullstackopen.com/en/part1/introduction_to_react) section of the course

_note-1_: If you are cloning the starter kit, delete the `.git` directory inside the clone.
_note-2_: See this [example exercise repository](https://github.com/fullstack-hy2020/example-submission-repository) for folder structure. Further details can be found with the [exercise instructions](https://fullstackopen.com/en/part1/introduction_to_react#exercises-1-1-1-2)

</details>

<details><summary>Part 1-b: Javascript</summary>

- [Part 1-b: Javascript](https://fullstackopen.com/en/part1/java_script)

**_WE-WILL-LEARN:_**

- Javascript concepts

**_TO-STUDY:_**

- master these Array methods: [Map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map), [Filter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter), [Reduce](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce), [forEach](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach), [Includes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/includes), [Some](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/some), [Every](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/every)

**_LECTURE-VIDEO:_**

- [Array methods in React](https://youtu.be/ZlBX5Wh6dBE)
  1. Create a react project that says `hello` to many people
  - create project `using-array` inside `part1`
  - copy the `src` files from [part1/tooling/src](https://github.com/TEJ-Fellowship/tej-bootcamp/tree/main/part1/tooling/src)
  2. In `App` create an array of objects of people to say hello to
  - a person object can have the properties for `firstName`, `lastName`, `id` etc.
  3. Display hello to each person
  - for each element in array, call `SayHello` component through the `map` method
    - pass entire person object to `SayHello`
    - in `SayHello`, destructure `props`
    - write a component helper function to return combination of `firstName`, `lastName`
    - use the helper function in the JSX returned by the component
  - If array is empty, display appropriate message
    - use if else condition
    - use ternary

```jsx
return (
  <div>
    {peopleArray.length > 0 ? (
      peopleArray.map((value) => <SayHello person={value} key={value.id} />)
    ) : (
      <h1>No records found</h1>
    )}
  </div>
);
```

- add `filter` method to say hello only to people with id greater than 2

_Instructions for the `workshop` shown in the `LECTURE-VIDEO`_

1. In the `fullstackopen-workshops` repository created in part1-a
   - create the workshop project `using-array` inside the folder `part1`
2. Please do the workshop at least once by yourself
   - read notes under `LECTURE-VIDEO` section
   - watch the lecture-video (if required)
   - do today's workshop in the `using-array` folder
   - refer to source code from lecture in [`part1-b` branch](https://github.com/TEJ-Fellowship/tej-bootcamp/tree/part1-b/part1/using-array) if needed

**_TO-DO:_**

- [1.3-1.5](https://fullstackopen.com/en/part1/java_script#exercises-1-3-1-5)

_Instructions for TO-DO_

1. In the `fullstackopen/part1/courseinfo` repository, continue to put your code for exercise 1.3-1.5

</details>

<details><summary>Part 1-c: Component state, event handlers</summary>

- [Part 1-c: Component state, event handlers](https://fullstackopen.com/en/part1/component_state_event_handlers)

**_LECTURE-VIDEO:_**

- [Component manual re-render](https://youtu.be/-GH2Qj9n-Mg)
  1. Create a react project that updates the count
  - create project `counter-app` inside `part1`
  - create component `App` and jsx file `index.jsx`
  2. Update the count in some set interval
  - use `setInterval` to update count, and also call the render manually to re-render the app
- [React state](https://youtu.be/RC-4xZIKqpo)
  1. Use `useState` hook to make a stateful component inside `App` component
  - convert the counter to a state using `useState`
  - use `setTimeout` to call a function after 1 second that changes the value of `counter` state
  - remove the manual call to render
- [React event handling](https://youtu.be/oeQ3M53rQVQ)
  1. add a button to increase the count
  - add button element
  - include an `onClick` event handler to the button. The event handler has to be a function, not function execution!
  2. Refactor components for display and button
  - refactor `Display` component
    - call `Display` from `App` and also pass it the counter state
  - refactor `Button` component
    - call it for plus, minus, and zero by passing appropriate event handlers

**_TO-DO:_**

- [1.6-1.14](https://fullstackopen.com/en/part1/a_more_complex_state_debugging_react_apps#exercises-1-6-1-14)

</details>

<details><summary>Part 1-d: Complex state, debugging React apps</summary>

- [Part 1-d: Complex state, debugging React apps](https://fullstackopen.com/en/part1/a_more_complex_state_debugging_react_apps)

**_WE-WILL-LEARN:_**

- a more complex state
  - array, object in state: don't mutate state!
- conditional rendering of component
- debugging React apps

**_LECTURE-VIDEO:_**

- [Using object, array in state](https://youtu.be/FBLdF4rpba4)
  1. Create a copy of `counter-app` in `part1` directory
  - first delete `node_modules` folder from `counter-app`
  - `cp -r counter-app double-counter`
  2. Put two counters
  - put the state of the left and right counter in an object
  - put the state of click history in an array
  - lets put the total number of clicks in a state
- [Conditional rendering in component](https://youtu.be/5AdVOjQMX2A)
  1. Create a new `History` component that shows the click history
  2. Conditionally show the history only when there is history
  - otherwise, show another message
- [React debugging, and notes on hooks](https://youtu.be/ExDd_g4rMkY)
  1. Do the following for debugging
  - console.log
  - debugger
  - [React developer tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi)
  2. Rules of hooks (useState, useEffect etc.)
  - only call hooks inside functional components
  - do not call hooks from
    - inside of a loop
    - a conditional expression
- [Exercise 1.1 to 1.14 guide](https://youtu.be/H18zHpNDKwg)

**_TO-DO:_**

- [1.6-1.14](https://fullstackopen.com/en/part1/a_more_complex_state_debugging_react_apps#exercises-1-6-1-14)

</details>

</details>

---

## [PART 2: Communicating with server](https://fullstackopen.com/en/part2)

Modules, forms, getting data from server, altering data in server

You can refer to the workshop code solutions [here](https://github.com/fullstack-hy2020/part2-notes)

<details><summary><h3 style="display:inline">Chapters</h3></summary>

<details><summary>Part 2-a: Rendering a collection, modules</summary>

- [Part 2-a: Rendering a collection, modules](https://fullstackopen.com/en/part2/rendering_a_collection_modules)

**_PRE-WORK:_**

- [watch at least first 3 parts of this youtube playlist](https://www.youtube.com/playlist?list=PL0zVEGEvSaeEd9hlmCXrk5yUyqUag-n84)

**_WE-WILL-LEARN:_**

- rendering collection [Array or Object]
  - don't mutate state! especially if state is Array or Object
- Array.map
- Array.reduce
  - [lecture notes from foundations](https://github.com/TEJ-Fellowship/js-foundations/blob/main/lecture-notes/testfirst-part-2.js)
  - [mdn documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce)
- most common problems in React up to this point
  - the props are expected to be of a different type,
  - or called with a different name than they actually are, and destructuring fails as a result

**_LECTURE-VIDEO:_**

- [Using Array.map to show data in React](https://youtu.be/bb2Jp2aAFac?t=2)
  1. Create react project `notes-app`
  - create directory `part2`
  - create react project `notes-app` inside `part2`
  - pass array of notes from `index.jsx` to `App.jsx`
  - in `App.jsx` access the array data using indices
  2. Access the array using map method
- [Using key in React lists, and further debugging notes](https://youtu.be/bb2Jp2aAFac?t=1114)
  1. Use the `key` attribute when rendering array
  - understand how map method is working
  - using index vs id for `key` attribute
  2. Refactor the code
  - destructure the props
  - create the `components` directory inside `src`
  - refactor components and put them in `components` directory
    - note that the `key` attribute is now required in the component

**_TO-DO:_**

- [2.1-2.5](https://fullstackopen.com/en/part2/rendering_a_collection_modules#exercises-2-1-2-5)

</details>

<details><summary>Part 2-b: Forms</summary>

- [Part 2-b: Forms](https://fullstackopen.com/en/part2/forms)

**_WE-WILL-LEARN:_**

**Main concepts**

- controlled HTML input component
- filtering displayed elements

**Side notes**

- form onSubmit event handler needs event.preventDefault()
- form in App
- controlled HTML component: using onChange
- ternary expression
- Array.filter

**_LECTURE-VIDEO:_**

- [Adding a controlled HTML input component to add notes](https://youtu.be/gMdffc85U2M)
  1. Create a state to keep track of notes array
  2. Add a form in JSX to add a note
  3. Put an `onSubmit` event handler to the form
  4. Add a [controlled HTML input component](https://react.dev/reference/react-dom/components/input#controlling-an-input-with-a-state-variable) to capture the entry of a new note
  - add a new state to store the new note
  - use the state as the input `value`
  - add an `onChange` event handler on the input
  5. Complete `onSubmit` to add new note to notes array
- [Filtering displayed notes](https://youtu.be/YJhQ_6zGgA8)
  1. Add state to keep track of `showAll`
  2. Add a `notesToShow` variable to keep notes to show based on `showAll` state
  - if `showAll` is true, then `notesToShow` is same as `notes`
  - else, `notesToShow` only has importants `notes`
  3. Add functionality to toggle between `all` and `important`
  - add button with text for action
  - add `onClick` to button to toggle `showAll` state

**_TO-DO:_**

- [2.6-2.10](https://fullstackopen.com/en/part2/forms#exercises-2-6-2-10)

</details>

<details><summary>Part 2-c: Getting data from server</summary>

- [Part 2-c: Getting data from server](https://fullstackopen.com/en/part2/getting_data_from_server)

**_WE-WILL-LEARN:_**

- getting data from backend server
  - using [JSON Server](https://medium.com/codingthesmartway-com-blog/create-a-rest-api-with-json-server-36da8680136d) as our backend server
- [useEffect hook](https://react.dev/reference/react/useEffect)
- using [Axios](https://axios-http.com/docs/intro) to call server
  - understanding [promises](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Using_promises)

**_LECTURE-VIDEO:_**

- [Setting up json-server as our backend server](https://youtu.be/jM5vB4hX8_8)
  1. Create the `db.json` file with array of notes
  2. Install `json-server` as dev dependency
  ```
  npm install json-server --save-dev
  ```
  3. Start the json-server
  ```
  npx json-server --port 3001 --watch db.json
  ```
  4. Include json-server start command in package.json scripts
  5. view the output on web browser
  - if required, install the [JSONVue](https://chrome.google.com/webstore/detail/jsonvue/chklaanhfefbnpoihckbnefhakgolnmc) extension
- [Understanding the useEffect hook](https://youtu.be/b_8Wz08L_Oo)
  1. in App.jsx, create a `useEffect` hook so that it is only called on first render
  2. update the `useEffect` hook so that it executes each time the `showAll` state changes
- [Using Axios in frontend to access data from backend](https://youtu.be/87ZVR9K9M70)
  1. Install axios as dependency
  ```
  npm install axios
  ```
  2. Read the data from json-server from our app using axios
  - start json-server in one terminal
  - start the app in another terminal
  - add code for axios.get in App.jsx inside the `useEffect` hook
  - modify `useEffect` so that it is called only on first render of the component

**_TO-DO:_**

- [2.11](https://fullstackopen.com/en/part2/getting_data_from_server#exercise-2-11)

</details>

<details><summary>Part 2-d: Altering data in server</summary>

- [Part 2-d: Altering data in server](https://fullstackopen.com/en/part2/altering_data_in_server)

**_WE-WILL-LEARN:_**

- understanding [REST](https://www.codecademy.com/article/what-is-crud)
  - routes
  - CRUD (Create, Read, Update, Delete) actions on REST routes
  - [axios methods corresponding to CRUD actions](https://www.freecodecamp.org/news/axios-react-how-to-make-get-post-and-delete-api-requests/)
- sending data to the Backend Server
  - [creating new data using axios.post](https://fullstackopen.com/en/part2/altering_data_in_server#sending-data-to-the-server)
  - [updating existing data using axios.put](https://fullstackopen.com/en/part2/altering_data_in_server#changing-the-importance-of-notes)
  - [handling Error in Promise using promise.catch](https://fullstackopen.com/en/part2/altering_data_in_server#promises-and-errors)

**Side notes**

- Array.find
- Review
  - Array.map
  - Array.filter

**_LECTURE-VIDEO:_**

- [Using axios.post to create note in backend](https://youtu.be/3R6ptNpQI78)
  1. Add `axios.post` code inside the event handler responsible for creating new note
  - a brief look at REST API
  - remove the `id` from your new note object, because now the REST API should create the id
  - update your notes state with the returned note object
  - now, even if you refresh, the newly added note is still present
- [Using `axios.put` to update note in backend](https://youtu.be/io2J85hh-Xw)
  1. Add button to toggle the `important` field of note
  - in `Note` component, add a button to toggle importance
  - what will be the `onClick` event handling function on the button?
  2. In the event handling function, add logic to update the data in server, and in state
  - first, find the note from our state
  - then, create a new object with the changed state of the note
    - don't mutate state directly!
  - send the new object using axios.put to update data in server
  - change the state of notes to reflect the updated note
- [Refactoring axios services](https://youtu.be/98dbEWhUxy4)
  1. Create a `services` folder inside the `src` folder
  2. Create `notes.js` fild inside `services`
  3. Create a `getAll`, `create`, and `update` functions specifically only for the server functions
  - return a promise that returns the destructured data
  - use these new functions in `App.jsx` to interact with the server
- [Handling axios errors in catch block](https://youtu.be/XTgRHClbphU)
  1. In `getAll` note service, add a fake note to the array returned from server
  2. Add a `catch` block to catch any error to the call to `update`
  - when we try to update a note in the server that does not exist, json-server will throw an error
  - print the error in the `catch` block
  - if the status code is `404`, it means the data does not exist
    - remove the data from `notes` state if data does not exist in server
    - show an alert with proper error message

**_TO-DO:_**

- [2.12-2.15](https://fullstackopen.com/en/part2/altering_data_in_server#exercises-2-12-2-15)

</details>

<details><summary>Part 2-e: Adding styles to React app</summary>

- [Part 2-e: Adding styles to React app](https://fullstackopen.com/en/part2/adding_styles_to_react_app)

**_WE-WILL-LEARN:_**

- adding styles to React app
  - 2 methods
    - importing style file into JS project
    - inline styles in JSX
  - CSS rules = selector + declerations
  - class selectors in JSX
- error message in it's own React component
  - activating error component by setting error message

**_LECTURE-VIDEO:_**

- [Inline styles](https://youtu.be/k5ZeIoaccv4)
  1. In `App.jsx`, define a new variable whose value is an object with css style
  - note that the CSS properties are written in camelCase, not hyphenated as in css file
  2. In the `h1` element in the JSX, create a new attribute called `style` and assign it the above variable
- [Using a css file to define a style](https://youtu.be/k5ZeIoaccv4?t=542)
  1. Create a css file `index.css` in the `src` directory
  2. Define a style for class `.redbackground`
  3. Import `index.css` in `index.jsx`
  4. In `App.jsx`, use the `redbackground` class in the `input` html element
- [Creating dynamic error message from catch block](https://youtu.be/KNDIhALqNP4)
  1. Create a new component called `Notification`
  - define an `error` class in css file to use in the Notification component
  2. Define a new state to put the error message with an initial value of `null`
  3. In the `catch` block for error handling, add code to display the error message in the Notification component
  - in the `catch` block, set the error message state with the error message
  - after a certain amount of time, set the error message back to `null`
- [Debugging openweather map api key](https://youtu.be/aByLiib_Zks)

**_TO-DO:_**

- [2.16-2.17](https://fullstackopen.com/en/part2/adding_styles_to_react_app#exercises-2-16-2-17)
- [2.18-2.20](https://fullstackopen.com/en/part2/adding_styles_to_react_app#exercises-2-18-2-20)

</details>

</details>

---

## [PART 3: Programming a server with NodeJS and Express](https://fullstackopen.com/en/part3)

You can refer to the workshop code solutions [here](https://github.com/fullstack-hy2020/part3-notes-backend)

<details><summary><h3 style="display:inline">Chapters</h3></summary>

<details><summary>Part 3-a: Node.js and Express</summary>

- [Part 3-a: Node.js and Express](https://fullstackopen.com/en/part3/node_js_and_express)

**_WE-WILL-LEARN:_**

- creating a simple Node project that runs in Node environment
- running a simple web server
- using Express library to build a more developer friendly web server
- using nodemon to run node
- defining routes in Express
  - CRUD functionality in Express routes
- Middleware
  - writing our own middleware

**Side notes**

- [difference between ES6 modules vs CommonJS syntax](https://www.freecodecamp.org/news/modules-in-javascript/)
- [what is JSON?](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON)
- [what does the version number in npm library mean?](https://fullstackopen.com/en/part3/node_js_and_express#express)
- [VSCode REST client](https://fullstackopen.com/en/part3/node_js_and_express#the-visual-studio-code-rest-client)
- [Math.max](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/max)

**_LECTURE-VIDEO:_**

- [Creating a simple express server](https://youtu.be/raUOxLZiPng)
  1. Create new project `notes-server`
  - create an npm project inside by `npm init -y`
  - create an http server that shows the text 'Hello world', listening on port 3001
  2. Serve notes as JSON data using http server
  - create a notes variable with the notes array
  - convert the http response to type `application/json`
  - JSON.stringify the notes array in the response
- [Using express for serving on the '/api/notes' route for a 'get' method request](https://youtu.be/QgC5oSEB_Tc)
  1. Install `express` library
  - modify code to use express library
  2. Modify to express route to server array of notes on `/api/notes` url for `get` request
  3. Install nodemon as dev dependency to run node server by hot reload on code changes
- [Side note on REST and JSON](https://youtu.be/GlanBqAtPj8)
- [Creating the '/api/notes/:id' route for a 'get' method request](https://youtu.be/CPMkmR6eSIU)
  1. Create a new get route at `/api/notes/:id`
  2. Respond with the json object of the note at that id
  - please note that the `request.params` always comes as a string
  3. If no notes are available at the id, then set status to 404 and return a friendly error message
- [Creating the `/api/notes/:id` route for a `delete` method request](https://youtu.be/rO6vsReA3d4)
  1. Create a new delete route at `/api/notes/:id`
  2. Respond with 204 status code, and no body
  3. Install `REST Client` extension
  4. Create file `requests/my_requests.rest` to store the REST requests
  - call the `delete` method on the REST endpoint
  ```
  DELETE http://localhost:3001/api/notes/2
  ```
- [Creating the '/api/notes' route for a 'post' method request](https://youtu.be/51_oufxrDUo)
  1. Create a new post route at `/api/notes`
  2. Use express.json() to read json objects in the request
  3. Use the json object in request to create a new post in the backend
  4. Respond with status 201 created and return the newly created note object
- [Creating middleware](https://youtu.be/wPZRiwHlz4Y)
  1. Create a middleware at the top of the express server to log method, path, and body
  2. Creat a middleware at the end of the express server (just before app.listen) to send a 404 not found to all paths that are not handled by the app

**_TO-DO:_**

- [3.1-3.6](https://fullstackopen.com/en/part3/node_js_and_express#exercises-3-1-3-6)
- [3.7-3.8](https://fullstackopen.com/en/part3/node_js_and_express#exercises-3-7-3-8)

</details>

<details><summary>Part 3-b: Deploying app to internet</summary>

- [Part 3-b: Deploying app to internet](https://fullstackopen.com/en/part3/deploying_app_to_internet)

**_WE-WILL-LEARN:_**

- [serving static files from server](https://fullstackopen.com/en/part3/deploying_app_to_internet#serving-static-files-from-the-backend)
- [including frontend code on server](https://fullstackopen.com/en/part3/deploying_app_to_internet#frontend-production-build)
- [deploying app to a cloud platform (e.g. Render)](https://fullstackopen.com/en/part3/deploying_app_to_internet#application-to-the-internet)
- [streamlining the deployment](https://fullstackopen.com/en/part3/deploying_app_to_internet#streamlining-deploying-of-the-frontend)

**Side notes**

- [CORS](https://fullstackopen.com/en/part3/deploying_app_to_internet#same-origin-policy-and-cors)
- [setting up proxy on react app](https://fullstackopen.com/en/part3/deploying_app_to_internet#proxy)
- [how the current set-up after part3-b looks](https://fullstackopen.com/en/part3/deploying_app_to_internet#the-whole-app-to-the-internet)

**_LECTURE-VIDEO:_**

- [Use notes-server instead of json-server](https://youtu.be/t7A5C8GAwBM?t=1)
  1. Start `notes-app`
  2. Start `notes-server`
  3. Change `baseUrl` in `notes-app` to the url of our `notes-server`
  4. Configure CORS in `notes-server` so that app and server work from different origins
  - install `cors` library
  - use `cors` library in server's `index.js` file
- [Serving frontend static files from node server](https://youtu.be/t7A5C8GAwBM?t=888)
  1. Build react app for serving from web server
  2. Include the build folder in your node application
  3. Instruct node server to serve the static files from the build folder
- [Modify frontend backend code to run in cloud](https://youtu.be/jt8qR6BI7h0)
  1. In react app, change the baseurl to a relative url
  2. In node server, read the PORT value from environment if available
- [Deploy fullstack app to Render](https://youtu.be/-xVexhcTjv8)
  1. Create a render account at https://dashboard.render.com/register
  - sign up using `GitHub`
  2. Create a new `Web Service`
  - connect to the proper github repository
  - configure `Root Directory`, `Build Command` (npm install), and `Start Command`
  3. Push your code to GitHub
  4. In notes-server, streamline notes-app build and deploy process
  - add npm script to build the react app and copy it to server repo
    - remove the existing `dist` folder
    - cd to notes-app
    - build notes-app
    - cp the `dist` folder from notes-app to notes-server
  5. Add proxy to vite config of notes-app so that we can use relative url in react dev environment
  ```
  server: {
    proxy: {
      "/api": {
        target: "http://localhost:3001",
        changeOrigin: true,
        secure: false,
      },
    },
  }
  ```

**_TO-DO:_**

- [3.9-3.11](https://fullstackopen.com/en/part3/deploying_app_to_internet#exercises-3-9-3-11)

</details>

<details><summary>Part 3-c: Saving data to MongoDB</summary>

- [PART 3-c: Saving data to MongoDB](https://fullstackopen.com/en/part3/saving_data_to_mongo_db)

**_LECTURE-VIDEO:_**

- [Introduction to mongodb](https://youtu.be/5Cdr5qnw8N4)
- [Setting up mongo database in mongodb.com](https://youtu.be/EvJJkLZ3RnM)
  1. Create a free account in mongodb.com
  - go to https://www.mongodb.com/cloud/atlas/register
  - you can sign up with google
  - select the 'free' option
  2. Create database userid and password
  - create project
  - build database using free option
  - choose the username password option for authentication
  - finish database creation
  3. Set network setting to allow access from anywhere
  - go the 'network access'
  - edit and select 'allow access from anywhere'. note - this is only for development!
  4. Get the connection string to your database
- [Using mongoose to set up a practice application](https://youtu.be/WevMzdj7pxg)
  1. `npm install mongoose`
  2. Create a new mongo.js file in your repo to create practice application
  - copy code from fullstackopen for mongo.js
  - change the url value to your db connection string
  - the mongo.js code has the following:
    - [create a schema for Note](https://fullstackopen.com/en/part3/saving_data_to_mongo_db#schema)
    - use the schema to create a model for Note
    - [use the Note model to create and save a Note object into mongodb](https://fullstackopen.com/en/part3/saving_data_to_mongo_db#creating-and-saving-objects)
  3. Run our code from terminal to create a collection and data in `noteApp` database
  - run `node mongo.js password`, this will create the note data in `test` database, in `notes` collection
  - delete the `test` collection
  - add `noteApp` to the db connection string
  - run `node mongo.js password` again, this will now create the note data in `noteApp` database
  4. [Write code to fetch data frome `notes` collection using the `Note` model](https://fullstackopen.com/en/part3/saving_data_to_mongo_db#fetching-objects-from-the-database)
  - in `mongo.js`, comment out the note creation code
  - add code to `get` the data
  - run `node mongo.js password` again
- [Connect the notes-server to the database](https://youtu.be/e0M8bBv_IEA)
  1. [Fetch db connection string from environment](https://youtu.be/Aph6jjDb2O8)
  - install npm library `dotenv` that will allow us to convert variables from .env file to `process.env` variables
  - for localhost
    - create a .env file to store the db connection string (add .env file to .gitignore)
    - in .env file, enter db connection string to variable `MONGODB_URI`
    - in index.js file, use `dotenv` library to read env variables
  - for render: configure db connection string in render `Environment`
  2. Create separate module to put database configuration
  3. Get data from database in the `/api/notes` route for `get` method
  4. Modify the returned data from mongoose to show the `id` field instead of `_id`, and hide the `__v` field
- [More node express routes configured through database](https://youtu.be/1NNyJnz3q4c)
  1. Rewrite `/api/notes` route for `post` method
  1. Rewrite `/api/notes/:id` route for `get` method
  1. Error handling
  1. Moving error handling to middleware
  - make sure middlewares are loaded in proper order
  1. Rewrite `/api/notes/:id` route for `delete` method
  1. Write `/api/notes/:id` route for `put` method

**_TO-DO:_**

- [3.12](https://fullstackopen.com/en/part3/saving_data_to_mongo_db#exercise-3-12)
- [3.13-3.14](https://fullstackopen.com/en/part3/saving_data_to_mongo_db#exercises-3-13-3-14)
- [3.15-3.18](https://fullstackopen.com/en/part3/saving_data_to_mongo_db#exercises-3-15-3-18)

</details>

<details><summary>Part 3-d: Validation and ESLint</summary>

- [PART 3-d: Validation and ESLint](https://fullstackopen.com/en/part3/validation_and_es_lint)

**_LECTURE-VIDEO:_**

- [Mongoose schema validation](https://youtu.be/F5vLQqKuCBo)
  1. Create a mongoose schema validation for `content` field in noteSchema
  2. In the note post route, catch the error in note.save
  3. Put the error handler in the error handling middleware
  4. Catch and display the error in the notes react app
- [Mongoose schema validation while updating](https://youtu.be/Zfmzodtq-5k)
  1. In the note update route, configure it to also throw schema validation errors
  2. Why schema based validation is better than logical error handling in code
- [Linting setup and configurations](https://youtu.be/SXLCt7Zzx8A)
  1. Install eslint as a dev dependency
  2. Setup config file for eslint
  - change env `browser` to `node`
  3. Setup the VSCode extensions for eslint
  4. Create script to run eslint
  5. Create eslint ignore config file `.eslintignore`
  - include the `dist` folder
  6. Create eslint rule for
  - `eqeqeq`
  - show warning for console.log
  7. Difference between formatting (prettier) vs code linting (eslint)

**_TO-DO:_**

- [3.19-3.21](https://fullstackopen.com/en/part3/validation_and_es_lint#exercises-3-19-3-21)
- [3.22](https://fullstackopen.com/en/part3/validation_and_es_lint#exercise-3-22)

</details>

</details>
