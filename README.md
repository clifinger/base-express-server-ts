# Minimal StarterKit with Express, Typescript
A simple as possible Express server with typescript,
Hot reloading and code linting/formatting

## Getting Started

* Install the project with 
    ```sh 
    npm install
    ```

* Launch the dev server
    ```sh 
    npm run dev
    ```

* Building server
    ```sh 
    npm run build
    ```

* Start server
    ```sh 
    npm run start
    ```


## Commands used to make the starterKit

```sh
mkdir  base-express-server-ts && base-express-server-ts
npm init --yes
npm i express dotenv
npm i -D typescript @types/express @types/node nodemon ts-node
npx tsc --init
npm init @eslint/config
npm i -D prettier eslint-config-prettier eslint-plugin-prettier
mkdir src/ && touch README.md src/index.ts .prettierrc
```
