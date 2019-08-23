# HEALTHY FOOD - Cookbook - Code Institute Milestone Project 3
Built by **_Cecilia Barriga_**

In this project, I build a full-stack site that allows users to manage a common dataset about a particular domain.
In this case, I created a web application that allows users to store and easily access cooking recipes with different fields ingredients, preparation steps, cooking time, preparation time, type of meal. 
The backend code and frontend form(s) allows users to add new recipes to the site, edit them and delete them.
User can also find recipes based on the type of meal: vegan, vegetarian, diary free desserts.


## UX
This application is intended for use by all, but mainly people that enjoy healthy food. 


## WireFrames
Below are the wireframes for the project.

Index:
![Index](https://user-images.githubusercontent.com/42648801/63551020-4bab4e80-c534-11e9-956f-4ab752959eae.png)

For the 3 meals (vegan, vegetarian & dessert) I made the same wireframe:
![meal](https://user-images.githubusercontent.com/42648801/63551091-78f7fc80-c534-11e9-8853-2f7cb90215d0.png)

Login and register are also the same:
![login](https://user-images.githubusercontent.com/42648801/63551112-857c5500-c534-11e9-8d46-f9e7589e83c3.png)

My Recipes:
![My Recipe](https://user-images.githubusercontent.com/42648801/63551130-9200ad80-c534-11e9-9111-146c27ba3db6.png)

Recipe:
![recipe](https://user-images.githubusercontent.com/42648801/63551149-9fb63300-c534-11e9-8cd2-c5d571d62531.png)

For add and edit recipe are also the same, with difference of the buttons:
![add recipe](https://user-images.githubusercontent.com/42648801/63551160-a8a70480-c534-11e9-9762-23b7b49c514c.png)


## Layout
The layout used the Materialize CSS template which I modified to suit my own requirements.


## Features
The following section describes the front-end features in this project.

- Navbar - Consists of the Healthy Foods logo which returns the user to the "Home" page of the application. There is also links to the "Vegan", "Vegetarian", "Dessert", "Add Recipe" "Login", "Register", "My recipes" and "Logout". The navbar will appear on all pages.
- Home - The home page consists on welcoming the user to the page and explaining they can also add their own recipes.
- Vegan, Vegetarian & Diary Free Dessert - They feature each the filtered meal depending on its category.
- My Recipes - The user can see all the recipes that he/her has uploaded. Here also user can add a recipe.
- Add Recipe - User can select category, and write the dish name, dish description, image url, preparation ingredients, preparation steps, cooking time, preparation time and author.
- Edit recipe: User can edit the recipe previously added.
- Login: User can login with his/her credentials
- Register: User can register in order to add recipes.
- Delete: User can delete recipe.
- Logout: logs our the user and redirect him to index page.
- Social Links - Provides users with links to the website social media pages (Links direct to social media pages for this project as this is not a real business and there are no"Healthy food" accounts).


## Technologies Used
- Cloud 9 IDE : This project used Cloud 9, an online integrated development environment, to construct the code end to end.
- Bootstrap: This project used Bootstrap, a library of website themes. The Materialize CSS template, was used for this project.
- Flask: This project uses Flask, a Python micro-framework. It is classified as a microframework because it does not require particular tools or libraries.
- MongoDB: This project uses mongoDB, a free and open-source cross-platform document-oriented database program. Classified as a NoSQL database program, MongoDB uses JSON-like documents with schemata.
- Jinga: This project uses Jinja, a template engine for Python, jinja code is included within the curly brackets.
- Python: This project uses Python, an interpreted high-level programming language for general-purpose programming and used to write the logic of this game, which is included within .py files.
- HTML: This project uses HTML, the standard mark-up language used to build website layout, which is included within the .html files.
- CSS: This project uses CSS, a style sheet language, used to add styling to a website. The custom.css file was added to this project, to add additional styling on top of the Bootstrap template.
- JavaScript: This project uses JavaScript, an object-oriented programming language used to create interactive effects within web browsers. JavaScript within this project was included with the Bootstrap template.
- Chrome Dev Tools: This project uses Chrome Dev Tools, a set of web developer tools, to continuously test and inspect that the web pages are rendering as intended within the browser.
- GitHub: This project uses GitHub, a web hosting service, for version control and final project backup.
- Heroku: This project uses Heroku, a web hosting service that supports Python applications, for final project deployment.
- Font Awesome: This project uses Font Awesome, vector icons and social logos on the website.
- Materialize CSS: Created and designed by Google, Material Design is a design language that combines the classic principles of successful design along with innovation and technology. Google's goal is to develop a system of design that allows for a unified user experience across all their products on any platform

## Testing
- Manual Testing: I retrieve a lot of issues while texting.

**Add Recipe Page:**
Go to the "Add Recipe" page.
Try to submit the empty form and verify that the recipe will not submit without a DISH NAME.
Try to submit the form without description and verify that the recipe will not submit without a DISH DESCRIPTION.
Try to submit the form without Vegan selected and verify that an error message appears.

**Recipe page:**
Try to edit and Delete a recipe

Once logged in, go to the My Recipes page and verify that is displaying the users recipes.

In every meal page, make sure that the page is filtering correctly.


- Responsive Testing

The app was tested on different devices and also using the Google Chrome inspect feature to test for repsonsiveness and any errors that occurred. 


## Deployment
The following section describes the process to deploy this project to Heroku.

- Ensure all required technologies are installed locally, as per the requirements.txt file.
- Via Terminal, login to Heroku, using 'heroku login' command. 
- Push project to Heroku, using 'push -u heroku master' command.
- Create scale, using 'heroku ps:scale web=1' command.
- Login to Heroku and select newly created app.
- Select settings. Select ‘Reveal Config'. Add IP 0.0.0.0 and PORT 5000.
- From 'More' menu on the top right, select 'Restart all dynos'.

You can see it here: [https://cook-book-ces.herokuapp.com/](url)


## Credits
I found several issues and I struggle with a few things:
- I had to remove :rsv in the MONGO_URI as Heroku was failing
- I had to constantly make sure that the data that I was passing in app.py and the data name in the template and in mongodb were consistent 


## Acknowledegments
- Content: The recipes came from the Cookie and Kate website.
- Media: The photos used in this site were obtained from Cookie and Kate website, and also from google.
- Acknowledgements: Big thank you to the tutors Xavier and Haley for all your help and patience, as I have many things breaking and you were extra patiente with me.

