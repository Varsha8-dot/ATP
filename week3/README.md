# this it a basic back end application 
###
1.generate package.json
###
2.create express server
###
3.install mongoose and connect to mongodb server
###
    REST API - mongodb native driver -> db server
    REST API -mongoose ODM driver -> db server
###
# pure-backend
mongodb connection and express server   
### How to run the application
1. Install dependencies: `npm install`
2. Start the server: `node server.js`
3. The server will be running on `http://localhost:4000`
4. Use an API client like Postman to interact with the API endpoints.
5. To stop the server, press `Ctrl + C` in the terminal.

### API Endpoints
- `GET /api/items`: Retrieve all items
- `POST /api/items`: Create a new item
- `GET /api/items/:id`: Retrieve a specific item by ID
- `PUT /api/items/:id`: Update a specific item by ID
- `DELETE /api/items/:id`: Delete a specific item by ID
### Technologies Used
- Node.js
- Express.js
- MongoDB
- Mongoose


4.Build USER REST api

         -Create user
         -read all user by id
         -read a user by id
         -update a user by id
         -delete a uesr by id


  



### status code
 |code|name|
 |---|---|
|`200`|sucess|
|`201`|created|
|`400`|bad request|
|`401`|unauthorize|
|`404`|not found|
|`500`|server error|


# techniques to learn
- handliing unavailable resources
- validators during update
- hashing password
- unique fields
- refined version of error handling middleware

