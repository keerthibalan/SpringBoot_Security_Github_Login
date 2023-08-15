# SpringBoot_Security_Github_Login
This repository is responsible for accessing Github project using spring boot security

# Prerequstics
Java SE 17 Spring STS tool( you can use any development tool)

# Create github application for oauth2
Login to your github application
Go to setting and click on the developer setting 
Create the SpringBoot_Security_Github_Login application
Get the client id and client secrect token and set the value into the applicaiton.yml file in your spring boot application

# Homepage URL
http://localhost:8080

# Authorization callback URL
http://localhost:8080/login/oauth2/code/github

# Run the spring security application
run using the STS or create the maven build to run the jar file
http://localhost/login

Rediect the page the github login

# Authorization
Autharize the spring security login to get the access token
