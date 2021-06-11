Budget Tracker App License: MIT
Description
This is an app to keep track of withdrawals and deposits. Its created using express.js and mongoDb. It also uses Progressive Web Applications such as Web Manifest, service worker and IndexedDB to add offline functionality.

Built Using
JavaScript, ES6, Node.js (Express, Mongoose, compression), MongoDB and PWAs (Web Manifest, Service worker, IndexedDB)

Table of Contents
Installation
Usage
User-Story
Acceptance-Criteria
License
Contributing
Screenshot
Deployed
Questions
Installation
To clone the repo run git clone. In order to install the necessary dependencies, run npm install in your terminal.

Usage
After installing all the dependencies, run npm start in your terminal to start the server.

User-Story
AS AN avid traveler
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling

Acceptance-Criteria
GIVEN a budget tracker without an internet connection
WHEN the user inputs an expense or deposit
THEN they will receive a notification that they have added an expense or deposit
WHEN the user reestablishes an internet connection
THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated