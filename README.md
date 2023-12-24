# CodeTheCode

CodeTheCode is a React application using dummy json database to display problems list and shows an interatctive About Contact Page.

## Features

- Front-end Application using React and Bootstrap framework.
- Displays a list of problems from dummy database using API request.
- Uses Bootstrap library to fit beautiful components.


## Prerequisites

Before you continue, ensure you have met the following requirements:
1. You have installed the version of NodeJS, can be installed from https://nodejs.org/en/download/.
2. run npm install to install all the dependencies.
3. run ```npm install -g json-server```
## Quickstart
1. Run on command-line (Two terminals required)
    ```
    npx json-server --watch db.json
    ```
    and 
    ```
    npm start
    ```
## Repository Overview

├── README.md
├──src
    ├──Components
        ├──About
        ├──Contact
        ├──Home
        ├──Login
        ├──NavBar
        ├──ErrorPage
        ├──ProblemCard
        ├──ProblemDetail
        ├──ProblemsContainer
├── public
├── node_modeules
└── db.json
