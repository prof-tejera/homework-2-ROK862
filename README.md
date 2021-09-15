# URL to live application:
Find me here: https://rok862.github.io/CSCIE39HomeWork2/

# How did you deploy it?
- I used github pages to deploy my project. However, since i am using SCSS preprocessor for partical effects, i needed to run `npm install sass` on the host. To achieve this, I added the `Install SASS` step to the build job--which is triggered everytime there is a change to the master branch.
- I also programmed a few scripts for color animation--just to make my life a bit harder :).

# What code editor are you using?
- I used visual studio code, preferably in browser. Makes things work easier, particulary when working with github repo's.

# React - Dev Setup and Deployment

This assignment is intented to help you set up your development environment for React. You will create a simple React App and deploy using one of the methods covered in lecture.

## Step 1
- Install `npx` following the instructions here: https://www.npmjs.com/package/npx
- run `npx create-react-app my-first-app` to create the React application
- In the newly created app, replace the contents of `App.js` including your name:

```
import './App.css';

function App() {
  return (
    <div className="App">
      <header className="App-header">
        <p>Hello CSCI E-39!</p>
        <p>
          My name is ____________
        </p>
      </header>
    </div>
  );
}

export default App;
```

- run `npm install`
- start the app with `npm start`
- verify the app is running

## Step 2
Deploy the application using one of the methods covered in class: Github Pages, Render, or AWS. If you prefer to use a different service, explain your choice and process.

## Submitting
Edit this file (README.md) and complete the following:

- URL to live application: 
- How did you deploy it?
- What code editor are you using?

That is all!
