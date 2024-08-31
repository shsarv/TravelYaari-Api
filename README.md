# TravelYaari-Api
the backend of TravelYaari Created using ExpressJs, NodeJs, and NoSql Database MongoDB (connect to MongoDB Atlas) 
The FrontEnd part of the project is avaialable at [https://github.com/shsarv/TravelYaari-react](https://github.com/shsarv/TravelYaari-react).

To run this API, do the following:
create .env with the following code (update credentials). Make sure to create .env in the root of the project,

<code>
    DATABASE="mongodb+srv://<username>:<password>@<clustername>.wf7c8.mongodb.net/<database name>?retryWrites=true&w=majority"
    PORT=5000
    JWT_SECRET=Your_jwt_Secret_key
    BRAINTREE_MERCHANT_ID=Your_braintreemerchant_id
    BRAINTREE_PUBLIC_KEY=Your_braintree_account_public_key
    BRAINTREE_PRIVATE_KEY=Your_braintree_account_private_key
</code>

## How to Create Credentials 

### For Database

1. Goto Mongodb and create an Account [https://www.mongodb.com/products/platform/cloud](https://www.mongodb.com/products/platform/cloud).

2. Create a new Project named **"TravelYaari"**.
3. Create a new Cluster (M0 Free Version for testing/development) under TravelYaari Project and click on deploy cluster.
4. Fill/copy the required credentials and click on create user.
5. click on choose a connection method.
6. you will get multiple option to connect to database. you can use any as you like.
7. if you dant want to do much, click on drivers>> select driver (Nodejs) >> copy the connection string and paste it into the .env file in front of Database = __________.

### For Braintree Details

* **Folow this website for detailed process.[https://developer.paypal.com/braintree/docs/guides/drop-in/overview/javascript/v3/](https://developer.paypal.com/braintree/docs/guides/drop-in/overview/javascript/v3/) or 
1. create a paypal account on paypal developer sandbox >> goto App and credentials and create a new app.
2. copy the credentials .
3. goto [https://sandbox.braintreegateway.com/login](https://sandbox.braintreegateway.com/login) and create an account.
4. Generate new API Key and copy credentials to .env files.


### For JWT_Secret

1. use some random Character (just for fun, not recommended in-case of Production)

Then run the following commands to start up the api.

<code>
    cd AwareWeGo-Api
    npm install
    npm start

</code>

**PS-** Order.js folder has sendgrid email service option which one can do using  sendgrid for email npm i @sendgrid/mail and generatinf credentials.
    
