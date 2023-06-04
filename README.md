# prog6221part2 

Recipe App
This is a recipe management application that allows users to create, store, and manage recipes. The application has been enhanced with the following improvements:
	Generic Collections: The application now uses generic collections (List) instead of arrays to store recipes, ingredients, and steps. This provides more flexibility and simplifies the management of data.
	Delegate for Calorie Notifications: A delegate has been added to notify the user when a recipe exceeds 300 calories. This allows for custom handling of calorie-related events and provides a way to inform the user about potentially unhealthy recipes.
	Improved User Interface: The user interface has been enhanced with clear menu options and prompts to guide the user through the recipe management process. This makes the application more intuitive and user-friendly.
	Exception Handling: The code now includes exception handling to validate user input. It ensures that valid values are entered for numeric inputs and non-empty values are entered for string inputs.
	Readme File: A comprehensive readme file has been included to provide instructions on running the application, explaining its features and functionalities.


Usage

Add Recipe: Select the option to add a new recipe. Enter the name of the recipe and provide details such as ingredients, quantities, units, calories, and food groups. The application will validate the input and add the recipe to the collection.
Display Recipes: Choose the option to display all the recipes. The recipes will be listed in alphabetical order by name.
View Recipe: Select this option to view the details of a specific recipe. Enter the name of the recipe, and the application will display the ingredients and steps.
Clear Recipe: Choose the option to clear the recipe collection. The application will prompt for confirmation, and if confirmed, all the recipes will be removed.
Exit: Select the exit option to terminate the application.

Getting Started

To run the application, follow these steps:
	Clone the repository or download the source code.
	Open the solution in an IDE or editor that supports C#.
	Compile the project to build the executable.
	Execute the generated executable file.
The application will present a menu of options. Enter the corresponding number to perform the desired action.
Follow the prompts to add recipes, view recipes, view a specific recipe, clear recipes, or exit the application.
Note: The Recipe App now uses generic collections (List) instead of arrays to store recipes, ingredients, and steps. It also incorporates a delegate to notify the user when a recipe's total calories exceed 300. Additionally, a unit test has been implemented to test the calculation of total calories.

Enjoy using the Recipe App to manage and explore your favorite recipes!

A brief description of what you changed based on your lecturer’s feedback.

The code has been organized into separate files, with each class in its own file:
	Ingredient.cs: Contains the Ingredient class definition, which represents an ingredient in a recipe.
	Recipe.cs: Contains the Recipe class definition, which represents a recipe. It includes properties for the recipe name, a list of ingredients, and a list of steps. The class provides methods to add ingredients and steps, display the recipe, and calculate the total calories.
	RecipeManager.cs: Contains the RecipeManager class definition, which manages the collection of recipes. It includes methods to add a recipe, display all recipes, retrieve a specific recipe, and clear all recipes. The class also defines an event to notify when a recipe's total calories exceed 300.
	Program.cs: Contains the Main method and the application's entry point. It provides the user interface for interacting with the Recipe App, such as adding recipes, displaying recipes, viewing a specific recipe, and clearing recipes.
The separation of classes into different files improves code organization and maintainability, making it easier to navigate and modify specific classes without affecting others. Each class has its own file, making it easier to locate and work with specific class definitions.

To run the Recipe App, simply compile and execute the Program.cs file. The application will present a menu of options that you can choose by entering the corresponding number. Follow the prompts to add recipes, view recipes, and perform other actions.
	Exception Handling: The code now includes exception handling to validate user input. It ensures that valid values are entered for numeric inputs and non-empty values are entered for string inputs.

The display of recipes has been enhanced to provide a more readable format. The following improvements have been made:


	The recipe name is displayed with a header to clearly identify the recipe.
	The ingredients are listed in a formatted manner, displaying the quantity, unit, and name of each ingredient.
	The steps are numbered and displayed in a clear and organized manner.
These improvements enhance the user experience by presenting the recipe information in a more readable and structured format.



