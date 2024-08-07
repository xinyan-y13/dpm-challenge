# It's your brand new recording page!

## Project Description

This is a Single Page Web Application which is able to record spoken text as audio (mobile and desktop) and replay the recorded audio. The once recorded audio should be sent together with the email address of the user to a REST-API backend.
The backend API receives the audio and asynchronously processes it by an algorithm which corrects potential (grammatical) errors and produces a corrected audio. Once the audio is corrected, the backend API sends it back to the frontend, where it is displayed and can be played back by the user.

### Audio-Frontend Project
This is the ui of this project using react.js. You can use `yarn start`  to start both projects.


### Audio-Backend Project
This is the server of this project using node.js

### Tech Stack

For frontend I created a simple react.js app

For backend I setup a minimal node.js server with express.js
