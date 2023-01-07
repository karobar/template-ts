# TypeScript Template

Start with a nice baseline of tools.

#### Components
* [ESLint (linting)](https://eslint.org/docs/user-guide/getting-started)
* [husky (git hook management)](https://typicode.github.io/husky/#/)
* [EditorConfig (IDE configuration)](https://editorconfig.org/)

# Installation Instructions
## Option 1: NPM + Yarn
### Initialize Template

    ./prepare.sh && rm ./prepare.sh
    npm install

### To run

    yarn start

### Automated Tests & Linting 
This template will run automated tests and linting tools before each `git push`, but if you
want to run those linting tools yourself manually, run:

    yarn test

## Option 2: pnpm
### Initialize Template

    ./prepare.sh && rm ./prepare.sh
    pnpm install
    
### To run

    pnpm start
