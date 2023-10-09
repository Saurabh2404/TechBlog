# Techie-Blog
- A blogging website to create posts sharing thoughts, ideas, and experiences.
- This website also supports Markdown to create different text styles and make your posts more readable.
- Just create an account and compose your own posts and don't forget to like other's posts 😁.
- Also get the collection of all of your posts in your profile.
<br>
<br />

## TECHNOLOGY USED
![HTML](https://img.shields.io/badge/-HTML-333333?style=flat&logo=HTML5)
![CSS](https://img.shields.io/badge/-CSS-333333?style=flat&logo=CSS3&logoColor=1572B6)
![JavaScript](https://img.shields.io/badge/-JavaScript-333333?style=flat&logo=javascript)
<br>
![MongoDB](https://img.shields.io/badge/-MongoDB-333333?style=flat&logo=mongodb)
![Express](https://img.shields.io/badge/-ExpressJS-333333?style=flat&logo=express)
![Node.js](https://img.shields.io/badge/-Node.js-333333?style=flat&logo=node.js)
![Embedded JS](https://img.shields.io/badge/-Embedded%20JS-333333?style=flat&logo=ejs)
![NPM](https://img.shields.io/badge/-Npm-333333?style=flat&logo=npm&logoColor=white)
<br>
![Git](https://img.shields.io/badge/-Git-333333?style=flat&logo=git)
![GitHub](https://img.shields.io/badge/-GitHub-333333?style=flat&logo=github)
![Heroku](https://img.shields.io/badge/-Heroku-333333?style=flat&logo=heroku&logoColor=6567a5)

<br>

## NPM DEPENDENCIES
```
 "dependencies": {
    "body-parser": "^1.19.0",
    "dompurify": "^2.3.0",
    "dotenv": "^10.0.0",
    "ejs": "^3.1.6",
    "express": "^4.17.1",
    "express-session": "^1.17.2",
    "jsdom": "^16.6.0",
    "marked": "^9.0.3",
    "method-override": "^3.0.0",
    "mongoose": "^5.13.20",
    "mongoose-findorcreate": "^3.0.0",
    "nodemon": "^3.0.1",
    "passport": "^0.6.0",
    "passport-google-oauth20": "^2.0.0",
    "passport-local-mongoose": "^6.1.0"
  }
```
<br>

## LOCAL ENVIRONMENT SETUP
- Clone repository by running this command on git-bash
```
    git clone https://github.com/<your user-name>/Techie-Blog.git
```

- Run command `cd TECHIE-BLOG`

- Install Dependencies using
```
    npm install
```
-  create .env file in the root folder and paste below things in it.
```
SECRET=thisIsMySecret
ATLAS_URI="mongodb+srv://ritikrog90:vrywSRpAsVF8TnZr@cluster0.6elhrwa.mongodb.net/postblogDB"     or
ATLAS_URI="mongodb://127.0.0.1:27017/blogAppDatabase"
PORT = 4000
```
- Run this command to start the project.
```
    npm run dev
```
- Open link to view the website in your browser window if it doesn't open automatically.
```
    http://localhost:4000
``` 
- That's all, now just Sign Up to Techie-Blog and compose your own posts.
<br>
<br>



## CONTRIBUTING
This project is open for contributions so Pull requests and Issues are welcome.


