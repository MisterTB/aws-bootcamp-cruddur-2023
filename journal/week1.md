# Week 1 — App Containerization

#Requirements

Created Dockerfile in both the backend-flask and frontend-react.js directories
Followed along with the video to bring up the docker images and view them in browser
Watched all of the supplemental videos.

##Building Notification API

Ran into some issues with the Notifications API. I didn't recieve the same results as Andrew's example so troubleshooting by looking through the code and the examples. Found that the issue was a wrongly named file
    frontend-react-js/src/pages/NotificationsFeedPage.js
left out the 's'. :(

##Added DynamoDB and Postgres databases

Following along with instruction, created both database services in the docker compose file.
Added a database explorer and .gitignore to the main directory to prevent adding the locally created db to the repo.  

##List of commands to remember 

git tag tagname

git push --tags
