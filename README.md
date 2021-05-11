# TravelYaari-Api
the backend of TravelYaari Created using ExpressJs, NodeJs, and NoSql Database MongoDB (connect to MongoDB Atlas) 
The FrontEnd part of the project is avaialable at [https://github.com/shsarv/TravelYaari-react](https://github.com/shsarv/TravelYaari-react).

To run this API, do the following:
create .env with the following code (update credentials). Make sure to create .env in the root of the project,

    MONGODB_URI="mongodb+srv://<username>:<password>@<clustername>.wf7c8.mongodb.net/<database name>?retryWrites=true&w=majority"
    PORT=5000
    JWT_SECRET=<Your jwt Secret key>
    BRAINTREE_MERCHANT_ID=<Your braintreemerchant id>
    BRAINTREE_PUBLIC_KEY=<Your braintree account public key>
    BRAINTREE_PRIVATE_KEY=<Your braintree account private key>

Then run the following commands to start up the api.

    cd AwareWeGo-Api
    npm install
    npm start
    
