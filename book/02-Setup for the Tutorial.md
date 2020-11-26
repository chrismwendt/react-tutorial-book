## Setup for the Tutorial

There are two ways to complete this tutorial: you can either write the code in your browser, or you can set up a local development environment on your computer.

### Setup Option 1: Write Code in the Browser

This is the quickest way to get started!

First, open this **[Starter Code](https://codepen.io/gaearon/pen/oWWQNa?editors=0010)** in a new tab. The new tab should display an empty tic-tac-toe game board and React code. We will be editing the React code in this tutorial.

You can now skip the second setup option, and go to the [Overview](#overview) section to get an overview of React.

### Setup Option 2: Local Development Environment

This is completely optional and not required for this tutorial!

<br>

<details>

<summary><b>Optional: Instructions for following along locally using your preferred text editor</b></summary>

This setup requires more work but allows you to complete the tutorial using an editor of your choice. Here are the steps to follow:

1. Make sure you have a recent version of [Node.js](https://nodejs.org/en/) installed.
2. Follow the [installation instructions for Create React App](/docs/create-a-new-react-app.html#create-react-app) to make a new project.

```bash
npx create-react-app my-app
```

3. Delete all files in the `src/` folder of the new project

> Note:
>
>**Don't delete the entire `src` folder, just the original source files inside it.** We'll replace the default source files with examples for this project in the next step.

```bash
cd my-app
cd src

# If you're using a Mac or Linux:
rm -f *

# Or, if you're on Windows:
del *

# Then, switch back to the project folder
cd ..
```

4. Add a file named `index.css` in the `src/` folder with [this CSS code](https://codepen.io/gaearon/pen/oWWQNa?editors=0100).

5. Add a file named `index.js` in the `src/` folder with [this JS code](https://codepen.io/gaearon/pen/oWWQNa?editors=0010).

6. Add these three lines to the top of `index.js` in the `src/` folder:

```js
import React from 'react';
import ReactDOM from 'react-dom';
import './index.css';
```

Now if you run `npm start` in the project folder and open `http://localhost:3000` in the browser, you should see an empty tic-tac-toe field.

We recommend following [these instructions](https://babeljs.io/docs/editors/) to configure syntax highlighting for your editor.

</details>

### Help, I'm Stuck!

If you get stuck, check out the [community support resources](/community/support.html). In particular, [Reactiflux Chat](https://discord.gg/reactiflux) is a great way to get help quickly. If you don't receive an answer, or if you remain stuck, please file an issue, and we'll help you out.
