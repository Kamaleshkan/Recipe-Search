# Recipe Search
## Objective

This module is used to search for the recipe for what you want to cook. You can search by using ingredient names or by using country names.

## Dependencies

•	Mendix Version 9.7.1

•	API Key: To create an API key, navigate to https://api-ninjas.com/api/recipe. Firstly, you need to sign up, then once you log in, search for the "Recipe API" and click on the "Get a Free API Key" button, then copy the same.


 ![image](https://user-images.githubusercontent.com/126890368/222751104-721782b1-1c5a-40da-adc2-3f47a406bf81.png)


## Configuration
•	Import the module "Recipe Search" from the Mendix Marketplace.

•	Paste your API-Key as the default value of the constant, which is named "API_Key," inside the Resources folder.

•	Add the "Recipe_Overview" page to your navigation.

•	Start the app, go to the Recipe Overview page, and search for a recipe.

•	Now, as a result, you will get a list of recipes with their ingredients, servings, and instructions on how to cook them.




## Resources

•		A sub-flow, namely "Sub_GetRecipesList," is used to call the REST service to fetch the recipe.

 ![image](https://user-images.githubusercontent.com/126890368/222751199-1164e60f-3bb0-40e4-99d3-00a1fd25188b.png)


•	A page with the name "Error_Page" is used to show the user when there is no recipe found on their search

![image](https://user-images.githubusercontent.com/126890368/222751253-eb4cdb97-2c35-4769-8361-3b62d65dbeeb.png)

 
•	A page named "Recipe_Overview" is the one we used to search the ingredients.
![image](https://user-images.githubusercontent.com/126890368/222751355-76d2ecee-05d2-43e1-87b0-2ceef04f169c.png)

 

## Response

When you search for any recipe, you will get a response like the below images:
 
![image](https://user-images.githubusercontent.com/126890368/222751403-0904df3e-be1f-4bce-9cbc-9f487b96f960.png)




 

