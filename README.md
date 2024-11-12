# React JS

## What is React JS?

ReactJS is a declarative, efficient, and flexible JavaScript library for building reusable UI components. It is an open-source, component-based front end library which is responsible only for the view layer of the application. The library first appeared in May 2013, developed and maintained by Facebook (now Meta 2021) and later used in its products like WhatsApp & Instagram. It is now one of the most commonly used front-end libraries for web development.

### Key Features:
- **JSX (JavaScript Syntax Extension)**: React uses JSX, a syntax extension for JavaScript allowing developers to write HTML structures in the same file as JavaScript.
- **Virtual Document Object Model (DOM)**: React creates a lightweight copy of the actual DOM, which significantly reduces the cost of updating the UI, resulting in faster rendering and better performance.
- **Component-Based Architecture**: React promotes building reusable UI components for cleaner, more organized code, and easier building of complex UIs.
- **One-Way Data Binding**: React follows unidirectional data flow, which gives better control to the user throughout the application resulting in more predictable and easier-to-debug applications.
- **Declarative UI**: React uses a declarative programming style, which allows developers to describe the desired UI state resulting in easier to build and maintain complex UIs.

---

## How to Set Up React JS?

### Prerequisite Apps

Before installing React JS, you need to install the following software on your system:
- **Node.js**: React relies on Node.js for package management (NPM/Yarn) and plays a crucial role in the development, build, and deployment processes of React applications. You can download it from [Node.js official website](https://nodejs.org/).
- **Code Editor**: A good code editor like [Visual Studio Code](https://code.visualstudio.com/) is recommended for React development.

### Step-by-Step Installation

1. **Install Node.js and NPM**
    - Download and Install Node.js – Visit [Node.js website](https://nodejs.org/) and install the latest version.
    - Check Node and NPM Version - After installation, open a terminal and check that both Node and npm are installed:
    ```bash
        node -v
        npm -v
    ```

2. **Create a New React Project**
    -  You can now create a new React application by opening a terminal and run the following command:
    ```bash
        npx create-react-app my-first-react-app
    ```
    - Replace `my-first-react-app` with your desired project name.

    **Note**: *If you've previously installed `create-react-app` globally via `npm install -g create-react-app`, we recommend you uninstall the package using `npm uninstall -g create-react-app` to ensure that npx always uses the latest version.*

3. **Navigate to the Project directory**
    ```bash
        cd my-first-react-app
    ```

4. **Start the Development Server**
    - Use the following command to start the development server:
    ```bash
        npm start
    ```
    - The development server will automatically open your app in your default web browser at `http://localhost:3000`.

5. **Open React application in VS Code**
    - Open another terminal and run the following command:
    ```bash
        cd my-first-react-app
        code .
    ```

6. **Overview of React App Structure**
    - After the installation of the required project files, your project structure may look something like this:
    ```bash
        my-first-react-app

        ├── README.md

        ├── node_modules

        ├── package.json

        ├── .gitignore

        ├── public

        │ ├── favicon.ico

        │ ├── index.html

        │ ├── logo192.png

        │ ├── logo512.png

        │ ├── manifest.json

        │ └── robots.txt

        └── src

        ├── App.css

        ├── App.js

        ├── App.test.js

        ├── index.css

        ├── index.js

        ├── logo.svg

        ├── serviceWorker.js

        └── setupTests.js
    ```
    - `README.md` - It is a markdown document with numerous links and useful advice that will assist you in using Create React App.
    - `node_modules` - It is a folder with all of Create React App's installed dependency-related code. There will not be any need to access this folder.
    - `package.json` - It oversees the `node_modules` in our project and the scripts required to execute our app.
    - `.gitignore` - It is a file that tells Git not to monitor certain files and folders. Actually, we would not need any large folder, such as the node_modules folder.
    -  `public` - Our React app's static assets, such as photos, svgs, and fonts, can be stored in a folder called public.
    -  `src` - This folder has the source code and all React-related code. Eventually, we will work mostly on it to create a React project.

    **Note**: *Every time you use Create React App to create a new React project, a new Git repository is created. Using `git add .` and `git commit -m "your commit message”`, you can begin saving changes to your app immediately.”*

7. **Building a React Application**
    - Now we need to run the following command to build the app:
    ```bash
        npm run build
    ```
    - This command will create a production build that is optimized for our React project, and it will output the files it has generated along with their sizes.

Following this setup guide, you should be able to install Node.js, set up a React project, and start developing a React application.

---

**Additional References:**
>- https://code.visualstudio.com/docs/nodejs/reactjs-tutorial
>- https://radixweb.com/blog/steps-to-build-react-project-with-create-react-app