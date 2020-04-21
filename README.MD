# Build Microservice using Node.js with Express

## About
A Node.js microservice which determines the distance for specific zip codes.

## Framework, tools, and repository
Node.js; Express; Reuest; VSCode; Git; GitHub

## Install Node.js and npm
`standard operation` 

## Install Express, Request packages and initial the project
`$ npm install express request --save`

`$ npm init`

## Processes in the code include
Creating a Server to Accept Requests; Defining the Routes; Adding Controller Logic

## Making the External Call
The call to a third-party API. We'll use the distance API provided by ZipCodeAPI.com. You need an API key to use this, and it is free if you register. You can also use the key from this example if you want to test your service in error condition because this key frequently expires during the day.

## Execution
npm install -g nodemon

npm install

npm start


## Live API
https://www.zipcodeapi.com/API

## Open your browser to view
http://localhost:3000/about

http://localhost:3000/distance/11003/10017

The result should be as follows if the API key is not expired, if expired, re-created a new API key via the link above
{"name":"microservicewithnodeexpress","version":"1.0.0"}

{"distance":14.397}

