<img src="https://raw.githubusercontent.com/Wonka86/Jobra-valley-farms/master/media/tractor-banner.png" style="margin: 0;">

# Jobra Valley Farms

Live Website can be visited <a href="https://Jobra-valley-farms.herokuapp.com/" target="_blank">Here</a>

Conceived from a love of fresh locally sourced food, Jobra Valley Farms  has become a hub for top notch produce.The online farming co-op plan is to serve people in the north-west region with freshly supplied produce from farms that specialise in different types of farming.

This project is used to showcase the use of Fullstack skills in the production of a farm shop to supply fresh produce in the local vicinity with the idea of creating a viable product that users and producers woould what to use to buy and sell on. 

## UX

### Target audience

- People who want to shop local but find it difficult to shop in person (for any reason)
- People who are not sure were to start when shopping fresh 
- People who are curious about what sort of products a grown locally
- People who are looking for an alternative choice
- People who are interested in sustainable farming practises and enviornment

### User Stories

### New User

- I expect to easily navigate the website, so that I can quickly find what I'm looking for.
- I want to be able to learn more about Jobra Valley farms and what makes them different.
- I expect to access the website from any device, so that I can use the website anytime and anywhere.
- I want to be able to easily contact the owner/manager of the company, so that I can write an additional query or ask a question.
- I expect to be able to easily register for an account so that I can see and save my personal details for quicker ordering in the future.
- I want to be able to access social media accounts of the company as i use these daily and would like more information through that interface.

### Returning user

- I want to be able to easily log in and out of my account so that I can access my personal information and order history.
- I expect to be able to reset/ change my password if I forgot it, so that I can get access to my profile again.
- I want to be able to have my delivery details prefilled so that I can save time.

### Website User

- I expect to be able to add/delete products from my cart so that I can update the products I would like to purchase
- I want to be able to see a list of products and easily break them down to different categories.
- I expect to be able to click on a product and see it in more detail.
- I want to be able to receive an order confirmation so that I can be sure my order has gone through.

### Website Owner

- I expect to be able to Sell products securely to customers
- I want to have convenient admin interface to be able to add, remove and update products.


## Wireframes

The following wire frame was used as the base design for thw website

- [Wireframe](https://github.com/Wonka86/Jobra-valley-farms/tree/master/wireframes)

There have been some changes from the orginal design due to aesthetic appeal not feeling quite right on production.

[wireframe](https://wireframe.cc/) tool was used to create the wireframes for the project

## Design

- I used Bootstrap framework for ease of use and ability to be easily customized. It is used for creating features such as navbar, cards, forms, as well as for the layout.
- JQuery is used for initializing some Bootstrap components.
- I used FontAwesome across the project for social media links, forms, cart, search and user icons in navigation.

## Website Features

Jobra valley farms contain the following applications: home, about, blog, bag, checkout, contact, products and profiles.

### Existing Website Features

- Navigation Bar:  Main nav bar is fixed at the top throughout all pages on desktop and mobile screen. The logo placed on the left hand side, search option, accounts and shopping cart moving left to right.  This allows for ease of navigation in finding products, login/ register and items bought so far.


- Navigation : secondary nav allows for accesing shop, reading information about shop, contact and blog. This collapses on small screen to a burger menu.

- Footer: Contains social media link and home logo/button comes in two forms one for desktop and mobile.

- Home page: The home page serves to draw in users to the business and give an idea of what is expected from the website. 
**Hero Image** section is what users see first. The idea behind this is to give an impression of wholsome hard working local farmers producing what we need with a button to take you directly to the products.
**Quotes** sections are there to give short sharpe emphasis on what standards that the company look for **sustainability** and **Quality**.
**short statement** section is to build on the eye catching quotes and fill the user in more.

- About Page: The about page continues to give more information on Jobra valley farms and its main focus and ideas

- Contact Page: Offers a contact form to fill out with name, email and message if a user has any questions or queries. The real email will be sent to the admin of the website. Contact details of where the main office is to be found, ways in which it can be contacted and opening hours are also made avaiable.

- Blog: This section offeres another form of interaction with users and a larger scope for engagement. If there are any events or further background information it can be posted here and users can comment.

- Products pages: (includes Butchery and groceries) Displays product cards with following information - img, name, category, rating and price. All cards are clickable and send the user to individual product detail page. Depending on weather the user has superuser privilege they will be able to edit and delete products on this page with the edit button directing them to product management page and the delete button deleting the product. Users of all levels also have the ability to filter products.

- Product details page: This page offers more information to the user on the specific item showing same informtaion that was in products page along with a detailed paragraph on the item. Here the user can select how many of a particular item they would like to buy with item quantity buttons. The user can then proceed to add to bag and either keep shopping or proceed to bag by clicking on the pop up that says item is added to bag or by clicking the trolly icon item on top right.

- Bag page: The user can evalulate what the have added and make adjustments. They have options to increase or decrease the quantity of the items they would like, see a total of how much everything costs and either keep shopping which return the user to the products page or head to payment by clicking the secure checkout button.

- Checkout Page:  The checkout page has a brief summary of what is being bought displaying quantities names and totals. The page also contains a form which if the user is logged in will be prefilled and all the user will have to complete will be the card payments. when the user can then complete or or adjust bag. adjust bag will go back to the bag section and complete order will go to checkout success page and put order through stripe payment.Since the website is made for educational purposes only and the Stripe functionality is only for testing, only 4242 4242 4242 4242 card number will lead to the successfull payment.

- Checkout success: A display message will thank you saying email confirmation. Information about the order is also displayed.

- Profile page: Available only for authenticated users it contains personal information shipping details and order history.

- Product Admin: Available only for authenticated superusers it contains the ability to add new products by filling out a form. If valid the form/new product is added to the products page.

- Django-allauth features: inlcude sign up ( allows a user to create a new account), Login (allows registered users to log into their account), Forgot password ( allows user to reset password), Logout (renders logout page that gices user option to continue logout)


### Features to add in the future:

- Social account login: This feature would allow an ease of use by connecting accounts such as facebook or google and enhance user experience.

- Defensive delete button: Currently, the Delete button to delete a product has no defence to stop it being automatically pressed. A confirmation of delete should be added.

- Reviews products section: Reading reviews are a great way to help users decide to purchase a product.

## Technologies Used

Languages

[HTML5](https://en.wikipedia.org/wiki/HTML5) 

[CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) 

[JavaScript](https://en.wikipedia.org/wiki/JavaScript) 

[Python](https://www.python.org/)

Libraries and Frameworks

[Django](https://www.djangoproject.com/)

[Bootstrap](https://www.bootstrapcdn.com/)

[stripe](https://stripe.com/gb)

[Fontawesome](https://fontawesome.com/)

[Gunicorn ](https://pypi.org/project/gunicorn/)

[Google Fonts](https://fonts.google.com/)

Tools

[AWS](https://aws.amazon.com/)

[GitHub](https://en.wikipedia.org/wiki/GitHub) 

[Heroku](https://www.heroku.com/what)

[GitPod ](https://www.gitpod.io/)

[wireframe](https://wireframe.cc/) 

Databases

[SQlite3](https://www.sqlite.org/index.html)

[PostgreSQL](https://www.postgresql.org/)

## Testing

### Manual Testing

Navbar

- New User Story - *I expect to easily navigate the website, so that I can quickly find what I'm looking for.*
- Returning user Story - *I want to be able to easily log in and out of my account so that I can access my personal information and order history.*
- Test
  - Check all links on navbar to check if they work properly.
  - Check links on different devices.
  - on mobile make sure menu goes to burger bar.
  - scroll to make sure menu is visible.
  - Make sure search bar appears on mobile devices.
  - Ensure if item added to art appears in alert and total in nav is updated.

- Some bugs appeared with smaller screens sizing, easily corrected. Fruit and veg link didnt work as the category was *fruit&veg* once the & symbol was removed it worked.

Footer

- New User story - *I want to be able to access social media accounts of the company as i use these daily and would like more information through that interface.*
- New User Story - *I expect to easily navigate the website, so that I can quickly find what I'm looking for.*
- Test 
  - Check all links on footer to check if they work properly (socail media links currently linked to main website as no accounts have been set up due to this being an educational project).
  - Check links on different devices.  

- No bugs found all links worked.

Search Bar

- New User Story - *I expect to easily navigate the website, so that I can quickly find what I'm looking for.*
- Test 
  - enter any search word into the search box to see if it redirects to the products page with correct results displayed.
  - submit an empty search query without entering anything.
  - Enter some search words that are expected to be found in the website such as beef and bread.
  - Enter some search words that are not expected to be found in the website.
  - Search from different pages to make sure it works accross all the website.

- Works as intended.

Home Page

- New User Story - *I want to be able to learn more about Jobra Valley farms and what makes them different.*
- Test
  - Main button on hero image clicked and working.
  - Click on all buttons on page to verify that they work.
  - scroll down and verify that statemeents of information on whats is to be expected on site is there.

- No bugs found during testing.

About page

- New User Story - *I want to be able to learn more about Jobra Valley farms and what makes them different.*
- Test
  - Verify that the expected text is displayed correctly.
  - Check that the correct images are displayed for each of the sections.

- No bugs found during testing . 

Contact Page

- New User Story - *I want to be able to easily contact the owner/manager of the company, so that I can write an additional query or ask a question.*
- Test
  - try to submit an empty Contact form and email without @.
  - try to submit the form with all valid information.
  - Verify that the expected text is displayed correctly.
  - Check that the correct images are displayed for each of the sections.

- No bugs found during testing.

Blog Page

- New User Story - *I want to be able to easily contact the owner/manager of the company, so that I can write an additional query or ask a question.*
- New User Story - *I want to be able to learn more about Jobra Valley farms and what makes them different.*
- Test
  - Create a blog post through admin successfully.
  - comments created and go to admin to be authorised before post.
  - Verify that the expected text is displayed correctly.
  - try to submit empty comment form.
  - try to submit valid comment form.


- Issue developed before testing in that blog was not developed on sqlite database and was an addition to website after it had been deployed. Database dump then loaddata to move the blog to heroku and get working. This still had issues in that some of the blog posts didnt transfer over and had to be rewrote manually.

Products & Products detail page

- Website User Story - *I want to be able to see a list of products and easily break them down to different categories.*
- Website User Story - *I expect to be able to click on a product and see it in more detail.*
- Test
  - Verify that the expected text and images are displayed correctly in both products and product details pages.
  - Select the category, clicking on the category-links.
  - Login with superuser credentials and verify that the Edit/Delete buttons appear in both products and product details pages.
  - Being a guest or logging in as a regular user, try manually enter the /edit/ and /delete/ urls.
  - Click on the "View Details" button and on the product image on the all products page.
  - Click on all links on pages.
  - Click on the "Add to Cart" button on the both products and product details pages
  - On the products page try to enter a negative or higher than 999 number in the quality form and click on "Add to cart" button.
  - Enter the quantity in the range of 1-999 and click on the "Add to cart" button.

- issue with increment buttons - found to be javascript indentation issue.

Bag Page

- Website User Story - *I expect to be able to add/delete products from my cart so that I can update the products I would like to purchase.*
- Test
  - Verify that the text and images of the added items are displayed correctly.
  - Try to update the item quantity with different products.
  - Try to manually enter invalid quantity.
  - Click on the "Checkout" button.
  - Remove all the items and check the empty cart, click on the "Go shopping" button.

- issue with increment buttons - found to be javascript indentation issue.

Checkout & Checkout success Pages

- Website User Story - *I want to be able to receive an order confirmation so that I can be sure my order has gone through.*
- Test
  - Verify that the text and images(Order summary) are displayed correctly
  - click on the "Edit bag" link.
  - try to put an incorrect information
  - Enter test card payment and ensure payment goes through to stripe.
  - enter invalid payment card.

- issue with increment buttons - found to be javascript indentation issue.
- email issue - no verification email was being sent out to confirm what items where bought. App deployed on Heroku had development set True, once delete emails worked fine.

Profile Page

- Returning user Story - *I want to be able to have my delivery details prefilled so that I can save time.*
- Test
  - Navigate to the My Profile from the Navbar link
  - Check being a logged in and non-logged in user, that it's only available to the authenticated users.
  - Click on the Order number on the Order History page.
  - Test update information button with correct and incorrect values.
  - After update make purchase to see if information has updated.

- No bugs found during testing.

Allauth Pages

- Returning user Story - *I want to be able to easily log in and out of my account so that I can access my personal information and order history.*
- Returning user Story - *I expect to be able to reset/ change my password if I forgot it, so that I can get access to my profile again.*
- New user Story - *I expect to be able to easily register for an account so that I can see and save my personal details for quicker ordering in the future.*
- Test
  - Try to register entering incorrect email, incorrect password and username/email that already exists in the database.
  - Submit valid registration form.
  - Entering two different passwords in registration form and trying to enter old password when re-setting password.
  - Create an account and try to login with correct and incorrect details.
  - Click on logout link in the navbar and then on logout button.

- email issue on deployed site - no verification email was being sent out upon registering. App deployed on Heroku had development set True, once delete emails worked fine.

Admin

- Website Owner Story - *I want to have convenient admin interface to be able to add, remove and update products.*
- Test
  - Navigate to the Product Management page from the navbar
  - Click on the "Add a New Product"
  - Try to submit a form with both empty and with invalid information to see if the error messages will appear.
  - Submit "Add a New Product" form with all valid information multiple times creating different products (providing/not providing an image, filling all/only required fields)  
  - After adding a product/service with an image, go to the AWS S3 website and check the basket to see if the image was saved there.
  - After clicking "Edit" button on the product/service pages, fill out the edit form.
  - Create few testing products and services with dummy data for testing the delete functionality:
  - Click on the "Delete" button on the product ensure it works.
  - Being a guest or logged in as a regular user(not admin), manually enter the edit/delete/add URLS to reach the corresponding pages trying to access admin functionality and manipulate the database.

- No bugs found during testing.

### Validators

- HTML - HTML files were tested with [W3 Validator](https://validator.w3.org/#validate_by_input) some minor errors showed but nothing that cause major issues.

- CSS - CSS files were tested with [https://jigsaw.w3.org/css-validator/](https://jigsaw.w3.org/css-validator/) again no major errors showed themselves.

- JavaScript - JS files were tested with [JShint](https://jshint.com/) and [Esprima](https://esprima.org/demo/validate.html). No major issues indicated.


### Responsiveness and compability

- Google Chrome's developer tools to see how it looks across all the different device screen sizes to ensure compatibility and responsiveness.

- The website was also tested on multiple browsers inlcudeing Chrome, Edge, Firefox and IE.

### other

The app was constantly tested with debugger locally with debug=True throughout all the development process. Every time when there was an issue, the debugger displayed an error message, that allowed me to locate and fix it issues.




## Deployment

Jobra-valley-farms was developed on gitpod and deployed on Heroku.

Heroku deployment process

- [requirements.txt](https://github.com/Wonka86/Jobra-valley-farms/blob/master/requirements.txt) is needed as it contains a list of dependencies and created by pip3 freeze > requirements.txt in gitpod console.
- [Procfile](https://github.com/Wonka86/Jobra-valley-farms/blob/master/Procfile) is needed in order to tell heroku how to run project.
- On [Heroku](https://dashboard.heroku.com/apps) go to create a new app, assign a name and closest region and click create app.
- In Heroku  resources tab go to Heroku Postgres select hobby dev and click provision button to add project.
- In Heroku settings tab click on reveal config vars and set the following - 
  - AWS_ACCESS_KEY_ID = your aws access key
  - AWS_SECRET_ACCESS_KEY = your aws secret access key
  - DATABASE_URL = your postgres database url
  - EMAIL_HOST_PASS = your email password(generated by Gmail)
  - EMAIL_HOST_USER = your email address
  - SECRET_KEY = your secret key
  - STRIPE_PUBLIC_KEY = your stripe public key
  - STRIPE_SECRET_KEY = your stripe secret key
  - STRIPE_WH_SECRET = your stripe wh key
  - USE_AWS =	True
- Temporary set up (do not push) - Copy DATABASE_URL's value(Postrgres database URL) from the Convig Vars and paste it into the default database in settings.py.
- Migrate the database models to the Postgres database using the following commands in the terminal - python3 manage.py makemigrations and python3 manage.py migrate
- Load the data fixtures - python3 manage.py loaddata <fixture_name>
- Create a superuser for the Postgres database - python3 manage.py createsuperuser
- Remove your Postgres URL database from the settings and uncomment the default DATABASE settings code in the settings.py file.
- Add your Heroku app URL to ALLOWED_HOSTS in the settings.py file
- Automatically deploy each time you push to GitHub by going to heroku 
  - Deploy section -> Deployment method -> select GitHub
  - link the Heroku app to your GitHub repository for this project
  - click Enable Automatic Deploys in the Automatic Deployment section
  - Run git push command in the terminal, that would now push your code to both Github and Heroku, and perform the deployment.
- on successful deployment you can view your app by clicking Open App on Heroku
- Verify email by logging on with superuser login on app address/admin

## Local Deployment

For local deployment the user can download the git repository by clicking 'download.zip' button at the top of the page and extracting the zip file to your chosen folder or clone the repository by following what is outlined here: https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository.

- Install the required dependencies with the following command: pip3 install -r requirements.txt

- Create an env.py file and add the following with your own values:
  - import os  
  - os.environ["DEVELOPMENT"] = True    
  - os.environ["SECRET_KEY"] = your secret key 
  - os.environ["STRIPE_PUBLIC_KEY"] = your stripe public key    
  - os.environ["STRIPE_SECRET_KEY"] = your stripe secret key    
  - os.environ["STRIPE_WH_SECRET"] = your stripe wh key
  - os.environ["EMAIL_HOST_USER"] = your email address
  - os.environ["EMAIL_HOST_PASS"] = your email password(generated by Gmail)

- Create a .gitignore and add these files so that they are not published at any stage. This is to keep the secret keys and values safe.

- You need to make migrations to set up the SQLite3 tables. You can do that by: python3 manage.py makemigrations, python3 manage.py migrate

- Create a superuser for your project by using the following command: python3 manage.py createsuperuser

- Run locally by the following command: python3 manage.py runserver


## Credits

- Code
   - The project code was developed with the help of Code Institute lessons based on Boutique Ado Django Project
   - The Blog section was created with the help of [Django Central](https://djangocentral.com/building-a-blog-application-with-django/)
   - Documentation was constantly referanced to especially [Django](https://docs.djangoproject.com/en/3.1/) and [Stripe](https://stripe.com/docs)

- Content & media
  - Images where taken from [Pxhere](https://pxhere.com/) particularly banners and hero Images
  - Images & content where taken from the inspiration given by british farm shops including [Keelham farm](https://keelhamfarmshop.co.uk/), [Balgrove Farm](https://www.balgove.com/) and [Kenniford farm](https://kennifordfarm.co.uk/)

- Acknowledgements
  - A special thanks to the tutors at Code Institute without their patience this project would have been alot more difficult. I would like to name you all but out of fear of forgeting anyone i will refer to the collective. You have been amazing.
  - My mentor Victor who helped me with my first steps on this journey.
  - The student slack community - I will never be able to fully repay the kindness and time other student have spent in answering questions and honestly do not know where they find all the extra time. You are all appreciated.

Disclaimer: This project was created for educational use only as part of the Code Institute Full Stack Software Development Course