# GeoQuiz educational web app and game

There are two different modes in this educational geography app: "Choose Learn" and "Choose Play".

In "Learn mode" you can discover facts and details about each of the world's countries by clicking in the interactive map.

In "Play mode", you will be prompted with a country's flag. Use the map to guess the country from its flag! You can create your own account that will save your details and a score for your correct guesses.

<br />

![GeoQuiz_landing_page](https://user-images.githubusercontent.com/65955047/103558058-00d17300-4eac-11eb-9f39-5e402a6c8d2b.png)

## MVP

A user should be able to:

- Interact with a visual map of countries
- Click on a country to display facts/details
- Play a game to guess a country from its flag

The app should:

- Use an API for country data
- Import library to render an interactive map

## Example Extensions
- See visual results of correct answers
- Record which countries have been correctly identified by a user
- Show details when correctly selected
- Top scores list

## Setup
Install dependencies in both the client and the server folders:
```
$ cd client
$ npm install

$ cd server
$ npm install
```

Seed the database.  Within the server folder:
```
$ npm run seeds
```

Run express (leave running in a terminal window).  Within the server folder:
```
$ npm run server:dev
```

Run Vue development environment (leave running in a terminal window).  Within client folder:
```
$ npm run serve
```


## API, Libraries, Resources
- [vue-svg-map](https://www.npmjs.com/package/vue-svg-map)
- [RESTCountries API](https://restcountries.eu/)
