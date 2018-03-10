# starter-react-flux 

[![Build Status](https://travis-ci.org/SokichiFujita/starter-react-flux.svg?branch=master)](https://travis-ci.org/SokichiFujita/starter-react-flux) 
[![total](https://img.shields.io/npm/dt/starter-react-flux.svg)](https://www.npmjs.com/package/starter-react-flux) 
[![per year](https://img.shields.io/npm/dy/starter-react-flux.svg)](https://www.npmjs.com/package/starter-react-flux) 
[![per month](https://img.shields.io/npm/dm/starter-react-flux.svg)](https://www.npmjs.com/package/starter-react-flux) 
[![per week](https://img.shields.io/npm/dw/starter-react-flux.svg)](https://www.npmjs.com/package/starter-react-flux) 
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/SokichiFujita/starter-react-flux/blob/master/LICENSE) 
[![npm](https://img.shields.io/npm/v/starter-react-flux.svg)](https://www.npmjs.com/package/starter-react-flux) 
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/SokichiFujita/starter-react-flux/blob/master/README.md) 

A starter kit for a React and Flux projext. You can easily start a standard React and Flux project using awesome libraries.

- [React](http://facebook.github.io/react/), [Flux](https://facebook.github.io/flux/)
- [Jest](https://facebook.github.io/jest/)
- [Webpack](https://webpack.js.org), [Webpack-dev-server](https://webpack.github.io/docs/webpack-dev-server.html), [Webpack Bundle Analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer)
- [Babel](https://babeljs.io), [React preset](http://babeljs.io/docs/plugins/preset-react/), [Env preset](https://babeljs.io/docs/plugins/preset-env/), [Stage 0 preset](https://babeljs.io/docs/plugins/preset-stage-0/)
- [ESLint](http://eslint.org), [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)
- [React-Router](https://reacttraining.com/react-router/)
- [Immutable.js](https://facebook.github.io/immutable-js/)
- [Material-UI](http://www.material-ui.com)
- [Axios](https://github.com/mzabriskie/axios)

## Installation

```
npm install -g starter-react-flux
```

## Usage

### Create a new project

```
mkdir my-app && cd my-app
starter-react-flux init       // Setup a new React and Flux project.
```

### Launch the application

```
npm start                     // Launch the app with webpack-dev-server.
```

#### Top page

![](./images/app1.png)

#### Another page with React-Router

![](./images/app2.png)


```
npm test                      // Test with Jest.
```

![](./images/test.png)

```
npm run build                 // Build the app into the ./public directory.
```

```
npm run lint                  // Check the code by ESLint with AirBnb's style guideline.
```

![](./images/lint.png)

```
npm run fix                   // Fix the code by Prettier with AirBnb's guidline.
```

![](./images/fix.png)


#### Bundle Analyze

```
npm run bundle-analyze
```

![](./images/webpack-bundle-analyzer.png)


### To add optional components for React or Flux

```
starter-react-flux generate component [Component_Name]   // Generate a React Component file.
starter-react-flux generate container [Container_Name]   // Generate a Container file for Flux.
starter-react-flux generate store [Store_Name]           // Generate a ReduceStore file for Flux.
starter-react-flux generate action [ActionCreators_Name] // Generate a ActionCreators file for Flux.
```

## Directory structure of the generated app

```
.
├── .babelrc          //Configuration for Babel
├── .eslintrc         //Configuration for ESLint
├── __tests__         //Test files for JEST
├── app
│   ├── App.js        //Entry point
│   ├── actions       //Action Creators
│   ├── components    //React Components
│   ├── constants     //Constatns for Action Creators and Stores
│   ├── dispatcher    //Dispatcher
│   ├── stores        //Reduced Store
│   └── utils         //Utils
├── node_modules
├── package.json
├── public            //Build assets and other assets
│   ├── css
│   ├── img
│   ├── index.html
│   └── js
└── webpack.config.js //Configuration for Webpack
```

## License

- MIT License


