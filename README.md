# Hotel Booking Full Stack App -> MERN STACK

- Technology Stack -> Javascript, React Library, React Context API, Axios Library, Node.JS, Express.JS, MongoDB, MongoDb Cloud, Cookie-Parser, JWT.

# Functionalities
- Implemented "SALT" from "bycrypt.js" to create a password hash and store it to the databse.
- Implemented "JWT" JSON Web Token in the middleware to Authenticate users.
- Implemented "JWT" JSON Web Token in the middleware to Authorize, And if the user permit to do the data manipulation then user's can delete or modify data's.
- Used Cookie-Parser to save the JWT in the cookies section. Cause everytime user loads the website, The cookie will be sent to the request. This helps us to keep track of user's action's.
- Implemented Search functionality to filter out the hotels according to users preference.
- Used React Context API to avoid Prop Drilling.

# How to run this project on your local system ?
- Clone this Repo.
- After cloning run this command in the client and api folder "yarn install".
- After that run "yarn start" -> Both for client and api. So that backend and frontend start locally.
- After that you can use the app. Also you can use the admin side "React Admin panel".
- To use React Admin Panel go to the admin floder and run "yarn install" command.
- After that you can do "yarn start". To start the admiin panel.