# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.


**ProjectSummary**
This project was designed to help consolidate the majority of the knowledge that I have built up through the Srimba course. It features the use of a sign in and sign up page, allowing users to create an account and return with their details still being valid. This was achieved with the help og google firebase authentication which is what stored the user email and password information. 

Once signed in, the users are greeted with a dashboard page which hosts information relating to various cryptocurrency coins that were fetched using the coingeko API. A search bar was built to allow users to search for any coin of their choosing which is recognised by coingecko. This was done by using the array.filter() method to instantly update the dashboard and allow the user to filter coins based on either the coin id or coin symbol name. For example, bitcoin could be searched by beginning to type 'bitcoin' or 'btc'. Since the filter property took the input field value and used the .includes() method, coins were easily found without the user having to correctly spell the coin name. 

**Note**
Since this is my main project, I strive to learn more things which can then be encorporated into this application. Some ideas that I have so far is that users will eventually be able to save a coin into a watchlist, and then detail how much money they invested into each coin and at what price. The application will store and track this information, giving an update on how well their investment is performing in percentage terms.

