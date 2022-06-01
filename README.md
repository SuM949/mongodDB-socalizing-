# mongodDB-socalizing-
## Table of content
   ## Description
  This application is an social networking API that allows users to share their thoughts, react to friends’ thoughts and create a friend list. The application uses Express.js for routing, a MongoDB database and Mongoose ODM. In addition to using the Express.js and Mongoose packages, the app uses DateJS package to format timestamps. Furthermore, as this is not a deployed application.


  * [Installation](#installation)
  * [Usage](#usage)
  * [Questions](#questions)

 
  ## Installation 
- open a terminal,clone the repo
- node.js needs to be installed all the packages
- enter npm start to start the server.js file which will then  start API on localhost PORT 3001

# Usage 
Routes for users:

- GET all users: http://localhost:3001/api/users
- GET a single user: http://localhost:3001/api/users/USERID
- POST a user: http://localhost:3001/api/users

Routes for adding friends:

- POST new friend to user: http://localhost:3001/api/users/USERID/friends/FRIENDID
- DELETE a friend from a user: http://localhost:3001/api/users/USERID/friends/FRIENDID

Routes for thoughts:

- GET all thoughts: http://localhost:3001/api/thoughts
- GET a single thought: http://localhost:3001/api/thoughts/THOUGHTID
- POST a thought: http://localhost:3001/api/thoughts/
- UPDATE a thought: http://localhost:3001/api/thoughts/THOUGHTID
- DELETE a thought: http://localhost:3001/api/thoughts/THOUGHTID

Routes for reactions:

- POST a new reactions: http://localhost:3001/api/thoughts/THOUGHTID/reactions
- DELETE a reactions: http://localhost:3001/api/thoughts/THOUGHTID/reactions/REACTIONID

## Questions

 Contact me with any questions: 
 [Email](mailto:sumayabile8@gmail.com) , [Github](https://github.com/SuM949)
 