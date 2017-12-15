# review_with_del

# Q2
## Week 1 Review


**Structure**
`top_characteer` our project directory
	`frequency.js` code to count character frequency
	`package.json` config to remember our nodes moduoles
	`index.js` our code to sort frequency entries and list **top ten**
	*Bonus: could also installe `chalk` to pretty print the top characters
	`test` a directory for our test using mocha
	*`frequency_test.js` it will exercise our frequency mode


We covered some of the following topics:

* Functional programming:

  * ForEach, Map, Filter, Reduce
  * Concepts: Avoid mutations and side effects maybe freezing objects
  * Composing small functions

* Node Ecosystems:

  * How to utilize NPM and what it is.
  * Export, Require and Node Modules: chalk
  * NPM Scripts (using `npm test` or `npm run test`)
  * Install `mocha` and `chai` as dev dependencies

* Git Flow:

  * How to use git with a new NodeJS project
  * Reviewing git commands:
    * `git init`
    * `.gitignore`
    * `git add` for staging
    * `git commit` and frequently committing
    * `git diff` and `git diff --cached` (for staged files)
    * `git log` to review commit comments
    * `git reset --hard` for a nuclear option: BE CAREFUL!!?!
    * NOTE: `git reset` by itself to just unstage files

* Shell Familiarity:

  * What is Shell vs Command Line
  * What is the PATH and it's connection to `bin` directories
  * Should have mentioned ENV variables: $PATH
  * We talked a bit about io
    * STDOUT and using `echo` with a redirect

* Practiced ES6

  * Using destructuring to select keys from objects
  * Using `=>` arrow functions to write functions
  * Using block scoping and `let` and `const`
  * Template strings vs array.join or string + string

* Generally Using Node:

  * Creating a module and exporting various values
  * Design: functional modularity, small abstractions, information hiding
  * Testing our modules and using `mocha` and `chai`

* Intro TDD

  * Simplest code to pass a test
  * The YAGNI principle
  * Red-Green-Refactor
  * Writing multiple tests for various behaviors
