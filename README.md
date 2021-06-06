<td><img src="static/images/camp_rover_logo.jpg" alt="Database Schema Visual" style="width: 400px;"/></td>

## Camp Rover Ecommerce App 

#### View Github Pages site [here](https://github.com/katyacano/milestone-project-4)
#### View Heroku deployed app [here](https://kc-ms4-camp-rover.herokuapp.com/)  
<br/>
<br/>

# User Stories (UX)


## Shopper Goals
| User Story No.  |  As A/An  |  A User Should Be Able To  |  So That They Can  |
| :-------------: | --------- | -------------------------- | ------------------ |
|        1        | Shopper   | Sort a specific category of product | Find the type of item they need to purchase, whether it be for day care, training services or accessories|
|        2        | Shopper   | Easily see search results and number of results | Quickly determine if the store offers the product or service they need |
|        3        | Shopper   | View list of products    | Select some to purchase|
|        4        | Shopper   | View individual product details | Identify the price, description, product rating, product image (if applicable), and sizes (if applicable) | 
|        5        | Shopper   | Easily view the total amount of intended purhase  | Know how much they will be spending |
|        6        | Shopper   | Be able to easily select the product or service they need, including (if applicable) the size and quantity| Make sure they purchase the right products and services|
|        7        | Shopper   | View items ready for purchase in cart | Understand the total cost of their purchase and ensure they have the right items in cart|
|        8       | Shopper   | Adjust the quantity of items within the cart  | Easily make changes to their intended purchase if needed |
|        9       | Shopper   | Easily enter payment information | Complete the purchase|
|        10       | Shopper   | Have confidence in the security of my personal information | Feel that my purchase is safe and that I can return to this site for future purchases|
|        11       | Shopper   | View an order confirmation at the end of the transaction and receive a confirmation email | Know that the purchase is complete and be able to keep a record of it |
|        12       | Shopper   | View specific categories of services or products| Quickly find the products they are interested in |

<br/>

## Visitor Goals
| User Story No.  |  As A/An  |  A User Should Be Able To  |  So That They Can  |
| :-------------: | --------- | -------------------------- | ------------------ |
|        1        | Visitor   |   Register for an account and have a personal profile    | Have a personal site account where their personal information can be stored |
|        2        | Visitor   | Easily log in or out | Quickly access personal details of account, previous orders, etc. |
|        3        | Visitor   |   Recover a lost or forgotten password  | Never lose access to shopping account and details |
|        4        | Visitor   |   Receive an email confirmation of account setup    | Verify that account was set up correctly |


 <br/>

 ## Site Owner Goals
| User Story No.  |  As A/An  |  A User Should Be Able To  |  So That They Can  |
| :-------------: | --------- | -------------------------- | ------------------ |
|        1        | Owner   | Add products    | Continously update the store with more products and services customers need and want|
|        2        | Owner   | Edit products | Change product and service details, prices, and descriptions as necessary | 
|        3        | Owner   | Delete a product  | Remove product and service offerings as needed |

 <br/>

# Design

  ### Color Scheme
  - The main colors used will be black, gray, white, and a yellow variant (specifically, #F7DC6F).
  ### Typography
  - The font for the logo is Boogaloo from Google Fonts 
  - The font family used for this site will be Lato throughout the site, with San Serif as the fallback if such font family is not being imported. 
  ### Imagery 
  - Imagery is very important on this app. It will be used to appeal to dog owners specifically and feature a variety of dogs. The images will be professional and acquired from Unsplash. Product images are very important and will be featured with a white background in order to show as much detail. Because this is a fictitious company created for this project, professional products images have been acquired from various Amazon.com product pages. 

<br/>
<br/>

# Wireframes

## Home Page
<td>
<img src="static/images/wireframes/homepage1.jpg" alt="Desktop Homepage Wireframe" style="width: 500px;"/> <img src="static/images/wireframes/homepage2.jpg" alt="Mobile Homepage Wireframe" style="height: 400px;"/>
</td>

<br/>
<br/>

## About Page
<td>
<img src="static/images/wireframes/about1.jpg" alt="Desktop About Wireframe" style="width: 500px;"/> <img src="static/images/wireframes/about2.jpg" alt="Mobile About Wireframe" style="height: 400px;"/>
</td>

<br/>
<br/>

## Product Pages
Day Care, Training, Accessories and Special Offers pages will all have the following layouts on desktop and mobile devices.
<td>
<img src="static/images/wireframes/daycare1.jpg" alt="Desktop Day Care Wireframe" style="width: 500px;"/> <img src="static/images/wireframes/daycare2.jpg" alt="Mobile Day Care Wireframe" style="height: 400px;"/>
</td>

<br/>
<br/>
<br/>

# Features

- Responsive on all device sizes
- Interactive elements: 
    - Search bar
    - Register form
    - Sign In/Out actions
    - My Profile update form
    - Log in/ log out actions
    - Go to secure checkout 
    - Adjust order option at checkout
    - Secure checkout page
    - Product management (Add a product) page for admin
    - Edit product page for admin
    - Edit/Delete options for each product (visible only to admin/superuser)

<br/>
<br/>


# Technologies Used

## Languages Used
- [HTML5](https://en.wikipedia.org/wiki/HTML5)
- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
- [Javascript]( https://www.javascript.com/) 
- [Python](https://www.python.org/)

<br/>

## Frameworks, Libraries & Programs Used

[Google Fonts:](https://fonts.google.com/)
   - Google fonts were used to import the Roboto font family into the style.css file which is used on all pages throughout the project.

[Google:](https://www.google.com/)
   - Google was used to find images for the Day Care, Training and Special Offers categories where and I was unable to find suitable images for other parts of the site. 

[GMail:](https://mail.google.com/)
   - Gmail was used to send confirmation emails (profile set-up, purchases, etc.)

[Font Awesome:](https://fontawesome.com/start)
   - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.

[Bulma:](https://bulma.io/)
   - Bulma was used to ensure that Font Awesome icons would stay consistently sized and centered.

[Bootstrap:](https://getbootstrap.com/)
   - Bootstrap was used to assist with the responsiveness and styling of the website.

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

[Stripe:](https://stripe.com/)
   - Stripe was used as the payment gatewway to process payments from customers on the site.

[Django:](https://www.djangoproject.com/)
   - Django was used as a framework to facilitate rapid site development.

[TempMail:](https://temp-mail.org/)
   - TempMail was used to create a temporary email to enable the creation of test profiles.

[MiniWebTool:](https://miniwebtool.com/django-secret-key-generator/)
   - MiniWebTool's Django Secret Key Generator was used to generate secret keys.

[W3C Validator:](https://validator.w3.org/)
   - This validator was used to check HTML and CSS.

[PEP 8 Online Validator:](http://pep8online.com/)
   - This validator was used to check Python code.

[JSHint:](https://jshint.com/)
   - This validator was used to check Javascript code. 

<br/>


# Database and Database Schema
Postgres is the database used for storing product categories, product details, user’s profile details and previous order information. 
The schema is as follows:
<td><img src="static/images/db_schema/db_schema.jpg" alt="Database Schema Visual" style="width: 800px;"/></td>

<br/>
<br/>

# Defensive Design (Security Features)
Defensive design and security features have been achieved by:
- Utilizing inbuilt Django validation and authentication features
- Assigning a specific Staff status to each user and only allowing those users labeled as Staff access to product management site features
- Users must sign in to view order history and personal profile details
- Users cannot view other users' previous order history and personal information
- If a users tries to enter a url for a protected area of the site, the Django @login required decorator and superuser class will stop the action and flash a warning message stating that only store owners are allowed access to that area
- If a user tries to checkout with an empty shopping bag, a warning messages lets them know that there is nothing in their shopping bag
- Email fields with correct email structure are required fields for registering onto the site as a new user
- When registering as a new user, a visitor is required to enter email and password twice to ensure they enter information correctly


<br/>
<br/>

# Testing

## Manual Testing

### **Test-** Clicking Camp Rover logo should return user to home page
- Result: Tested logo on all pages and action works as intended. No errors.

### **Test-** Clicking on navbar links should direct user to corresponding pages
- Result: Tested all links (in desktop, tablet and mobile modes) before and after logging in. Links work as intended. No errors.

### **Test-** Entering required info on Register page and clicking on Register button should create a new user in database.
- Result: Entered data for user 'testytest'. Action completed as intended. No errors.

### **Test-** Entering valid user info on Log In page and clicking on Log In button should allow user access to app and direct user to Home page.
- Result: Tested by entering info for all three current users. Action worked as intended. No errors. 

### **Test-** Entering invalid user info on  Log In page and clicking on Log In button should not grant access to app and flash an error message.
- Result: Tested with three different user entries. Action works as intended. No errors. 

### **Test-** Entering required information on Add Product page should result in a new product being added to database.
- Result: Tested all entry fields. Action works as intended. No errors. 

### **Test-** Missing any information on Add Product page should result in error messages for each line that is missing or has insufficient characters.
- Result: Tested by entering various combinations of information/misinformation. Action works as intended. No errors.

### **Test-** Edit/Delete buttons for each product should only be visible to super user designated as "Staff" in databse. 
- Result: Tested with different users. Action works as intended. Users are not able to edit or delete products unless they are superusers. No errors.

### **Test-** Search function should look for keyword matches in category name, product, and product detail pages. 
- Result: Tested with various keywords from all fields. Action works as intended. When keyword was found in any of these pages Search function returned a match. When keyword was found in other areas (ie. Username), no result was found and No Result message falshed. 


<br/>
<br/>


## Testing Shopper Goals (UX)  

| User Story No. |  A User Should Be Able To  |  So That They Can  |
| :-------------:| -------------------------- | ------------------ |
|        1       | Sort the list of products and services available for purchase | Easily identify them by rating, price and category |
|        2       | Sort a specific category of product | Find the type of item they need to purchase, whether it be for day care, training services or accessories|
|        3       | Sort multiple categories of products and services on the same page | Find the type of item they need to purchase, whether it be for day care, training services or accessories|
|        4       | Easily see search results and number of results | Quickly determine if the store offers the product or service they need |
|        5       | View list of products    | Select some to purchase|
|        6       | View individual product details | Identify the price, description, product rating, product image (if applicable), and sizes (if applicable) | 
|        7       | Easily view the total amount of intended purhase  | Know how much they will be spending |
|        8       | Be able to easily select the product or service they need, including (if applicable) the size and quantity| Make sure they purchase the right products and services|
|        9       | View items ready for purchase in cart | Understand the total cost of their purchase and ensure they have the right items in cart|
|        10      | Adjust the quantity of items within the cart  | Easily make changes to their intended purchase if needed |
|        11      | Easily enter payment information | Complete the purchase|
|        12      | Have confidence in the security of my personal information | Feel that my purchase is safe and that I can return to this site for future purchases|
|        13      | View and order confirmation at the end of the transaction and receive a confirmation email | Know that the purchase is complete and be able to keep a record of it |

<br/>

## Testing Visitor Goals (UX)
| User Story No.  |  A User Should Be Able To  |  So That They Can  |
| :-------------: | -------------------------- | ------------------ |
|        1        |   Register for an account and have a personal profile    | Have a personal site account where their personal information can be stored |
|        2        |   Easily log in or out | Quickly access personal details of account, previous orders, etc. |
|        3        |   Recover a lost or forgotten password  | Never lose access to shopping account and details |
|        4        |   Receive an email confirmation of account setup    | Verify that account was set up correctly |


 <br/>

 ## Testing Site Owner Goals
| User Story No.  |  A User Should Be Able To  |  So That They Can  |
| :-------------: | -------------------------- | ------------------ |
|        1        | Add products    | Continously update the store with more products and services customers need and want|
|        2        | Edit products | Change product and service details, prices, and descriptions as necessary | 
|        3        | Delete a product  | Remove product and service offerings as needed |

<br/>
<br/>


## Testing Responsiveness
### Responsiveness of the app was tested using Google Dev tools. The following issues were found and fixed accordingly:
- **Issues Found:** When viewing in mobile phone view, Search, Reset, Edit and Delete buttons were pushed off center and distorted.
- **Fix:** Changed and deleted class for div assigned to Search and Reset buttons. Applied separate div to Edit/Delete buttons. 
- **Outcome:** Buttons and corresponding text on the side is properly aligned. 
  
<br/>
<br/>

# Code Validation

### Code was validated using the following:
#### **Python3**
- Validator: (http://pep8online.com/)
- **Outcome:** First test resulted in several errors pertaining to trailing whitespaces, line-too-long and various linting errors. Corrected all trailing whitespace and line-too-line errors possible. Ignored the linting errors on advice of tutor and Slack community.

#### **HTML & CSS**
- Validator: (https://jigsaw.w3.org/css-validator/)
- **Outcome:** First test failed with various errors due to missing elements (paragraph and div) and Jinja syntax. Corrected errors. Second test passed with zero errors.

#### **Javascript**
- Validator: (https://jshint.com/)
- **Outcome:** Tests of various javascript code passed with no errors. 

<br/>
<br/>


# Deployment to Github Pages
**To deploy to GitHub Pages use the following steps:**

1. Log in to GitHub and locate your GitHub Repository. For this particular project the name is **milestone-project-4**.
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
11. Set "DATABASE_URL" and "SECRET_KEY".
12. Once the build is complete, go to Domains section of Settings page and you will find a link to app.
13. Other Config Vars you will set include: AWS_ACCESS_KEY_ID, AWS_SECRET_ACCESS_KEY, EMAIL_HOST_PASS, EMAIL_HOST_USER, STRIPE_PUBLIC_KEY, STRIPE_SECRET_KEY, STRIPE_WH_SECRET, and USE_AWS.

<br/>
<br/>

# Credits

## Code
 - [Bootsrap:](https://getbootstrap.com/) Boostrap was used throughout the project to rapidly achieve responsiveness. 
 - [Bulma:](https://fontawesome.com/start) Bulma was used to ensure that Font Awesome icons were consistently sized and centered. 
 - [JQuery:](https://jquery.com/) jQuery was used to facilitate functionality of Bootstrap and other functions.
 - [Code Institute:](https://codeinstitute.net/) Code Institute learning modules set the foundation for generating the code on this site. 
 
<br/>

## Content
  - All content, except as otherwise already noted here, was written by the developer.

<br/>

## Media
Image sources are as follows:
- Home page image was acquired from [Unsplash.com]( https://unsplash.com/). 
- About Us image was acquired from [Unsplash.com]( https://unsplash.com/). 
- Photos of Daycare and Training services were acquired from [GoogleImages](https://www.google.com/search?q=images&source=lnms&tbm=isch&sa=X&ved=2ahUKEwj0vs7rjYTxAhXxoFsKHXxVDmwQ_AUoAXoECAEQAw&biw=1920&bih=969).   
- Product images and descriptions were acquired from [Amazon.com]( https://amazon.com/) since this is a school project and will not be made public.

<br/>

## Acknowledgements
  - My Mentor Brian for continuous helpful feedback.
  - Tutor Support at Code Institute for their support.
  - CI Slack community for their ongoing assistance.

