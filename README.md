# Notes Keeper (Backend)

This is the backend of the Notes Keeper app created using Node, Express, MongoDB. It lets users create, edit, and delete notes (with Title and Content).

It has been deployed on Render (https://fullstack-final-backend.onrender.com/).

This project was based off of Shivam Shekhar's Note Taking app (https://github.com/shvam0000/Full-Stack-Note-Taking-Application).

The frontend can be found here: https://github.com/jk4671/fullstack_final_frontend.git.

## Author

Jordyn Kim

UNI: jk4671

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
If you wish to run the program locally, change process.env.PORT in index.js to 8000.
```
8000
```
Run the backend Node.js server
```
npm run start
```
