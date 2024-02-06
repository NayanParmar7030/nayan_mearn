1) Install Node js
2) Install VS code extension (Auto rename tag, es7...etc)
3) Install React Js (npx create-react-app my-app)
4) remove unwanted file and code in app.js
5) npm start
6) search bootstrap 5 dark mode and take css link

- https://github.com/vinorodrigues/bootstrap-dark-5/blob/main/docs/bootstrap-dark.md
7) Create Components like navbvar,footer
8) Create pages
9) copy bootstrap 5 navbar and add in navbar.js file
- https://getbootstrap.com/docs/5.0/components/navbar/
10) taken card body from below link
- https://getbootstrap.com/docs/5.0/components/card/
11) taken bootstrap slider from - https://getbootstrap.com/docs/5.0/components/carousel/
12) npm i bootstrap-dark-5 bootstrap react-bootstrap
13) generate random images - https://awik.io/generate-random-images-unsplash-without-using-api/
14) download mongodb db tools and paste it in C drive - https://www.mongodb.com/try/download/database-tools
15) Signup in MOngo DB atlas which is same as mongo db compass but we can use it cloud service - https://www.mongodb.com/cloud/atlas/register
16) create json files to import data in mongo db
17) Download "MongoDB Command Line Database Tools Download" and extract it in c/program files dir
18) run "mongoimport" as Administrator
19) run command below to import data
- mearn7030 is DB password
- food_items is collection where to data import
- jsonArray is file type
- C:\Users\HP\Desktop\foodData2.json is file path

mongoimport --uri mongodb+srv://gofood:mearn7030@cluster0.mpv1sbz.mongodb.net/gofoodmearn --collection food_items --jsonArray --file "C:\xampp\htdocs\gofood\mearnapp\foodcategory.json"

20)Mongo DB atlas login

Username:np.phpdeveloper@gmail.com
Pass: mearn7030

21) Create backend directory in application
22) run "npm init" command to create a package.json file for your application.
23) npm install express nodemon mongoose - install node modules for backend

24) install express validator - https://express-validator.github.io/docs/


The app.use() function is used to mount the specified middleware function(s) at the path which is being specified. It is mostly used to set up middleware for your application. 
- MongoDB is schemaless and mongoose is use schema 


25 If we face any CORS error during frontend form submission please add below code in express js index.js file.

before router

appdata.use(function (req, res, next) {
  res.setHeader('Access-Control-Allow-Origin', 'http://localhost:3000');
  res.setHeader('Access-Control-Allow-Methods', 'POST');
  res.setHeader('Access-Control-Allow-Headers', 'X-Requested-With,content-type');
  next();
});

26) In backend, Install bcrypt (https://www.npmjs.com/package/bcrypt) and Jwswebtokens (https://www.npmjs.com/package/jsonwebtoken)
