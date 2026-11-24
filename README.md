# Simple API Restaurant — Restaurant Recipe Finder

This project is a browser-based recipe finder. It uses [TheMealDB API](https://www.themealdb.com/api.php) to search for meals by name or retrieve a random meal, then displays the recipe information returned by the API.

## How It Works

- **Search meals:** Enter a meal name, such as chicken or pasta, and submit the form to search TheMealDB.
- **Find a random meal:** Select the random-meal option to request a randomly selected recipe.
- **View recipe details:** Results display the meal name and image, category, cuisine/area, ingredients and measurements, and preparation instructions.
- **Handle API responses:** The app provides loading feedback, handles searches with no matching meals, and reports request or rendering errors. Console messages help diagnose issues.

## Technology

The front end uses HTML, CSS, and vanilla JavaScript. It fetches data directly from TheMealDB in the browser and does not require a database or a separately hosted application server.

## Live Demo

[Open Simple API Restaurant](https://simple-api-restaurant-hlhu.onrender.com/)

The front end is deployed as a Render Static Site.
