# bearer-auth
[Heroku](https://alfredo-bearer-auth.herokuapp.com/)

## Deployment
Your server must be deployed at Heroku.
If it requires a database, provision it.
For APIs, your endpoints should all be testable remotely using an HTTP REST client.
For Web Servers, your website must be reachable.

## Testing
Write a complete set of tests for all data models, independent of the server
Use an in-memory SQL dialect to test your Postgres Models.
For testing the server and routes, make sure you initialize the database before your tests run.
What we’re testing is not whether express works, but whether your routes are doing the correct things.
Your tests must be running green on Github Actions.
[TESTS](./__tests__)

## Documentation
![](Images/Lab-07-1.png)
![](Images/Lab-07-2.png)

## Routing
Run "npm test" in the terminal to test routes. You can also test these routes in thunder client:
/signup
/signin
/users
/secret
