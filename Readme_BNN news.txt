# BNN News
BNN News is a private and nonprofit web application which is responsible for gathering and broadcasting news and current affairs. 
It assist the users as well as public to see the news and explore what’s going on in the world. This web application is used for broadcasting the news on the spot after the incident took place which helps the public save their time and get updated quickly. 
Public can also be part of this application and include their thoughts, views and ideas about the news as a comment based on the news they are interested in.
Also, the BNN News provides horoscope feature for the people who believe it can predict future events and a medium to get rid of any kind of mishap and planetary positions.



## Pre-requisites
All the dependencies is under package.json file. To install all dependencies you must install Node.js' and 'npm.

[Node.js installation](https://nodejs.org/en/) provides a practical guide for installation of Node.js.

[npm installation](https://docs.npmjs.com/cli/install) provides a practical guide for installation of npm.

Once Node.js and npm is installed, clone this repository and inside the cloned folder type this:
npm install package.json



## API usage

 * @api {get} api/news/:_id Get Single News
 * @title
 * @news
 
 * @apiParam {Number} id User's unique ID.
 
 * @apiSuccess {String} firstname Firstname of the User.
 * @apiSuccess {String} lastname  Lastname of the User.



## HTTP requests
All API requests are made by sending a secure HTTPS request using one of the following methods, depending on the action being taken:

* [POST] Create a resource
* [PUT] Update a resource
* [GET] Get a resource or list of resources
* [DELETE] Delete a resource



## HTTP response
Each response will include a status object and (if successful) a result (result will be an object for single-record queries and an array for list queries). The status object contains an HTTP status_code, text, description, error_code (if an error occurred - see Error Codes) about the result. The result contains the result of a successful request. 

## HTTP response code
Each response will be returned with one of the following HTTP status codes:

* 200 OK The request was successful
* 400 Bad Request There was a problem with the request (security, malformed, data validation, etc.)
* 401 Unauthorized The supplied API credentials are invalid
* 404 Not found An attempt was made to access a resource that does not exist in the API