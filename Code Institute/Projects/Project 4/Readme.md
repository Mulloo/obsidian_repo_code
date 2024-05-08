# Gear Gradian & Recall Radar

Gear Gradian and Recall Radar is a site for Climbing Personal Protective Equipment reviews as well as a place to find any manufacturer safety notices or equipment recalls.

  

## Table Of Contents

  

# User Stories

  

# Wireframes

  

# Agile methodology

  

# Database Diagram

  

# Features

  

* **User-friendly design**

  

* **User Registration and Authentication:**

  

* **Add Items:**

  

* **Edit items:**

  

* **Delete items:**

  

* **Delete confirmation:**

  

* **Mark Items as Purchased:**

  

* **Search items:**

  

# Future Features

  

# Technologies Used

  

# Testing

  

## User story testing

  

##### About The App

  

##### Register

  

##### Login / Logout

  

##### View Shopping list items

  

m to that form with item details.

  

##### Add item

  

##### Edit item

  

##### Delete item

  

##### Search the shopping list

  

## Manual Testing

  

## Automated testing

  

##### Used Django default test framework to test views and the model

  

## Code Validation

  

##### HTML validation

  

##### CSS validation

  

##### PEP Validation

  

## Lighthouse

  

## Browser and Device Testing

  

## Deployment

  

The app was deployed to Heroku from a GitHub repository. Below is the deployment step-by-step guide:

  

1. Create Respository on Github

  

* Login into your Github account, in the Repositories section click on the New button.

  

* From the dropdown select the Code Institute Template, give a repository name and click Create repository.

* Once the repository was created, click on the button to create a workspace in GitPod or Codeanywhere (depending on your IDE preferences).

  

2. Install Django and supporting libraries.

  

* pip3 install 'django<4' gunicorn

  

* pip3 install 'dj_database_url psycopg2

* pip3 install 'dj3-cloudinary-storage

  

3. Create a requirements.txt file that lists all the project's dependencies. The file is generated using **pip3 freeze > requirements.txt**.

  

4. Create a Procfile

  

* Heroku uses a Procfile to determine how to run an application. Create a Procfile (without any file extension) in the project's root directory and specify the command to start the application:  **web: gunicorn shoppinglist.wsgi**

  

5. Create the app on Heroku

  

* Go to heroku.com and sign in.

  

* On the home page, click New and then click Create new app from the drop down.

* Give the app a name and select a region, then click Create app.

  

6. Create an external database on ElephantSQL

  

* Log in to your ElephantSQL account and click “Create New Instance”.

  

* Set up your plan and click “Select Region”.

* Return to the ElephantSQL dashboard and click on the database instance name for this project.

* Copy your ElephantSQL database URL using the Copy.

* Go to Gitpod and create a Database URL enviroment variable the env.py file and set it equal to the copied url.

  

7. Environment Variables:

  

* Set environment variables for sensitive data such as SECRET_KEY, DATABASE_URL, CLOUDINARY_URL, and PORT which should be set to 8000. You can set them through the Heroku Dashboard.

  

8. Deploying to Heroku

  

* Scroll to the top of the settings page in Heroku and click the 'Deploy' tab. - For deployment method, select 'Github'. Search for the repository name you want to deploy and then click connect.

  

* Scroll down to the manual deployment section and click 'Deploy Branch'.

  

## Credits