# Required

* Node v14.16.0
* Clone Repository
* Create docker container for MongoDB
* Create .env file and add in this use .env.example file
* Install Packages

## Create docker container for MongoDB

* Pull Mongo:  `sudo docker pull mongo:5`
* Create Container: `sudo docker run -d -p 27017:27017 --name mongodb-container mongo:5`
* Connect Container: `sudo docker exec -it mongodb-container bash`
* Connect Mongo: `mongosh`
* Create Database: `use mydb`
* Close Mongo: `exit`
* Close Container: `exit`


# **Commands for start process.**

## Copy Repository
`git clone `

## Install Packages
`npm i`

## Start Unit Test
`npm test`
