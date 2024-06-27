
 
1. Filtering Recipes
•	Filter by Ingredient:
o	Enter an ingredient name in the "Filter by Ingredient" textbox. The application will display recipes that contain the specified ingredient in their list of ingredients.
•	Filter by Food Group:
o	Choose a food group from the dropdown menu under "Filter by Food Group." This filters recipes to show only those belonging to the selected food group (e.g., Vegetables, Fruits, Meat, Dairy).
•	Filter by Maximum Calories:
o	Adjust the slider labeled "Maximum Calories" to set an upper limit for calorie content. Recipes with calories below or equal to the selected value will be displayed.
•	Applying Filters:
o	Click the "Filter Recipes" button to apply the specified filters. The recipes list (RecipesListBox) will update to show only those recipes that match the applied criteria.
2. Managing Recipes
•	Viewing Recipe Details:
o	Select a recipe from the list (RecipesListBox). Click on the "Show Recipe Details" button to view detailed information about the selected recipe, such as ingredients, food group, and calorie content.
•	Creating a New Recipe:
o	Click on the "Create Recipe" button to open a window where you can input details for a new recipe. After entering the recipe details, click "Save" to add the new recipe to the application. The recipes list will update to include the newly added recipe.
•	Scaling a Recipe:
o	Click on the "Scale Recipe" button to open a window where you can choose a scaling factor (0.5 for half, 2 for double, 3 for triple). Select the desired scaling option, and all ingredients of all recipes will adjust their quantities accordingly.
•	Deleting All Recipes:
o	Click on the "Delete All Recipes" button to prompt a confirmation dialog. If confirmed, all recipes will be deleted from the application, and the recipes list will be cleared.
3. Additional Features
•	Navigating Between Windows:
o	Use the various buttons ("Filter Recipes", "Create Recipe", "Show Recipe Details", "Scale Recipe", "Delete All Recipes") to navigate between different functionalities of the application. Each button triggers specific actions or opens new windows for interaction.
•	Managing Recipe Lists:
o	The main window (MainWindow.xaml) displays the list of recipes (RecipesListBox). Updates to this list, such as filtering, scaling, creating new recipes, or deleting recipes, are reflected in real-time upon interaction.

