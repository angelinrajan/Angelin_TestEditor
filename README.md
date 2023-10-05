# Angelin_TestEditor

This project aims to develop a text editor web application that allows users to create notes or code snippets with or without an internet connection. The application should provide a reliable way to retrieve and access these notes or snippets for later use.


## Functionality

The text editor application functions in the browser without errors.Upon opening the text editor, IndexedDB should immediately create a database storage which can be viewed frmom devTools/application.
After reopening the text editor, the previously saved content is retrieved from IndexedDB.Clicking on the Install button allows the user to download the web application as an icon on their desktop.
Service Worker and Manifest files are also displayed in the devTool/Application section. When opening the installed we application, the previously saved texts within the editor is displayed.


## How to Run the Application

1. Clone this repository to your local machine.
2. Navigate to the root directory of the project.
3. Run `npm install` to install the necessary dependencies.
4. Run `npm run start` to start the application.

## Technologies Used

- HTML
- CSS
- JavaScript
- Webpack
- IndexedDB
- Service Workers
- Workbox
- Heroku

## Deployment Steps

Follow these steps to deploy the application to Heroku:

1. Ensure you have a Heroku account and the Heroku CLI installed.

2. Navigate to the project directory in your terminal.

3. Log in to Heroku using the command:
heroku login

4. Create a new Heroku app:
heroku create

5. Commit your changes to git (if you haven't already):
git add .
git commit -m "Initial commit for Heroku deployment"

6. Push the code to the Heroku remote repository:
git push heroku master

7. Once the deployment is successful, open the web application using the provided Heroku app URL.

8. Your text editor web application is now deployed and accessible online.