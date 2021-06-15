# COVID-19 Tracker

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
COVID-19 Tracker fetches data of infected people, recovered people and deaths in different countries and visualises it on a web page.

## API Used

[COVID-19 Data API](https://covid19.mathdro.id/api)

The API provides us with the historic data of covid cases globally. It is represented using line graph.
Unfortunately, the API does not provide us the same historic data country wise. It only provides us the info about total infected, total recovered and total deaths. It is represented using bar graph.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

### `npm run deploy`

Deploys the app in the specified origin. It automatically creates a new production build to deploy.
