# Forkify

Forkify is a web application that allows users to search for recipes, bookmark their favorite ones, and even add their own recipes. It utilizes the **Forkify API**, **Form Data API**, and **History API** to deliver a seamless user experience.

## Features
- Search for recipes such as pizza, pasta, dosa, and more.
- View detailed recipe ingredients and adjust servings to modify ingredient quantities dynamically.
- Bookmark recipes to save them for later viewing.
- Add new recipes using a specific format.
- Click the **Directions** button to visit a webpage with detailed cooking instructions.

## Technologies Used
- **Forkify API**: Fetches recipe data.
- **Form Data API**: Allows users to add their own recipes.
- **History API**: Manages navigation history within the app.

## How to Use
### Searching for Recipes
1. Use the search bar to look for a recipe (e.g., "Pizza").
2. Click on a recipe to view its details, including ingredients and servings.

### Adjusting Servings
- Modify the servings count, and the ingredient quantities will automatically update.

### Bookmarking Recipes
1. Click the **Bookmark** icon to save a recipe.
2. Access all bookmarked recipes via the **Bookmark** section.

### Adding a New Recipe
1. Click the **New Recipe** button.
2. Enter recipe details, ensuring ingredients follow the format:
   ```
   quantity, unit, ingredient name
   ```
   Example:
   ```
   1, tbsp, olive oil
   2, cups, flour
   ```
3. Submit the form to add your custom recipe.

## Project Structure
- **Search Bar**: Allows users to find recipes.
- **Recipe Display**: Shows selected recipe details, including ingredients.
- **Bookmark Section**: Stores user-saved recipes.
- **New Recipe Form**: Enables users to submit custom recipes.
- **Directions Button**: Redirects users to an external page with step-by-step instructions.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/forkify.git
   ```
2. Navigate to the project folder:
   ```sh
   cd forkify
   ```
3. Open `index.html` in your browser to run the application.

## Contributing
Feel free to contribute by submitting issues or feature requests. Fork the repository and submit a pull request with your improvements.

## License
This project is licensed under the MIT License.
