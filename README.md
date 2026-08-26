# Recipe App 馃嵈

A clean JavaScript application for finding, viewing, and saving recipes from the Forkify API.


## What it can do

- Search recipes and browse paginated results
- View ingredients, cooking time, and servings
- Adjust ingredient quantities when servings change
- Save bookmarks in the browser
- Add a personal recipe with an API key

## Built with

JavaScript (ES6+) 路 HTML5 路 Sass/SCSS 路 Parcel 路 Forkify API 路 MVC architecture

## Run locally

```bash
git clone https://github.com/fhjoy/Recipe--App.git
cd Recipe--App
npm install
npm start
```

Parcel will display the local development URL in the terminal.

To add personal recipes, replace `<YOUR_KEY>` in `src/js/config.js` with a valid Forkify API key.

## Project status

This is a learning project from 2022. The Forkify search API is still available, but the repository uses an old Parcel 2 release candidate and a legacy lockfile. The current deployment or installation may therefore fail with modern Node.js versions until the dependencies are updated.

## Visit the site

https://recipe-appv2.netlify.app

