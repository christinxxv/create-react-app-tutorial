# How to Set up a React Application
This tutorial will show you how to set up a React Application using Node JS and Visual Studio Code. 

</br>

## Overview
This tutorial is a step by step tutorial that walks you through creating a basic react app using Visual Studio Code. In this tutorial we will:
- [Install Visual Studio Code](#installing-visual-studio-code)
- [Install Node JS](#installing-node-js)
- [Create A React App](#creating-a-react-app)
- [Run the React App](#running-the-react-app)
- [Declutter the Project](#decluttering-the-project)

</br>

## Installing Visual Studio Code
Click [here](https://code.visualstudio.com/) to install Visual Studio Code.

</br>

## Installing Node JS
Click [here](https://nodejs.org/en/download/) to install Node JS. I reccommend always choosing the latest LTS version.

</br>

## Creating a React App
1. Open Visual Studio Code
<img src="https://github.com/christinxxv/react-create-app-tutorial/blob/main/src/images/open-vs-code.png" alt="Alt text" style="width: 400px; height: auto;">

2. Open the Terminal using ctrl + shift + \` (This character is the back quote character. It is located on the same key as tilde '~'). You can also use the Terminal option on the top nav.
<img src="https://github.com/christinxxv/react-create-app-tutorial/blob/main/src/images/vs-code-terminal.png" alt="Alt text" style="width: 600px; height: auto;">

3. Ensure that you have installed node correctly by running this command:
````
 node --version
 ````
4. To create the React Application, run this command:
````
npx create-react-app 'whatever-you-want-to-name-the-app'
````
- For example, mine is called 'my-app'
````
npx create-react-app my-app
````
5. Once your react app is done loading you should see something like this:
<img src="https://github.com/christinxxv/react-create-app-tutorial/blob/main/src/images/app-created.png" alt="Alt text" style="width: 300px; height: auto;">
 

## Running the React App
To run your application, run this command:
````
npm start
````
<img src="https://github.com/christinxxv/react-create-app-tutorial/blob/main/src/images/run-default-preview.png" alt="Alt text" style="width: 300px; height: auto;">


## Decluttering the Project
I know that it can be a little frustrating not know what all these files and folders are for. You really do not need them all. If you want to break it down and declutter the project. Here are the files you really need!
</br></br>
_Note: Once you start deleting files you will have to refactor and change imports and pointers._
<img src="https://github.com/christinxxv/react-create-app-tutorial/blob/main/src/images/app-decluttered.png" alt="Alt text" style="width: 300px; height: auto;">

You can also use or reference my above source code to see how to customize and refactor it to get it running with the decluttered format. 


</br>


## More on Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)