<a name="readme-top"></a>
### <div align="center"><a href="#"><img src="https://github.com/Benawi/Benawi/assets/21217148/de823737-5f7f-4de8-b62e-3fe88c238eab"/></a></div> 

# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
    - [Live Demo](#live-demo)
    <!-- - [Walkthrough](#Walkthrough) -->
- [💻 Getting Started](#getting-started)
  - [Setup](#setup)
  - [Prerequisites](#prerequisites)
  - [Install](#install)
  - [Usage](#usage)
  - [Run tests](#run-tests)
  - [Deployment](#triangular_flag_on_post-deployment)
- [👥 Authors](#authors)
- [🔭 Future Features](#future-features)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)

- [📝 License](#license)

# 📖 Book Store React Project <a name="about-project"></a>

Book Store React Project - Microverse! - An online Bookstore app built with React, Redux, CSS, and HTML. Users can browse books by category, add them to a cart, and proceed to checkout. The app features a search function, allowing users to search for books by title or author. project is a repository consisting of the following files:
- Html files.
- CSS files
- JS files.
- HTML, CSS, and JS linters file.

## 🛠 Built With <a name="built-with"></a>

## Tech Stack <a name="tech-stack"></a>

<ul>
  <ul>
  <li><a href="https://microverse.notion.site/HTML-CSS-Get-a-head-start-275eb85fd34b4416aa06ec635d69cdaf">HTML</a></li>
  <li><a href="https://microverse.notion.site/HTML-CSS-Get-a-head-start-275eb85fd34b4416aa06ec635d69cdaf">CSS</a></li>
      <li><a href="https://microverse.notion.site/HTML-CSS-Get-a-head-start-275eb85fd34b4416aa06ec635d69cdaf">JS</a></li>
      <li><a href="https://react.dev/learn/start-a-new-react-project#create-react-app">React</a></li>
</ul>


## 🔑 Key Features <a name="key-features"></a>

### React Project: [Requirements](https://github.com/microverseinc/curriculum-react-redux/blob/main/bookstore/sneak_peek_v3_0.md)

### Features Added:
- [x] Book Store: 
   - [x] Setup a new React application using Create React App
   - [x] Create a directory for your reusable components: /components.
   - [x] Install React [Router V6](https://reactrouter.com/en/main/start/tutorial#setup)
   - [x] [Setup your router](https://reactrouter.com/en/main/start/tutorial#adding-a-router) inside of <App>
   - [x] Add 2 routes in your application, each should render a page component:
        - [x] /
        - [x] /categories
   - [x] Create components inside of the /components directory:
        - [x] Contains individual book states, as well as a button to delete the book.
        - [x] Contains a list to render individual books
        - [x] Contains a form to create a new book
        - [x] Contains navigation to link to the 2 routes you created
    - [x] Add Redux Toolkit (npm install react-redux @reduxjs/toolkit).
   - [x] Create a directory that will contain all your Redux logic (/src/redux)
   - [x] Configure a Redux store (/src/redux/store.js)
   - [x] Define a slice of state for books that:
        - [x] Includes an array of books (initial state: empty array)
       - [x] Includes a reducer that adds books
      - [x] Includes a reducer that removes a book
  - [x] Define a slice of state for categories that:
      - [x] Includes an array of categories (initial state: empty array)
      - [x] Includes a reducer that checks the status and always returns "Under construction" (the initial state should check to that string)
 -[x] Structure your application files using a "feature folder" approach and use the [ducks pattern](https://github.com/erikras/ducks-modular-redux) for your Redux files.
 - [x] Wrap `<App>` with the `<Provider>` component from react-redux
  - [x] Pass your configured store into the `<Provider>`
  - [x] Create an initialState variable for your booksSlice, which will include 
  - [x] Display your books, received from the slice, in a reusable component
  - [x] Dispatch actions using useDispatch.
  - [x] Add a `<Button>` component, which includes:
    - [x] An event handler that adds a book to the books array (with attributes id, title, and author)
  - [x] Add a `<Button>` component, which includes:
    - [x] An event handler that removes a book from the books array (by  id)
  - [x] Add any missing JSX elements to the project (without adding extra functionality)
  - [x] The final design should match [Zeplin's design](https://github.com/microverseinc/curriculum-react-redux/blob/main/bookstore/images/bookstore.png) (this includes all elements + the same styling)
  - [x] The CSS rules detailed in [Zeplin](https://app.zeplin.io/project/5b35a9e13227086040f8eb75/screen/5b695e29bb8c844f118f9378) to style the website used.
  - [x] In the browser tested ; it render without problems, [this](https://benawi.github.io/Microverse-React-Bookstore/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🌐 Live Demo <a name="#live-demo"></a>
- [React Book Store Web App](https://benawi.github.io/Microverse-React-Bookstore/) 
- Learn More [How to deploy react app](https://github.com/gitname/react-gh-pages)
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 💻 Getting Started with Create React App <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console

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

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single-build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point, you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However, we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Setup

Clone this repository to your desired folder:

> cd my-folder
> git clone git@github.com:Microverse-JS-Capstone.git

### Prerequisites

In order to run this project you need:

- GitHub account;
- git installed on your OS.

### Install

> [Linters](https://github.com/microverseinc/linters-config/tree/master/html-css-js)

- Installations required to run this project:

### Install the node module

- Run the following command:

```
npm install
```
### Creat the react 
[Create react app](https://create-react-app.dev/docs/getting-started)

- Run the following command:

```
npx create-react-app my-app
cd my-app
npm start
```

### In order to import a CSS file add the style-loader and css-loader to your module configuration

- Run the following command:

```
npm install --save-dev style-loader css-loader
```

### Webhint installation.

- Run the following command:

```
npm install --save-dev hint@7.x
```

### Stylelint installation.

- Run the following command:

```
npm install --save-dev stylelint@13.x stylelint-scss@3.x stylelint-config-standard@21.x stylelint-csstree-validator@1.x
```

### ESLint

- Run

```
npm install --save-dev eslint@7.x eslint-config-airbnb-base@14.x eslint-plugin-import@2.x babel-eslint@10.x
```

### Usage

You can use this project by cloning it to your folder and changing index.html and styles.css files.

### Run tests

To run tests, run the following commands:

To track linter errors locally follow these steps:

Download all the dependencies run:

```
npm install
```

Track HTML linter errors run:

```
npx hint.
```

Track CSS linter errors run:

```
npx stylelint "**/*.{css,scss}"
```

Track JavaScript linter errors run:

```
npx eslint .
```

### Deployment

You can redeploy this project by adding new lines of code to source files.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 👥 Authors <a name="authors"></a>

### 👤 Habtamu Alemayehu

- GitHub: [Benawi](https://github.com/Benawi)
- Linkdin: [Habtamu](https://www.linkedin.com/in/habtamu-alemayehu-b90367101/)


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🔭 Future Features <a name="future-features"></a>
-  Add some animation style for the project💯
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🤝 Contributing <a name="contributing"></a>

Contributions, [issues](https://github.com/Benawi/Microverse-React-Bookstore/issues), and feature requests are welcome!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ⭐️ Show your support <a name="support"></a>

Give me ⭐️ If you like this project!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🙏 Acknowledgments <a name="acknowledgements"></a>

- We would like to thank the Microverse program for providing us with this great chance

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 📝 License <a name="license"></a>

This project is [MIT](./MIT.md) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
