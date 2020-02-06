# Code-Center

Created MERN Stack Application using online documentation to get familiar with Web technologies such as MongoDB, Express, React, and Node.js. To start with this, I followed that documentation to get the basic knowledge of MERN stack workflow and then started creating this social media developer network to understand the MERN stack application in depth.

- Code-Center is small social media platform that includes authentication, forum posts, and profiles.
- The application contains Landing page which has Navbar of opaqueness set to 50%. Navbar has tabs attach to it such as Sign Up, Sign In, Developer tab, and Website Name written with font-awesome. The developer tab on landing page shows profile of the users and other developers of the website without registering in website. 
- The website uses Gravitor to shows profile image of the users. Profile tab of the navbar shows full profile of the users that contains their Bio, Education, Experience, Github Repos, and Skill Sets. There is also a link to reach out the developer social media profiles.
- The logged in user can access Dashboard from which they can edit their profile by adding or deleting the experience, education, and skill set. Also, user get an option to delete his account.
- It also have an alert Reducer within Redux where we can easily set and remove alerts which are displayed when user create, update, delete, and modify the profile and after few seconds alert goes automatically.
- Once you logged in you also get a post tab where you can see the latest post that you submitted and also other user's post. Also featured option is created to start discussion on the commented post.
- Inside the post user gets an option to like and dislike a post with the notification number over to convey number of discussion held inside that post. The posted topic has a time stamp and the logged in user's have an option to delete their own post anytime.

# Build with 

MongoDB - As a Database.

Mongoose - As a data abstraction layer for MongoDB.

JWT (JSON Web Token) - To build custom middleware.

Heroku - To deploy the website using Git for Production purpose.

Postman - To check the end to end points between server and client.

Bcrypt - For password hashing encryption with salt for additional security.

React Hooks - Used for strict function component on client & React components for User Interface.

