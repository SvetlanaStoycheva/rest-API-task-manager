## Task-manager REST API

#### using Node.js, Express, MongoDB, Atlas, Mongoose

- (John Smilga tutorial) [https://www.youtube.com/watch?v=jIsj0upCBAM&t=43s]
- install all the packages: npm install; start nodemon with: npm start
- in app.js we setup the most basic express server. It is going to be listening for one route and is going to be on port 3000.
- testing our routes with Postman
- we are building a server, so we want to create HTTP interface, so that other front-end apps can interact with our data. REST stands for representational state transfer. It is the most popular API design pattern. It is a pattern that combines HTTP verbs (get, post etc), route paths and our resources aka our data. REST determents how the API looks like.
  Since JSON is a common format for receiving and sending data in REST API we will use that approach as well.
- we use MongoDB database. No SQL, non relational DB.We can store everything as JSON and it does not matter how the data relate to each other. Group of items is a collection, a single item is a document. A document is a set of key/value pairs. We are using the cloud option. We are using MongoBD Atlas as a free cloud hosting.
- Implement CRUD (Create, read, update and delete) in our REST API
- Using Mongoose, object data modelling mongodb library. Simple validations in mongoose.
