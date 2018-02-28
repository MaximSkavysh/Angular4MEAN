# MEAN Angular 4 Login Authentication
## Authentication
This project consists of complete login authentication(verification through email + activation link) which is 100% working.
You can signup, signin and the account is registered in a mongoDB collection and verification email will be received in your account.
Forgot Password, forgot username, Resend activation link has also included in this project.Complete validation has been implemented on server side and client side.
## Blog Posting
Users can create a blog/post and share with all the users, other users can like/dislike/post comment to the blog post and share their feelings with each other.The project is still ongoing, but till so far, this application is bug free and working perfectly.

## Technologies Used
* MongoDB
* Express
* Angular 4
* NodeJS

##### Others technologies used:
* Bootstrap
* Angular2-jwt
* Bcrypt
* Validator

## Current Softwares
Application is currently running on the following softwares
1. Node v7.7.1
2. MongoDB 3.4
3. Git 2.12.0

## Run
All packages are available on this project, you dont need to install the packages, all you need is MongoDB Node.js Nodemon installed to run project.

1. run mongod
2. Go to the project meanStackAngular4 folder, open git terminal and type command nodemon index.js and press enter
3. Project will be successfully running on port 8080
The server will auto restart on changes, due to nodemon.
### Note
Please go to the router>>authentication.js file and add your own gmail address and secret password, otherwise you will not receive any email.
## How to use
You can create an account in the signup page, then verify your account using activation link sent to your email address. The accounts are registered in a mongoDB collection (mean-angular2-authentication). An account requires email and password. The password is crypted in the collection.

If you are logged, the private page which is profile page show you your email and username.
### Thanks and links
I started with the DavidAcousta's project, and I added the complete authentication system.

tutorials helped me a lot:

https://www.youtube.com/watch?v=G_xHi0jywmc&t=208s
Thanks for their help.

### Contributors
Momin Shahzad

### License
No License
