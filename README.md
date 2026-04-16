# Essential JS2 React Sample with Router and Webpack
 
This repository contains a sample application that demonstrates how to build a React application using **TypeScript (TSX)** and **Webpack**, with **React Router** configured for client-side navigation. The project serves as a clean and lightweight reference for developers who want to understand how modern React applications can be structured without relying on large frameworks or extensive boilerplate tooling.
 
The sample focuses on compiling React and TypeScript source files into a single JavaScript bundle using Webpack. This bundled output is then served through a static HTML page, making the application suitable for static web hosting scenarios. The explicit configuration and minimal setup help developers better understand the relationships between React, TypeScript, Webpack, and routing.
 
## Features
 
- Webpack-based build pipeline for compiling React and TypeScript (TSX) source files 
- Integration with React Router for client-side navigation and route management 
- Generation of a single JavaScript bundle optimized for static HTML serving 
- Simple and transparent project structure for easier customization and learning 
- Useful reference for setting up React applications with custom tooling 
 
## Prerequisites
 
Before running this project, ensure the following tools are installed on your system:
 
- **Node.js**
- **npm** version 6.6.0 or newer 
 
You can verify the installed versions using the following commands:
 
```bash
node -v
npm -v
```
If necessary, install the referenced Webpack version globally:
```bash
npm i -g webpack@2.6.1
```

Note that global installation is optional if Webpack is already included as a local dependency in the project.
Install
Install all required dependencies by running the following command in the root directory of the repository:
 
```bash
npm install
```

This will download and install all packages specified in the package.json file.
Run (Development)
To compile and run the application in development mode, use the following command:
```bash
npm start
```

The project will be built using Webpack and served locally. This setup allows developers to test changes and experiment with the configuration while exploring how routing and bundling work together in a React and TypeScript environment.
