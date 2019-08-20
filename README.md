*healthy Food - Cookbook - Code Institute Milestone Project 3*
In this project, I build a full-stack site that allows users to manage a common dataset about a particular domain.
In this case, I created a web application that allows users to store and easily access cooking recipes with different fields ingredients, preparation steps, cooking time, preparation time, type of meal. 
The backend code and frontend form(s) allows users to add new recipes to the site, edit them and delete them.
User can also find recipes based on the type of meal: vegan, vegetarian, diary free desserts.

**UX**
This application is intended for use by all, but mainly people that enjoy healthy food. 

**User Stories**

I like healthy food, but easy to make
As a stay at home dad with limited cooking skilled, I would love to find recipes that are simple and easy to cook for my family.
As a student away from home for the first time, I am looking for somewhere to get easy recipes.


**WireFrames**

Below are the wireframes for the project.
First Idea:


**Layout**
The layout used the Materialize CSS Parallax template which I modified to suit my own requirements.

**Features**
The following section describes the front-end features in this project.

Navbar - Consists of the Healthy Foods logo which returns the user to the "Home" page of the application. There is also links to the "Vegan", "Vegetarian", "Dessert", "Add Recipe" "Login". The navbar will appear on all pages.
Home - The home page consists of 4 sample recipes along with some information on contacting the webmaster and a link to the contact us page of the site.
Social Links - Provides users with links to the website social media pages and also shortcuts to the "All Recipes" & "My Recipes" pages.(Links NOT LIVE current social media pages for this project as this is not a real business).



**Technologies Used**
- Cloud 9 IDE : This project used Cloud 9, an online integrated development environment, to construct the code end to end.
- Bootstrap: This project used Bootstrap, a library of website themes. The Materialize CSS Parallax template, was used for this project.
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

**Testing**
- Manual Testing

Add Recipe Page:
Go to the "Add Recipe" page.
Try to submit the empty form and verify that the recipe will not submit without a RECIPE NAME.
Try to submit the form without description and verify that the recipe will not submit without a RECIPE DESCRIPTION.
Try to submit the form without Vegan selected and verify that an error message appears.

Eddit a Recipe
when editing a recipe a new recipe will create instead of modifying the existing file.

Login
Create a user and login


- Responsive Testing

The app was tested on different devices and also using the Google Chrome inspect feature to test for repsonsiveness and any errors that occurred. 


**Deployment**
The following section describes the process to deploy this project to Heroku.

Ensure all required technologies are installed locally, as per the requirements.txt file.
Via Terminal, login to Heroku, using 'heroku login' command. 
In Herok Heroku app, using 'heroku apps:create appname' command.
Push project to Heroku, using 'push -u heroku master' command.
Create scale, using 'heroku ps:scale web=1' command.
Login to Heroku and select newly created app.
Select settings. Select ‘Reveal Config'. Add IP 0.0.0.0 and PORT 5000.
From 'More' menu on the top right, select 'Restart all dynos'.
View app: In settings, select Domain URL, NOT Git URL to view your hosted application.

