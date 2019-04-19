# studybuddy

So much to learn, so little time. Sometimes studying is a little easier and more enjoyable with a buddy. Find your study buddy with the Study Buddy app.
Study Buddy is an app created to help people interested in various study topics to connect with others interested in the same topics. Users can find those who want to study on the same terms as themselves, as well as can create a favorites page to keep track of their favorite study buddies. 

## How to Use:
When the user loads the Study Buddy app, they must either log in or create an account. Creating an account requires the user to provide their First Name, Last Name, Username, Password, Email, Location, and a user Photo. The site will not allow the user to search for buddies until logged in. The users individual user information is then stored in a User table in MySQL using Sequelize. 

The user is then prompted to take a survey which captures the users desired Topic, Sub-Topic, if they want to meet Remote or In Person, preferred Meeting Time of day, and then they are presented with the days of the week to individually select which days work best for them. The users survey information is then stored in a Survey table in MySQL. 

Once the user has completed their survey, they will be presented with study buddy matches which are generated by running an algorithm that compares the current users survey results to the results of other users, and then shows those that most closely match the current users results on the Matches page. 

The user has the option to go back via the nav bar and re-take the survey should they want to study a different Topic/Sub-Topic. In order to keep track of past studies buddies, the user has the option to favorite matches. They do this by clicking on the star icon on other users card(s). The favorites information is then stored in a third table called Favorites in MySQL via Sequelize.
The Matches and Favorites pages are both generated based off of the backend tables in MySQL. The user card information is generated by pulling from the MySQL tables. 

The user has the ability to log out, as well as to view an About page with further Study Buddy App details. 

## Components Used:
* JavaScript
* CSS
* Bootstrap
* Node
* Express
* MySQL
* Sequelize ORM
* GET and POST routes
* Heroku
* MVC file structure
* Handlebars
* Passport.js with Bcrypt
* Cloudinary SaaS
* GitHub
* Visual Studio Code
* MySQL Workbench

## Authors:
* Michael Albaneze
* Aprille Perez
* Will Wilkens
* Claire Gibeau

## Feedback:
This was our groups first time working with many of the components used. We had a learning curve on many of the technologies in making Study Buddy, and working as a group was both helpful (people to talk to when you have questions!) and sometimes not as helpful (merge conflicts on GitHub, we’re looking at you!). Three particularly challenging potions of the project included using Sequlize, Passport, and Cloudinary. Each presented unique challenges. 

Sequlize was a brand new tool for each of us, so integrating it was very thought-provoking as we didn’t have much context or experience. We were tempted to stick with what we knew going into the project (MySQL) but pushed ourselves to use Sequlize. We learned a lot, but a few more days of experience would have been helpful in using this tool. 
Passport.js was a great for user authentication. Integrating it into the project was interesting as we hadn’t ever used it before, so we were leaning on our experience from other .js library integrations and the documentation to make it work. User authentication is working, so that’s a win!

Cloudinary is a SaaS component that was used for capturing user images. It stopped working at one point so we spent a lot of time reviewing the code to see what was wrong, only to learn that it was an issue with our Cloudinary account vs. and issue with our code. This too is working; win/win!

Our team did a great job planning this project and understanding what the MVP was. We challenged ourselves to use new tools and supported each other through the learning process resulting in an app we are all proud of; Study Buddy. 


## GitHub Link:
https://github.com/aprilleperez/studybuddy

## Heroku Link: 
https://your-study-buddy.herokuapp.com/

