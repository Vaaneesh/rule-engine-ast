# Rule Engine AST

## Overview

The Rule Engine AST is a web application designed to create, combine, and evaluate rules using Abstract Syntax Trees (AST). The system allows users to input rules, combine multiple rules, and evaluate these rules against a given dataset. This application is built using React for the frontend and Node.js with Express for the backend.

## Features

- **Create Rules**: Input rules in a specified format and convert them to AST.
- **Combine Rules**: Combine multiple rules into a single AST.
- **Evaluate Rules**: Evaluate the combined rules against a dataset.
- **Visualize AST**: Display the AST for individual and combined rules.

## Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js, Express.js

## Installation

### Prerequisites

- Node.js
- npm (Node Package Manager)

### Steps

1. **Clone the repository**

    ```sh
    git clone https://github.com/Vaaneesh/rule-engine-ast.git
    cd rule-engine-ast
    ```

2. **Backend Setup**

    - Navigate to the backend directory

        ```sh
        cd backend
        ```

    - Install the dependencies

        ```sh
        npm install
        ```

    - Start the backend server

        ```sh
        npm start
        ```

    ![API check](./create_rule(postman).png)
    ![API check](./combine_rule(Postman).png)
    ![API check](./evaluate%20rule.png)

3. **Frontend Setup**

    - Navigate to the frontend directory

        ```sh
        cd ../frontend
        ```

    - Install the dependencies

        ```sh
        npm install
        ```

    - Start the frontend development server

        ```sh
        npm start
        ```

4. **Concurrent Start**

    - You can also start both frontend and backend concurrently using the root package script

        ```sh
        npm run dev
        ```

## Usage

### Create Rule

- Open your browser and navigate to `http://localhost:3000`
- Enter a rule in the input box (e.g., `age > 30`) and click the "Create Rule" button.
- The rule will be converted to AST and displayed on the screen.

### Combine Rules

- Enter multiple rules and create them as described above.
- Click the "Combine Rules" button to combine the created rules into a single AST.
- The combined AST will be displayed on the screen.

### Evaluate Rule

- Enter the JSON data in the textarea (e.g., `{"age": 35}`).
- Click the "Evaluate Rule" button to evaluate the combined rules against the entered data.
- The result of the evaluation will be displayed on the screen.

