# TwitterApp
Assignment_5467 , Twitter app with CRUD operations enabled using mongoDb and Express JS

Steps to run this project
Step 1.
- Clone this repo on your local system using following url :~
```js
  https://github.com/jchy/TwitterApp.git
```
Step 2.
- Now navigate inside the < TwitterApp > folder 

Step 3.
- Now run the following command
```js
  npm install
```

Step 4.
- Now in your terminal ( preferably VS Code Terminal ) run the following command :~
```js
  npm run start
```
Step 5.
- Now go to postmane and make a GET request at the following URL to get all users with their data :~
```js
  http://localhost:5001/users
```

Step 6.
- To get a specific user make a GET request at the following url :~
```js
  http://localhost:5001/users/code/pw_009
```

Step 7.
- To make a PATCH request got to follwoing usr :~
```js
  http://localhost:5001/users/< user_id >
```

Step 8.
- To delete a user make a delete request at the following url with user_id :~
```js
  http://localhost:5001/users/ < user_id >
```
Step 9. 
- To get all the tweets make a get request on the following URL :
```js
  http://localhost:5001/tweets
```
NOTE :  Rest all CRUD operations are same as the above just replace < http://localhost:5001/users > with < http://localhost:5001/tweets url >
