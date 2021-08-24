# wayfinder

"Suddenly I came out of my thoughts to notice everything around me again-the catkins on the willows, the lapping of the water, the leafy patterns of the shadows across the path. And then myself, walking with the alignment that only comes after miles, the loose diagonal rhythm of arms swinging in synchronization with legs in a body that felt long and stretched out, almost as sinuous as a snake…when you give yourself to places, they give you yourself back; the more one comes to know them, the more one seeds them with the invisible crop of memories and associations that will be waiting for when you come back, while new places offer up new thoughts, new possibilities. Exploring the world is one the best ways of exploring the mind, and walking travels both terrains."
— Rebecca Solnit (Wanderlust: A History of Walking)


# Introduction

A social media/review app built using the MVC Architecture.

Users can sign up, customize & personalize their favorite walking, biking, strolling paths.

link to working app: `https://protected-forest-09739.herokuapp.com/`


# Objectives

- It's an advance level app created to understand how MVC concepts with backend technology and CRUD logic to comment, post, delete images and paths posted by users.

---

# Who is this for? 

- It's for intermediate programmers with little more experience, to help understand the various aspects of building a node app with some complex features

---

# Tech used 

- HTML, CSS, Bootstrap, JavaScript, Express, Node.js, Mongodb/Mongoose, EJS, Cloudinary, Heroku, Mapbox, joi

---

# Packages/Dependencies used 

mapbox,
cloudinary,
connect-flash,
connect-mongo,
dotenv,
ejs,
ejs-mate,
express,
express-mongo-sanitize,
express-session,
helmet,
joi,
method-override,
mongoose,
multer,
multer-storage-cloudinary,
passport,
passport-local,
passport-local-mongoose,
sanitize-html

---

# Install all the dependencies or node packages used for development via Terminal

`npm install mapbox cloudinary connect-flash connect-mongo dotenv ejs ejs-mate express express-mongo-sanitize express-session helmet joi method-override mongoose multer multer-storage-cloudinary passport passport-local passport-local-mongoose sanitize-html`


---

# Future Add-ons
- Currently working with this same architecture to build an app to find the best wheelchair accessible restrooms in your city.
- Add more methods to login (gmail, yahoo, github, etc..)
---

# Things to add
- Create a `.env` file and add the following as `key: value` 
  - PORT: 2121 (can be any port example: 3000) 
  - DB_URL: `your database URL from MONGODB` 
  - CLOUDINARY_CLOUD_NAME: `cloudinary name` 
  - CLOUDINARY_KEY: `your cloudinary api key` 
  - CLOUDINARY_SECRET: `your cloudinary api secret` 
  - SECRET: `secret used (you write your own)`
  - MAPBOX_TOKEN: `your mapbox token`
  
  In your `.env` file, add the above with this syntax:
  `DB_URL=mongodburlfromyourmongoaccount`
  
  Note the equals sign, no quotes, no spaces.
 ---
 