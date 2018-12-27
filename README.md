# ![Icon](https://raw.githubusercontent.com/clsavino/react-shift-scheduler/master/public/assets/images/logo-small.png) Rostr

### [Please check out our wiki!](https://github.com/Mystr-Melbourne/Mystr/wiki)

Rostr is an employee management and scheduling app that allows…
* Managers to manage and schedule employees
* Employees to view work schedules

View app live on [Heroku](https://reactRostr.herokuapp.com)

## Run locally

Rostr requires [Node.js](https://nodejs.org/) and [MongoDB](https://docs.mongodb.com/manual/installation/) to run

### Installation
Once mongo is installed, open a new terminal and run 

`$ mongod`

Open another terminal window and navigate to project directory and run

`$ npm install`

Create a .env file with and add the code below (not strings)

``` 
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
GOOGLE_CALLBACK_URL=http://YOUR_DOMAIN/auth/google/callback
    
LINKEDIN_ID=
LINKEDIN_SECRET=
LINKEDIN_CALLBACK=http://YOUR_DOMAIN/auth/linkedin/callback
```

If you dont want to go through the trouble of creating the API keys, put in dummy numbers/text and the app should still work, however passport social login will not.

### Run App

Use this command to automatically build and run the environment with one command

`$ npm run dev`

---

otherwise you can manually build with

`$ npm run build`

Wait for webpack to bundle then

`$ npm start`

Open a browser and go to [http://localhost:8080](http://localhost:8080)

## Original Developers of [Schedulr](https://github.com/clsavino/react-shift-scheduler) on which this project is based
* Andrea Roche @amr08
* Christi Savino @clsavino
* Houston Breedlove @hcbreedl
* Nicolás Cáceres @mr-attack

## Tech
Built with React, Node, Express, MongoDB, Passport.js
