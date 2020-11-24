## **Shelby El-rassi and Adrienne Smith T3A2**

### MERN Full Stack Application Assignment

|Shelby El-rassi|Adrienne Smith|
|:-------------:|:-------------:|
|[www.shelby-el-rassi.com](www.shelby-el-rassi.com)  |[]() |
|[github.com/Shelby219](www.shelby-el-rassi.com/)  |[github.com/aes89](https://github.com/aes89) |

---

##### Deployed App: 

##### Documentation Repository: https://github.com/CA-MERN/MERN-Part-A-Docs

##### Client Repository: https://github.com/CA-MERN/MERN-client

##### Server Repository: https://github.com/CA-MERN/MERN-server

---
### Purpose
<details>
<summary>Click to expand</summary>

The purpose of this application is for users to be able to enter ingredients which are always on their grocery list/fridge with the intent to search for recipes made up from those ingredients. The idea for this web application stemmed from the situation of the first Australiam lockdown of Covid19, in which stores sold out of a lot of popular and favourite grocery items of customers. An application such as this means users can input the ingredients they have currently at home and recipes including these ingredients will be displayed. Along side this factor is the need for users to stick to a grocery budget, so they do not want to be constantly going to the store to get expensive ingredients. Also the type of users using this app are ones that need recipe inspiration for their weekly meals, ones that search recipes based on dietary requirements and excluded ingredients, and also users that are new to the cooking scene and want to start with cooking by just utilising ingredients already at home. This app can help to minimise food waste by helping users to combine items they may not have made a meal with otherwise.

The overall goal of this application is a search application based on user ingredient lists, with the ability to save those recipes, like and review recipes. 

</details>

---
### Functionality / features
<details>
<summary>Click to expand</summary>

#### MVP Features
* User accounts
    * Signup
    * Login
    * Logout
    * Edit details
    * Delete account.
* User dashboard
    * Default Pantry Staples List which can also be add or deleted. (like salt, pepper, olive oil, vinegar)  
    * View grocery list by category.
    * Recipe interaction (saved, liked, reviewed).
* Main Application
    * Grocery input, add and delete. Implement predictive search.
    * Implement alternate ingredient middleware matching eg. Cilantro = coriander if API does not have in place. 
    * Recipe search button on main interface.
    * Return recipes in sorted categories (breakfast, lunch, dinner).
    * Filter feature used for diet filter, prep time . 
    * Save recipes to favourites.
    * Vote and review on best recipes.
</p>

#### Nice to Have Features
* Search History capture.
* User can add a photo of their cooked dish, public or private collection. 
* Oauth with signup and login. 
* Recipes of the week on the home page
* Saved recipes in recipe collections
* Filter recipe by dish type(eg soup)
* No ingredient recipe search (returns random recipe suggestions)
* Filter recipes by cuisine type
* Advanced diet preference eg low-carb

</details>

---
### Target audience
<details><summary>Click to expand</summary>

* Key Demographics
    - Gender: Anyone, but predominantly women.
    - Age: 20-55.
    - Family status: Cooking for self, partner or dependents.
    - Profession: Students, professionals and homemakers.
    - Language: English.
    - Main interests: cooking, health, diet, low waste, saving money, trying new things.

* Key Psychographics
    - Dislikes repetitive meals, like variety and new options.
    - Dislikes spending lots of money on lots of ingredients and food waste.
    - Enjoys sharing and preparing meals.

* Challenges
    - Finds it difficult to create recipes
    - Has a limited food budget or limited access to ingredients
    - Has an interest in cooking but limitations (eg budget, dietary restrictions, skill).

* Preferred Channels
     - Follows celebrity chefs and food themed accounts on social media.
     - Searches for recipes/blogs on Google.

* Preferred Content Types
    - Articles.
    - Blog posts.
    - Social media posts.

</details>

---
### Tech stack
<details><summary>Click to expand</summary>

**Design and Planning**
* Trello
* Figma
* xtensio
* Draw.io  
* Slack   

**Frontend**
* HTML5
* CSS3
* React JS
* JavaScript
* JSX
* Material-UI
* Bootstrap
* Axios

**Backend**
* ExpressJS
* Node JS

**Database**
* MongoDB
* Mongoose

**Testing**
* Cypress
* Supertest

**Other**
* Edamam API
* Heroku
* Netlify
</details>

---
### Dataflow Diagram
<details><summary>Click to expand</summary>
![Dataflow Diagram](DataflowDiagram.png)
</details>

---
### Application Architecture Diagram
<details><summary>Click to expand</summary>
![Application Architecture Diagram](app-arch-diagram.png)
</details>

---
### User Stories

<details><summary>Click to expand</summary>

#### Personas
![Sarah Persona](persons/sarah.png)
![Wayne Persona](persons/wayne.png)
![Liza Persona](persons/Eliza.png)
![Bez Persona](persons/bez2.png)

#### Version 1
##### Overall User
* As a overall user:
    * I can go to the home page signup to create an account
    * I can login
    * I can navigate to my account settings and edit my account details
    * I can navigate to the account settings and delete the account
    * I can navigate to my dash and see what recipes I have interacted with (vote, save, reviewed) so I can quickly access/reaccess them later.
    * Through the navigation bar I can see my current fridge items organised by category
    * Through the navigation bar I can and see my current pantry staples
    * I can navigate to main interface and see 'get searching today'!
    * Once an initial search is done, I want see 'refresh again'
    * From main interface  I can make a recipe search 
    * From main interface I can navigate to my grocery lists
    * From main interface I can navigate to my saved recipes
    * From main interface I can navigate to my diet preferences
    * I can add more groceries with predictive input
    * I can delete groceries from my list
    * I can clear all of my grocery list
    * I can see my recipes returned search with them categories in breakfast, lunch and dinner
    * I can further filter by diet (eg vegan) and prep time
    * I can see my recipes returned via list with image, name, time and rating.
    * I can see how many ingredients I have in the receipe eg. "You have 4/5 ingredients"
    * I can click go to recipe
    * I can click a like heart on the recipe
    * On a clicked recipe page I can click the save recipe button
    * On a clicked recipe page I can view the whole recipe
    * On a clicked recipe page I can rate the recipe

##### Sarah 
* As a mother and busy worker…
    * I would like to have a tool where I can utilise my current groceries to the fullest.
    * I would like to find some recipe variety for my family.
    * I would like to be able to filter via prep time in case I want a quick and easy recipe.
    * I would like a tool that is simple and easy to use.
    * I would like to see my saved recipes so I can use them another time if I like them.
    * I would like to filter via gluten free due to my child’s allergies.
    * I would like to see the nutrient values in the recipes as I am health conscious.

##### Wayne 
* As a full-time worker and novice chef...
    * I would like to view times on recipes when deciding what to try.
    * I can see other user's reviews on recipes to decide if I will try it.
    * I would like a simple interface without confusing options.
    * I would like to limit the amount of ingredients in recipes I search.
    
##### Eliza 
* As a student and vegetarian…
    * I would like to have a tool to find recipe inspiration with my favourite ingredients.
    * I would also like a tool to find dishes with alternatives to my favourite ingredients.
    * I would like to be able to filter recipes based on my dietary needs as a vegetarian.
  
##### Bez 
* As a chef with an egg surplus, an interest in learning different ways to cook them and some extra time for cooking...
    * I would like to search for a recipe by dish type (eg soup) and ingredients.
    * I would like to search for recipes without an ingredient, for when I am sick of eggs.
    * I would like to search recipes by cuisine type (eg Spanish) so I can choose matching music.

#### Version 2


</details>

---
### Wireframes

#### Version 1

<details><summary>Click to expand</summary>

#### Mobile
![Mobile Wireframe 1](screenshots/Mobile1.png)
#### Tablet
![Tablet Wireframe 1](screenshots/Tablet1.png)
#### Desktop
![Desktop Wireframe 1](screenshots/Desktop1.png)

</details>

---
### Project Management
#### Trello Screenshots

<details><summary>Click to expand</summary>

![Trello Screen Shot 1](screenshots/trello1.png)
![Trello Screen Shot 2](screenshots/trello2.png)
![Trello Screen Shot 3](screenshots/trello3.png)
</details>