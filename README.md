# Setting up a production grade Express backend server with TypeScript

### Basic setup to start the project

Initialise the project with `npm init -y`

And install the express module to build the basic express server by typing a command `npm i express`

Install ts-node `npm i ts-node` for executing TypeScript directly

- Install ts-node to execute TypeScript files directly in Node.js without manually compiling them into JavaScript first.

- Simplify the development workflow by allowing .ts files to run directly during development.

- Useful for running TypeScript scripts and backend development tasks.

Install type definition for node and express by entering a command `npm i -D @types/express @types/node` in the CLI

- @types/express: Provides TypeScript types for Express APIs like Request, Response, and Router.
- @types/node: Provides TypeScript types for Node.js APIs like process, Buffer, and built-in modules.

Install the typeScript for static types for our js code `npm i -D typescript`

- TypeScript is a superset of JavaScript that adds static typing, helping you catch errors before running your code.
- Enables type checking in your Express/Node.js project.
- Helps catch type-related errors during development.
- Improves code quality and editor autocomplete.
