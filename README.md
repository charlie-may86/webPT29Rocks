# Steps to start a new node project
1. intitalize the package.json npm init -y
2. make a gitignore with npx gitignore node
3. intialize a git repo with git init
4. get the linter fired up with npx eslint --init
5. questions you will be asked
    1. to check syntax and find problems
    2. CommonJS (require/exports)
    3. None of these
    4. No (the project does not use typescript)
    5. Toggle using spacebar to have only Node on
    6. JSON
    7. Yes
6. Get and index.js file
7. npm i -D nodemon
8. in package.json add the script: "server": "nodemon index.js",
9. hit npm run server
10. Nodemon is for development purposes only, so we need to add a start script in the package.json
    "start": "node index.js",

Dependencies to install
    npm i express cors helmet dotenv

For heroku:
    1. start .env file