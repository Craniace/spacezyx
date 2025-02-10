# Sapcezyx Project

## Overview
This project contains a simple HTML file named `index.html` that serves as the main entry point for the NASA-themed application. The application utilizes modern JavaScript features for handling API calls and data storage.

## Functionality
- **API Calls**: The project makes asynchronous API calls using the `async/await` syntax, providing a cleaner and more readable way to handle asynchronous operations.
- **Local Storage**: The application leverages local storage to save data retrieved from API calls, allowing for persistent data access even after page refreshes.

## File Structure
- `index.html`: The main HTML file that contains the structure and content of the webpage.
- `style.css`: The CSS file for styling the HTML elements.
- `img/`: Directory containing images used in the project.

## Usage
To view the webpage, open the `index.html` file in a web browser.

## License
This project is licensed under the MIT License.

##✅ Preloading Today's Image
The page fetches today's NASA image automatically when loaded.
This improves the user experience as they don’t see an empty page.

##✅ Caching API Responses
Stores previously fetched images in localStorage.
If a user reselects a date, it loads instantly without another API call.

##✅ Skeleton Loader Instead of Text
Instead of "Loading image...", shows a grey box (smoother UI).
Looks better than just text while waiting for the image to load.

##✅ Lazy Image Loading (loading="lazy")
Ensures the browser only loads images when they are visible.
Reduces unnecessary data usage & speeds up page load.

##✅ Loading Optimization
Shows "Loading image..." instead of a blank screen.
Uses image.loading = 'lazy' to delay loading until needed.

##✅ Faster Image Loading
Uses data.hdurl || data.url
hdurl → High-resolution image (slow but high quality).
url → Lower-resolution image (loads faster).
Enables lazy loading so images load only when visible.

##✅ Handles API Response Properly
Uses async/await instead of .then() for better performance.
Catches errors and prevents broken UI. 
