# Fast Food Delivery Web Application 🍔 🛵

# Tech Stack

### Frontend
- [React Js](https://reactjs.org/)
- [React Router](https://reactrouter.com/)
- [Redux Toolkit](https://redux-toolkit.js.org/introduction/getting-started)
- [React Bootstrap](https://react-bootstrap.github.io/)
- [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)
- [Paystack Api](https://paystack.com/) to handle payments

### Backend
- [Multer](https://www.npmjs.com/package/multer) and [Cloudinary](https://cloudinary.com/) for file uploads.
- [Mongodb](https://www.mongodb.com/) with [Mongoose](https://mongoosejs.com/)
- [Express Js](https://expressjs.com/)
- [Jest Js](https://jestjs.io/)
- [Yarn](https://yarnpkg.com/)
- [Json Web Token](https://jwt.io/)

## Installation Process
```
git clone https://github.com/zanderdg/fooddeliveryweb.git
cd fooddeliveryweb
```
install backend server dependencies
```
yarn install
yarn post-install
```
create a .env file within the root folder, because you will need the following details to start the backend server.
```
PORT
JWT_TOKEN_KEY
CLOUDINARY_NAME
CLOUDINARY_API_KEY
CLOUDINARY_API_SECRET
MONGO_URI
```
start the backend server on your chosen port number
```
yarn start
```
open another terminal, cd into the frontend folder and install frontend dependencies
```
cd frontend
yarn install
```
start the frontend
```
yarn start
```

Happy Coding!!!!
