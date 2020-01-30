# Oauth2

Oauth2 simple implementation for php pure 

## Getting Started

These instructions will guide you to implement Oauth2 for PHP PURE for quick setup

1. Create mysql database and name it "oauth2"
2. Import file from db/oauth2.sql in the database
3. Excute insert query to add api user "INSERT INTO oauth_clients (client_id, client_secret, redirect_uri) VALUES ("testclient", "testpass", "http://fake/");"
4. Use this user "testclient" with password "testpass" to get token via getAccessToken endpoint

## Running the tests

1. Import collection into postman from postman/Oauth2.postman_collection.json folder, also don't forget to change host url and client_id and client secret.
2. getAccessToken endpoint to get new access token
3. Use Example Request (endpoint) in postman collection To test oauth2
4. You can change access token granted in header (Authorization Bearer) every time you get new access token
5. Access token will be expired after one hour
6. Done

## Built With

* PHP (Pure) 

## Authors

* bshaffer https://bshaffer.github.io/oauth2-server-php-docs/cookbook/


