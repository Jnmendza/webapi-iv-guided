# Deployment Notes

Web Servers run web apps

- they accept requests from clients
- send back responses to clients

Web servers are a software running on someones machine

[client] === [web server (multiple web applications/apis)]

Dev process

- write code
- commit and push
- profit (it's deployed automatically to heroku)

Steps to prepare our API for deployment to Heroku

- make the port dynamic port
- setup a "start" script that uses `node` (not `nodemon`) to run our server
======== "start" : "node"

The environment is the platform (the place/operating system/machine) where the application is running.
