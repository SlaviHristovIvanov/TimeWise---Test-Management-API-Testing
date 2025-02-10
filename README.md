# TimeWise---Test-Management-API-Testing
 This repository contains test management cases and API test collections for the TimeWise project.
The Test-Management-and-Bug-Tracker-Template.xls file contains structured test cases for the TimeWise application, including:

Test Case ID

Test Description

Steps to Reproduce

Expected Result

Actual Result

Bug Status

*** How to Use: ***

Open the .xls file using Microsoft Excel or Google Sheets.

Log test cases and update results as needed.

Track bug reports efficiently.

API Testing with Postman

The TimeWise.postman_collection.json file includes API test cases for:

User Authorization (/api/User/Authorization)

Task Creation (/api/Task/Create)

View All Tasks (/api/Task/AllTasks)

Edit a Task (/api/Task/Edit/{taskId})

Delete a Task (/api/Task/Delete/{taskId})

*** How to Use Postman Collection: ***

Import the Collection:

Open Postman.

Click File > Import and select TimeWise.postman_collection.json.

Set Up Environment Variables:

Ensure authentication tokens are updated in the request headers.

Run API Tests:

Use Send to test each endpoint.

View responses and debug issues.
