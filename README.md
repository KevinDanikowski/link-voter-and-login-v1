# Link Voter and Login App

This app is a mimic of Hacker News

Much of the Tutorial can be found at https://www.howtographql.com/react-apollo/0-introduction/ , however there were some issues I've resolved here in this project.
Additionally, some of the code here was made a bit cleaner.

# What was wrong with the HowToGraphQL Tutorial?

Their tutorial was amazing, but here are some additional notes.
1. There is an issue with the subscriptions-transport-ws npm package due to deprecation, this is fixed in the index.js file
2. I've added some explanatory comments for newer people

# How to Start It
1. Go to graph cool, create an account
2. use `npm install` when in the main directory to download node_modules dependencies
3. use `npm i -g graphcool`
4. Go to graphcool console and click endpoints, or type `graphcool endpoints` in bottom left and insert them into the `index.js` file
5. Now you should be able to use `npm start`

# Add Some Data