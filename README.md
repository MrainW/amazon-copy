# MERN AMAZONA

## Technical stacks

- Frontend: react, react-bootstrap, react-paypal, node.js
- Backend: express, mongoose, bcryptjs, node.js

## MongoDB & paypal setting

JWT_SECRET=somethingsecret
mongodb://localhost/amazona
PAYPAL_CLIENT_ID=(https://developer.paypal.com/home)
MONGODB_URI=(https://cloud.mongodb.com/)

## Create Node.js Server

1. run npm init in root folder
2. update package.json set type: module
3. add .js to imports
4. npm install express
5. create server.js
6. add start command as node backend/server.js
7. require express
8. create route for /api/products
9. return products
10. run npm start

Two important tips:

- nodemon
- ``can accept variable

## Fetch products from backend

1. set proxy in package.json
2. npm install axios (fetch data from backend)
3. use state hook
4. use effect hook
5. use reducer hook

## Manage state by reducer hook

1. define reducer
2. update fetch data
3. get state from usReducer

## Add bootstrap UI Framework

1. npm install react-bootstrap bootstrap
2. update App.js

## Create Product and Rating Component

1. create Rating component
2. Create Product component
3. Use Rating component in Product component

## Create Product Details Screen

1. fetch product from backend
2. create 3 columns for image, info and action

tips:

- helmet -> change page title

## Create Loading and Message Component

1. create loading component
2. use spinner component
3. craete message component
4. create utils.js to define getError fuction

## Create React Context For Add Item To Cart

1. Create React Context
2. define reducer
3. create store provider
4. implement add to cart button click handler

## Complete Add To Cart

1. check exist item in the cart
2. check count in stock in backend

## Create Cart Screen

1. create 2 columns
2. display items list
3. create action column

## Complete Cart Screen

1. click handler for inc/dec item
2. click handler for remove item
3. click handler for checkout

## Create Signin Screen

1. create sign in form
2. add email and password
3. add signin button

## Connect To MongoDB Database

1. create atlas monogodb database //cloud server
2. install local mongodb database
3. npm install mongoose
4. connect to mongodb database

Tips:
dotenv and mongoose help connect the mongobd
mongodb compass visilize the db

## Seed Sample Products

1. create Product model
2. create seed route
3. use route in server.js
4. seed sample product

## Seed Sample Users

1. create user model
2. seed sample users

bcrypt.hashSync('password')//encrypt

## Create Signin Backend API

1. create signin api
2. npm install jsonwebtoken
3. define generateToken

Advanced REST client// like postman

## Complete Signin Screen

1. handle submit action
2. save token in store and local storage
3. show user name in header

## Create Shipping Screen

1. create form inputs
2. handle save shipping address
3. add checkout wizard bar

## Create Sign Up Screen

1. create input forms
2. handle submit
3. create backend api

## Implement Select Payment Method Screen

1. create input forms
2. handle submit

## Create Place Order Screen

1. show cart items, payment and address
2. create order create api

## Implement Place Order Action

1. handle place order action
2. create order create api

## Create Order Screen

1. create backend api for order/:id
2. fetch order api in frontend
3. show order information in 2 cloumns

## Pay Order By PayPal

1. generate paypal client id
2. create api to return client id
3. install react-paypal-js
4. use PayPalScriptProvider in index.js
5. use usePayPalScriptReducer in Order Screen
6. implement loadPaypalScript function
7. render paypal button
8. implement onApprove payment function
9. create pay order api in backend

Tips:
@paypal/react-paypal-js for pay

## Display Order History

1. create order screen
2. create order history api
3. use api in the frontend

## Create Profile Screen

1. get user info from context
2. show user information
3. create user update api
4. update user info

## Publish To Heroku

1. create and config node project
2. serve build folder in frontend folder
3. Create heroku account
4. connect it to github
5. Create mongodb atlas database
6. Set database connection in heroku env variables
7. Commit and push
