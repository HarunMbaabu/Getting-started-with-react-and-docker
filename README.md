# Getting Started with Create React App 

Docker is possibly the most popular solution to have all your services run in a container. Containers allow us to run and develop an application in the same environment, regardless of what machine you’re on.


Containers are a standardized unit of software that allows developers to isolate their app from its environment, solving the “it works on my machine” headache.


Containers are an abstraction at the app layer that packages code and dependencies together. Multiple containers can run on the same machine and share the OS kernel with other containers. 

![alt text](https://github.com/LuxTechAcademy/Getting-started-with-react-and-docker/blob/main/reactcontainer.png) 


When you deploy an application you have to install all the dependencies (MySQL, Node, Redis) on the host system. With Docker, instead of managing host systems, you just specify a Docker file that lists all the dependencies for the project. 

Docker builds an image out of all of those dependencies which we can re-use over multiple computers. Docker users can store images in private or public repositories, and from there can then deploy containers, test images, and share them. 


Think of Docker applications as tiny containers, which have their own filesystem and dedicated RAM, but a shared kernel with the host operating system.


## Here Are a Few Reasons Why You Should Consider Using Docker
   1). Docker helps to make shipping environments more predictable. 
   
   2). Solves the “works on my machine” problem.
   
   3). You can share and reuse Docker containers between projects and teams.

## Installing Docker
You can download and install Docker on multiple platforms. Refer to the following section and choose the best installation path for you. Head over to this link to download Docker.

![alt text](https://github.com/LuxTechAcademy/Getting-started-with-react-and-docker/blob/main/docker.png) 



# About The Project.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

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

### `yarn build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
