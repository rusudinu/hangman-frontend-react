# Getting Started with Create React App

The backend can be found in [this repo](https://github.com/rusudinu/hangman-api).

1. You will clone and start the backend mentioned above.
2. You will start developing the frontend according to the following requirements:

* You will need to have two routes: one for creating a game and another one for joining a game.
* The game creation route will have a form with an input field for the word to be guessed and another input for the number of allowed guesses.
* The game joining route will have a form with an input field for the game id and another input for the player's name. After joining a game, on the same route, the player will be able to see the game status and the word to be guessed. The player will also be able to make a guess on this page. The player will be able to see the number of guesses left and the letters that have been guessed.

Please note that: these are the minimum requirements. You can add more features if you want. You can use bootstrap, tailwindcss or write the css 'by-hand'.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!
