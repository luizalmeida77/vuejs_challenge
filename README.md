# vuejs-challenge
Coding challenge for evaluating VueJS candidates at Hypery

## Description
You should develop a simple project using VueJS to read an [external API](https://developers.themoviedb.org/3/trending/get-trending) and render the movies that are trending on the day or week, you should have the option to select daily or weekly.

## Tasks
 - [x] Fork this repository;
 - [x] Config a single route in your app, like /trending;
 - [x] You must show the movie's image, title, release date and average vote;
 - [x] Feel free to choose from grid, list or carousel to display the movies;
 - [x] Open a PR and submit your code for review;

## Requirements
 - [x] Vue 3

### Tips
- Use [The Movie DB API v3](https://developers.themoviedb.org/3/trending/get-trending)
- To get a valid token go to [your panel](https://www.themoviedb.org/settings/api) Settings -> API -> API Key (v3 Auth)
- You'll use the request below to get the trending movies:
```
 GET https://api.themoviedb.org/3/trending/movie/{week/day}?api_key={YOUR_API_KEY}
```
- To be able to display the movie poster, you'll need to use the image URL in the following format:
```
https://image.tmdb.org/t/p/w200/{POSTER_PATH}
```

# Install the dependencies
```bash
yarn
# or
npm install
```

### Start the app in development mode (hot-code reloading, error reporting, etc.)
```bash
npx quasar dev 
or
quasar dev
```
(Need quasar) https://quasar.dev/start/quasar-cli

### Lint the files
```bash
yarn lint
# or
npm run lint
```
