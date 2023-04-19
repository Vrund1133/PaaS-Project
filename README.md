# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


# **STEPS TO COMPLETE THE PROJECT**

**1. Push your code to the GitHub.**

- Download the PaaS_Code provided by professor.
- Create a new repository called PaaS-Project on GitHub.
- Copy the PaaS_Code provided by sir and paste it onto PaaS-Project repository.
- Open your PaaS-Project folder into the VS Code.
- Now into the Source Control option click to connect to GitHub.
- Once you connect to your repository(PaaS-Project) commit and push your project to GitHub.

**2. Create A Heroku Account.**

- Go to the Heroku website and Sign up for the new email address, you must use your school email for this project.
- Select the language as Ruby.
- Click on create.
- You will recieve an email from Heroku to verify and active your account.
- This will ask to create 2 step verification to create your account.
- Select any one option that suits you and verify your account.
- Now you have created your account on Heroku.

**3. Set the stack version of your code.**

- The Heroku will create application on heroku-22 stack version and it will throw an error while deploying.
- So we need to change the stack version to heroku-20 to run the application successfully.
- Now open the Project in VS Code.
- Open terminal and insert the following command to login to your Heroku account.
  >heroku login
- Hit any key to open the web page and login to your account.
- Now you are logged in to your account.
- Enter the following code to change the stack version of your app, in the end of code there will be your new application name.
  > heroku create --remote heroku-20 --stack heroku-20 vrund-smartapp
- This will create the seperate application based on heroku-20.
- Now you are all set to go to the next step.

**4. Deploying Your Application on Heroku.**

- Go to the Heroku account you had created earlier.
- There you can see your application you created in VS Code with the stack version of heroku-20.
- Open the application.
- Now go to the Deploy option.
- Skip the Choose pipeline option and continue with connect with GitHub.
- Connect your GitHub account then select the PaaS-Project repository you have created earlier.
- Then enable Autometic Deploy.
- Click on deploy branch. (this will take some time.)
- Now you application is deployed.

**5. Opening your application.**

- Open your application from selecting Open app from upper side.
- This will throw some error because of ruby configuration.

**6. Configure your application.**

- There is More button beside of Open app, click on that then open console.
- In the console run the following commands to configure your app.
    buldle install
- Then run the following command to open the rails server.
    rails server
- Then run the following command to migrate the database.
    rails db:migrate
- Lastly, run the following command to seed the database.
    rails db:seed
- Now your application has data in it.

**7. Open your seeded application.**

- After running these  commands your app will be live on Heroku server.
- I am giving my application link here to understand - 
  https://vrund-smartapp.herokuapp.com/
- You just need to sign up in the application.
- Now you can see the 50 Articles and 10 comments to each of them.