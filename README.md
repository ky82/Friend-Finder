# Friend-Finder
########################################
# Description:
Friend Finder implements friend matching based on the user's responses to a ten question survey. The user responds to questions with values from 1 (Strongly Disagree) to 5 (Strongly Agree). When the survey is submitted, an existing user record closest to the current user's responses is found and returned. The closest set of user responses is defined as the set with the lowest absolute difference for all ten questions combined.

Friend Finder application is meant to simulate a simple dating app. The application is implemented using a Node.js and Express server on the back end and the Materialize CSS framework on the front end.
########################################
# Link in Heroku:
https://calm-falls-47750.herokuapp.com/
#########################################
# Installation & to run it locally:
To install the application follow the instructions below:

git clone https://github.com/ky82/Friend-Finder.git
cd friend-finder
npm install
node server.js
