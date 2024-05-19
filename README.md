# Sprint 7 project
The Sprint 7 Project focuses on testing the Urban Grocers API by creating and executing tests for GET, POST, PUT, and DELETE requests. The objective is to ensure that the API endpoints function correctly and return the expected results. The project involves writing tests to validate the response status codes and the content of the response bodies for various API requests.
This project involves writing and running tests for the Urban Grocers API using Jest. By completing the tasks for GET, POST, PUT, and DELETE requests, we ensure that the API endpoints function correctly and return the expected results. The use of Git and GitHub allows for effective version control and collaboration throughout the project.

Technologies and Techniques Used
Node.js: JavaScript runtime used for running the test scripts.
Jest: JavaScript testing framework used for writing and running the tests.
fetch: A function used to make HTTP requests to the API endpoints.
Git and GitHub: Version control system and platform used for managing the project repository.
TripleTen: Platform used for linking GitHub accounts,starting the Server and creating the project repository.
apiDoc: Tool used for generating API documentation and checking the endpoints.

Setting Up the Project
Link GitHub Account to TripleTen: This will automatically create a repository named hm07-qa-us.
Clone the Repository: Clone the repository to your local machine (git clone https://github.com/<your-github-username>/hm07-qa-us.git).
Navigate to the Project Directory: Open the project folder on your computer type: cd hm07-qa-us.
Start the Server: Use the "start server" button on the TripleTen platform to get your server URL.
Check API Endpoints: Use the apiDoc: URL /docs/ to view and verify the API endpoints.

Variable Naming
camelCase: Variables in the project are named using camelCase. This convention is used for readability and consistency.
Example: actualResponseBody, responseStatus.

Variable Declarations: let vs const
const: Used for variables that should not be reassigned. It ensures the value remains constant throughout the code.
Example: const config = require('../config');

let: Used for variables that may be reassigned. It provides more flexibility in changing the value.
Example: let actualResponseBody;


Task 1: Tests for GET Requests: For the GET requests, select an endpoint from the Urban Grocers documentation.Check the response status code:
Ensure the API returns a status code of 200 (OK).
Parse the response and check the response body contains the expected data:
Verify that the response body contains the expected data.

Task 2: Tests for POST Requests:For the POST requests, choose an endpoint from the Urban Grocers documentation.Check the response status code:
Ensure the API returns a status code of 201 (Created).
Parse the response and check the response body contains the expected data:
Verify that the response body contains the data that was sent in the request.

Task 3: Tests for PUT Requests:For the PUT requests, choose an endpoint from the Urban Grocers documentation.Check the response status code:
Ensure the API returns a status code of 200 (OK).
Parse the response and check the response body contains the expected data:
Verify that the response body contains the updated data.

Task 4: Tests for DELETE Requests:For the DELETE requests, choose an endpoint from the Urban Grocers documentation.Check the response status code:
Ensure the API returns a status code of 200 (OK).
Parse the response and check the response body contains the expected data:
Verify that the response body is empty or contains a message indicating successful deletion.

Running the Tests
To run the tests, we have to follow these steps:

Install Dependencies:
npm install

Run the Tests:
Execute the tests using Jest:
npx jest for all the tests, or npx jest test/nameofthetestHandlers.test.js for single test to run.

Committing Changes to the Project: 
If the repository is not already initialized, run: git init
Add all new and modified files: git add -A
Commit the changes with a meaningful message:git commit -m "Add Sanja"
Push the changes to the main branch of the remote repository:git push -u origin main



