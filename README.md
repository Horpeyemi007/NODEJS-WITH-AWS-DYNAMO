## BUILDING A REST API WITH NODE JS AND AWS DYNAMO DB

- ### Using AWS Dynamo DB to store student record and creating a RestApi with nodeJS to for connection.
- ### The RestApi connects to AWS using the npm "aws-sdk" library.

#### Steps:
- Create an AWS DynamoDB table with the following parameter
  1. email
  2. id
  3. firstname
  4. lastname
  5. grade
  6. subject

- Clone the source code
- Create a "*.env*" in the working directory to store your aws credentials.

```
PORT=3000
AWS_DEFAULT_REGION="Enter here"
AWS_ACCESS_KEY_ID="Enter here"
AWS_SECRET_ACCESS_KEY="Enter here"
NODE_ENV=development
DYNAMO_TABLE_NAME="Enter here"
```

Open Postman and send the following request
 ```
  POST request to /api/v1/records/student
  GET request to /api/v1/records/student
  GET request to /api/v1/records/student/email
  PUT request to /api/v1/records/student/email
  DELETE request to /api/v1/records/student/email
 ```

 #### Thanks🙂
