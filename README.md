User Registration and User Details Fetch API
This project implements a RESTful API using Spring Boot for user registration and fetching user details.

//API Endpoints

/api/user/register [POST]: Endpoint to register new users.
/api/user/fetch [GET]: Endpoint to fetch user details by username.


Requirements
/api/user/register
POST api
Implement an endpoint to register new users.
Accepts a JSON request body containing the user's details (username, email, password).
Stores the user's information securely in the database or any storage mechanism.
Returns appropriate responses to indicate success or failure of the registration process.

/api/user/fetch

GET api
Implement an endpoint to fetch user details.
Accepts a query parameter username.
Retrieves the user's information securely from the database or any storage mechanism.
Returns appropriate responses to indicate success or failure of the user fetch process.

Implementation Details

Developed using Spring Boot framework.
Implements proper exception handling and security best practices to protect user data.
