# Lab 6 - Web Components and localStorage API

This lab demonstrates the use of custom web components, shadow DOM, and localStorage to create recipe cards.

## Team Members
- [Your Name]
- [Your Partner's Name]

## Features Implemented

### Part 1 - Expose
- Created a custom `RecipeCard` web component with shadow DOM
- Implemented template-based rendering for recipe cards
- Added functionality to load recipes from localStorage 
- Displayed recipe cards on the page

### Part 2 - Explore  
- Implemented form functionality to add new recipes
- Added localStorage integration to save and retrieve recipes
- Added "Clear Local Storage" button functionality
- Made the form visible for user interaction

## Instructions to Run

1. Clone this repository
2. Open `index.html` using Live Server in VS Code
3. Open the Developer Console and set up initial recipes by running:
   ```javascript
   localStorage.setItem('recipes', JSON.stringify([
     // Paste content from reference/recipes.json here
   ]));
   ```
4. Refresh the page to see the recipe cards loaded
5. Use the form to add new recipes or clear localStorage

## Published Site URL
[GitHub Pages URL]
