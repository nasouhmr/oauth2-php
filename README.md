# Oauth2

Oauth2 simple implementation for php pure 

## Getting Started

These instructions will guide you to implement Oauth2 for PHP PURE for quick setup

1. Create DB
2. Import file from db/oauth2.sql in db
3. Insert test api user "INSERT INTO oauth_clients (client_id, client_secret, redirect_uri) VALUES ("testclient", "testpass", "http://fake/");"
4. Use this user "testclient" with password "testpass" to get token  

## Running the tests

1. Import collection into postman from postman/Oauth2.postman_collection.json folder, also don't forgot to change host url and client_id and client secret.
2. getAccessToken endpoint to get new access token
3. Use Example Request (endpoint) in postman collection To test oauth2
4. You change access token granted in header (Authorization Bearer)
5. token will expire after one hour
6. Done

## Built With

* PHP (Pure) 

## Authors

* bshaffer https://bshaffer.github.io/oauth2-server-php-docs/cookbook/


