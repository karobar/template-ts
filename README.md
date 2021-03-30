# Node Template

Clone this repo.

#### Components
* [ESLint (linting)](https://eslint.org/docs/user-guide/getting-started)
* [husky (git hook management)](https://typicode.github.io/husky/#/)
* [EditorConfig (IDE configuration)](https://editorconfig.org/)

### Initialize Template

    ./prepare.sh && rm ./prepare.sh
    npm install

### To run

    yarn start

### Automated Tests & Linting 
This template will run automated tests and linting tools before each `git push`, but if you
want to run those linting tools yourself manually, run:

    yarn test