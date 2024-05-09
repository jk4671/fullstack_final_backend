# Notes Keeper (Backend)

This is the backend of the Notes Keeper app created using Node, Express, MongoDB. It lets users create, edit, and delete notes (with Title and Content).

It has been deployed on Render (https://fullstack-final-backend.onrender.com/).

This project was based off of Shivam Shekhar's Note Taking app (https://github.com/shvam0000/Full-Stack-Note-Taking-Application).

The frontend can be found here: https://github.com/jk4671/fullstack_final_frontend.git.

## Author

Jordyn Kim

UNI: jk4671

## Prerequisites

### System requirement :

1. Any system with basic configuration.
2. Operating System : Any (Windows / Linux / Mac).

### Software requirement :

1. Updated browser
2. Node.js installed (If not download it [here](https://nodejs.org/en/download/)).
3. Any text editor of your choice.

## Steps to run the program

Create a .env file and add MONGO_DB_URI to the file
```
touch .env
```
or 
```
cat .env
```
Install all the dependencies
```
npm install
```
If you wish to run the program locally, change process.env.PORT to 8000 in index.js.
```
8000
```
Run the backend Node.js server
```
npm run start
```
