# Simple API Restaurant — Restaurant Recipe Finder

This project is a browser-based recipe finder for people working in or managing a restaurant. It uses TheMealDB API to search for meals by name or retrieve a random meal, then displays the recipe information returned by the API.

## How it works

- **Search meals:** Enter a meal name, such as chicken or pasta, and submit the form. The app sends the search term to TheMealDB's search endpoint.
- **Find a random meal:** Select **Random Meal** to request a randomly selected recipe.
- **View recipe details:** Each result displays the meal name and image, category, cuisine/area, available ingredients and measurements, and preparation instructions.
- **Handle API responses:** The app shows a loading message, reports when no matching meals are returned, and displays an error if the API request or result rendering fails. Console messages help diagnose request and rendering issues.

The front end is built with HTML, CSS, and vanilla JavaScript. It fetches data directly from TheMealDB in the browser and does not require a database or a separately hosted application server.

## Live Demo

[Open Simple API Restaurant](https://simple-api-restaurant-hlhu.onrender.com/)

The front end is deployed as a Render Static Site.
