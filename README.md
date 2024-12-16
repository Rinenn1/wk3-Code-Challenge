# wk3-Code-Challenge

# Movie Selector App

This project is a simple movie selector web application built with HTML, CSS, and JavaScript. The app allows users to select a movie from a dynamically generated list and view detailed information about the selected movie.

## Features

- Dynamically renders a list of movies using JavaScript.
- Displays details for the selected movie, including:
  - Title
  - Genre
  - Director
  - Year of release
  - Description
- Highlights the currently selected movie for better user experience.

## How It Works

1. **Dynamic Rendering**: The movie list is dynamically generated using JavaScript from a predefined data structure.
2. **Event Handling**: Clicking on a movie in the list triggers an event handler that updates the movie details section.
3. **Interactive UI**: The selected movie is visually highlighted to indicate the user's current choice.

## File Structure

```
project-folder/
│
├── index.html       # HTML structure for the app
├── style.css        # CSS for styling the app
├── script.js        # JavaScript for dynamic functionality
└── README.md        # Documentation for the app
```

## Setup and Usage

1. Clone this repository or download the files.
2. Open the `index.html` file in your favorite browser to run the application.
3. Select a movie from the list to view its details in the details section.

## Demo

1. Open the app in your browser.
2. Select a movie from the list.
3. View the movie details in the details section.

## CSS Customization

The `.selected` class is used to highlight the currently selected movie. You can customize the styles for this class in the `style.css` file.

```css
.selected {
  background-color: #f0f0f0;
  color: #333;
}
```

## Future Improvements

- Add more movies to the list.
- Include a search bar to filter movies.
- Enhance the UI with animations and improved styles.
- Make the app responsive for mobile devices.

---

Enjoy exploring the movies with this app! Feel free to contribute or provide feedback.
