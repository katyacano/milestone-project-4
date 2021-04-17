# ** Rover Camp Ecommerce App **

#### View Github Pages site [here](https://katyacano.github.io/milestone-project-3/)
#### View Heroku deployed app [here](https://kc-milestone-3-project.herokuapp.com/)  
<br/>
<br/>

# User Stories (UX)


## Shopper Goals
| User Story No.  |  As A/An  |  A User Should Be Able To  |  So That They Can  |
| :-------------: | --------- | -------------------------- | ------------------ |
|        1        | Shopper   | Sort the list of products and services available for purchase | Easily identify them by rating, price and category |
|        2        | Shopper   | Sort a specific category of product | Find the type of item they need to purchase, whether it be for day care, training services or accessories|
|        3        | Shopper   | Sort multiple categories of products and services on the same page | Find the type of item they need to purchase, whether it be for day care, training services or accessories|
|        4        | Shopper   | Easily see search results and number of results | Quickly determine if the store offers the product or service they need |
|        5        | Shopper   | View list of products    | Select some to purchase|
|        6        | Shopper   | View individual product details | Identify the price, description, product rating, product image (if applicable), and sizes (if applicable) | 
|        7        | Shopper   | Easily view the total amount of intended purhase  | Know how much they will be spending |
|        8        | Shopper   | Be able to easily select the product or service they need, including (if applicable) the size and quantity| Make sure they purchase the right products and services|
|        9        | Shopper   | View items ready for purchase in cart | Understand the total cost of their purchase and ensure they have the right items in cart|
|        10       | Shopper   | Adjust the quantity of items within the cart  | Easily make changes to their intended purchase if needed |
|        11       | Shopper   | Easily enter payment information | Complete the purchase|
|        12       | Shopper   | Have confidence in the security of my personal information | Feel that my purchase is safe and that I can return to this site for future purchases|
|        13       | Shopper   | View and order confirmation at the end of the transaction and receive a confirmation email | Know that the purchase is complete and be able to keep a record of it |

<br/>

## Site User Goals
| User Story No.  |  As A/An  |  A User Should Be Able To  |  So That They Can  |
| :-------------: | --------- | -------------------------- | ------------------ |
|        1        | Shopper   |   View list of products    | Select some to purchase|
|        2        | Shopper   | View individual product details | Identify the price, description, product rating, product image (if applicable), and sizes (if applicable) | 

 <br/>

 ## Site Owner Goals
| User Story No.  |  As A/An  |  A User Should Be Able To  |  So That They Can  |
| :-------------: | --------- | -------------------------- | ------------------ |
|        1        | Shopper   |   View list of products    | Select some to purchase|
|        2        | Shopper   | View individual product details | Identify the price, description, product rating, product image (if applicable), and sizes (if applicable) | 

 <br/>

# Design

  ### Color Scheme
  - The main colors used will be black, gray, white, and a yellow variant (specifically, ##F7DC6F).
  ### Typography
  - The font for the logo is Boogaloo from Google Fonts 
  - The font family used for this site will be Roboto throughout the site, with San Serif as the fallback font if such font family is not being imported. 
  ### Imagery 
  - Imagery is limited on this app to the Home page. Images used here are on a slider, located above the library of dining spots that users can search through. 

<br/>
<br/>

# Wireframe
- View complete wireframe [here](https://github.com/katyacano/milestone-project-3/blob/master/wireframe/foodscapela-wireframe.pdf)

<br/>
<br/>

# Features

- Responsive on all device sizes
- Interactive elements: 
    - Search bar
    - Dining spots library
    - Register form
    - Log in/ log out actions
    - Log a new spot form
    - Edit and delete spot actions

<br/>
<br/>

# Technologies Used

## Languages Used
- [HTML5](https://en.wikipedia.org/wiki/HTML5)
- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
- [Javascript]( https://www.javascript.com/) 
- [Python](https://www.python.org/)
- [Django](https://www.djangoproject.com/)

<br/>

## Frameworks, Libraries & Programs Used

[Materialize 1.0.0:](https://materializecss.com/)
   - Materialize was used to assist with the responsiveness and styling of the app.

[Google Fonts:](https://fonts.google.com/)
   - Google fonts were used to import the Roboto font family into the style.css file which is used on all pages throughout the project.

[Font Awesome:](https://fontawesome.com/start)
   - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.

[jQuery:](https://jquery.com/)
   - jQuery came with Bootstrap to make the navbar responsive but was also used for the smooth scroll function in JavaScript.

[Git:](https://git-scm.com/)
   - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.

[GitHub:](https://github.com/)
   - GitHub is used to store the projects code after being pushed from Git.

[Balsamiq:](https://balsamiq.com/)
   - Balsamiq was used to create the wireframes during the design process.

[PicResize:](https://picresize.com/)
   - PicResize was used to resize the Home page image.

[Postgres:](https://www.postgresql.org/)
   - Postgres was used for the app database and to store collected data.

[Heroku:](https://www.heroku.com/)
   - Heroku was used to deploy the application.

[Amazon Web Services:](https://aws.amazon.com//)
   - Amazon Web Services was used to store static and media files.

<br/>


# Database and Database Schema
Postgres is the database used for storing user’s details and food spot review information. 
There are three collections in the database- users, categories and spots. The schema is as follows:
<td><img src="static/images/db_schema.jpg" alt="Database Schema Visual" style="width: 800px;"/></td>

<br/>
<br/>

# Defensive Design (Security Features)
- Werkzeug was used for password security. SPecifically: generate_password_hash and check_password_hash
- Users are not able to edit or delete other user's entries into the directory.
- Site prevents visitors from adding a new spot without logging in by checking if user is in session. Redirects to log in page if no user in session.


<br/>
<br/>

# Testing

## Manual Testing

### **Test-** Clicking FoodscapeLA logo should return user to home page
- Result: Tested logo on all pages and action works as intended. No errors.

### **Test-** Clicking on navbar links should direct user to corresponding pages
- Result: Tested all links, before and after logging in. Links work as intended. No errors.

### **Test-** Entering required info on Register page and clicking on Register button should create a new user in database.
- Result: Entered data for user 'joegagner'. Action completed as intended. No errors.

### **Test-** Entering valid user info on Log In page and clicking on Log In button should allow user access to app and direct user to Profile page.
- Result: Tested by entering info for all three current users. Action worked as intended. No errors. 

### **Test-** Entering invalid user info on  Log In page and clicking on Log In button should not grant access to app and flash an error message.
- Result: Tested with three different user entries. Action works as intended. No errors. 

### **Test-** Entering required information on Log A New Spot page should result in a new spot being added to database.
- Result: Tested all entry fields. Action works as intended. No errors. 

### **Test-** Missing any information on Log A New Spot page should result in error messages for each line that is missing or has insufficient characters.
- Result: Tested by entering various combinations of information/misinformation. Action works as intended. No errors.

### **Test-** Edit/Delete buttons should only be visible to user if Spot has been entered by the user. 
- Result: Tested with different users. Action works as intended. Users are not able to edit or delete Spots that they have not personally entered into the database. No errors.

### **Test-** Search function should look for keyword matches in Type of Cuisine, Location Name, and Description. 
- Result: Tested with various keywords from all fields. Action works as intended. When keyword was found in any of these three fields Search function returned a match. When keyword was found in other fields (ie. Address), no result was found and No Result message falshed. 

### **Test-** Clicking Reset button should reload all Dining Spots on Home Page.
- Result: Tested by doing a search and then clicking Reset button. Action works as intended. No errors.  
  
<br/>
<br/>

# Code Validation

## app.py 
- Code: Python3
- Validator: (http://pep8online.com/)
- **Outcome:** First test failed with 3 errors all pertaining to whitespace. Second test passed with zero errors.

## style.css
- Code: css
- Validator: (https://jigsaw.w3.org/css-validator/)
-**Outcome:** First test passed with zero errors.

## base.html 
- Code: HTML5
- Validator: (https://validator.w3.org/)
- **Outcome:** First test failed with 25 errors due to Jinja code elemnets. No action taken to correct because this is how module was structured.

## add_spot.html 
- Code: HTML5
- Validator: (https://validator.w3.org/)
- **Outcome:** First test failed with 6 errors due to Jinja code elemnets. No action taken to correct because this is how module was structured.

## edit_spot.html
- Code: HTML5
- Validator: (https://validator.w3.org/)
- **Outcome:** First test failed with 10 errors. Some due to Jinja code elemnets. Second test failed with 6 errors. No further action taken to correct because this is how module was structured.

## login.html
- Code: HTML5
- Validator: (https://validator.w3.org/)
- **Outcome:** First test failed with 5 errors due to Jinja code elemnets. No action taken to correct because this is how module was structured.

## profile.html
- Code: HTML5
- Validator: (https://validator.w3.org/)
- **Outcome:** First test failed with 3 errors due to Jinja code elemnets. No action taken to correct because this is how module was structured.

## register.html
- Code: HTML5
- Validator: (https://validator.w3.org/)
- **Outcome:** First test failed with 5 errors due to Jinja code elemnets. No action taken to correct because this is how module was structured.

## spots.html
- Code: HTML5
- Validator: (https://validator.w3.org/)
- **Outcome:** First test failed with 17 errors due to Jinja code elemnets. No action taken to correct because this is how module was structured.

<br/>
<br/>

## Testing First Time Visitor Goals (UX)  

### 1. A first time visitor should be able to clearly understand that FoodscapeLA is an app for people who love to dine out in Los Angeles, and want to come together online to exchange first-hand accounts of their dining experiences, while simultaneously creating a library of great dining spots that others using the app can go out and try. 
- **Outcome:** The Home Page slider and intro paragraph clearly define the app's purpose and functionality.
### 2. A first time visitor should be able to easily navigate throughout the site in a simple and intuitive way. 
- **Outcome:** The navigation bar at the top is simple and provides user with clarity as to what functions user can implement. Navigation bar options change while user is logged in, yet functionality is still clear.
### 3. A first time visitor should be able to quickly find a collection of great dining spots in the city.
- **Outcome:** The Home page prmonently shows the local dining spots the user can review and search through. 
### 4. A first time visitor should be able to search for a dining suggestions based on other user’s experiences. 
- **Outcome:** A search bar is prominently displayed on the Home Page above the Spot directory list. 
### 5. A first time visitor should easily be able to join the community of app users if they would like to contribute to the dining spots library.
- **Outcome:** A Register option is available on the navigation bar for first time visitors to register and begin using app.
### 6. A first-time user should be able to contribute to the library upon registering as a user.
- **Outcome:** A Log A New Spot option is available on the navigation bar for users to contribute dining spots to the list.

<br/>
<br/>

## Testing Returning Visitor Goals (UX)
### 1. A returning visitor’s purpose for using the app would be to either find a dining spot based on other users’ experiences or to add to the library a new dining spot they have personally visited.
- **Outcome:** Goal accomplished with directory displayed on Home page and Log A New Spot option on navigation bar.
### 2. A returning visitor should be able to quickly browse through the library of dining spots collected on the app.
- **Outcome:** Goal accomplished with directory displayed on Home page.
### 3. A returning visitor should be able to quickly and easily log in to the app.
- **Outcome:** Goal accomplished with Log In option on navigation bar.
### 4. A returning visitor should be able to contribute to the library upon logging in. 
- **Outcome:** Goal accomplished with Log A New Spot option on navigation bar. 
### 5. A returning visitor should be able to edit his/her own entries to the library.
- **Outcome:** Goal accomplished with Edit & Delete buttons displayed next to dining spots entered by user. 
### 6. A returning visitor should be able to view their app profile.
- **Outcome:** Goal accomplished with Profile option on navigation bar.

<br/>
<br/>

## Testing Responsiveness
### Responsiveness of the app was tested using Google Dev tools. 
- **Issues Found:** When viewing in mobile phone view, Search, Reset, Edit and Delete buttons were pushed off center and distorted.
- **Fix:** Changed and deleted class for div assigned to Search and Reset buttons. Applied separate div to Edit/Delete buttons. 
- **Outcome:** Buttons and corresponding text on the side is properly aligned. 
  
<br/>
<br/>

# Deployment to Github Pages
**To deploy to GitHub Pages use the following steps:**

1. Log in to GitHub and locate your GitHub Repository. For this particular project the name is **milestone-project-3**.
2. At the top of the Repository, find the "Settings" button and select it. 
3. Scroll down the Settings page and find "GitHub Pages" section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page should automatically refresh but if it doesn't, refresh the page.
6. Scroll back down through the page to the same section and find a published site link.

**To clone this repository use the following steps:**

1. When logged into GitHub, navigate to the repository you want to clone. For this project, click here.
2. Click on the 'Clone or download' button which should be displayed above and to the right of the repository files.
3. You are presented with a HTTPs address. Copy this address by pressing the button to the right of the address.
4. Open your terminal.
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type 'git clone' and then paste the URL you copied.
7. Press Enter and your local clone will be created.

<br/>
<br/>


# Deployment to Heroku
To deploy to Heroku use the following steps:
1. On Heroku create an account and log in.
2. Click new and create new app.
3. Choose a unique name for your app, select region and click on Create App
4. Under the Settings click Reveal Config Vars and set IP to 0.0.0.0 and the PORT to 5000
5. Go to the CLI and type $ sudo snap install --classic heroku
6. Type $ heroku login command into the terminal
7. Create requirements.txt ($ sudo pip3 freeze --local > requirements.txt)
8. Create a Procfile ($ echo web: python app.py > Procfile)
9. Go back to Heroku, under Deploy find Existing Git repository and find corresponding Git repository by name. 
10. In the app dashboard, under Settings click on Reveal Config Vars
11. Set "MONGO_URI" and "MONGO_DBNAME" and "SECRET_KEY"
12. Once the build is complete, go to Domains section of Settings page and you will find a link to app.

<br/>
<br/>

# Credits

## Code
 - [Materialize:](https://materializecss.com/) Materialize used throughout the project mainly to make site responsive. 
 - [JQuery:](https://jquery.com/) jQuery was used to facilitate functionality of Bootstrap and other functions.
 
<br/>

## Content
  - All content, except as otherwise already noted here, was written by the developer.

<br/>

## Media
Image sources are as follows:
- Home page image was acquired from [Unsplash.com]( https://unsplash.com/). Photo #1: Jarritos Pineaple Taco Break. Photographer: Jarritos Corp.
- Photo #2: People Eating a Meal Around a Table. Photographer: Priscilla Du Preez
- Photo #3: Burgers Being Served. Photographer: Miha Rekar
- Photo #4: Food Truck. Photographer: Should Wang

<br/>

## Acknowledgements
  - My Mentor Brian for continuous helpful feedback.
  - Tutor Support at Code Institute for their support.
  - CI Slack community for their ongoing assistance.

