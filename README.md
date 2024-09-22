# Getting Started

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

Run the json-server to get json data from the endpoint using the following command:
json-server --watch ./data/db.json

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

## About Project

Displays trip details in list format having styling similar to cards.
The trip details can be filtered based on European & All Trips.

Uses a custom hook useFetch to get the data from the endpoint (as provided).
Implemented error handling, loading and cleanup function in useFetch hook.
