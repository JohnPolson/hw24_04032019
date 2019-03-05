1. What is responsible for defining the routes of the games resource?
- ../helpers/create_router.js called in the server.js file.

2. What are the the responsibilities of server.js?
- define the "public" path.
- parse the json.
- connect to mongoDB.
- listen for connection.

3. What process does the the client (front-end) use to communicate with the server?
- MongoClient.connect

4. What optional second argument does the fetch method take? And what is it used for in this application? Hint: See Using Fetch on the MDN docs.
- 

5. Which of the games API routes does the front-end application consume (i.e. make requests to)?
-

6. Why do we need to use ObjectId from the MongoDB driver?
- to create a searchable id object.

7. What are we using the MongoDB Driver for?
- To handle callbacks & promises.
