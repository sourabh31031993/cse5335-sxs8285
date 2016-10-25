# README

1. What server framework did you choose and why? 

   The server framework used for the project is Ruby on Rails where the app is run on the rails server and it is deployed on Heroku. Ruby on Rails is opinionated which means the framework is adhered to do things in a particular way unlike the case with NodeJS. Also some the CRUD applications can be developed at a faster pace compared to NodeJS.

2. What client framework did you choose and why?    

   The client framework used to develop the application is AngularJS. AngularJS is best for building testable web application that scale. The dependency management is effortless and intuitive. And moreover it is easy to write and perform the unit test and end-to-end test.

3. 	What aspect of the implementation did you find easy, if any, and why?   

    The client framework was easy to implement, as I was familiar with HTML and little bit of JavaScript. Also the MVC framework provided by AngularJS helped in developing the app easily.

4. 	What aspect of the implementation did you find hard, if any, and why?      

    While implementing the charts and map I found difficulty in getting the proper format of the Json file for accessing and displaying it.

5. 	What components OTHER than your client and server framework did you install, if any,  and if so, what is their purpose for your solution?    

      Apart from client and server I did not install anything.

6. What Ubuntu commands are required to deploy and run your server?

    The commands required for deploying and running the server is as follows:
    cd myApp is used to open the directory where the app is saved.
    git init is used to initialize the empty repository.
    git commit  -m “my first commit” –This is used to commit the code to git hub.
    Also we can install Heroku CLI and deploy the app on heroku. Initially we use the command
    “heroku login”  - is used to login to heroku by providing the email ID and password.
    “heroku create” – creates an app on heroku .
    “git push heroku master” – is used to push the code to heroku.
    The way I deployed the app was I pushed my code to github repository and in the heroku I created an app and connected to github to fetch the code from github. Then it is compiled in heroku and open app is clicked to see the application. 
