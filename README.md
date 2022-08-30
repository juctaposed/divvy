# Divvy
An interface for individuals to share, or "divvy" their stories with one another

**Link to Project:** https://divvy-your-stories.herokuapp.com/

![divvy](https://user-images.githubusercontent.com/99512305/187522673-fb7c4d99-87b6-4d8b-8ed4-68b3ea6a850d.JPG)


# How It's Made
**Tech used:** HTML, Materialize CSS, JavaScript, Handlebars, Passport.js, Express.js, Sessions, Mongoose, MongoDB

By following an **MVC Framework**, I was able to:

Organize the app to use Google OAuth2.0 for user authentication to login and access user stories. 

Apply User schemas via Mongoose to talk to the database and structure relevant data made with requests such as user ID, first/last name, and profile picture.

Use handlebars to structure the view templates of adding, editing, and showing stories as well as the login page and dashboard interface.

Route HTTP handlers to their appropriate controller, i.e. /google for Authenticating with Google, and a redirect to landing if Authentication fails.

# Optimizations
Even though I am not a designer, I would like to add more design to this site when I have the opportunity. I'm extremely happy with the functionality, but theres still 
something to be desired in terms of UX. I also would perhaps use Bulma instead of Materialize CSS, as it may have provided more flexibility as I try to scale this website.

# Lessons Learned
One of the most vital things I learned from this project was using Google Authentication/Passport.js - it was awesome to see and compare the different ways to authenticate
users and all the different datapoints you can use to structure user schemas in a very unopinionated way. In that regard, it was also great practice creating user schemas
for Mongoose.
