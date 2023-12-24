# Registration Form

This is a simple registration form implemented using Node.js, Express, and MongoDB. The form allows users to sign up by entering their username and password.

## Features

- User Registration: Users can enter their username and password to sign up. The entered data is then stored in a MongoDB database.

## Prerequisites

- Node.js
- MongoDB
- NPM

## Dependencies

- Express
- Body-parser
- Mongoose

You can install the dependencies by running `npm install express body-parser mongoose` in your project directory.

## How to Run

1. Start your MongoDB server.
2. In your project directory, run `node server.js` to start the server.
3. Open your web browser and go to `http://localhost:3000` to see the registration form.

## Code Structure

The server is set up in `server.js`. This file connects to the MongoDB database and starts the server.

The user schema is defined using Mongoose. A new user is created and saved in the database when the form is submitted.

The HTML form is served as a static file by Express. The form makes a POST request to the `/submit-form` endpoint when submitted.

## Note

This is a basic implementation and does not include any form of password encryption or user authentication. In a real-world application, you would want to add those for security reasons. You might also want to add more fields to your form and schema depending on the information you want to collect from the user.
