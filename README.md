# Agri Chain
A prototype for the Course: Blockchain Optimization
by 
Sai Pujitha (UFID: 7179-9872)
V. Sindhu Kandula (UFID: 1914-5414)
Adil Shaik (UFID: 6998-5592)

## Installation

1. Install Truffle globally.
    ```javascript
    npm install -g truffle
    ```
2. Compile and migrate the smart contracts. Note inside the development console we don't preface commands with `truffle`.
    ```javascript
    compile
    migrate
    ```
3. Run the `liteserver` development server (outside the development console) for front-end hot reloading. Smart contract changes must be manually recompiled and migrated.
    ```javascript
    // Serves the front-end on http://localhost:3000
    npm run dev
    ```
