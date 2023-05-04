# E-Commerce Responsive Design Playground
> Built using the MERN Stack & Redux

## Features
- Full-featured shopping cart
- Product reviews & ratings
- Top products carousel
- Product pagination
- Product search feature
- User profile (w/ orders)
- Admin product management
- Admin user management
- Admin order details page
- Mark orders as delivered option
- Checkout process (shipping, payment method, etc.)
- PayPal/CC Integration
- Database seeder (products & users)

## Usage
- Create a MongoDB database
- Create PayPal account (developer)

### Env Variables
Rename .env.example file to .env and add:
```
NODE_ENV = development
PORT = 5000
MONGO_URI = MongoDB URI
JWT_SECRET = 'cms1307'
PAYPAL_CLIENT_ID = PayPal ID
PAGINATION_LIMIT = 8
```
JWT_SECRET & PAGINATION_LIMIT can be changed to user defined values

### NPM Packages
- [Express](https://www.npmjs.com/package/express)]
- [Express Async Handler](https://www.npmjs.com/package/express-async-handler)
- [BCrypt](https://www.npmjs.com/package/bcryptjs)
- [DotEnv](https://www.npmjs.com/package/dotenv)
- [Mongoose](https://www.npmjs.com/package/mongoose)
- [Colors](https://www.npmjs.com/package/colors)
- [JWT](https://www.npmjs.com/package/jsonwebtoken)
- [Morgan](https://www.npmjs.com/package/morgan)
- [Multer](https://www.npmjs.com/package/multer)
- [Concurrently](https://www.npmjs.com/package/concurrently)
- [Nodemon](https://www.npmjs.com/package/nodemon)
- [React BootStrap](https://www.npmjs.com/package/react-bootstrap)
- [React Router Dom](https://www.npmjs.com/package/react-router-dom)
- [Redux](https://www.npmjs.com/package/redux)
- [React Redux](https://www.npmjs.com/package/react-redux)
- [Redux Thunk](https://www.npmjs.com/package/redux-thunk)\
- [Redux Devtools](https://www.npmjs.com/package/redux-devtools-extension)
- [React PayPal](https://www.npmjs.com/package/react-paypal-button-v2)
- [React Helmet](https://www.npmjs.com/package/react-helmet)
- [Axios](https://www.npmjs.com/package/axios)