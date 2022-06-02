<!-- GETTING STARTED -->

## Getting Started

### Installation and Setup

You will need `node` and `npm` installed globally on your machine.

Installation:

`npm install`

To Start Dev Server:

`npm run dev`

To Visit App:

`localhost:3000`

### Getting Started

#### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

-   npm
    ```sh
    npm install npm@latest -g
    ```
-   onchange - used in the scripts to listen for changes in files and automatically format them for you.
    ```sh
    npm install -g onchange
    ```
-   rimraf - needed in the `clean` script. It's used to bypass issues with removing `node_modules` in Windows.
    ```sh
    npm install -g rimraf
    ```

## Usage

### Scripts

I've added the following scripts for convenience. Feel free to modify them to your liking.

-   `npm start`: Starts your production build. Requires you to run `npm run build` beforehand.
-   `npm run dev`: Starts the development server, initially formats all of your code and runs prettier watch mode.
-   `npm run build`: Build your code for production.
-   `npm run lint`: Runs ESlint to check and fix errors automatically. This script is used by Husky.
-   `npm run lint:fix`: Runs `lint` and fixes any found errors.
-   `npm run prettier`: Outputs prettier errors.
-   `npm run prettier:fix`: Fixes all prettier errors.
-   `npm run prettier-watch`: This script uses `onchange` to watch for any changed files and fixes them automatically.
-   `npm run format`: Formats all of your files based on both prettier and eslint configs.
-   `npm run prepare`: Prepares .husky
-   `npm run test`: Runs jest configuration.
-   `npm run test:watch`: Runs jest watch mode.
-   `npm run clean`: Removes node_modules and package-lock.json.
-   `npm run reinstall`: Creates a clean installation.

## Deployment

-   `npm run build` - Builds the app for production. It correctly bundles React in production mode and optimizes the build for the best performance. Your app is ready to be deployed!

Once you have ran `npm run build`, you can run the production build locally with `npm start`.
