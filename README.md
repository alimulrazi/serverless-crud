# serverless-crud
Building an API in Node.js using AWS λ, API Gateway, and Serverless

### Prerequisites
Prerequisite
To go through this tutorial you will need following:

1. AWS account
2. Node.js
3. AWS CLI and configure it

### Installation

2. Clone the repo
   ```sh
   git clone git@github.com:alimulrazi/serverless-crud.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your MongoDB credential in `.env`
   ```js
   DB = 'ENTER YOUR USERNAME AND PASSWORD';
   ```
5. Run Serverless offline to test local machine
   ```sh
   serverless offline start
   ```
6. Deploy Serverless on AWS
   ```sh
   serverless deploy
   ```   
### Reference URL

* [Medium](https://medium.com/tech-at-nordstrom/building-a-rest-api-in-node-js-using-aws-services-mongodb-and-serverless-framework-9e0530baaa3f)
* [Serverless Offline](https://fauna.com/blog/develop-using-serverless-offline)
* [Serverless CRUD](https://www.serverless.com/blog/node-rest-api-with-serverless-lambda-and-dynamodb)
