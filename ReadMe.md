# PrepPal

## Project Description 
PrepPal is an ingredient-based recipe generator designed to help home-cooks use their ingredients effictively.
View the Demo here: https://www.youtube.com/watch?v=73dNgn_QokU 

## Technologies Used
- FrontEnd: HTML, CSS, JavaScript，Bootstrap
- Backend: Node.js, Express.js
- Database: MongoDB

## File Contents of Folder
   ```shell
│   │   LICENSE
│   │   package.json
│   │   README.md
│
├+---public
|       404.jpg
|       dino.jpg
|       dinomeat.jpg
|       logo.jpeg
|       step1.jpg
|       step2.jpg
|       step3.jpg
|       step4.png
|       
\---views
    |   404.ejs
    |   allFavourites.ejs
    |   DOB.ejs
    |   easter.ejs
    |   edit.ejs
    |   errorMessage.ejs
    |   favouriteRecipe.ejs
    |   forgotPassword.ejs
    |   home.ejs
    |   index.ejs
    |   kitchen.ejs
    |   login.ejs
    |   noIngredientInput.ejs
    |   personal.ejs
    |   recipe.ejs
    |   resetPassword.ejs
    |   search.ejs
    |   searchedRecipe.ejs
    |   settings.ejs
    |   shoppinglist.ejs
    |   signup.ejs
    |   step1.ejs
    |   step2.ejs
    |   step3.ejs
    |   step4.ejs
    |   welcome.ejs
    |   
    \---templates
            favRecipeInfo.ejs
            footer.ejs
            header.ejs
            ingredientCard.ejs
            recipeCard.ejs
            
```
            

## How to Install or Run the Project

### What you need to install

1. Install Visual Studio Code (VS Code): Download and install VS Code from the official website: [https://code.visualstudio.com/](https://code.visualstudio.com/).

2. Install Node.js: Download and install Node.js, which includes npm (Node Package Manager), from the official website: [https://nodejs.org/](https://nodejs.org/).

3. Create a fork of this repository

5. Open the project in VS Code: Launch VS Code and open the project folder.

6. Install project dependencies: In the VS Code terminal, navigate to the project directory and run the following command to install the required npm packages:
   ```shell
   npm install
7. Set up environment variables: Create a .env file in the project root directory. Add the necessary environment variables to the .env file. 

8. Set up the database: Install and set up MongoDB. Configure the MongoDB connection URL in the .env file.
  
9. You can now use terminal and use the following command to run the project on your localHost:
   ```shell
    nodemon .\index.js
    
10. Access the web app: Open a web browser. Enter the URL http://localhost:3000.

### 3rd party API(s)

This app uses the spoonacular API. You will need to make an account to obtain and api key.

## How to Use the Product (Features)

Our app is designed to help you generate recipes based on the ingredients you have. It offers the following features:

1. **Recipe Favoriting**: You can easily save your favorite recipes for quick access. Simply browse through the generated recipes and click the heart icon on ones you love as favorites for later reference.

2. **Recipe Search**: Our app allows you to search for specific recipes based on various criteria such as meal type, cuisine, dietary restrictions, or specific ingredients. This feature enables you to find the perfect recipe that suits your preferences and available ingredients.

3. **Ingredient Input**: When searching for recipes, you can input the ingredients you have on hand. Our app intelligently analyzes your inputs and generates a list of relevant recipes that can be created using those ingredients.

4. **Recipe Editing**: If you come across a recipe that you would like to customize or modify, our app provides an easy-to-use recipe editing feature. After favourting a recipe simply go to your favourite recipe collections where you can make changes to ingredients, quantities, cooking instructions, or add your personal touch to the recipe.

5. **Shopping List Creation**: To help you identify missing ingredients, our app offers a convenient shopping list creation feature. Simple press the create shopping list button on a recipe and it will generate a shopping list for you. Additionally, it will even mark you missing ingredients for you.

By utilizing these features, our app empowers you to discover new recipes, personalize them according to your preferences, and make the most of the ingredients you have available. Enjoy the journey of culinary exploration with our recipe generation app!


## Credits, References, and Licenses

### Credits
Contributors
- NAinZhou
- LucasHYing
- John2T
- VietNguyen10

### References 
-Node.js: Official website and documentation - https://nodejs.org

-Bootstrap: Official website and documentation - https://getbootstrap.com

-MongoDB: Official website and documentation - https://www.mongodb.com

-GitHub: Official website and documentation - https://github.com

-Studio3T: Official website and documentation - https://studio3t.com 

-Spoonacular API - https://spoonacular.com/food-api/docs

## Contact Information 
- NAinZhou (nainzhou@gmail.com)
- LucasHYing ( hying3@my.bcit.ca)
- John2T (johntu537@gmail.com)
- VietNguyen10 (vnguyen141@my.bcit.ca)
