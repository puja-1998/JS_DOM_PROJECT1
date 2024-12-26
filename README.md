DOM Project README

Overview

This project demonstrates how to manipulate a DOM element using JavaScript. The goal is to use the getElementById method to fetch a target div element and apply various style changes, including background color, margin, padding, font size, font weight, height, and width.

Table of Contents

Installation
Usage
Code Explanation
Contributing
Installation

To get started with this project, simply clone the repository:

git clone

Open the index.html file in your preferred web browser.

Usage

Ensure that your HTML file contains a div element with a specific id (e.g.,
Content here
).
Open the JavaScript file and ensure that the script is linked correctly in your HTML.
Run the JavaScript code to see the changes applied to the div element.
Code Explanation

The following JavaScript code retrieves a target div element and applies various style modifications: // Retrieve the target div element using getElementById const targetDiv = document.getElementById("myDiv");

// Change the background color of the fetched div element to yellow targetDiv.style.backgroundColor = "yellow";

// Add a margin of 20 pixels to the element targetDiv.style.margin = "20px";

// Apply a padding of 10 pixels targetDiv.style.padding = "10px";

// Change the font size to 18 pixels targetDiv.style.fontSize = "18px";

// Set the font weight to bold targetDiv.style.fontWeight = "bold";

// Change the height of the element to 200 pixels targetDiv.style.height = "200px";

// Modify the width of the element to 300 pixels targetDiv.style.width = "300px";

Breakdown of Style Changes

Retrieve Element: document.getElementById("myDiv") fetches the element with the specified ID and stores it in the variable targetDiv.

Background Color: Changes the background color to yellow.

Margin: Adds a margin of 20 pixels around the element.

Padding: Applies a padding of 10 pixels inside the element.

Font Size: Sets the font size to 18 pixels for text within the element.

Font Weight: Changes the font weight to bold, enhancing text visibility.

Height: Sets the height of the element to 200 pixels.

Width: Adjusts the width of the element to 300 pixels.

Contributing

If you wish to contribute to this project, please fork the repository and submit a pull request. Make sure to follow the code style and maintain consistent formatting.
