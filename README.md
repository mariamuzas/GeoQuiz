# GeoQuiz educational web app and game

You will find 2 different modes in this web application: “Choose Learn” and “Choose Play”.

In "Learn mode" you can discover different details and facts from each country just by simply clicking the country in the interactive map.

If you want to play the game, change the mode to “Choose Play”. There, you will be able to create your own account that will store your scores and details. In the game you will be prompted with a flag, try to find where the country is located in the map from its flag!

<br />

![GeoQuiz_landing_page](https://user-images.githubusercontent.com/65955047/103558058-00d17300-4eac-11eb-9f39-5e402a6c8d2b.png)

## MVP

A user should be able to:

- Interact with a visual map of countries
- Click on a country to display facts/details
- Play a game to guess a country from its flag
- Incorporate API for country details / import library for map

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
