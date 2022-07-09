# Dento - a website for your dental needs

This is my 4th milestone project. This site has been created for educational purposes only.

## Visitors Goal:

The target audience for this website are people that have dental issues ranging from small tootaches to metal-ceramic bridge on implants.

## User Stories:

As a new visitor to this website, i would like to see:

* how much experience do the dentists have;
* how modern is the equipment being used;
* how many patients are content with the services provided;
![about](https://user-images.githubusercontent.com/90277864/178124390-6d8950f2-960d-4ba1-ae57-c6ebd5523a71.png)



* if i am able to contact the clinic and ask questions before making an appointment;
![contact form](https://user-images.githubusercontent.com/90277864/178124331-2f024cd8-a3b6-4970-b38f-8105d8ca99ef.png)

* a pretty straight-forward appointment form via the website
![appointment](https://user-images.githubusercontent.com/90277864/178124349-d97065b3-b1cc-4855-b840-eabc8a0732f8.png)



## Wireframes:

* The wireframes were created using Balsamiq during the inception phase of the design and planning process for this project.

![main](https://user-images.githubusercontent.com/90277864/178124289-586a97ef-333b-418a-a2bd-653a30c15d16.jpeg)
![services](https://user-images.githubusercontent.com/90277864/178124296-a198c7cf-623b-4b73-a04e-93749c89cfbc.png)
![pricing](https://user-images.githubusercontent.com/90277864/178124302-7a35d291-fdf1-4684-864f-d9d262735255.jpeg)
![contact](https://user-images.githubusercontent.com/90277864/178124309-208eea79-8b51-4734-a683-6ce866524779.jpeg)


## Features

* At the top of the webpage we have the adress of the clinic, the email adress, social media accounts, and of course the nav bar, which stands out.
![navbar](https://user-images.githubusercontent.com/90277864/178124467-7af3ba73-0f81-49d6-b0cc-fd160450d94b.png)

* The website features information regarding:
  * services being carried out at the clinic;
  * about us section;
  * pricing;
  * an appointment form (name, email, phone number, address, appointment time and date);
  * a contact-us form (name, email and message form)
  
  * MailTrap has been implemented, thus booking an appointment or using the contact-us form will be sent to my account.
  
  ![emails](https://user-images.githubusercontent.com/90277864/178124837-c90c941a-a766-4ca0-afcc-319b0a71f2b8.png)
  
  ## Languages Used: 
  
  * This project uses HTML, CSS, JavaScript and Python programming languages.
  
  ## Tools used:

 * Balsamiq to create the wireframes for this project.
 * Sublime - This was used as the IDE for building the application. This is my 1st time using a local IDE for a Milestone Project.
 * Django as python web framework rapid development and clean, pragmatic design.
 * Git Bash to handle everything locally to deployment on GitHub and Heroku.
 * Heroku CLI to create and manage Heroku apps directly from Bash.
 * PIP for installation of tools needed in this project.
 
 ## Database:
 
 * Django normally works with SQL databases and comes prepacked with sqlite3. 
 * During development on my local machine I worked with the standard sqlite3 database installed with Django. 
 * On deployment, the SQL database provided by Heroku is a PostgreSQL database.

## Manual User testing:
This was the primary method of testing the application. Friends and family were asked to visit the website on a variety of devices; 
to book for an appointment and to use the contact-us form. The feedback was very useful to determine any bugs that may have been present.
I also tested the app manually myself on a varietly of browsers.

## Browsers used for testing:

 * Google Chrome 
 * Mozilla Firefox
 * Microsoft Edge


Manual testing was carried out using the above browsers, and also on mobile devices. No bugs or desplay issues could be identified.


## Bugs:

* When booking an appointment and/or using the contact-us form, the user would get this error:
![error](https://user-images.githubusercontent.com/90277864/178125421-b3fc5b7d-97c6-4cda-956a-ea563519b827.jpg)

 * Email and contact form were not properly implemented through the email service. It has been now fixed.
 
 ## Local Deployment
 
 This project has been worked upon locally through Sublime. The Git Bash terminal has been used for all the necesary procedures in order to upload the project on
 GitHub and on Heroku. All the necessary PIPs have been installed through Git Bash. 
 
 ## Initializing Git For Version Control
 
 * $ git config --global user.name "Your Name"
 * $ git config --global user.email "you@youraddress.com"
 * $ git config --global push.default matching
 * $ git config --global alias.co checkout
 * $ git init
 * ssh key has been generated for integration into GitHub account (ssh-keygen.exe)
 
 ## GitHub Repository:
 
 * an existing repository was pushed from the command line
  * git remote add origin git@github.com:"accountname/websitename.git"
  * git push -u origin main 
 
## Heroku procedure:

 ( as stated before, everything was done through Git Bash )
 
  * pip install gunicorn : webserver
  * pip install django-heroku : heroku dependencies 
  * touch Procfile : to let heroku know what kind of app it is + necessary adjustments through Sublime
  * heroku login : passing through Heroku CLI
  * heroku git:remote -a PROJECT NAME
  * git push heroku <branch>
  
 ## Updates made to the app, while being deployed:

 1. Clone the repository from GitHub to your local device:

 * git clone HTTPS URL FROM GITHUB

 2. Make your changes, and commit them to GitHub:

* git add .
* git commit -m "YOUR COMMIT MESSAGE"
* git push origin BRANCH

 3. Login to Heroku account:

* heroku login

 4. Set remote for your project:

* heroku git:remote -a  PROJECT NAME

5. Push to Heroku master to deploy updates:

* git push heroku BRANCH
 
