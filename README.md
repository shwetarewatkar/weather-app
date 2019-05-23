## Ovanah Frontend Coding Challenge
Create a react app that displays a 5 day weather forecast.
Send a zip file of all the code.  Include a README about project usage and explain your approach along with technical difficulties.

Minimum tech requirements:
1. Use Redux to hold weather information, user location, api communication status, and authorization status.
2. Use component state to hold entered input.
3. Use axios to fetch data.
4. Use mateial ui for components

The api we are using is https://www.metaweather.com/api/.

Screens:
1. Get user's geolocation and display weather information.  Screen should display the city name and a row of cards with the weather state image and queried/useful information.  The screen must be responsive.
2. Add a search bar with a search button for user to search for a specific city.  If the city name is ambiguous, show a screen with the list of cities to choose from. Search bar should be fixed on the top.
3. Create a css spinner when reetriving data from the api.  Disable search bar input when loading.
4. Show no results screen if no results are returned.
5. Create a login page.  Show this screen first if someone tries to access previous screens if they are not logged in.  Hard code a password in Redux.  Set authorization state in redux.

If you have time, host this on Google Cloud.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
