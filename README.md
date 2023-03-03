# Recipe Search
## Objective

This module is used to search the recipe of what you want to cook, you can search by using ingredient names or by using country names.

## Dependencies

•	Mendix Version 9.7.1

•	API Key – To create API key navigate to https://api-ninjas.com/api/recipe Firstly you need to signup then once you Login, search for the “Recipe API” and click on the “Get a Free API Key” button, then copy the same.


 ![image](https://user-images.githubusercontent.com/126890368/222751104-721782b1-1c5a-40da-adc2-3f47a406bf81.png)


## Configuration

•	Import the module Recipe Search from the Mendix Marketplace.

•	Paste your API-Key as the default value of the constant which is named as “API_Key” inside Resources the folder.

•	Add the “Recipe_Overview” page in your navigation.

•	Run the application, Navigate to Recipe Overview page and search a recipe you want.

•	Now as a result you will get the list of Recipe’s with its ingredients, servings and instruction to cook.




## Resources

•	A sub Microflow namely “Sub_GetRecipesList” which is used to call the REST service to Fetch the Recipe.

 ![image](https://user-images.githubusercontent.com/126890368/222751199-1164e60f-3bb0-40e4-99d3-00a1fd25188b.png)


•	A page on the name of “Error_Page” which is used to show the user when there is no recipe found on their search.

![image](https://user-images.githubusercontent.com/126890368/222751253-eb4cdb97-2c35-4769-8361-3b62d65dbeeb.png)

 
•	A Page named as “Recipe_Overview” is the one we used to search the ingredients.

![image](https://user-images.githubusercontent.com/126890368/222751355-76d2ecee-05d2-43e1-87b0-2ceef04f169c.png)

 

## Response

When you search for any Recipe, you will get the response like the below images…
 
![image](https://user-images.githubusercontent.com/126890368/222751403-0904df3e-be1f-4bce-9cbc-9f487b96f960.png)

![image](https://user-images.githubusercontent.com/126890368/222751433-bd573f4f-4b55-42da-9d2d-786e9f8713d9.png)


 

