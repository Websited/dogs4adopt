## Intro

This NodeJS app scrapes data from animal shelters in Poland and serves this data as API. The goal is to provide as much information as possible to people who wants to adopt a dog.

## Installation & Running

- Clone this repo
- provide link to your mongodb database in `db/mongoose.js`
- uncomment proper command in app.js to scrape data to your database (please run this one time and then comment out again)
- Run with `npm run start` command
- visit `localhost:3000` to see the app use paths below to read data from DB

## API

This app has api feature, api routes are listed below:

- `/api/all` gets all dogs from database
- `/api/shelter/[shelter]` gets dogs from certain `shelter`, currently working shelters are:
  - `lodz` (Łódź)
  - `dgorna` (Dłużyna Górna)
- `/api/id/[id]` gets certain dog by it's `id`
- `/api/name/[name]` searches dogs by `name`, or part of it
- `/api/random/[x]` returns `x` random dogs


## Features to implement

- Add more shelters
- DB pagination

## Contributing

Feel free to help!
Please read [[Contribute](CONTRIBUTING.md)] first!

## Demo

[[Demo on heroku](http://dogs4dopt.herokuapp.com)] (might take some time to run at first visit, this version is limited)

## Important Notes!
- Please do not abuse this application as currently it uses other page resources (dog images)
- If you feel that this app harms you in any way please contact me @ [przemekpierzchalka@gmail.com(mailto:przemekpierzchalka@gmail.com)]
